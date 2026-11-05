# About This Book

![2Sigma School](2sigma-school-logo.svg)

**Machine Learning Crash Course Exercises** · *Programming exercises from Google's Machine Learning Crash Course*

**2Sigma School** · Alps edition · Updated October 2026

These are the programming exercises from Google's Machine Learning Crash Course, on NumPy and pandas, linear regression, feature crosses, classification, neural networks and fairness. This Alps edition keeps Google's words and runs the data exploration in the page, with nothing to install.

| At a glance | |
|---|---|
| **15 exercises** | One notebook each |
| **126 cells that run** | NumPy, pandas and plotting code that runs in the browser |
| **120 cells for reference** | TensorFlow and Keras code, shown as written |

## How to Use It

Each exercise is a notebook. Run a cell on its own, or choose **Run all cells** in the toolbar to run the page from the top. Cells that need TensorFlow are shown for reference: TensorFlow does not run in the browser runtime yet, so those cells stay on the page, cannot be edited, and are stepped over by Run all. Read them alongside the results the page describes. Some cells have a blank for you to fill in, and show an error until you do.

> **Found a problem?** Teachers: choose Report Bug in the left menu, then select the bug icon on the item, or highlight the text. Students: tell your teacher. You can also email [support@alps.2sigma.us](mailto:support@alps.2sigma.us) with the book, chapter and page name.

## Credits

The exercises are by Google, from the Machine Learning Crash Course.

Copyright Google LLC.

Source: [https://github.com/google/eng-edu](https://github.com/google/eng-edu), in `ml/cc/exercises`.

License: [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0). This edition is shared under the same license.

This edition has been adapted for Alps. As with every book on Alps, its preparation draws on Alps's content-enhancement capabilities, which include the use of language models.

Google is not affiliated with, and does not endorse, this edition.

## Alps Compatibility Changes

The exercises' text is as Google wrote it. These are the only changes, and each one is there so the exercises run in Alps. The numbering of the book's chapters is not affected: this page comes after them.

**A table of contents is added.** The source is a collection of notebooks, so this edition adds one to make it a book. Each chapter takes its notebook's own heading as its title, with the dataset added where two would share a name. The `estimators` notebooks, which only point readers to the current exercises, are left out.

**Cells are marked, not rewritten.** A cell is shown for reference when it needs TensorFlow, Keras, `ml_edu` or TensorFlow Model Analysis, or when it reads a name only those cells define. A cell with a blank to fill in is marked as expected to fail until the reader completes it.

**Setup cells are split.** Where a setup cell imports both these libraries and pandas or plotting libraries, the imports of these libraries move to a new cell after it, so the rest of the setup still runs. No line of code is changed.

| Notebook | Cells for reference | Expected to fail | Setup cell split |
|---|---|---|---|
| Binary Classification | 15 | | |
| Binary Classification (Rice) | 10 | 1 | Yes |
| Addressing Bias and Fairness Issues in ML Models | 22 | | Yes |
| Introduction to Fairness in ML | 15 | | |
| Introduction to Neural Nets | 10 | | |
| Linear Regression (Chicago Taxi) | 7 | | Yes |
| Linear Regression with a Real Dataset | 9 | | Yes |
| Simple Linear Regression with Synthetic Data | 10 | | Yes |
| Multi-Class Classification | 9 | 1 | Yes |
| NumPy UltraQuick Tutorial | | 2 | |
| Representation with a Feature Cross | 8 | | Yes |
| Validation Sets and Test Sets | 5 | | Yes |
