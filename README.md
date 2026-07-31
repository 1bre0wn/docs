# Documentación de ConcienciaCiber

Documentación oficial de **ConcienciaCiber**, la plataforma de concienciación y formación en ciberseguridad de [Legitec](https://www.legitec.com). Construida con [Mintlify](https://mintlify.com).

## Estructura

- `index.mdx` — portada de la documentación.
- `primeros-pasos/` — guía rápida y catálogo de servicios.
- `manual/` — manual de usuario del panel de administración y del portal del alumno.
- `whitelisting/` — guías de entregabilidad por proveedor (M365, Google, Fortinet, Sophos, Barracuda) y configuración avanzada.
- `recursos/` — noticias y planes.
- `docs.json` — navegación y tema.
- `images/`, `logo/` — recursos gráficos.

## Desarrollo local

```bash
npm i -g mint
mint dev
```

Abre `http://localhost:3000`. Antes de subir cambios, comprueba los enlaces:

```bash
mint broken-links
```

## Publicación

Los cambios en `main` se publican automáticamente a través del panel de Mintlify conectado a este repositorio.
