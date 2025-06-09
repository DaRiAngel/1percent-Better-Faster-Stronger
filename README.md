# 1percent-Better-Faster-Stronger

## Description of Technology & Why

**Language:**  
- **Python** — chosen for its flexibility, simplicity, and power in data manipulation and scripting.

**Core Packages:**  
- `os`: for file and directory navigation  
- `pandas`: for working with structured data  
- `re`: for regular expressions and pattern matching  
- `string` and `random`: for text processing, generation, and utilities  

**Why:**  
This project is a personal toolbox — built to document lessons learned and create reusable functions for data cleaning, automation, and experimentation. It’s designed to help my future self move faster by building once and reusing often.

## Process Used & Why

**Trigger for updates:**  
Each time I solve a new problem in another project, I update this repository with at least one distilled, reusable function.

**Code standards:**  
- All functions are tested before being uploaded.  
- New code may leverage existing functions in this library when appropriate.

**Learning stance:**  
While I reference AI tools like ChatGPT for guidance, I intentionally avoid using Copilot or auto-complete tools to write code for me. This is to ensure hands-on understanding and to strengthen my skills through direct implementation.

## Table of Contents

1. **Data Inspection**  
   - `value_counts_all_columns(df)`: Display value counts for each column in a DataFrame.

2. **Variable & Filename Sanitization**  
   - `stripForVariableUse()`: Remove problematic characters from strings to make them safe for Python variables or OS use.

3. **Code Generation Utilities**  
   - `generateCode_csv_xlsx_dataframesFrom_directory(directory)`: Auto-generate Python code to load all CSV/XLSX files in a given directory.

4. *Coming Soon*  
   - Random data generation  
   - Regex-based string cleaning  
   - OS-safe path utilities  

## Project Conception

**The spark:**  
After working in fast-paced, detail-heavy environments — especially with clinical and structured data — I realized that many tasks were repetitive, with minor variations.

**The insight:**  
I kept finding myself rewriting similar snippets to solve problems that felt routine but still required precision. Whether renaming files, cleaning column names, or loading datasets — these were small actions that slowed down the bigger goals.

**The purpose:**  
This project was born from a need to reduce friction. By automating the "boring but necessary," I can focus more on high-impact work and less on remembering syntax.

## Motivation

**Atomic learning:**  
This project is built piece-by-piece — a growing set of small, self-contained tools that I can mix and match as needed.

**Why:**  
I’ve spent too much time re-solving the same problems. By documenting what works, I’m building a personal library I can trust and reuse.

**Bigger picture:**  
This isn’t just about saving time. It’s part of becoming a sharper, faster, and more capable clinical data scientist — with a battle-tested toolkit and a habit of learning through doing.

## Challenges & Limitations

**Platform scope:**  
This project is primarily developed and tested on macOS. Compatibility with Windows and Linux may vary and will evolve as needs arise.

**Code style tradeoffs:**  
While Python favors chaining functions for brevity, I prioritize readability and clarity — often modeling my approach after R-style scripting.  
- I prefer creating named variables to explain each step clearly.  
- This makes the code easier to re-learn after breaks and more accessible to others.

**Growing pains:**  
As this library expands, I anticipate some code bloat. I’m addressing that by breaking functions into atomic parts — but clarity will always come before extreme conciseness.

**And if Plan A fails?**  
Plan B is simple: adapt, refactor, and keep moving forward.

## What Problem This Solves

This project solves a familiar challenge: repetition in early-stage data work.

- Cleaning data and running exploratory checks often feel like déjà vu — same tasks, different files.  
- Remembering how I solved a problem six months ago? Not always easy.

**Solution:**  
By capturing reusable, tested code snippets in one place, I can move faster, stay agile, and focus on what really matters: extracting value from real-world data.

## Intended Use

**Primary use:**  
This repo is built for my future self — to speed up future projects, eliminate repetition, and serve as a foundation I can trust.

**Secondary use:**  
If others find value in these tools — whether fellow data scientists or my own children someday — then this becomes more than just code. It becomes a guide to solving real-world problems with clarity and care.

**Long-term vision:**  
If the pieces come together cleanly, I’d love to evolve this into a full Python library or pip-installable package.

## Credits

- **David Angel** — creator, builder, and future user of this repo  
- **Mrs. Kathy Wesier** — my high school Java teacher who sparked my interest in coding  
- **365 Data Science**, **Datacamp**, and countless creators on **YouTube** — for their unofficial mentorship through the internet’s greatest classroom
