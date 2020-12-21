# vulnerability-review
寻找公开漏洞案例进行复盘学习。
在模仿中学习挖洞姿势！

*vuln/tricks来源*：
```
wooyun 漏洞库
hackerone 公开漏洞
bugreader 公开报告
```


## 漏洞列表
### SQL Injection
###### [01 SQL Injection on cookie parameter](https://hackerone.com/reports/761304)
###### [02 SQL Injection - https://███/█████████/MSI.portal](https://hackerone.com/reports/674838)
###### [03 Followup - SQL Injection - https://██████████/██████/MSI.portal](https://hackerone.com/reports/692326)
###### [04 SQL Injection in Login Page: https://█████/█████████/login.php](https://hackerone.com/reports/447742)


### SSRF
###### [01 wooyun-2016-0227704 当当网某站点SSRF可以遍历本地文件](https://wooyun.laolisafe.com/bug_detail.php?wybug_id=wooyun-2016-0227704) √
###### [02 wooyun-2014-083592 利用两个鸡肋SSRF探测360内网](https://wooyun.laolisafe.com/bug_detail.php?wybug_id=wooyun-2014-083592) √
###### [03 CVE-2019-5464 Server Side Request Forgery mitigation bypass](https://hackerone.com/reports/632101)
###### [04 labs.data.gov/dashboard/validate中的SSRF / XSPA](https://hackerone.com/reports/272095)


### XSPA（跨站点端口攻击）
###### [01 labs.data.gov/dashboard/validate中的SSRF / XSPA](https://hackerone.com/reports/272095)



### CSRF

### Reflected XSS
###### [01 Reflected XSS on www.hackerone.com and resources.hackerone.com](https://hackerone.com/reports/840759)
###### [02 XSS in select attribute options](https://hackerone.com/reports/753567)
###### [03 Prevent XSS when passing a parameter directly into link_to](https://hackerone.com/reports/755354)
###### [04 Reflected XSS on https://apps.topcoder.com/wiki/page/](https://hackerone.com/reports/866433)
###### [05 Reflected XSS on https://apps.topcoder.com/wiki/](https://hackerone.com/reports/866426)
###### [06 Reflected XSS on https://apps.topcoder.com/wiki/pages/createpage.action](https://hackerone.com/reports/866576)


### Stored XSS
###### [01 Stored XSS on upload files leads to steal cookie](https://hackerone.com/reports/765679)
###### [02 Potential stored Cross-Site Scripting vulnerability in Support Backend](https://hackerone.com/reports/858894)

### CRLF Injection(HTTP响应拆分)
###### [01 CVE-2019-9947 CRLF Injection in urllib](https://hackerone.com/reports/590020)

### XXE
###### [01 XXE through injection of a payload in the XMP metadata of a JPEG file](https://hackerone.com/reports/836877)

### Path Traversal(路径遍历)
###### [01 Arbitrary file read via the UploadsRewriter when moving and issue](https://hackerone.com/reports/827052)
###### [02 [Total.js] Path traversal vulnerability allows to read files outside public directory](https://hackerone.com/reports/748765)
###### [03 [https://███] Local File Inclusion via graph.php](https://hackerone.com/reports/492767)

### File Upload 



### Insecure Direct Object Reference - Generic(IDOR)
###### [01 Missing ownership check on remote wipe endpoint](https://hackerone.com/reports/819807)
###### [02 Insecure redirect rule results in bypassing ban redirect on certain pages](https://hackerone.com/reports/703058)
###### [03 [██████████] Unauthorized access to admin panel](https://hackerone.com/reports/648222)
###### [04 IDOR on update user preferences](https://hackerone.com/reports/854290)
###### [05 Idor on the DELETE /comments/](https://hackerone.com/reports/861849)
###### [06 IDOR on deleting drafts on https://apps.topcoder.com/wiki/users/viewmydrafts.action via discardDraftId parameter](https://hackerone.com/reports/868590)

### XPath Injection


### Code Injection
###### [01 [git-promise] RCE via insecure command formatting](https://hackerone.com/reports/728047)



### Command Injection - Generic（命令注入）
###### [01 Command Injection (via CVE-2019-11510 and CVE-2019-11539)](https://hackerone.com/reports/680480)

### Denial of Service（拒绝服务）
###### [01 Denial of service to WP-JSON API by cache poisoning the CORS allow origin header](https://hackerone.com/reports/591302)
###### [02 Malformed string sent through FireServer leads to server freezing/hanging](https://hackerone.com/reports/679907)
###### [03 File Upload Restriction Bypass](https://hackerone.com/reports/259913)

### HTML injection

### Clickjacking(点击劫持)
###### [01 frame injection on bittorrent.com](https://hackerone.com/reports/846430)


### Open Redirect（重定向）
###### [01 Open Redirection leads to redirect Users to malicious website](https://hackerone.com/reports/625546)
###### [02 open redirect in eb9f.pivcac.prod.login.gov](https://hackerone.com/reports/798742)


### Information Disclosure（信息泄露）
###### [01 Internal IP Address Disclosed](https://hackerone.com/reports/707228)
###### [02 Firewall rules for ████████ can be bypassed to leak site authors](https://hackerone.com/reports/743643)


### Improper Access Control
###### [01 Unrestricted access to any "connected pack" on docs](https://hackerone.com/reports/777942)
###### [02 Sourcemaps and Unminified Source Code Exposed on Pages](https://hackerone.com/reports/845677)


### Improper Authorization
###### [01 You can override the speed limit by adding the X-Forwarded-For header.](https://hackerone.com/reports/855013)

### Misconfiguration（错误的配置）
###### [01 misconfigured CORS let to HPP and SOP bypass](https://hackerone.com/reports/867436)



### Deserialization of Untrusted Data（反序列化）
###### [01 Remote Code Execution via Insecure Deserialization in Telerik UI](https://hackerone.com/reports/838196)

### HTTP Request Smuggling(HTTP请求走私)
###### [01 HTTP Request Smuggling on https://labs.data.gov](https://hackerone.com/reports/726773)

### Phishing
###### [01 URL link spoofing](https://hackerone.com/reports/481472)


### Other
###### [01 disclosure of email by sending a message.](https://hackerone.com/reports/327200)
###### [02 Session works after logout from Shopify account and password of online store is displayed](https://hackerone.com/reports/837729)
###### [03 Subdomain Takeover to Authentication bypass](https://hackerone.com/reports/335330)
