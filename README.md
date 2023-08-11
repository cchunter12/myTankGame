# myTankGame
This is a tank game project that I created in my software development class and it was created in Java.  This project utilizes JFrame to provide a smooth user interface and gaming experience.  

![title](https://github.com/cchunter12/myTankGame/assets/89422782/c5a9ea99-1042-4102-a3b3-0c79dbf42fef)

# Disclaimer
"Please note that due to academic integrity concerns for the potential of plagiarism, I cannot publish the source code. Please feel free to reach out to me if you would like to review the code associated with this project to ensure originality. Thanks!"

# Brainstorming
During this part of the project, I came up with a class diagram for this game, focusing on the tank.  No codes were involved at this point and this diagram is expected to change as the game is being implemented, but it will stay very close to what the final game will look like.
![tank1](https://github.com/cchunter12/myTankGame/assets/89422782/84db00db-8ef1-4570-b058-806b91b1a151) ![tank2](https://github.com/cchunter12/myTankGame/assets/89422782/41e5aeca-773f-4578-bbca-ba001eb1612c)

![diagram](https://github.com/cchunter12/myTankGame/assets/89422782/82beb358-bfc7-4ac0-b6a5-0bfb674d48c3)

# Implementation
There are three main implementations in this game:  The tank, the game objects, and the game world itself.  How each object interacted with each other is what makes this game fun.

The tank is a moveable object which shoots bullets that interact with other objects in the world.  For example, a tank might collide into a breakable wall and a solution is to shoot it down with bullets. It might run into a powerup to gain new powers.

The game objects include walls and powerups.  Some walls are breakable while others are not.  Some powerups are speed up, stronger firepower, and health packs.
![speed](https://github.com/cchunter12/myTankGame/assets/89422782/cb9c7707-5e0b-407c-9e10-68cd5eb0713e)
![rocket](https://github.com/cchunter12/myTankGame/assets/89422782/ad00ddb9-49ae-4bc9-bdd4-52d467c20d97)
![health](https://github.com/cchunter12/myTankGame/assets/89422782/8a963367-7012-42af-afb2-f4b4c9ea40d8)

The game world is a giant rectangle of unbreakable walls.  This world is filled with game objects for the tanks to interact with.
![image](https://github.com/cchunter12/myTankGame/assets/89422782/4e55c883-f459-4402-82fc-c7c239f22bff)
