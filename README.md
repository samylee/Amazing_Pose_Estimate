# Amazing_Pose_Estimate
CPU Real-time Amazing Pose Estimate
# FIND CODE  
https://blog.csdn.net/samylee/article/details/112056728  
# Test steps
## step1
Download 'third_part dll' and put it to current directory. [BaiDu Cloud](https://pan.baidu.com/s/1X9-pDypbj-TJMFxiSqow9A) Password: 4wpj
## step2
Set parameters:
`Amazing_Pose_Estimate.exe min_size test_type img_path`
```cpp
like:  Amazing_Pose_Estimate.exe 256 imgdir /img/path/test_imgs  (for imgdir)
or:    Amazing_Pose_Estimate.exe 256 video test.avi  (for video)
or:    Amazing_Pose_Estimate.exe 256 video 0  (for usbcam)
```
# Algorithm efficiency
| Image Size | min_size | CPU(i7-9700K) Speed/FPS |
|:------:|:------:|:------:|
| any resolution  | 256 | 30ms/33.3 |
| any resolution  | 368 | 60ms/16.6 |
# Example result
![](results/0.jpg)
# Reference
https://blog.csdn.net/samylee
