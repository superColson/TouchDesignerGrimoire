## 3D Trails

Based on an [Atagen tutorial](https://www.youtube.com/watch?v=ykpkqmoxRyo), 3D trails processed with GLSL MAT, use of swaggy_bokeh by Ovvostudio, Bloom fx by keithlostracco

<p align="center">
<img src="https://github.com/superColson/TouchDesignerGrimoire/raw/master/graphical_research/3d_trails/pvw.gif" alt="pvw image not found" width="720" height="500"/>
</p>



## Bees & Bombs cubes pattern

Reproduction of [Dave Whyte work](https://www.instagram.com/p/BFKeuxOlont/?utm_source=ig_web_copy_link), isometric view of cubes rotation. Animation is driven by a 32-bit color ramp which holds the rx ry rz values.

<p align="center">
<img src="https://github.com/superColson/TouchDesignerGrimoire/raw/master/graphical_research/beesbomb_cubes_pattern/pvw.gif" alt="pvw image not found" width="500" height="500"/>
</p>

## Cube voxels

sampling Simplex 3D noise to scale cube instances. SSAO on render

<p align="center">
<img src="https://github.com/superColson/TouchDesignerGrimoire/raw/master/graphical_research/cube_voxels/pvw.gif" alt="pvw image not found" width="500" height="500"/>
</p>

## Point Cloud Tutorial by Markus Heckmann (Derivative)

Project based on fantastic [Markus Heckmann point cloud tutorial](https://www.youtube.com/watch?v=QB3P0-uCszo) , it creates a 3D mesh particle dissolve effect, all the particle system (position, life, color) is built with TOP, very cool features explained here. Project also contains a custom OBJ to Point Cloud converter/normalizer.

<p align="center">
<img src="https://github.com/superColson/TouchDesignerGrimoire/raw/master/graphical_research/experimental_pointcloud_markus_tutorial/pvw.gif" alt="pvw image not found" width="500" height="500"/>
</p>



## Font Destroyer

Old demo project which explores SOP Text destroying possibilities as graphic FX. Uses Facet SOP, primitive animation driven by noise. Also contains camera animation, wireframe render and some post-FX

<p align="center">
<img src="https://github.com/superColson/TouchDesignerGrimoire/raw/master/graphical_research/font_destroyer/pvw.gif" alt="pvw image not found" width="720" height="500"/>
</p>



## Instanced Sea

Grid of instanced cubes, scale animation driven by Noise TOP. Proper setup of shadows rendering.

<p align="center">
<img src="https://github.com/superColson/TouchDesignerGrimoire/raw/master/graphical_research/instanced_sea/pvw.gif" alt="pvw image not found" width="720" height="500"/>
</p>



## Instances vector rotate

Proper setup of instances oriented to point normal vector, uses the add SOP to add an up vector attribute, line MAT for rendering.

<p align="center">
<img src="https://github.com/superColson/TouchDesignerGrimoire/raw/master/graphical_research/instances_vector_rotate/pvw.gif" alt="pvw image not found" width="720" height="500"/>
</p>

## Noise displacement Polyhop tutorial

Based on [Simon Alexander-Adams tutorial](https://www.simonaa.media/tutorials/noisedisplacement), Simplex 3D Noise resampled twice and used to generate normal and height map in the Phong material. SSAO on the render. very cool stuff

<p align="center">
<img src="https://github.com/superColson/TouchDesignerGrimoire/raw/master/graphical_research/noise_displacement_polyhop/pvw.gif" alt="pvw image not found" width="500" height="500"/>
</p>



## Circle Collision Paketa12 tutorial

Based on [Aurelian Ionus aka Paketa12 tutorial](https://www.youtube.com/watch?v=w47xTWMNTFA), 2D circles collision detection built only with TOP operators (totally mindblowing)

<p align="center">
<img src="https://github.com/superColson/TouchDesignerGrimoire/raw/master/graphical_research/paketa12_circlecollision/pvw.gif" alt="pvw image not found" width="500" height="500"/>
</p>



## Particles oriented

Old demo project of cubic particles oriented towards their movement path. Shadow rendering setup, camera animation, rim lighting, depth of field luma blur, various render passes for post FX purposes. 

<p align="center">
<img src="https://github.com/superColson/TouchDesignerGrimoire/raw/master/graphical_research/particles_oriented/pvw.gif" alt="pvw image not found" width="720" height="500"/>
</p>



## Plexus Effect Paketa12 tutorial v2

updated to v2, Based on [Aurelian Ionus aka Paketa12 tutorial](https://www.youtube.com/watch?v=0A01XKt_3rM), plexus-like effect built with TOP operators (and a few CHOP), awesome texture maths in there !

<p align="center">
<img src="https://github.com/superColson/TouchDesignerGrimoire/raw/master/graphical_research/plexus_paketa12/pvw_v2.gif" alt="pvw image not found" width="720" height="500"/>
</p>



## Rutt-Etra scanlines FX

Recreate the cool fx from analog synthetizer Rutt-Etra, vertex displacement based on input texture luminance. made with GLSL material

<p align="center">
<img src="https://github.com/superColson/TouchDesignerGrimoire/raw/master/graphical_research/rutt_etra/pvw.gif" alt="pvw image not found" width="720" height="500"/>
</p>



## Spring lines

Lines behaving like springs with constrained ends, affected by external force. Lots of mystic SOP operator in there: metaball SOP, Force SOP, Spring SOP... 

<p align="center">
<img src="https://github.com/superColson/TouchDesignerGrimoire/raw/master/graphical_research/spring_lines/pvw.gif" alt="pvw image not found" width="720" height="500"/>
</p>



## Text particle attractor

Particles attracted by text, based on trace SOP and particle SOP, proof of concept that could be rethink in a more optimized way

<p align="center">
<img src="https://github.com/superColson/TouchDesignerGrimoire/raw/master/graphical_research/text_particle_attractor/pvw.gif" alt="pvw image not found" width="720" height="500"/>
</p>



## Topography

Attempt to recreate the work of [Mike Creighton on topography line effect](https://butdoesitfloat.com/There-probably-is-a-God-Many-things-are-easier-to-explain-if-there-is) originally made in Processing. the line is generated by a Noise TOP, that could be replaced by a live video feed for more organic results. Effect is done by displacing the generated lines with a feedback TOP. 

<p align="center">
<img src="https://github.com/superColson/TouchDesignerGrimoire/raw/master/graphical_research/topography/pvw.gif" alt="pvw image not found" width="720" height="500"/>
</p>



## Truchet Tiles

Little demo of Truchet tiles animation

<p align="center">
<img src="https://github.com/superColson/TouchDesignerGrimoire/raw/master/graphical_research/truchet_tiles/pvw.gif" alt="pvw image not found" width="500" height="500"/>
</p>



## Wireframe Landscape

Discord challenge to recreate artwork from ???. Multiple noises + height map in PhongMAT  to create the "mountain" effect

<p align="center">
<img src="https://github.com/superColson/TouchDesignerGrimoire/raw/master/graphical_research/wireframe_landscape/pvw.gif" alt="pvw image not found" width="500" height="600"/>
</p>