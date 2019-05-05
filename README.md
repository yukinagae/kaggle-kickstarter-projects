# kaggle-kickstarter-projects <!-- omit in toc -->

## Table of Contents <!-- omit in toc -->

- [Description](#description)
- [Summary](#summary)
- [TODO](#todo)
- [Dependencies](#dependencies)
- [Installation](#installation)
- [Usage](#usage)
- [Project Organization](#project-organization)

## Description

[Kickstarter](https://www.kickstarter.com) is the world's largest funding platform for creative projects. 16 million people have backed a project, $4.2 billion has been pledged, and 161,886 projects have been funded since its launch from 2009.

In this repository, I will dive into the Kickstarter dataset, analyse it to answer the below three questions:

1. Is the number of projects increasing?
2. What factors may be correlated with the success/failure of the projects?
3. How to make your technology project successful? (Because I'm a tech person.)

## Summary

1. The number of projects has been decreasing after 2015, but the total amount of pledge has been increasing.
2. A category of the projects is one of the keys factors associated with the success/failure of the projects. Dance, Theatre and Comics are the top three successful categories.
3. Hardware and gadgets for your technology project to increase the success ratio.

---

## TODO

- [x] Three Questions: related to business or real-world applications of how the data could be used
- [x] Jupyter Notebook
  - [x] Follow CRISP-DM process
  - [x] Prepare Data
    - [x] Handle categorical/missing values etc
  - [x] Analyze, Model, and Visualize
- [x] Create a GitHub Repository
- [x] Create a blog post for a non-technical audience

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
│   └── ks-projects-201801.csv
└── pyproject.toml <- config file contains the project information and package dependencies etc.
```
