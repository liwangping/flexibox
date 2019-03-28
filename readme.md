适配于各个屏幕的大小，然后整体思想为，将屏幕宽度分成100份，然后每rem为实际手机屏幕宽度除以
目前Flexible会将视觉稿分成100份（主要为了以后能更好的兼容vh和vw），而每一份被称为一个单位a。同时1rem单位被认定为10a。针对我们这份视觉稿可以计算出：

1a   = 7.5px
1rem = 75px 
那么我们这个示例的稿子就分成了10a，也就是整个宽度为10rem，<html>对应的font-size为75px：


设备像素比 = 物理像素/设备独立像素

学习链接https://www.w3cplus.com/mobile/lib-flexible-for-html5-layout.html