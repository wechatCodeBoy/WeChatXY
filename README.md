# 最新微信ipad_7.04协议，功能更完善、稳定不易掉线。可以测试demo或api接口。请联系qq：3226944661
可实现微信80%功能；支持62数据登录、扫码登录、A16登录、收发朋友圈、查看朋友圈、微信建群、微信拉人进群、微信公众号阅读、微信消息收发、微信附近的人定位、微信添加好友、分享小程序、微信加粉、微信收藏、微信标签等<br/>
协议源码使用c#进行开发，开发环境为VS2017 .net framework 4.6.1 <br/>
# 接口地址
http://120.79.47.194:22222/swagger/ui/index#/
# 使用说明
1.通过/api/Login/GetQrCode接口获取二维码，可以设置代理IP，如没有，可前三个参数都设置为""
2.去http://imgbase64.duoshitong.com/进行base64转码，生成二维码图片
3.扫码登陆，之后调用/api/Login/CheckLogin/{uuid}，传入上个接口生成的Uuid，会返回wxId和用户信息
4.后续通过wxId进行其他接口的调用
# 接口文档
![demo1](https://github.com/weixinbao/WeChatXY/blob/master/API.png) <br/>
# 声明
仅供自己学习研究使用，引起任何法律纠纷概不负责
# QQ交流群
<a target="_blank" href="https://jq.qq.com/?_wv=1027&k=5UQXBEr">微信mac/ipad/android协议QQ群</a><br/>
![demo2](https://github.com/weixinbao/WeChatXY/blob/master/QQ.png) <br/>

