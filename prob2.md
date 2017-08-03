Trainer Bob has been training and preparing N of his special trainees for the Annual Mega Combat which is about to happen in a few weeks. Though all his trainees have put in their best efforts in the process yet at the end of the training period, some are better than others. Bob needs to ascertain the abilities of all his trainees so that he could register the right candidate into the right category at the contest. The obvious way of letting one combat against the other in a mock combat comes to his mind and he does the same. He randomly picks two of his trainees, lets them battle in a combat round and records the winner in the format (“A B” denoting A beats B). Bob conducts several such rounds (k rounds) and now has a list of results of the rounds. Now he wonders if on the basis of the results ,he can ascertain a unique order of the trainees in the descending order of their capabilities.
As usual he is stuck at this math and needs you to help.<br/><br/>
***You can assume that if A beats B and B beats C then A is automatically better than C (A will beat C if their round is conducted);
You can also assume no two trainees have identical abilities, one of them is bound to be better than the other.<br/>
The trainees are labelled from 0 to N-1.***

**Input:**<br/>
First line of input contains two integers N (no of trainees) and k (no of rounds of combat conducted).
K lines that follow contain an entry each in the form of two integers “A B” signifying that A beats B in 
the round i.e. A is better than B.<br/><br/>
**Output:**<br/>
If the results provided are enough to a ascertain the unique order of trainees arranged in decreasing order of their skill level, then output the order (the best trainee being at the top)
Otherwise output “cannot be decided”

**Constraints:**<br/>
1≤N≤1000<br/>
0≤K≤N(N-1)/2<br/>


**Sample Input:**<br/>
*5 5<br/>
0 4<br/>
4 2<br/>
3 1<br/>
4 3<br/>
0 1<br/>*

**Sample Output:**<br/>
*cannot be decided*<br/>

**Sample Input:**<br/>
*6 7<br/>
0 1<br/>
0 2<br/>
4 3<br/>
2 3<br/>
1 2<br/>
3 5<br/>
2 4<br/>*

**Sample Output:**<br/>
*0<br/>
1<br/>
2<br/>
4<br/>
3<br/>
5<br/>*

