java c
Problem #1 – Bayes’ Law: 
As part of a routine medical exam to obtain a term life insurance, a man is tested for HIV using the RAPID test. His result turns out to be positive. Alarmed, he asks his doctor whether he definitely has HIV. The doctor assures him that the test is good (over 95% correct), but not infallible. To be precise, the doctor tells him that the sensitivity of the test – P(Positive | HIV) - is 0.99 and that the specificity – P(Negative | No HIV) is 0.98. The man is a heterosexual and has never used drugs with needles. The doctor estimates that his prior probability – P(H) – was about 0.0001, before taking the test. 
What is:
1. The man’s posterior probability of having HIV?
Extra Credit (1 point): 
2. The doctor recommends a second, independent test. If this is also positive, which is his posterior probability now?
3. If the posterior probability after the second test is still low, a third, independent test would likely resolve the issue. What is the posterior probability, if the third test also is positive?
All tests have the same sensitivity and specificity.
Reminder:  

Parameters: 
· Hypothesis (H)= Haning HIV
· Null Hypothesis (H’) = Not having HIV
· Evidence (E)= Tested Positive for HIV
· Evidence, given Hypothesis (E|H) = Tested Positive for HIV, given he has HIV
· Evidence, given null Hypothesis (E|H’) = Tested Positive for HIV, given he doesn’t HIV
· Null Evidence, given null Hypothesis (E’|H’) = Tested negative for HIV, given he doesn’t HIV, {the complement of (E|H’): P(E|H’) + P(E’|H’) = 1} 
· Hypothesis, given Evidence (H|E) = Haning HIV, knowing the man tested positive ←Find 
Problem #2 – Statistical Distribution: The Bureau of Finance has always been a relaxed place to work. Employees are allowed 60 minutes for a lunch break and are not required to sign or punch in or out. Recently the head of the Bureau has come to suspect employees are taking advantage of the comfortable atmosphere by disappearing for more than 60 minutes at lunch. He decides to check his suspicions by monitoring for a week the number of minutes spent at lunch by each employee in a typical department of the Bureau. He considers a lunch break of up to 65 minutes acceptable, longer than that unacceptable. Below are the data collected (rounded up by minutes). Should the head of the Bureau be concerned about the time taken at lunch by employees? Present the data in ways to support your answer.Tips (you can delete these tips in your submittal):1. Convert the continuous variable “time spent at lunch” to a discrete variable, the first class starts at 60, and the class interval of 5.2. Do not use Excel Histogram function, we need to see the tabulated data 
3. You can use Excel’s “COUNTIF” Function, or just hand-count the number of instances in each class4. Use column chart to plot the % histogram and scatter plot for the cumulative % and make assessments based on % above 65 min.Minutes Spent at Lunch 
75 
93 
66 
68 
60 
67 
63 
85 
78 
86 
73 
77 
69 
63 
64 
87 
93 
61 
80 
65 
82 
77 
60 
64 
62 
84 
64 
63 
63 
61 
70 
67 
76 
73 
72 
90 
80 
70 
89 
82 
Extra Credit (1 point) 
#2.1 Calculate the mean (average) using a) the raw data, and b) Sx.P(x) formula and show the error of this discrete approximation.  Then reduce the Bin (Class) interval to 4, then 3, then 2, then 1, recalculate the mean using Sx.P(x) formula for each scenario and show how the accuracy of the  discrete approximation increases as bin interval decreases, using a x-y graph (interval size on x-axis, calculated mean on Y-axis.
#2.2 Review the standard statistical distributions we discussed in the class and, with visual inspection, decide which statistical distribution might be appropriate for this data, and why you think the data has such a behavior, based on human behavior. (work ethics, dedication, etc.).  How would this graph look for Google X (research before answering!)
Problem #3 – Decision Tree: The summer Job 
Sam Chu was in a quandary. With two job offers in hand, the choice he should make was far from obvious. The first alternative was a j代 写Problem #1 – Bayes’ Law
代做程序编程语言ob as an assistant at a local small business, let’s name this one the “In-Town Job”; the job would pay minimum wage ($5.25 per hour), require 30 to 40 hours per week, and the hours would be primarily during the week, leaving the weekends free. The job would last for 13 weeks, but the exact amount of work, and hence the amount Sam could earn, was uncertain, with the following likelihoods: 30 hours with 15%, 34 hours with 45%, and 40 h0urs with 40% likelihood. On the other hand, the free weekends could be spent with friends, that is fun level 3 in table 1 (with 100% certainty).
The second alternative was to work as a member of a trail-maintenance crew for a conservation organization.  This job would require 10 weeks of hard work, 40 hours per week at $6.50 per hour, in a national forest in a neighboring state, let’s name this one the “Forest Job”. The job would involve extensive camping and backpacking. Members of the maintenance crew would come from a large geographic area and spend the entire 10 weeks together, including weekends. Although Sam had no doubt about the earnings this job would provide, the real uncertainty was what the staff and other members of the crew would be like. Would new friendships develop? The nature of the crew and the leaders could make for 10 weeks of a wonderful time, 10 weeks of misery, or anything in between.
1. Prepare a simple 6 element influence diagram for this problem using the following symbols, connected with arrows:
a. Decision: Rectangle (straight edges)
b. Input variables (Circle)
c. Individual Consequences Rectangle (beveled edges)
d. Aggregate Consequences Rectangle (bold beveled edges)
2. Prepare the complete decision tree for this problem, with:
a. Scenarios: “In-Town job” and “Forest job”
b. Choices for each scenario: probabilities of Income and Fun level
c. Consequences: Income level and Fun Level
Note: you will come up with your own “preference probabilities” for different fun levels for the forest job, using the “probability wheel”, like what you did in the class exercises
3. Calculate the expected value of each objective for each objective, for each scenario:
a. EV(In-Town job, Salary)	VS	EV(Forest job, Salary)
b. EV(In-Town job, Fun Level) 	VS	EV(Forest job, Fun Level)
Can you decide which alternative to pick? Let’s make your job easier:
4. Let’s use the “Personal Indifference Selling Price (PISP)” concept we learned in the class workshop to convert the fun levels to currencies.
a. Think in the order of magnitude of the salaries: “How much $#,###.## should I pay you to be willing to switch from level 5 to level 4, then from level 4 to level 3, etc.
b. Combine the two consequences into one $ value and then calculate then calculate the expected value of each option and show which one you would pick.
Extra Credit #3 (1point): Now go back and revisit your assumptions and see what changes could result in changing your selection and explain it.
Note: show your calculations clearly. You will lose points if you don’t even if your answer is correct!
Warning: You will find the reference document online.  The solution they provide is very different from what we are trying to do here. Please do not copy from the reference, you will lose all points at the minimum! 
Rank 
Description of level of fun Pref. Prob.
(Forest Job) 5
(Best) A large, congenial group. Many new friendships made. Work is enjoyable, and time passes quickly. 100% 4
A small but congenial group of friends. The work is interesting, and time off work is spent with a few friends in enjoyable pursuits. 
3
No new friends are made. Leisure hours are spent with a few friends doing typical activities. Pay is viewed as fair for the work done. 
2
Work is difficult. Coworkers complain about the low pay and poor conditions. On some weekends it is possible to spend time with a few friends, but other weekends are boring. 
1
(Worst) Work is extremely difficult, and working conditions are poor. Time off work is generally boring because outside activities are limited or no friends are available. 0% 
Table 1 – Fun Levels descriptions and “your” preference probabilities 



         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
