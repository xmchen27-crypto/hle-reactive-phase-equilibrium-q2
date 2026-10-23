# Reactive Liquid–Liquid Equilibrium · Q2

**反应耦合的液液相平衡**：一份 HLE 训练数据构造项目中的物理化学数值题案例。

Adiabatic reactive liquid-liquid equilibrium, enthalpy conservation, common-tangent construction and global entropy stability.

## 阅读入口

- [题目 / Question](QUESTION.md)：完整英文题干、模型条件、输出精度、单位与容差。
- [解答 / Solution](SOLUTION.md)：原始推导与数值结果。
- [标准答案 / Answer](ANSWER.md)：有序三元组及逐项判定标准。
- [结构化数据](data/problem.json)：便于数据集导入的单题 JSON。
- [数据格式说明](docs/DATA_FORMAT.md)：整理范围与格式约定。

## 考察内容

定压绝热焓守恒、反应平衡、液液分相、公切线条件与全局熵最大化。

题目与解答保持英文；项目入口与整理说明使用中文。公式保留原始 LaTeX，阅读和使用题目无需模型账户。

## 标准答案

$(321.65,\ 0.0824,\ 2.421)$

单位依次为：$(\mathrm K,\ 1,\ \mathrm{J\,K^{-1}})$。具体精度和绝对容差见 [标准答案](ANSWER.md) 与原题。

## 来源与整理范围

来源文件：`晓天睿士 (2026_9_18 22：21：31)第2题.html`。

本仓库使用 2026-09-18 导出版本，保留题干、解答、答案和单位，并去除平台界面及重复公式预览。原导出页面状态为“验收中”。

参考的任务说明为【0914】HLE训练数据构造（本地 2026-10-15 导出）。本次完成字段一致性、公式源码、答案长度及数值容差结构核对；标准答案和推导按原文件收录。

原页面注明 **版权归阿里所有 / Copyright owned by Alibaba Group.** 详见 [来源与版权标注](NOTICE.md)。
