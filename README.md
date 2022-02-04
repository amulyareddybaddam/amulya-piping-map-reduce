# amulya-piping-map-reduce

# Map-Reduce
- processing and generating the big datasets using piping method in map-reduce

## Data Description:
- This Dataset gives in detailing about heart health in humans such as age , gender, heartrate and the cholestrol percentage.

## Study:
- From this dataset i can estimate the average heart health in humans.

## Execution:
- ***Mapper File*** and ***Reducer File*** sort the data by user input key values.

### PowerShell Command:
  ***cat heart.csv | python 22mapper.py | python 22sorter.py | python 22reducer.py > output.txt***

## Summary:
- By executing the sorted output from hearthealth datasets it clearly specifies that the average heart rate is the average age group. 



