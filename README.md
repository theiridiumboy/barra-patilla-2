# Barra de Patilla 2

Sandbox pa widget nuevo, mismas dimensiones que **Barra de Patilla 1** (el reloj
flip de la mesa de diálogo, en `~/proyectos/reloj-flip`).

- Banner fijo 980×200px, escalado proporcional vía `container-type: inline-size`
  + `transform: scale(calc(100cqw / 980px))` — misma técnica que Barra 1, verificada
  en producción (1200/600/375/320px sin overflow).
- Archivo único autocontenido (`index.html`), pensado pa embeber tal cual en
  LaPatilla.com igual que el reloj.
- Assets de logo (`lp-logo*.png`) copiados de Barra 1 por si el widget necesita
  el crédito "Desarrollado por".
- Contenido: sin definir todavía. `index.html` trae solo el marco 980×200 vacío.
