# BiliVideoDecode
解密B站UWP下载的视频

这个工具用于B站UWP版本下载的视频进行解密\
使用PyQt构建UI具有良好的用户界面\

### 基本原理
B站UWP视频只是在视频开头添加了三个字节的ff，这导致你是用其他播放器进行播放时会无法解码\
这个工具只是简单地把前面三个字节的ff删掉了，如果以后B站修改了其他加密算法可能就无效了😂
### 使用教程
1、点击选择文件选择要解密的文件，可选择多个\
2、点击输出路径选择要输出的路径\
3、如果勾选了输出到原路径则会输出到原路径，工具会重命名不会覆盖掉原文件
