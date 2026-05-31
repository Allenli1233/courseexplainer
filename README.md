# coursepptexplainer

`coursepptexplainer` is a Codex skill for explaining course PPTs, PDF lecture files, lecture slides, screenshots, notes, and textbook excerpts in a detailed teacher-like style.

It is designed for students who want more than direct translation. The skill explains the logic behind the material, highlights important academic terms in both English and Chinese, points out common mistakes, and ends with transfer practice questions.

## What It Does

When used with a course PPT or lecture material, this skill asks Codex to:

- explain mostly in Chinese
- keep key academic terms in English and Chinese
- teach concepts in a clear, step-by-step way
- explain graphs, formulas, models, and curves carefully
- add reflection, intuition, and teacher-style summaries
- point out likely homework, quiz, test, or exam angles
- provide English practice questions and English answers with Chinese explanations

## Best For

- course PPT explanation
- PDF lecture file explanation
- lecture slide review
- screenshot-based course questions
- textbook excerpt explanation
- economics, business, social science, or other concept-heavy classes
- exam review and self-check practice

## Installation

Clone this repository into your Codex skills folder.

### Windows PowerShell

```powershell
git clone https://github.com/Allenli1233/coursepptexplainer.git "$env:USERPROFILE\.codex\skills\coursepptexplainer"
```

### macOS or Linux

```bash
git clone https://github.com/Allenli1233/coursepptexplainer.git ~/.codex/skills/coursepptexplainer
```

After installation, start a new Codex chat so the skill list can refresh.

## Usage

You can call the skill directly:

```text
Use coursepptexplainer to explain this PPT.
```

Or in Chinese:

```text
用 coursepptexplainer 帮我讲这个 PPT。
```

For PDF lecture files:

```text
用 coursepptexplainer 帮我讲这个 PDF 课件，先讲第 1-10 页。
```

You can also use a natural request:

```text
按我的课程 PPT 讲解方式讲一下这个文件。
```

## Output Style

The skill prefers this structure:

1. 本部分核心主题
2. 逐点详细讲解
3. 重点概念中英双语整理
4. 易错点提醒
5. 老师式总结
6. 举一反三例题

Practice questions follow this format:

```text
Question 1:
[English question]

Answer:
[English answer]

中文解析：
[Chinese reasoning and explanation]
```

## Example Prompt

```text
用 coursepptexplainer 帮我讲解这几页 ECO102 PPT。请重点解释图表、公式和考试可能会考的地方。
```

```text
用 coursepptexplainer 帮我讲解这个 ECO102 PDF lecture。请按页码顺序分段讲，不要只翻译原文。
```

## Skill File

The actual skill instructions are in [`SKILL.md`](./SKILL.md).
