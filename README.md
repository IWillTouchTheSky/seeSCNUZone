# seeSCNUZone
存放SCNUZone的最新代码，文件已加密

#### 2018年7月24日 星期二

1.修复了清除缓存后登陆进来读取不到已填写过的数据的问题<br>
2.将队伍详情页面纯学号的完善成了头像+姓名<br>
3.修改了队伍分享海报的内容<br>
待解决问题：添加队伍时，如果填写的学号还没有注册要提示，得等师兄把api写出来才能做

#### 2018年7月25日 星期三

1.名片页面，默认填写计算机学院时会undefined，已修复
2.扫小程序码进入以后，没有返回到主页的按钮，影响用户体验，已修复
3.按钮可以多次点击问题，所以给每个按钮的点击事件都加了wx.showloading，wx.hideloadinga，点击后锁定用户行动，直至按钮事件完成，已修复
4.修改了证书页面的一些文字
5.修复了“我的收藏”页面“队伍收藏”滑动删除无法使用的bug
