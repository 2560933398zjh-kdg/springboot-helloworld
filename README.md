# web-ai-project01 — Maven 入门项目

包含一个纯 Maven 的 Java 入门项目 `mevan-project01`，用于学习 Maven 工程结构与基础用法。

## 子项目

### mevan-project01

最简单的 Java Maven 项目：`HelloWorld` 控制台输出示例。

- **技术**：Java 8 + 纯 Maven（无框架依赖）
- **结构**：

```
mevan-project01/
├── pom.xml                          # Maven 配置（Java 8）
└── src/main/java/com/itheima/HelloWorld.java
```

- **运行**：

```bash
cd mevan-project01
mvn compile        # 编译
mvn exec:java -Dexec.mainClass="com.itheima.HelloWorld"   # 或直接运行
# 输出 HelloWorld
```
