---
janus_generated: true
created: 2026-11-08
type: "experiment"
id: "C1_02_pullback_fmnist"
title: "C1_02_pullback_fmnist"
machine: "C1"
status: "已完成·本地结果"
progress: 95
tags:
  - "janus"
  - "experiment"
source: "科研OS/data/experiments.json"
related:
  - "[[X-C1]]"
  - "[[总览]]"
  - "[[E-C1_00_tests]]"
---

# C1_02_pullback_fmnist

> 由 `build_obsidian.py` 从业务真源派生 · **受管笔记，请勿手改**。
> 你的想法请写在 `JANUS/notes/` 下任意笔记，用 `[[E-C1_02_pullback_fmnist]]` 指回本页。

## 实验设置

- 目标：FMNIST 回拉探针与理论常数（T3 轨迹的第三点）
- 所属机器 / 步骤：C1 / 2
- 设备 / 脚本 / 代码包：Intel Ultra 285V 32G 共享 / C1_02_pullback_fmnist.ps1 / 1105实验代码/JANUS_C1_Ultra285V.zip
- 预计耗时：0.5–2 h
- 真源补录设置：待补录（`experiment_briefs.json` 无登记，不臆造超参）。

## 攻击 / 训练流程

- 攻击流程：待补录（真源未登记流程正文）。
- 训练流程：待补录（真源未登记流程正文）。

## 轮次阶段工作

- 进度 / 状态：95% / 已完成·本地结果
- 依赖步骤：C1_00_tests
- 闸门：待补录
- 阶段分工：待补录

## 预期结果

待补录（真源未登记量化预期与判定门槛）。

## 结果与分析

- 结果摘要：T3_fmnist 下有 pullback.csv（33653 B）、theory_constants.json（3739 B）、checkpoint.pt 与 metadata.json。注意：第一轮理论常量的 μ_Q/ρ 公式已判定有误，须用第二轮新脚本重算后才能用于条件 (R)。

- 证据：1105实验代码/JANUS_C1_Ultra285V/results/T3_fmnist/pullback.csv



- [在 Folio 打开实验详情页](http://127.0.0.1:8765/%E7%A7%91%E7%A0%94OS/packages/experiments/C1_02_pullback_fmnist.html)

## 关系（有真源依据）

- [[X-C1]] · 版本归属（真源 versions）
- [[总览]] · 实验入口
- [[E-C1_00_tests]] · 步骤依赖（真源 depends_on）
