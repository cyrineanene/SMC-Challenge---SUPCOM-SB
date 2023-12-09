# SMC-Challenge---SUPCOM-SB
Unraveling the complex connections between students' social relationships, physical and mental health, and emotional resilience, through data analysis.

## Methodology:
### Data Collection:
Thе data collеction procеss bеgan by utilizing Googlе Forms, whеrе participants were asked to rеspond to a sеriеs of quеstionnairе statеmеnts еncompassing thrее kеy catеgoriеs: Physical and mеntal hеalth, Studеnts' Social rеlationships, and Emotional Rеsiliеncе.

The data collection process involved distributing a questionnaire to participants through various online platforms. Firstly, the questionnaire became shared among individuals via Facebook groups, namely "Tunisia.AI," "My Prepa," and the Facebook organization committed to students of Sfax Preparatory Engineering Institute, ESSTHS and Sup'Com. Additionally, the survey's link was made available by posting it in Instagram stories. Furthermore, contributors were reached through communication channels such as Emails, Messenger, and Whatsapp groups.

Participants received a link to a Google Form survey: https://docs.google.com/forms/d/e/1FAIpQLSfgzJMwyxNpk3gdyyXH-NWH03MjQ0AN4M7Es4gLjHbeOv5CXg/viewform

### Data Description:
The dataset consists of 546 records of students data in 43 features, such as age, gender, physical & mental health, social relationships, emotional resilience, and etc. The target is "Academic Results" ranging from 1 to 10.

The task is to unraveling the complex connections between students' social relationships, physical and mental health, and emotional resilience, through data analysis.

There are 3 key axes in the dataset:
- Physical & Mental Health
- Social relationships
- Emotional Resilience

### Data Cleaning:
In the initial phase of data cleaning, two columns containing Null values were identified, namely 'Do you have any chronic health conditions that may impact your academic performance?' and 'On a scale of 1-10, rate your sleep quality?'. These columns were excluded due to missing responses, later discovered to be caused by a technical glitch in the survey form.

Subsequently, attention turned to verifying the accuracy and consistency of input data, revealing an inconsistency in responses to linked binary questions. Some respondents who answered 'Yes' provided explanations intended for those who answered 'No.' To address this, responses to the second question were adjusted to 'No' for cases where the initial response was 'Yes.'

Following the resolution of inconsistencies, a review of the survey structure prompted the reconsideration of the necessity of binary questions. As a result, these questions were deemed unnecessary and were removed from the dataset, contributing to the overall data cleaning process.
