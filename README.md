# deep-learning-pre-tutorials
深度学习环境配置及远程工具教程

## VScode 远程连接方法

1. 安装Remote-SSH扩展库。
![extension image](https://github.com/BIT-zhwang/deep-learning-pre-tutorials-release/blob/master/resource/1.png)
2. 连接

安装插件后重启VScode，可以在侧边栏找到远程连接的button

![remote connect image](https://github.com/BIT-zhwang/deep-learning-pre-tutorials-release/blob/master/resource/3.png)

点击远程连接图标，在Tag栏中点击`+`，在弹出框里输入ssh连接命令：
`ssh username@140.143.22.244`

![ssh image](https://github.com/BIT-zhwang/deep-learning-pre-tutorials-release/blob/master/resource/4.png)

其中，username是你的用户名，ip地址是你服务器的ipv4地址。

选择配置文件保存地址，推荐保存到当前用户地址下

![config image](https://github.com/BIT-zhwang/deep-learning-pre-tutorials-release/blob/master/resource/5.png)

3. 选择连接路径

![address image](https://github.com/BIT-zhwang/deep-learning-pre-tutorials-release/blob/master/resource/6.png)

右击SSH Targets，选择在当前窗口中打开服务器，输入密码

![address image](https://github.com/BIT-zhwang/deep-learning-pre-tutorials-release/blob/master/resource/9.png)

根据提示选择想要打开的地址。

![address image](https://github.com/BIT-zhwang/deep-learning-pre-tutorials-release/blob/master/resource/8.png)