# PWC Call Center Power BI Dashboard
## Dataset Used
- <a href="https://github.com/kalim-git/Forage-PWC-Switzerland-Power-BI-Virtual-Internship/blob/main/01%20Call-Center-Dataset.xlsx">Call Center Dataset</a>
## Object
The object of this analysis is to create a dashboard in PowerBI for Call Center Manager that reflects all relevant Key Performance Indicators (KPIs) and metrics in the dataset.
## Possible KPIs include (but not limited to):
- Overall customer satisfaction
- Overall calls answered/abandoned
- Calls by time
- Average speed of answer
- Agent’s performance quadrant -> average handle time (talk duration) vs calls answered
## Table Details
The tabulation below shows the Call center table with its column names and their description:

| Column Name | Description |
|--- | --- |
| Call Id | Represents every unique observation in the dataset |
| Agent | Describes the name of the agent |
| Date | Describes the date of the call |
| Time | Represents the time of the call |
| Topic | Describes the topic of the caller |
| Answered | (Y/N) Describes if the call was Answered or not |
| Resolved | Describes if the problem was Resolved or not |
| Speed of answer(in seconds) |	Represents the speed of answer in seconds|
| AvgTalkDuration	| Represents the average talk duration of call |
| Satisfaction rating |	Represents the satisfaction rating of the agent during the call |

## Data Transformation
Data transformation was done in Power Query and the dataset was loaded into Microsoft Power BI Desktop for modelling.

The call center dataset is given by a table named: 
- Call Center which has 10 columns and 5000 rows of observation.
