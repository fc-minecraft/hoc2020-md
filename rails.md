### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Проложить рельсы

## Step 1
Создай более лёгкий способ путешествовать между двумя городами, проложив рельсы для вагонетки через туннель.

#### ~ tutorialhint
Блок "установить рельсы" установит рельсы под Агентом.
Блок "переместить агента" переместит Агента в указанном направлении.
Блок "повторить" позволит повторить набор блоков несколько раз.

```ghost
    hoc2020.placeRails()
    hoc2020.moveAgent(SixDirection.Left, 0)
    hoc2020Different.customRepeatLoop(0, () => {})
```
```template
//
```
```package
hoc2020-ts=github:fc-minecraft/hoc2020-ts
```