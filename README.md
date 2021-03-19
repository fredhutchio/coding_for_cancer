# Coding for Cancer

**This project is currently under construction!**

The information presented below includes some options for how these materials might be developed.

## Description

These materials are supported by the [Science Education and Training](https://www.fredhutch.org/en/about/education-outreach.html)
program at Fred Hutchinson Cancer Research Center.

General objectives:
  - developing computational thinking
  - understanding the process of biomedical research
  - coding with R
- Questions these materials will help participants answer include:
  - What is research? How does biomedical research work?

Target audience:
- assumes no prior coding experience
- aimed at upper-level high school students (and potentially their teachers)

Delivery mechanism:
- two-week instructor-led summer course
- potential incorporation with [Articulate](http://articulate.com)
- self-directed, self-paced learning

## Suggestions for curriculum development

For a two week summer program,
the first week could focus on training and skills development,
with the second week providing time to explore inquiry-based questions with various levels of scaffolding

To create basic intro to R materials,
the [introductory materials](#class-material) using a clinical cancer dataset could be streamlined by:
- framing the example coding as research questions
- minimize redundancy in examples
- remove second half of class 2 (factors and creating data frames by hand)
- add very basic statistical testing (t-tests?) to complement data visualizations
- explicitly incorporating aspects of computational thinking and the research lifecycle, perhaps also reproducibility and open science principles?
- including additional challenge exercises

The inquiry-based coding explorations in the second week could build on:
- [these prompts](https://github.com/fredhutchio/practice-covid-19) created for practice coding using COVID-19 data; see R prompts [here](https://github.com/fredhutchio/practice-covid-19/blob/master/R/README.md)
- [these materials](https://github.com/FredHutch/bioDS-bootcamp) that include RNAseq analysis, taught to interns in summer 2019

## Class material

Materials for the original fredhutch.io materials include:

- [Class 1](class1.md): R syntax, assigning objects, using functions
- [Class 2](class2.md): Data types and structures; slicing and subsetting data
- [Class 3](class3.md): Data manipulation with `dplyr`
- [Class 4](class4.md): Data visualization in `ggplot2`

The data used for this course are from the [National Cancer Institute's Genomic Data Commons](https://gdc.cancer.gov).
Please see [Introduction to R](https://fredhutchio.github.io/r_intro)
from fredhutch.io for more information about how these data were compiled.

Please see the [instructor's guide](instructors.md)
for information on teaching these materials
and the [contributing guide](CONTRIBUTING.md)
for assistance in developing or modifying these materials.

**Required software**: Software requirements for this course include:
- [R and RStudio]()
- [tidyverse]()

This course is adapted from the following sources:
- [R for data analysis and visualization of Ecological Data](https://datacarpentry.org/R-ecology-lesson/) from Data Carpentry
- [Introduction to R](https://fredhutchio.github.io/r_intro) from fredhutch.io
