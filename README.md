# Portfolio - Julián Marqués García

Portfolio personal migrado a [Astro](https://astro.build) para mejorar rendimiento, arquitectura y experiencia de desarrollador.

## 🚀 Cómo empezar

Este proyecto requiere **Node.js** instalado.

1.  **Instalar dependencias:**

    ```bash
    npm install
    ```

2.  **Iniciar servidor de desarrollo:**

    ```bash
    npm run dev
    ```

    La web estará disponible en `http://localhost:4321`.

3.  **Construir para producción:**

    ```bash
    npm run build
    ```

    Esto generará la carpeta `dist/` con los archivos estáticos listos para subir a cualquier hosting (GitHub Pages, Netlify, Vercel...).

4.  **Previsualizar build:**
    ```bash
    npm run preview
    ```

## 🛠️ Stack Tecnológico

- **Astro**: Framework principal.
- **View Transitions**: Navegación SPA nativa.
- **CSS Variables**: Sistema de diseño con modo oscuro/claro.
- **Glassmorphism**: Estilos visuales modernos en CSS puro.

## 📂 Estructura

- `src/pages`: Rutas de la web (`index.astro`, `about.astro`, `projects.astro`).
- `src/components`: Componentes reutilizables (`Header`, `Footer`, `ThemeToggle`).
- `src/layouts`: Plantilla base HTML (`Layout.astro`).
- `public/`: Assets estáticos (imágenes, fuentes, favicon).
