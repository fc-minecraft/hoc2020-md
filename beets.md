### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Protect the beets

## Step 1
Something keeps getting into the garden and taking beets. Have the Agent build an enclosure around the farm to keep out whatever is doing it.

#### ~ tutorialhint 
The ``||hoc2020:place iron bars down||`` block will place an iron bar below the Agent.  
The ``||hoc2020:agent move||`` block will move the Agent in whatever direction you specify.  
The ``||hoc2020:turn agent||`` block will turn the Agent either left or right.  
The ``||hoc2020_different:repeat||`` block will allow you to repeat a set of blocks multiple times.


```ghost
    hoc2020.placeFence()
    hoc2020.moveAgent()
    hoc2020.turnAgent()  
    hoc2020_different.customRepeatLoop()
```
```template
\\
```
```package
hoc2020-ts=github:rewrite-media/hoc2020-ts
```