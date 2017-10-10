## 文件规范

### styles
- _global.scss （编写全局基本共用样式）
- _variable.scss （变量 & mixin）
- _master.scss （主界面样式）
- _layout.scss （布局、版面样式）
- _font.scss（文字样式）
- _icon.scss（图标样式）
- _form.scss （表单样式）
- _theme.scss （主题样式）
- _mend.scss （补丁）
- _print.scss （打印样式）


## CSS书写顺序
1.	位置属性(position, top, right, z-index, display, float等)
2.	大小(width, height, padding, margin)
3.	文字系列(font, line-height, letter-spacing, color- text-align等)
4.	背景(background, border等)
5.	其他(animation, transition等)


## CSS书写规范
1.	两空格缩进
2.	段落之间留两空行，块之间留一空行
3.	每个一个选择器都独占一行，用逗号连接的并列选择器应在逗号处换行，以满足本条规则
4.	属性定义必须以分号结尾，并且另起一行
5.	选择器 和 “{”之间要有一个空格
6.	属性名 与 : 之间不空格，: 与属性值之间有一个空格
7.	选择器的嵌套层级尽量不大于5级
8.	使用css缩写属性，比如padding,margin,font等等
9.	font-weight总是使用数据normal=400, bold=700
10.	如非必要，尽量不使用 !important 声明
11.	去掉小数点前面的“0”
12.	0值除非必要，总是不带有单位
13.	文本内容尽量使用双引号包围
14.	url() 函数中的路径不加引号
15.	RGB颜色值尽量使用十六进制记号形式 #rrggbb，可以缩写时尽量使用缩写
16.	带有透明度的颜色信息使用rgba()
17.	媒体查询尽可能放在相关规则附近，以免被遗忘
18.	注释：确保代码能够自描述、注释良好且易于理解


## CSS的命名规范
1.	命名需尽量简短，可适度但不可过度简写，需要意义明确
2.	class名称中只能出现小写字母，连接以中划线 “-”
3.	不能用“_”命名class
4.	使用两个中划线“--”表示特殊化，如 .item-img--small
5.	状态类直接使用单词，如：.active, .hover, .checked
6.	使用 .js-* class 来标识行为（与样式相对），并且不要将这些 class 包含到 CSS 文件中
7.	使用“.icon-”为icon命名前缀
8.	同一个标签不要超过四个class组合使用


## css命名参考表
1.	布局类：header, footer, container, main,  content, aside, page, section
2.	包裹类：wrapper, wrap, inner
3.	区块类：region, block, box, column
4.	结构类：hd, bd, ft, top, bottom, left, right, middle, col, row, grid, span
5.	列表类：list, item, field
6.	主次类：primary, secondary, sub, minor
7.	大小类：s ( small ) , m ( middle ) , l ( large ) , xl
8.	状态类：active, current, checked, hover, fail, success, warn, error, on, off
9.	导航类：nav, prev, next, breadcrumb, forward, back, indicator, paging, first, last, menu
10.	交互类：tips, alert, modal, pop, panel, tabs, accordion, slide, scroll, overlay
11.	星级类：rate, star
12.	分割类：group, separate, divider
13.	等分类：full, half, third, quarter
14.	表格类：table, tr, td, cell, row
15.	图片类：img, thumbnail, original, album, gallery
16.	语言类：cn, en
17.	论坛类：forum, bbs, topic, post
18.	方向类：up, down, left, right
19.	页面类：login, register, setting, profile,  dashboard

### 常用布局参考：
