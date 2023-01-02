# Entry 2
##### 1/2/2023

### Context

`Kaboom` has a lot of objects, components, assets, and a lot more you can learn. But a tutorial is the best to look at when first learning kaboom because it is very helpful and it will teach you a lot of basics about kaboom. To start loading to put a background in kaboom Js put `kaboom()` and to load a character are: `loadSprite("bean", "images/bean.png")` “bean” is a character’s name and "images/bean.png" is the images we get from the `images` files.  By adding `kaboom()` and  `loadSprite("bean", "images/bean.png")` it wouldn’t show anything only the background so we going to add a game object called `add()` and a game object is basically any character in the game. Add object is where you add something to the screen
```Js
const bean = add([             ← add something to screen
    sprite("bean"),	 ← add Bean to the screen
    pos(80, 40),		 ← x 80 and Y 40
    area(),         ←  gives it a collider area, so we can check for collisions with other characters   later on —->
    body(),	←– gives it a physical body, making it fall due to gravity and the ability to jump
])

onKeyPress("space", () => {	← By pressing space
    bean.jump()		← Bean can jump
})
```

To start making a game by using the Kaboom game engine you need to start setup Kaboom first before going to the tutorial. https://kaboomjs.com/doc/setup
After finishing setting up Kaboom you can go tutorial to start the basics. https://kaboomjs.com/doc/intro
Concept tutorials are also very helpful because there are useful Basic components and Functionality people use in games. https://kaboomjs.com/doc/concept-tutorials

`How to read` In any freedom project tool webpage there will be a useful source to help you get better at learning your tool. My goal after my winter break is to learn the basics like knowing to make a game with kaboom.

[Previous](entry01.md) | [Next](entry03.md)

[Home](../README.md)