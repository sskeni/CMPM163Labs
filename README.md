# CMPM163Labs

## Lab 2

Video: [link](https://drive.google.com/file/d/1F82mxIKp4eEwQVWIswMUm7CMT9Kl9J8b/view?usp=sharing "Link to cubes video")
![](lab2/SanchitKeniPart2Models.png)

## Lab 3

Video: [link](https://drive.google.com/file/d/1-ocZeBH3URbb47b0JOQo5Os_0Ou92bHm/view?usp=sharing "Link to other cubes video")

For the first cube on the left, I created a shader that gradients on the x axis from white to black. It gave it a really cool ghostly look. For the second cube, I created another Three.js material similar to the one created in the tutorial. The third cube is the one from the tutorial made with a Three.js material. The forth cube is the other one from the tutorial made with a fragment shader.

## Lab 4
Video: [link](https://drive.google.com/file/d/1gFdLvhPXL-bivbOr8Zn0YwJ-b3Sa8HbJ/view?usp=sharing "link to yet another cubes video")

The tiled cube was made using a formula that mapped the texture( (vUv.x % 0.5) * 2). The second cube from the left was made using three.js with only a texture and no normal map. The middle cube was made using Three.js materials with a texture and a normal map. The forth cube from the left was made by the same method as the middle cube, but with a different texture and normal map. The final cube was made using shaders to parse a texture.

a. u = x/8
b. v = y/8
c. white

## Lab 5
Video: [link](https://drive.google.com/open?id=1Izm9lSazlhOq39EKCzf2hrjUJiOjP1P4 "link to something that isn't a cube video")

For this project I wanted to see if I could add the classic particle systems found in most racing games. I started by adding a smoke system so that if you were turning hard enough, smoke would come out of the wheels. I had to change the simulation space to "world" so that it would realistically leave the smoke in a 'trail' behind the path of the car. Next I decided to add a celebration firework that would go off whenever you would pass through a check point. This was interesting because I added trails to the particles which really make it look like a firework. The last particle system I added involved adding a new game mechanic. I added a system that would allow you to boost when you hold left shift. Once you held it, it would increase your max speed allowing you to go faster. The particle system I made used the system that allows you to change the color of the particle over its lifetime. I used this to start the particles as blazing white hot and then turning red, then finally turning into smoke. A few smaller touches include modifying the player to have the same skin color as me and the car to be the same color as my car!
