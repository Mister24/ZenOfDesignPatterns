# ZenOfDesignPatterns

![Java](https://img.shields.io/badge/Java-8+-orange.svg)

> 基于《设计模式之禅》思路，用 Java 实现并演示常用设计模式的练习仓库。

## 项目简介
每个模式一个 package，包含完整的类结构与可直接运行的 `Main` 演示，帮助理解模式意图、角色划分与协作流程。

## 环境要求
- Java 8 及以上
- 无需构建工具，直接 `javac` 编译运行

## 目录结构（已实现模式）
```
zenOfDesignPatterns/src/
├── chain/       # 责任链模式（多级审批：一/二/三级 Handler 串联）
├── strategy/    # 策略模式（出行方式：飞机 / 火车 / 大巴 自由切换）
└── observer/    # 观察者模式（主题-观察者 注册 / 通知 / 注销）
```

## 运行方式
```bash
javac zenOfDesignPatterns/src/chain/*.java
java chain.Main
```

## 说明
- 个人学习项目。
- 仓库未声明开源协议（LICENSE）。
