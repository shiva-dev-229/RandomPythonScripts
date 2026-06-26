# Random Python Scripts

> A personal sandbox of Python experiments, mini-projects, and coding challenges — everything from a desktop weather app and a Pong game to turtle-graphics art and a folder of small algorithm puzzles. The place where I try ideas out.

---

## About

This repository is a collection of standalone Python scripts I've written while learning and experimenting. It isn't one project — it's a workbench. Some pieces grew into real little applications (a GUI weather app, a Pong game); others are quick challenges and one-off experiments.

---

## Highlights

### Weather app (`Wheather app/`)
A desktop GUI app built with **tkinter** that fetches live data from the **OpenWeatherMap API**, displays the current conditions and temperature (in both °F and °C), and shows matching weather icons. It was even packaged into a standalone executable with PyInstaller.

> **Setup note:** the app needs an OpenWeatherMap API key. Provide it through an environment variable (e.g. `OPENWEATHER_API_KEY`) rather than hardcoding it, and keep it out of version control.

### Pong (`Pong_game_shivansh.py`, `Pong2.py`)
A playable **Pong** clone built with Python's `turtle` graphics — paddles, ball physics, and scoring. (Uses `winsound`, so sound effects are Windows-only.)

### Turtle art (`Intrecet_design_Turtle.py`, `Trees_design_shivansh.py`, `drawing_app_shivansh`)
Generative graphics experiments using the `turtle` module — geometric designs, procedural trees, and a small drawing app.

### Calculators (`Calculater/`)
Several takes on a calculator, including a command-line version and a `tkinter` GUI version.

---

## Mini challenges (`Mini Chalenges/`)
A set of classic small programming exercises — Fibonacci, palindromes, Pascal's Triangle, sentence/string reversers, bracket matching, and more — written as practice.

---

## Running

Each script is standalone. Most run directly with Python 3:

```bash
python3 Pong_game_shivansh.py
```

Scripts that use external services or libraries (like the Weather app, which needs `requests` and an API key) have their requirements noted above.

```bash
pip install requests    # for the Weather app
```

---

## Note

This is a personal experimentation repository — a running collection of things I've built while learning Python. It's intentionally broad rather than focused on a single project.
