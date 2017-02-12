## ZoomingImageBrowser

> 工作原理：采用UIScrollView加UIImageView来实现。因为UIScrollView 支持两个指头缩放，将UIIMageView作为UIScrollView的子view加到UIScrollView中，指定缩放UIscrollView时同时缩放UIImageView，即可实现图片的放大缩小。最后我们再单独给UIImageView加上双击手势。

> 1. 注意在手势缩放的时候实时更新布局
> 2. 注意在UIImage的setter方法里面重置UIScrollView的缩放比，并且重新计算UIImageView的frame

### 效果图
##### 不需要依赖框架即可集成的功能

> 
![photoBrowser.gif](http://upload-images.jianshu.io/upload_images/2473291-96280fd136949b39.gif?imageMogr2/auto-orient/strip)
