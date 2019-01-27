# UnityUiParticles
Unity ParticleSystem for built-in UI

Full compatibility with Unity UI Canvas: sorting order, masking, UI shaders etc...
Size and speed of particles are canvas-based coordinate system.

## Usage
Just add ParticleSystemMeshGenerator to gameobject with ParticleSystem.

## Restrictions
Texture sheet animation 'Sprites' mode is unsupported due to availability of using the
'Trails' module that requires second material in one canvas renderer.
Otherwise, 'Sprites' mode requires that all the sprites were inside the same texture, makes it redundant.
Just use the 'Grid' mode instead.

## Requirements
Unity 2018.2+ due to new interface for ParticleSystemRender:
* BakeMesh
* BakeTrailsMesh
