# Musical Holiday lights

## Step 1

First you need to make your snowflakes. Take a ``||basic:show leds||`` block and place it our ``||basic:forever||`` loop.

``` blocks
basic.forever(function () {
    basic.showLeds(`
        . . . . .
        . . # . .
        . # # # .
        . . # . .
        . . . . .
        `)
})
```

## Step 2

Brilliant. Now add a couple more snowflakes to the ``||basic:forever||`` loop to make an animation.
    
``` blocks
basic.forever(function () {
    basic.showLeds(`
        . . . . .
        . . # . .
        . # # # .
        . . # . .
        . . . . .
        `)
    basic.showLeds(`
        . . # . .
        . . # . .
        # # . # #
        . . # . .
        . . # . .
        `)
    basic.showLeds(`
        . # . # .
        # # # # #
        . # . # .
        # # # # #
        . # . # .
        `)
})
```

## Step 2

Now you're ready to add some music!