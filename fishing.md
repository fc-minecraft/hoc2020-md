### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Строительство причала

## Step 1
Построй внешние края причала длиной 6 блоков и шириной 4 блока. (Подсказка: Нарисуй картинку своего причала перед началом!)

#### ~ tutorialhint
Блок "переместить и установить" переместит агента вперёд и установит деревянную доску под ним.
Блок "переместить агента" переместит Агента в указанном направлении.
Блок "повернуть агента" повернёт Агента влево или вправо.


```ghost
    hoc2020.placePlanks(0)
    hoc2020.moveAgent(SixDirection.Left, 0)
    hoc2020.turnAgent(TurnDirection.Left)  
```
```template
//
```
```package
hoc2020-ts=github:fc-minecraft/hoc2020-ts
```