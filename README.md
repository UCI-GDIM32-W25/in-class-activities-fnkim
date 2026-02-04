<img width="500" height="300" alt="Screenshot 2026-01-27 181137" src="https://github.com/user-attachments/assets/7b0c764e-c46b-45e8-91ec-8297a54363f9" /># GDIM32 In Class Activities
## Week 1
#### Activity 1
- Ask for help from your peers
- Go to tech hours
- Read Unity documentation
- Try to get a good estimate of how much time it will take to finish a task. Don't underestimate


#### Activity 2
- Question 1: x = 10
- Question 2: x = 2
- Question 3: Every Update(), which means every frame, the code runs PrintMessage(). What PrintMessage() does is that it prints "hello world" to the console as a debug message.
- Question 4: Monobehavior class
- Question 5: When the program starts, it runs the method PrintMessage() with the argument 10. In PrintMessage(), it runs the code and in the end, there is a debug message that says "x = 10".
- Question 6: "10" is the argument that gets passed through and used in "'x =' + x" in order to print x = 10.
- Question 7: It's calling Translate on Transform, but Transform is a class, not an object
- Question 8: Change Transform to _playerTransform


#### Activity 3
[Link to MG1 breakdown document](https://docs.google.com/document/d/1ZloeI2O3HLCZUm7UvvfKdylog4EuKHg3eZPcW1Tevz0/edit?tab=t.0)



## Week 2
#### Activity 1
![IMG_0199](https://github.com/user-attachments/assets/72bd6f83-9716-4403-a125-7e43fbaca5d0)

#### Activity 2
- I added the sprites for the ground and penguin as well as the components needed for movement. I also added a jump functionality to the penguin, making sure to check whether the penguin was grounded using collisions to let it jump again.
- [Link to commit](https://github.com/UCI-GDIM32-W25/mg2-fnkim/commit/1478a57c63e44907068b6efef3db87be06e2e44f)

## Week 3
#### Activity 0
Buddy: Rebecca Feng


#### Activity 3
<img width="500" height="300" alt="Screenshot 2026-01-20 180854" src="https://github.com/user-attachments/assets/49986856-fabd-41d8-9dd5-9b53d9569510" />

## Week 4
#### Activity 0
Rebecca Feng

#### Activity 1
When multiple Locator objects are added to the Scene, they disappear until only one is left when the game is run. This is because in the code, it checks for if there is an Instance of the locator and there are multiple, it destroys it.

#### Activity 2
<img width="500" height="300" alt="Screenshot 2026-01-27 184239" src="https://github.com/user-attachments/assets/bbcc9375-cd56-480b-8908-7107d99635f2" />

#### Activity 3
[Link to Commit to HW](https://github.com/fnkim/HW4/commit/aadda961c47dcb32a05e3b22729dd58d27a27cd7)
I added the sprites and made the input controls to make the bird flap, as well as making the pipe spawning feature.


## Week 4
#### Activity 1
I think the design of the interfaces and abstract classes are utilized pretty well overall, like the Use() method in the abstract parent class "Item" being used in all of the items. However, I think there are some inefficiencies, like the _durability variable being defined over and over again in each item child, rather than being defined once and then being set separately by the item children.


#### Activity 2
In the second demo, the ItemW5Demo class represents the Model because it is a ScriptableObject that contains game data without making GameObjects. The InventoryUI class is an example of the View because it shows the aesthetic parts of the game that the player sees. PlayerW5Demo2 class represents the Controller because it deals with game logic.


#### Activity 3
- Scenario 1 (Rhythm game): Prefabs with scriptableObjects on them, the data contains the starting timing, the type of note. The prefab contains the sprite for the notes.
- Scenario 2 (team shooter): MVC pattern is used as the model contains the different weapons used while the view displays the images.
- Scenario 3 (Farming game): You would need all of the design patterns. You would need a Model-View-Controller to decouple things like data for plants from logic like how the planting function works from visual aspects like inventory menus. You would need inheritance with polymorphism to make larger classes encompassing categories like objects and plants and child classes for more specific things. Interfaces might be used for qualities like an object being breakable so that objects can inherit the interface as well as other stuff and dictate that specific functionality. A finite state machine would be needed for animations as there would only be one animation being played at once. Singletons and locators would be used to connect the player or GameController to the rest of the scripts. ScriptableObjects would contain data for the types of plants and objects and their properties.


#### Activity 4
- Attendance: Rebecca Feng, Landon Her, Nansong Sun
- [Link to proposal](https://docs.google.com/document/d/12oXcMbRqu-4vIfI7XU0rpLQhKyyF9Gy7RNBljYCJIrA/edit?tab=t.0)
