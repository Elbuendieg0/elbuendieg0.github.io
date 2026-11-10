# Mandala que baila

Un mandala para colorear por números. Cuando se termina de pintar con la clave de colores:

1. **Es un código QR** (25×25, tolerancia alta) que abre https://elbuendieg0.github.io
2. **Es la imagen que reconoce la realidad aumentada**: al apuntarle con la cámara aparece un personaje 3D bailando samba en el centro, con audio.

| Archivo | Qué es |
|---|---|
| `mandala-para-colorear.png` | Hoja para imprimir y colorear por números |
| `mandala-terminado.png` | Cómo queda pintado; es también la imagen objetivo |
| `targets.mind` | La imagen objetivo compilada para MindAR |
| `personaje.glb` | Modelo 3D con esqueleto y baile de Mixamo |
| `audio.m4a` | Audio que suena al aparecer el personaje |

El QR guarda el enlace en mayúsculas (`HTTPS://ELBUENDIEG0.GITHUB.IO`) para usar el modo alfanumérico del QR, que ocupa menos casillas.

La AR compara contra `mandala-terminado.png`, así que reconoce mejor el mandala cuando se pinta con la clave de colores.
