# title: README

This document aims to collect Data Science resources and tie them together into logical and comprehensive learning paths. Most resources are either product-promoting, or product-specific. They tend to push people to learn in a direction best suited to using their package, framework, or language of choice. The content here will help you learn data science to meet *your* goals.

This is a fork of work done by [@aescay](https://github.com/aescay) on the DataRookiesLearningPortal package. Feel free to contribute here by forking this repository and sending a pull request!

## What is data science

<!-- Insert high-level description of data science here-->

## Basic core skills

Don't even try to learn Machine Learning without picking up these core skills. I repeat, *don't try to learn machine learning without picking up these core skills*. It can't be stressed enough how 90% of the work you'll be doing will involve some very basic skills. It's the Pareto principle, these 20% make 80% of the impact in your data science work. 

### Code

We do data science in computers. If you're doing data science on pen and paper, feel free to contact me because that's actually really interesting, but I digress. The most efficient way to actually work on a computer is to learn to code. Say what you want about Microsoft Excel. But generally, when the data gets really big, Excel becomes a bunch of crap you have to maintain with a lot of moving parts.

#### Scripting languages - R and Python

Learn the minimal required to get by with these two languages. Honestly, being a "deep" R or Python user does not matter all that much. If you can do a `group_by` in either of those languages, you're all set. Why do I limit it to the minimal? Most of the "data" work you'll be doing is not in R or Python but in SQL (see below).

Learn to read data in, transform it, get some basic statistics out of it, then spit it out again in either language, and you're good to go.

<!-- Material to recommend -->

Here are some specific code lessons.

Installing and Initial usage - [R]() [Py]()
The basics of navigating the language
[R](https://cran.r-project.org/doc/manuals/r-release/R-intro.html#Vectors-and-assignment)

- Open the link, read down and type code in own R console
- Skip Section 5
- Complete Section 7
- Section 8 optional
- Complete Secion 9
- Section 10 optional
- Section 11 optional
- Section 12 optional
- Complete Section 13
- Skip Section 14
- Skip appendices

[Py](https://docs.python.org/3/tutorial/introduction.html)

- Read all documentation from link above onwards until you complete Section 7

IDEs - [R: RStudio](https://www.youtube.com/watch?v=5YmcEYTSN7k) [Py: JupyterLab](https://www.youtube.com/watch?v=7wfPqAyYADY)

Reading in data - [R](https://readr.tidyverse.org/reference/read_delim.html) [Py](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.read_csv.html)

Picking and dropping variables -s [R](https://r4ds.had.co.nz/transform.html#select) [Py]()

Filtering - [R](https://r4ds.had.co.nz/transform.html#filter-rows-with-filter) [Py]()

Transforming variables - [R](https://r4ds.had.co.nz/transform.html#add-new-variables-with-mutate) [Py]()

In all honesty, R and Python are gateway drugs to data science. What I mean by this is that these two things will get you into this field (see every job description requirement for Data Analyst/Data Scientist, etc.), but being extreme at these isn't the shit. Once you get the job, or get projects going, you have to be prepared with the real guns.

<!-- Andrew's take -->

#### SQL

SQL is a really beautiful language. All your doing with it is you're getting data and telling the system how you want it. Now this in and of itself does not drive insights, but knowing SQL means you know the logic behind your dataset. It means you have a good grasp of the assumptions behind each variable (they call it field sometimes) and know how to pull them and what they mean.

Unfortunately, you really won't get exposure to a real-life database with the problems of real businesses until you get your first data science job BUT it's important to have this in your arsenal of tools anyway -- it's the most important one. 

<!-- Material to recommend -->

Learning the basics - [SelectStarSQL](https://selectstarsql.com/)
Some Medium-Hard Problems - [Zachary Thomas](https://quip.com/2gwZArKuWk7W)
Handy Query style guide - [DBT](https://github.com/fishtown-analytics/corp/blob/master/dbt_coding_conventions.md)

Play with this [dataset](https://colinfay.me/clients-db/).

### Statistics

#### Summary statistics1

#### Linear regression

### Business acumen

#### Top-line metrics

#### Cost metrics

#### Bottom-line metrics
