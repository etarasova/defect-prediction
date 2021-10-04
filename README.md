# Just-in-Time (Change-Level) Software Defect Prediction (JIT-SDP)

One direction is to examine feature transformation for JIT-SDP.

- src. Source code written as part of the project. 
- download. Downloaded data and replication packages.
- run. Run experiments. Contain shell scripts.

## Project description

To produce a  high-quality software developers use different quality assurance activities including source code inspection, unit testing, etc. Usually these methods are expensive and time-consuming. That's why several researchers came up with the idea of just-in-time defect prediction model that determines the high probability of bugs in the code at the commit time. So the developers can review their code immediately and make necessary changes while they still remember context. 
This model most likely can be improved by applying feature transformation methods. Exploration of these improvements and development of a new prediction model was the main goal of this project. Workflow of this new model will remain the same and will occur at check-in time.
The target audience of this project are developers who would like their code to be bug-free. 

### Technical overview of the project

This project is based on data analysis and prediction using statistical algorithms and machine learning. In simple terms, we take information from several open-source projects, split data on training and test sets, apply statistical algorithms to them, and try to predict with what probability this code contains  defects. Then we try to improve the existing model by exploring feature transformation methods and study their impact on the original version of the program.
 
## Project goals:

The first goal was to develop a system that attempts to identify defect-prone
code just-in-time.

The second goal of the project was to explore feature transformation
methods and their impact on the original version of the program.

## Project outcomes:

- Gather specs, put together project proposal
- Revise existing R scripts in the replication packages in
research paper
- Define the metrics to build a prediction model at change
level
- Define machine learning / statistical learning algorithms
- Rewrite existing R scripts into Python Jupyter Notebook
format
- Explore different preprocessing techniques and feature
selection techniques
- Create validation test scripts and conduct the validation
tests
- Analyze the validation results
