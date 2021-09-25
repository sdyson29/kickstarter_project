# Kickstarting with Excel
<img src="Outcomes vs Goals.png">
## Overview of Project
The first project for the UNCC Bootcamp is to familiarize the students with the high-level functionality of excel as a baseline for further data visualization projects. 
### Purpose
The data-set utilized is the Kickstarter, specifically, data from Louise. She was interested in knowing how different campaigns fared in relation to their launch dates and funding goals. By utilizing what was learned in the training module, I created multiple charts based on the criteria, filtered specific data using statistical formulas, and saved charts for future usage
## Analysis and Challenges
Analysis for this project came from the Kickstarter data-set to filter out theater outcomes and outcomes based on their goals, with data filtered from the main Kickstarter data-set through multiple charts and pivot tables. Most of the project followed most of the examples we utilized throughout the project. One quick realization was the relationship of having a correct formula. I ran into many early issues because of this problem, which often stalled me from advancing until the problem formula was corrected. The biggest obstacles I had to overcome with utilizing the "Countifs" function. I admittedly struggle for days to figure out the right formula to populate the cells. Once I overcame those obstacles, I was able to carry on with the project.  My initial issues with the formula stemmed from the formula that I was using (=COUNTIFS(Kickstarter!D:D,"= successful," Kickstarter!D:D, ">=1000", Kickstarter!D:D,"<5000", Kickstarter!U: U," plays"). I was able to correct and use the following code: =COUNTIFS(Kickstarter!$D:$D,"<1000",Kickstarter!$F:$F,"Successful",Kickstarter!$R:$R,"plays"). I am certain that better familiarity ith the functions will allow for faster codes with the cells. 	

PARENT CATEGORY	THEATER				
YEARS	(All)				
					
COUNT OF OUTCOMES	Column Labels				
ROW LABELS	successful	failed	canceled	Grand Total	
JAN	56	33	7	96	
FEB	71	39	3	113	
MAR	56	33	3	92	
APR	71	40	2	113	
MAY	111	52	3	166	
JUN	100	49	4	153	
JUL	87	50	1	138	
AUG	72	47	4	123	
SEP	59	34	4	97	
OCT	65	50		115	
NOV	54	31	3	88	
DEC	37	35	3	75	
GRAND TOTAL	839	493	37	1369	
					
					
					

Goal			Number Successful	Number Failed	Number Canceled 	Total Projects	Percentage Succesful	Percentage Failed				Percentage Canceled 	
Less than 1000		141					45					0				186						76%						24%							0%	
1000-4999			388					146					0				534						73%						27%							0%	
5000-9999			93					76					0				169						55%						45%							0%	
10000 to 14999		39					33					0				72						54%						46%							0%	
15000 to 19999		12					12					0				24						50%						50%							0%	
20000 to 24999		9					11					0				20						45%						55%							0%	
25000 to 29999		1					4					0				5						20%						80%							0%	
30,000 to 34999		3					8					0				11						27%						73%							0%	
35000 to 39999		4					2					0				6						67%						33%							0%	
40000 to 44999		2					2					0				4						50%						50%							0%	
45000 to 49999		0					1					0				1						0%						100%						0%	
	
### Analysis of Outcomes Based on Launch Date
The analysis of the outcomes based on launch date data suggest that there were more successful play in May and June where as the majority of the failed plays stem from the winter months of December and January. This suggest that some of the failures and successes are more do to the time of the year rather than the actually play.
### Analysis of Outcomes Based on Goals
The analysis of the outcomes based on goals suggest that that higher goals generally have a higher failure rate in contrast to goals that are $20,000 or less are generally more successful. The outlier to this is the goals between 35,000 to 45,000. All goals over that amount have a 100% fail.
### Challenges and Difficulties Encountered
One quick realization was the relationship of having a correct formula. I ran into many early issues because of this problem, which often stalled me from advancing until the problem formula was corrected. The biggest obstacles I had to overcome with utilizing the "Countifs" function. I admittedly struggle for days to figure out the right formula to populate the cells. Once I overcame those obstacles, I was able to carry on with the project.  My initial issues with the formula stemmed from the formula that I was using (=COUNTIFS(Kickstarter!D:D,"= successful," Kickstarter!D:D, ">=1000", Kickstarter!D:D,"<5000", Kickstarter!U: U," plays"). I was able to correct and use the following code: =COUNTIFS(Kickstarter!$D:$D,"<1000",Kickstarter!$F:$F,"Successful",Kickstarter!$R:$R,"plays"). I am certain that better familiarity ith the functions will allow for faster codes with the cells. 	
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
The first conclusion that I drew from the outcomes based on launch date coincides with my previous statement that May and subsequently June not only showed when most kickstarter begin but also that these months were more successful. The failures to the kickstarters begin when the weather and the season changed to where people were more likely to stay indoors and not go to a play. The best time for Louise to launch would be May with June being a close second. The worst time to start is toward the end of the year extending into January.  
- What can you conclude about the Outcomes based on Goals?
 My conclusion is that plays with a fundraising goal of 5000 or less saw a higher success rate than plays with higher goals. The goals with the lowest success rate occured when the goals where between 45,000 to greater than 50,000. Because of the higher success rate for the lower goals I would suggest that she set her goals between 1000 to 5000.
- What are some limitations of this dataset?
A limitation of the data set is that it can't be filtered more finely such as for the US dat, which states have the best success rate compared to other states. For example I would assume that a play in New York or California would be more succesful than a play on West Virginia.
- What are some other possible tables and/or graphs that we could create?
One table I would suggest is to give a demographic breakdown on where the success and failures are taking place. A graph that shows which states as well as the months would be helpful to establish if a city is worth the risk to start funding or is it better in another state. Additionally, I would like to know if the weather (Dec and Jan) have any effects on states with a more moderate year round temperture such as Florida.