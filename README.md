南阳市微信前端项目
=============

### 已知bug
- 注册还是需要验证码
- 启动流程中，有几项不能用，提交数据应该是没有问题的，应该是后端的问题


### 一些说明
- 第一次注册登录完，进到首页之后会获取个个项目的启动流程按钮，存入 localStorage ，如果有新的流程按钮添加进去，需要用户注销登录一次才能获取。这么做的原因是你们的服务器实在太慢了。

- 项目已经压缩过了，在 build 文件夹中，拷贝 build 文件夹下的所有文件就可以用了
