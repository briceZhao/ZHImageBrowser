## ZoomingImageBrowser

> 工作原理：采用UIScrollView加UIImageView来实现。因为UIScrollView 支持两个指头缩放，将UIIMageView作为子view加到UIScrollView，指定缩放UIscrollView时同时缩放UIImageView，即可实现图片的放大缩小。最后我们再单独给UIImageView加上双击手势。

### 效果图
##### 不需要依赖框架即可集成的功能
![pictureCycleDetector.gif](http://upload-images.jianshu.io/upload_images/2473291-905709598ec3efd4.gif?imageMogr2/auto-orient/strip)



![photoBrowser.gif](http://upload-images.jianshu.io/upload_images/2473291-96280fd136949b39.gif?imageMogr2/auto-orient/strip)

##### Github链接：https://github.com/briceZhao/ZoomingImageBrowser