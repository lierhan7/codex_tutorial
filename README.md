# Codex CLI 学习包

这是一个面向初学者的 Codex CLI 中文学习包，目标不是只教你“怎么提问”，而是帮助你逐步建立一套可落地的使用方法。

这套材料适合以下人群：

- 第一次接触 Codex CLI
- 会基础终端操作，但不清楚如何和 Codex 协作
- 想把 Codex CLI 真正用进日常开发
- 想减少无效提问、误改代码和低质量输出

---

## 文档目录

### 1. 完整教程

[codex_tutorial.md](./codex_tutorial.md)

适合第一次系统学习时阅读。  
内容重点：

- Codex CLI 是什么
- 适合做什么
- 如何正确提需求
- 权限、沙箱和审批
- 修改代码与验证的基本工作流
- 初学者常见误区

### 2. 速查手册

[codex_cheatsheet.md](./codex_cheatsheet.md)

适合平时快速翻看和复制。  
内容重点：

- 最常用的指令句式
- 提示词模板
- 高质量限制语句
- 审批判断原则
- 一页版使用原则

### 3. 实战案例

[codex_case_studies.md](./codex_case_studies.md)

适合想看“完整任务怎么问、怎么推进、怎么验收”的用户。  
内容重点：

- 读仓库
- 修 bug
- 补测试
- 做 code review
- 新增小功能
- 写项目文档
- 如何纠偏和收窄范围

### 4. 提示词库

[codex_prompt_library.md](./codex_prompt_library.md)

适合直接复制到 Codex CLI 里使用。  
内容重点：

- 通用模板
- 仓库理解类提示词
- 代码解释类提示词
- bug 修复类提示词
- 测试、重构、review、文档类提示词
- 纠偏与格式控制提示词

### 5. 常见问题 FAQ

[codex_cli_faq.md](./codex_cli_faq.md)

适合遇到卡点时快速查阅。  
内容重点：

- 为什么它一直在看文件
- 为什么有时只分析不修改
- 为什么会改太多文件
- 审批怎么判断
- 测试为什么跑不起来
- 怎么判断结果靠不靠谱
- 跑偏时怎么纠正

---

## 推荐阅读顺序

如果你是第一次接触 Codex CLI，建议按这个顺序看：

1. 先读 [codex_tutorial.md](./codex_tutorial.md)，建立整体认知
2. 再看 [codex_cheatsheet.md](./codex_cheatsheet.md)，熟悉日常常用句式
3. 接着看 [codex_case_studies.md](./codex_case_studies.md)，理解真实任务怎么推进
4. 然后把 [codex_prompt_library.md](./codex_prompt_library.md) 当作可复制模板库
5. 最后把 [codex_cli_faq.md](./codex_cli_faq.md) 作为遇到问题时的排错手册

---

## 如果你只想先快速上手

可以直接走这条最短路径：

1. 先读 [codex_cheatsheet.md](./codex_cheatsheet.md)
2. 再从 [codex_prompt_library.md](./codex_prompt_library.md) 里复制一个模板
3. 遇到问题时查 [codex_cli_faq.md](./codex_cli_faq.md)

这样上手最快。

---

## 如果你想真正用到工作里

建议重点掌握这几件事：

1. 提问时始终写清楚目标、范围、约束和验证要求
2. 对 bug 修复类任务，优先要求“最小修改”
3. 对高风险任务，先让 Codex 分析，不要立刻改代码
4. 对任何实际改动，都尽量要求验证结果
5. 对审批请求保持敏感，不要看见就同意

这几条比“提示词写得像不像专家”更重要。

---

## 一句话使用原则

如果你只记住一句话，记这个就够了：

`任务具体，边界明确，改完验证。`
