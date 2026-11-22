---
janus_generated: true
created: 2026-11-08
type: "experiment"
id: "G2_06_fldetector"
title: "G2_06_fldetector"
machine: "G2"
status: "部分失败·上游缺陷"
progress: 40
tags:
  - "janus"
  - "experiment"
source: "科研OS/data/experiments.json"
related:
  - "[[X-G2]]"
  - "[[总览]]"
  - "[[E-G2_04_mirage_fixed]]"
---

# G2_06_fldetector

> 由 `build_obsidian.py` 从业务真源派生 · **受管笔记，请勿手改**。
> 你的想法请写在 `JANUS/notes/` 下任意笔记，用 `[[E-G2_06_fldetector]]` 指回本页。

## 实验设置

- 目标：附录 FLDetector 行（BackFed 原生服务器，非共同起点）
- 所属机器 / 步骤：G2 / 6
- 设备 / 脚本 / 代码包：3080 Ti 12G / 16G RAM / G2_06_fldetector.ps1 / 1105实验代码/JANUS_G2_3080Ti.zip
- 预计耗时：约 1 h
- 真源补录设置：待补录（`experiment_briefs.json` 无登记，不臆造超参）。

## 攻击 / 训练流程

- 攻击流程：待补录（真源未登记流程正文）。
- 训练流程：待补录（真源未登记流程正文）。

## 轮次阶段工作

- 进度 / 状态：40% / 部分失败·上游缺陷
- 依赖步骤：G2_04_mirage_fixed
- 闸门：需先修 fldetector_server.simple_mean 第 137 行的 [d]+[d,1] 广播缺陷
- 阶段分工：待补录

## 预期结果

待补录（真源未登记量化预期与判定门槛）。

## 结果与分析

- 结果摘要：11-07 12:26–12:57 在 G2 机器实测：FedAvg 对照 3/3 跑满 80 轮；FLDetector 3/3 在第 11 轮请求 29156 GiB 触发 CUDA OOM。根因是 hvp 为 [d,1]、grad 为 [d] 的广播错误，不是显存不足，也不是防御无效。
- 指标：`{"fedavg_success": "3/3", "fldetector_success": "0/3", "failed_at_round": 11}`
- 证据：实验报告/B06_FLDetector_20261107.zip



- [在 Folio 打开实验详情页](http://127.0.0.1:8765/%E7%A7%91%E7%A0%94OS/packages/experiments/G2_06_fldetector.html)

## 关系（有真源依据）

- [[X-G2]] · 版本归属（真源 versions）
- [[总览]] · 实验入口
- [[E-G2_04_mirage_fixed]] · 步骤依赖（真源 depends_on）
