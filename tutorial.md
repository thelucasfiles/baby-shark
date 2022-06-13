# JAWS

## Step 1

Select your favorie color for background

```blocks
scene.setBackgroundColor(2)
```

## Step 2

Create a Sprite or Choose One that You Like!

```blocks
let mySprite = sprites.create(img`
    ......ffff..............
    ....fff22fff............
    ...fff2222fff...........
    ..fffeeeeeefff..........
    ..ffe222222eef..........
    ..fe2ffffff2ef..........
    ..ffffeeeeffff......ccc.
    .ffefbf44fbfeff....cddc.
    .ffefbf44fbfeff...cddc..
    .fee4dddddd4eef.ccddc...
    fdfeeddddd4eeffecddc....
    fbffee4444ee4fddccc.....
    fbf4f222222f1edde.......
    fcf.f222222f44ee........
    .ff.f445544f............
    ....ffffffff............
    .....ff..ff.............
    ........................
    ........................
    ........................
    ........................
    ........................
    ........................
    ........................
    `, SpriteKind.Player)

```


## Step 3

Give the sprite special effects (spray!)

```blocks
mySprite.startEffect(effects.spray)
```
    
## Step 4

Play Spooky Melody

```blocks
music.playMelody("E B C5 A B G A F ", 120)
```

## Step 5

Make Sure Sprite Bounces on The Walls!

```blocks
mySprite.setBounceOnWall(true)
```


## Step 6

Move Sprite around the Screen! 

```blocks
mySprite.setVelocity(50, 50)
```


## Step 7

Create baby shark!

```blocks
let myEnemy = sprites.create(assets.image`baby shark`, SpriteKind.Enemy)
```


## Step 8

Make baby shark chase after sprite!

```blocks
myEnemy.follow(mySprite, 25)
```

