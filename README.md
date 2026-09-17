# Barra de Patilla 2

Banner 980×200, dos especiales de investigación de La Patilla lado a lado
(salud pública / derechos humanos). Hermano de **Barra de Patilla 1** (el
reloj flip de la mesa de diálogo, en `~/proyectos/reloj-flip`): mismo ADN
visual, mismo flujo de despliegue (GitHub Pages + iframe al webmaster).

- Banner fijo 980×200px, escalado responsivo vía `container-type: inline-size`
  (sin `transform: scale()` — a diferencia de Barra 1, acá hay titulares de
  texto real con `clamp()` sobre piso legible, no un mecanismo numérico).
- Dos mitades clickeables (490×200 c/u), cada una a su propio especial, con
  Ken Burns sutil en el fondo (respeta `prefers-reduced-motion`).
- Línea SVG propia cruzando los 980px: electrocardiograma (salud) que se
  convierte en alambre de púas (cárceles).
- Crédito "Desarrollado por" + logo LaPatilla, esquina superior derecha.
- Estilo aprobado por Rory, iterado en artifact de Claude (v17, 2026-09-16):
  https://claude.ai/artifact/KT2FyjLA2vWfBJhP4q294W
- Actualización manual del contenido (editar, commit, push), igual que Barra 1.

**Pendiente:** faltan 4 assets de imagen en `img/` (`hospitales.jpg`,
`ruinas-icon.png`, `horror-icon-duotone.png`, `helicoide.png`) — el tool de
Artifact de Claude devolvió error (HTTP 403) al intentar bajarlos de los
archivos publicados del artifact durante esta promoción. Solo `lp-logo-light.png`
se copió (ya existía local desde Barra 1). Hay que reintentar la descarga y
copiarlos a `img/` antes de embeber esto en producción.
