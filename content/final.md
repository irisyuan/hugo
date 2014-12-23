+++
date = "2014-12-11T01:57:50-05:00"
draft = true
title = "Three.js Final 12/23"

+++

Make sure volume is on. Press play button (should load in a few seconds). Play around with zoom in/out/rotation.
View final <a href="http://irisyuan.github.io/threejs/" target="_blank">here</a>.

I used these values for the shapes:

THREE.CylinderGeometry(0, 0.1, 0.08, 20, 1, false);

THREE.MeshPhongMaterial({
	color: randomColor(),
	wireframe: false
});