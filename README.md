# RigifyToUnity
This A python script/guideline for exporting a Blender Rigify rig to unity with animations
This script is now also fixed to also include facial expressions and works with Blender 2.8

## Exporting The Model
  1. Create your model and rig it using rigify in blender
  (Optional: if you want eyes and teeth to follow correctly I recommend you seperate each eye along with the bottom and top teeth and parent them in Unity)
  2. Put the armature in the default pose
  3. Select everything you want to export, make sure the rig is the active selection 
  4. Run RigifyToUnity.py 
  5. Export to FBX, and check selection only
  6. In Unity you can now create the avatar from this model, humanoid is also possible, but I believe you'll lose facial expressions

## Exporting Animations
  1. Once you have your model ready you can export your animations, Unfortunately this has to happen one by one
  2. Select the animation you need from the action editor
  3. Select ONLY the rig and run RigifyToUnity.py
  4. Export to FBX, and check selection only 
  5. In Unity set the animation to copy avatar from the full model
  6. Before you export your next animation press ctrl-z twice so the rig is restored to the moment before it got edited
