# Lab 3 --- Titanic Passenger Survival Prediction (KNIME)

This folder contains the Lab 3 practical submission for **Titanic
Passenger Survival Prediction**, developed using **KNIME Analytics
Platform**.

The project demonstrates an end-to-end classification workflow using the
Titanic passenger dataset.

## Project Overview

-   **Project:** Titanic Passenger Survival Prediction
-   **Platform:** KNIME Analytics Platform
-   **Source dataset:** 891 passenger records × 12 columns
-   **Target column:** `Survived` (`0` = did not survive, `1` =
    survived)
-   **Model:** Decision Tree classifier

## Workflow Covered

1.  **Import and inspect** --- Load the Titanic CSV using CSV Reader and
    inspect the source data.
2.  **Prepare data** --- Remove unused columns with Column Filter and
    handle missing values.
3.  **Create a readable target label** --- Use Rule Engine to create
    `SurvivedLabel`.
4.  **Explore subsets** --- Use Row Filter to examine first-class
    passengers.
5.  **Analyze survival patterns** --- Use GroupBy and Bar Chart to
    compare survival by sex.
6.  **Study numeric relationships** --- Use Linear Correlation to
    inspect associations among numeric fields.
7.  **Train and predict** --- Partition the data into training and test
    sets, train a Decision Tree, and generate predictions.
8.  **Evaluate the model** --- Use Scorer and actual-versus-predicted
    grouping to review classification results.
9.  **Visualize and summarize** --- Present the survival distribution
    and final workflow overview.

## Key Results Reported

-   Total passengers: **891**
-   Survived: **342**
-   Did not survive: **549**
-   Female survival rate: **74.2%**
-   Male survival rate: **18.9%**
-   Test partition: **179 records**
-   Decision Tree accuracy: **78.8% (141 correct predictions out of
    179)**

The accuracy is the result reported for this particular train/test
split; it should not be interpreted as a guarantee of performance on new
data.

## Files

  -------------------------------------------------------------------------
  File                                  Description
  ------------------------------------- -----------------------------------
  `Titanic_KNIME_Workflow_Report.pdf`   Step-by-step practical report with
                                        workflow screenshots and model
                                        evaluation

  `Titanic.csv`                         Source dataset used by the KNIME
                                        CSV Reader

  `Titanic_Survival_Prediction.knwf`    Exported KNIME workflow, if
                                        available
  -------------------------------------------------------------------------

> Add the actual dataset and exported KNIME workflow files to this
> folder before submitting. The PDF report alone does not contain the
> editable KNIME workflow or a standalone CSV dataset.

## Software

-   KNIME Analytics Platform

## Repository

This Lab 3 project is part of the [Power_Bi_Lab1
repository](https://github.com/Adityakataria0/Power_Bi_Lab1).
