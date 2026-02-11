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


## Week 5
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


## Week 6
#### GDW Talk 1, Freeland Narrative Writer: Cory Lanham
- Writing involves collaborating with other departments—design, art, animation, audio, engineering, studio leadership
- Freelance writers are independent contractors
- In-house writers are full-time studio employees and have more influence
-----------

Pre-Production:
- High-level narrative summary, setting and characters, detailed story outlines, narrative delivery methods, and sorting out databases
-----------

Production:
- Cinematic and mission scripts which involves collaborating with leadership and level design; rewriting is cheap
- Dialogue barks
- Ambient dialogue
- Specialized dialogue systems: Eg. Character reacts to specific things you do, like doing a thumbs up back. Different lines needed for each interaction
- Worldbuilding and lore: Not player-facing, this is set up so that writers know how to write things that players see
- UI/UX Text: Narrative checks over UI stuff, Eg Tooltips
- Casting and recording: This is when writing stops being cheap. Something that gets recorded can’t be redone as easily as just rewriting lines. Writers should not be voiceover directors, as having a fresh look can be really helpful
-----------

Post production to ship:
- Marketing Materials like website copy and trailers
- Nondialogue text revisions
- Localization: translation notes
-----------

Tools:
-  Google docs/MZ office
-  Excel/Sheets
-  Narrative implementation: Visual scripting, branching narrative (important for games) like arcweave and twine
-  Scriptwriting tools
-----------

Breaking into the industry
- Starting in another department (especially In-House QA team
- Provide feedback, don't be an asshole
- Internships
- Look for opportunities to help the narrative team
- Build your portfolio, make a game alone or with others, and participate in game jams
- Networking: IGDA/community meetings, discord servers
-----------

Game writing advice:
- Showcase that you're broad in your talent but lean into your strengths
- Understand story structure and how it works so you know how to break it for game writing
-----------

Resources
- Books on craft: Video Game Storytelling (Skolnick), The Game NArrative Toolbox (Heussner)


#### GDW Talk 2, Technical Art: Stephen Coan
- Background: Technical artist at Secret Door
--------

What is Technical Art?
- Well-paying and needed role
- Solve problems relating to the implementation of art in a game engine
- Build art pipelines
- MAke the artistic process simpler, faster, more accessible, or possible in the first place
- Glue between Art and Engineering
- Making games is a technical effort not matter what kind work you're doing. Tech Artists focus on making sure technical problems don't get in the way of making art
----------
Sub-disciplines
- Character Tech Art
- Rigging and skinning
- Animation tools
- Taking 3d models and making them animatable
- Abstracting complex implementation into something simple for the animator
---
Tools Tech Art
- Asset Management
- Standards and conventions
- Art import.Export
- Workflow simplification
- Automation
- Engine hookup
- Works with artists and designers, workflow needs to be made to help them collaborate
---
Runtime Tech Art
- Authoring shaders, collaborating with artists and art director
- Destruction simulation
- Procedural Generation
- Optimization
- Determines what performance budgets are based on target hardware and enforcing these budgets
---
- Tech artists are usually either character TAs or Tools + Runtime TAs
- Every project has different problems for Tech Artists to solve
- Tech Art work crosses into different disciplines like technical design and gameplay engineering. Tech artists fill gaps, so they kind of know broadly things about game development
-------
Examples of Technical Art
- Scene Footprints analyzer
- Environment memory was a bottleneck to shipping on Switch
- Built a tool to break down the most expensive assets in a scene and warn artists if they've built a scene too large to ship on Switch


FX Data Hookup Tooling
- FX behavior needed to be able to be connected to gameplay for FX artists
- Did not want hard-coded behavior
- Deal with FX and designers to determine what gameplay hooks would need to be exposed
- Extended existing design tools for creating spells with additional data for FX behavior


Chromas
- Changes to character rendering
- New shader logic for tinting base appearnace
- Worked with Art Director to determine visual requirements
- Determined additional textures and parameters required to achieve the effect
- Optimization
  
--------
How to become a technical artist
- Strong communication skills
- Ability to break complex tasks down into more approachable steps
- Excitement about learning new things
- Passion for helping others achieve their passions
- Don't be afraid of approaching a problem you don't know the solution for


Learn:
- Shader editing in Unity or Unreal
- Scripting for 3D modeling tools (Maya/Blender/Houdini)
- Basics of runtime optimization
