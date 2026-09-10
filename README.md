# prompt-shelf-kit

Prompt collection: review, SQL, explain, rewrite

## Usage

```bash
# copy a prompt into your system message
cat prompts/senior-reviewer.md
```

## What it does

- One prompt per file, easy to diff and review
- index.json for programmatic access
- Tested against GPT and Claude models
- Each prompt has usage notes and known failure modes

## Getting started

```bash
# no dependencies - browse the prompts/ folder
```

## Project structure

```text
├── docs/
│   ├── development.md
│   ├── faq.md
│   ├── roadmap.md
│   └── usage.md
├── prompts/
│   ├── eli-junior.md
│   ├── rewrite-pass.md
│   ├── senior-reviewer.md
│   └── sql-helper.md
├── .editorconfig
├── .gitignore
├── CONTRIBUTING.md
└── index.json
```
