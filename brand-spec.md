# Charléa — Brand Spec (Nicole & Rodrigo Wedding) · v2 champagne/blanco/dorado

Paleta actual (pedida por el cliente): champagne, blanco y dorado. Tipografías sin cambios.

Sistema observado del mockup `image.png` + brief. Una sola exclamación visual: tipografía script + serif monumental sobre papel crema.

## Tokens (`:root` — usar verbatim)

```css
:root{
  --bg: oklch(0.94 0.025 88);        /* pearl crema de página */
  --surface: oklch(0.97 0.018 90);   /* papel tarjeta */
  --fg: oklch(0.24 0.02 75);         /* ink tinta cálida */
  --ink: oklch(0.24 0.02 75);
  --pearl: oklch(0.94 0.025 88);
  --muted: oklch(0.55 0.03 80);      /* texto secundario */
  --border: oklch(0.86 0.03 85);     /* línea fina divisoria */
  --accent: oklch(0.60 0.06 135);    /* sage salvia */
  --sage: oklch(0.60 0.06 135);
  --sage-deep: oklch(0.45 0.05 135);
  --gold: oklch(0.72 0.08 85);
}
```

HSL de respaldo: `--pearl:#F4EEE3; --surface:#FBF8F1; --ink:#211D17; --muted:#7C7466; --border:#E4DAC6; --sage:#7D8B6F; --sage-deep:#5C6650`.

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
