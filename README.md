# Visual-Gale-Shapley
Visualizing Gale-Shapley Algorithm

This algorithm considers a group of n girls and n boys, and initilizes a random ranking of all girls for each boy and a random ranking of all boys for each girl. 

Then the algorithm runs of a day-by-day basis:
Each day all the guys propose to the top person in their list that they are not rejected by her yet, and all the girls who are proposed to, that day, accept the guy which is ranked best in their list. This process goes on until at the end of a day all the guys are married. Then it stops.

Acording to Gale-Shapley, this is a stable matching, in the sense that for any two couples, the at least one of the four people preferes to be with their current spouse.

The algorithm can be simplified quite a bit if in each step only one guy proposes and the girl right away decides to accept or reject the proposal, but I wanted to visualize it on a day-by-day basis of all possible proposals for that day. This requires more memory, but less cycles through the whole algorithm.
