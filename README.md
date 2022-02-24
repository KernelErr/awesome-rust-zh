# Awesome Rust Zh

中文Rust社区资源汇总，[贡献指南](CONTRIBUTING.md)。欢迎加入[Rust中文社群](https://301.one/rustzhgroup)（飞书群聊）和小伙伴们探讨Rust。

![CC BY-SA 4.0](https://licensebuttons.net/l/by-sa/4.0/88x31.png)

本作品采用<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">知识共享署名-相同方式共享 4.0 国际许可协议</a>进行许可。

## 目录

- [书籍/教程/文档](#书籍教程文档)
  - [在线资料](#在线资料)
  - [实体书籍](#实体书籍)
  - [博客资源](#博客资源)
  - [其他资源](#其他资源)
- [库](#库)
  - [WebAssembly](#WebAssembly) 
  - [编程语言](#编程语言)
  - [GUI](#GUI)
  - [机器学习](#机器学习)
  - [操作系统](#操作系统)
  - [容器技术](#容器技术)
  - [前端相关](#前端相关)
  - [后端相关](#后端相关)
  - [异步框架](#异步框架)
  - [文件系统](#文件系统)
  - [其他库](#其他库)
- [软件](#软件)
  - [数据库](#数据库)
  - [其他软件](#其他软件)
- [社区](#社区)

## 书籍/教程/文档

#### 在线资料

- [Rust 程序设计语言](https://kaisery.github.io/trpl-zh-cn/)
- [Rust语言开源杂志（2021）](https://rustmagazine.github.io/rust_magazine_2021/)
- [Rust 秘典（死灵书）](https://nomicon.purewhite.io/)
- [rCore-Tutorial-Book 第三版](https://rcore-os.github.io/rCore-Tutorial-Book-v3/)
- [RustPrimer](https://rustcc.gitbooks.io/rustprimer/content/)
- [Rust 文档网](https://rustwiki.org/)
  - [Rust 程序设计语言](https://rustwiki.org/zh-CN/book)
  - [通过例子学 Rust](https://rustwiki.org/zh-CN/rust-by-example)
  - [Rust 参考手册](https://rustwiki.org/zh-CN/reference)
  - [Rust Cookbook](https://rustwiki.org/zh-CN/rust-cookbook)
  - [Rust 版本指南](https://rustwiki.org/zh-CN/edition-guide)
  - [Rust 速查表](https://cheats.rs/)
- [Rust 编码规范 中文版](https://github.com/Rust-Coding-Guidelines/rust-coding-guidelines-zh)
- [Rust 中的异步编程](https://huangjj27.github.io/async-book/index.html)
- [编写 Rust 语言的操作系统](https://github.com/rustcc/writing-an-os-in-rust)
- [rustlings - Rust小练习](https://github.com/rust-lang/rustlings)
- [rust-course - Rust语言圣经](https://github.com/sunface/rust-course)

##### 2021 年 Rust 生态版图调研报告

- [2021 年 Rust 生态调研报告 | 星辰大海 【上篇】](https://mp.weixin.qq.com/s/SN0it6uHf2mv0O_KYTooUg)
- [2021 年 Rust 生态调研报告 | 星辰大海 【下篇】](https://mp.weixin.qq.com/s/Q9leuL0mkykw28_tOjKhaQ)

##### RustFriday 线上沙龙

- [RustFriday 飞书群线上沙龙 第二十期 - 定制rustc_lint](https://www.bilibili.com/video/BV1oL411G758/)

##### Rust源码阅读俱乐部

- [GitHub repo](https://github.com/ZhangHanDong/rust-code-reading-club)
- [第一期：名称解析](https://www.bilibili.com/video/BV1534y1Z7Bv)
- [第二期：类型推断 和 Tokio 源码 Part1](https://www.bilibili.com/video/BV1uT4y1R75U)

#### 实体书籍

- Rust权威指南
- Rust编程：入门、实战与进阶
- Rust编程之道

#### 博客资源
- [fasterthanli - Rust 长篇博文](https://fasterthanli.me/articles)
- [Jon Gjengset - Rust 超长视频 up 主](https://www.youtube.com/c/JonGjengset/playlists)

#### 其他资源

- [Rust国内源（字节）](https://rsproxy.cn/)
- [Rust 开发者学习路线图](https://github.com/anshulrgoyal/rust-web-developer-roadmap)
- [Rust 安全顾问数据可视化](https://rsadv.lirui.tech/)

## 库

#### WebAssembly

- [wasmtime - 独立Wasm JIT运行时](https://github.com/bytecodealliance/wasmtime)
- [WasmEdge - 边缘计算优化的轻量级、高性能、可扩展的 WebAssembly (Wasm) 虚拟机](https://github.com/WasmEdge/WasmEdge)
- [wasmer - 支持WASI和Emscripten的WebAssembly运行时](https://github.com/wasmerio/wasmer)
- [wit-bindgen - `wit`语言绑定生成器](https://github.com/bytecodealliance/wit-bindgen)

#### 编程语言

- [pua-lang - Rust编写的PUA语言](https://github.com/flaneur2020/pua-lang)
- [chen_lang - 用 Rust 写的 一个小编程语言](https://github.com/zuisong/chen_lang)

#### GUI

- [slint - 高效GUI开发套件](https://github.com/slint-ui/slint)
- [iced - 跨平台GUI库，受Elm启发](https://github.com/hecrj/iced)
- [egui - 易用的即时GUI库](https://github.com/emilk/egui)
- [flutter-rs - 使用Rust和Flutter构建好看的桌面端App](https://github.com/flutter-rs/flutter-rs)

#### 机器学习

- [MegFlow - 快速视觉应用落地](https://github.com/MegEngine/MegFlow)

#### 操作系统

- [Linux - 为Linux内核添加Rust支持](https://github.com/Rust-for-Linux/linux)
- [rCore - 清华uCore系统的Rust版本](https://github.com/rcore-os/rCore)
- [core-os-riscv - 一个Rust编写的类xv6系统](https://github.com/skyzh/core-os-riscv)
- [zCore - 用Rust语言重写的Zircon微内核](https://github.com/rcore-os/zCore)

#### 容器技术

- [Shallow Container](https://github.com/KernelErr/shallow-container)
- [krustlet - 在本机运行WebAssembly程序](https://github.com/krustlet/krustlet)

#### 前端相关

- [Vue Compiler in Rust](https://github.com/HerringtonDarkholme/vue-compiler)
- [Yew - 现代Rust/Wasm多线程前端框架](https://github.com/yewstack/yew)
- [Robinson - 玩具Web渲染引擎](https://github.com/mbrubeck/robinson)
- [sycamore - 基于Rust和WebAssembly的响应式web库](https://github.com/sycamore-rs/sycamore)

#### 后端相关

- [poem - 简单易用功能丰富的后端框架](https://github.com/poem-web/poem)
- [axum - 基于Tokio/Tower/Hyper的现代化Web框架](https://github.com/tokio-rs/axum)
- [hyper - Rust HTTP库](https://github.com/hyperium/hyper)
- [actix-web - 强大且速度极快的web框架](https://github.com/actix/actix-web)
- [Rocket - 简单快速的web框架](https://github.com/SergioBenitez/Rocket)
- [Perseus - 支持服务器渲染和静态生成的web开发框架](https://github.com/arctic-hen7/perseus)

####  异步框架

- [monoio - 一个基于 io-uring 和 thread-per-core 模型 Rust Runtime](https://github.com/bytedance/monoio)
- [glommio - 支持io_uring的线程与核绑定异步框架](https://github.com/DataDog/glommio)

####  文件系统

- [procfs - 解析proc下的各种文件](https://github.com/eminence/procfs)

#### 其他库

- [variant-counter - 优雅的Enum计数库](https://github.com/Folyd/variant-counter)
- [CaoE - 当父进程退出杀死所有子进程](https://github.com/wayslog/caoe)
- [udbg-base - udbg基础库带有跨平台内存读写等功能](https://github.com/udbg/udbg-base)

## 软件

#### 数据库

- [tikv - 分布式KV数据库](https://github.com/tikv/tikv)
- [pelikan - Twiiter统一缓存后端](https://github.com/twitter/pelikan)
- [sled - 嵌入式数据库](https://github.com/spacejam/sled)
- [indradb - 图数据库](https://github.com/indradb/indradb)
- [materialize - SQL数据流数据库](https://github.com/MaterializeInc/materialize)
- [noria - 高性能数据流数据库](https://github.com/mit-pdos/noria)
- [lucid - 提供HTTP API的高性能KV数据库](https://github.com/lucid-kv/lucid)
- [parity-db - 实验性区块链数据库](https://github.com/paritytech/parity-db)
- [skytable - 快速安全持久化的NoSQL数据库](https://github.com/skytable/skytable)

#### 其他软件

- [RustDesk - 远程桌面软件](https://rustdesk.com/)
- [Rust Search Extension - 在地址栏快速搜索 Rust 文档、crates、内置属性、官方书籍和错误码等](https://github.com/huhu/rust-search-extension)
- [ESSE - 加密对称会话引擎](https://github.com/CympleTech/esse)
- [Clean DNS with eBPF - 基于 Rust + eBPF 丢弃 GFW DNS 污染包](https://github.com/ihciah/clean-dns-bpf)
- [meilisearch - 快速实时搜索引擎](https://github.com/meilisearch/MeiliSearch)
- [bottom - 跨平台可视化资源管理器](https://github.com/ClementTsang/bottom)
- [paste - 云粘贴板](https://github.com/yanfenglee/paste) [在线链接](http://p.gluc.cn/)
- [lapce - 强大快速的代码编辑器](https://github.com/lapce/lapce)
- [gyroflow - 使用相机的陀螺仪数据稳定录像](https://github.com/gyroflow/gyroflow)
- [AppFlowy - 开源的Notion替代](https://github.com/AppFlowy-IO/AppFlowy)

## 社区

- [Rust语言中文社区](https://rustcc.cn/)

