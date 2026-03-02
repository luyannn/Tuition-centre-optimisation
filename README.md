# Tuition-centre-optimisation

## Overview
This repository contains integer programming solutions for assigning tutors to students under two scenarios.

## Scenarios
**Scenario A:** Minimise the total number of tutors assigned, then maximise tutor preference on tuition centre

**Scenario B:** Balance tutor workload as evenly as possible, then maximise tutor preference on tuition centre

## Visualisations
Includes visualisations of tutor workload, preference match breakdown, and the assignment heatmap to summarise and display the validity and accuracy of the optimisation model.

## How to Run python notebook
1. Ensure `Interview small data.xlsx`, `requirements.txt` and the notebook are all in the same folder
2. Open `Tuition_centre_optimisation_problem_code.ipynb` in Jupyter
3. Run all cells (dependencies are installed automatically in the first cell)
4. The model uses IBM CPLEX Community Edition. Download it from https://www.ibm.com/products/ilog-cplex-optimization-studio before running the notebook.

## Slides
Slides covering the decision variables, constraints, objective function, assumptions, results, and post-analysis are included in the repository as Tuition_Centre_Optimisation_Slides.pptx
