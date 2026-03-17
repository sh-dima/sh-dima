Minecraft Profile
=================

These are the instructions to generate my Minecraft profile picture.

Make sure you are using the [correct skin](./Skin.png) and the migrator cape.

Install the following mods on Minecraft 1.21.11 with Fabric:
* [Simple Image Renderer v1.1.0+1.21.11](https://modrinth.com/project/kp31625Q/version/J3laIGuM)
* [3D Skin Layers v1.10.2](https://modrinth.com/project/zV5r3pPn/version/JS9deRtw)
* [No Idle Animation v1.0.0](https://modrinth.com/project/ooznHpAN/version/v8vvKm1T)

Configure 3D Skin Layers with the following values:
```
Fast Render: unchecked
```

Steps taken to create the render:
1. Make sure the character is still and not moving.
2. Run `/render entity @s`
3. Specify the following settings:
	```
	Width: 1024
	Height: 1024
	Pitch: 15
	Yaw: 30
	Roll: -3
	Scale: 215%
	X: 0.2
	Y: 6.65
	Rotate Light: OFF
	Lighting: ENTITY_IN_UI
	Body Rotation: OFF
	Head Rotation: OFF
	Entity Age: <Unchanged> -1
	Walking Pos: <Unchanged> -1
	Walking Speed: <Unchanged> -1
	```
4. Click "Render Image".
