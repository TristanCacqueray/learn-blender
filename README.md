# learn blender

Video resources:

- [The BEST Way To Learn Blender in 2023!!](https://www.youtube.com/watch?v=8K4AShjq-MU) by [Ducky 3D](https://www.youtube.com/@TheDucky3D)
- [Get Good @ Blender](https://www.youtube.com/playlist?list=PLn3ukorJv4vvv3ZpWJYvV5Tmvo7ISO-NN) by [Grant Abbitt][grabbitt]
- [Donut Tutorial](https://www.blenderguru.com/tutorials/2022/1/27/how-to-use-blender) by [Blender Guru](https://www.blenderguru.com)

## Notes

### General tips

- Edit -> Preference -> Interface -> Line Width: **thick**
- Camera properties -> Viewport Display -> Composition Guide -> **thirds**, **diagonals**, ...
- <kbd>shift</kbd><kbd>c</kbd>: put cursor in the center

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



# Backlog

- [Compositor Series](https://www.youtube.com/watch?v=M20P4tkNWLM&list=PLn3ukorJv4vvH9O2bE6I8c0rjcz3oot8G) by [Grant Abbitt][grabbitt]


[grabbitt]: https://www.youtube.com/@grabbitt
