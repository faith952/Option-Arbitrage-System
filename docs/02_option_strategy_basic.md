# 02 Basic Option Strategies

## 1. 本节目标

本节学习基础期权组合策略，包括：

- Long Straddle
- Long Strangle
- Bull Call Spread
- Bear Put Spread
- Long Butterfly

目标不是机械记住策略名称，而是理解每个策略背后的市场观点、风险结构和适用场景。

---

## 2. 为什么需要组合策略？

单腿期权只能表达比较粗糙的观点，例如看涨、看跌或保护风险。

组合策略可以更精细地表达：

- 看涨但上涨有限
- 看跌但下跌有限
- 预期大波动但方向不确定
- 预期价格维持区间震荡
- 想降低权利金成本
- 想控制最大亏损
- 想设计特定风险收益结构

期权组合的核心不是“多买几个期权”，而是主动设计风险结构。

---

## 3. Long Straddle

### 3.1 构造

买入同一行权价、同一到期日的 Call 和 Put：

```text
Buy Call K
Buy Put  K
