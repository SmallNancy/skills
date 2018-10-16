### 后端
  https://github.com/truechain/truechain-task-platform
#### 1、导入源文件 
- 刚开始导入时选择import project然后按照
- https://www.cnblogs.com/wangcp-2014/p/8125063.html

![](https://github.com/SmallNancy/skills/blob/master/imgs/importSource.png)

#### 2、点击右边的MavenProject,该目录下面有四个工程，然后点击每个工程下面的Lifecycle的install命令打包该工程，我的在打包过程中有两个包没有下载下来
- 如果你也遇到这个错误就到群里面下载然后放到repository相应的目录下
 server  maven分别   Lifecycle install 
 启动   TruechainTaskPlatformApplication
- mvn install   缺失包导入

![img](https://github.com/SmallNancy/skills/blob/master/imgs/settingMVN.png)

 
 
 ### 端口号
 - task_front[分支manage,修改端口8088]-->nginx[/admin，端口80]-->task_admin[8081]
 
 ### 修改host,用SwichHost
 - 127.0.0.1 www .1 www.phptrain.cn
 
 ### 前端
 - 修改index.js 端口号为  8088
 - 下载地址github.com\truechain\task-front  master 分支
 - 在task-front目录下执行npm install
 - 修改前端github.com\truechain\task-front\config的index.js的端口号
 - 启动npm run dev。
 - 启动nginx、redis服务器
