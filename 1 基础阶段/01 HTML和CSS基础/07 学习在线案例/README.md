# 1 常见的图片格式

* jpg图像格式：jgp（jpeg）对色彩的信息保留较好，高清，颜色较多，产品类的图片经常使用jpg格式。
* gif图像格式：gif格式最多只能存储256色，所以通常用来显示简单图形及字体，但是可以保存透明背景和动态效果，实际经常用于一些图片小动画效果。
* png图像格式：是一种新兴的网络图形格式，结合了gif和jpg的优点，具有存储形式丰富的特点，能够保持透明背景。如果想要切成背景透明的图片，请选择png格式。
* psd图像格式：是Photoshop的专用格式，里面可以存放图层、通道、遮罩等多种设计稿。对前端来说，最大的优点，可以从上面复制文件、获取图片、测量大小和距离。

# 2 学成在线案例的目的

![学成在线案例](images/学成在线案例.png)

* 典型的企业级网站。
* 目的是为了整体感知企业级网站布局流程，复习前面学习的知识。



# 3 准备工作

* 学成在线psd源文件。
* 开发工具 = PS（切图）/cutterman插件 + vscode （代码） + chrome（测试）。



# 4 案例准备工作

* 本次采取结构和样式相分离的思想：
* ①创建study目录文件夹，用于存放页面相关的内容。
* ②study目录内新建images文件夹，用于保存图片。
* ③新建首页index.html（网站的首页统一规定为index.html）。
* ④新建style.css样式文件。本次采用外链样式表。
* ⑤将样式引入到index.html页面中。
* ⑥样式表中写入清除内外边距的样式，来检测样式表是否引入成功。



# 5 CSS属性书写顺序

* 建议遵循以下顺序：
* ①布局定位属性：display / position / float / clear / visibility / overflow（建议 display 第一个写，毕竟关系到模式）
* ②自身属性：width / height / margin / padding / border / background
* ③文本属性：color / font / text-decoration / text-align / vertical-align / white- space / break-word
* ④其他属性（CSS3）：content / cursor / border-radius / box-shadow / text-shadow / background:linear-gradient …



























