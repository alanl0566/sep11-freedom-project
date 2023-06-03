# Entry 6
##### 5/29/23

### Progressing
While still working on my mvp and beyond mvp I have add a lot of things recently from adding adding more object to the game and texts label for my Mvp and for my Beyond Mvp I add a portal to the second map, creating a second level, working object and adding more commanding to the character.

Mvp
```
const mc = add([
	sprite("stickman"),
	pos(2550, 200),
	area(),
  body(),
  scale(5),
])

```
This is the character that will be moving around and jumping around

Beyond Mvp
```JS
mc.collides('portal', (p) => {
    p.destroy()
    level_id++
    if(level_id < maps.length){
     go('game', {level_id: level_id})
    }
    else{
     go('win')
    }
  })

```
This code shows that if the character collides with the portal it will go to the next level or else it goes win.

```JS
[
    "                   -   -            -      ",
    "                             -      -      ",
    "                                           ",
    "                                           ",
    "       ====                                ",
    "            ^                              ",
    "              ==                           ",
    "                 =          ^              ",
    "                   =       ====            ",
    "                     =                     ",
    "                                =          ",
    "                                           ",
    "                                   ==      ",
    "                                    ====== ",
    "                                           ",
    "                                           ",
    "                                           ",
    "                                           ",
    "                                           ",
    "                                           ",
    "                                         * ",

],

```

23 to 43 lines of code show it is a working map and my second map to my game and those are Syntax for adding objects like a block to the ground.

### Before Expo and In-Class presentation
After finishing my MVP and Beyond MVP, I finish my game. Also starting to prepare for the Expo elevator pitch and the In-class presentation. So I start getting ready to present and making my slide for the In-class presentation.

### During the Expo and In-Class presentation
During the In-class presentation, I was really nervous and talked really fast but 

### Expo elevator pitch takeaways

### In-class presentation takeaways

[Previous](entry05.md) | [Next](entry07.md)

[Home](../README.md)