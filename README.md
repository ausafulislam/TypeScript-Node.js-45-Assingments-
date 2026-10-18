# TypeScript & Node.js — 45 Assignments

A collection of beginner-friendly TypeScript exercises completed as part of the **Governor’s Initiative for Artificial Intelligence and Computing (GIAIC)** course. The assignments build core programming skills through small, focused command-line programs that run with Node.js.

## About the repository

This repository contains solutions for exercises **2–45**. Exercises 7 and 8 are combined in one folder because both use arithmetic expressions that produce the number `8`. Each exercise includes:

- `main.ts` — TypeScript source code
- `main.js` — compiled JavaScript
- `tsconfig.json` — TypeScript compiler configuration

## Topics covered

- Variables, strings, numbers, and comments
- Arrays and array methods
- Objects and interfaces
- Conditional statements
- Loops
- Functions and parameters
- Optional and rest parameters
- Basic TypeScript types
- Running TypeScript programs with Node.js

## Assignment index

| Exercise | Topic | Source |
| ---: | --- | --- |
| 02 | Personal Message | [View](Project%2002/main.ts) |
| 03 | Name Cases | [View](Project%2003/main.ts) |
| 04 | Famous Quote | [View](Project%2004/main.ts) |
| 05 | Famous Quote 2 | [View](Project%2005/main.ts) |
| 06 | Stripping Names | [View](Project%2006/main.ts) |
| 07–08 | Number Eight | [View](Project%2007%20and%2008/main.ts) |
| 09 | Favorite Number | [View](Project%2009/main.ts) |
| 10 | Adding Comments | [View](Project%2010/main.ts) |
| 11 | Names | [View](Project%2011/main.ts) |
| 12 | Greetings | [View](Project%2012/main.ts) |
| 13 | Your Own Array | [View](Project%2013/main.ts) |
| 14 | Guest List | [View](Project%2014/main.ts) |
| 15 | Changing Guest List | [View](Project%2015/main.ts) |
| 16 | More Guests | [View](Project%2016/main.ts) |
| 17 | Shrinking Guest List | [View](Project%2017/main.ts) |
| 18 | Seeing the World | [View](Project%2018/main.ts) |
| 19 | Dinner Guests | [View](Project%2019/main.ts) |
| 20 | Creating a List | [View](Project%2020/main.ts) |
| 21 | TypeScript Objects | [View](Project%2021/main.ts) |
| 22 | Intentional Error | [View](Project%2022/main.ts) |
| 23 | Conditional Tests | [View](Project%2023/main.ts) |
| 24 | More Conditional Tests | [View](Project%2024/main.ts) |
| 25 | Alien Colors #1 | [View](Project%2025/main.ts) |
| 26 | Alien Colors #2 | [View](Project%2026/main.ts) |
| 27 | Alien Colors #3 | [View](Project%2027/main.ts) |
| 28 | Stages of Life | [View](Project%2028/main.ts) |
| 29 | Favorite Fruit | [View](Project%2029/main.ts) |
| 30 | Hello Admin | [View](Project%2030/main.ts) |
| 31 | No Users | [View](Project%2031/main.ts) |
| 32 | Checking Usernames | [View](Project%2032/main.ts) |
| 33 | Ordinal Numbers | [View](Project%2033/main.ts) |
| 34 | Pizzas | [View](Project%2034/main.ts) |
| 35 | Animals | [View](Project%2035/main.ts) |
| 36 | T-Shirt | [View](Project%2036/main.ts) |
| 37 | Large Shirts | [View](Project%2037/main.ts) |
| 38 | Cities | [View](Project%2038/main.ts) |
| 39 | City Names | [View](Project%2039/main.ts) |
| 40 | Album | [View](Project%2040/main.ts) |
| 41 | Magicians | [View](Project%2041/main.ts) |
| 42 | Great Magicians | [View](Project%2042/main.ts) |
| 43 | Unchanged Magicians | [View](Project%2043/main.ts) |
| 44 | Sandwiches | [View](Project%2044/main.ts) |
| 45 | Cars | [View](Project%2045/main.ts) |

## Prerequisites

Install the following tools before running the exercises:

- [Node.js](https://nodejs.org/) 18 or later
- npm (included with Node.js)

You can check your installation with:

```bash
node --version
npm --version
```

## Getting started

1. Clone the repository:

   ```bash
   git clone https://github.com/ausafulislam/TypeScript-Node.js-45-Assingments-.git
   cd TypeScript-Node.js-45-Assingments-
   ```

2. Run the compiled JavaScript for any exercise:

   ```bash
   node "Project 02/main.js"
   ```

### Run the TypeScript source directly

Use `npx` to run a source file without installing TypeScript globally:

```bash
npx --yes ts-node "Project 02/main.ts"
```

### Compile an exercise

Use the `tsconfig.json` inside the exercise folder:

```bash
npx --yes tsc --project "Project 02/tsconfig.json"
node "Project 02/main.js"
```

Replace `Project 02` with the exercise you want to run. Keep quotation marks around folder names because they contain spaces.

## Project structure

```text
TypeScript-Node.js-45-Assingments-/
├── Project 02/
│   ├── main.ts
│   ├── main.js
│   └── tsconfig.json
├── Project 03/
│   └── ...
├── Project 07 and 08/
│   └── ...
├── Project 45/
│   └── ...
└── README.md
```

## Learning purpose

These solutions are intended for learning and practice. Try solving each exercise yourself before reviewing the corresponding implementation.

## Author

Created by [Ausaf Ul Islam](https://github.com/ausafulislam).

Contributions, suggestions, and improvements are welcome through issues or pull requests.
