##Models Homework

1. From section "What is parsimony doing anyway?": How is the parsimony score impacted if you set a different number of characters to the custom model? For this answer, give the ctype command that you used to set up the model, and the number of parsimony steps in the best tree uncovered.
Using binary character matrix and making the assumption that characters are Dollo characters so a change from 0 -> 1 is possible but a reverse from 1 -> 0 is highly unlikely. 
The best parsimony score from the original character model was 67. Running the search again but indicating that character 1 is a dollo character (ctype my_ctype:1) we see an better parsimony score by one step. 
Changed the ctype to extend for characters 1 and 2 and the best tree score was 65. 
ctype my_ctype:1-2

2. From section "Transitions and Transversions". Try the same analysis, except with a 3-1 weighting on transitions to transversions. For this answer, paste below your transition matrix and provide the parsimony score. Also note if there were any major differences in the consensus tree built from the 2-1 transition-transversion model and the consensus tree built from 3-1 transition-transversion model.
Exhaustive search with equal weight on transition v. transversion - tree score - 1153
Exhaustive search with 2_1 weight on transition v. transversion - tree score - 1529
Exhaustive search with 3_1 weight on transition v. transversion - tree score - 1905
For both the 2_1 and 3_1 weight the tree topologies were exactly the same.
Transition matrix
command - ctype 3_1:1-898
usertype 3_1 = 4                [weights transversions 3 times transiti$
                a  c  g  t
        [a]     .  3  1  3
        [c] 3  .  3  1
        [g]     1  3  .  3
        [t]     3  1  3  .

3. So far, we looked at models that vary in two paramters, base frequencies and transition/transversion bias. Which parameter made a bigger difference? Does this make sense to you? Why or why not?
nst =1 
basefreq=1 
Score= 6424.20245

nst=2
basefreq=equal
Score = 6144

nst=1
basefreq=emp 
Score = 6303

nst=2 
basefreq=emp
5988.05924

Based upon these results the substitution rate parameter has the biggest impact on tree score and it makes sense given that the probability of changing should be more influential than empirical base frequencies.
Both substitution and empirical base frequencies combined had the biggest effect on tree score. 
## Commit and push to your copy of the repository by Friday at 5 pm.
