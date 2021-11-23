# HTTP
HTTP（hypertext transport protocol）协议『超文本传输协议』，协议详细规定了浏览器和万维网服务器之间互相通信的规则。
约定, 规则

## 请求报文（四部分）
重点是格式与参数
```
行（三部分）      POST（请求方式）  /s?ie=utf-8（URL内容）  HTTP/1.1 （协议版本）

头      Host: atguigu.com
        Cookie: name=guigu
        Content-type: application/x-www-form-urlencoded（请求体类型）
        User-Agent: chrome 83

空行
（如果是GET请求的话 请求体为空）
体      username=admin&password=admin

```

## 响应报文
```
行      HTTP/1.1  200（响应状态码）  OK（响应状态字符串）

头      Content-Type: text/html;charset=utf-8
        Content-length: 2048
        Content-encoding: gzip

空行    

体      <html>
            <head>
            </head>
            <body>
                <h1>尚硅谷</h1>
            </body>
        </html>
        
```
* 404
* 403
* 401
* 500
* 200