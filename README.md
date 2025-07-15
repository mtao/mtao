### Hi there 👋
I'm a Faculty Fellow at New York University working with [Daniele Panozzo](/danielepanozzo). 
My interests lie in improving the fidelity of physically based simulations by improving how the geometry of boundary conditions are represented and handled.
My PhD was on this topic, where I developed [Mandoline](https://github.com/mtao/mandoline) to do discretize dirty input geometry into volumetric **cut cell meshes** and used [VEMPIC](mtao/vempic) to combine these cut-cell meshes with the **Virtual Element Method** to make [fluid simulations](https://www.youtube.com/watch?v=V8Hlt66qrys).

#### Current Work
I'm currently primarily working my fork of the [Wildmeshing Toolkit](https://github.com/mtao/wildmeshing-toolkit), which uses a transactional attribute management system to declaratively define stdndard meshing algorithms on multiple meshes simultaneously (and keeping them synchronized!).

On the side I've continued various explorations to keep up to date on programming. Currently experimenting with C++26/Conan/Meson via [zipper](https://github.com/mtao/zipper), a generic tensor library that tries to follow [Eigen](https://eigen.tuxfamily.org) and use C++23's `mdspan`. I'm trying to abstract individual operations from base types so I can generically switch between Matrices, Vectors, Tensor, and Alternating Tensor (Forms).
This is being dogfooded by an [experimental raytracer](https://github.com/mtao/AnotherRayTracer) I'm using to experiment with deferring/avoiding division as much as possible and learning more about some fun math like geometric algebra and plucker coordinates.

I'm also working on a second version of my [core](https://github.com/mtao/core) library in what I'm calling [balsa](https://github.com/mtao/balsa), for which I'm trying to build a generic baseline for projects that can switch between GLFW+imgui and full blown Qt. These two libraries are pretty unfocused, and my intent is to move any large organized segments of code off into their own projects as they organically emerge.

#### Tooling
Lots of C++, working on gaining decent competency with the most modern stuff, but I write lots of Python/Bash as well. Trying to learn some Rust/Go on the side.
Traditionally used CMake to build the C++, but working on using Meson with Conan, though I'm also using CPM for some stuff as well. Have also used scons/bazel as well.


<!--
**mtao/mtao** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
