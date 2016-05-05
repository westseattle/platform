# How to Build a Platform Game in Snap

By Larry K

## What is a Platform Game?

A platform game  consists of a player-controlled **Hero** who completes a series of **levels** or **missions**. Each level has an **objective** or **goal** that must be achieved in order to complete the level. It is called a platform game because the player jumps on **platforms** and dodges various **enemies**. Platform games also typically have a number of **powerups** that make the Hero more powerful. 

One of the most famous platform games is Super Mario Brothers. In Mario Brothers, the Hero is Mario. Mario completes a level by touching the flag or defeating Bowser. Enemies in Mario Brothers include Goombas, Koopa Troopas, and Thwomps, who each attack Mario in various ways. Mario can grab a number of **powerups** to become mower powerful. Examples of powerups in Mario Brothers include Mushrooms, Stars, and Flower Power. 

Other examples of platform games include Sonic the Hedgehog, Metroid, and many others. In Metroid, the hero is Samus Aran. Examples of powerups in Metroid include the Ice Beam (freezes enemies), High Jump Boots (makes Samus jump higher), and Missile Packs (more powerful attacks). 

Your first task will be to design your own platform game nd

## The Hero

We will start off our platform game by creating a Hero sprite. The Hero is controlled the person playing the gamet. In Super Mario Brothers, the Hero is Mario. In Metroid, the Hero is Samus Aran.

### Animating a Character

A character should have multiple costumes representing each frame. Right click on each of the images below and save them to your desktop. 

![Costume 0](./costumes/0.png)
![Costume 1](./costumes/1.png)
![Costume 2](./costumes/2.png)
![Costume 3](./costumes/3.png)
![Costume 4](./costumes/4.png)
![Costume 5](./costumes/5.png)

Drag these images to the costumes tab for your sprite in Snap. Rename your main Sprite to "Hero". This will make it clear that this Sprite represents the main character in your platform game. When you are done, your Costumes tab should look like the one below:

![Hero Sprite](./screenshots/step1.png)

![Screenshot 2](./screenshots/step2.png)

## Creating a Level 

Our Hero is now animated, but the stage still has the default white background costume. Since our platform game will have multiple levels or stages, we will want to design multiple costumes for the stage that represent each level. Let's start by saving the image below to the desktop:

![Stage Costume](./costumes/stage.png)

Once the image is saved, switch to the Stage Sprite in Snap and click on the Costumes tab. Drag the stage image to the costumes tab to change the background. You will create a background for each level or stage in the game. When the player completes the objective for each level, you can broadcast a "level completed" message and change the costume of the stage to the next level's background.

![Stage Screenshot 1](./screenshots/step3a.png)
![Stage Screenshot 2](./screenshots/step3b.png)

## Moving Left and Right

![Left and Right 1](./screenshots/step4a.png)
![Left and Right 2](./screenshots/step4b.png)

## Jumping and Gravity

![Jumping 1](./screenshots/step5a.png)

After our Hero sprite reaches the peak of its jump, we want it to fall until it hits the ground. We can make our Sprite slowly fall by changing its Y position by a negative number. We eventually want our Sprite to stop falling. We can tell our Sprite to stop falling when it hits the ground by repeating until it is touching the color of the ground. To choose the ground color, bring up the color chooser and click on the ground on the stage. This will let us pick the exact color of the ground.

![Jumping 2](./screenshots/step5b.png)
