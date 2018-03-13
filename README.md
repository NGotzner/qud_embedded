# QUD effects on the interpretation of embedded quantifiers

The project is a follow-up on and combination of the following four papers:

- Chemla & Spector 2011
- Potts, Lassiter, Levy & Frank 2015
- Degen & Goodman 2014 
- Gotzner & Benz 2018

Wee add Degen & Goodman style QUD manipulations to the Chemla and Potts style paradigms for assessing the derivation of local implicatures.

The question: does the QUD affect the probability of implicatures in sentences where "some" is embedded under "each", e.g. "Each girl found some of her marbles"?

## Design

Critical sentence: "Each girl found some of her marbles"

World/pictorial condition: false (AANN), literal (AAAA), weak (AASS), strong (SSSS)


## Hypotheses

1. embedded implicatures are derived locally by the grammar
2. embedded implicatures are dependent on a contextual QuD making alternative readings relevant

## Predictions 

Mixed effects logistic regression with weak and literal condition by QuD (2*4)

1. Main effect of QuD, no interaction between QuD and pictorial condition
2. Main effect of QuD, interaction between QuD and pictorial condition

Baseline: No effect of QuD on false and strong control conditions


