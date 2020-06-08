# Threejs-VR-Hipparcos

Explore Hipparcos Catalogue of 119,617 stars with Threejs VR.<br>

<img src="images/hipparcos_color_index.jpg" width="720">

<img src="images/hipparcos_color_index_stereo.jpg" width="720">

Stereoscopic view. The yellow sphere is the Solar system. Lower left is Alpha Centauri, closest star system ~4 light years.<br>

# Hardware

Oculus Quest recommended (required 6DOF headset/controllers).<br>

# Software

Oculus Browser (tested Quest Update >17.0 and three.js r115).

# Threejs-VR-Hipparcos Pages

[https://physicslibrary.github.io/Threejs-VR-Hipparcos/](https://physicslibrary.github.io/Threejs-VR-Hipparcos/)

# Installation

No installation.<br>

In Oculus Quest, open Oculus Browser and go to link (let browser finished loading before "Enter VR"):<br>

[https://physicslibrary.github.io/Threejs-VR-Hipparcos/examples/threejs_vr_hipparcos_color_index.html](https://physicslibrary.github.io/Threejs-VR-Hipparcos/examples/threejs_vr_hipparcos_color_index.html)

Solar system is the yellow sphere.<br>

Use Oculus Touch controllers to move around stars. It implements a simple way to move around 3D by making a "velocity vector" from left to right controllers.<br>

The distance between controllers is the speed (controller next to the other is the lowest speed).<br>

Press one front trigger to move (two triggers to double speed).<br>

Hold the left controller fixed and point the right controller in the direction to move.<br>

Other buttons on controllers do not work, yet.<br>

# References

[https://threejs.org/](https://threejs.org/)

hygxyz.csv (1989 data):<br>
[https://github.com/astronexus/HYG-Database](https://github.com/astronexus/HYG-Database)

[https://www.cosmos.esa.int/web/hipparcos/home](https://www.cosmos.esa.int/web/hipparcos/home)

[https://www.cosmos.esa.int/web/hipparcos/common-star-names](https://www.cosmos.esa.int/web/hipparcos/common-star-names)

[http://sci.esa.int/star_mapper/](http://sci.esa.int/star_mapper/)

[https://en.wikipedia.org/wiki/Hipparcos](https://en.wikipedia.org/wiki/Hipparcos)

This project is a port of [https://github.com/Physicslibrary/ARKit-Stereoscope-Hipparcos](https://github.com/Physicslibrary/ARKit-Stereoscope-Hipparcos) which started with a book "3D Scientific Visualization with Blender". In the book, there is a tutorial on how to plot a stellar catalog.

Brian R. Kent, 3D Scientific Visualization with Blender, Morgan & Claypool Publishers (2015).

[https://www.cv.nrao.edu/~bkent/blender/thebook.html](https://www.cv.nrao.edu/~bkent/blender/thebook.html)

[https://www.cv.nrao.edu/~bkent/blender/tutorials.html](https://www.cv.nrao.edu/~bkent/blender/tutorials.html)

Three.js on how to convert WebGL examples to WebVR:

[https://threejs.org/docs/index.html#manual/en/introduction/How-to-create-VR-content](https://threejs.org/docs/index.html#manual/en/introduction/How-to-create-VR-content)

Three.js on how to load a file (eg. read hygxyz.csv):

[https://threejs.org/docs/index.html#api/en/loaders/FileLoader](https://threejs.org/docs/index.html#api/en/loaders/FileLoader)

Three.js on how to draw a star field:

[https://threejs.org/docs/#api/en/materials/PointsMaterial](https://threejs.org/docs/#api/en/materials/PointsMaterial)

Three.js examples is the best place to learn and experiment:

[https://github.com/mrdoob/three.js/tree/dev/examples](https://github.com/mrdoob/three.js/tree/dev/examples)

[https://github.com/Physicslibrary/Threejs-WebXR-67P](https://github.com/Physicslibrary/Threejs-WebXR-67P)

[https://stars.chromeexperiments.com/](https://stars.chromeexperiments.com/)

[https://www.html5rocks.com/en/tutorials/casestudies/100000stars/](https://www.html5rocks.com/en/tutorials/casestudies/100000stars/)

http://exploratoria.github.io/exhibits/astronomy/star-spotter/index.html

The next two links are no longer updated. The first uses the headset 6DOF tracking and no controllers. The second is a scale down slice view of Hipparcos Catalog.<br>

[https://physicslibrary.github.io/Threejs-VR-Hipparcos/examples/webxr_vr_hipparcos.html](https://physicslibrary.github.io/Threejs-VR-Hipparcos/examples/webxr_vr_hipparcos.html)

[https://physicslibrary.github.io/Threejs-VR-Hipparcos/examples/webxr_vr_hipparcos2.html](https://physicslibrary.github.io/Threejs-VR-Hipparcos/examples/webxr_vr_hipparcos2.html)

# Making Threejs-VR-Hipparcos (under construction)

Camera frustum far plane default is 1000. Check how many stars appears when far plane is varied.<br>

[https://threejs.org/docs/#api/en/cameras/PerspectiveCamera](https://threejs.org/docs/#api/en/cameras/PerspectiveCamera)

Use 6th column ProperName in hygxyz.csv to display common star names.<br>

<br><br>Copyright (c) 2020 Hartwell Fong
