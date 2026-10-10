# Charléa — Brand Spec (Nicole & Rodrigo · Jardín) · v3 olivo/blanco/dorado

Paleta actual (pedida por el cliente): verde olivo, blanco y dorado, estilo rústico jardín. Tipografías sin cambios.

Sistema observado del mockup `image.png` + brief. Una sola exclamación visual: tipografía script + serif monumental sobre papel crema.

## Tokens (`:root` — usar verbatim)

```css
:root{
  --bg: oklch(0.94 0.02 100);        /* perla neutra de página */
  --surface: oklch(0.995 0.005 95);  /* papel tarjeta blanco */
  --fg: oklch(0.27 0.03 75);         /* ink tinta cálida */
  --ink: oklch(0.27 0.03 75);
  --pearl: oklch(0.94 0.02 100);
  --muted: oklch(0.55 0.03 110);     /* texto secundario oliva gris */
  --border: oklch(0.87 0.03 95);     /* línea fina divisoria */
  --accent: oklch(0.62 0.07 120);    /* olivo */
  --sage: oklch(0.62 0.07 120);
  --sage-deep: oklch(0.48 0.07 120); /* olivo profundo (botones) */
  --gold: oklch(0.65 0.12 85);       /* dorado (corazones, acentos) */
}
```

Hex en uso: `--pearl:#F4F1E4; --surface:#FFFDF8; --ink:#2B241A; --muted:#7C7C5F; --border:#E2D9BF; --sage:#B98A2F; --sage-deep:#5C6B3C; hover:#46532C`.

## Tipografías

- Display: `"Cormorant Garamond","Playfair Display",Georgia,serif` — títulos en mayúsculas con tracking amplio.
- Script: `"Pinyon Script","Great Vibes",cursive` — solo para `our story / the / kindly / and / with love, / we can't wait`.
- Body: `"Montserrat","DM Sans",system-ui,sans-serif` — 11–13px, uppercase con letter-spacing en kickers y etiquetas.

## Reglas visuales (5)

1. Tarjeta papel redondeada (22–26px) sobre fondo perla; sombra suave, sin bordes duros.
2. Jerarquía: script pequeño arriba + serif grande abajo (ej. *the* / DETAILS).
3. Líneas finas de 1px (`--border`) como divisores y eje de timeline con punto sólido.
4. Iconos de línea fina sage-deep, 1.25px, nunca sólidos ni emoji.
5. Fotografía cálida dorada; bordes "torn paper" con `clip-path` poligonal en transiciones foto→papel.
