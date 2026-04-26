---
title: "Critical Thinking for Engineers - Collaboration Guide"
description: "Contributing guide for Critical Thinking for Engineers course content"
tableOfContents: true
sidebar:
  order: 999
---

# Critical Thinking for Engineers

![Build](https://img.shields.io/badge/build-passing-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
![Contributors Welcome](https://img.shields.io/badge/contributors-welcome-orange)

**Read this course at:** [https://siliconwit.com/education/critical-thinking-engineers/](https://siliconwit.com/education/critical-thinking-engineers/)

Nine lessons on logical fallacies, cognitive biases, statistical pitfalls, and evidence-based reasoning for engineers and researchers. Every lesson uses relatable engineering examples.

## Lessons

| # | Title |
|---|-------|
| 1 | How Your Brain Tricks You |
| 2 | Logical Fallacies in Technical Arguments |
| 3 | Cognitive Biases in Engineering Decisions |
| 4 | Statistics Done Wrong |
| 5 | How to Lie with Charts and Data |
| 6 | Estimation, Uncertainty, and Confidence |
| 7 | Correlation, Causation, and Evidence |
| 8 | Debugging as Scientific Reasoning |
| 9 | Making Better Engineering Decisions |

## How to Contribute

All commands below work on Linux, macOS, and Windows (using Git Bash, PowerShell, or Command Prompt with Git installed).

### For Team Members (with push access)

**First time setup (clone the repo once):**

```bash
git clone https://github.com/SiliconWit/critical-thinking-engineers.git
cd critical-thinking-engineers
```

**Every time you start working:**

```bash
git pull origin main
```

Always pull before making changes. This avoids conflicts with other contributors.

**After making your changes:**

```bash
git add .
git commit -m "Brief description of what you changed"
git push origin main
```

**If you get a push error** (someone pushed before you):

```bash
git pull origin main
```

Git will merge the changes automatically in most cases. If there is a conflict, Git will mark the conflicting lines in the file. Open the file, choose which version to keep, then:

```bash
git add .
git commit -m "Resolve merge conflict"
git push origin main
```

**Tips to avoid conflicts:**

- Always `git pull origin main` before you start working
- Push your changes as soon as you are done, do not hold onto uncommitted work for long
- Coordinate with other contributors so two people are not editing the same file at the same time

### For External Contributors (without push access)

1. Fork the repository: [SiliconWit/critical-thinking-engineers](https://github.com/SiliconWit/critical-thinking-engineers)
2. Clone your fork:
   ```bash
   git clone https://github.com/YOUR-USERNAME/critical-thinking-engineers.git
   cd critical-thinking-engineers
   ```
3. Make your changes and commit:
   ```bash
   git add .
   git commit -m "Brief description of what you changed"
   git push origin main
   ```
4. Open a Pull Request against `main` on the original repository
5. Describe what you changed and why in the PR description

## Content Standards

- All lesson files use `.mdx` format
- Do not use `<BionicText>` in this course
- Use relatable engineering and everyday examples
- No emojis, no em dashes

## License

This course content is released under the [MIT License](LICENSE).
