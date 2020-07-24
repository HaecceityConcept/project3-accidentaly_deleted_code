# project3
Project 3 deliverable for the Python Programming, Part-Time General Assembly Course

-----------------------------------------------------------------------------------

## Project Schedule

Once again, due to time constraints I was finding it extremely difficult to complete this project as I solely had available time during the weekend.

|  Day | Deliverable | Status
|---|---| ---|
|Day 1| Project Description | Complete
|Day 1| Priority Matrix / Timeline | Complete
|Day 2| Core Application | Complete
|Day 2| MVP & Bug Fixes | Complete
|Day 3| Final Touches | Complete
|Day 3| Deploy to GitHub | Complete

## Project Description
I was trying to analyse film related information obtained from 2 different data bases, which were merged for the purpose of this project.

## Functional Components

#### MVP
| Component | Priority | Estimated Time | Time Invested | Actual Time |
| --- | :---: |  :---: | :---: | :---: |
| Data Cleanse | H | 4hr | 8hr | 8hr|
| Data Analysis  | H | 4hr | 6hr | 6hr|
| Data Visualization  | H | 2hr | 4hr | 4hr|
| Total | H | 10hrs| 18hr | 18hr |

#### PostMVP - Future Steps, which will not be actioned in the Project 3
| Component | Priority | Estimated Time | Time Invested | Actual Time |
| --- | :---: |  :---: | :---: | :---: |
| More indepth Data Analysis | H | 20hr | n/a-hr | n/a-hr|
| Web Scraper to obtain live Film information | M | 40hr | n/a-hr | n/a-hr|
| Interactive visualizations, which are automatically updated with the newly scraped data | L | 10hr | n/a-hr | n/a-hr|
| Total | H | 70hrs| n/a-hr | n/a-hr |


## Additional Libraries
I was using:
- Pandas
- seaborn
- matplotlib

## Code Snippet

This cleanse method took me an eternity!

I am very happy that I managed to make it work!

```python
data_set["budget"] = data_set["budget"].fillna("$ 0").apply(lambda x: x.split(" ")[1])
data_set["usa_gross_income"] = data_set["usa_gross_income"].fillna("$ 0").apply(lambda x: x.split(" ")[1])
```

## Issues and Resolutions
- After applying .groupby(), series got transformed into indexes and i was not able to use that column anymore:
**ERROR**:  series not defined                                
**RESOLUTION**: Had to create another column with that would include all the values that were previously indexed


- To be fair, i had so many errors here and there along the way, it is hard to recollect all of them. It is very difficult to run through this course so quickly!
I am excited to take some time after this course to re-watch all the classes and internalise the concepts better.

-----------------------------------------------------------------------------------

- **Comfortability [0 to 5]**
**3** - I found Project 3 to be the hardest one so far. I feel like there was not as much time to get comfortable with the pandas as we had the time with other 2 projects.
I am looking forward to going through all of the study materials one more time!

- **Completeness [0 to 5]**
**5** - I know that this is by far not a very perfect, extensive or advanced piece of work, but I am still happy with it as I started from 0 and fount many time contraints along the way.
Hooray for progress! Python is still super difficult though!

- **What was a win?**
To make the freaking visualizations work, I was really struggling with them for some reason!

- **What was a challenge?**
I found visuals to be difficult to apply!

- **Any other comments**
Just happy that I managed to deliver all the homework and projects no matter how hard it was for me and am very excited to continue learning more Python and further develop this skill!
Thank you to all of the team, I know that sometimes I was most likely not the easiest to teach as found this very very hard.
Thank you for your patience, support and understanding! Britt, Suresh and Vonn - all of you are great and thank you for everything! <3
