# Data Analysis with Python: Cyber attacks
# Benjamin Rosendahl, November 2024

## Aims and projectives
The database "cyber" (source: Kaggle) lists cyber attacks by date and time, (attacked) country, attack type, severity level, action taken etc.
Using Python with the pandas, numpy, seaborn and madpotlib libraries, I will try to map the cyber attacks as follows:
- by country
- by month and year
- by attack type
- by severity level
- by action taken

## Research questions
- Which countries are attacked the most, which the least, and why?
- What is the average number of attack per time, per country and combined?
- What is the average severity level per attack type, country, per month, per year? What is the standard deviation?
- What is the median severity level per attack type, country, per month, per year? What is the standard deviation?
- When (year and month) do cyber attacks occur more frequently, when less?
- At what times and where is the severity level the highest?
- Are different countries attacked at different times, by different attack types and at different severity level?

## Assumptions
- The more advanced the country is, the higher is the number and severity level of the attack
- Different countries are attacked by different type of cyber attacks, according to their infrastructure (for example, cell phone network)
- There are regular high and low peak times for attacks (for example, summer - low, because of vacation, winter - high, because of larger amount of time spent indoors in front of computers)
- There are irregular peaks for attacks (for example, 2020 - Corona, everybody stayed at home, and face-to-face meetings where converted to Zoom meetings, meaning more exposure)
- Different actions are taken against different types of attacks, different levels of attacks and different countries    
