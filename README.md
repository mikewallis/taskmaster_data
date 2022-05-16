# taskmaster_data
csvs of taskmaster data

## tasks.csv 
### columns:
    Series, Episode, Task Type, Task Text (1), Task Text (2)

Task type column codes:
```
p = prize
r = pre-recorded task
rt = pre-recorded team task
s = live studio task
t = tie break
cx (where x is a number between 1-5) = sole task for just one contestant
```
cx also includes pre-recorded tasks where the instructions differ slightly eg Joe Lycett's additional "smile" during the portrait task
	
Task Text (2) is only used if there are additional parts to the task (eg "now eat the sandwich" or if one or two contestants are asked to do something very different, such as "Hula") null by default

## contestants.csv 
### columns:
    series, contestant 1, contestant 2, contestant 3, contestant 4, contestant 5

## episodes.csv 
### columns:
    series, episode number, episode title, winner
