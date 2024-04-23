# Manuela_ABtesting_Python

The goal of the project was to analyse the results of an A/B test run by an e-commerce website 
and to help the company understand if they should implement the new page or keep the old page. 

I used Python and  linear regression to check A/B testing results and to compare the performance of two versions of websites – old and new. 
-	I gathered data from the company’s CSV files, cleaned them, and then prepared it for A/B testing by creating new tables
    with data on things like how long people spend on each website, how many pages they visit, etc. 
	Then I used a linear regression model to see if there is a relationship between which website they are on (new or old) 
	and these metrics.
-	For example, if the regression shows that people spend significantly more time on the new website compared to the old one,
    I could conclude that the new website is likely better. If the regression shows no significant difference, 
	then there may not be a clear winner between the two versions. 

 
Conclusions: I conducted multiple tests to check if the new company page will effectively increase conversion rates. 
All tests’ results suggested that the new page wouldn’t increase the conversion rate, so I failed to reject the null hypothesis.
That meant that the new page wouldn’t be better than the old page. 
I suggested it might be reasonable to conduct more tests (with more variables). 
However, I recommended keeping the old page while working on the new page improvements.
