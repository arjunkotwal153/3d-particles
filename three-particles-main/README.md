<div align="center">
  <img src="./docs/hero.svg" alt="Three Particles — a colorful 3D particle world" width="100%" />

  <br />

  <p><strong>A little universe, built one particle at a time.</strong><br />
  A real-time WebGL experiment in motion, color, and computational geometry.</p>

  <p>
    <img src="https://img.shields.io/badge/Three.js-WebGL-111827?style=for-the-badge&logo=threedotjs&logoColor=white" alt="Three.js and WebGL" />
    <img src="https://img.shields.io/badge/Vite-powered-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Powered by Vite" />
    <img src="https://img.shields.io/badge/GLSL-custom%20shaders-7C3AED?style=for-the-badge" alt="Custom GLSL shaders" />
  </p>
</div>

## In motion

This short screen recording shows the particle simulation running in the browser. The scene is rendered live with Three.js and custom shaders.

<div align="center">
  <img src="./docs/particle-demo.gif" alt="Screen recording of the colorful Three Particles simulation in motion" width="760" />
</div>

## Inside the scene

<div align="center">
  <img src="./docs/tech-icons.svg" alt="3D illustrations for GPU simulation, shader particles, and tracery" width="100%" />
</div>

- **262,144 animated particles** — particle positions evolve on the GPU with a curl-noise simulation.
- **Custom shader rendering** — GLSL shaders shape, shade, and color the particles in real time.
- **Generative tracery** — drifting coordinate labels and dashed connections add a subtle data-visualization layer.
- **Motion blur and lighting** — post-processing, shadows, and environment lighting give the scene depth.
- **Responsive canvas** — the camera and rendering adapt to the browser viewport.

## Run it locally

You’ll need [Node.js](https://nodejs.org/) and npm.

```bash
npm install
npm run dev
```

Open the local URL printed by Vite. To create a production build:

```bash
npm run build
npm run preview
```

## Built with

| Tool | Role |
| --- | --- |
| [Three.js](https://threejs.org/) | 3D scene, renderer, and GPU computation |
| [GLSL](https://www.khronos.org/opengl/wiki/OpenGL_Shading_Language) | Particle simulation and rendering shaders |
| [Vite](https://vite.dev/) | Local development and production build |
| [Tailwind CSS](https://tailwindcss.com/) | Base styling |

<div align="center">
  <br />
  <sub>Made with curiosity by <strong>Kamlesh Singh Kotwal</strong></sub>
</div>
