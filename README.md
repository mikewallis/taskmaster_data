# taskmaster_data
csvs of taskmaster data

## tasks.csv 
### columns:
    Series, Episode, Task number, Task Type, Task Text 

I've grouped together tasks with the same task number if they make sense to group them together, but the tasks themselves appear in broadcast order, so Josh's counting tasks all have the same task number but appear non-consecutively in the list.

Task type column codes:
```
p = prize
r = pre-recorded task
rt = pre-recorded team task
s = live studio task
st = live studio team task
t = tie break
cx (where x is a number between 1-5) = sole task for just one contestant
```
cx also includes pre-recorded tasks where the instructions differ slightly eg Joe Lycett's additional "smile" during the portrait task
	

## contestants.csv 
### columns:
    series, contestant 1, contestant 2, contestant 3, contestant 4, contestant 5

## episodes.csv 
### columns:
    series, episode number, episode title, winner
