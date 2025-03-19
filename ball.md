### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Достать мяч

## Step 1
Похоже, рычаги на лифте заклинило. Пусть Агент использует свою силу, чтобы переключить все рычаги, чтобы Житель мог спустить детский мяч.

#### ~ tutorialhint
Используй блок "переместить агента", чтобы взобраться **вверх** по стене, и блок "переключить рычаг", чтобы включить рычаг.


```ghost
    hoc2020.moveAgent(SixDirection.Left, 0)
    hoc2020.flipLever()
```
```template
//
```
```package
hoc2020-ts=github:rewrite-media/hoc2020-ts#v0.5.2
```
