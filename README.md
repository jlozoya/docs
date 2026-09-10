# Docs

Public documentation and legal pages for browser extensions and apps.

Publicado con GitHub Pages en **<https://jlozoya.github.io/docs/>**. Las
plataformas de revisión (Meta, Google, Chrome Web Store) rechazan los enlaces
`blob` de github.com, así que declara siempre las URLs de Pages, no las del
repositorio.

## Páginas legales

Genéricas: aplican a todas las aplicaciones salvo que una indique lo contrario.

| Documento | URL a declarar |
|---|---|
| [Aviso de Privacidad](./lozoya/privacy.md) | `https://jlozoya.github.io/docs/lozoya/privacy.html` |
| [Términos y Condiciones](./lozoya/terms.md) | `https://jlozoya.github.io/docs/lozoya/terms.html` |
| [Eliminación de datos](./lozoya/data-deletion.md) | `https://jlozoya.github.io/docs/lozoya/data-deletion.html` |

## Por aplicación

| Aplicación | Documento |
|---|---|
| Screen Recorder | [Privacy Policy](./screen-recorder/privacy.md) |

## Cómo añadir una página

Los archivos `.md` necesitan front matter para que Jekyll los convierta a HTML:

```yaml
---
layout: default
title: "Título de la página"
---
```

Sin él, Jekyll copia el archivo tal cual y la URL `.html` no existe.
