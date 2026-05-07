# 《Una habitación propia》— 反例类候选单元

- id: ce01
  title: "有钱有房间就够了"
  type: counter-example
  failure_mode: |
    将Woolf的论点简化为"有钱有房间就够了"——好像物质条件是充分条件。Woolf的论点是必要条件，不是充分条件：没有物质条件不可能有精神自由，但有物质条件不保证精神自由。
  mechanism: |
    将"依赖于"理解为"等同于"。Woolf说的是"智力的自由依赖于物质条件"——这是必要条件，不是充分条件。
  warning_signs:
    - 论证中出现"只要有钱就能自由"
    - 忽视精神自由的其他条件（传统、价值观、社会支持）
    - 将物质条件问题简化为"个人选择"
  bound_to:
    - "物质条件-精神自由关联分析"
  tags: [counter-example, sufficient-condition, materialism]

- id: ce02
  title: "女性天生写不好"
  type: counter-example
  failure_mode: |
    将女性写作的局限归因于"天赋"而非"条件"——好像Charlotte Brontë写不好是因为她是女人，而不是因为她被剥夺了经验和自由。
  mechanism: |
    将结构性条件的效果归因于内在本质。Woolf的论点恰恰相反：女性写作的局限来自条件而非天赋——"莎士比亚的姊妹"有同等天赋，只是没有同等条件。
  warning_signs:
    - 论证中出现"女性天生不适合"
    - 将创作局限归因于性别而非条件
    - 忽视结构性障碍的存在
  bound_to:
    - "莎士比亚的姊妹"识别框架"
  tags: [counter-example, essentialism, talent-vs-conditions]
