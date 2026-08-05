# DATA209 — Advanced Exploratory Data Analysis

Course website and materials for **DATA209**, BTech Hons. (Data Science), Semester III.
School of Engineering and Technology, Vidyashilp University.

**Live site → https://shitalbhatt.github.io/data209/**

---

## For students

Everything for the course is on the site above: syllabus, weekly schedule, lecture notes,
slides, lab notebooks, datasets, assignment briefs and reading lists. Start there.

If you prefer to work offline, use the green **Code → Download ZIP** button on this page,
unzip it, and open `index.html` in a browser. Keep every file in the same folder or the
download links will not work.

## What is here

| | Count | Notes |
|---|---|---|
| Course website | 1 | `index.html` — open this |
| Lecture notes (PDF) | 16 | One printable handout per lecture pair, plus a combined booklet |
| Lecture notes (Word) | 15 | Editable, with worked code and real output |
| Lecture decks (PowerPoint) | 15 | Teaching slides with code-and-output slides |
| Module decks (PowerPoint) | 4 | One per module, following the course plan |
| Lab notebooks | 14 | 13 standalone practicals plus one combined manual |
| Assignment model answers | 8 | Worked case studies for Assignments 1 and 2 |

## Running the lab notebooks

The notebooks need a standard scientific Python stack:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy jupyter
```

Then open any notebook and set `DATA_DIR` (or `SOURCE_A` / `SOURCE_B`) in the setup cell to
point at your copy of the data. Each practical notebook rebuilds whatever it needs from the
CSV, so you can start at any session in a fresh kernel.

Google Colab works too if you would rather not install anything locally.

## A note on the assignment case studies

The worked case studies show the expected structure, depth and standard of interpretation.
They are **models, not templates** — the assignment briefs award zero marks where groups
submit the same dataset, so your own analysis must use a different one.

---

*Course materials © Vidyashilp University. Datasets referenced remain under their original
licences; check each source before redistributing.*
