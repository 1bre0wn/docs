# Instrucciones del proyecto de documentación

## Sobre este proyecto

- Documentación de **ConcienciaCiber**, la plataforma de concienciación en ciberseguridad de Legitec (repo de la app: `1bre0wn/whiteshark`).
- Sitio construido con [Mintlify](https://mintlify.com): páginas MDX con frontmatter YAML, navegación en `docs.json`.
- `mint dev` para previsualizar en local; `mint broken-links` para comprobar enlaces antes de subir.

## Terminología

- La marca es **ConcienciaCiber** (C mayúscula en "Ciber"). Nunca "Concienciaciber" ni "WhiteShark" (nombre interno antiguo, no usar de cara al cliente).
- **Organización** o **tenant** para cada empresa cliente; **destinatarios** para los empleados que reciben campañas; **alumnos** cuando se habla del portal de formación; **usuarios** solo para quienes acceden al panel de administración.
- **Simulacros de phishing** (no "ataques"); **campañas de formación**; **portal del alumno**.
- El público de esta documentación son los **clientes** (administradores de organización), salvo la página de superadmin.

## Estilo

- Español, voz activa y segunda persona ("tú").
- Frases concisas: una idea por frase.
- Negrita para elementos de la interfaz: pulsa **Guardar**.
- Formato de código para comandos, rutas y nombres de fichero.
- Componentes Mintlify preferidos: `<Steps>` para procesos, `<CardGroup>` para catálogos, `<AccordionGroup>` para FAQs, `<Tip>/<Note>/<Warning>` para avisos.

## Límites de contenido

- No documentar detalles internos de infraestructura (Azure, GoPhish, colas, base de datos) ni credenciales/IPs concretas: para eso está la documentación operativa del repo de la app.
- Los dominios e IPs de envío de simulaciones se facilitan por soporte, no se publican aquí.
- La página `manual/superadmin.mdx` describe la vista solo a nivel funcional; la operativa interna de Legitec no va en esta documentación pública.
