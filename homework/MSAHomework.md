## Alignment Homework

### Some of these questions do not have a right answer.

Fill out this worksheet (it can be opened in a plain text editor, like TextEdit [Mac] or TextWrangler [Mac] or Notepad [Windows]. Commit and push it to your copy of the course repo. I will pull your copies Friday at 5, and try to have comments for you by next class period, when we will discuss them. 

Feel free to work in groups, and discuss the assignments as needed. However, I do expect you to turn in your own copy, with answers in your own words.

1. Some algorithms treat a gap as a single penalty value, regardless of how large the gap is. Others assess a gap opening penalty, then a smaller gap extension penalty. When (i.e. what kind of biological scenarios) might you think it might be better to use one algorithm over the other?
Depending on the time scale of the taxa it might be beneficial to use a gap extension penalty such as in the case for closely related organisms. Assigning gap extension penalties would lower the score for recovered alignments with an excess amount of insertion or deletions, which we would not expect to find across shallow time scales. For more divergent taxa groups it would be reasonable to assign just a gap opening penalty and not an extension as we would expect to find greater frequencies of insertions and deletions. Consideration for the molecular marker in use is also another aspect that needs to be accounted for, especially if it has previoulsy been indentified as having numerous insertions or deletions. 
2. Breaking problems into subproblems is a common way to attack a tough problem. In the case of iterative alignments, we break the tree into smaller pieces. Are there biological questions for which you expect this would not be helpful?
I do not think there is a specific "biological" question in which iterative alignment might not be beneficial but I can see how the operational portion of the alignment might need modification depending on the time scale and sampel size in question. If the data set contains a large amount of individuals I would be cautious as to how few iterations were performed in the alignment as the repeated process would hopefully return more accurate cluster/groupings the more times it was performed. 
3. From the iterative alignment section: Which aslignment (pasta_script1, pasta_script2, pasta_script3) do you think is the "best"? By what criteria did you arrive at this decision?
N/A 