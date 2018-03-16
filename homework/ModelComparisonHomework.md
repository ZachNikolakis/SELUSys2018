## Model Comparison Homework

1. In our initial model comparisons, we compared K80, F81 and JC. K80 was the best, but ultimately, that branch of the nested diagram did not produce the best model. What does this tell you about the strengths and weaknesses of hierachical model testing?
This indiciates that cross comparison of models is not possible which can be misleading if the values support one branch of models even though it would not be the most optimal choice. This would also suggest that this type of  model selection would need to encompass more hiarchical avenues in order to find the best model choice.
2. Fill in the model table:

| Model | nst | basefr | Invariant sites? | Gamma Distributed rate heterogeneity | Score | LR |
|-------|-------|----|------|-------| -------|-----|
| Name of model-HKY           | nst=2   | basefr=EMP   | no | gamma =No  | L=5988.05924 | 2\*(lnL1-lnL2) =631.2033 | 
| Name of model-GTR           | nst=6   | basefr=EMP   | no | gamma =No  | L=6303.6608  | 2\*(lnL1-lnL2) =631.2013 |
| Name of model-GTR+Gamma     | nst=6   | basefr=EMP   | no | gamma =Yes | L=6131.20931 | 2\*(lnL1-lnL2) =344.903 |

2b. Which model was ultimately preferred out of your set of candidate models? 
HKY
3. In the RAxML call, change the name of the run, and the random number seed. Add the -N flag, and a number of your choosing, to get multiple replicates. Do you get the same score every time?

4. Use the treecompare script to compare if you got the same topology for each tree. 
