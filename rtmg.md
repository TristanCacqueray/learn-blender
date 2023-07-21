[Real Time Motion Graphics](https://blendermarket.com/products/rtmg)
====================================================================

# Shortcuts

## Viewport

- <kbd>shift</kbd><kbd>c</kbd>: move the cursor to the origin of the scene
- <kbd>shift</kbd><kbd>z</kbd>: toggle wireframe view

- <kbd>ctrl</kbd><kbd>alt</kbd><kbd>0</kbd>: move camera to match the current view

## Object mode

- <kbd>ctrl</kbd><kbd>a</kbd>: apply transformation/scaling

## Edit mode

- <kbd>ctrl</kbd><kbd>a</kbd>: changes the vertex radius (useful with skin modifier)

## Timeline

- <kbd>shift</kbd><kbd>left/right</kbd>: jump to begining/end


# Intro

## 1 - Setup

- Remove workspace from startup file
- Setup a three column views
- Disable viewport anti-aliasing
- Set animation default interpollation to linear

## 202 - Simple Cable

Create cable with:

- apply skin modifier to a single point
- extrude to shape the cable
- apply subdivide modifier to reduce control points
- apply displace modifier to adjust path location

## 203 - Modifier Coordinates

Create terrain:

- subdivide a plane
- apply displace modifier
- set displace texture to noise
- change texture coordinate to taste

## 501 - indirect lightning

- Lower light custom distance
- Add irradiance volume

![rtmg-irradiance](media/rtmg-irradiance.png)

- Adjust probes
- Bake the indirect light
- Display irradiance size to observe the effect

![rtmg-irradiance-debug](media/rtmg-irradiance-debug.png)

- Result:

![rtmg-01](./media/rtmg-01.jpg)


# Second part

## 204 - Deforming Arrays

Create a rope procedurally.

- apply array modifier using an empty plane offset object
- rotate the plane offset to create the threads
- apply simple deform modifier for the twist effect
- apply curve modifier to follow a bezier path

- Result:

![rtmg-02-rope](./media/rtmg-02-rope.jpg)


https://github.com/TristanCacqueray/learn-blender/assets/154392/b472fac8-2e4f-40af-8ea6-8f86c38dfacb
