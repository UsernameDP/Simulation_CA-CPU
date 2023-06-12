# Simulation_CA-CPU
Originally, the plan was to run this program entirely on the GPU. However, due to the due date of this assignment (6/11/2023) I was not able to fully implement the "Compute Shader" such that we used textures on the GPU rather than having to create 2D arrays representing the generations on the CPU. The portion that seems to be the problem is the process of binding a texture to Sampler2D, which prevents me from being able to upload some texture for the fragment shader to output vec4 colors.

## Todo (Simulation_CA-GPU)
- Find out how to upload Sampler2D correctly
- Integrate the saving feature (using "Jackson" JSON Library)
