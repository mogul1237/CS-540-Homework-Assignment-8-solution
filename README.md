# CS-540-Homework-Assignment-8-solution

Download Here: [CS 540 Homework Assignment # 8 solution](https://jarviscodinghub.com/assignment/cs-540-homework-assignment-8-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

Question 1: Resolution Proof in Propositional Logic [25 points]
Given the knowledge base
p =⇒ (q =⇒ r)
use resolution to prove the query
(p =⇒ q) =⇒ (p =⇒ r).
Be sure to show what you convert to CNF and how (do not skip steps), and how you perform each resolution
step.
Question 2: Translation to First Order Logic [25 points]
Here are two riddles.
1. Question: What jumps higher than a building? Answer: Everything, buildings don’t jump.
2. There is a party of 100 politicians. All of them are either honest or liars. You know two things: 1. At
least one of them is honest. 2. If you take any two politicians, at least one of them is a liar.
For each riddle separately, do the following:
1. Write a plain English explanation for the riddle. This explanation should correspond to your logic
statement later. For example, the first riddle can probably be stated as “Everything that is not a
building jumps higher than a building,” or “Everything that can jump jumps higher than a building.”
But the explanation “Everything jumps higher than a building” might be problematic if everything
includes that building itself. Use your judgment to create a concise but correct statement. Remove
non-essential details. If you think the riddle is ambiguous, explain why so and which interpretation
you picked.
2. Define your First Order Logic (FOL) variables and their domains.
3. Define your FOL predicates and functions. Make sure you specify their values for ALL their input
combinations.
4. Give the FOL sentences.
Question 3: Hierarchical Clustering [25 points]
Consider the following six major cities. In the US: Madison, Seattle, Boston; and in Canada: Vancouver,
Winnipeg, Montreal.
1. Create a 6 × 6 table with the distances between the cities. Consult the website https://www.
distance-cities.com. Use the pink “fly distance” (the shorter distance), not the blue distance
by car. Use miles and round to the nearest mile.
2. Use hierarchical clustering with complete linkage to produce TWO clusters by hand. Specifically, show
the following in each iteration: (1) the closest pair of clusters; (2) the distance between them as defined
by complete linkage; (3) all clusters at the end of that iteration.
CS 540 Fall 2017
3. Now repeat the above question, but with the following constraint: at no point should a US city and
a Canadian city be put in the same cluster. Equivalently, whenever the complete linkage between two
clusters is due to two cities in different countries, treat the two clusters as infinity apart, regardless of
what other cities are in those two clusters. You still need to show all steps.
Question 4: K-means Clustering [25 points]
Given the following six items in 1D: x1 = 0, x2 = 2, x3 = 4, x4 = 6, x5 = 7, x6 = 8, perform k-means
clustering to obtain k = 2 clusters by hand. Specifically,
1. Start from initial cluster centers c1 = 1, c2 = 10. Show your steps for all iterations: (1) the cluster
assignments y1, . . . , y6; (2) the updated cluster centers at the end of that iteration; (3) the energy at
the end of that iteration.
2. Repeat the above but start from initial cluster centers c1 = 1, c2 = 2.
3. Which k-means solution is better? Why?
