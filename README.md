# Borrador · CAI (Cuestionario de Adaptación Infantojuvenil)

Borrador pedido por Rosario (vía Doña Clotilde) el 03/11/2026. **Solo staging**: https://borrador-cai.2-31-95-201.sslip.io (noindex). Sin dominio real ni DNS: eso solo con el OK de Joaquín.

- Diseño = borrador-bap (Inter, `.sec`/`.sec-alt`, botones, tarjetas con filete terracota, header sticky, pie #1f2328, cookies `src/cookies.js`, banner Flash y chat de Ofelia).
- Estructura de la home = socioemociograma.com (sin FAQ). Copy literal del brief de Rosario.
- Multipágina con Vite (`vite.config.js`): `index.html` + `<ruta>/index.html`. Enlaces siempre con barra final (`/que-es/`); la home redirige `/que-es` → `/que-es/`.
- Subpáginas placeholder con breadcrumbs: /que-es/, /aplicacion/, /indicadores/, /informes/, /documentacion/, /videos/, /preguntas-frecuentes/, /infografia/, /tour-guiado/.

## Pendientes
- CTA de Ofelia `cai` (slug provisional; hoy da 404 hasta que Ofelia lo dé de alta).
- Fotos (hero 4:3), logo ICCE y logo oficial del CAI (ahora icono SVG de las pruebas BAP + sigla).
- GA4 (`GA4_ID` placeholder en `src/main.js`; en *.sslip.io no se carga nunca).
- URL de «Solicitar información» y de «Documentación de la herramienta» (docs.habilmind.com); contenido de las subpáginas.

```
npm ci && npm run dev     # local
npm run build             # dist/
```
