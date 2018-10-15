### 后端
- 新建含有源code maven 
- mvn install 
 server  maven分别   Lifecycle install 
 启动   TruechainTaskPlatformApplication
 
 ### 端口号
 - task_front[分支manage,修改端口8088]-->nginx[/admin，端口80]-->task_admin[8081]
 
 ### 前端
 - 修改index.js 端口号为  8088
 - 下载地址github.com\truechain\task-front  master 分支
 - 在task-front目录下执行npm install
 - 修改前端github.com\truechain\task-front\config的index.js的端口号
 - 启动npm run dev。
