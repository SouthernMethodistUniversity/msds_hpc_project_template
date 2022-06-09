# MSDS HPC and DS Final Project

The goal of semester project is to produce a single-submit, end-to-end,
performant pipeline for a complex and computationally intensive data analysis
workflow.

## Semester Project Details

- The analysis and dataset, possibly generative, needs to be
  sufficiently computationally intensive such that a reasonable
  performance analysis can be conducted.
- The specific dataset, analysis, and performance analysis will be
  agreed to at various stages during the semester.
- The pipeline should be single-submit, meaning that a single job is
  submitted to the queue system and then entire pipeline is run with
  each stage run on appropriate hardware with appropriately optimized
  software stacks.

## Semester Project Details

- The deliverable will be a ready to present slide deck in your GitHub
  repo, *i.e.* a job will be submitted on an SMU HPC cluster and then,
  sometime later with zero human interaction, a PDF presentation will
  appear in your GitHub repo.
- The presentation should discuss both the dataset analysis and
  performance analysis.
- Specific compute resources will be reserved for final testing and
  the production run.

## Repository Structure

- `bin`, Executable scripts.
- `src`, Non-directly executable source code.
- `data`, Datasets, where appropriate, and parameter files
- `docs`, Workflow documentation and location of the final deliverable
