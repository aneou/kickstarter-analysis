# kickstarter-analysis
An analysis of Kickstarter data to find trends helpful twoards a successful Kickstarter projects
---
## Overview
Using Kickstarter data from projects started between 2009 and 2017 analyses were performed to find trends that led to succesful Kickstarter projects. Particular attention was put to Theater and Play category/subcategory.

## Analysis
Using the given data it as refined by splitting the parent and subcategories into seperate columns. This allowed for easier filtering of the data. The date started and deadline were converted from UNIX timestamps to dates in MM/DD/YYYY format. Using the Date created the year for each project was found. A pivot chartwas made that showed project outcomes based on what month they were created and could be filtered based on year and Parent category. A second sheet was made that showed the what percentage of theater projects succeeded, failed or were canceled based on the goal amount.

## Results
![Theater_Outcomes_vs_Launch](https://github.com/aneou/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)
The best time to start a project is in May. As can be seen in the graph above the number of succesful projects reaches a peak in May with 111. The worst time to start a project is December.


![Outcomes_vs_Goals](https://github.com/aneou/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png)
As seen in the graph above the highest percentage of failed campaigns occured at the 45000 to 49999 range.

It should be noted that for the outcomes based on goals is that for projects over 20000 to 24999 range there was limited data as most had less than 10 projects in those ranges.
