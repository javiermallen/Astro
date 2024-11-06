![Astro](image.png)(#center)

Comenzando con Astro

pnpm create astro@latest 

🚀 Estructura básica de un proyecto

Dentro de tu proyecto Astro, verás las siguientes carpetas y archivos:

├── public/

├── src/

│   ├── components/

│   ├── content/

│   ├── layouts/

│   └── pages/

├── astro.config.mjs

├── README.md

├── package.json

└── tsconfig.json

Astro busca archivos .astro o .md en el directorio src/pages/. Cada página se expone como una ruta basada en su nombre de archivo.
En la carpeta src/components/, es donde se suelen poner los componente de Astro/React/Vue/Svelte/Preact.
En la carpeta src/layouts/, se colocaran las plantillas de Astro, estas son componentes de Astro para proporcionar una estructura reutilizable, como una plantilla de página.
Cualquier activo estático, como imágenes, puede colocarse en el directorio public/.

🧞 Comandos

Todos los comandos se ejecutan desde la raíz del proyecto, desde un terminal:

| Comando                   | Acción                                                        |
|---------------------------|---------------------------------------------------------------|
| pnpm install              | Instalar dependencias.                                        |
| pnpm run dev              | Inicia un servidor local de desarroollo en localhost:4321     |
| pnpm run build            | Construye el sitio en producción en la carpeta ./dist/        |
| pnpm run preview          | PPrevisualiza tu compilación localmente, antes de desplegarla |
| pnpm run astro ...        | Ejecuta comandos CLI como astro add, astro check              |
| pnpm run astro -- --help  | Obtener ayuda sobre el uso de Astro CLI                       |

👀 ¿Quieres saber más?

No dudes en consultar la documentación de [Astro](https://docs.astro.build/en/getting-started/)

🧑🏿‍🚀 Instalaciones Recomendadas

Imprescindibles

    Visual Studio Code

    Node

Programa para pruebas de API

    Postman

    Insomnia

SQLite Viewers

    SQLiteBrowser

    Table Plus

Instalaciones adicionales para Visual Code

    Necesaria - Astro - Language Support

    Paste JSON as Code

    .env

    Tailwind CSS IntelliSense

    Auto Rename Tag

    Console Ninja

    DotEnv

    Easy Snippet

    Error Lens

    SQLite Viewer

    Turbo Console Log



