# Space Invaders ![Difficulty](https://img.shields.io/badge/Difficulty-Intermediate-blue.svg)

![Space Invaders](https://github.com/digitsensitive/phaser3-typescript/blob/master/src/games/space-invaders/assets/github/spaceInvaders.png)

## Description

A very simple game to learn the basics of Phaser 3.

## How to run it

Adjust the entry path in the `webpack.config.js` file as follows:
```
entry: './src/games/space-invaders/game.ts'
```

## References used

* [Bullets Pool](https://labs.phaser.io/edit.html?src=src\pools\bullets.js)
* [Phaser 2 Invaders](https://phaser.io/examples/v2/games/invaders)
* [Wikipedia Invaders](https://de.wikipedia.org/wiki/Space_Invaders)
* [YouTube Space Invaders](https://www.youtube.com/watch?v=kR2fjwr-TzA)

## Fixes of the TypeScript definition file

This is a work around I have done in the phaser.d.ts file.
```
Line 46963:
overlap(object1: ArcadeColliderType | any, object2?: ArcadeColliderType | any, collideCallback?: ArcadePhysicsCallback, processCallback?: ArcadePhysicsCallback, callbackContext?: any): boolean;

```
