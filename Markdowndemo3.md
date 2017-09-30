# Markdowndemo3

## 水平分隔线demo

- 在HTML语法中有`<hr>（Horizontal Rule）`代表水平分隔线的意思。在Markdown中实现水平分隔线有三种方式
  - 一是用三个‘-’实现，如
  ---
  - 二是用三个‘*’实现，如
  ***
  - 三是用三个‘_’实现，如
  ___
## HTML代码demo

- **可以通过HTML语法实现更多的语法效果。**如可以借助HTML代码使文字或段落居中，如：  
`<p align = 'center'> hello World!</p>`
<p align = 'center'> hello World!</p>
- 也可以使用HTML中的语法`<！-- -->`注释，如：
<!-- 这是注释，这行文字会被忽略 -->
- 或者用HTML语法插入图片，如：  
`img src = 'http://img1.3lian.com/2015/a1/79/d/79.jpg'
<img src = 'http://img1.3lian.com/2015/a1/79/d/79.jpg'/>

## 表格demo

- 在Markdown语法中实现表格是十分简单且直观的。通过“|”和“-”来实现表格的竖线和横线，因为表格是由这些竖线和横线组成的。
- 表格里的文字默认是左对齐的，居中对齐是在横线中间加入两个冒号右对齐是在横线右边加一个冒号。如：  
| 这  | 是   | 表头 |
|----|:---:|-----:|
|cell1|cell2dticshihidh|celldgsfifoff3|
|** row2左对齐 ** |row2居中对齐|row2右对齐|
|图片|demo[百度]|![图片][logo]|
|row4|row4|row4|
- 精简表格，将左右两头的竖线去掉，效果一样  
 这  | 是   | 表头 
-----  |:---:|-----:
cell1|cell2dticshihidh|celldgsfifoff3
row2左对齐 |row2居中对齐|row2右对齐

## GFMdemo

- GFM（GitHub Flvored Markdown）语言，是指GitHub实现的具有自身特色的Markdown。在这里介绍两个与GitHub相关的语法
  - task list 任务列表,如下，在item前面加【 】+空格，效果如何checkbox，在【】中加x就代表在选择。如:
    - [x] task1
    - [ ] task2
    - [ ] task3
  - emoji 表情符两个冒号包围的表情字符可以显示出不同的表情
    - 笑脸 `：smile：`，:smile:  
    - 打钩:white_check_mark:  
  - 表情符号可以访问我在GitHub上找到的一个老师整理的表情符号的文档：
  	`https://github.com/guodongxiaren/README/blob/master/emoji.md`
  	
  	
<!-- 以下是本文档用到的链接 -->
[logo]:http://img15.3lian.com/2015/h1/310/d/113.jpg
[百度]:https://www.baidu.com
