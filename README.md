#Proyecto con Vite — Guía Rápida

Este README explica cómo instalar, ejecutar y construir el proyecto de Optimización de Transporte Público creado con **Vite** y **TypeScript**, de forma simple y directa.

##Requisitos previos

Asegúrate de tener instalados:

  * **Node.js** (versión 16 o superior)
  * **npm** o **Yarn**

---

##Instalación

Primero, clona el repositorio e instala las dependencias del proyecto:

```bash
npm install
```

O si usas Yarn:

```bash
yarn
```

-----

##Ejecutar en modo desarrollo

Para iniciar el servidor local de desarrollo:

```bash
npm run dev
```

O con Yarn:

```bash
yarn dev
```

El proyecto se abrirá en:

```
http://localhost:5173/
```

-----

##Construir para producción

Para generar la versión optimizada del proyecto:

```bash
npm run build
```

Esto creará la carpeta:

```
dist/
```

-----

##Previsualizar la build

Si quieres ver cómo se comporta la versión final optimizada:

```bash
npm run preview
```

-----

##Estructura del Proyecto

Esta es la estructura específica de tu proyecto, haciendo énfasis en la división entre la lógica de la aplicación y los algoritmos:

```
project/
│── index.html
│── vite.config.ts
│── package.json
│── /src
│     ├── main.ts
│     ├── styles.css
│     ├── /data/ 
│     │     ├── (datasets: METRO, RUTAS, SITP, TM)
│     ├── /interfaces/ 
│     │     ├── (tipos de TypeScript)
│     └── /algorithms/ 
│           ├── Graph.ts
│           ├── /Btree+/
│           └── /TransformData/
```

-----

##Scripts disponibles

```json
"scripts": {
  "dev": "vite",
  "build": "vite build",
  "preview": "vite preview"
}
```

-----
