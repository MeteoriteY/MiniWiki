# Aircraft(Airplane) Maintenance Manual 航空器维护手册

>以下内容基于Airbus A380 的AMM手册。

[TOC]

## 手册使用场合
- 无论针对安装在飞机上或飞机系统上的设备工作时；
- 无论飞机位于停机坪还是机库中 ；
- 无论想要实施什么类型的维护操作。

## AMM 适用范围
### AMM手册提供**系统和结构相关**的：
- 说明和原理[D&O](Aviation:Abbreviation:D&O)
- 维护程序[MP](Aviation:Abbreviation:MP)

### 适用范围包括：
- 定期维护[MPD](Aviation:Abbreviation:MPD)
- 非计划维护检查[AMM](Aviation:维修类手册:AMM)
- 非计划维护程序（[MMEL](Aviation:Abbreviation:MMEL)、[CDL](Aviation:Abbreviation:CDL)、[TSM](Aviation:维修类手册:TSM)）

### 不适用范围：
- 飞机的结构修理应该使用结构修理手册[SRM](Aviation:维修类手册:SRM)。
- 内场的部附件维护应该使用部附件修理手册[CMM](Aviation:维修类手册:CMM)。

## 手册的主要结构

### 主要分为两个部分：
1. 手册的前言部分（Manual Front Matter）
2. 手册的具体章节内容（[用ATA章节排序](Aviation:维修类手册:常用ATA章节)）

### 各章节的结构：
1. 系统的说明和原理[D&O](Aviation:Abbreviation:DO)
2. 相关维护程序[MP](Aviation:Abbreviation:MP)

### 章节号的构成：

Chapter章节 - Sub-system子系统 - Sub-sub-system次子系统 - Component部件号

示例： 28-21-51

细化分类：每个 AMM 的标题按照具体需要进一步划分为页面工作包PB(Page Blocks)

### 页面工作包和页码的关系
| 英文名称 | 中文名称 | 页面包 | 页码 |
| ------ | ------- | ----- | ---- |
| Description & Operation | 说明和原理 | PB 001 | 001-199 |
| Standard Maintenance Practices | 标准维护施工 | PB 201 | 201-299 |
| Task Related to Servicing | 相关勤务工作 | PB 301 | 301-399 |
| Removal or Installation | 拆卸和安装 | PB 401 | 401499 |
| Adjustment or Test | 调节和测试 | PB 501 | 501-599 |
| Inspection or Check | 检查 | PB 601 | 601-699 |
| Cleaning or Painting | 清洁和标图 | PB 701 | 701-799 |
| Approved Repair | 其他批准修理 | PB 801 | 801-899 |
| Deactivation or Reactivation | 失效和恢复 | PB 901 | 901-999  |

### 前言内容
- AMM 手册中相关有效的临时修订页清单（TR List）
- 按照 ATA 排序的页面变更信息清单（Highlight）
- 手册使用说明——相关定义等（Introduction - Description & Operation）
  1. Manual Breakdown & Numbering System
  2. How to use the Manual
  3. AMTOSS Numbering
  4. SB & COC display
  5. FIN Numbering
  6. ...
- 客户机队系列号/生产系列号关联表（Fleet No./MSN Cross-reference table）
  - FSN - Fleet Serial Number - 机队有效性系列号
  - MSN - Manufacturer Serial Number - 生产系列号
- 基于客户提供信息的服务通告状态信息（Service Bulletin List）
  - POST SB 用"C"代表「已完成」
  - PRE/POST SB 用"S"代表「计划已完成」
  - 营运人根据 SB 产生相应的工程指令文件（EO）
- 航空公司特定的技术参数，反映客户属性的数据（Customer Originated Change [COC] List）
  - 客户指定变更信息单
  - 客户属性数据描述了航线特定技术解决方法
- 在同一个索引下的构型缺损清单和主最低设备清单（Deactivation/Reactivation Index）
  - 该目录指引提供CDL/MMEL项目之间的交叉参考和相应的维护操作任务号
  - 包括功能失效操作程序和功能恢复程序指引

### 查找CDL/MMEL操作程序
> 仅针对Airbus系列飞机机型

在AMM手册中，通过CDL/MMEL搜索引擎快速查找相关操作程序，使用该操作程序的原因通过CDL/MMEL的项目号说明。

## 手册详解

### 说明和原理[D&O](Aviation:Abbreviation:DO)
可以获取的信息：
- 系统的概述
- 部件位置
- 系统/部件的描述
- 供电源（如果可用）
- 相关系统的接口（如果可用）
- 运行/控制和指示
- 系统自测试

这些内容将包含理解该系统的相关必要信息。

### 有效性的指示和确认
- ** ON A/C ALL 该工作任务对机队所有飞机有效
- ** ON A/C 051-099,101-199 该子任务对于机队系列号 051-099 和 101-199有效
- ** ON A/C 201-299 该子任务对于机队系列号 201-299 有效
- ** ON A/C ALL (Subtask) 该子任务对于所有飞机有效
