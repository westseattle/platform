# How to Build a Platform Game in Snap

By Larry K

## Animating a Character

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

## Adding a Background

![Stage Costume](./costumes/stage.png)

![Stage Screenshot 1](./screenshots/step3a.png)
![Stage Screenshot 2](./screenshots/step3b.png)

## Moving Left and Right

![Left and Right 1](./screenshots/step4a.png)
![Left and Right 2](./screenshots/step4b.png)

## Jumping and Gravity

![Jumping 1](./screenshots/step5a.png)

After our Hero sprite reaches the peak of its jump, we want it to fall until it hits the ground. We can make our Sprite slowly fall by changing its Y position by a negative number. We eventually want our Sprite to stop falling. We can tell our Sprite to stop falling when it hits the ground by repeating until it is touching the color of the ground. To choose the ground color, bring up the color chooser and click on the ground on the stage. This will let us pick the exact color of the ground.

![Jumping 2](./screenshots/step5b.png)
