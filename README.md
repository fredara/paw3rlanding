# PAW3R Landing

Landing divertida y dinámica para **PAW3R** — ropa con actitud. Caracas, Venezuela.

- **Astro** + **Tailwind CSS**
- Mobile first, responsive
- Tres idiomas: **ES** · **EN** · **Ugo** (mascota gorila caraqueño, modismos y humor venezolano)
- Efectos hover y animaciones
- Todos los botones llevan a [paw3r.com](https://paw3r.com/)

Si quieres ver la landing page: 
https://paw3rlanding.vercel.app/


## Cómo correr el proyecto

```bash
npm install
npm run dev
```

Abre [http://localhost:4321](http://localhost:4321).

## Build para producción

```bash
npm run build
npm run preview
```

## Estructura

- `src/pages/index.astro` — página principal (landing)
- `src/layouts/Layout.astro` — layout base
- `src/styles/global.css` — estilos globales y utilidades
- `public/images/` — imágenes (logo, referencias, Ugo)

Las imágenes se sirven desde `public/images/`. El idioma se guarda en `localStorage` (`pawer-lang`).
