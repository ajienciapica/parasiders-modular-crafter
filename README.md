# PARASIDERS Modular Sprite Crafter

Generador web estático para GitHub Pages. No necesita backend, dependencias ni compilación.

## Probar localmente
Abre `index.html` en Chrome/Firefox. La aplicación compone una hoja PNG transparente de 128 × 192 px, con 4 columnas de fotogramas y 4 filas de direcciones. El dibujo se renderiza sin suavizado.

## Publicar en GitHub Pages
1. Crea un repositorio público en GitHub, por ejemplo `parasiders-modular-crafter`.
2. Descomprime este ZIP y sube **el contenido** de esta carpeta (index.html y assets/) a la raíz del repositorio.
3. En el repositorio abre **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Elige la rama `main` y la carpeta `/ (root)`, pulsa **Save**.
6. Espera a que termine el despliegue. La URL será `https://TU-USUARIO.github.io/parasiders-modular-crafter/`.

## Importante sobre RPG Maker XP
- La exportación actual es 128 × 192 px: 4 frames por fila y 4 filas de dirección.
- Los nombres de filas son Frente, Izquierda, Derecha y Espalda; comprueba el orden requerido por tu proyecto antes de usarla en producción.
- Es una primera biblioteca modular dibujada por código para validar la composición. Todavía requiere trabajo de pixel art manual para alcanzar la fidelidad exacta de las referencias, y ampliar los patrones de animación por dirección.
- Los sprites de referencia originales se incluyen en `assets/` y no se modifican.

## Siguiente etapa recomendada
Reemplazar los patrones geométricos iniciales por piezas de 16 × 24 píxeles dibujadas manualmente en una cuadrícula común, con poses específicas por dirección y fotograma; después ampliar biblioteca (cabezas, torso, piernas, capas, armas y accesorios).
