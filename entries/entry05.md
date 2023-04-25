# Entry 5
##### 4/23/2023

### Previous
I got a problem with my 'IDE' and some of the kaboom code was not working in the IDE so I have to change IDE to 'Replit'.
Replit has a lot of replit and they already have some tutorial code for us to review and I thinks is pretty useful. After I move my code to replit, me and my parther. We start learning to make our platformer game.

```js
    import kaboom from "kaboom"

    // initialize context
    kaboom()

    // load assets
    loadSprite("bean", "sprites/bean.png")

    // add a character to screen
    add([
        // list of components
        sprite("bean"),
        pos(80, 40),
        area(),
    ])

    // add a kaboom on mouse click
    onClick(() => {
        addKaboom(mousePos())
    })

    // burp on "b"
    onKeyPress("b", burp)
### context
Me and my parther we are been learning our tool so that we can make our game. What I Recently made is that I was trying to add scene to my game so it can feel a little bit like a real game. A scene is when u start the game and it tells you the detail or story about the game. Also we can a scene were when a

[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)