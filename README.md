# *JobHunt2019*

## Scope: 
52 year old male. Master's degree in Data Science (recent grad). 30 years experience as a defense contractor systems engineer. Out of work (retired) for three years but roaring and ready to get back into the work force. How long will it take (days, weeks, months... egads!) to find a new job? The purpose of this project is to create a series of visualizations detailing the results of the job hunt.

## Methodology: 
The dataset and visualizations will be developed in parallel. Work will be done in excel (data entry) and Tableau (visualizations).

### dataset
The dataset has the following features:<br>
***Date*** - (date). Either the date of the submitted job application (by me) or the date a potential employer initiated contact.<br>
***Source*** - (factor). The source of the contact as either direct (self-initiated), employer (potential employer ititiated), or the job fair or job service (indeed, monster, dice, ziprecruiter, etc) used to initiate contact.<br>
***Company*** - (character). Company Name. <br>
***Industry*** - (factor). The industry general type. **(TBR)**<br>
***JobTitle*** - (character). The Job Title.<br>
***JobType*** - (factor). The general job area (data engineering, data science, project management, systems engineering, test engineering). This area may grow as my job search grows.<br>
***CallFromEmployer*** - (binary). Either 'call', signifying the employer reached out following application. 'NA' signifies that no call was ever received. I might just change this to 'nocall' later. <br>
***CallDate*** - (date). <br>
***Interview*** - (factor).'interview', signifies an interview was scheduled. 'NA' signifies that no interview was scheduled. I might just change this to 'nointerview' later. 'interviewpassed' means I passed on the job offer and no interview was scheduled.<br>
***InterviewDate*** - (date). <br>
***Status*** - (factor). <br>
***StartDate***<br>

### visualizations
Initial ideas for the dataset are: radial tree, dendrogram, modified sankay diagram. **(TBR)** <br>


References:
https://guides.library.duke.edu/datavis/vis_types