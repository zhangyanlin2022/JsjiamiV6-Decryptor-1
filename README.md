# JsjiamiV6解密工具
* 使用 NodeJs 开发。
* 未使用外部库，轻量快捷。
* 简易的 [JavaScriptV6](https://www.jsjiami.com/) 解密工具。
* 仅支持使用 AutoJs配置 模式加密的JS文件。
## 使用方法
1. 在 [DecryptV6.js](https://github.com/NXY666/JavaScriptV6Decryptor/blob/master/DecryptV6.js) 的常量 FILE_NAME 中填写路径。
2. 运行该脚本。

## 输出结果
* encryptEdited1.js：去除全局加密
* encryptEdited2.js：去除函数加密
* encryptEdited3.js：去除if-else死代码
* encryptEdited4.js：16进制数字转10进制、['XXX']转.XXX.