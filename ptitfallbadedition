controller.A.onEvent(ControllerButtonEvent.Pressed, function () {
    animation.runImageAnimation(
    mySprite,
    assets.animation`vfgheg`,
    100,
    false
    )
})
controller.left.onEvent(ControllerButtonEvent.Pressed, function () {
    animation.runImageAnimation(
    mySprite,
    assets.animation`fddkjjnmfgmbn67mh`,
    100,
    false
    )
})
controller.right.onEvent(ControllerButtonEvent.Pressed, function () {
    animation.runImageAnimation(
    mySprite,
    assets.animation`f`,
    100,
    false
    )
})
sprites.onOverlap(SpriteKind.Player, SpriteKind.Enemy, function (sprite, otherSprite) {
    myEnemy = sprites.create(assets.image`crocoliele`, SpriteKind.Enemy)
    info.changeLifeBy(-1)
    info.setLife(2)
    sprites.destroyAllSpritesOfKind(SpriteKind.Enemy)
    myEnemy = sprites.create(assets.image`crocoliele`, SpriteKind.Enemy)
    sprites.destroyAllSpritesOfKind(SpriteKind.Enemy, effects.spray, 500)
})
let mySprite: Sprite = null
let myEnemy: Sprite = null
scene.setBackgroundImage(assets.image`dgbhfvhzfxhb`)
myEnemy = sprites.create(assets.image`crocoliele`, SpriteKind.Enemy)
info.setLife(3)
mySprite = sprites.create(assets.image`pitnaws`, SpriteKind.Player)
controller.moveSprite(mySprite)
music.playMelody("C5 B A G F G E A ", 191)
mySprite.setStayInScreen(true)
mySprite.setPosition(24, 126)
