# Axelor 模块开发演示

此项目演示如何使用 Axelor Development Kit 框架进行快速数据库应用开发。

## 预先需求

* Java JDK 8
* PostgreSQL 9.6+ 或 MySQL
* Gradle

** 注意：由于 Axelor Development Kit 的 bug，本代码需要在 Linux/MacOS 下构建运行，在 Windows 平台上会有字符编码的问题。
Windows 10 用户建议使用 Windows Linux 子系统进行操作。**

## 运行

1. 为 PostgreSQL 数据库新建一个用户，并以此用户的身份创建一个空数据库
2. 修改 `src/main/resources/application.properties` 文件中的数据库连接参数为 1. 的设置。
3. 执行 `$gradle tomcatRun` 启动 Axelor。
4. 通过浏览器访问 `http://localhost:8080/my-axelor-app`
5. 初始用户名/密码为：`admin/admin`

## 作者及授权协议

作者：李屠户

本代码使用 AGPL 3.0 协议授权。
