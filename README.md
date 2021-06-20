# DiscoRunner-Game
In this Game, you will program an arcade-style Sumo battle with the objective of knocking increasingly difficult waves of enemies off of a floating island, using power ups to help defeat them. In creating this prototype, you will learn how to implement new gameplay mechanics into your projects, which are new rules or systems that make the game more interesting to play. On one hand, you will learn to program a powerup, which give the player a temporary advantage. On the other hand, you will learn to program increasingly difficult enemy waves, which make survival more challenging for the player. A good balance of powerups and increasing difficulty make for a much more interesting gameplay experience.

# Press "R" to Restart the Game

Use WASD Keys for Playing the Game- </br>
A-D For Rotation </br>
W-S For Movement(Forward & Backward)

# Part-1
The camera will evenly rotate around a focal point in the center of the island, provided a horizontal input from the player. The player will control a textured sphere, and move them forwards or backwards in the direction of the aforementioned focal point.

# Part-2
A textured and spherical enemy will spawn on the island at start, in a random location determined by a custom function. It will chase the player around the island, bouncing them off the edge if they get too close.

# Part-3
A powerup will spawn in a random position on the map, eagerly awaiting the player. Once the player collides with this powerup, the powerup will disappear and the player will be highlighted by an indicator. The powerup will last for 7 seconds after pickup, granting the player super strength that blasts away enemies!

# Part-4
The Spawn Manager will operate in waves, spawning multiple enemies and a new powerup with each iteration. Every time the enemies drop to zero, a new wave is spawned and the enemy count increases.

![Screenshot (131)](https://user-images.githubusercontent.com/67385503/122681964-7b047280-d214-11eb-8acb-c4be71f1e06b.png)





