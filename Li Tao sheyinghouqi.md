# 李涛简单摄影后期课笔记

## 课时9 清晰度锐化

1. 在基本参数设置里加一定的锐化，此时可能会提高曝光值，需要回退一点曝光值
2. 在全部处理结束，输出前做锐化。在细节标签里，这里需要加上蒙版，按住快捷键ALT，可以看锐化被加在什么地方。（高频处）

## 课时12 输出与文件夹结构

1. 相机端设置色彩空间为`Adobe RGB`而不是`sRGB`（应用在网络上）
2. 在bridge打开图片的格式也为`Adobe RGB`+`16位深度`
3. 输出打印级别图片（用bridge或者PS输出）都用`tiff`+压缩（LZW和ZIP都可以）+`Adobe RGB`+`16位`+不修改图片大小+默认ppi（300）
4. `ctrl+R`同时预览多张图片，可以批量输出
5. 输出网络级别：在tiff文件夹下输出+`JPEG`+质量（6、 8、 10）+`sRGB`+`8位`+调整图片大小（宽和高设置为2000，表示单边最大尺寸2000点）
   
## 课时14 二次构图2 垂直矫正

1. 图片在进入颜色处理之前，先进入`镜头矫正`，第一个选项`启动配置文件矫正`，第二个选项`删除色差`，第三个选项`手动`进行垂直/水平矫正
2. 然后进入`相机校准`，这里可以使用【风光】、【人像】等配置文件进行场景处理，比在相机端选择这些模式更好
3. 在做镜头【垂直/水平】矫正后，软件会自动缩放画面使之全屏，这时候进行`缩放`然后再进行裁剪