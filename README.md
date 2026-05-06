# My Appreticeship Begins!

## Who are three fellow apprentices and/or your Magister you have met?

- Nathan
- Quan
- James

## What is one Computer Graphics-related skill or interest each of them has?

- Nathan has an avid interest in video games and is eager to learn more about ray casting.
- Quan has an interest in Adobe Illustrator.
- James, like me, shares a heavy interest in game development.

## If you could explore any magical realm in the world, where would it be and why?
I would love to visit Japan because the country is home to many large gaming companies, amazing food, and interesting culture. I've never had the chance to travel outside of the United States and have many places I'd like to visit, but Japan would definitely be at the top of my list.

---

## Visions of Japan (Project 1 Description):
I initially went for a nature theme, but somewhere along the line, I thought it would be cool to tie in the place that I wanted to visit the most in the world. This led me to illustrating a bonzai tree with flowers in a flower pot. This contains squares/rectangles, circles/ovals, and triangles. I wanted to fill up the background a bit, so I put in mountains and the red sun that is emblematic of Japan's flag. A way I can see the them improving is learning how to make more defined, stylized renders that can give the image some texture. Maybe have the image look like parchment (weathered and preserved).

Something I thought that was impressive from me was that I enabled my geometry-based JavaScript files have the ability to stretch and scale freely. This can be seen with the circles on the tree as well as the triangles of the mountains and the dirt in the tree pot. Another accessible option is to allow the shapes to define their own individual colors.

---

## Arcane Planetarium (Project 2 Requirements Completed):
- A space-like background using an image texture.
- Apply grayscale filter.
- At least one orbit is elliptical.
- Use simple shapes and colors to present celestial bodies and orbits.
  - Doesn't have multiple colors, so I don't know if it fully counts.
- A complete solar system animation (sun and the eight planets).
- At least one planet orbits the sun.
- At least one moon orbits around a planet.

---

## Summoning Gate (Project 3 Requirements Completed):
- Grid of Life Implemented
- Cells Randominzed and at least 256x256
- Render Cells Using Fragment Shader; 2 Colors For Live and Dead State Respectively
- Using Keyboard to Resume/Pause/Reset
- Using Keyboard to Speedup/Slowdown Simulation
- Camera Moves Left/Right/Up/Down
- Camera Zooms In/Out
  - Camera Won't Zoom Out Beyond Original Scale...But Still Is Able To Move Out-Of-Bounds
- Run at Real Time w/ Large Grid of 2048/2048
- Use Mouse Input to Toggle Cells
  - Best Seen During Pause, However First Click Renders All Cells Before Only Changing The Selected Cell 
- Render Instruction Text Box

---

## Firework Particles (Project 4 Requirements Completed):
- Set up particle-system physics in compute shaders (initial particles, emitters, etc.)
- Introduce forces such as gravity, wind, or a central attraction force to influence particle motion
- Add a lifespan for particles (remove them as they age) and enforce a maximum particle count
- Update particle positions based on velocity and acceleration (forces)
- Implement a circular boundary condition (particles that go off screen wrap around to the other side)
- Use mouse and/or keyboard interaction to spawn or attract particles
- Create a recognizable effect such as fireworks, smoke, or water.
- Apply non-linear interpolation.
- Compose a scene that has at least two different effects. You do not need to implement both systems; you can reuse one system to design a secondary effect
- Run in real time even with a large number of particles (e.g., >= 10,000)

---

## Raycasting and Ray-Object Intersection (Project 6 Requirements Completed):
- Implement ray generation using a pinhole camera model and show correct projective camera results
- Implement camera translation control and show correct interaction results
- Implement camera rotation control and show correct interaction results
- For a projective camera, implement camera focal change and show correct interaction results
- Implement at least one object translation control and show correct interaction results
- Implement at least one object rotation control and show correct interaction results
- Color the intersection results using the hit value (for example, smaller as red, larger as blue, no hit as black) so depth is easy to perceive
- Show intersection results with at least three different shapes
- Implement a ray-cube intersection and display the intersection results on screen
- Implement a ray-sphere intersection and display the intersection results on screen
- Implement a ray-cylinder intersection and display the intersection results on screen
- Implement a ray-cone intersection and display the intersection results on screen

---

## Volume Rendering & Minecraft Voxel Generation (Project 7 Requirements Completed):
- mplement ray marching using either an orthogonal camera or a pinhole camera model and show correct basic volume rendering (e.g. using maximum intensity as the transfer function)
- Customize the volume data loader to load new volume data (i.e. showing a different data loaded and visualized)
- Procedural generation of volume data. (i.e. showing a different data generated and visualized)
- Implement the linear transfer function and correctly visualize the results
- Implement the piecewise linear transfer function to visualize more appealing results
- (Repeatable, 1 point per transfer function) Design and implement a new transfer function and produce interesting results (e.g. a gradient transfer function to highlightt the edges)
  - Done multiple functions
- (Repeatable, 1 point per terrain) Use volume rendering to implement and visualize a (Perlin noise-based) terrain
  - Grass, Rock/Dirt, Water, Snow
- (Repeatable, 1 point per effect) Use volume rendering to implement and visualize a (Perlin noise-based) special effects e.g. cloud, fog, fire, etc.
  - Clouds, fire, smoke (Non-dynamic)
- Compose an interesting 3D scene
