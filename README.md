# Blender to Gazebo Conversion

## Instructions
1. Open the .blend and select the objects desired in the sim.
2. Run the script `sdf_exporter`.
3. Do `cp proto-world.sdf <directory of generated files>/e-world.sdf`
4. Navigate into the directory and start the simulation:
```
gz sim e-world.sdf
```
All the selected objects from blender will be in Gazebo.
