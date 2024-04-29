# Create a Regression Model

## Instructions

In this lesson you were shown how to build a model using both Linear and Polynomial Regression. Using this knowledge, find a dataset or use one of Scikit-learn's built-in sets to build a fresh model. Explain in your notebook why you chose the technique you did, and demonstrate your model's accuracy. If it is not accurate, explain why.

## Rubric

| Criteria | Exemplary                                                    | Adequate                   | Needs Improvement               |
| -------- | ------------------------------------------------------------ | -------------------------- | ------------------------------- |
|          | presents a complete notebook with a well-documented solution | the solution is incomplete | the solution is flawed or buggy |

## my work

X : mom IQ

### Lineaire:

Mean error: 20.4 (23.5%)
Model determination: 0.18122954949681425

### Lineaire + Polynomial:

Mean error: 18.5 (21.6%)
Model determination: 0.188914928509485

> une amélioration au niveau de model determination, mais pas significatif.

en ajoutant au X, l'age de la mere

### Lineaire:

Mean error: 19.5 (22.7%)
Model determination: 0.21084425271634366

l'age a amélioré le model determination

### Lineaire + Polynomial:

Mean error: 19.5 (22.8%)
Model determination: 0.24507321892731604

on dirait que l'age n'a aucun effet
