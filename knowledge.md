# 基于知识的问题 #

*这些问题有正确或错误的答案。他们应该有不同的答案。*
*原文请查看knowledge-EN.md*

## 技术问题 ##

### 常规渗透 ###

1. 渗透测试有哪几阶段？ *@whereistehnarwhal, reddit*
2. 风险评估、漏洞评估和渗透测试之间有什么区别？ *@whereistehnarwhal, reddit*
3. 运行 nmap 扫描时，指定从哪个源端口扫描，通常可以绕过防火墙规则？ *@jstnkndy*
4. 写一个 Nmap 命令，要求使用 SYN 扫描，它不进行 DNS 查找，不 ping 主机，只返回 tcp/139 和 tcp/445 的开放端口。 *@whereistehnarwhal, reddit*
5. ARP Spoofing 是什么攻击？在渗透测试中如何利用？ *@jstnkndy*
6. 什么是 NBNS 欺骗（NBNS poisoning）？在渗透测试中如何利用？ *@jstnkndy*
7. 双因素身份验证可防止会话劫持，是或不是，原因？ *@jstnkndy*
8. 从浏览器发起连接到服务器，OSI 每一个层都发生了什么？ *@dhauenstein*

### 加密/哈希/密码 ###

1. 说出流加密（对称密钥算法的一种）如何输入和输出。 *@jstnkndy*
2. 列出几个分组密码，描述其特性和安全性问题。 *@jstnkndy*
3. 描述在应用程序渗透测试期间何时使用空字节（null byte）。 *@jstnkndy*
4. LM 哈希（Windows）有什么问题？ *@jstnkndy*
5. netNTLM 和 NTLM 哈希之间有什么区别？ *@jstnkndy*
6. 什么是传递哈希？ *@jstnkndy*
7. 什么是模拟令牌（token impersonation，线程token）？ *@jstnkndy*

### Web 应用 ###

1. SQL 注入是什么？你会如何测试是否存在该漏洞很难过？ *@jstnkndy*
2. SQL 盲注(Blind SQL Injection)是什么？它与其他的 SQL 注入类型有什么不同？ *@jstnkndy*
3. SQL 注入如何导致远程代码执行？ *@morgoroth*
4. 如何使用 MSSQL 注入执行命令？ *@enddo*
5. 描述一个 Webshel​​l 以及如何上传/使用它。 *@enddo*
    1. 如何绕过上传保护措施？ *@enddo*
6. 描述远程命令执行（RCE）是什么。 *@enddo*
    1. 如何在 PHP 中阻止 RCE？ *@enddo*
7. 描述跨站点请求伪造（CSRF）。 *@jstnkndy*
    1. 如何防御 CSRF ？
8. 有哪几种类型的 XSS。 *@jstnkndy*
    1. 利用 XSS 能做什么？
9. 与文档对象模型相关的原始策略的目的是什么？ *@jstnkndy*
10. 描述分组密码的输入和输出的基础知识。 *@jstnkndy*
11. 心脏出血（Heartbleed）漏洞原理是什么？ *@webbreacher*
12. 如何利用Shellshock漏洞？攻击者可以利用它做些什么？ *@webbreacher*

### EXP开发 ###

1. 描述缓冲区溢出是什么？如何测试该漏洞的存在？ *@enddo*
2. 描述 SEH 是什么？如何利用它？ *@enddo*
3. 描述调试器模块和插件如何帮助 EXP 开发更加迅速？ *@enddo*
4. 如何在 Windows 7 中绕过 DEP 或 ASLR？ *@enddo*
5. 如何绕过 SafeSEH？ *@enddo*

### Mobile ###

1.如何 root Android 设备或越狱 iOS 设备。 *@webbreacher*

### 活动目录(Active Directory，域控方面) ###

1. 什么是 kerberoasting（Kerberos攻击）？ *@leesoh*
> Kerberos协议在请求访问某个服务时存在一个缺陷，Kerberoasting正是利用这个缺陷的一种攻击技术。
2. 什么是 golden ticket（Kerberos）？ *@leesoh*
3. 什么是 silver ticket（Kerberos）？ *@leesoh*
