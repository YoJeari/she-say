# Gender Trouble — Skill Index


## 关于这本书

- **作者**: Judith Butler
- **出版年**: 1990（初版）/ 1999（再版）
- **一句话主旨**: 性别不是内在本质的表达，而是一套被反复表演的规范性行为——"性别麻烦"在于揭示这种表演性，从而打开性别可能性的场域
- **整书理解**: 见 [BOOK_OVERVIEW.md](./BOOK_OVERVIEW.md)

## Skill 列表 (按分析层次分组)

### 核心理论

- [`gender-performativity-detector`](./gender-performativity-detector/SKILL.md) — 识别性别作为表演性建构——"性别是做的不是是的"

### 拆解工具

- [`heterosexual-matrix-deconstructor`](./heterosexual-matrix-deconstructor/SKILL.md) — 拆解生物性别/社会性别/欲望的强制关联
- [`normativity-detector`](./normativity-detector/SKILL.md) — 识别使某些性别表达"可理解"其他"不可理解"的规范性权力机制

### 政治批判

- [`identity-category-critic`](./identity-category-critic/SKILL.md) — 批判"统一身份"作为政治前提的问题

## 依赖图

```
gender-performativity-detector (核心)
  ├── heterosexual-matrix-deconstructor (depends-on: performativity)
  ├── normativity-detector (depends-on: performativity)
  └── identity-category-critic (depends-on: performativity, contrasts-with: performativity)

heterosexual-matrix-deconstructor ──composes-with── normativity-detector
identity-category-critic ──composes-with── normativity-detector
```

## 建议学习顺序

1. `gender-performativity-detector` — 理解性别的表演性是所有后续分析的基础
2. `heterosexual-matrix-deconstructor` — 拆解性别/欲望的强制关联
3. `normativity-detector` — 理解规范性权力如何生产"可理解的"性别
4. `identity-category-critic` — 批判统一身份，思考开放联盟的政治
