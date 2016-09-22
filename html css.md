#HTML
##1.定义：超文本标记语言
##2.常用标签：h p a img ul li link span input table
##3.选择器：# id class 
####选择器格式：选择器{
    属性名：属性值；
}
##4.属性：# id class src href alt
##5.格式：英文状态下编写，！后按Tap键直接生成，基本格式如下：
####<!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>Document</title>
    </head>
    <body>
        hello html
    </body>
    </html>
##6.标签的分类及属性：
###块元素：独立成行，可以设置宽高，包括：h,p,ul ,li
###行内元素：不独立成行，可不以设置宽高，包括：a,span
###行内块元素：不独立成行，可以设置宽高，包括：img   input
##7.常用快捷键：
###ctrl+[]:集体缩进
###ctrl+shift+D：复制整句文字
###ctrl+Z：撤销前一步操作
###ctrl+Y：取消撤销
###Alt+shift+x：同时打开x个窗口
###Alt+Fn+F3：全部选中
###ctrl+F:查找文件
###windows+D:返回桌面
###windows+R:运行
###windows+L:锁屏
###windows+E:我的电脑
###ul>li*x后，直接Tap键即可生成ul下x个li的格式
###.header后，直接Tap键等价于class名为header的容器<div class="header"></div>
#CSS
##1.定义：层叠样式表
##2.选择器：id class 元素 层级 *通配符
###选择器权重：id(100)>class(10)>标签（1）
##3.盒模型：外边距：margin ；内边距：padding ；边框：border ；宽度：width；高度 height
##4.常用属性：
###text-align:center  :行内元素居中
###background-color:背景色设置
###background-image:url(images/bg1.jpg) ：加背景图片
###font-size:设置字号大小，单位为像素
###argin:0 auto :块元素居中
###list-style:none:ul下的li去掉前面的点
###float:left  :左浮动
###line-height:文字行高，文字垂直居中
###text-decoration:none :去掉a标签的下划线
###display:block :标签变成块元素
###border-radius: 1px:设置圆角
###border:border-none：去掉边框
###outline: none  ：去掉点击的边框
###cursor:pointer:光标变成手状
###overflow: hidden; 自动隐藏超出部分 
####子集加margin-top作用在父集上，对父集加overflow: hidden
###overflow: auto;多下拉框
###菜单置顶：position：fixed
###绝对定位，参照body标签：
####position: absolute;
            top:0;
            left: 0;
###相对定位，参照原文档流所在位置：position: relative;
###固定定位，参照浏览器固定：position: fixed;
###.box:hover{
            background-color: #fff;
        }  伪类选择器：鼠标移动到处有下划线
###z-index: 999：垂直向前
###*{
            margin: 0;
            height: 0;
        } *为通配符选择器，选择所有标签，此代码实现清除页面边距
###&nbsp:空格
###insert:切换光标
###一个容器宽度=border+padding+width
###不定宽元素居中：块元素若不设置宽高会被里面的元素撑开，若里面元素浮动则不占位，需将里面元素清浮动才可以
####<style type="text/css">
        .clear{
            clear:both;
        }
    </style>
    <div class="clear"></div>
##5.宽度自适应：header平铺，background-repeat: repeatX,content内容：margin:0auto
##6.表单
###标签<form action=""></form>
###提交表单三种方式如下：
####<input type="image">
####<input type="button">
####<input type="submit">
###表单样式：
####<input type="text">文本 
####<input type="button">按钮  
####<input type="checkbox">复选框
####<input type="radio">单选框
####<input type="text" placeholder="search..."> 
