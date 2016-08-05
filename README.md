# js_encryption

一般来说，js 都是用混淆压缩方式，防君子不防小人。而要交给浏览器运行，不能解密，就没法运行。

但随着 Node 大行其道，JS 使用越来月光，加密成为一种需求，也许以后 js 运行，会由浏览器提供解密，类似黑盒，能运行但代码未知。

关于 js 加密，有如下网络探究内容，可参看：

- https://www.zhihu.com/question/28468459
- http://www.cnblogs.com/mq0036/p/4983858.html

下面只是收集下最浅显常用的 JS 加密手段，用作学习之用

## 其他参考

- [https://github.com/webcoding/JS_Encryption_App]()
- [https://github.com/webcoding/hieroglyphy]()

## 常见加密方法（加密文件参见 crypt）

- base64加密 `var b = new Base64(); b.encode('string'); b.decode('str');`
- md5加密 `var hash = hex_md5(str);`
- sha1加密(据说这是最安全的加密) `var sha = hex_sha1(str)`
