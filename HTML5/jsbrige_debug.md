#JSBrige Debug手册#
##JSbrige 开发需要解决什么问题##

由于JS会和页面嵌入的容器打交道（跳转等）,所以在开发的时候强依赖于手机端的千牛容器。随着客户端请求API的JS开放,数据开始走JSBrige,而手机端容器非常难以开发调试,这就使得开发千牛退化到了最原始的方式alert;

本方案就是为了无缝解决对手机端容器强依赖的问题,让程序可以跑在chrome等桌面浏览器里,同时又不影响JS brige的native API请求的调用。

##JSBrige Debug方案的原理##
