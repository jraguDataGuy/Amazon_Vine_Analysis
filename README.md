# Amazon Vine Program - Pay To "Play" - Analyzing the Vine program with Video Games"
## Summary
Amazon started a program to try to increase valuable feedback for their customers. This program, entitled "Vine", was to currate reviewers for different product lines. The question today is: Does it work?
## Analysis
For this excercise, we used PySpark to sift through the data and determine how many paid versus unpaid reviews we were, while taking a look at a granular level of the quality of the reviews from the Vine program versus the general public. 
![Image](https://github.com/jraguDataGuy/Amazon_Vine_Analysis/blob/main/Resources/Original%20Data.png)
- We started with the data set pulled from Amazon in review of video game reviews
![Image](https://github.com/jraguDataGuy/Amazon_Vine_Analysis/blob/main/Resources/Totals%20for%20Paid%20and%20Unpaid.png)
- Using PySpark, we filtered our data to review paid vs unpaid totals. Please see the full coding in the "Vine_Review_Analysis.ipynb" file. 
![Image](https://github.com/jraguDataGuy/Amazon_Vine_Analysis/blob/main/Resources/Screen%20Shot%202022-02-27%20at%209.25.43%20PM.png)
- Ultimately, we were able to calculate the number of 5 star reviews received by Vine members and non-Vine members. 

Our results are as follows for the Video Game product line:
- 94 total paid reviews
- 40,471 total unpaid reviews
- 48 Five-Star reviews from paid reviewers
- 15,663 Five-Star reviews from unpaid reviewers
- 51.06% of Paid reviews were Five Stars
- 38.70% of Unpaid reviews were Five Stars
## Summary
Ultimately, the data initially may infer a positivity bias, as paid reviewers seemed to leave more Five Star reviews. Ultimately, we must call into question the viability of said statement, as the paid reviewers have a much smaller sample size than unpaid. To be sure, we could take additional measures. First of all, it would likely provide value to check all product lines at amazon to see if there is a trend for higher reviews from Vine Program members for different products. Our analysis is a snapshot of video game data only. It is reasonable to assume that Paid reviewers have diminished cost in obtaining a product, thus taking away a pain point in a review. We will need a much deeper dive in the program before making such a conclusion. 
