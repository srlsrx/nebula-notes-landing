# Nebula Notes Landing

**Este proyecto es un producto ficticio creado únicamente con fines educativos y de práctica. Su objetivo es entender y experimentar con Astro y tecnologías modernas de desarrollo frontend. No representa un producto real ni está asociado a ninguna empresa.**

Nebula Notes Landing es la página de presentación de Nebula Notes, una aplicación de toma de notas en Markdown diseñada específicamente para desarrolladores. Este proyecto está construido con [Astro](https://astro.build/) y utiliza TailwindCSS para el diseño y estilos.

## 🚀 Estructura del Proyecto

```
/
├── public/                  # Archivos públicos y estáticos (favicon, imágenes)
├── src/
│   ├── assets/              # Recursos gráficos y fuentes
│   ├── components/          # Componentes reutilizables de la UI (Header, Footer, Hero, etc.)
│   ├── icons/               # Iconos personalizados
│   ├── layouts/             # Layouts base (Layout.astro)
│   ├── pages/               # Páginas del sitio (index.astro)
│   └── styles/              # Hojas de estilos globales
├── .astro/                  # Archivos generados por Astro
├── .vscode/                 # Configuración recomendada para VS Code
├── package.json             # Dependencias y scripts del proyecto
├── pnpm-lock.yaml           # Archivo de bloqueo de dependencias (pnpm)
├── pnpm-workspace.yaml      # Configuración de workspace para pnpm
├── tsconfig.json            # Configuración de TypeScript
├── astro.config.mjs         # Configuración de Astro
└── .gitignore               # Archivos y carpetas ignorados por git
```

## ✨ Características

- **Landing page moderna** con diseño responsive.
- **Componentes reutilizables**: Hero, BentoFeatures, AppMockup, Testimonial, PreFooterCTA, Header, Footer.
- **Soporte para Markdown** y resaltado de sintaxis.
- **Estilos con TailwindCSS**.
- **Optimizado para desarrolladores**: enfoque en la productividad y la organización.

## 📦 Instalación

1. Clona el repositorio:
   ```sh
   git clone https://github.com/srlsrx/nebula-notes-landing
   cd nebula-notes-landing
   ```

2. Instala las dependencias:
   ```sh
   pnpm install
   ```

## 🧞 Comandos

Todos los comandos se ejecutan desde la raíz del proyecto:

| Comando         | Acción                                               |
|-----------------|-----------------------------------------------------|
| `pnpm dev`      | Inicia el servidor de desarrollo en `localhost:4321`|
| `pnpm build`    | Compila el sitio para producción en `./dist/`       |
| `pnpm preview`  | Previsualiza el build de producción localmente      |
| `pnpm astro ...`| Ejecuta comandos CLI de Astro                       |

## 🛠️ Scripts

- `dev`: Inicia el entorno de desarrollo.
- `build`: Compila el sitio para producción.
- `preview`: Previsualiza el build.
- `astro`: Acceso directo a la CLI de Astro.

## 🧩 Componentes Principales

- `Header.astro`: Barra de navegación principal.
- `Hero.astro`: Sección principal de bienvenida.
- `BentoFeatures.astro`: Características destacadas.
- `AppMockup.astro`: Vista previa de la app.
- `Testimonial.astro`: Testimonios de usuarios.
- `PreFooterCTA.astro`: Llamada a la acción antes del pie de página.
- `Footer.astro`: Pie de página con enlaces y redes sociales.

## 📄 Página Principal

- `index.astro`: Página de inicio que integra todos los componentes principales.

## 🖌️ Estilos

- TailwindCSS configurado en `src/styles/global.css`.

## 📝 Licencia

Este proyecto está bajo la licencia MIT.

---

¿Quieres contribuir? ¡Pull requests y sugerencias son bienvenidas!

```
Nota: Actualiza `https://github.com/srlsrx/nebula-notes-landing` con la URL real de tu repositorio.
