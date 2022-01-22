# Get vaccine slot in Vilnius
![Vaccine](https://ichef.bbci.co.uk/news/976/cpsprodpb/16131/production/_115371409_gettyimages-1265248637.jpg)

## Goal
Gather dynamic changes of all available vaccine slots at Vilnius vaccination centers.
Register for Pfizer vaccine before a certain age group was allowed to register for vaccinating.

## Process
Infinite script which scrapes Vilnius vaccination website every 10 minutes*. It collects all of the information and updates the existing PostgreSQL database on Heroku.
Since the target was the Pfizer vaccine, thus the script sends an email once the Pfizer vaccine is available at any of the vaccination centers in Vilnius.

*website update time

## Results
Since the Vilnius vaccination center had too much AstraZeneca vaccine, they allowed early registration for any group.
However, there was a loophole that allowed to register for any vaccine available. The only catch - all other vaccines were out of stock.

* I have collected roughly 3 weeks of dynamic changes of available vaccines at Vilnius vaccination centers.
* My script with an email notification allowed me to get my family and friends Pfizer vaccine 3 to 4 weeks before their age groups have started the vaccination process.

