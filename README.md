# Hello, Security!

- **按漏洞类型划分**
  - XSS
    - [前端安全系列（一）：如何防止XSS攻击？](https://tech.meituan.com/2018/09/27/fe-security.html)
    - [浅谈React框架的XSS及后利用](https://mp.weixin.qq.com/s/1AU2TEePckzSWpHyuEGGJQ)
    - [DOM-based XSS 与存储性 XSS、反射型 XSS 有什么区别？](https://www.zhihu.com/question/26628342)
    - [深入理解浏览器解析机制和XSS向量编码](http://bobao.360.cn/learning/detail/292.html)
    - [SVG XSS的一个黑魔法](https://www.hackersb.cn/hacker/85.html)
    - [无需括号与分号的XSS](https://www.anquanke.com/post/id/178610)
    - [使用 Dom Clobbering 扩展 XSS](https://xz.aliyun.com/t/7329)
    - [XSS Game分析以及知识点总结](https://www.freebuf.com/articles/web/245209.html)
    - [XSS靶场](http://prompt.ml/4)
    - [Cross-site scripting (XSS) cheat sheet](https://portswigger.net/web-security/cross-site-scripting/cheat-sheet)
    - [AwesomeXSS](https://github.com/s0md3v/AwesomeXSS)
    - 绕过方法
      - JSFuck
        - [无需括号与分号的XSS](https://www.anquanke.com/post/id/178610)
        - [JSFuck](http://www.jsfuck.com/)
  - CRLF
    - [新浪某站CRLF Injection导致的安全问题](https://www.leavesongs.com/PENETRATION/Sina-CRLF-Injection.html)
  - CSRF
    - [前端安全系列（二）：如何防止CSRF攻击？](https://tech.meituan.com/2018/10/11/fe-security-csrf.html)
    - [CSRF攻击技术浅析](https://xz.aliyun.com/t/8186)
  - SSRF
    - [SSRF安全指北](https://security.tencent.com/index.php/blog/msg/179)
    - [A New Era of SSRF - Exploiting URL Parser in Trending Programming Languages!](https://www.blackhat.com/docs/us-17/thursday/us-17-Tsai-A-New-Era-Of-SSRF-Exploiting-URL-Parser-In-Trending-Programming-Languages.pdf)
    - [SSRF bible. Cheatsheet](https://docs.google.com/document/d/1v1TkWZtrhzRLy0bYXBcdLUedXGb9njTNIJXa3u9akHM/edit#)
    - [SSRF绕过方法总结](http://byd.dropsec.xyz/2017/11/21/SSRF%E7%BB%95%E8%BF%87%E6%96%B9%E6%B3%95%E6%80%BB%E7%BB%93/)
    - DNS Rebinding
      - [从0到1认识DNS重绑定攻击](https://xz.aliyun.com/t/7495)
  - SQL注入
    - [SQL注入绕过技巧](http://byd.dropsec.xyz/2016/08/01/SQL-Injection%E7%BB%95%E8%BF%87%E6%8A%80%E5%B7%A7/)
    - 宽字节注入
      - [浅析白盒审计中的字符编码及SQL注入](https://www.leavesongs.com/PENETRATION/mutibyte-sql-inject.html)
    - [PostgreSQL Injection](https://evi1cg.me/archives/PostgreSQL-Injection.html)
    - [SQL Injection Lab](https://tryhackme.com/room/sqlilab)
  - 点击劫持
    - [Clickjacking](https://www.imperva.com/learn/application-security/clickjacking/)
  - 标签页劫持（Tabnabbing）
    - [钓鱼攻击之Reverse Tabnabbing](https://xz.aliyun.com/t/7080)
  - XXE
    - [DTD 教程](https://www.w3school.com.cn/dtd/index.asp)
    - [XML 教程](https://www.w3school.com.cn/xml/index.asp)
    - [Blind XXE详解与Google CTF一道题分析](https://www.freebuf.com/vuls/207639.html)
  - XPath注入
    - [XPath 教程](https://www.w3school.com.cn/xpath/index.asp)
    - [XPath 注入指北](https://www.tr0y.wang/2019/05/11/XPath%E6%B3%A8%E5%85%A5%E6%8C%87%E5%8C%97/)
  - CORS错误配置
    - [Exploiting CORS misconfigurations for Bitcoins and bounties](https://portswigger.net/research/exploiting-cors-misconfigurations-for-bitcoins-and-bounties#top)
  - DOS
    - ReDos
      - [ReDOS初探](http://www.lmxspace.com/2019/02/16/ReDOS%E5%88%9D%E6%8E%A2/)
      - [ReDOS攻击](https://lingwu111.github.io/ReDOS.html)
      - [在线检测redos](http://redos-checker.surge.sh/)
      - [Regular Expression Denial of Service](https://www.checkmarx.com/wp-content/uploads/2015/03/ReDoS-Attacks.pdf)
    - zip bomb
      - [zip炸弹制作](https://github.com/abdulfatir/ZipBomb)
      - [A better zip bomb](https://zerosun.top/2019/07/07/A-better-zip-bomb/)
      - [The (Decompression) Bomb Site](https://bomb.codes/)
    - SLOW HTTP 
      - [Slowhttptest攻击原理](https://cloud.tencent.com/developer/article/1180216)
    - 缓冲区投毒
      - CPDoS
        - [CPDoS：一种新的Web缓存污染攻击](https://www.anquanke.com/post/id/189507)
        - [cpdos网站](https://cpdos.org/)
        - [Your Cache Has Fallen: Cache-Poisoned Denial-of-Service Attack](https://cpdos.org/paper/Your_Cache_Has_Fallen__Cache_Poisoned_Denial_of_Service_Attack__Preprint_.pdf)
  - Zip Slip
    - [Zip Slip Vulnerability](https://snyk.io/research/zip-slip-vulnerability)
  - blind regex injection
    - [A Rough Idea of Blind Regular Expression Injection Attack](https://diary.shift-js.info/blind-regular-expression-injection/)
    - [Revisiting ReDoS: A Rough Idea of Data Exfiltration by ReDoS and Side-channel Techniques](https://speakerdeck.com/lmt_swallow/revisiting-redos-a-rough-idea-of-data-exfiltration-by-redos-and-side-channel-techniques)
  - 文件上传
    - [简单粗暴的文件上传漏洞](https://paper.seebug.org/560/)
    - [Upload-labs通关手册](https://xz.aliyun.com/t/2435)
    - [文件解析漏洞总结](https://www.smi1e.top/%E6%96%87%E4%BB%B6%E8%A7%A3%E6%9E%90%E6%BC%8F%E6%B4%9E%E6%80%BB%E7%BB%93/)
  - Reflected File Download
    - [Reflected File Download A New Web Attack Vector](https://www.wooyaa.me/download/RFD.pdf)
    - [反射文件下载攻击](https://wooyaa.me/archives/RFD-Attack)
  - HTTP request smuggling
    - H2C Smuggling
      - [h2c Smuggling: Request Smuggling Via HTTP/2 Cleartext (h2c)](https://labs.bishopfox.com/tech-blog/h2c-smuggling-request-smuggling-via-http/2-cleartext-h2c)
      - [h2csmuggler](https://github.com/BishopFox/h2csmuggler)
    - WebSocket Smuggling
      - [Smuggling HTTP requests over fake WebSocket connection](https://github.com/0ang3el/websocket-smuggle)
    - [HTTP Desync Attacks: Request Smuggling Reborn](https://portswigger.net/research/http-desync-attacks-request-smuggling-reborn#top)
    - [协议层的攻击——HTTP请求走私](https://paper.seebug.org/1048/)
    - [一篇文章带你读懂 HTTP Smuggling 攻击](https://xz.aliyun.com/t/6878#toc-16)
    - [HRS自动化测试工具](https://github.com/defparam/smuggler)
  - HTTP参数投毒
    - [A Look at HTTP Parameter Pollution and How To Prevent It](https://securityintelligence.com/posts/how-to-prevent-http-parameter-pollution/) 
    - [HTTP Parameter Pollution Vulnerabilities in Web Applications](https://www.blackhat.com/docs/webcast/bhwebcast28-balduzzi.pdf)
  - TLS 投毒
    - [一篇文章带你读懂 TLS Poison 攻击](https://blog.zeddyu.info/2021/04/20/tls-poison/)
    - [When TLS Hacks You -- BlackHat2020](http://zeroyu.xyz/2020/08/11/When-TLS-Hacks-You-BlackHat2020/)
    - [When TLS Hacks You 科普](https://mp.weixin.qq.com/s/-NABL-xz1Allxr6SKGiYcQ)
  - 条件竞争
    - [Race Condition](https://ctf-wiki.org/pwn/linux/race-condition/introduction/)
  - 业务逻辑漏洞
    - [攻防演练中的业务逻辑漏洞及检测思路](http://blog.nsfocus.net/business-logic-vulnerabilities-1208/)
- **按编程语言划分**
  - JavaScript 
    - 原型污染
      - [深入理解 JavaScript Prototype 污染攻击](https://www.leavesongs.com/PENETRATION/javascript-prototype-pollution-attack.html)
    - [Node.js 常见漏洞学习与总结](https://threezh1.com/2020/01/30/NodeJsVulns/)
  - Java
    - [Java 漏洞分析之远程调试方法总结](https://paper.seebug.org/1316/#weblogicdocker)
    - [从零开始，分析Spring Framework RCE](https://tttang.com/archive/1532/#toc_introspector)
    - [Java框架级SSM代码审计思路](https://www.freebuf.com/vuls/220197.html)
    - [Identity Security Authentication Vulnerability](http://noahblog.360.cn/an-quan-ren-zheng-xiang-guan-lou-dong-wa-jue/)
    - Java 安全机制
      - Java沙箱
        - [浅析Java沙箱逃逸](https://www.mi1k7ea.com/2020/05/03/%E6%B5%85%E6%9E%90Java%E6%B2%99%E7%AE%B1%E9%80%83%E9%80%B8/#Java%E6%B2%99%E7%AE%B1%E7%AE%80%E4%BB%8B)
        - [AccessController.doPrivileged的作用](https://tech101.cn/2019/08/15/AccessController%E7%9A%84doPrivileged%E6%96%B9%E6%B3%95%E7%9A%84%E4%BD%9C%E7%94%A8)
    - XML注入
      - XXE
        - [Java-XXE-总结](http://www.lmxspace.com/2019/10/31/Java-XXE-%E6%80%BB%E7%BB%93/)
        - [探讨XXE防御之setFeature设置](https://www.mi1k7ea.com/2019/06/09/%E6%8E%A2%E8%AE%A8XXE%E9%98%B2%E5%BE%A1%E4%B9%8BsetFeature%E8%AE%BE%E7%BD%AE/) 
    - 表达式注入
      - OGNL注入
        - [OGNL表达式注入漏洞总结](https://www.mi1k7ea.com/2020/03/16/OGNL%E8%A1%A8%E8%BE%BE%E5%BC%8F%E6%B3%A8%E5%85%A5%E6%BC%8F%E6%B4%9E%E6%80%BB%E7%BB%93/#0x03-OGNL%E8%A1%A8%E8%BE%BE%E5%BC%8F%E6%B3%A8%E5%85%A5%E6%BC%8F%E6%B4%9E)
        - [浅析 OGNL 的攻防史](https://paper.seebug.org/794/)
      - Spel表达式注入
        - [SpEL表达式注入漏洞总结](https://www.mi1k7ea.com/2020/01/10/SpEL%E8%A1%A8%E8%BE%BE%E5%BC%8F%E6%B3%A8%E5%85%A5%E6%BC%8F%E6%B4%9E%E6%80%BB%E7%BB%93/)
        - [SPEL 表达式注入漏洞深入分析](https://paper.seebug.org/1694/)
        - [Spring 全家桶各类 RCE 漏洞浅析](https://paper.seebug.org/1422/#spel)
        - [Spring Data Commons Remote Code Execution 分析-【CVE-2018-1273】](https://xz.aliyun.com/t/2269)
        - [CVE-2017-17485: 远程下载bean配置文件导致表达式注入](https://www.cnblogs.com/afanti/p/10203282.html)
      - Groovy
        - [从Jenkins RCE看Groovy代码注入](https://www.mi1k7ea.com/2020/08/26/%E4%BB%8EJenkins-RCE%E7%9C%8BGroovy%E4%BB%A3%E7%A0%81%E6%B3%A8%E5%85%A5/)
      - EL表达式注入
        - [浅析EL表达式注入漏洞](https://xz.aliyun.com/t/7692)
        - [remote code execution with el injection vulnerabilities](https://www.exploit-db.com/docs/english/46303-remote-code-execution-with-el-injection-vulnerabilities.pdf)
      - Jexl
        - [Nexus Repository Manager 3 RCE 分析 -【CVE-2019-7238】](https://xz.aliyun.com/t/4136)
      - JBoss EL表达式注入
        - [nuxeo rce 漏洞复现分析](https://xz.aliyun.com/t/3352)
    - 模板注入
      - [Room for Escape: Scribbling Outside the Lines of Template Security](https://www.blackhat.com/us-20/briefings/schedule/#room-for-escape-scribbling-outside-the-lines-of-template-security-20292)
      - Freemarker 模板注入
        - [Freemarker模板注入 Bypass](https://mp.weixin.qq.com/s/8YIVWtdqCAVPKaLXEZtFkg)
        - [逃逸安全的模板沙箱（一）——FreeMarker（上）](https://paper.seebug.org/1304/)
      - Velocity 模板注入
        - [Apache Solr Velocity 模板注入漏洞深度分析](https://paper.seebug.org/1107/)
        - [TESTING VELOCITY SERVER-SIDE TEMPLATE INJECTION](https://antgarsil.github.io/posts/velocity/)
      - Thymeleaf 模板注入
        - [Exploiting SSTI in Thymeleaf](https://www.acunetix.com/blog/web-security-zone/exploiting-ssti-in-thymeleaf/)
        - [java 安全开发之 spring boot Thymeleaf 模板注入](https://paper.seebug.org/1332/)
        - [Thymeleaf模板注入导致命令执行漏洞分析](https://www.freebuf.com/articles/network/250026.html)
        - [Spring View Manipulation Vulnerability](https://github.com/veracode-research/spring-view-manipulation)
      - Pebble
        - [服务器端模板注入-以Pebble为例](https://research.securitum.com/server-side-template-injection-on-the-example-of-pebble/)
    - 反序列化
      - 原理介绍
        - [反序列化流程分析总结](https://www.cnpanda.net/sec/928.html)
        - [Lib之过？Java反序列化漏洞通用利用分析](https://blog.chaitin.cn/2015-11-11_java_unserialize_rce/)
      - XMLDecoder反序列化
        - [XMLDecoder解析流程分析](https://xz.aliyun.com/t/5069)
      - XStream反序列化
        - [Remote Code Execution with XStream](https://www.baeldung.com/java-xstream-remote-code-execution)
        - [Java XStream反序列化漏洞](https://www.mi1k7ea.com/2019/10/21/XStream%E5%8F%8D%E5%BA%8F%E5%88%97%E5%8C%96%E6%BC%8F%E6%B4%9E/)
      - Yaml反序列化
        - [Java SnakeYaml反序列化漏洞](https://www.mi1k7ea.com/2019/11/29/Java-SnakeYaml%E5%8F%8D%E5%BA%8F%E5%88%97%E5%8C%96%E6%BC%8F%E6%B4%9E/)
        - [SnakeYaml 反序列化的一个小 trick](https://b1ue.cn/archives/407.html)
        - [Java安全之SnakeYaml反序列化分析](https://tttang.com/archive/1591/)
      - Jackson反序列化
        - [Jackson 反序列化汇总](http://www.lmxspace.com/2019/07/30/Jackson-%E5%8F%8D%E5%BA%8F%E5%88%97%E5%8C%96%E6%B1%87%E6%80%BB/)
        - [Jackson系列一——反序列化漏洞基本原理](https://www.mi1k7ea.com/2019/11/13/Jackson%E7%B3%BB%E5%88%97%E4%B8%80%E2%80%94%E2%80%94%E5%8F%8D%E5%BA%8F%E5%88%97%E5%8C%96%E6%BC%8F%E6%B4%9E%E5%9F%BA%E6%9C%AC%E5%8E%9F%E7%90%86/)
        - [Jackson系列二——CVE-2017-7525（基于TemplatesImpl利用链）](https://www.mi1k7ea.com/2019/11/16/Jackson%E7%B3%BB%E5%88%97%E4%BA%8C%E2%80%94%E2%80%94CVE-2017-7525%EF%BC%88%E5%9F%BA%E4%BA%8ETemplatesImpl%E5%88%A9%E7%94%A8%E9%93%BE%EF%BC%89/)
        - [Jackson系列三——CVE-2017-17485（基于ClassPathXmlApplicationContext利用链）](https://www.mi1k7ea.com/2019/11/17/Jackson%E7%B3%BB%E5%88%97%E4%B8%89%E2%80%94CVE-2017-1748%EF%BC%88%E5%9F%BA%E4%BA%8EClassPathXmlApplicationContext%E5%88%A9%E7%94%A8%E9%93%BE%EF%BC%89/)
        - [Jackson系列四——CVE-2019-12086（基于MiniAdmin利用链）](https://www.mi1k7ea.com/2019/11/19/Jackson%E7%B3%BB%E5%88%97%E5%9B%9B%E2%80%94%E2%80%94CVE-2019-12086%EF%BC%88%E5%9F%BA%E4%BA%8EMiniAdmin%E5%88%A9%E7%94%A8%E9%93%BE%EF%BC%89/)
        - [Jackson系列五——CVE-2019-12384（基于logback利用链）](https://www.mi1k7ea.com/2019/11/22/Jackson%E7%B3%BB%E5%88%97%E4%BA%94%E2%80%94%E2%80%94CVE-2019-12384%EF%BC%88%E5%9F%BA%E4%BA%8Elogback%E5%88%A9%E7%94%A8%E9%93%BE%EF%BC%89/)
        - [Jackson系列六——CVE-2019-12814（基于JDOM XSLTransformer利用链）](https://www.mi1k7ea.com/2019/11/24/Jackson%E7%B3%BB%E5%88%97%E5%85%AD%E2%80%94%E2%80%94CVE-2019-12814%EF%BC%88%E5%9F%BA%E4%BA%8EJDOM-XSLTransformer%E5%88%A9%E7%94%A8%E9%93%BE%EF%BC%89/)
        - [Jackson系列七——其他Gadgets与检测防御](https://www.mi1k7ea.com/2019/11/24/Jackson%E7%B3%BB%E5%88%97%E4%B8%83%E2%80%94%E2%80%94%E5%85%B6%E4%BB%96Gadgets/)
      - Fastjson反序列化
        - [Fastjson 流程分析及 RCE 分析](https://paper.seebug.org/994/)
        - [Fastjson 反序列化漏洞史](https://paper.seebug.org/1192/)
        - [Fastjson系列一——反序列化漏洞基本原理](https://www.mi1k7ea.com/2019/11/03/Fastjson%E7%B3%BB%E5%88%97%E4%B8%80%E2%80%94%E2%80%94%E5%8F%8D%E5%BA%8F%E5%88%97%E5%8C%96%E6%BC%8F%E6%B4%9E%E5%9F%BA%E6%9C%AC%E5%8E%9F%E7%90%86/)
        - [Fastjson系列二——1.2.22-1.2.24反序列化漏洞](https://www.mi1k7ea.com/2019/11/07/Fastjson%E7%B3%BB%E5%88%97%E4%BA%8C%E2%80%94%E2%80%941-2-22-1-2-24%E5%8F%8D%E5%BA%8F%E5%88%97%E5%8C%96%E6%BC%8F%E6%B4%9E/)
        - [Fastjson系列三——历史版本补丁绕过（需开启AutoType）](https://www.mi1k7ea.com/2019/11/10/Fastjson%E7%B3%BB%E5%88%97%E4%B8%89%E2%80%94%E2%80%94%E5%8E%86%E5%8F%B2%E7%89%88%E6%9C%AC%E8%A1%A5%E4%B8%81%E7%BB%95%E8%BF%87%EF%BC%88%E9%9C%80%E5%BC%80%E5%90%AFAutoType%EF%BC%89/)
        - [Fastjson系列四——1.2.25-1.2.47反序列化漏洞（无需开启AutoType）](https://www.mi1k7ea.com/2019/11/11/Fastjson%E7%B3%BB%E5%88%97%E5%9B%9B%E2%80%94%E2%80%941-2-25-1-2-47%E5%8F%8D%E5%BA%8F%E5%88%97%E5%8C%96%E6%BC%8F%E6%B4%9E%EF%BC%88%E6%97%A0%E9%9C%80%E5%BC%80%E5%90%AFAutoType%EF%BC%89/)
        - [Fastjson系列五——高版本JDK绕过及检测与防御](https://www.mi1k7ea.com/2019/11/13/Fastjson%E7%B3%BB%E5%88%97%E4%BA%94%E2%80%94%E2%80%94%E9%AB%98%E7%89%88%E6%9C%ACJDK%E7%BB%95%E8%BF%87%E5%8F%8A%E6%A3%80%E6%B5%8B%E4%B8%8E%E9%98%B2%E5%BE%A1/)
        - [FastJson checkAutoType安全机制研究](https://kumamon.fun/FastJson-checkAutoType/)
        - [如何利用 JSON 反序列化 0day 窃取区块链上的金钱](https://i.blackhat.com/USA21/Wednesday-Handouts/US-21-Xing-How-I-Used-a-JSON.pdf)
        - [Blackhat 2021议题详细分析 ——FastJson反序列化漏洞及在区块链应用中的渗透利用](http://noahblog.360.cn/blackhat-2021yi-ti-xiang-xi-fen-xi-fastjsonfan-xu-lie-hua-lou-dong-ji-zai-qu-kuai-lian-ying-yong-zhong-de-shen-tou-li-yong-2/)
      - Mysql JDBC反序列化
        - [MySQL JDBC客户端反序列化漏洞](http://scz.617.cn:8/network/202005262206.txt)
        - [MySQL JDBC反序列化漏洞](https://www.mi1k7ea.com/2021/04/23/MySQL-JDBC%E5%8F%8D%E5%BA%8F%E5%88%97%E5%8C%96%E6%BC%8F%E6%B4%9E/) 
        - [MySQL Fake Server](https://github.com/fnmsd/MySQL_Fake_Server)
    - JDWP
      - [Hacking the Java Debug Wire Protocol – or – “How I met your Java debugger”](https://ioactive.com/hacking-java-debug-wire-protocol-or-how/)
    - JMX
      - [JMX远程代码漏洞研究](https://www.freebuf.com/vuls/231132.html)
    - RMI
      - 大佬的Java RMI利用系列文章
        - [Java RMI入门](http://scz.617.cn:8/network/202002221000.txt)
        - [Java RMI入门(2)](http://scz.617.cn:8/network/202003081810.txt)
        - [Java RMI入门(3)](http://scz.617.cn:8/network/202003121717.txt)
        - [Java RMI入门(4)](http://scz.617.cn:8/network/202003191728.txt)
        - [Java RMI入门(5)](http://scz.617.cn:8/network/202003241127.txt)
        - [Java RMI入门(6)](http://scz.617.cn:8/network/202004011650.txt)
        - [Java RMI入门(7)](http://scz.617.cn:8/network/202004101018.txt)
        - [Java RMI入门(8)](http://scz.617.cn:8/network/202004141657.txt)
        - [Java RMI入门(9)](http://scz.617.cn:8/network/202004161823.txt)
        - [Java反序列化利用中绕过Registry白名单检查](http://scz.617.cn:8/network/202004211620.txt)
        - [从RMI Registry中转储动态端口信息](http://scz.617.cn:8/network/202004232047.txt)
      - [Java RMI for pentesters: structure, recon and communication (non-JMX Registries)](https://itnext.io/java-rmi-for-pentesters-structure-recon-and-communication-non-jmx-registries-a10d5c996a79)
      - [Java RMI for pentesters part two — reconnaissance & attack against non-JMX registries](https://itnext.io/java-rmi-for-pentesters-part-two-reconnaissance-attack-against-non-jmx-registries-187a6561314d)
    - JNDI
      - [浅析JNDI注入](https://www.mi1k7ea.com/2019/09/15/%E6%B5%85%E6%9E%90JNDI%E6%B3%A8%E5%85%A5/)
      - [浅析高低版JDK下的JNDI注入及绕过](https://www.mi1k7ea.com/2020/09/07/%E6%B5%85%E6%9E%90%E9%AB%98%E4%BD%8E%E7%89%88JDK%E4%B8%8B%E7%9A%84JNDI%E6%B3%A8%E5%85%A5%E5%8F%8A%E7%BB%95%E8%BF%87/)
      - [由JNDI注入引发的Spring Framework反序列化漏洞](https://www.mi1k7ea.com/2019/09/02/%E7%94%B1JNDI%E6%B3%A8%E5%85%A5%E5%AF%BC%E8%87%B4%E7%9A%84Spring-Framework%E5%8F%8D%E5%BA%8F%E5%88%97%E5%8C%96%E6%BC%8F%E6%B4%9E/)
      - [JAVA JNDI注入基础与高版本限制绕过](https://threezh1.com/2021/01/02/JAVA_JNDI_Learn/)
      - [搞懂RMI、JRMP、JNDI-终结篇](https://xz.aliyun.com/t/7264)
      - [8u191之后的JNDI注入(LDAP)](http://scz.617.cn:8/network/202005011956.txt)
      - [Java 中 RMI、JNDI、LDAP、JRMP、JMX、JMS那些事儿（上）](https://paper.seebug.org/1091/)
      - [浅谈 Log4j2 漏洞](https://tttang.com/archive/1378/)
      - [A JOURNEY	FROM JNDI/LDAP	MANIPULATION TO REMOTE CODE EXECUTION DREAM LAND](https://www.blackhat.com/docs/us-16/materials/us-16-Munoz-A-Journey-From-JNDI-LDAP-Manipulation-To-RCE-wp.pdf)
      - [Exploiting JNDI Injections in Java](https://www.veracode.com/blog/research/exploiting-jndi-injections-java)
    - 开源三方件
      - shiro
        - [Shiro 历史漏洞分析](https://tttang.com/archive/1645/#toc_cve-2019-12422)
    - 工具
      - [详解Java自动代码审计工具实现](https://tttang.com/archive/1334/#toc_)
      - Find-Sec-Bugs
        - [Android漏洞扫描工具Code Arbiter](https://tech.meituan.com/2017/08/17/android-code-arbiter.html) 
        - [Taint analysis added to FindBugs](https://www.ysofters.com/2015/08/31/taint-analysis-added-to-findbugs/)
        - [SpotBugs manual](https://spotbugs.readthedocs.io/en/latest/index.html)
      - RASP&IAST
        - [Rasp 技术介绍与实现](https://paper.seebug.org/330/)
        - [java Agent 简单学习](https://www.javaweb.org.cn/Ideas/java-agent-jian-dan-xue-xi.html#morphing)
        - [浅谈RASP技术攻防之基础篇](https://xz.aliyun.com/t/4290)
        - [浅谈RASP技术攻防之实战[环境配置篇]](https://xz.aliyun.com/t/4902)
        - [浅谈RASP技术攻防之实战[代码实现篇]](https://xz.aliyun.com/t/4903)
        - [浅谈被动式IAST产品与技术实现](http://tttang.com/archive/1375/)
        - OpenRASP
          - [Java底层防护 - OpenRASP核心源码浅析](https://xz.aliyun.com/t/7005)
          - [以OpenRASP为基础-展开来港港RASP的类加载](https://xz.aliyun.com/t/8148)
      - Gadget构造
        - [深入分析GadgetInspector核心代码](https://xz.aliyun.com/t/10363)
        - [Java 反序列化工具 gadgetinspector 初窥](https://paper.seebug.org/1034/)
        - [java反序列化利用链自动挖掘工具gadgetinspector源码浅析](https://xz.aliyun.com/t/7058)
        - [改造gadgetinspector篇-自动化挖掘Fastjson gadget chain](https://xz.aliyun.com/t/7063)
        - [浅析反序列化利用链自动化挖掘工具GadgetInspector](https://www.mi1k7ea.com/2020/05/11/%E6%B5%85%E6%9E%90%E5%8F%8D%E5%BA%8F%E5%88%97%E5%8C%96%E5%88%A9%E7%94%A8%E9%93%BE%E8%87%AA%E5%8A%A8%E5%8C%96%E6%8C%96%E6%8E%98%E5%B7%A5%E5%85%B7GadgetInspector/)
        - [Automated Discovery of
  Deserialization Gadget Chains](https://i.blackhat.com/us-18/Thu-August-9/us-18-Haken-Automated-Discovery-of-Deserialization-Gadget-Chains.pdf)
        - [gadgetinspector](https://github.com/JackOfMostTrades/gadgetinspector)
  - GoLang
  - Python
    - 漏洞
      - SSTI
        - [浅析Python Flask SSTI](https://www.mi1k7ea.com/2019/06/02/%E6%B5%85%E6%9E%90Python-Flask-SSTI/)
      - [一文看懂Python沙箱逃逸](https://www.freebuf.com/articles/system/203208.html)
      - 反序列化
        - pickle 
          - [pickle反序列化初探](https://xz.aliyun.com/t/7436)
          - [Python 的另外几个反序列化漏洞检查点](https://b1ue.cn/archives/218.html)
        - Yaml
          - [浅谈PyYAML反序列化漏洞](https://xz.aliyun.com/t/7923#toc-10)
          - [YAML Deserialization Attack in Python](https://www.exploit-db.com/docs/english/47655-yaml-deserialization-attack-in-python.pdf?utm_source=dlvr.it&utm_medium=twitter)
          - [pyyaml CVE-2020-14343](https://github.com/yaml/pyyaml/issues/420)
        - jsonpickle
          - [Jsonpickle Deserialization Issue](https://github.com/jsonpickle/jsonpickle/issues/332) 
    - 工具
      - Fuzz
        - [Python fuzz tool: atheris](https://github.com/google/atheris)
      - 污点分析
        - [Facebook Pyre](https://github.com/facebook/pyre-check)
    - MISC
      - [Python 源码混淆与加密](https://mp.weixin.qq.com/s/LmxdXRjMCOIisQzCISBoGw)
- **按开源软件划分**
  - Docker
    - [云原生安全初认识之容器安全 Cheat Sheet](https://threezh1.com/2021/02/26/%E4%BA%91%E5%8E%9F%E7%94%9F%E5%AE%89%E5%85%A8Cheat_Sheet/)
    - [Docker渗透思路调研](https://forum.90sec.com/t/topic/1338)
    - docker容器逃逸
      - [Docker逃逸小结 第一版](https://xz.aliyun.com/t/7881)
      - [CVE-2019-14271：Docker copy漏洞分析](https://xz.aliyun.com/t/6806)
    - [红蓝对抗中的云原生漏洞挖掘及利用实录](https://security.tencent.com/index.php/blog/msg/183)
    - [云原生安全攻防｜使用eBPF逃逸容器技术分析与实践](https://mp.weixin.qq.com/s/Psqy3X3VdUPga7f2cnct1g)
  - K8S
    - [K8s安全入门学习扫盲贴](https://tttang.com/archive/1465/)
  - 代理
    - Nginx
      - [三个案例看Nginx配置安全](https://www.leavesongs.com/PENETRATION/nginx-insecure-configuration.html) 
      - 检查工具
        - [gixy: 检查Nginx配置安全性](https://github.com/yandex/gixy)
    - [代理测试指南](https://github.com/GrrrDog/weird_proxies)
    - [A Fresh Look On Reverse Proxy Related Attacks](https://www.acunetix.com/blog/articles/a-fresh-look-on-reverse-proxy-related-attacks/)
    - [Abusing HTTP hop-by-hop request headers](https://nathandavison.com/blog/abusing-http-hop-by-hop-request-headers)
  - Redis
    - [Redis 常见漏洞利用方法总结](https://www.freebuf.com/articles/network/280984.html)
  - etcd
    - [云原生技术栈安全之etcd](https://mp.weixin.qq.com/s/5RorSaxl3HwBtKbmc4lctQ)
- **按协议划分**
  - OAuth
    - [OAuth 2.0 authentication vulnerabilities](https://portswigger.net/web-security/oauth)
- **OS**
  - [Arm Heap Exploitation
PART 1: UNDERSTANDING THE GLIBC HEAP IMPLEMENTATION](https://azeria-labs.com/heap-exploitation-part-1-understanding-the-glibc-heap-implementation/)
  - [gtfobins:Unix二进制的利用方法查询库](https://gtfobins.github.io/)
  - 提权
    - [LinPEAS - Linux Privilege Escalation Awesome Script](https://github.com/carlospolop/privilege-escalation-awesome-scripts-suite/tree/master/linPEAS)
    - [CVE-2021-4034 pkexec 本地提权](https://mp.weixin.qq.com/s/3rnkcRfX_BxzlVzp0stQRw)
  - 命令注入
    - [巧用命令注入的N种方式](https://mp.weixin.qq.com/s/Hm6TiLHiAygrJr-MGRq9Mw)
    - [OS命令绕过技巧](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Command%20Injection)
  - [Linux的Cgroups在HIDS-Agent资源限制上的应用](https://www.freebuf.com/articles/system/265733.html)
- **安全基础知识**
  - 密码学
    - RSA
      - [RSA算法原理（一）](https://www.ruanyifeng.com/blog/2013/06/rsa_algorithm_part_one.html)
      - [RSA算法原理（二）](https://www.ruanyifeng.com/blog/2013/07/rsa_algorithm_part_two.html)
    - AES
      - [我对Padding Oracle攻击的分析和思考](https://www.freebuf.com/articles/web/15504.html)
  - Web
    - 同源策略
      - [浏览器同源政策及其规避方法](https://www.ruanyifeng.com/blog/2016/04/same-origin-policy.html)
    - HTTP请求头
      - [一些安全相关的HTTP响应头](https://imququ.com/post/web-security-and-response-header.html)
      - [安全相关HTTP响应头解读、配置、示例与检测](https://xz.aliyun.com/t/7202)
    - SSL/TLS
      - [SSL/TLS协议运行机制的概述](http://www.ruanyifeng.com/blog/2014/02/ssl_tls.html)
      - [图解SSL/TLS协议](http://www.ruanyifeng.com/blog/2014/09/illustration-ssl.html)
      - [SSL/TLS协议详解(上)：密码套件，哈希，加密，密钥交换算法](https://xz.aliyun.com/t/2526)
      - [SSL/TLS协议详解(中)——证书颁发机构](https://xz.aliyun.com/t/2530)
      - [SSL/TLS协议详解(下)——TLS握手协议](https://xz.aliyun.com/t/2531)
    - [Unicode标准化对照表](https://appcheck-ng.com/wp-content/uploads/unicode_normalization.html)
- **企业安全建设**
  - [安全左移理念，腾讯DevSecOps如何实践？](https://security.tencent.com/index.php/blog/msg/191)
  - [浅谈如何有效落地DevSecOps](https://www.freebuf.com/articles/security-management/264610.html) 
  - [互联网企业数据安全体系建设](https://tech.meituan.com/2018/05/24/data-security-system-construction.html)
  - [实践之后，我们来谈谈如何做好威胁建模](https://tech.meituan.com/2021/04/08/threat-modeling-security.html)
  - [聊聊漏洞自动修复技术的行业现状](https://mp.weixin.qq.com/s/xgwdhBSvE7yW0YcekGEWjA)
  - [应用程序接口（API）数据安全研究报告（2020年）](http://www.caict.ac.cn/kxyj/qwfb/ztbg/202007/P020200727599918681913.pdf)
- **Tools**
  - Burpsuite
    - [BurpSuite Trick ALL In ONE (第一版)](https://forum.butian.net/share/686?&continueFlag=52c12e2e2fade49f105ad607843177bb)
    - [Burp Suite 文档手册](https://www.bookstack.cn/read/BurpSuite/AuthKey.MD)
    - [burpsuite实战指南](https://t0data.gitbooks.io/burpsuite/content/chapter6.html)
  - CodeQL
    - [CodeQL从入门到放弃](https://www.freebuf.com/articles/web/283795.html)
    - [代码分析平台CodeQL学习手记](https://www.4hou.com/posts/o6wX)
    - [代码分析引擎 CodeQL 初体验](https://paper.seebug.org/1078/#_4)
    - [CodeQL官方文档](https://codeql.github.com/docs/)
    - [CodeQL中文翻译文档](https://github.com/xsser/codeql_chinese)
  - crawlergo
    - [crawlergo 动态爬虫源码学习](https://mp.weixin.qq.com/s/votEOvJafPjCka7gIB8DEA)
- **MISC**
  - GFW
    - [Shadowsocks 是如何被检测和封锁的](https://gfw.report/blog/gfw_shadowsocks/zh.html)
    - [Trojan基本原理](https://p4gefau1t.github.io/trojan-go/basic/trojan/)
  - WebShell
    - [冰蝎](https://github.com/rebeyond/Behinder)
    - [Spring Boot Fat Jar 写文件漏洞到稳定 RCE 的探索](https://landgrey.me/blog/22/)
    - [JDK8任意文件写场景下的Fastjson RCE](https://threedr3am.github.io/2021/04/13/JDK8%E4%BB%BB%E6%84%8F%E6%96%87%E4%BB%B6%E5%86%99%E5%9C%BA%E6%99%AF%E4%B8%8B%E7%9A%84Fastjson%20RCE/)
  - 如何成为一名黑客
    - [How do I get Started in Cyber Security? — My Perspective & Learning Path!](https://hbothra22.medium.com/how-do-i-get-started-in-cyber-security-my-perspective-learning-path-b53065189ba5)
    - [HowToHunt](https://kathan19.gitbook.io/howtohunt/)
  - 书籍
    - [HackTricks](https://book.hacktricks.xyz/)
