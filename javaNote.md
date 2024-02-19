javaSE是桌面应用开发，其他两个版本的基础。CandC++比Java更有桌面开发的优势。javaSE是javaEE基础。

javaME 移动设备主要使用

javaEE web  浏览器+服务器就是java的战场。java,go可以承载巨大的访问量。

编译型语言 整体翻译。Java,c都会产生一个整体翻译后的新文件。
解释型语言 一行一行翻译。Python不会产生新文件

Java的跨平台实际上是通过虚拟机完成的。这个虚拟机是Java为我们提供了现成的。

JDK：开发代码需要的东西：JVM（虚拟机）核心类库，比如System，Java帮我们写好的库。开发工具。
javac 编译工具
java 运行工具
jdb 调试工具
jhat 内存分析工具

JRE:JVM+核心类库+运行工具

JDK包含JRE。JRE包含JVM


Project: MISUMI EC Site https://jp.misumi-ec.com/
从几十年前的 php 版本切换到 Next/React 版，追加各种新功能，各国/移动端对应等等
基本上分为商品选定导线（主要是 ssr 页面展示商品信息）和注文导线（主要 csr 页面，登録/見積/注文/カートなど）

Tech Stack: Next.js/Vercel/Typescript (React/Redux/styled-components/css-modules/React Hook Form)


面试问题

1. 自己紹介
2. 根据项目经验提问（我被问到的和这个项目相关的有 i18n 和性能优化）
3. React/Vue/Nextの評判
4. Github package経験
5. リクエストライブラリが何を使ってます
6. 注目してる技術
7. Agile/Scrum経験（経験あればSprint周期どれくらい）
8. Redux経験、理解
9. CSS Module と styled-component
10. （英語で説明）Next.js’s Server Side vs. Client Side Component
11. よく使ってるReact Hooks、useMemo/useEffect区別
12. よいソースコートはなんですか
13. 品質の良いシステムはなんですか

class就相当于人的细胞。
关键字都是小写。

1. 整数 
2. 小数
3. 字符串 "abc","",
4. 字符 'a','我','0'
5. 布尔值
6. 空 null,null是不能被直接打印的，我们如果想要打印null必须要以"null"形式，这个其实还是字符串

```java
public class HelloWorld{
    public static void main(String[] args){
        System.out.println("abc"+'\t')//"\t"也可以，会把整个字符串补充到8的倍数。abc是3，那么此时\t是5.我们可以利用制表符，来对其我们的打印s。可以让我们的字符串类似表格一样对齐，所以叫制表符。制表符只和他前面的字符串有关系。
    }
}
```

int 整数
double 小数
int n=5;//不同于TS，没有const let var这种。
int a=1,b=2,c=3;
