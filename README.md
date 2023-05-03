Hello! My name is Julius Häger and I'm a Swedish graphics programmer.

I'm the current maintainer of [OpenTK](https://github.com/opentk/opentk), a platform abstraction layer and OpenGL bindings for C#, and this is my work.

# [OpenTK](http://github.com/opentk/opentk) maintainer

OpenTK provides OpenGL bindings and window creation and management for C#, and has over 3.5 million downloads on [Nuget](https://www.nuget.org/packages/OpenTK/).

I've been maintainer for OpenTK since November 2020. 
During that time we've worked hard on our new OpenGL bindings generator and platform abstraction layer targeting Win32, Linux, and macos.

<a href="http://github.com/opentk/opentk"><img src="img/OpenTK.png" alt="OpenTK banner." width="100%"></a>

# [Two New Methods for Real-Time Ptex](http://www.diva-portal.org/smash/get/diva2:1701157/FULLTEXT01.pdf)

In 2022 me and Hugo Dettner presented two new methods for efficiently rendering and filtering ptex on the GPU in real-time as part of our Batchelor's thesis. One of our presented methods outperformed previous work while having quality matching previous state of the art.

<a href="http://www.diva-portal.org/smash/get/diva2:1701157/FULLTEXT01.pdf"><img src="img/ptex.png" alt="Image showing the individual ptex quads." width="100%"></a>

# Real-time GPU path tracer

<img src="img/path-tracer.png" alt="Path traced Cornell box." width="80%">

I made a small real-time GPU path tracer for the course DH2323 at KTH. 
It's written in C# using OpenTK, and has BVH acceleration.

<img src="img/misc/bunny_bvh.png" alt="Stanford bunny containd within lots of BVH boxes." width="80%">

# Game engine using OpenTK/C#

A "from scratch" game engine written with OpenTK. It features a PBR render pipeline, cascaded shadow maps, frustum culling, and integrated physics using [BepuPhysics2](https://github.com/bepu/bepuphysics2). The engine also contains nice to have features such as live shader reloading.

![sponza](img/sponza_editor.png)

![gizmo-and-undo](img/misc/gizmo_and_undo.mp4)

Video showing transform gizmo and undo functionality.

![shader-reload](img/misc/live_shader_reload.mp4)

Video showing live shader reloading.

![frustum-culling](img/misc/frustum_culling.mp4)

Video showing frustum culling.

# [Metro vision](https://marcuskaraker.itch.io/metrovision)

<img src="img/metrovision.png" alt="Metro Vision start screen" width="80%">

Metro vision was made during the 2020 GMTK Game Jam where I and a team of 8 other people made a innovative puzzler where your line of sight determines what controls/actions are available at your displosal.

<img src="img/metrovision2.png" alt="Metro Vison gameplay screenshot showing that some controls are not in sight and as such not possible actions to take." width="80%">

# [Candela](https://swedishpancaces.itch.io/candela)

A small charming game about a candle finding it's place. Make in 48 hours for the 2017 GMTK Game Jam, in a team of 3 people.

<img src="img/candela_gameplay2.png" alt="Gameplay screenshot of candela." width="80%">

<img src="img/candela_gameplay5.png" alt="Gameplay screenshot of candela." width="80%">

<img src="img/candela_gameplay3.png" alt="Gameplay screenshot of candela." width="80%">

# [Block buster](https://globalgamejam.org/2019/games/block-buster)

Block Buster was created in 48h during the 2019 Global Game Jam in a team of 9 people.

<iframe width="560" height="315" src="https://www.youtube.com/embed/yMX827OTp2c" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<img src="img/blockbuster_gameplay.png" alt="Gameplay screenshot of candela." width="80%">

# Gallery

A gallery of random screenshots from my graphics coding adventures.

![pbr](img/misc/pbr.png)
PBR sphere.

![lights](img/misc/lights.png)
Multiple lights and editor gizmos.

![particles](img/misc/particles.png)

Particle effect.

![mandelbrot](img/misc/mandelbrot.png)

Mandelbrot set visualization.

![particles-shadow](img/misc/particles_with_shadows.png)

Particle system with shadowed particles, creating an illusion of volumetric shadow.

![](img/misc/boxes.png)
![](img/misc/boxes2.png)
![](img/misc/boxes3.png)

Debugging visualizations created when implementing Cascaded Shadow Maps.

![imgui](img/misc/imgui.png)

![imgui](img/misc/imgui_text_edit.webm)

![imgui](img/misc/color_picker.mp4)

An Immediate Mode GUI I made.