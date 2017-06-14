# 应用构造服务

Build Server为UAP Studio集成开发环境的“应用构造工具”提供支持服务，开发人员通过UAP Studio集成开发环境访问WebServies服务器，通过WebServies服务启动构建服务命令。移动平台维护人员通过web对移动平台进行维护，支持构造android、IOS应用。

![](/articles/build/6-/images/image39.png)

开发人员在UAP Studio集成开发环境内，通过“窗口”→“首选项”→“UAP-Studio集成开发环境”→“UAP Mobile”→“Build Server”，可以在开发端对BuildServer提供的构造服务进行集成配置。如下图：

![](/articles/build/6-/images/image40.png)

当开发人员完成移动应用的开发工作后，可以非常方便的使用UAP Studio集成开发环境进行移动应用构建。而构建生成的移动应用原生工程及原生安装包，会直接自动的下载到本地工作空间的工程目录下。

![](/articles/build/6-/images/image41.png)

默认的原生安装程序路径为“【工作空间】\【项目名称】\【模块名称】\native\ 【Android或者IOS】\【模块名称】\bin”。

![](/articles/build/6-/images/image42.png)
