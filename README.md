# qn
七牛相关
![](https://img.shields.io/badge/%E4%B8%83%E7%89%9B%E4%BA%91%E5%AD%98%E5%82%A8-me%20%20%7C%20Api-brightgreen.svg)
![](https://img.shields.io/badge/qn-me%20%20%7C%20Api-orange.svg)

参考：
http://blog.csdn.net/netdxy/article/details/50507161
修改七牛官网的demo



1. 上传只需要 key(文件上传后用于查找的名字) 、token 、file 就可以了，当然还需要(http://upload.qiniu.com/) 和上传空间

2. 只有当没有设置 key  时，才可以通过  hash 访问，一般都是domain+key ，即上传空间加key值


### qq.md可以直接下载到本地，就是一个html，这个名字是qq，其实和qq一点关系没有，就是一个名字；平时需要上传图片、视频和音频时直接打开，会有一个按钮，选择图片就行，如果图片大于6M等待一会，这部分使用的上传空间由七牛免费提供

### 具体使用时，将刚刚显示在 input里面的url直接复制到 src 中就可以了 ，涉及到base64的话，也很简单，project中有代码

### 像现在每天需要图床的时候，我会选择七牛直接上传，简单方便，另外几个案例都可以直接使用，下载下来就可以，里面的代码我都改过，样式也更好看一点，涉及到视频的话，与图片做相同处理，无任何区别（具体参考我的个人博客，均采用七牛）
