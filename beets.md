### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Защитить свёклу

## Step 1
Что-то постоянно проникает в сад и крадёт свёклу. Заставь Агента построить забор вокруг фермы, чтобы защитить свёклу.

#### ~ tutorialhint
Блок "установить железные прутья вниз" установит железный прут под Агентом.
Блок "переместить агента" переместит Агента в указанном направлении.
Блок "повернуть агента" повернёт Агента влево или вправо.
Блок "повторить" позволит повторить набор блоков несколько раз.


```ghost
    hoc2020.placeFence()
    hoc2020.moveAgent(SixDirection.Left, 0)
    hoc2020.turnAgent(TurnDirection.Left)  
    hoc2020Different.customRepeatLoop(0, () => {})
```
```template
//
```
```package
hoc2020-ts=github:fc-minecraft/hoc2020-ts
```