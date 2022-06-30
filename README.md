# Smite_Analysis
A Data analysis with some ML models on the data gotten from the Hi Rez Video Games SMITE

## GOAL

This is a long form project I was working on with the following goals.
- I wanted to understand how to work with an API and be able to pull data effectivly
- I wanted to be able to store large amounts of data into a personal SQL database
- I wanted to be able to use this SQL database effectivly to build up some data analysis knowledge
- I wanted to apply my data science knowledge to anser some questions about the game that would be easier to answer with the data

## Questions to Answer
- What classes are the Tankiest Squsihiest ect. (base stats analysis)
- Can you identify classes based on there base stats alone?
- What team comps give you the best chance of winning, does youre oponents comp matter in your choice of comp.
- Can we find a way of reccomending items to build based on the current items and gods in the game
- What contributes most to winning the game, build? gods? wards placed?
- Also want to use the data to build up dashboards for both gods base stats and item builder and maybe DPS calculator.
- Construct way to accuractly calculating Time to Kill an oponent.

## STRUCTURE
In the root folder of the database I have all of the current files, 
- API_Pull -> is a notebook that has the logic to pull from the Hi Rez API and put the data into the SMITE.db database
- SMITE.db -> this is the database file, unforunatly it is not on github as it exceeds the file size limit for Github LFS of 2 GBs. Currently working on a way to include it. if someone wants a copy feel freee to email me at mageena@tcd.ie and ill send a copy of the current file to you
- General -> This is a notebook where i do some basic EDA and have coded in an algorithm that calculates the average stats of gods over a period of games for a higher view(looking to imporve speed)
- MMR_ranges -. very quick analysis on the MMR ranges of different Queues, identifys when people of different skill are playing.
- Table_Creation -> File that initilises the three tables in the database.

## CONTACT
If anyone wants any more information of the project feel free to reach out to me at mageena@tcd.ie
