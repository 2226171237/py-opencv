# OpenCV-python3.6

# 教程参考：

* 天池AI学习：【视觉与图像】Python+OpenCV教程入门篇
* 讲师：EX2TRON
* 网站：https://tianchi.aliyun.com/course/courseDetail?spm=5176.12282042.0.0.1dce290a7knzyq&courseId=40992

# 章节介绍
## [chapter01](https://github.com/2226171237/py-opencv/blob/master/chapter01_%E5%AE%89%E8%A3%85opencv.ipynb):
* opencv-python安装与介绍
    pip install opencv-python
## [chapter02](https://github.com/2226171237/py-opencv/blob/master/chapter02_%E5%9B%BE%E5%83%8F%E8%BD%BD%E5%85%A5%E6%98%BE%E7%A4%BA%E5%92%8C%E4%BF%9D%E5%AD%98.ipynb):
* 图片得载入显示和读取
```
cv2.imread()
cv2.imshow()
cv2.imwrite()
```
## [chapter03](https://github.com/2226171237/py-opencv/blob/master/chapter03_%E6%89%93%E5%BC%80%E6%91%84%E5%83%8F%E5%A4%B4.ipynb):
* 打开摄像头

```
函数：cv2.VideoCapture(),cv2.VideoWriter()
视频播放 
视频录制
滑动条 cv2.createTrackbar()
```
## [chapter04](https://github.com/2226171237/py-opencv/blob/master/chapter04_%E5%9B%BE%E5%83%8F%E5%9F%BA%E6%9C%AC%E6%93%8D%E4%BD%9C.ipynb):
* 图像基本操作
```
访问和修改图像像素点的值
获取图像的宽高和通道数等属性
分离和合并图像通道
img[y,x]获取/设置像素点值，img.shape：图片的形状（行数、列数、通道数）,img.dtype：图像的数据类型。

img[y1:y2,x1:x2]进行ROI截取，cv2.split()/cv2.merge()通道分割/合并。更推荐的获取单通道方式：b = img[:, :, 0]。
```
## [chapter05](https://github.com/2226171237/py-opencv/blob/master/chapter05_%E9%A2%9C%E8%89%B2%E7%A9%BA%E9%97%B4%E5%8F%98%E6%8D%A2.ipynb):
* 图像颜色空间变换
```
函数
    cv2.cvtCOLOR()
    cv2.InRange()
颜色空间变换，如BGR<-->Gray，BGR<-->HSV等
追踪视频中特定颜色的物体

```

