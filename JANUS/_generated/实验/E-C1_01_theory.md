---
janus_generated: true
created: 2026-11-08
type: "experiment"
id: "C1_01_theory"
title: "C1_01_theory"
machine: "C1"
status: "已完成·本地结果"
progress: 100
tags:
  - "janus"
  - "experiment"
source: "科研OS/data/experiments.json"
related:
  - "[[X-C1]]"
  - "[[总览]]"
  - "[[E-C1_00_tests]]"
---

# C1_01_theory

> 由 `build_obsidian.py` 从业务真源派生 · **受管笔记，请勿手改**。
> 你的想法请写在 `JANUS/notes/` 下任意笔记，用 `[[E-C1_01_theory]]` 指回本页。

## 实验设置

- 目标：P1 逐方向 CSV 两块比例 s_O² / s_U² 与比值（纯后处理，分钟级）
- 所属机器 / 步骤：C1 / 1
- 设备 / 脚本 / 代码包：Intel Ultra 285V 32G 共享 / C1_01_theory.ps1 / 1105实验代码/JANUS_C1_Ultra285V.zip
- 预计耗时：几分钟
- 真源补录设置：待补录（`experiment_briefs.json` 无登记，不臆造超参）。

## 攻击 / 训练流程

- 攻击流程：待补录（真源未登记流程正文）。
- 训练流程：待补录（真源未登记流程正文）。

## 轮次阶段工作

- 进度 / 状态：100% / 已完成·本地结果
- 依赖步骤：C1_00_tests
- 闸门：待补录
- 阶段分工：待补录

## 预期结果

待补录（真源未登记量化预期与判定门槛）。

## 结果与分析

- 结果摘要：p1_two_block.json 已落盘（4879 B）。严格 Σ=s²H 不成立，A/B 两块各自保持比例系数，对应假设 2 的分块比例噪声。数值填入表 3 前须与论文口径复核。

- 证据：1105实验代码/JANUS_C1_Ultra285V/results/theory/p1_two_block.json



- [在 Folio 打开实验详情页](http://127.0.0.1:8765/%E7%A7%91%E7%A0%94OS/packages/experiments/C1_01_theory.html)

## 关系（有真源依据）

- [[X-C1]] · 版本归属（真源 versions）
- [[总览]] · 实验入口
- [[E-C1_00_tests]] · 步骤依赖（真源 depends_on）
