[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/MjLLqDcN)
# HW1
## W1L2 In-Class Activity

Player:

1. Movement controlled by WASD
2. SPACE to plant
3. No border restrictions

UI:

4. Plant seeds remaining starts at 5
When SPACE is hit:
5. Plant seeds remaining decrease by 1 if there are remaining seeds
6. Plants planted increases by 1 if there are remaining seeds
7. Nothing happens if there is no remaining seed  

Plant:

8. Gameobject generated from prefab at the position of the player when SPACE is hit and there are remaining seeds
9. No movement or collision with the player


## Devlog
My break down is different from Prof Reid's in that mine is less detailed. I may want to add in more details next time when writing the break down. I find my break down connects to the code I write. When I am
implementing the player behaviors, I find that my bullets 1 and 2 connect to the _Update_ function in _Player_ class. The bullet 3 is a feature that needs no additional implementation. When implementing UI,
I find that there should be connection between _Player_ and _PlantCountUI_ classes. I first implemented _UpdateSeeds_ function in _PlantCountUI_ class so I can use it as a method as a black box in the _Player_
script. This is a underlined function not specifically mentioned in my break down. My bullets 4 associates with the _Start_ function in _Player_ class. My bullets 5 to 7 connect with _PlantSeed_ function in
the _Player_ class. Bullet 7 makes it necessay to use a if statement to check number of remaining seeds in _PlantSeed_ function. The last thing I implemented is the plant prefab. My bullet 8 connects with the
plant prefab I made, which is connected to variable _plantPrefab_ in _Player_ class through Unity inspector. My bullet 9 is a feature of the plant which needs no additional implementation. Through homework 1, 
I find break down very useful in helping me organize the work.



## Open-Source Assets
If you added any other outside assets, list them here!
- [Sprout Lands sprite asset pack](https://cupnooble.itch.io/sprout-lands-asset-pack) - character and item sprites
