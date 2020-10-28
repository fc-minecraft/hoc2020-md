### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Building a farm.

## Step 1
The Villagers agreed to teach the Illagers how to farm, but first they need farmland setup. Have the Agent till the last two rows of dirt into farmland.

#### ~ tutorialhint 
The ``||hoc2020:till soil below||`` block will till the dirt block below the Agent.  
The ``||hoc2020:agent move||`` block will move the Agent in whatever direction you specify.  
The ``||hoc2020:turn agent||`` block will turn the Agent either left or right.  
The ``||loops:repeat||`` block will allow you to repeat a set of blocks multiple times.

```ghost
for (let i = 0; i < 5; i++) {
    hoc2020.tillSoil()
    hoc2020.moveAgent()
    hoc2020.turnAgent()  
}    
```
```template
\\
```
```package
hoc2020-ts=github:rewrite-media/hoc2020-ts
```