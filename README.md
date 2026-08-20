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

**4. Submit it for grading — share the link (don't download, don't email).** When you're done:

1. Make sure you've **run the cells** so your outputs are visible, and that your Drive copy is saved (it autosaves).
2. Click **Share** (top-right in Colab). Under **General access**, change *Restricted* to **“Brandeis University,”** and set the role to **Viewer**.
3. Click **Copy link.**
4. Paste that link into the lab's assignment on our Moodle page.

That's the whole submission — the link lets me open and read your notebook (code and outputs) with no file uploads and no email. A few notes:

- **Do not** use *Share → add people → my email*; that floods my inbox with notifications. Link-sharing sends nothing.
- Keep the access set to **Brandeis University / Viewer** so I can open it while signed into my Brandeis account.
- I see the **current** version when I open the link, and Moodle records your submission time — so once you submit, don't keep editing that copy.
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

I would still like for you to upload it to Google Drive and share it with me in the format above, to make grading easier.

---

## Getting help

Raise your hand to ask questions during class, or work with your neighber.  For conceptual questions, please come to office hours. If a notebook has a typo or a bug, let me know via email (or open an issue on this repo) and I'll fix it.
