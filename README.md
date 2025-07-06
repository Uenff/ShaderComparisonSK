# ShaderComparisonSK
For '25 SK2 in HS Anhalt, Testat3.

#Contents

This repo includes:
* Scenes for testing tweo simple procedural Shaders.
* Code for the shaders in Unity and Godot.
* The RenderDoc Snapshots taken.


# General Takeaways:

Unity Brick: 117 Draw Calls.
Unity Wood: 66 Draw Calls.
First Comparison:
Metric	Brick Shader/Wood Shader
Draw Calls	117/66
Geometry per draw	Cube: (36 indices)	Cube (36 indices)
Fragment Shader Loops:	3 noise rounds	8 FBM + Musgrave
Overdraw (estimated)	Moderate /	Same
Shader ALU Complexity	Medium	/High
Texture Fetches	0	/0
Memory Use	Low	/Low

