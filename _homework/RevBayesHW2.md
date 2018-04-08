---
title: Bayesian Methods HW2
teaching: 180
exercises: 0
questions:
- "How does a estimating a solution using a Bayesian method differ from likelihood?"
- "How does the output of a Bayesian tree search differ from that of likelihood or parsimony?"
objectives:
- "Explain what different models are telling us about evolution."  
- "How does a heuristic search differ under likelihood?"
- "Perform ML analyses using PAUP on LONI" 
---

## RevBayes Homework Two

1. In the slide move, try 5 different ranges for the slide move. Which one produces the best ESS? 
I randomly went from 0.1 to 10 for changing the delta value on the move slide function and the best result was chagning the value to 5 which produced an ESS value of 739. 
2. In the slide move, try 5 different ranges for the scale move. Which one produces the best ESS? 
Same as above, I changed went from 0.1 to 10 and the best one was a lambda value of 5 which produced an ESS value of 781.
3. How does using both moves change the ESS? Why does this make (or not make) sense? 
Using both the move_scale and move_slide functions works better than using one or the other for the same values. I assume it makes sense because we are utilizing two different functions within our MCMC which allows for a more accurate or focused sampling. 
4. What happens if you double one of the moves? For example, if you have a scale move that means the mu prime will be far from the mu, _and_ one that implies the mu prime should be really different? 
If I double the lambda for the move_scale function from 1 to 2 it increases the ESS value going from 739 to 901.However if I move from 1 to 10 I decrease the ESS and if I move from 1 to 0.1 I decrease the ESS below the 200 threshold.
##Try to have this done by the end of the work week, but if it's done by the end of spring break, that's OK, too.
