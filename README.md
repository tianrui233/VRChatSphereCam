## 它能实现怎样的功能？
它可以让你在VRChat中录制360度的全景视频
 
## 什么原理？
正方体有6个面，所以它有6个摄像头分别用来获取不同方向的画面然后通过shader合到一起~
 
## 它会给我和其他玩家带来什么影响？
只要离得不是太近就没有问题...毕竟它是个shader，离近了就是“糊脸shader”
除此之外没啥负面影响了，尽情体验吧~

## 我要怎么把它加到我的avatar里？
很简单，在[releases](https://github.com/tianrui233/VRChatSphereCam/releases)里下载scam.unitypackage，导入后按照常规的方法把它当作可固定在世界位置的avatar道具处理即可
 
## 在游戏里要怎么操作？
通过圆盘开关控制，先打开“全景相机”把立方体移动到你想要放置的位置之后打开“位置锁定”开关
![GIF动图](https://user-images.githubusercontent.com/37788769/162582757-9f89afaf-72f7-4e92-96bb-81104072732e.gif)

然后打开vrchat官方的直播相机，并且把摄像头的位置修改为世界位置（world）
并把它塞到立方体里
![GIF动图](https://user-images.githubusercontent.com/37788769/162582699-d842f321-41c4-4fee-b2a4-fa6f4e63095b.gif)

立方体内部是透明的，所以不会被遮挡。在这之后，打开电脑上的屏幕录制工具录制全景视频吧~
 
推荐使用显卡配套的程序录制视频，可以节省不少性能开销，4k分辨率建议把码率设置在50000kbp/s
## 还有什么需要注意的吗？
# 清 晰 度 ！
①录制的清晰度取决于你电脑显示的分辨率大小（可以超分辨率），我就是用2k显示器录制的4k视频
![截图（加载不出来就算了）这个也不是很重要](https://img.gejiba.com/images/ac40e42b63a9eff422cea9cbccd6d7ad.png)

通常情况下在显卡驱动程序里面有相关设置，别调太高，不然硬件设备也会吃不消

②除此之外还需要在unity里修改前、后、左、右、上、下这六个面的分辨率
![我用的4096的清晰度..3070ti有点吃力了](https://s1.ax1x.com/2022/04/10/LFwD6P.png)


****
# 详细的教程近期会在[bilibili@欧阳大鸽子](https://space.bilibili.com/338134956)和Github上发布
