# windows-runner
Project files for 3D render

## Blender Nodes Overview

The Blender file includes several pre-loaded animation presets.

Open the **Geometry Nodes** tab to view them. You should see a screen like this:

![Blender Nodes Overview](https://github.com/user-attachments/assets/003f4e9e-241a-4006-9410-44985e5f4538)

## Switching Effects

To view different effects (Cards, Paint, Minesweeper), replace the 4 inputs in the **"Point Converter"** node:
- Point Density  
- Instances  
- Scale  
- Seed  

Connect these inputs to the corresponding outputs from the **Cards**, **Paint**, or **Minesweeper** nodes.

The values are already set for each effect.

To have *No effect* (3d model only), connect the "3d Model" output of the "Running Man" node straight to the "Output" socket in "Group Output" (Ignore Point Converter in this instance).

## Editing Values

To adjust settings:
- Select a node
- Press `Tab` to enter it
- Modify values as needed
