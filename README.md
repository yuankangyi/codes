# codes
这个代码是用于打开大量图片，并通过移动鼠标，来获取图片多个角度的png.
具体来说，是通过3DMAX的一个轻量级软件打开一个.obj格式的卫星模型，然后通过截图的方式获取Png，然后移动鼠标使卫星模型旋转，再截图获取png，一共获取64张照片后，再打开下一个.obj模型。

window.exe是袁丰写的python打包后的程序，其作用是讲打开的模型窗口，固定到桌面的某一个位置，因为.obj模型在打开的时候，位置会发生变化，具体缘由不清楚，但这样就不方便我们截图，因此需要将窗口固定位置。
