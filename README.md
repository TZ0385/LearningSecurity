# Hello, Security!

- **web**
  - 同源策略
    - [浏览器同源政策及其规避方法](https://www.ruanyifeng.com/blog/2016/04/same-origin-policy.html)
  - HTTP请求头
    - [一些安全相关的HTTP响应头](https://imququ.com/post/web-security-and-response-header.html)
    - [安全相关HTTP响应头解读、配置、示例与检测](https://xz.aliyun.com/t/7202)
  - SSL/TLS
    - [SSL/TLS协议运行机制的概述](http://www.ruanyifeng.com/blog/2014/02/ssl_tls.html)
    - [图解SSL/TLS协议](http://www.ruanyifeng.com/blog/2014/09/illustration-ssl.html)
  - XSS
    - [前端安全系列（一）：如何防止XSS攻击？](https://tech.meituan.com/2018/09/27/fe-security.html)
    - [深入理解浏览器解析机制和XSS向量编码](http://bobao.360.cn/learning/detail/292.html)
    - [SVG XSS的一个黑魔法](https://www.hackersb.cn/hacker/85.html)
    - [无需括号与分号的XSS](https://www.anquanke.com/post/id/178610)
    - [使用 Dom Clobbering 扩展 XSS](https://xz.aliyun.com/t/7329)
    - [XSS Game分析以及知识点总结](https://www.freebuf.com/articles/web/245209.html)
    - [XSS靶场](http://prompt.ml/4)
  - XXE
    - [XML文档类型定义](http://210.34.136.253:8488/XML_Study_New/Chapter4.htm)
    - [Blind XXE详解与Google CTF一道题分析](https://www.freebuf.com/vuls/207639.html)
  - 标签页劫持（Tabnabbing）
    - [钓鱼攻击之Reverse Tabnabbing](https://xz.aliyun.com/t/7080)
  - SQL注入
    - [SQL注入绕过技巧](http://byd.dropsec.xyz/2016/08/01/SQL-Injection%E7%BB%95%E8%BF%87%E6%8A%80%E5%B7%A7/)
    - 宽字节注入
      - [浅析白盒审计中的字符编码及SQL注入](https://www.leavesongs.com/PENETRATION/mutibyte-sql-inject.html)
    - [PostgreSQL Injection](https://evi1cg.me/archives/PostgreSQL-Injection.html)
  - DOS
    - ReDos
      - [ReDOS初探](http://www.lmxspace.com/2019/02/16/ReDOS%E5%88%9D%E6%8E%A2/)
      - [ReDOS攻击](https://lingwu111.github.io/ReDOS.html)
      - [在线检测redos](http://redos-checker.surge.sh/)
    - SLOW HTTP 
      - [Slowhttptest攻击原理](https://cloud.tencent.com/developer/article/1180216)
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
  - zip bomb
    - [zip炸弹制作](https://github.com/abdulfatir/ZipBomb)
    - [A better zip bomb](https://zerosun.top/2019/07/07/A-better-zip-bomb/)
    - [The (Decompression) Bomb Site](https://bomb.codes/)
  - CRLF
    - [新浪某站CRLF Injection导致的安全问题](https://www.leavesongs.com/PENETRATION/Sina-CRLF-Injection.html)
  - CSRF
    - [前端安全系列（二）：如何防止CSRF攻击？](https://tech.meituan.com/2018/10/11/fe-security-csrf.html)
    - [CSRF攻击技术浅析](https://xz.aliyun.com/t/8186)
  - SSRF
    - [SSRF绕过方法总结](http://byd.dropsec.xyz/2017/11/21/SSRF%E7%BB%95%E8%BF%87%E6%96%B9%E6%B3%95%E6%80%BB%E7%BB%93/)
  - 缓冲区投毒
    - CPDoS
      - [CPDoS：一种新的Web缓存污染攻击](https://www.anquanke.com/post/id/189507)
      - [cpdos网站](https://cpdos.org/)
      - [Your Cache Has Fallen: Cache-Poisoned Denial-of-Service Attack](https://cpdos.org/paper/Your_Cache_Has_Fallen__Cache_Poisoned_Denial_of_Service_Attack__Preprint_.pdf)
  - HTTP request smuggling
    - [HTTP Desync Attacks: Request Smuggling Reborn](https://portswigger.net/research/http-desync-attacks-request-smuggling-reborn#top)
    - [协议层的攻击——HTTP请求走私](https://paper.seebug.org/1048/)
    - [一篇文章带你读懂 HTTP Smuggling 攻击](https://xz.aliyun.com/t/6878#toc-16)
  - WebShell
    - [冰蝎](https://github.com/rebeyond/Behinder)
  - MISC
    - [代理测试指南](https://github.com/GrrrDog/weird_proxies)
- **OS**
  - [Arm Heap Exploitation
PART 1: UNDERSTANDING THE GLIBC HEAP IMPLEMENTATION](https://azeria-labs.com/heap-exploitation-part-1-understanding-the-glibc-heap-implementation/)
  - [gtfobins:Unix二进制的利用方法查询库](https://gtfobins.github.io/)
  - 提权
    - [LinPEAS - Linux Privilege Escalation Awesome Script](https://github.com/carlospolop/privilege-escalation-awesome-scripts-suite/tree/master/linPEAS)
  - 命令注入
    - [巧用命令注入的N种方式](https://mp.weixin.qq.com/s/Hm6TiLHiAygrJr-MGRq9Mw)
    - [OS命令绕过技巧](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Command%20Injection)
- **JavaScript**
  - 原型污染
    - [深入理解 JavaScript Prototype 污染攻击](https://www.leavesongs.com/PENETRATION/javascript-prototype-pollution-attack.html)
  - [Node.js 常见漏洞学习与总结](https://threezh1.com/2020/01/30/NodeJsVulns/)
- **Java**
  - 表达式注入
    - OGNL注入
      - [OGNL表达式注入漏洞总结](https://www.mi1k7ea.com/2020/03/16/OGNL%E8%A1%A8%E8%BE%BE%E5%BC%8F%E6%B3%A8%E5%85%A5%E6%BC%8F%E6%B4%9E%E6%80%BB%E7%BB%93/#0x03-OGNL%E8%A1%A8%E8%BE%BE%E5%BC%8F%E6%B3%A8%E5%85%A5%E6%BC%8F%E6%B4%9E)
      - [浅析 OGNL 的攻防史](https://paper.seebug.org/794/)
    - Spel表达式注入
      - [SpEL表达式注入漏洞总结](https://www.mi1k7ea.com/2020/01/10/SpEL%E8%A1%A8%E8%BE%BE%E5%BC%8F%E6%B3%A8%E5%85%A5%E6%BC%8F%E6%B4%9E%E6%80%BB%E7%BB%93/)
    - EL表达式注入
      - [浅析EL表达式注入漏洞](https://xz.aliyun.com/t/7692)
      - [remote code execution with el injection vulnerabilities](https://www.exploit-db.com/docs/english/46303-remote-code-execution-with-el-injection-vulnerabilities.pdf)
    - JBoss EL表达式注入
      - [nuxeo rce 漏洞复现分析](https://xz.aliyun.com/t/3352)
  - 模板注入
    - Freemarker模板注入
      - [Freemarker模板注入 Bypass](https://mp.weixin.qq.com/s/8YIVWtdqCAVPKaLXEZtFkg)
  - 反序列化
    - 原理介绍
      - [Lib之过？Java反序列化漏洞通用利用分析](https://blog.chaitin.cn/2015-11-11_java_unserialize_rce/)
    - XMLDecoder反序列化
      - [XMLDecoder解析流程分析](https://xz.aliyun.com/t/5069)
    - XStream反序列化
      - [Java XStream反序列化漏洞](https://www.mi1k7ea.com/2019/10/21/XStream%E5%8F%8D%E5%BA%8F%E5%88%97%E5%8C%96%E6%BC%8F%E6%B4%9E/)
    - Yaml反序列化
      - [Java SnakeYaml反序列化漏洞](https://www.mi1k7ea.com/2019/11/29/Java-SnakeYaml%E5%8F%8D%E5%BA%8F%E5%88%97%E5%8C%96%E6%BC%8F%E6%B4%9E/)
    - Jackson反序列化
      - [Jackson系列一——反序列化漏洞基本原理](https://www.mi1k7ea.com/2019/11/13/Jackson%E7%B3%BB%E5%88%97%E4%B8%80%E2%80%94%E2%80%94%E5%8F%8D%E5%BA%8F%E5%88%97%E5%8C%96%E6%BC%8F%E6%B4%9E%E5%9F%BA%E6%9C%AC%E5%8E%9F%E7%90%86/)
    - Fastjson反序列化
      - [Fastjson系列一——反序列化漏洞基本原理](https://www.mi1k7ea.com/2019/11/03/Fastjson%E7%B3%BB%E5%88%97%E4%B8%80%E2%80%94%E2%80%94%E5%8F%8D%E5%BA%8F%E5%88%97%E5%8C%96%E6%BC%8F%E6%B4%9E%E5%9F%BA%E6%9C%AC%E5%8E%9F%E7%90%86/)
    - Gadget构造
      - [Automated Discovery of
Deserialization Gadget Chains](https://i.blackhat.com/us-18/Thu-August-9/us-18-Haken-Automated-Discovery-of-Deserialization-Gadget-Chains.pdf)
      - [gadgetinspector](https://github.com/JackOfMostTrades/gadgetinspector)
  - JDWP
    - [Hacking the Java Debug Wire Protocol – or – “How I met your Java debugger”](https://ioactive.com/hacking-java-debug-wire-protocol-or-how/)
  - JMX
    - [JMX远程代码漏洞研究](https://www.freebuf.com/vuls/231132.html)
- **GoLang**
- **Python**
  - [Python 源码混淆与加密](https://mp.weixin.qq.com/s/LmxdXRjMCOIisQzCISBoGw)
  - SSTI
    - [浅析Python Flask SSTI](https://www.mi1k7ea.com/2019/06/02/%E6%B5%85%E6%9E%90Python-Flask-SSTI/)
- **容器**
  - [Docker渗透思路调研](https://forum.90sec.com/t/topic/1338)
  - docker容器逃逸
    - [Docker逃逸小结 第一版](https://xz.aliyun.com/t/7881)
    - [CVE-2019-14271：Docker copy漏洞分析](https://xz.aliyun.com/t/6806)
- **Fuzz**
  - [Python fuzz tool: atheris](https://github.com/google/atheris)
- **密码学**
  - RSA
    - [RSA算法原理（一）](https://www.ruanyifeng.com/blog/2013/06/rsa_algorithm_part_one.html)
    - [RSA算法原理（二）](https://www.ruanyifeng.com/blog/2013/07/rsa_algorithm_part_two.html)
  - AES
    - [我对Padding Oracle攻击的分析和思考](https://www.freebuf.com/articles/web/15504.html)
- **Tools**
  - Burpsuite
    - [Burp Suite 文档手册](https://www.bookstack.cn/read/BurpSuite/AuthKey.MD)
    - [burpsuite实战指南](https://t0data.gitbooks.io/burpsuite/content/chapter6.html)
- **书籍**
    - [HackTricks](https://book.hacktricks.xyz/)
- **MISC**
  - [How do I get Started in Cyber Security? — My Perspective & Learning Path!](https://hbothra22.medium.com/how-do-i-get-started-in-cyber-security-my-perspective-learning-path-b53065189ba5)
  - [Unicode标准化对照表](https://appcheck-ng.com/wp-content/uploads/unicode_normalization.html)
