**School District Analysis**

**School District Analysis using Anaconda, Jupyter Notebook, Pandas & Python**

**Overview of Project**

The school board we ran initial analysis for suspects that there is academic dishonesty at play within Thomas High School’s reading and math scores. While an investigation is underway, we were tasked with performing another analysis on our data set after making slight changes to our code and methodology. More specifically, we were asked to replace Thomas High School’s data with NaNs values without altering the rest of our data set. From here, we perform another analysis and observed several changes in the overall results.
RESULTS

o	How is the district summary affected?

**Before Cleanup**

1.	Average Math Score = 79.0
2.	% Passing Math 75
3.	Average Reading Score = 81.9
4.	% Passing Reading 86
5.	% Overall Passing 65

![image](https://user-images.githubusercontent.com/91284661/138610044-22b89816-9ed1-41cd-a13e-38832bdacd72.png)

**After Cleanup**

•	Average Math Score = 78.9
•	Average Reading Score = 81.9
•	% Passing Math 74.8
•	% Passing Reading 85.7
•	% Overall Passing 64.9
 
![image](https://user-images.githubusercontent.com/91284661/138610051-e7037a81-9b6b-4d2f-9056-817395a91c90.png)

o	How is the school summary affected?

•	Thomas High School's % Overall Passing was 91, placing second

**Before Cleanup**

![image](https://user-images.githubusercontent.com/91284661/138610071-39464096-11a1-49f4-9012-4702fcc5969a.png)

**After Cleanup**

•	Thomas High School's % Overall Passing was 65, placing eight
 
![image](https://user-images.githubusercontent.com/91284661/138610013-ae2662d3-013b-46a8-bca2-1c4366fd44fa.png)

o	How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

From images and results above, it shows that replacing the ninth grade math and reading score affect Thomas High Schools position within the ranking significantly, dropping from the 2nd highest to 8th

**•	Math and reading scores by grade**
 
![image](https://user-images.githubusercontent.com/91284661/138610008-e1cf0459-9183-467a-91a9-7508790ed463.png)

**•	Scores by school spending**

![image](https://user-images.githubusercontent.com/91284661/138610004-a1713ed3-d874-497e-9216-84e0418fb98d.png)

**•	Scores by school size**

![image](https://user-images.githubusercontent.com/91284661/138609997-80dc14c6-0004-448e-a5b6-b90eb51bdfe8.png)

**•	Scores by school type**

![image](https://user-images.githubusercontent.com/91284661/138609984-a7ecbab0-00ec-4ea7-8c15-8b2de9c6a11d.png)

**Summary:** Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
As we summarize our finding, lets bring back the scores before and after our modifications to the data analysis.

**Before**

![image](https://user-images.githubusercontent.com/91284661/138609948-afeec353-b489-4089-9878-470586c1f5a7.png)

**After**

![image](https://user-images.githubusercontent.com/91284661/138609935-1755acd8-7060-4832-8f43-16bd17d1fcb5.png)

The first thing that is noticed is that the % Passing Math takes a very minor dip of only -.2% after we cleaned up our data. The second thing to note is that our % Passing Reading also take a minor dip of .3% after our data is cleaned up, this is in spite of Average Reading Score remaining unchanged after our data was cleaned up. Still, with average Math Score dipping from 79.0 to 78.9, it would seem to me that investigation of any academic dishonesty should begin focusing more on the math than reading. Either way, despite a seemingly negligible difference in overall passing scores after our data was cleaned up, it is apparent that the modification for Thomas High Schools particular data set do negatively affect overall passing % throughout the district which makes sense if the allegations of academic dishonesty are indeed true.

