# qn
七牛相关
![](https://img.shields.io/badge/%E4%B8%83%E7%89%9B%E4%BA%91%E5%AD%98%E5%82%A8-me%20%20%7C%20Api-brightgreen.svg)
![](https://img.shields.io/badge/qn-me%20%20%7C%20Api-orange.svg)

参考：
http://blog.csdn.net/netdxy/article/details/50507161
修改七牛官网的demo



1. 上传只需要 key(文件上传后用于查找的名字) 、token 、file 就可以了，当然还需要(http://upload.qiniu.com/) 和上传空间

2. 只有当没有设置 key  时，才可以通过  hash 访问，一般都是domain+key ，即上传空间加key值
