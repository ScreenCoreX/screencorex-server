# Screencorex Server

大屏后端服务项目，基于 Spring Boot 构建，提供高性能、可扩展的数据接口，支持大屏可视化应用的快速开发与部署。

## 主要特性
- RESTful API，支持多种数据格式
- 高性能、易扩展
- 支持多数据源接入
- 简单配置，快速部署
- 适配主流前端大屏框架

## 技术栈
- Java 17+
- Spring Boot
- Maven

## 环境要求
- JDK 17 及以上
- Maven 3.9 及以上
- 操作系统：Windows / Linux / macOS

## 快速启动
1. 克隆项目：
   ```bash
   git clone <your-repo-url>
   ```
2. 进入项目目录：
   ```bash
   cd screencorex-server
   ```
3. 构建并运行：
   ```bash
   ./mvnw spring-boot:run
   ```
   或在 Windows 下：
   ```cmd
   mvnw.cmd spring-boot:run
   ```
4. 默认服务端口：`8080`

## 目录结构
```
├── src/main/java/com/example/screencorexserver/         # 核心后端代码
│   └── ScreencorexServerApplication.java                # 启动类
├── src/main/resources/                                  # 配置与资源文件
│   ├── application.properties                           # 应用配置
│   ├── static/                                          # 静态资源
│   └── templates/                                       # 模板文件
├── src/test/java/com/example/screencorexserver/         # 测试代码
├── pom.xml                                              # Maven 配置
├── mvnw, mvnw.cmd                                       # Maven Wrapper
└── README.md                                            # 项目说明
```

## 常见问题
- 启动失败请检查 JDK 和 Maven 版本是否符合要求。
- 端口冲突可在 `application.properties` 中修改 `server.port`。
- 如需接入数据库，请在配置文件中补充相关信息。

## 许可证
本项目基于 Apache License 2.0 开源。

