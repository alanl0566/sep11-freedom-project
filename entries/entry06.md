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
During the In-class presentation, I was really nervous and talked really fast but the presentation goes really well and I finish my slide just in time for the presentation in class. I present two times, One time I was presenting myself and the second time I presentation with My parther Selina.

During the Expo I was really nerous to seeing so many people is coming and I don't even have sentence to begin the Conversation about my products. So I start to practice my line and I start not to get nervous and remember my lines. A lot of people was coming to see my products and most of them say that my product and my speaking was very good, Also my parther Selina was also there to help me during the Expo and the Presentation.

### Expo elevator pitch takeaways
*
*
*
### In-class presentation takeaways
*
*
*
* Talk loud and clearly
* Eye contact wuth audience
* Better Hook (a little Similar of the my purducts or the things I'm doing )
### In-class presentation takeaways
[Previous](entry05.md) | [Next](entry07.md)

[Home](../README.md)