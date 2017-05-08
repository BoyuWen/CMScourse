# 1. Github

1. github是什么

	GitHub is a web-based Git or version control repository and Internet hosting service. It offers all of the distributed version control and source code management (SCM) functionality of Git as well as adding its own features. It provides access control and several collaboration features such as bug tracking, feature requests, task management, and wikis for every project.

2. git是什么

	Git (/ɡɪt/[8]) is a version control system (VCS) for tracking changes in computer files and coordinating work on those files among multiple people. It is primarily used for software development,[9] but it can be used to keep track of changes in any files. As a distributed revision control system it is aimed at speed,[10] data integrity,[11] and support for distributed, non-linear workflows.
Git was created by Linus Torvalds in 2005 for development of the Linux kernel, with other kernel developers contributing to its initial development. Its current maintainer since 2005 is Junio Hamano.
As with most other distributed version control systems, and unlike most client–server systems, every Git directory on every computer is a full-fledged repository with complete history and full version tracking abilities, independent of network access or a central server.
Like the Linux kernel, Git is free software distributed under the terms of the GNU General Public License version 2.

3. github的好处(转)

	1). 可以为项目建立静态主页(即gh-pages分支), 也可以建立命名特殊的repo(http://username.github.io)来建立个人静态网站
    
	2). 依赖Github来管理插件
    
	3). 可以作为自己的简历 
    
	4). 用Gists管理代码片段，而且可以内嵌到网页
    
	5). 托管编程环境
    
	6). Github API  你可以用Github API做很多事情: 用github issues系统来做评论系统(petal，comcom ) ，用Github的markdown接口来渲染markdown，用github的oauth来做第三方登录..
    

4. github的优势
	开源(公有), 能够支持http(s), 能在线编辑, 仓库托管.

5. 通过github年度报告让你记忆最深刻的信息由哪些
	技术因开源而美丽, 科技因交流而进步, 合抱之木生于毫末.

6. github上有可以个人账号 还可以有( 组织 )账号.

7. github上面的两个组成要素是什么
	人 / 组织、仓库 / 项目.

8. github上两个重要页面
	登录页面、个人主页.

9. 主页菜单都包含什么
	Github要素、Overview(个人信息、主要仓库、活跃度信息)、Repositories(自己的或参与的仓库)、Stars、Watch、Followers、Following、Github数字仪表盘.

10. 仓库的心跳线代表什么
	该仓库过去一年的活跃程度.

11. star的作用是？
	star喜欢的项目.

12. fork的作用是？
	fork并pull为他人项目打补丁.

13. watch的作用是？
	关注的意思, 有动态及时汇报.

14. 搜索结果分别有哪些类别
	范围、内容、页面、资料.

15. 你在github上挖到什么宝
	项目、人、资料.

	
## Github问题集（2）

13.	个人主页上的“+”下拉菜单可创建的四种类别分别有？分别的意思？
	--`new repository`, `import repository`, 	`new gist`, 			`new organization`.
	--建立新仓库,		  导入仓库,			    数据的粘贴和引用,	       创建新的组织.

14.	如何能将仓库中的html文件直接解析成页面？
	--将链接粘贴进: <http://htmlpreview.github.com/>

15.	如何删除仓库
	--在该库的settings里的底部有删除.

16.	Bash是什么操作系统的命令
	--Unix家族的.

17.	Pwd是什么命令
	--查看当前目录.

18.	Cd是什么命令
	--切换当前目录.

19.	Echo是什么命令
	--响应, 亦可用来创建文本文件.

20.	配置git用户名的命令
	--`git config --global user.name 'a'`

21.	配置邮箱的命令
	--`git config --global user.email "15732115701@163.com"`

22.	命令行换行方式
	--字符\

23.	命令行终结方式
	--Ctrl + c, Ctrl + d(2者有所不同, 不在这细说)

24.	使用命令行比GUI方式有何优势
	--根本上: 一些功能在GUI中是无法实现的, 
		其次:	命令行的效率要高于GUI.

25.	提交到本地仓库时为什么有暂存区
	--作为缓存, 提高了效率,
	细化一次提交, 划分版本, 多一层确认保障.

26.	新建代码仓库的命令
	--`github-create REPO_NAME`

27.	git clone [url] 这个命令的作用是
	--将url对应的仓库拷贝到本机目录下.

28.	添加指定文件到暂存区的命令
	--`git add NAME_OF_FILE`.

29.	删除工作区文件，并且将这次删除放入暂存区的命令
	--`git rm [file1] [file2] ...`

30.	改名文件，并且将这个改名文件放入暂存区的命令
	--`git mv [file-original] [file-renamed]`

31.	提交暂存区到仓库的命令
	--`git commit -m "XXXX"`, 
	或 git commit 后进入记事本输入相应的"XXXX" 

32.	直接从工作区提交到仓库的命令
	-- `git add NAME_OF_FILE | git commit -m "SOME_MESSAGE"`

33.	显示变更信息的命令
	--`git status`

34.	查看历史信息的命令
	--`git log --follow [file], git whatchanged [file]`

35.	Commit的意义是
	--提交.

36.	Pull的意义是
	--拉取文件.

37.	Push的意义是
	--上推文件.
	
	
	
# 2. Markdown

1. Markdown是什么: 
	--一种多用于写作的轻量级标记语言.
2. Markdown的特点: 
	--语法简单格式多, 使写作的人更关注于文字本身而非格式.
3. Markdown的用途: 
	--用于进行文本编辑, 样式修饰.
4. Markdown的编辑工具: 
	--MaHua, 简书, 小书匠编辑器, Cmd Markdown, FarBox, Sublime Text 2, Atom, Github.
5. Markdown的区块元素和区段元素分别包含哪些: 

| 区块元素   | 区段元素                                                   |
|:-------:|:-----------------------------------------------------------:|
| 段落和换行  | 链接 |
| 标题     | 强调    |
| 区块引用 | 行内标记 |
| 列表    | 插入图片    |
| 代码区块    |      ...                                     |
| 分割线 | ... |
| pip2    | ...    |
