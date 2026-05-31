# ai-knowledge-quiz

[English](#english) | [中文](#中文)

---

## English

A bilingual (Chinese/English) interactive quiz webpage — **"Comprehensive Core Knowledge Quiz in the AI Era"**. Contains 43 questions testing knowledge about LLMs, AI companies, AI concepts, and industry trends. 

### Features

- Bilingual — every question, option, and explanation in both Chinese and English
- Interactive — select answers, submit, get immediate feedback with explanations
- Scoring — tracks your score out of total questions
- Wrong answer review — export incorrect answers as a TXT file for review
- Zero dependencies — single HTML file, open in any browser

### Usage

Open `index.html` in any browser. No build step, no server required.

```bash
# On macOS
open index.html

# On Windows
start index.html
```

### Quiz Data Format

Each question in the `qData` array follows this structure:

```js
{
    qZ: "Chinese question text",
    qE: "English question text",
    oZ: ["4 Chinese options"],
    oE: ["4 English options"],
    a: 0,          // index of correct answer (0-based)
    eZ: "Chinese explanation",
    eE: "English explanation"
}
```

---

## 中文

一个中英双语互动测试网页 —— **「AI时代核心知识综合测试」**。共 43 道题目，涵盖大语言模型（LLM）、AI 公司、AI 概念和行业趋势等知识点。

### 功能特点

- 双语支持 — 每道题的题目、选项和解析均有中英文版本
- 互动作答 — 选择答案后立即获得反馈和详细解析
- 自动计分 — 实时统计得分
- 错题导出 — 支持将错题导出为 TXT 文件，方便复习
- 零依赖 — 单文件 HTML，浏览器直接打开即可使用

### 使用

用任意浏览器打开 `index.html` 即可，无需安装或构建。

```bash
# macOS
open index.html

# Windows
start index.html
```

### 题目数据格式

`qData` 数组中每道题的结构如下：

```js
{
    qZ: "中文题目",
    qE: "English question",
    oZ: ["四个中文选项"],
    oE: ["4 English options"],
    a: 0,          // 正确答案索引（从 0 开始）
    eZ: "中文解析",
    eE: "English explanation"
}
```

---

## License

MIT
