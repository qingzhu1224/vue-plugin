1. npm init

2. npm login / npm publish

3. You do not have permission to publish "npmtest". Are you logged in as the correct user? 
错误输出内容

[html] view plaincopyprint?
npm ERR! publish Failed PUT 403  
npm ERR! code E403  
npm ERR! You do not have permission to publish "npmtest". Are you logged in as the correct user? :  
出现原因：所要publish的包的name和npmjs网上已经发布的包的名字重复，所以收你没有权限发布这个名字的包。（简单解释就是你想要的名字被别人抢先注册了）
解决方法：找到package.json文件，把name的值换掉。如果还出现上述错误就是还是重名的，继续换！


4. https://www.cnblogs.com/chengzp/p/7757839.html

5. https://juejin.im/post/58d9aae02f301e007e8ee278

6. https://www.cnblogs.com/luozhihao/p/7414419.html
