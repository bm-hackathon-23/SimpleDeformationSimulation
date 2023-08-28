# SimpleDeformationSimulation
A simple simulation for deformation using pick and drag

This simulation is based on https://andrew.wang-hoyer.com/experiments/cloth/.
During the hackathon a labeled model named sym_cort_seg_2023.nii was used to generate 3D particles models and 2D slices for simulation.
Since local image files access is a risky practice to enable, this code only has a hardcoded example from a slice of thaat model.
You can create your own models, just consider using images of maximun 400x400 8 bit, where the background is 0 and the foreground is not 0.

Replace the variable imgData with your own 2d integer array in the file cloth.js(78).
