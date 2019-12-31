## MIS284N Text Analysis
 Projects for Text Analysis


 - **Project 1 - Brand Association Analysis**
 
    We used Selenium to fetch messages from [Edmunds.com](Edmunds.com). We choose a discussion thread about entry level luxury sedans. The goal is to provide actionable recommendations to brand managers/ product managers/ advertising managers, based on the analysis of social media conversations. Used MDS maps as a visualization tool to convey our findings.


 - **Project 2 - Topic Modeling on Image Tags**
 
    1. Scraped image urls from National Geographic's instagram page ([@natgeo](https://www.instagram.com/natgeo/?hl=en)), and fed them into Google Vision Cloud to obtain image labels. Afterwards, we created a metric of engagement by using a weighted sum of # likes and # comments, the ran a logistic regression with engagement as the dependent variable, and image tags as independent variables.
    2. Did topic modeling with LDA on the image labels, and found the differences in the average topics for the quartiles with the highest and lowest engagement scores.
    3. Using the findings from the steps above, provide recommendations for National Geographic to increase engagement on its instagram page.
