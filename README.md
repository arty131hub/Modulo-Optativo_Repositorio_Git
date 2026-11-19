# Mi Proyecto Web

Proyecto de práctica para aprender **Git** y **GitHub**: creación de un repositorio, trabajo con ramas, Pull Requests y documentación en Markdown. La web está hecha únicamente con HTML.

## Tabla de contenido

- [Instalación](#instalación)
- [Estructura](#estructura)
- [Mejoras implementadas](#mejoras-implementadas)
- [Flujo de trabajo con Git](#flujo-de-trabajo-con-git)

## Instalación

1. Clona el repositorio:

   ```bash
   git clone https://github.com/USUARIO/NOMBRE-REPOSITORIO.git
   ```

2. Entra en la carpeta del proyecto:

   ```bash
   cd NOMBRE-REPOSITORIO
   ```

3. Abre `index.html` en tu navegador (no requiere ninguna dependencia).

## Estructura

```text
.
├── .gitignore    # Ficheros y carpetas excluidos del repositorio (.vscode, etc.)
├── index.html    # Página principal
└── README.md     # Documentación del proyecto
```

## Mejoras implementadas

- [x] **Menú de navegación** con enlaces internos (`#inicio`, `#sobre-mi`, `#contacto`) — rama `feature/menu`.
- [x] **Footer** con enlaces a redes sociales (solo texto) — rama `feature/footer`.

## Flujo de trabajo con Git

Cada mejora se desarrolló en una rama independiente (`feature/...`), se subió a GitHub y se fusionó en `main` mediante un Pull Request.
