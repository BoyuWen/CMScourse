#MarkDown语法
---
##标题
- #一级标题
- ##二级标题
- ###三级标题
- ####四级标题
- #####五级标题
- ######六级标题

##段落
这是一段语句。  
这是第二段语句。

##强调
- *倾斜*
- **加粗**
- ***加粗倾斜***
- ~~删除~~
- `文本阴影`

##列表
###有序列表
1. 列表1
  1. 列表1.1
  2. 列表1.2
2. 列表2
3. 列表3


###无序列表
- 列表1
  - 次列表1
  - 次列表2
  - 次列表3
- 列表2
- 列表3

##链接
###内嵌链接:
- 外部链接:[这是我的Github网页] (http://www.github.com/boyuwen)
- 内部链接，链接仓库的其他文件[demo1] (相对路径)
- 内部链接，链接本文档的其它部分[代码块demo] (相对路径)

###引用链接:
- 外部链接:[百度]  
[百度]：http://www.baidu.com

##图片
###语法:
`![alt] (url "text")`
###实例:
![百度logo] (https://ss0.bdstatic.com/5aV1bjqh_Q23odCf/static/superman/img/logo/bd_logo1_31bdc765.png "logo")

##引用
###语法：
- 一重引用：`> text`
- 多重引用：`>>> text`

###实例：
> 这是一重引用  

——出自我 `打断引用要空出一行` 
>>>这是三重引用

##代码块
###行内代码：
- 这是一段代码：`System.out.println("Hello World!");`

###代码块：
```java
improt java.util.*;

public Main{
	public static void main(String[] args){
		System.out.println("Hello World!");
	}
}
```

##水平分割线
`---or***or___`
---
***
___

##HTML代码dmeo
`直接嵌入HTML代码：`
<p align='center'>这是一段居中的段落。</p>

##表格
| aaaaa | bbbbb | ccccc |
|  ---  | :---: |  ---: |
|   1   |   2   |   3   |

##GFM
###任务列表：
- [] 任务一，未完成
- [x] 任务二，已完成
###表情
`语法：:demo`
