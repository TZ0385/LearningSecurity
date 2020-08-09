# Hello, Security!

- **web**
  - 同源策略
    - [浏览器同源政策及其规避方法](https://www.ruanyifeng.com/blog/2016/04/same-origin-policy.html)
  - SSL/TLS
    - [SSL/TLS协议运行机制的概述](http://www.ruanyifeng.com/blog/2014/02/ssl_tls.html)
    - [图解SSL/TLS协议](http://www.ruanyifeng.com/blog/2014/09/illustration-ssl.html)
  - XSS
    - [深入理解浏览器解析机制和XSS向量编码](http://bobao.360.cn/learning/detail/292.html)
    - [SVG XSS的一个黑魔法](https://www.hackersb.cn/hacker/85.html)
    - [XSS靶场](http://prompt.ml/4)
  - XXE
    - [XML文档类型定义](http://210.34.136.253:8488/XML_Study_New/Chapter4.htm)
    - [Blind XXE详解与Google CTF一道题分析](https://www.freebuf.com/vuls/207639.html)
  - SQL注入
    - [SQL注入绕过技巧](http://byd.dropsec.xyz/2016/08/01/SQL-Injection%E7%BB%95%E8%BF%87%E6%8A%80%E5%B7%A7/)
    - 宽字节注入
      - [浅析白盒审计中的字符编码及SQL注入](https://www.leavesongs.com/PENETRATION/mutibyte-sql-inject.html)
  - ReDos
    - [ReDOS初探](http://www.lmxspace.com/2019/02/16/ReDOS%E5%88%9D%E6%8E%A2/)
    - [ReDOS攻击](https://lingwu111.github.io/ReDOS.html)
  - blind regex injection
    - [A Rough Idea of Blind Regular Expression Injection Attack](https://diary.shift-js.info/blind-regular-expression-injection/)
    - [Revisiting ReDoS: A Rough Idea of Data Exfiltration by ReDoS and Side-channel Techniques](https://speakerdeck.com/lmt_swallow/revisiting-redos-a-rough-idea-of-data-exfiltration-by-redos-and-side-channel-techniques)
  - 文件上传
    - [简单粗暴的文件上传漏洞](https://paper.seebug.org/560/)
    - [Upload-labs通关手册](https://xz.aliyun.com/t/2435)
    - [文件解析漏洞总结](https://www.smi1e.top/%E6%96%87%E4%BB%B6%E8%A7%A3%E6%9E%90%E6%BC%8F%E6%B4%9E%E6%80%BB%E7%BB%93/)
  - zip bomb
    - [zip炸弹制作](https://github.com/abdulfatir/ZipBomb)
  - CRLF
    - [新浪某站CRLF Injection导致的安全问题](https://www.leavesongs.com/PENETRATION/Sina-CRLF-Injection.html)
  - SSRF
    - [SSRF绕过方法总结](http://byd.dropsec.xyz/2017/11/21/SSRF%E7%BB%95%E8%BF%87%E6%96%B9%E6%B3%95%E6%80%BB%E7%BB%93/)
  - 缓冲区投毒
    - CPDoS
      - [CPDoS：一种新的Web缓存污染攻击](https://www.anquanke.com/post/id/189507)
      - [cpdos网站](https://cpdos.org/)
      - [Your Cache Has Fallen: Cache-Poisoned Denial-of-Service Attack](https://cpdos.org/paper/Your_Cache_Has_Fallen__Cache_Poisoned_Denial_of_Service_Attack__Preprint_.pdf)
- **JavaScript**
  - 原型污染
    - [深入理解 JavaScript Prototype 污染攻击](https://www.leavesongs.com/PENETRATION/javascript-prototype-pollution-attack.html)
- **Java**
  - 表达式注入
    - OGNL注入
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
    - XMLDecoder反序列化
      - [XMLDecoder解析流程分析](https://xz.aliyun.com/t/5069)
    - XStream反序列化
      - [Java XStream反序列化漏洞](https://www.mi1k7ea.com/2019/10/21/XStream%E5%8F%8D%E5%BA%8F%E5%88%97%E5%8C%96%E6%BC%8F%E6%B4%9E/)
    - Yaml反序列化
      - [Java SnakeYaml反序列化漏洞](https://www.mi1k7ea.com/2019/11/29/Java-SnakeYaml%E5%8F%8D%E5%BA%8F%E5%88%97%E5%8C%96%E6%BC%8F%E6%B4%9E/)
- **Tools**
  - Burpsuite
    - [burpsuite实战指南](https://t0data.gitbooks.io/burpsuite/content/chapter6.html)
