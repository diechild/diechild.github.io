## 欢迎来到我的主页

李杰 软件工程 请多多关照
## 小组作业
#### 文字说明

Download Files用例图说明：
作者：李杰,葛洲宇
用例图建模过程分析：
一：根据上述的Download Files中的功能分析，对其进行如下描述 Files Manage中总共有以下的几大用例：
1.查找文件（Search Files）
2.下载文件（Download Files）
3.克隆或下载文件（Clone or Download）
4.源文件下载（Raw）
5.桌面打开（Open  in  Desktop）
6.Zip下载（DwonloadZip）
其中Download Files中主要有两大参与者：
1 用户（User）
2管理员（Administrator） 
二：模型分析
1.管理员（Administrator）和用户（User）都共同有下载文件（Download Files）
2.下载文件（Download Files）的下载之前应该有查找文件（Search Files）固然有依赖关系;下载文件（Download Files）分为两种，分别是克隆或下载文件（Clone or Download）和源文件下载（Raw），存在的是泛化关系。
3.   克隆或下载文件（Clone or Download）中又分为桌面打开（Open  in  Desktop）以及Zip下载（DwonloadZip）两种方式；
三．模型建立： 
1.用户（User）和管理员（Administrator）都共同指向下载文件（Download Files）
2.下载文件（Download Files）指向查找文件（Search Files），为依赖关系;
3.克隆或下载文件（Clone or Download）和源文件下载（Raw）共同指向下载文件（Download Files）并且是泛化关系；
4.桌面打开（Open  in  Desktop）以及Zip下载（DwonloadZip）指向克隆或下载文件（Clone or Download），并且是extend关系；
