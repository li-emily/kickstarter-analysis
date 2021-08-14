# kickstarter-analysis

## Overview of Project
### Purpose
The purpose of this project was to get us familiar with using Excel and PivotTables, as well as working with some data that is relatively straightforward. We were able to learn more about specific Excel functions, getting used to using data and basic statistics (such as standard deviation, mean, and median), representing data through visual charts and graphs, and managing as well as referencing multiple individual worksheets inside a Excel workbook. 

## Analysis
### Analysis of Outcomes Based on Launch Date
Based on launch date, it seemed that there were the most theater Kickstarters launched in May, June, July, and August.  However, not all of these months were equally successful. May had both the overall most Kickstarters launched, as well as the most successful Kickstarters as well, with 111 out of 166. However, most months had at least above a 60% success rate, excluding January, August, October, and the least successful month, December. Notably, December's success rate is just above 49%, around 7% lower than October. Overall, there were few theater campaigns canceled throughout the year; the range of cancelations by month went from 0 to only 7.

![Theater Outcomes by Launch Date graph](https://github.com/li-emily/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)


Based on the graph, you can see the spike in successful Kickstarter campaigns from late spring winding down into early summer. Additionally, the number of failed campaigns is much less varied compared to the successful outcomes, and canceled campaigns is a relatively small footnote.

### Analysis of Outcomes Based on Goals
Most theater (subcategory plays) Kickstarters, in order, had targeted goals of $1000 to $4999, less than $1000, and $5000 to $9999. Interestingly enough, the Kickstarters with the highest success rates were targeted goals of less than $1000, $1000 to $4999, $35000 to $39999, and $40000 to $44999, with 76%, 73%, and 67% success rate for the last two. Also notable is the low number of Kickstarters that had high goals, with less than 20 for each category above $20000. The Kickstarters with the highest failure rate were $45000 to 49999 and greater than $50000, with 100% and 88% failed, respectively.

The following graph is mirrored over the 50% success rate line, as percentage failed and successful are proportional to each other. 

![Outcomes Based on Goals graph](https://github.com/li-emily/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
Some challenges and difficulties that were encountered included proper referencing of cells across different worksheets in the workbook, as well as manipulating pivot table data. For Analysis of Outcomes Based on Goals, I initially forgot to add the condition of the subcategory 'plays' to a few of the lines and had both incorrect analysis statistics and a wonky graph. I also found myself slightly confused while attempting to sort through which variables needed for certain pivot tables, but attending the online class was helpful in rectifying this issue.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  - From Outcomes based on Launch Date, it seems that the best time to release a theater Kickstarter would be in May, and roughly late spring to early summer is also alright. Additionally, it seems that releasing a Kickstarter in December, October, January and August have a higher chance of failing, especially December.

- What can you conclude about the Outcomes based on Goals?
  - From Outcomes based on Goals, it seems that the sweet spot for for play based theater Kickstarters is a final goal of less than $1000 or from $1000 to $4999. Higher goals can also be successfully funded, but the willingness to fund expensive plays seems to be lower.

- What are some limitations of this dataset?
  - Some limitations of this dataset include how popular Kickstarter as a website is; there seems to be a decent amount of fundraising data collected from over several years, but since our data only comes from one source, it can be limited and biased in certain ways. There also seems to be a sizable amount of outliers which should not be given the same weight as the rest of the data (extremely expensive Kickstarters being very successful).

- What are some other possible tables and/or graphs that we could create?
  - Other data that could be explored would be the popularity of certain categories and subcategories, as well as country of origin, and year of creation. As we did analysis on only a certain portion of the data, it would be great to create some tables looking at other categories, with similar line graphs exploring how successful the Kickstarters were over time or based on funding goals. Ranking and seeing success rates as well as funding goals of different categories could help give a larger picture. While we did have some analysis of country of origin, with most Kickstarters originating from the US, a more thorough look at other countries like Great Britain is not a bad idea. Year of creation could be measured similarly to months, which would help evaluate the popularity of Kickstarter over the years. 

