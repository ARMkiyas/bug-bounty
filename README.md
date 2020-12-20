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


### SSRF
##### [wooyun-2016-0227704 当当网某站点SSRF可以遍历本地文件](https://wooyun.laolisafe.com/bug_detail.php?wybug_id=wooyun-2016-0227704) √
##### [wooyun-2014-083592 利用两个鸡肋SSRF探测360内网](https://wooyun.laolisafe.com/bug_detail.php?wybug_id=wooyun-2014-083592) √
##### [CVE-2019-5464 Server Side Request Forgery mitigation bypass](https://hackerone.com/reports/632101)

### CSRF

### Reflected XSS



### Stored XSS
##### [Stored XSS on upload files leads to steal cookie](https://hackerone.com/reports/765679)


### CRLF Injection
[CVE-2019-9947 CRLF Injection in urllib](https://hackerone.com/reports/590020)

### XXE
##### [XXE through injection of a payload in the XMP metadata of a JPEG file](https://hackerone.com/reports/836877)

### Insecure Direct Object Reference (IDOR)
##### [Missing ownership check on remote wipe endpoint](https://hackerone.com/reports/819807)

### XPath Injection

### Denial of Service
##### [Denial of service to WP-JSON API by cache poisoning the CORS allow origin header](https://hackerone.com/reports/591302)

### HTML injection

### Clickjacking


### Information Disclosure


### Improper Access Control
##### [Unrestricted access to any "connected pack" on docs](https://hackerone.com/reports/777942)
##### [Sourcemaps and Unminified Source Code Exposed on Pages](https://hackerone.com/reports/845677)


### Improper Authorization
[You can override the speed limit by adding the X-Forwarded-For header.](https://hackerone.com/reports/855013)

### Misconfiguration
##### [misconfigured CORS let to HPP and SOP bypass](https://hackerone.com/reports/867436)

### Command Injection - Generic
[Command Injection (via CVE-2019-11510 and CVE-2019-11539)](https://hackerone.com/reports/680480)

### Deserialization of Untrusted Data
[Remote Code Execution via Insecure Deserialization in Telerik UI](https://hackerone.com/reports/838196)
