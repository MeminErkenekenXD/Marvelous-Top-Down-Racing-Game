# Marvelous-Top-Down-Racing-Game
Marvelous Top Down Racer is a racing game with top down view made with Unity. Supports up to 4 players with local multiplayer.
# Features and Content
- **Single Player** : Single player game mode is where you can test out cars and get familiar with tracks and *Try to get the Best Lap Times*.
- **Local Multiplayer** : Game supports *Split-Screen Local Multiplayer up to 4 Players* with full *Gamepad Support*.
- **8 Unique Cars** :  All having varying *Styles and Stats*. They also have *Unique Engine Sounds*.
- **2 Tracks** : One has *Long Straights* to build speed and *Tight Corners*. While other is smaller but has more *Consecutive Turns* with a *Bridge Mechanic*.

# Controls
* **Forward** : Throttle, which is used to accelerate.
* **Reverse** : Brake, which is used to slow down, or go in reverse if the car is stopped. However when going reverse, top speed is reduced.
* **Right/Left** : Used for steering.
* **Drift** : Hold drift to enhance steering with a tighter but more slippery turning arc without losing speed.
* **Reset** : Reset the car to the last checkpoint passed.

# Mechanics
Car behaviour is based on three stats <BR>

**Top Speed** : Determines the cars top speed. <br>
**Acceleration** : Determines how fast the car accelerates. <br>
**Handling** : Determine how well car takes turns. <br>

Speed System : The car will gain speed as long as the car keeps going and the player is applying throttle until it reaches its top speed (top speed stat).
The car has higher acceleration when it takes off, but when the car reaches its acceleration limit (acceleration stat). It will accelarate more slowly until it reaches top speed.

Turning System : The car turns better when the player releases throttle , and it turns even better while braking.
However these actions reduces speed. In order to take sharp turns without losing speed, the player must master drifting.
Drifting allows car to turn without losing speed.

