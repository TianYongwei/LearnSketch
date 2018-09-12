# Sketch 使用总结

> 要常回顾概念，最重要的。

目录
- [组件概念说明](#组件概念说明)
- [组件下的操作](#组件下的操作)
- [全局操作](#全局操作)
- [组件杂项](#组件杂项)
- [可直接使用的设计内容](#可直接使用的设计内容)
- [插件相关](#插件相关)

## 组件概念说明

> Sketch中都有什么概念，分别是什么

Sketch 本身

- Sketch 是一款*矢量*处理软件，不擅长处理位图。
- Sketch 的特点是可以高效的完成原型设计和高保真原型。

File

- 我们使用Sketch本质上市在操作Sketch File.
- 使用Sketch也是从新建File开始
- 文件以 .sketch 结尾
- 这与其他任何软件都一样

Template

- Template是一种特殊的File
- 可以将自己制作的File保存成Template
- Sketch软件自身携带了若干常用Template
- 从template新建（[The Best Hidden Features In Sketch | Meng To - UI/UX Designer](http://blog.mengto.com/the-best-hidden-features-in-sketch/)）

画布（Convas）

- 一个Sketch File可以包含多张画布，即一个文件可有多个Page
- 一张画布对应一个Page
- 画布可以无限延伸

图层（Layer）

- 画布上的元素都是图层
- 比如新建的矩形，原型，甚至导入一张图片
- 图层都在画布上

分组（Group）

- 可将两个甚至更多图层合并成一个“组”
- 组是图层的集合

画板（Artboard）

- 因为画布是可以无限延伸的，画板是在画布上划分出的一块固定面积的区域
- 画板是一种特殊的组
- 需要在指定区域内绘图的时候，用到画板


## 组件下的操作

File & Template 

- 可将普通files设置为Template
- 文件只能保存，不能导出成图片

图层

- 可锁定
- 可调整顺序
- 可重命名
- 当图层完全被覆盖使用 option 键
- 可分组（command + G）
- 分组可嵌套
- 可隐藏
- 图层可搜索 （command + F）
- 布尔运算
    - 合并（Uunion）
    - 减去顶层（Subtract）
    - 保留重叠（Intersect）
    - 减去相交 (Difference)
- 拷贝样式（类似格式刷）
- 可以导出CSS, 甚至是Less和Sass, 需要设置
- 自动横向纵向均匀布局
- 按住shift能等比缩放
- 双击图形直接进入钢笔工具模式
- 钢笔工具，快捷方式 V
- 变形工具（Transform）
    - 能快速变成梯形
- 蒙版（Mask）
    - 快速制作原型头像
- 剪刀工具（Scissors）
    - 裁剪线段
- 旋转复制
    - 制作六个一样的圆形，组成一个圆形
- 渐变工具
    - 线性
    - 对称
    - 可以叠加效果

分组

- 分组完成之后点击右下角的“make exportable”，之后分组文件夹上就会出现slice小刀的样式，但这里的小刀跟slice的图标没什么关系，虽然很相似。

## 全局操作

- Symbol（符号文件）—— Sketch 中的全局图层变量,达到复用的目的
    - create symbol
    - dettach symbol
- Styled Text : 类似Symbol
- 只有三种组件可导出成图片
    - *slice*之后的图层
    - *make exportable*之后的分组
    - Artboard
- 可减小导出源文件尺寸（Reduce File Size）
- 文本工具
    - 第一个工具：Text
        - 可调整字体
        - 字重
        - 大小写
        - 颜色
        - 字间距
        - 行距
        - 透明度
        - 描边
        - 阴影
        - Text on Path
        - 字体变为轮廓
        - ...
    - 第二个工具：Font（都在工具栏）
- 位图操作
    - 选区工具
        - 裁剪
        - 剪切
        - 填充颜色
    - 魔棒工具
        - 同上...
    - 退出位图编辑 esc
    - 色相处理
        - 灰度
        - 明度
        - 对比度
- 原型功能（交互：热区和链接）
- 自动保存
- 可查看所有自动保存版本

## 组件杂项

- 导出图层和slice的区别 [Sketch - Make Exportable](https://sketchapp.com/docs/exporting/exporting-layers/)

## 可直接使用的设计内容
- Template：模板，创建文件的快捷方式
    - Android Icon Design
    - iOS App Icon
    - iOS UI Design
    - Material Design
    - Web Design
- 画板 (Artboard)
    - Apple Devices
        - iPhone7 
        - iPad
        - Apple Watch
        - Apple TV
    - Material Design
        - Mobile
        - Tablet 9'
        - Tablet 7'
        - Desktop

## 插件使用

## 插件开发（暂时不考虑了）

## 参考

[Sketch - Make Exportable](https://sketchapp.com/docs/exporting/exporting-layers/)