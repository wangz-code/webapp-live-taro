## webapp-live-taro
 基于腾讯云微信直播小程序(live-pusher, live-player) taro 版本
 demo的界面太简洁了, 稍微优化一下 UI

## 需求
> 必须在小程序上发起直播, 推流, 等操作

> 必须在小程序上观看直播, 拉流, IM , 聊天, 等操作

> 直播间需要支持 加入购物车, 观看直播 ,观看PPT ,购买商品 等操作

## 分析

> 整体小程序使用 taro 开发, 毋庸置疑为了方便整合也是 taro( vue3 )

> 现有的轮子无法满足定制化的需求, 重写过程中可能会遇到无数的 bug, 层级穿透, 原生组件的渲染问题

