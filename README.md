
### 脚本已被微软积分红字警告限制，请谨慎使用吧   
警告可能和添加的随机数字有关，已删除该功能，并添加大量搜索关键字   
### 每天打开自动搜索获取积分   
### 不需要安装任何环境，你只需要微软microsoft edge浏览器，登录微软账号      
脚本分为电脑版和手机版   
用微软edge浏览器打开,即可运行        
电脑版可以一直打开，每天8点后自动延时刷    
---手机版区别就是字体大一点    
关键字可自己添加修改   
每隔一段时间自动搜索关键字，10秒自动关闭已打开窗口   
只刷搜索分，  
每日活动和签到什么的分没有，这种手动刷吧   

居然有人用，那我写个说明吧  
### 你需要修改为自己的浏览器指纹  

我有写注释，就是网址搜索关键字后面带的一堆东东，不然没有积分  
这个指纹好像每个电脑都不一样  

手机端也要改  
手机版可以用分享链接的方式获取网页连接  

//
//举例，下面我搜索关键字积分, 积分后面的所有东西就是我们要的东西，  
//其中&FORM=ANSPA1&PC=ESBXSP这个东西应该最重要  
//https://cn.bing.com/search?q=积分&cvid=8c50072b399147d49aa6772b9869c9ef&aqs=edge.0.69i59j0j69i59j0l6.803j0j1&pglt=171&FORM=ANSPA1&PC=ESBXSP

请自己修改该处为你电脑的浏览器指纹，用你自己的浏览器搜索的结果网址获取  

根据上面搜索获取的网址，修改下面这个extend变量的内容  

复制下来就好了  
`
var extend = "&cvid=8c50072b399147d49aa6772b9869c9ef&aqs=edge.0.69i59j0j69i59j0l6.803j0j1&pglt=171&FORM=ANSPA1&PC=ESBXSP";
`
