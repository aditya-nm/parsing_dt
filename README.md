# What I want yall to do 

Just automate the process of generating these files. 

'Demo Tabs - Sheet1.csv' will be downloaded from Google sheets responses 
We will need to generate the files Insitutions.csv, Participants.csv, and Teams.csv 

## Insitutions.csv 

Format: Full_name, short_form
National University of Advanced Legal Studies,NUALS

Put cross team in the end. 

## Participants.csv 

Example of an entry:
Cross Team 
Weird
Devashish, Rito
adityamuralidhar3725@gmail.com,adityamuralidhar3726@gmail.com

Format: 
Instiution (Cross team for cross teams) 
Team name -1
Speaker-1, Speaker-2 
Email-1, Email-2
Team name -2
Speaker-1, Speaker-2
Email-1, Email-2

Important: Put cross teams first, and then follow alphabetical order of institution names. 
Team names can be of any order within an institution 

## Teams.csv 

Institution, count (number of teams of that institution)
Put count of cross teams first 
Alphabetically arrange the names of the other institutions

## Preferred way of running the code 

cat 'Demo Tabs - Sheet1.csv' | python basic_template.py > Institutions1.csv
(This way you don't have a lot of BT with opening and reading files)

## Extra steps

If you're really jobless and have finished this, you can try seeing whether you want to automate it further by using something called Selenium. It's used for web testing. Really helpful for doing laborious tasks, but might be overkill for this 