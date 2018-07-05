在浏览器输入地址会发生什么：

1. 语法解析网址
2. 浏览器在本地查询本地的cache
3. DNS解析（解析出域名对应的IP）
4. 连接服务器，tcp/ip连接服务器
5. 发送http请求
6. 接收http服务器请求
7. 如果connection不是keep-alive
8. 写cache，将能缓存的内容缓存

http request：

- 请求头
	- http请求方法
	- http协议
- http头
	- User-Agent
	- Accept
	- 。。。
- 请求体
	- 一般只有POST有


