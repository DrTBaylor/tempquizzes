# Quizzes

This folder holds quizzes generated from the Sorry! topic files in the main folder.

## How to generate a quiz

Ask Claude something like:

> Make a 10-question quiz on `rules.md` and `cards.md`, medium difficulty.

Claude should:
1. Read the source topic file(s).
2. Write questions using **only** facts from those files.
3. Follow the format in [template.md](template.md).
4. Save the quiz in this folder using the naming rule below.

## Naming

`<topic>-<difficulty>-<number>.md`

Examples: `rules-easy-01.md`, `cards-medium-01.md`, `mixed-hard-02.md` (use `mixed` for quizzes covering several topics).

## Difficulty levels

| Level | Meaning |
|---|---|
| **easy** | Basic facts stated directly in one sentence of a topic file |
| **medium** | Details, numbers, or combining two facts |
| **hard** | Applying rules to a game situation, or tricky edge cases from `faq.md` |

## Question types

- **Multiple choice** — four options (A–D), one correct
- **True/False**
- **Short answer** — a word, number or short phrase

## Answer key

Answers go at the bottom of each quiz under an **Answer Key** heading, with a one-line explanation and the source file for each answer, so quizzes can be checked against the topic files.

## Quiz list

| Quiz | Topics | Difficulty | Questions |
|---|---|---|---|
| [rules-easy-01.md](rules-easy-01.md) | rules, cards | easy | 10 |
