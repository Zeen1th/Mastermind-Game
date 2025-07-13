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
