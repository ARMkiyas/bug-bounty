# vulnerability-review
寻找公开漏洞案例进行复盘学习。
在模仿中学习挖洞姿势！

*漏洞来源*：
```
wooyun漏洞库
hackerone 公开报告漏洞
```
*站在师傅们的肩膀上*：

[一篇文章教你如何发现密码找回处漏洞](https://xz.aliyun.com/t/7623)


## 漏洞列表
### SQL Injection
###### [SQL Injection on cookie parameter](https://hackerone.com/reports/761304)

### SSRF
###### [wooyun-2016-0227704 当当网某站点SSRF可以遍历本地文件](https://wooyun.laolisafe.com/bug_detail.php?wybug_id=wooyun-2016-0227704) √
###### [wooyun-2014-083592 利用两个鸡肋SSRF探测360内网](https://wooyun.laolisafe.com/bug_detail.php?wybug_id=wooyun-2014-083592) √
###### [CVE-2019-5464 Server Side Request Forgery mitigation bypass](https://hackerone.com/reports/632101)
###### [labs.data.gov/dashboard/validate中的SSRF / XSPA](https://hackerone.com/reports/272095)


### XSPA（跨站点端口攻击）
###### [labs.data.gov/dashboard/validate中的SSRF / XSPA](https://hackerone.com/reports/272095)



### CSRF

### Reflected XSS
###### [Reflected XSS on www.hackerone.com and resources.hackerone.com](https://hackerone.com/reports/840759)
###### [XSS in select attribute options](https://hackerone.com/reports/753567)

### Stored XSS
###### [Stored XSS on upload files leads to steal cookie](https://hackerone.com/reports/765679)
###### [Potential stored Cross-Site Scripting vulnerability in Support Backend](https://hackerone.com/reports/858894)

### CRLF Injection(HTTP响应拆分)
###### [CVE-2019-9947 CRLF Injection in urllib](https://hackerone.com/reports/590020)

### XXE
###### [XXE through injection of a payload in the XMP metadata of a JPEG file](https://hackerone.com/reports/836877)

### Path Traversal(路径遍历)
###### [Arbitrary file read via the UploadsRewriter when moving and issue](https://hackerone.com/reports/827052)
###### [[Total.js] Path traversal vulnerability allows to read files outside public directory](https://hackerone.com/reports/748765)

### Insecure Direct Object Reference (IDOR)
###### [Missing ownership check on remote wipe endpoint](https://hackerone.com/reports/819807)
###### [Insecure redirect rule results in bypassing ban redirect on certain pages](https://hackerone.com/reports/703058)


### XPath Injection

### Denial of Service（拒绝服务）
###### [Denial of service to WP-JSON API by cache poisoning the CORS allow origin header](https://hackerone.com/reports/591302)
###### [Malformed string sent through FireServer leads to server freezing/hanging](https://hackerone.com/reports/679907)
### HTML injection

### Clickjacking(点击劫持)
###### [frame injection on bittorrent.com](https://hackerone.com/reports/846430)


### Open Redirect（重定向）
###### [Open Redirection leads to redirect Users to malicious website](https://hackerone.com/reports/625546)



### Information Disclosure（信息泄露）


### Improper Access Control
###### [Unrestricted access to any "connected pack" on docs](https://hackerone.com/reports/777942)
###### [Sourcemaps and Unminified Source Code Exposed on Pages](https://hackerone.com/reports/845677)


### Improper Authorization
###### [You can override the speed limit by adding the X-Forwarded-For header.](https://hackerone.com/reports/855013)

### Misconfiguration（错误的配置）
###### [misconfigured CORS let to HPP and SOP bypass](https://hackerone.com/reports/867436)

### Command Injection - Generic（命令注入）
###### [Command Injection (via CVE-2019-11510 and CVE-2019-11539)](https://hackerone.com/reports/680480)

### Deserialization of Untrusted Data（反序列化）
###### [Remote Code Execution via Insecure Deserialization in Telerik UI](https://hackerone.com/reports/838196)

### Phishing
###### [URL link spoofing](https://hackerone.com/reports/481472)


### other
###### [disclosure of email by sending a message.](https://hackerone.com/reports/327200)
###### [Session works after logout from Shopify account and password of online store is displayed](https://hackerone.com/reports/837729)

