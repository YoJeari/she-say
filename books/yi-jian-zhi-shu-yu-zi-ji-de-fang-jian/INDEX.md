# Una habitación propia — Skill Index


## 关于这本书

- **作者**: Virginia Woolf
- **出版年**: 1929
- **一句话主旨**: 女性要写小说，必须有钱和一间自己的房间——物质条件是精神自由的前提
- **整书理解**: 见 [BOOK_OVERVIEW.md](./BOOK_OVERVIEW.md)

## Skill 列表 (按分析层次分组)

### 核心理论

- [`material-freedom-analyzer`](./material-freedom-analyzer/SKILL.md) — 分析物质条件如何制约/enable精神自由

### 识别工具

- [`shakespeares-sister-detector`](./shakespeares-sister-detector/SKILL.md) — 识别被结构性条件扼杀的潜在创造力

### 创作分析

- [`anger-distortion-analyzer`](./anger-distortion-analyzer/SKILL.md) — 分析愤怒如何扭曲创作/判断

## 依赖图

```
material-freedom-analyzer (核心)
  ├── shakespeares-sister-detector (depends-on: material-freedom)
  └── anger-distortion-analyzer (depends-on: material-freedom)

shakespeares-sister-detector ──composes-with── anger-distortion-analyzer
```

## 建议学习顺序

1. `material-freedom-analyzer` — 理解物质条件与精神自由的关系是所有后续分析的基础
2. `shakespeares-sister-detector` — 理解结构性障碍如何扼杀潜力
3. `anger-distortion-analyzer` — 理解愤怒与创作/判断的复杂关系
