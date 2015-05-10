# imagemap-generator
网上找的image map生成热区工具，放到本地方便访问

出处： http://imagemap-generator.dariodomi.de/

替换思路：

上传图片方法需要上传到服务器，繁琐速度慢，优先考虑改进逻辑为本地文件拖拽作为输入

1. 监听url输入框的拖拽事件，读取文件为data url设置输入框内容，实现本地文件拖拽使用
2. 使用默认功能：上传图片到cdn然后输入地址到url输入框

