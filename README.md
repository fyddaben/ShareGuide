# ShareGuide

> Twitter, Facebook ，社交分享整理


## 'Facebook'  social plugins
> [刷新工具](https://developers.facebook.com/tools/debug/og/object/)
### 1. 评论
> 通过facebook账号，评论当前网页所发生的内容

[TouchMe](https://developers.facebook.com/docs/plugins/comments)

- 还可以通过fb工具。管理评价内容，排序，设置黑名单的用户或词汇。

###2. 嵌入公共推送

> 在自己的网页上面，展示'Facebook' 公共页面的内容

[TouchMe](https://developers.facebook.com/docs/plugins/embedded-posts)
- 可以不断更新中奖名单之类的，需要随着活动进行，不断更新的内容

###3. Page Plugin
> 更详细的展现'fb' 公共账号的相关信息

[TouchMe](https://developers.facebook.com/docs/plugins/page-plugin)

###4. 点赞按钮
> 针对某个页面点赞，并分享，预览显示的内容来自页面的og:title等标签

[TouchMe](https://developers.facebook.com/docs/plugins/like-button)
#### 建议
- 1.各个国家，地区的首页，完善 title,description,image等信息
- 2.单品页面，title或者fb:description 能够写清，商品价格，名称，图片等信息

###5. 分享按钮
> 分享某个页面，预览显示的内容来自页面的og:title等标签

[TouchMe](https://developers.facebook.com/docs/plugins/share-button)

###6. 与友分享
> 发送某个页面，并评价，给指定好友

[TouchMe](https://developers.facebook.com/docs/plugins/send-button)
###7. 订阅
> 订阅某个fb公共账号
[TouchMe](https://developers.facebook.com/docs/plugins/follow-button)

## Facebook Api

###1. 'Login'

[TouchMe](https://developers.facebook.com/docs/facebook-login/overview/)

- 默认权限包括, public_profile(Your name, user id, username, profile picture, gender and network in order to identify you), user_friends and email
###2. Share

[TouchMe](https://developers.facebook.com/docs/sharing/web)
- 一个页面，指定分享不同的内容
- 向某人发送网址

## Twitter 

>[刷新工具](https://cards-dev.twitter.com/validator)

###  卡片

>  类似fb的分享网址原理，在目标网页的源代码加入meta标签，标示twitter要抓取的内容

[TouchMe](https://dev.twitter.com/cards/getting-started)

- 和fb一样采用og标签。需要额外添加几个twitter:card属性

### 时间线等

>  时间线，喜欢，列表，搜索，推文集等内容

[TouchMe](https://twitter.com/settings/widgets/new)

### 自定义按钮
> 分享链接，关注标签，提及等
[TouchMe](https://about.twitter.com/zh-hans/resources/buttons#tweet)

### API 自定义分享

> 主动分享twitter内容
[TouchMe](https://dev.twitter.com/web/tweet-button/web-intent)

- 利用window.open的方式
