## Last Week's Accomplishments


Got authorization working to check if someone is a TA. I pretty much reverse engineered the authentication that checks
if someone is an instructor and added similar code except modified it to be for a TA instead. It took a lot more
work and code than I had intially expected, as there are a lot of files that handle authorization.

## This Week's Plan

Continue work on the TA grading panel, hopefully create a new tab for TAs to use to grade and show what classes they're TAing for.
Now that authentication is working I plan to use that authentication to create a new section and page in the TA's navbar.

## Anything Blocking?
Past code that would update TA users does not seem to be working, so I can't test my TA code without 
modifying the database myself. If I create a new TA, it visually appears to be changed, but it does not actually
seem to change anything in the database.
## Notes
