# Variables CSS principales de bravuraysabor.cl

Este archivo documenta y preserva las variables CSS definidas en el sitio [bravuraysabor.cl](https://bravuraysabor.cl/) (ver snapshot en [Wayback Machine](https://web.archive.org/web/20250603170905/https://bravuraysabor.cl/)), útiles para mantener consistencia visual en restauraciones, migraciones o rediseños.

---

## Variables generales

```css
:root {
    --tooltip-text-color: white;
    --tooltip-background-color: black;
    --tooltip-margin: 30px;
    --tooltip-arrow-size: 6px;

    --cookie-banner-primary-color: #fff;
    --cookie-banner-secondary-color: #000;
    --cookie-banner-font-family: HelveticaNeue, Helvetica Neue, helvetica, Sans-Serif;
    --cookie-banner-font-size: 14px;

    --swiper-theme-color: #007aff;

    --one-unit: 1vw;
    --section-max-width: 9999px;
    --spx-stopper-max: 9999px;
    --spx-stopper-min: 0px;
}
```

## Paleta de colores y estilos extendida

```css
:root, :host, .spxThemeOverride, .max-width-container {
    --color_0: 255, 255, 255;
    --color_1: 255, 255, 255;
    --color_2: 0, 0, 0;
    --color_3: 237, 28, 36;
    --color_4: 0, 136, 203;
    --color_5: 255, 203, 5;
    --color_6: 114, 114, 114;
    --color_7: 176, 176, 176;
    --color_8: 255, 255, 255;
    --color_9: 114, 114, 114;
    --color_10: 176, 176, 176;
    --color_11: 0, 0, 0;
    --color_12: 64, 64, 64;
    --color_13: 128, 128, 128;
    --color_14: 255, 255, 255;
    --color_15: 255, 255, 255;
    --color_16: 89, 58, 11;
    --color_17: 173, 112, 21;
    --color_18: 230, 199, 235;
    --color_19: 232, 166, 67;
    --color_20: 254, 96, 47;
    /* ...continúa según la lista original... */
}
```

## Estilos para botones y elementos de UI

```css
:root {
    --wst-button-color-fill-primary: rgb(var(--color_48));
    --wst-button-color-border-primary: rgb(var(--color_49));
    --wst-button-color-text-primary: rgb(var(--color_50));
    /* ...y el resto de variables personalizadas de botones y texto... */
}
```

## Estilos globales

```css
body, html {
    height: 100%;
    background: transparent;
    border: 0;
    margin: 0;
    outline: 0;
    padding: 0;
    vertical-align: baseline;
}
```

---

> **Referencia:** Estas variables representan la identidad visual y configuración base de bravuraysabor.cl. Úsalas para mantener consistencia al restaurar, migrar o recrear el sitio web.