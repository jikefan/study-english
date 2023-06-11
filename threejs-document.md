# Creating a Scene

The goal of the section is to give a brief(简要) introduction to three.js. We will start by setting up a scene, with a spining cube(一个旋转立方体).A working example is provided at the bottom of the page in case you get stuck and need help.

## Before we start

If you have't yet, go through the Installation guide. We'll assume you've already set up the same project structure (including index.html and main.js), have install three.js, and are either running a build tool, or using a local server with a CDN and import maps.

## Creating the Scene

To actually be able to display annoying with three.js, we need three things:scene, camera and renderer, so that we can render the scene with camera.

*main.js--*

```js
import * as THREE from 'three';

const scene = new THREE.Scene();
const camera = new THREE.PerspectiveCamera(75, window.innerWidth / window.innerHeight, 0.1, 1000);
```



