# Rust Web 开发项目

## 概述

这个基于 Rust 的 Web 开发项目综合了后端和前端组件，强调了 RESTful API 服务器的构建。本教程涵盖了各种功能，包括 TCP 服务器设置、HTTP 处理、Actix-Web 集成、sqlx 和 PostgreSQL 数据库操作、错误处理以及服务器改进。项目还探讨了前端开发，使用了传统的服务器端渲染（SSR）和 WebAssembly（Wasm），全部采用 Rust 编程语言实现。

## 后端开发

### 核心特性

- **TCP 服务器和 HTTP 处理：** 构建了基本的 TCP 服务器，实现了 HTTP 请求和响应处理，并为路由器（Router）、服务器（Server）和处理器（Handler）组件奠定了基础。
- **Actix-Web 集成：** 使用 Actix-Web 框架开发了基础服务器。
- **RESTful API 服务器：** 创建了一个具有健康检查、课程添加和各种查询功能的 REST API 服务器。数据存储在内存中。
- **sqlx 数据库集成：** 使用 sqlx 从数据库的 'Course' 表中查询数据。
- **PostgreSQL 数据库集成：** 继续对数据库的 'Course' 表进行 SQL 查询，并将数据源替换为 PostgreSQL 数据库。
- **错误处理：** 实现了错误处理机制以增强服务器的可靠性。
- **带有 PostgreSQL 的服务器改进：** 增强了现有服务器，重点关注了 PostgreSQL 数据库知识。

## 前端开发

### 核心技术

- **WebAssembly（Wasm）和服务器端渲染（SSR）：** 同时实现了传统的 SSR 用于 Web 应用和 Wasm 用于增强前端功能。

### 语言

- 完全采用 Rust 编程语言实现。

## 技术实施

- 每个组件的详细实施说明都在项目结构中提供。

## 技术总结

- **后端：** Actix-Web 框架、TCP 服务器、RESTful API 开发、sqlx 和 PostgreSQL 数据库集成。
- **前端：** 服务器端渲染（SSR）、WebAssembly（Wasm）、Rust 语言同时用于前端和后端。

## 入门指南

- 按照项目提供的每个组件的说明，深入了解项目的全貌。

## 注意

- 为了获得更有凝聚力的学习体验，建议全面了解整个项目。
- 前端和后端组件紧密集成，为 Rust 中的 Web 开发提供了整体视角。

## 文件夹树

```
|
├───db
│   └───src
├───s1
│   ├───http
│   │   └───src
│   ├───httpserver
│   │   ├───data
│   │   ├───public
│   │   └───src
│   ├───src
│   ├───tcpclient
│   │   └───src
│   └───tcpserver
│       └───src
└───ws
    ├───src
    └───webservice
        └───src
            ├───bin
            ├───db_access
            ├───handlers
            └───models
```

## Rust 版本

```
>> rustup --version

rustup 1.26.0 (5af9b9484 2023-04-05)
info: This is the version for the rustup toolchain manager, not the rustc compiler.
info: The currently active `rustc` version is `rustc 1.75.0 (82e1608df 2023-12-21)`
```