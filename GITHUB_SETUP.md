# Guía de Setup — Repositorio GitHub

Este documento explica cómo se creó y cómo mantener este repositorio.

## Estructura del repositorio

```
juanmotato/
├── README.md               # CV principal (perfil, proyectos, educación, skills)
├── portfolio.html           # Portafolio interactivo (HTML standalone)
├── CINORA_CASE_STUDY.md     # Caso de estudio detallado del proyecto Cinora
├── GITHUB_SETUP.md          # Este archivo
├── CV_GITHUB_LINKS.md       # Links listos para compartir
├── .gitignore
└── LICENSE                  # MIT
```

## Cómo se creó

1. Autenticación con GitHub vía [GitHub CLI](https://cli.github.com/) (`gh auth login`) — sin exponer tokens en texto plano.
2. Repositorio creado con `gh repo create juanmotato --public`.
3. Archivos preparados localmente, commit inicial y push a `main`.

## Cómo actualizar el contenido

```bash
# Editar los archivos que quieras (README.md, portfolio.html, etc.)
git add .
git commit -m "Actualiza CV/portafolio"
git push
```

## Cómo publicar el portafolio como sitio web (opcional)

**GitHub Pages:**
1. Ve a Settings → Pages en el repositorio.
2. En "Source", selecciona la rama `main` y carpeta `/ (root)`.
3. Guarda. El sitio quedará disponible en `https://sebasmotato8-rgb.github.io/juanmotato/portfolio.html`.

## Notas de seguridad

- El token de GitHub nunca se pegó en esta conversación ni se guardó en archivos: la autenticación la maneja `gh` CLI localmente.
- El archivo original `JuanSebastianMotato_Adso_SENA_2026_updated.doc` (formulario oficial SENA con cédula, teléfono, dirección y fecha de nacimiento) **no se incluyó** en este repositorio público por ser información personal sensible.
