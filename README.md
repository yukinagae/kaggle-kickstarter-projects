# kaggle-kickstarter-projects <!-- omit in toc -->

## Table of Contents <!-- omit in toc -->

- [Description](#description)
- [Summary](#summary)
- [TODOs](#todos)
- [Dependencies](#dependencies)
- [Installation](#installation)
- [Usage](#usage)
- [Project Organization](#project-organization)

## Description

TODO: not yet written

## Summary

TODO: not yet written

---

## TODOs

- [ ] Three Questions: related to business or real-world applications of how the data could be used
- [ ] Jupyter Notebook
  - [ ] Follow CRISP-DM process
  - [ ] Prepare Data
    - [ ] Handle categorical/missing values etc
  - [ ] Analyze, Model, and Visualize
- [ ] Create a GitHub Repository
- [ ] Create a blog post for a non-technical audience

## Dependencies

- Python3.6
- [Poetry](https://github.com/sdispater/poetry)

## Installation

```bash
cd kaggle-kickstarter-projects
poetry install
```

## Usage

```bash
cd kaggle-kickstarter-projects
poetry run jupyter notebook
```

## Project Organization

```text
[project root]
├── README.md
├── eda.ipynb <- EDA result shown as Jupyter Notebook
├── input <- contains Kickstarter Projects dataset
│   ├── ks-projects-201612.csv
│   └── ks-projects-201801.csv
└── pyproject.toml <- config file contains the project information and package dependencies etc.
```
