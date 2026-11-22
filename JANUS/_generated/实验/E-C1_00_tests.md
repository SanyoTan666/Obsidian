---
janus_generated: true
created: 2026-11-08
type: "experiment"
id: "C1_00_tests"
title: "C1_00_tests"
machine: "C1"
status: "已完成·三行 PASS"
progress: 100
tags:
  - "janus"
  - "experiment"
source: "科研OS/data/experiments.json"
related:
  - "[[X-C1]]"
  - "[[总览]]"
---

# C1_00_tests

> 由 `build_obsidian.py` 从业务真源派生 · **受管笔记，请勿手改**。
> 你的想法请写在 `JANUS/notes/` 下任意笔记，用 `[[E-C1_00_tests]]` 指回本页。

## 实验设置

- 目标：全部单测 + R-gate 已知 Hessian 测试（T1_bitwise / μ_Q / gate 捕获率）
- 所属机器 / 步骤：C1 / 0
- 设备 / 脚本 / 代码包：Intel Ultra 285V 32G 共享 / C1_00_tests.ps1 / 1105实验代码/JANUS_C1_Ultra285V.zip
- 预计耗时：30–60 min
- 真源补录设置：待补录（`experiment_briefs.json` 无登记，不臆造超参）。

## 攻击 / 训练流程

- 攻击流程：待补录（真源未登记流程正文）。
- 训练流程：待补录（真源未登记流程正文）。

## 轮次阶段工作

- 进度 / 状态：100% / 已完成·三行 PASS
- 依赖步骤：无
- 闸门：待补录
- 阶段分工：待补录

## 预期结果

待补录（真源未登记量化预期与判定门槛）。

## 结果与分析

- 结果摘要：test_rgate_s0/s1/s2.json 三份全部 PASS:true，T1_bitwise 逐位一致；门控捕获弱方向 0.971–0.987、强方向 0.008–0.023。这是 G2/G3 带 JANUS+RG 列的前置闸门。
- 指标：`{"pass": [true, true, true], "T1_bitwise": true, "mu_Q_eta1": "0.664–0.726", "gate_captures_true_weak": "0.971–0.987"}`
- 证据：1105实验代码/JANUS_C1_Ultra285V/results/test_rgate_s0.json



- [在 Folio 打开实验详情页](http://127.0.0.1:8765/%E7%A7%91%E7%A0%94OS/packages/experiments/C1_00_tests.html)

## 关系（有真源依据）

- [[X-C1]] · 版本归属（真源 versions）
- [[总览]] · 实验入口
