# v2hero 

1. 点击[![](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https://github.com/onplus/heroku_go-getting-started)创建HerokuAPP，配置服务器参数(appname和uuid，类似账号密码)
   ![create new app heroku](https://user-images.githubusercontent.com/31188782/33353392-905c3abe-d4e8-11e7-812a-866f95875ef9.png)

2. Fork本项目，然后Gihub授权登录[TravisCI](https://travis-ci.org/profile)，选择fork的项目

3. 在项目的settings设置Environment Variables：HEROKU_APPNAME，HEROKU_EMAIL和[Heroku_APIKEY](https://dashboard.heroku.com/account)
   
4. 查看HerokuAPP并重启一次，从logs确认启动成功

5. 配置V2Ray本地参数
   https://www.v2ray.com/ui_client/
   https://toutyrater.github.io/basic/vmess.html#客户端配置



### 实现参考

https://github.com/wangyi2005/v2ray

https://hub.docker.com/r/v2ray/official/

Heroku
https://devcenter.heroku.com/articles/container-registry-and-runtime

Travis-CI
https://docs.travis-ci.com/user/docker/
