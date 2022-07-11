# Amazon_Vine_Analysis

Overview   
The purpose of this analysis is to determine if there is any bias  toward favorable reviews from Vine members in the data set analyzed. To accomplish this, the analysis compared review statistics between non-Vine members and Vine members.  The dataset chosen was from the multi-lingual section of Amazon reviews; specifically, the French language dataset.   

Using extract and transform methods on the database, the analysis calculated summary data for both groups. This summary data included the total number of reviews, the number of five-star reviews, and the percentage of five-star reviews of the total.   A comparison of the percentage of five-star reviews gave the result for evidence of bias.   

Data Transformation  
•	Data transformation filtered the original dataset from 254,080 to 10,942 by successively excluding records based on customers’ response to each review     
•	Initial screening eliminated reviews which had fewer than 20 customer response votes   
•	The resulting dataset was further reduced by filtering for positive response votes as 50 percent of the total number of votes for the review  
•	The resulting data frame was then divided into Vine members’ reviews and non-Vine members’ reviews  

Results  
 Vine  
•	Total Reviews 19  
•	Total 5-Star   9   
•	Percent 5-Star 47.37%     
Non-Vine   
•	Total Reviews 10,923  
•	Total 5-Star      5,194  
•	Percent 5-Star 47.55%  

Summary  
Based on the information from the analysis, there is no bias in the Vine members’ evaluation of the products reviewed.  

Expanding the analysis to encompass reviews with fewer than 20 votes would help demonstrate bias. 

