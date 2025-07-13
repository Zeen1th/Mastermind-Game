# Mastermind – Console Edition

A small C-sharp console game built for the Steer Elite 2025 Gameplay Programming assessment.

---

## Overview
* Solve a secret four-symbol code.
* Symbols are digits **0–8** with no repeats.
* You get feedback as **well placed** and **misplaced** counts.
* Default limit is ten rounds. Change it with a flag.
* Clean single-file code so reviewers can skim it fast.

---

## Features
| Flag | Purpose | Example |
|------|---------|---------|
| `-c` | Set a custom secret code. Must be four distinct digits 0-8. | `-c 0123` |
| `-t` | Set max rounds. Positive integer only. | `-t 6` |

You can combine flags in any order.

---

## Requirements
* .NET 6 SDK or newer  
  Check with `dotnet --version`.

---

## Build
```bash
dotnet build
Run
bash
Copy
Edit
# random secret and default rounds
dotnet run --project Mastermind

# custom code and five rounds
dotnet run --project Mastermind -- -c 0123 -t 5
Quit any time on Windows by pressing Ctrl+Z then Enter.

How to Play
Type a four-digit guess such as 0267.

Press Enter.

Read the feedback.

Well placed means right digit right spot.

Misplaced means right digit wrong spot.

Refine the next guess. Break the code before your rounds drop to zero.

If all four digits are well placed you win.
If rounds run out the secret code is revealed and the game ends.

Project Layout
sql
Copy
Edit
Mastermind/
├─ Program.cs  →  Full game logic
└─ README.md   →  This file
License
Released under the MIT License. See LICENSE for details.

About the Author
I have shipped Unity projects like While He Seeks and a procedural driving prototype. I led the AI Club content team at the University of Hail. I also build data dashboards and train Arabic TTS models. This mix of gameplay programming and machine learning shows I learn tech fast and solve problems quickly.

sql
Copy
Edit

Copy everything above into `README.md` and commit it along with your code.
