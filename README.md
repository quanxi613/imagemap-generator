# imagemap-generator
网上找的image map生成热区工具，放到本地方便访问

出处： http://imagemap-generator.dariodomi.de/


## 使用方法

1. 将本项目克隆到本地,浏览器打开index.html或者直接访问[http://qiudeqing.com/imagemap-generator/](http://qiudeqing.com/imagemap-generator/)
2. 在输入框输入图片地址或者拖拽本地图片到输入框
3. 等待图片加载后,鼠标移入图片区域会显示为十字架图标,依次点击热区图形的顶点,系统会自动计算区域并高亮,生成坐标代码.如需要生成矩形热区,在矩形左上角点击一下,然后在右下角点击一下即可
4. 需要添加多个热区时,点击下方菜单中的Add Area即可从新计算热区
5. 得到全部热区之后.下方会显示所有热区对应的area坐标代码.复制粘贴到项目源代码中即可使用


## 其他工具

[https://github.com/kemayo/maphilight](https://github.com/kemayo/maphilight)是imagemap 热区可视化工具,可以方便查看图片热区范围是否是需要的区域


## 注意事项

图片太大时拖拽会出错,建议图片不要太大,如果图片太大.推荐上传到服务器后输入绝对地址到输入框

