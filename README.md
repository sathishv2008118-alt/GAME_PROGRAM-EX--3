# GAME_PROGRAM-EX--3
# Change the third person character mesh and add animations

# Aim
To replace the default third person character mesh with a custom skeletal mesh and apply new animations using an animation blueprint.

# Procedure
 # 1.Import New Character Mesh and Animations:
      In the Content Browser, import a new Skeletal Mesh along with its Animations (FBX files).
      Ensure the mesh is rigged correctly (ideally to the UE4 Mannequin Skeleton or compatible with it).

  # 2.Replace Character Mesh:     
       Open the ThirdPersonCharacter Blueprint (usually found in ThirdPersonBP/Blueprints).
       Select the Mesh component.
       In the Details Panel, change the Skeletal Mesh to the newly imported mesh.
 
  # 3.Set Animation Blueprint:
       If available, assign a matching Animation Blueprint in the Details Panel under the Animation section.
       If not available, create one:
           Right-click in the Content Browser → Animation → Animation Blueprint.
           Choose the correct skeleton.
           In the AnimGraph, set up state machines or direct animation nodes.
           Compile and save.
 
  # 4.Preview and Test:
       Place the character in the level.
       Press Play to test idle, walk, and run animations based on character movement.

# Output

<img width="557" height="361" alt="image" src="https://github.com/user-attachments/assets/d306d250-9741-4eda-813f-51bd6df6ec14" />

<img width="468" height="414" alt="image" src="https://github.com/user-attachments/assets/32713267-f65b-4f99-8aa4-e1f2cd6216f5" />

<img width="557" height="327" alt="image" src="https://github.com/user-attachments/assets/14f27281-6673-4fa4-93c1-f7976eac1f15" />

# Result
The default Third Person C
