### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Строительство фермы

## Step 1
Жители предложили научить Разбойников фермерству, но им нужна помощь в подготовке земли. Заставь Агента вспахать первые 2 ряда земли.

#### ~ tutorialhint
Блок "вспахать и переместить" вспашет блок земли под Агентом и затем переместится вперёд.
Блок "переместить агента" переместит Агента в указанном направлении.
Блок "повернуть агента" повернёт Агента влево или вправо.


```ghost
    hoc2020.tillSoil(0)
    hoc2020.moveAgent(SixDirection.Left, 0)
    hoc2020.turnAgent(TurnDirection.Left)  
```
```template
//
```
```package
hoc2020-ts=github:rewrite-media/hoc2020-ts#v0.5.2
```