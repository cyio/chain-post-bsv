# ChainPost
无需访问 memo.cash，就可以发 memo 的网页工具
完全开源，私钥只存储在用户浏览器端

## 特性：
* 合理的手续费。此页面使用了我 fork 的 [cyio/datacash: The simplest way to write data to Bitcoin Cash blockchain](https://github.com/cyio/datacash) 库，支持了按字节计算手续费。
* PWA 支持，缓存页面到本地，打开更快
* 简单的私钥管理，查看、记住

## 如何使用：
1. 设置私钥，从 memo 账户导出私钥，或使用新的私钥 （如果经常用，建议选择记住）
2. 写下你想说的话，点击发布。完。
