# COSI 165b - Deep Learning - Labs

Hands-on lab notebooks for **COSI 165b: Deep Learning** at **Brandeis University**, taught by **Professor Dylan Cashman**.

Each lab is a Jupyter notebook (`.ipynb`). You'll open one most weeks typically in class to build and experiment with the ideas from lecture and the book. You can run them in **Google Colab** (nothing to install) or on your own machine with Jupyter.

---

## Attribution

These labs are **adapted from the official notebooks for *Understanding Deep Learning* by Simon J.D. Prince** (MIT Press, 2023), the textbook for this course. The book and its original notebooks are freely available at:

- **Book & notebooks:** https://udlbook.github.io/udlbook/
- **Original notebook source:** https://github.com/udlbook/udlbook

The *Understanding Deep Learning* labs are released under an MIT license. The notebooks here are lightly modified for use in COSI 165b, with gratitude to the author. If you find them useful, please go read the (free) book.

---

## Running a lab in Google Colab (recommended)

Colab runs the notebook in your browser on Google's machines — no setup, and a free GPU is available if a lab needs one.

**1. Open it.** From the lab's page on GitHub, click the **“Open in Colab”** badge at the top of the notebook. (No badge? Take the notebook's GitHub URL and replace `github.com` with `colab.research.google.com/github` — that opens it in Colab.)

**2. Save your own copy so your work persists.** Opening a notebook straight from GitHub gives you a **temporary** view — edits are *not* saved. Immediately do:

> **File → Save a copy in Drive**

This puts a personal copy in your Google Drive (in a folder called *Colab Notebooks*) and turns on autosave. From then on, your changes are kept.

**3. Come back to it later.** Reopen your saved copy any time from [drive.google.com](https://drive.google.com) or from Colab's **File → Open notebook → Recent**. Your code and outputs will be right where you left them — handy if you don't finish in class.

**4. Submit it for grading.** When you're done, submit the notebook **with its outputs**:

> **File → Download → Download .ipynb**

and upload that file to the corresponding assignment on the course LMS. (If the assignment asks for a share link instead, use **Share** on your Drive copy and follow the submission instructions for that week.)

---

## Running a lab locally (if you prefer your own machine)

If you'd rather use your own Python/Jupyter setup:

```bash
git clone https://github.com/<github-user>/<repo>.git
cd <repo>
python3 -m venv .venv && source .venv/bin/activate     # optional to set up a virtual environment
pip install -r requirements.txt                        # or: pip install jupyter numpy matplotlib torch
jupyter lab                                             # or: jupyter notebook
```

Then open the lab you want. Requirements vary a little by lab; each notebook installs or imports what it needs at the top.

---

## Getting help

Raise your hand to ask questions during class, or work with your neighber.  For conceptual questions, please come to office hours. If a notebook has a typo or a bug, let me know via email (or open an issue on this repo) and I'll fix it.

---

<sub>**Maintainer note (instructor):** to give each notebook a one-click Colab button, paste this as the first cell (a Markdown cell), replacing the path:</sub>

```markdown
<a href="https://colab.research.google.com/github/<github-user>/<repo>/blob/main/path/to/lab.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>
```

<sub>The badge renders both on GitHub and inside Colab, so students landing on the GitHub file can open it in one click.</sub>
