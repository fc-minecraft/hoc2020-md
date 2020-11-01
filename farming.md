### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Building a farm

## Step 1
The Villagers offered to teach the Illagers how to farm, but they need help to prepare the land. Have the Agent till the first 2 rows of dirt.

#### ~ tutorialhint 
The ``||hoc2020:till soil below||`` block will till the dirt block below the Agent.  
The ``||hoc2020:agent move||`` block will move the Agent in whatever direction you specify.  
The ``||hoc2020:turn agent||`` block will turn the Agent either left or right.  
The ``||loops:repeat||`` block will allow you to repeat a set of blocks multiple times.

```ghost
    hoc2020.tillSoil()
    hoc2020.moveAgent()
    hoc2020.turnAgent()  
    customRepeatLoop()   
```
```template
\\
```
```package
hoc2020-ts=github:rewrite-media/hoc2020-ts
```