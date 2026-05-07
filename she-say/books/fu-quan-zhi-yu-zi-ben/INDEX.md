# Patriarcado y acumulación — Skill Index


## 关于这本书

- **作者**: Maria Mies
- **出版年**: 1986（英文初版）/ 2019（西班牙文版）
- **一句话主旨**: 父权制与资本积累是全球性共生体系——对女性身体、自然和殖民地的暴力占有是资本主义积累的永久性基础
- **整书理解**: 见 [BOOK_OVERVIEW.md](./BOOK_OVERVIEW.md)

## Skill 列表 (按分析层次分组)

### 核心理论

- [`ongoing-primitive-accumulation`](./ongoing-primitive-accumulation/SKILL.md) — 识别"原始积累"不是史前史而是持续过程

### 暴力分析

- [`violence-accumulation-analyzer`](./violence-accumulation-analyzer/SKILL.md) — 分析暴力如何作为积累的基础而非例外

### 全球尺度

- [`global-domestication-detector`](./global-domestication-detector/SKILL.md) — 识别从家庭到国际分工的驯化逻辑

### 起源批判

- [`division-of-labor-critic`](./division-of-labor-critic/SKILL.md) — 批判"自然分工"神话——性分工是社会起源

## 依赖图

```
ongoing-primitive-accumulation (核心)
  ├── violence-accumulation-analyzer (depends-on: accumulation)
  ├── global-domestication-detector (depends-on: accumulation)
  └── division-of-labor-critic (depends-on: accumulation)

violence-accumulation-analyzer ──composes-with── global-domestication-detector
global-domestication-detector ──composes-with── division-of-labor-critic
```

## 建议学习顺序

1. `ongoing-primitive-accumulation` — 理解原始积累的持续性是所有后续分析的基础
2. `violence-accumulation-analyzer` — 理解暴力与积累的结构性关联
3. `global-domestication-detector` — 理解驯化逻辑的全球尺度
4. `division-of-labor-critic` — 批判性分工的"自然性"神话
