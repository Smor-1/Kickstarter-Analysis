# Kickstarting with Excel

## Overview of Project and Purpose

This project investigated Kickstarter data for Louise. She is spearheading a play called Fever and wants to know how launch date and funding goal impacts success rates. 

The purpose of the first part of this project was to determine how the launch date (in terms of month launched) for various kickstarter initiatives impacted their success--whether it be successful, failed or canceled most specifically analyzing the theatre data. The second part of this analysis investigated how the monetary funding goal of the kickstarter project impacted the outcome success. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

For this analysis I first created a pivot table using all of the Kickstarter data. I then filtered the data based on years and parent category, and specifically on theatre. I then created my rows based on the date created conversion data on the months and both my columns and values were the outcome data. I then filtered out the live projects and sorted the data on the successful column in descending order. I then created a line graph showing the theatre outcomes based on launch date, which can be found as a .png file. 
/Users/sandymo/Desktop/Data Bootcamp/Module 1 (Excel)/Assignment/Resources/Analysis_1.png
/Users/sandymo/Desktop/Data Bootcamp/Module 1 (Excel)/Assignment/Resources/Theater_Outcomes_vs_Launch.png

### Analysis of Outcomes Based on Goals

For this analysis I used the countifs function in excel to count the number of successful, failed and cancelled projects based on a funding goal range of <1000, between 1000 and 4999 and so on up to greater than 50000. I then found the sum of each row to determine the percent successful, percent failed and percent cancelled. This data was then graphed with the x axis as the funding goal ranges and the y axis as percentages for each outcome.
/Users/sandymo/Desktop/Data Bootcamp/Module 1 (Excel)/Assignment/Resources/Analysis_2.png
/Users/sandymo/Desktop/Data Bootcamp/Module 1 (Excel)/Assignment/Resources/Outcomes_vs_Goals.png

### Challenges and Difficulties Encountered

For the first analysis a challenge for me was knowing which data to put in my pivot table--the rows specifically. This was the only challenge for this part. 

For the second analysis I had two challenges. The first was knowing how to use the countifs function. I had trouble figuring out how to create a range of funding goals, but then realized I could just iterate on the same column and keep adding more filters and then I got the outcome I wanted. 
The second challenge I had with the second analysis was the spelling of cancelled. In the kickstarter data, it is 'canceled' with only one 'l', however I am use to spelling it 'cancelled' with two 'l's' which tripped me up momentarily. 

## Results

### What are two conclusions you can draw about the Outcomes based on Launch Date?

Firstly, we can conclude that the most successful campaigns for theatre were launched in the months of May and June. Secondly, we can conclude that overall, there are more successful than failed campaigns and very few ones that were cancelled, which is great news for Louise! 

### What can you conclude about the Outcomes based on Goals?

We can conclude here that in general, there is a higher percent of successful outcomes based on goal if the goal was <$15000. There seems to be an inflection point of sorts when your goal is higher than that number and the initiatives tend to fail more often with a higher goal. Also, the most successful projects have goals of <$1000.

### What are some limitations of this dataset?

A limitation I thought of was the lack of a standardized monetary value. What I mean by this is that the money is set as a number, but not converted into a relative currency based on what currency the goal was in (ex: USD, GBP, CAD...etc). Therefore, it is hard to make a universal statement on initiatives because we know currency from around the world is worth more or less than others! 
Another limitation is that in the blurb column sometimes the data is in a different language than English as well as the fact that it contains some characters that are not recognized by excel. 

### What are some other possible tables and/or graphs that we could create?

It would be interesting for me to look at the success of a project based on the number of backers they have. For example, it could be said that a higher number of backers leads to a greater percent chance for success. 
It would also be cool to see the relationship between the parent category of a project and how successful the kickstarter campaign was. For example, are technology initiatives more successful than plays? 
