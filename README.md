# Snake · HLG Codes

Juego de la culebrita (Snake) clásico, hecho en una sola página (`index.html`) con HTML, CSS y JavaScript puro. No tiene dependencias, no usa CDN ni fuentes externas.

## Cómo jugar

Abre `index.html` en el navegador (computador o celular). Come la comida brillante para crecer y sumar puntos. Pierdes si chocas contra la pared o contra tu propia cola. Entre más comes, más rápido va la culebra.

### Controles con teclado

| Acción | Teclas |
| --- | --- |
| Moverse | Flechas o `W` `A` `S` `D` |
| Pausar / continuar | `Espacio` o `P` |
| Reiniciar | `Enter` o `R` |

### Controles en el celular

- **Deslizar** el dedo sobre el tablero hacia arriba, abajo, izquierda o derecha.
- **Cruceta (D-pad)** en pantalla, que aparece automáticamente en dispositivos táctiles.
- Botones de **Pausa** y **Reiniciar** arriba del tablero.

## Detalles

- Puntaje en vivo y **récord** guardado en el navegador (`localStorage`).
- La velocidad sube poco a poco.
- Las vueltas rápidas se guardan en cola, así que no te chocas por girar dos veces seguidas.
- Se ignoran los giros de 180°.
- Se pausa solo si cambias de pestaña.

## Publicación

Incluye `.nojekyll` para servirlo tal cual con GitHub Pages.
