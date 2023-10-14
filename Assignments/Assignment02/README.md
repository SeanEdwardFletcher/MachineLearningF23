# End to End Workflow for predicting Type II Diabetes

The notebooks in this file (parts a, b, c, and d) are the requirements for the second assignment in the Machine Learning course taught at the University of Southern Maine

Notebooks b, c and d are copies of notebook a, but with different focuses.

Notebook a used a small data set (2017-2018 only) from the CDC's NHANES dataset and trained a Stochastic Gradient Descent (SGD) Classifier on that data.

Notebook b uses data from more years (2014-2018), AND additional features.

Notebook c trained a multi-class SGD model.

Notebook d trains more models in addition to SGD: Ridge Regression, support vector machine, decision tree, random forests, and an ensemble model. It also explores how each of the models weighted each feature.

## Table of Contents

- [Usage](#Usage)
- [Data-Preprocessing](#Data-Preprocessing)
- [Results](#Results)

    
## Usage

I recommend downloading this file and then running it in Google Colab. The introduction section in the notebooks should show you exactly where to go and what to do.


## Data Preprocessing

Columns were renamed, null values were removed or imputed, categorical data was relabeled ordinally if possible, a target "diabetes" column was created.


## Results

All of the models performed badly. I discuss my view as to why that is the case at the end of notebook d in the "Most Influential Attributes" subsection under section "Grad Students / extra credit (notebook d)"


