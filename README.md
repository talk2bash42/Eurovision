# Eurovision Song Competition Analysis

## Introduction

This project analyzes country performance and voting patterns in the Eurovision Song Competition, held annually since 1956 (except for 2020) among European Broadcasting Union (EBU) member countries. The dataset includes information on contestants, their entries, and voting details.

### Data Sources
- [Contestants Dataset](https://raw.githubusercontent.com/tturocy/eco7026a/main/2022-23/contestants.csv): Information on each country's entry and results.
- [Votes Dataset](https://raw.githubusercontent.com/tturocy/eco7026a/main/2022-23/votes.csv): Details of points awarded by each country to others.

## Table of Contents

1. [Internal Consistency](#internal-consistency)
2. [Country Success Analysis](#country-success-analysis)
3. [Ordering Effects](#ordering-effects)
4. [Reciprocity Analysis (pre-2016)](#reciprocity-analysis-pre-2016)
5. [Jury vs. Public Voting (2016 onwards)](#jury-vs-public-voting-2016-onwards)

## Internal Consistency

Verify the internal consistency of the data by confirming if points reported by contestants in the final match the sum of points reported as awarded in the votes dataset. Additionally, check if reported rankings align with points totals.

## Country Success Analysis

Determine the most and least successful countries considering appropriate measures such as votes, rankings, averages, medians, or variability. Account for variations in the number of participating countries and total points available.

## Ordering Effects

Investigate the potential for ordering effects in voting. Analyze if the running order affects the final ranking and explore possible behavioral biases related to song presentation sequence.

## Reciprocity Analysis (pre-2016)

Examine data up to 2015 to provide evidence supporting the hypothesis of reciprocity between country pairs. Explore if certain countries coordinate and vote for each other.

## Jury vs. Public Voting (2016 onwards)

Test the hypothesis that professional juries are less prone to reciprocity. Analyze voting patterns from 2016 onwards, comparing jury votes to public votes to determine potential biases.

Feel free to explore and contribute to this exciting analysis of the Eurovision Song Competition! Your insights into behavioral biases will add depth to this project.