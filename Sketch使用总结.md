## Sketch 使用总结

> 要常回顾概念，最重要的。

### 一、概念说明

Sketch

- Sketch 是一款*矢量*处理软件，不擅长处理位图。
- Sketch 的特点是可以高效的完成原型设计和高保真原型。

面板

- 顶部：常用工具栏
- 左侧：图层列表
- 右侧：编辑器
- 中间：工作区

功能列表

- 插件管理
- 减小导出源文件尺寸（Reduce File Size）
- 页面尺寸设置，方向
- 可以定制工具栏
- 按住shift能等比缩放
- 只有四个图形有快捷键
- 图形可以调整点的数量 变成多个角
- 双击图形直接进入钢笔工具模式
- 钢笔工具，快捷方式-V,(点击那里？)
- 布尔运算
    - 合并（Uunion）
    - 减去顶层（Subtract）
    - 保留重叠（Intersect）
    - 减去相交 (Difference)
- 变形工具（Transform）
    - 能快速变成梯形
- 蒙版（Mask）
    - 快速制作原型头像
- 剪刀工具（Scissors）
    - 裁剪线段
- 旋转复制
    - 制作六个一样的圆形，组成一个圆形
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
- ✨ Symbol（符号文件）—— Sketch 中的全局图层变量,达到复用的目的
    - create symbol
    - dettach symbol
- ✨ Styled Text : 类似Symbol
- 渐变工具
    - 线性
    - 对称
    - 可以叠加效果
- 拷贝样式（类似格式刷）
- 原型功能（交互：热区和链接）
- 可以导出CSS, 甚至四Less和Sass, 需要设置
- 自动横向纵向均匀布局
- 从template新建（[The Best Hidden Features In Sketch | Meng To - UI/UX Designer](http://blog.mengto.com/the-best-hidden-features-in-sketch/)）
- 有自动保存设置
- 可查看所有自动保存版本
- 导出图层和slice的区别 [Sketch - Make Exportable](https://sketchapp.com/docs/exporting/exporting-layers/)

组件概念

- Page：Sketch 中逻辑上相关但是维度不同的内容
- Template：模板，创建文件的快捷方式
    - Android Icon Design
    - iOS App Icon
    - iOS UI Design
    - Material Design
    - Web Design
- 图层：
    - 可锁定
    - 可调整顺序
    - 可重命名
    - 当图层完全被覆盖使用 option 键
    - 可分组（command + G）
    - 分组可嵌套
    - 可隐藏
    - 图层可搜索 （command + F）
- 右侧图层编辑器
    - 角度
    - 尺寸
    - 翻转
    - 圆角
    - 透明度
    - 填充颜色
    - 描边
        - 颜色
        - 粗细
    - 阴影
    - 高斯模糊
- 画布 (Convas): 无限大小
    - 不在画布上的组件无法导出
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
    - 可快速复制画板（command + D）
- Sketch File
    - Pages
        - page1：画布（convas）概念
        - page2
        - page3
            - artboard1：画板（artboard）概念
            - artboard2
                - layer1-图层（layer）概念
                - layer2-可以是形状矩形三角形等
                - layer3-也可以是slice图层
- 分组完成之后点击右下角的“make exportable”，之后分组文件夹上就会出现slice小刀的样式，但这里的小刀跟slice的图标没什么关系，虽然很相似。