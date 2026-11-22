---
janus_generated: true
created: 2026-11-08
type: "experiment"
id: "G2_B06_fldetector"
title: "G2_B06_fldetector"
machine: "G2"
status: "已回传·部分失败"
progress: 40
tags:
  - "janus"
  - "experiment"
source: "科研OS/data/experiments.json"
related:
  - "[[X-G2]]"
  - "[[总览]]"
---

# G2_B06_fldetector

> 由 `build_obsidian.py` 从业务真源派生 · **受管笔记，请勿手改**。
> 你的想法请写在 `JANUS/notes/` 下任意笔记，用 `[[E-G2_B06_fldetector]]` 指回本页。

## 实验设置

- 目标：B06 补充实验：FLDetector 附录行的独立复核与失败根因定位
- 所属机器 / 步骤：G2 / 7
- 设备 / 脚本 / 代码包：3080 Ti 12G / 16G RAM / B06 手工三车道并行 / 实验报告/B06_FLDetector_20261107.zip
- 预计耗时：31 min
- 真源补录设置：待补录（`experiment_briefs.json` 无登记，不臆造超参）。

## 攻击 / 训练流程

- 攻击流程：待补录（真源未登记流程正文）。
- 训练流程：待补录（真源未登记流程正文）。

## 轮次阶段工作

- 进度 / 状态：40% / 已回传·部分失败
- 依赖步骤：无
- 闸门：修复后须用新结果目录重跑，不要与本次失败目录混用
- 阶段分工：待补录

## 预期结果

待补录（真源未登记量化预期与判定门槛）。

## 结果与分析

- 结果摘要：FedAvg 三个攻击全部跑满 80 轮，BA 攻击末 26.94% / 62.38% / 72.61%；FLDetector 三个运行均在第 11 轮崩溃，CSV 只有 10 行。包内含代码、日志、运行台账与逐轮 JSON。
- 指标：`{"fedavg_ba_end": {"BadNets": 0.2694, "DBA": 0.6238, "Neurotoxin": 0.7261}, "fedavg_ma_final": {"BadNets": 0.9081, "DBA": 0.907, "Neurotoxin": 0.9172}}`
- 证据：实验报告/B06_FLDetector_20261107.zip



- [在 Folio 打开实验详情页](http://127.0.0.1:8765/%E7%A7%91%E7%A0%94OS/packages/experiments/G2_B06_fldetector.html)

## 关系（有真源依据）

- [[X-G2]] · 版本归属（真源 versions）
- [[总览]] · 实验入口
