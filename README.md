# 🪐 Experiments with 20th-Century Speculative Fiction in HathiTrust

In order to make books that are still under copyright available for computational text analysis, HathiTrust Research Center has devised a machine-readable data format called Extracted Features. This repository contains data and Jupyter Notebooks for analyzing over three thousand works of speculative fiction in HathiTrust, all published between 1900-1999.

The tutorials here assume a working familiarity with Python and Jupyter Notebooks. For those new to both, *The Programming Historian's* ["Introduction to Jupyter Notebooks"](https://programminghistorian.org/en/lessons/jupyter-notebooks) by Quinn Dombrowski, Tassie Gniady, and David Kloster is a great starting point. We'll also be working with Pandas, a Python library for working with tabular data. Melanie Walsh's Intro to Cultural Analytics course includes a fantastic [overview of Pandas](https://melaniewalsh.github.io/Intro-Cultural-Analytics/03-Data-Analysis/00-Data-Analysis.html) (as well as the conceptual and ethical challenges inherent to data work in the humanities).

## Contents

### Code
- 👉 [`htrc_sf_experiments.ipynb`](https://github.com/gwijthoff/HTRC_SF_experiments/blob/main/htrc_sf_experiments.ipynb) is the main tutorial. Start there.
- instructions for running TF-IDF on a volume (TK)

### Data
- 📁 [`/data/SF_Extracted_Features_Full`](https://github.com/gwijthoff/HTRC_SF_experiments/tree/main/data) contains Extracted Features files for each volume (aka book)
- 📁 [`/data/thompson-mimno-SF-final-matches.tsv`](https://github.com/gwijthoff/HTRC_SF_experiments/blob/main/data/thompson-mimno-SF-final-matches.tsv) list of all SF volumes in HTRC identified by David Mimno and Laure Thompson
