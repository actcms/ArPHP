说明：扩展（包括WEB端扩展及一些类库扩展）目录

##
Ext

类库扩展
包含分页，图片缩放，二维码生成等

use : copy 至 项目目录 Ext 下边。

##
Seg
arSeg 函数配合自定义开发的html seg标签 实现同一块html代码的多重复利用实现快速开发，并且改善了模板嵌入php代码的难读的乱麻格局，使后台开发人员专助于功能的实现
配合相关的js插件，做到真正的一行php代码 ，完成一大块html + js 的功能，快速高效的
重用性开发。简单又不失高雅。

Seg\Html
常用的 html快速导入
Seg\Redirect
跳转页面自定义
Seg\Sys
系统默认实现的Seg标签
可以 动态的加入 css ，js代码。

其他的相关js插件，如弹出层layer,百度editor, 上传uploadify, 日历插件，配合自定义开发的地址，分类选择插件，简直好用到爆。（loader.seg集合了相关插件,调用的时候php就可以加载相关的js css 代码）

使用：拷贝 Seg目录至最外层Public目录中（与public.config.php同级）
