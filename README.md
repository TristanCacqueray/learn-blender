# learn blender

Video resources:

- [The BEST Way To Learn Blender in 2023!!](https://www.youtube.com/watch?v=8K4AShjq-MU) by [Ducky 3D][d3]
- [Get Good @ Blender](https://www.youtube.com/playlist?list=PLn3ukorJv4vvv3ZpWJYvV5Tmvo7ISO-NN) by [Grant Abbitt][grabbitt]
- [Donut Tutorial](https://www.blenderguru.com/tutorials/2022/1/27/how-to-use-blender) by [Blender Guru](https://www.blenderguru.com)
- [Nodes 4 Noobs](https://www.youtube.com/playlist?list=PLn3ukorJv4vtnU_TaZob7QD6Q8d9C9Ki7) by [Grant Abbitt][grabbitt]

## Notes

Each tutorials takes between 10 to 20 minutes. Let's get started!

### General tips

- Edit -> Preference -> Interface -> Line Width: **thick**
- Camera properties -> Viewport Display -> Composition Guide -> **thirds**, **diagonals**, ...
- <kbd>shift</kbd><kbd>c</kbd>: put cursor in the center
- <kbd>ctrl</kvd><kbd>alt</kbd><kbd>0</kbd>: move camera to the current view

### Node wrangler addon

- <kbd>ctrl</kbd><kbd>t</kbd>: plug texture coordinate
- <kbd>ctrl</kbd><kbd>shift</kbd><kbd>left-click</kbd>: preview node
- drag <kbd>ctrl</kbd><kbd>shift</kbd><kbd>right-click</kbd>: mix two nodes

### Donut Tutorial - Part 1 - The basics

Learn how to move around and select things.

- <kbd>~</kbd>: bring menu to focus on object.

### Get Good @ Blender - Part 1 - Beginner Exercises

Learn the edit mode:

- <kbd>ctrl</kbd><kbd>g</kbd>: loop cut
- <kbd>e</kbd>: extrude
- <kbd>i</kbd>: inset face

![desk](media/desk.png)

### Donut Tutorial - Part 6/7 - Rendering/Texturing

Learn the shader node:

- Principled BSDF, based on the Disney PBR shader
- Noise texture + color ramp
- Bump normal

![wood-desk](./media/wood-desk.png)


### Get Good @ Blender - Part 2 - Beginner Exercises

Learn modifier. In object mode:

- <kbd>shift</kbd><kbd>h</kbd>: hide all but selected, use <kbd>alt</kbd> for inverse.
- <kbd>n</kbd>: show item
- <kbd>ctrl</kbd><kbd>a</kbd>: apply transformation/scaling

In edit mode:

- <kbd>c</kbd>: circle select
- <kbd>alt</kbd><kbd>e</kbd>: extrude individual

![wheel](./media/wheel.png)

### Get Good @ Blender - Part 3 - Low Poly Weapons

In edit mode:

- Select menu: select more
- Addon: auto mirror tool, available in edit on the left
- <kbd>g</kbd><kbd>g</kbd>: grab along edge
- <kbd>o</kbd>: proportional editing

![sword](./media/sword.png)

![desk2](./media/desk2.png)


### Get Good @ Blender - Part 4 - Low Poly Buildings

Learn about repeat modifier:

- <kbd>ctrl</kbd><kbd>j</kbd>: join objects
- Combine 3 array modifiers to repeat a wall pattern:

![array-mod](./media/array-mod.png)

![wall](./media/wall.png)

- <kbd>k</kbd>: cut tool
- <kbd>f</kbd>: make face

![planks](./media/planks.png)


### Get Good @ Blender - Part 4 - Hard Surface Modelling 1

- Use *shade smooth*, in the Object data properties -> Normals -> **Auto Smooth**
- Addon: loop tools, and use by right-clicking on edges to create circle.

![loop-tools1](./media/loop-tools1.png)

![loop-tools2](./media/loop-tools2.png)


- Use *Subdivision Surface* modifier, and adjust loop cut to sharpen. That's called supporting edge loop, or proximity edge loop:

![supporting-edge-loop](./media/supporting-edge-loop.png)

![balls](./media/balls.png)


### Nodes 4 Noobs | Lvl 1

![ocean](./media/ocean.png)

### Nodes 4 Noobs | Lvl 2

![node-voronoi](./media/node-voronoi.png)
![musgrave](./media/musgrave.png)

### Nodes 4 Noobs | Lvl 3

![musgrave2](./media/musgrave2.png)
![voronoi2](./media/voronoi2.png)


### [Blender 3D - Create a 3D Isometric BEDROOM](https://www.youtube.com/watch?v=yCHT23A6aJA)

![lowpoly-isometric-room](./media/lowpoly-isometric-room.png)

### [10 Minute Tutorial - Build a Simple Network in Geometry Nodes (Blender Abstract tutorial)](https://www.youtube.com/watch?v=vcESjx01DdA) by [Ducky 3D][d3]

![geometry-nodes](./media/geometry-nodes.png)

![geometry-network](./media/geometry-network.png)


### [How To Get That Modern 3D Look in Blender](https://www.youtube.com/watch?v=eDTvDHIa7TE) by [Ducky 3D][d3]

In edit mode:

- <kbd>f3</kbd>: Mesh -> Separate -> By Loose Parts
- Then in object mode, <kbd>m</kbd>: move to new collection

![separate-loose-parts](./media/separate-loose-parts.png)

- Glass material

![material-glass](./media/material-glass.png)

- Light noise shader for cycles

![light-noise-cycle](./media/light-noise-cycle.png)

- Result:

![modern-look](./media/modern-look.png)

### Loop smoke

- Tutorial video: [The Loop Hole #01 - Looping Smoke Simulations](https://www.youtube.com/watch?v=EJkX83giWlg) by [Midge Sinnaeve][mantissa.xyz]

- Loop technique:
  - Disable flow after frame 150, bake 300 frames.
  - Import the fluid data twice, and offset the second version by 150.
  - Set render loop to 150 frame, and confirm the first and last frame are the same.

- Domain settings:

![loop-smoke-domain](./media/loop-smoke-domain.png)

- Emitter settings:

![loop-smoke-emiter](./media/loop-smoke-emiter.png)

- Smoke shader:

![loop-smoke-shader](./media/loop-smoke-shader.png)

Result:

https://github.com/TristanCacqueray/learn-blender/assets/154392/b008792d-d1b0-4410-aca4-b1a747a20667

### Contoured Curls

- Tutorial video: [Weird Shit S02E02 - Contoured Curls (Blender Curl Noise Volume)](https://www.youtube.com/watch?v=w8jOBRMlaTU) by [Midge Sinnaeve][mantissa.xyz]

- Addon: modifier tools, to apply all

- Remesh modifier:

![remesh-modifier](./media/remesh-modifier.png)

- Dynamic paint mask:

![dynpaint-mask](./media/dynpaint-mask.png)

Result:

![contoured-curls](./media/contoured-curls.png)

- Create geometry taper with poly spline:

![spline-taper](./media/spline-taper.png)


Result:

![contoured-curls](./media/contoured-curls-taped.png)

### Looping an Abstract Particle System

- Tutorial video: [The Loop Hole #02 - Looping an Abstract Particle System](https://www.youtube.com/watch?v=UUPFE99Ou3E)

- Set particle drag:

![particule-drag](media/particule-drag.png)

Result:

https://github.com/TristanCacqueray/learn-blender/assets/154392/4ad857cc-e8bd-464a-9935-122d3ec853a9


### The Shear Tool

- Tutorial video: [Get Good At Blender 3 - The Shear Tool](https://www.youtube.com/watch?v=N8O0bE898Qc&list=PLn3ukorJv4vvv3ZpWJYvV5Tmvo7ISO-NN&index=23) by [Grant Abbitt][grabbitt]

![shear-tool](./media/shear-tool.png)

![shear](./media/shear.png)

### Fog render with principled volume shader

- From: [One hour of greeble](https://www.youtube.com/watch?v=pKxbSiK6NE0)

Result:

![fog-render](./media/fog-render.jpg)

### planet-loop

- Tutorial video: [Physics Loop](https://www.youtube.com/watch?v=C6lF9yv0tXY) by [Ducky 3D][d3]

- Use dynamic paint physic to displace a canvas mesh:

![dynamic-paint](media/dynamic-paint.png)

Result:

https://github.com/TristanCacqueray/learn-blender/assets/154392/ba6e1fcc-7f3d-49cb-b603-201ec757d1c6



# Backlog

- [Compositor Series](https://www.youtube.com/watch?v=M20P4tkNWLM&list=PLn3ukorJv4vvH9O2bE6I8c0rjcz3oot8G) by [Grant Abbitt][grabbitt]

## Photorealism

![light-scale](./media/light-scale.png)
![exposure](./media/exposure.png)


[grabbitt]: https://www.youtube.com/@grabbitt
[d3]: https://www.youtube.com/@TheDucky3D
[mantissa.xyz]: https://mantissa.xyz
