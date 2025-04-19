# Dataset of Worker Perceptions of Workforce Robotics Regarding Safety, Independence, Job Security, and Privacy

## Contents
[Description](#description)

[Contributors](#contributors)

[Overview of Dataset](#overview-of-dataset)

[Demographic Summary of Dataset](#demographic-summary-of-dataset)

[Survey Questions and Response Value Choices](#survey-questions-and-response-value-choices)

## Description
With an aging blue-collar workforce spanning critical sectors such as construction, transportation and delivery, manufacturing, and warehousing, there is an increased need for collaborative workforce robots. Fear and perception of robotics in blue-collar job sectors are influenced by a range of demographic and socio-economic factors. In this paper we present a dataset consisting of 337 complete responses to a 40-question survey that we administered anonymously via Google Forms to blue-collar workers in Australia, Canada, United Kingdom, and United States of America working in six different job sectors, namely manufacturing, retail, transportation & delivery, warehousing, construction, and contract work. The questions range from worker demographics (7 questions), perceptions toward physical safety in the workplace (8 questions), perceptions toward working with human coworkers in the workplace (6 questions), perceptions toward working with robots (16 questions), and perceptions toward data privacy on robots (3 questions). 

## Contributors
Yu (Andrew) Liu, Gurpreet Kaur, Natasha Kholgade Banerjee, Sean Banerjee

[Terascale All-sensing Research Studio](https://tars-home.github.io)

## Overview of Dataset
The dataset consists of a single Comma-Separated Values (CSV) file ([WorkerSurveyDataRelease.csv](https://github.com/Terascale-All-sensing-Research-Studio/Workforce_Robotics_Survey_Dataset/blob/main/WorkerSurveyDataRelease.csv)) of the survey responses consisting of 338 rows, including a header row, and 40 columns. The data is provided in raw format, but filtered to excludes entries from participants who did not wish to have their responses publicly released. The 337 non-header rows in our dataset represents the complete responses provided by the participants. The header contains the questions asked to participants. For the list of questions and response value choices see the section titled [Survey Questions and Response Value Choices](#survey-questions-and-response-value-choices) below. The 40 columns contain responses for the 40 questions are broken into categories as follows: 

| Category |	Number of Questions	| Columns in Data |
| ------------- | ------------- | ------------- |
| Participant demographics |	7	| 1 to 7 |
| Perceptions toward physical safety |	8	| 8 to 15 |
| Perceptions toward working with coworkers |	6	| 16 to 21 |
| Perceptions toward working with robots	| 16 |	22 to 37 |
| Perceptions toward data privacy on robots	| 3 |	38 to 40 |
| Total Questions	| 40 |  |	

For each category we provide the list of questions and response value choices below in the section titled [Survey Questions and Response Value Choices](#survey-questions-and-response-value-choices). Response value choices are separated by a semi-colon, i.e. ";'. For response value choices that did not have a multiple choice option we indicate the type of entry, i.e. Text box, in the Reponse Value Choices column. All multiple choice question responses were single choice except where the question indicates "select all that apply". 

## Demographic Summary of Dataset
We summarize our dataset by providing counts and percentages of the following demographic variables: Country, Age, Self-Identified Gender, Job Domain, and Working Location.

| Demographic |	Count |	Percentage |
| ------------- | ------------- | ------------- |
| **Country** | | |	 	 
| Australia	| 24	| 7.12% |
| Canada |	130	| 38.58% | 
| UK	| 101	| 29.97% | 
| USA	| 82 |	24.33% |
| **Age**	| | 	 
| 18 - 29 | 119 |	35.31% | 
| 30 - 39	| 93 |	27.60% | 
| 40 - 49	| 76 | 22.55% | 
| 50 - 59	| 33 | 9.79% | 
| 60 - 69	| 11 | 3.26% | 
| 70 - 79	| 5 | 1.48% | 
| **Self-Identified Gender** |  | 	
| Female	| 126	| 37.39% | 
| Male	| 209 |	62.02% | 
| Prefer not to say	| 2	| 0.59% | 
| **Job Domain** |  | 
| Construction	| 40	| 11.87% | 
| Contract Work	| 24	| 7.12% | 
| Manufacturing	| 57	| 16.91% | 
| Retail	| 45	| 13.35% | 
| Transportation / Delivery / Postal Services	| 48	| 14.24% | 
| Warehousing	| 123	| 36.50% | 
| **Working Location** | |  		
| Rural	| 47	| 13.95% | 
| Suburban |	103 |	30.56% | 
| Urban, large-size city |	65 |	19.29% |  
| Urban, mid-size city |	122	| 36.20% | 

## Survey Questions and Response Value Choices

### Participant Demographics

The following demographic information was collected from each participant:

| Dataset Column | Question | Response Value Choices | 
| ------------- | ------------- | ------------- |
| 1 | Country: | Australia; Canada; United Kingdom; United States of America
| 2 | Age: | 18-29; 30-39; 40-49; 50-59; 60-69; 70-79; 80-89 
| 3 | Self-identified gender: | Male; Female; Prefer Not To Say; Other (Text box)
| 4 | Height (feet' inches") | Text box |
| 5 | Weight (pounds) | Text box |
| 6 | Job domain: | Construction; Contract Work; Manufacturing; Retail; Transportation/Delivery/Postal Services; Warehousing |
| 7 | Working Location: | Rural; Suburban; Urban – large-size city; Urban – mid-size city |

### Perceptions Toward Physical Safety 

The following questions were asked to participants regarding their perceptions toward physical safety in the workplace:

| Dataset Column | Question | Response Value Choices | 
| ------------- | ------------- | ------------- |
| 8 | In an average week how many hours do you spend lifting heavy objects? | 0-5 hours; 6-20 hours; 21-40 hours; 40+ hours | 
| 9 | How many injuries have you had over the past 6 months related to your job? | 0 to 2; 3 to 5; 6 to 10; 11 or more | 
| 10 | What has been the nature of your injuries (select all that apply)? | Musculoskeletal injury (lower back, knee); Slip, trip, or falls; Impact from objects; Other (Text box)| 
| 11 | How often do you feel that you encounter barriers to safety in your occupation? | Never; Rarely; Sometimes; Often; All the time | 
| 12 | How often do you feel that you encounter barriers to performing your task in your occupation? | Never; Rarely; Sometimes; Often; All the time | 
| 13 | What is the nature of these barriers (select all that apply)? | No barriers; Social, e.g., I do not feel that I belong to a team; Psychological, e.g., I feel stressed out by the nature of my work or by the lack of safety; Physical, e.g., I do not feel that I have enough physical help to be safe or to carry out my tasks | 
| 14 | Do you feel comfortable discussing barriers with your co-workers or your superiors? | Occasionally; Yes; No | 
| 15 | How concerned are you that barriers may cause you to have reduced longevity in your job? | Not concerned; Somewhat concerned; Very concerned | 

### Perceptions Toward Working with Coworkers

The following questions were asked to participants to garner perceptions toward coworkers when needing assistance in the workplace:

| Dataset Column | Question | Response Value Choices | 
| ------------- | ------------- | ------------- |
| 16 | Do you (or would you) feel comfortable receiving assistance from a co-worker during lifting operations? | Not applicable, I do not have a co-worker; Not comfortable; Comfortable; Somewhat comfortable; Very comfortable |
| 17 | When you require assistance from a co-worker in lifting, how do you (or would you) expect to receive it? | Not applicable, I do not have a co-worker; Not applicable, as I prefer to work on my own; I prefer to let my co-worker know that I need assistance; I prefer that my co-worker figure out that I need assistance; It depends on the package I am carrying and how I feel at the time |
| 18 | When receiving assistance from a co-worker in lifting, what form of interaction do you (or would you) prefer (select all that apply) | Not applicable, I do not have a co-worker; Not applicable, as I prefer to work on my own; I prefer that my co-worker and I work together; I prefer that my co-worker intervene and take over the lifting task; It depends on the package I am carrying and how I feel at the time |
| 19 | When a co-worker assists you in your tasks, do you feel that they respect your independence at task performance? | Not applicable, I do not have a co-worker; Not applicable, as I prefer to work on my own; Not at all; Somewhat; Absolutely |
| 20 | If a co-worker assists you in your tasks, do you feel worried that your job is at stake? | Not applicable, I do not have a co-worker; Not at all; Somewhat; Absolutely |
| 21 | If a co-worker assists you in your tasks, would you feel safe at task performance? | Co-worker does not care whether or not I have a lifting-related injury; Co-worker ensures I do not have lifting-related injuries, but I would be worried that co-worker would injure me; Co-worker ensures I do not have lifting-related injuries |

### Perceptions Toward Working with Robots

The following questions were asked to participants to garner perceptions toward working alongside robots of varying capabilities in the workplace:

| Dataset Column | Question | Response Value Choices | 
| ------------- | ------------- | ------------- |
| 22 | Have you worked along-side or with robot assistants before on the job? | Yes, and the robot was involved in lifting operations; Yes, but the robot was not involved in lifting operations; No |
| 23 | If you have worked alongside robots in lifting operations, did the robot perform lifting by itself, or did you and the robot work together? | Not applicable (I have not worked alongside a robot in lifting operations); The robot and I worked together to lift the package; The robot performed the lifting by itself |
| 24 | If you have worked alongside robots in lifting operations, did you feel safe working alongside the robot? | Not applicable (I have not worked alongside a robot in lifting operations); Not safe; Somewhat safe; Safe; Very safe |
| 25 | If you have worked alongside robots in lifting operations, did you feel that the robot respected your independence at task performance? | Not applicable (I have not worked alongside a robot in lifting operations); Not at all; Somewhat; Absolutely |
| 26 | If you have worked alongside robots in lifting operations, did you feel worried that your job is at stake? | Not applicable (I have not worked alongside a robot in lifting operations); Not at all; Somewhat; Absolutely |
| 27 | If a robot is available as a lifting assistant, what would you prefer? | The robot never helps; The robot helps only when I ask it to; Sometimes I should be able to ask the robot to help, and sometimes the robot should figure out that I am struggling on its own; The robot always helps and does all the lifting; The robot helps by automatically detecting if I am struggling without me asking |
| 28 | If you want the robot's help, what would you prefer? | It depends on the package and how I am feeling, i.e., sometimes the robot and I should work together, and sometimes it should lift the package on its own; The robot should lift package on its own; The robot and I should work together to lift the package; Not applicable, I do not want a robot's help |
| 29 | If a robot always lifted packages for you, would you feel that | The robot ensures I do not have lifting-related injuries; The robot does not care whether or not I have a lifting-related injury; The robot ensures I do not have lifting-related injuries, but I would be worried that the robot would injure me |
| 30 | If a robot always lifted packages for you, would you feel that | The robot respects my independence; The robot does not respect my independence |
| 31 | If a robot always lifted packages for you, would you feel that your job is at stake? | Not at all; Somewhat; Absolutely |
| 32 | If a robot stood by the side, and never lifted packages for you, would you feel that | The robot ensures I do not have lifting-related injuries; The robot does not care whether or not I have a lifting-related injury; The robot ensures I do not have lifting-related injuries, but I would be worried that the robot would injure me |
| 33 | If a robot stood by the side and never lifted packages for you, would you feel that | The robot respects my independence; The robot does not respect my independence |
| 34 | If a robot stood by the side and never lifted packages for you, would you feel that your job is at stake? | Not at all; Somewhat; Absolutely |
| 35 | If a robot helped you with lifting only when you need its help, would you feel that | The robot ensures I do not have lifting-related injuries; The robot does not care whether or not I have a lifting-related injury; The robot ensures I do not have lifting-related injuries, but I would be worried that the robot would injure me |
| 36 | If a robot helped you with lifting only when you need its help, would you feel that | The robot respects my independence; The robot does not respect my independence |
| 37 | If a robot helped you with lifting only when you need its help, would you feel that your job is at stake? | Not at all; Somewhat; Absolutely |

### Perceptions Toward Data Privacy on Robots 

The following questions were asked to participants to garner perceptions toward privacy when robots use different forms of sensing to determine need for assistance:

| Dataset Column | Question | Response Value Choices | 
| ------------- | ------------- | ------------- |
| 38 | To detect whether you need help, the robot may have to record data about you, e.g., it may need to record your audio to hear your request, or it may need to record video to determine if you are struggling. If your audio data is recorded, how concerned are you about privacy issues? | Not concerned; Somewhat concerned; Very concerned |
| 39 | If your video data is recorded, how concerned are you about privacy issues? | Not concerned; Somewhat concerned; Very concerned |
| 40 | We now have computer software that can detect the movement of your body joints from video data. If the robot uses a camera to record your video, detect and store the movement of your body joints, and delete the video, how concerned would you be about privacy issues? | Not concerned; Somewhat concerned; Very concerned |
