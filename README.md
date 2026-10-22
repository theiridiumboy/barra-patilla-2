# Barra de Patilla 2

Banner 980×200, tres especiales de investigación de La Patilla lado a lado
(salud pública / damnificados del terremoto / derechos humanos). Hermano de **Barra de Patilla 1** (el
reloj flip de la mesa de diálogo, en `~/proyectos/reloj-flip`): mismo ADN
visual, mismo flujo de despliegue (GitHub Pages + iframe al webmaster).

- Banner fijo 980×200px, escalado responsivo vía `container-type: inline-size`
  (sin `transform: scale()` — a diferencia de Barra 1, acá hay titulares de
  texto real con `clamp()` sobre piso legible, no un mecanismo numérico).
- Tres tarjetas clickeables (~327×200 c/u), cada una a su propio especial, con
  Ken Burns sutil en el fondo (respeta `prefers-reduced-motion`). Bajo 600px
  de ancho solo se muestra el titular. Solo el especial más nuevo (`.fresh`)
  lleva CTA en pastilla roja con pulso.
- Línea SVG propia cruzando los 980px: electrocardiograma (salud), sismógrafo
  con el doblete del 24J (terremoto) y alambre de púas (cárceles).
- Crédito "Desarrollado por" + logo LaPatilla, esquina superior derecha.
- Estilo aprobado por Rory, iterado en artifact de Claude (v17, 2026-09-16):
  https://claude.ai/artifact/KT2FyjLA2vWfBJhP4q294W
- Actualización manual del contenido (editar, commit, push), igual que Barra 1.
