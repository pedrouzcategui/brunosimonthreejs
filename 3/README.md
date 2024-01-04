# Scene

- Scene
- Objects
- Camera
- Renderer

## How to import Three.js

## What is a Scene

Is a container where we put objects, models, particles, lights, etc...

## How to create a scene

We create a Scene by instantiating a class

```js
const scene - new THREE.scene();
```

## What are objects?

Objects are things like primitive geometries, imported models, particles, lights, etc...

## What is a Mesh

It's a combination of geometry (the shape) and a material (how it looks)

## Create a Geometry

```js
const geometry = new Three.BoxGeometry(1, 1, 1);
```

## Assign a Material to the Geometry (create a mesh)

```js
const geometry = new THREE.BoxGeometry(1, 1, 1);
const geometry = new THREE.MeshBasicMaterial({ color: 0xff0000 });

const mesh = new THREE.Mesh(geometry, material);
scene.add(mesh); // Add the mesh to the scene
```

## How to specify colors in Three

We can use hex values

```js
const material = new Three.MeshBasicMaterial({ color: 0xff0000 });
```

We can use strings

```js
const material = new Three.MeshBasicMaterial({ color: "ff0000" });
```

We can use literal values

```js
const material = new Three.MeshBasicMaterial({ color: "red" });
```

We can instantiate the Color Class

```js

```

## What is a Camera?

Theoretical point of view used when rendering.
We can have multiple, but usually we just use one.

## Using a camara

Let's use a Perspective Camera

```js
// Field of View, express on degrees
```

## Renderer

## Camera Position

## Wireframe property on Materials
