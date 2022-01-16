## EMPLOYEE EXIT SURVEY

**Showcase:**
- data cleaning and analysis
- working with missing and duplicate data
- transforming and merging/concatinating data

**The goal of the analysis is to answer the following questions:**
* Are employees who only worked for the institutes for a short period of time resigning due to some kind of dissatisfaction? What about employees who have been there longer?
* Are younger employees resigning due to some kind of dissatisfaction? What about older employees?

**The source:**
* exit survey from employees of the Department of Education, Training and Employment (DETE) in Queensland, Australia
* exit survey from employees of the Technical and Further Education (TAFE) institute  in Queensland, Australia

A data dictionary wasn't provided with the dataset, so to confirm the definitions of the data, a manager who worked the surveys had to be contacted in person.

**Columns of significance (DETE survey):**
* `ID` - An ID used to identify the participant of the survey
* `SeparationType` - The reason why the person's employment ended
* `Cease Date` - The year or month the person's employment ended
* `DETE Start Date` - The year the person began employment with the DETE
* `Age` - Age of the participant of the survey

**Columns of significance (TAFE survey):**
* `Record ID` - An ID used to identify the participant of the survey
* `Reason for ceasing employment` - The reason why the person's employment ended
* `LengthofServiceOverall. Overall Length of Service at Institute (in Years)` - The lenght of the person's employment (in years)
* `Current Age. Current Age` - Age of the participant of the survey
