# proj87-picorio-rv64cpu

### 对开源CPU PicoRio处理器的软硬件协同优与扩展

### 项目描述

RISC-V 国际开源实验室（RIOS）的首个开源 RISC-V 架构微型计算机 PicoRio。PicoRio项目涵扩了对Chromium OS内核以及V8 JavaScript 引擎的RISC-V平台移植和支持。 可运行完整的Linux和FreeRTOS系统。PicoRio项目将于2021年完成ARM A75级别的芯片设计和验证，将用于 RISC-V 的平板电脑/笔记本电脑，其中所有应用程序软件和存储都在云中运行（类似 Chromebook）。

RIOS Laboratory：https://rioslab.org



本课题的目标是在 PicoRio 上面通过软件和硬件协同的方式，提升整体的系统性能和安全性。

### 项目奖励：
比赛优胜的团队不仅能获得本比赛所设立的奖项，并且有机会获得以下额外奖励：
* 将获得清华大学summer camp的实习机会，参加面试，争取清华大学研究生的保送名额。
* 与Google Skywater Open Foundry合作，免费提供芯片流片的机会。
* 将获得RISC-V创始人，图灵奖得主Dr. David A. Patterson本人的亲笔签名书一本。


### 所属赛道

2021全国大学生操作系统比赛的“OS功能设计”赛道



### 参赛要求

- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生（2021年春季学期或之后本科毕业的大一~大四的学生）
- 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
- 请遵循“2021全国大学生操作系统比赛”的章程和技术方案要求



### 项目导师

王翕

* gitlab https://github.com/

* email :xi.w@rioslab.org



### 难度

中等

### 特征

*开源硬件
*高性能处理器设计
*微架构信息安全
*操作系统协同


### 文档

*PicoRio Specification：https://gitlab.com/picorio/picorio-doc
*RISC-V Specification: https://riscv.org/technical/specifications/
*RISC-V Tools https://github.com/riscv/riscv-tools
*RISC-V GNU Toolchain:https://github.com/riscv/riscv-gnu-toolchain
*PicoRio RTL Repository: 参赛小组成员请联系导师获取代码访问权限

### License

开源协议 FreeBSD


## 预期目标

### 注意：下面的内容是建议内容，不要求必须全部完成。选择本项目的同学也可与导师联系，提出自己的新想法，如导师认可，可加入预期目标

### 第一题 CPU Design and Performance Optimizations on PicoRio

优化开源CPU PicoRio处理器的性能和设计，可实现的功能拓展包括:
*多发射 (Multi-issue)
*多核的缓存一致性设计 (Multicore Cache Coherence)
*非阻塞式缓存 (Non-blocking Cache)
*乱序执行 (Out-of-Order Execution)
*数据预取等等 (Data Prefetching, etc.)

将在FPGA上对扩展的PicoRio处理器之上运行Linux，并根据性能指标performance，power and die area来进行性能评价。 

将提供开源的RTL代码，完整PicoRoo工具链。

### 第二题 RISC-V Trusted Execution Environment (TEE) Design based on Physical Memory Protection Unit

*通过对PiciRio处理器微架构扩展实现基于RISC-V PMP unit的Enclave系统实现。在Enclave环境下支持基本的应用程序执行。
*利用Linux完成Untrusted OS环境以检测物理内存隔离（Physical Memory Isolation）的效果测试。
*硬件扩展根据性能指标 performance，power and die area来进行评价。
*Enclave的整体性能将和第一题所提交的处理器性能对比来判定安全扩展所带来的额外开销。

### 提交内容
*完整源代码和RTL综合结果
*Technical Report
*Runtime Test Evaluation

