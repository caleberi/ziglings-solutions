# Ziglings-Solutions

This repository contains my **solutions** to the Ziglings exercise series — a hands-on set of tiny, broken programs designed to teach the Zig programming language by fixing them. (Based on the original Ziglings project.)

## 🎯 Purpose

* To document and track my progress learning Zig through problem-solving.
* To provide clean, working implementations for each exercise, along with commentary as needed.
* To serve as a reference and study aid for others exploring Zig in a practical, incremental way.

## 📚 Structure

* Each exercise is stored in its own folder (e.g., `exercise-001`, `exercise-002`, …).
* Within each folder:

  * `main.zig` (or appropriate filename) — my corrected version of the broken program.
  * `README.md` — a short note on what was broken, how I fixed it, and what I learned.
* A top-level `SUMMARY.md` or `INDEX.md` lists all exercises solved so far, their status (✅, 🧪 in progress, etc.), and links to the folders.

## ✅ Approach

* I attempt each exercise in the order provided by Ziglings.
* I first run the broken version (if provided), observe the compile/run errors or logic misbehaviours, then apply fixes.
* I annotate my fixed version with comments to highlight the key Zig idioms and language features I encountered.
* I maintain a “what I learned” section in each folder to record insights, pitfalls, and references.

## 🔍 Why this repository might be useful

* It makes my learning journey transparent and reproducible — you can see how I solved each step.
* It provides concrete working Zig code examples (useful for learners switching from other languages or exploring Zig for the first time).
* If you’re also working through Ziglings, you can compare your approach with mine, adopt ideas, or identify alternate solutions.
* It helps me build a habit of incremental, disciplined learning with version control + documentation.

## 🛠 Usage

1. Clone the repo:

   ```bash
   git clone https://github.com/caleberi/ziglings-solutions.git  
   ```
2. Navigate to a solved exercise folder, e.g.:

   ```bash
   cd exercise-012  
   ```
3. Build and run (assuming Zig is installed):

   ```bash
   zig build run  
   ```

   or appropriate command according to the exercise.
4. Inspect `README.md` in that folder for commentary.

## 📅 Progress & Roadmap

* [x] Exercises 001-010
* [x] Exercises 011-020
* [ ] Exercises 021-030
* [ ] … continuing until completion of all available Ziglings exercises.
* Future: Add a summary section at the end of each month with “Key Insights from this batch”.

## 🙏 Acknowledgements

Thanks to the original Ziglings project for the exercise set: [https://github.com/ratfactor/ziglings](https://github.com/ratfactor/ziglings) ([GitHub][1])
Also open to feedback/contributions if you’d like to compare solutions or suggest alternative fixes!
