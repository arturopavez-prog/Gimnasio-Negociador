# Gimnasio del Negociador

App para el teléfono (PWA) con un curso de teoría de juegos aplicado a negociar con proveedores de Pavez Economat. Siete módulos: cada uno enseña un concepto en tarjetas (con lectura en voz alta), lo practica en casos con 45 segundos por respuesta y deja una misión para el mundo real. Lleva puntaje, tiempo, racha diaria y alerta si pasan dos días sin entrenar.

Es un repositorio independiente: no toca MESA CERO ni Spinning.

## Publicar en GitHub Pages
1. Crear un repositorio nuevo llamado `gimnasio-negociador`.
2. Subir todo el contenido de esta carpeta a la raíz (incluye `.github/` y `.nojekyll`), en la rama `main`.
3. El workflow copia `main` a la rama `gh-pages` en cada push.
4. Settings → Pages → Source: "Deploy from a branch" → rama `gh-pages`, carpeta `/ (root)`.
5. La dirección queda en https://arturopavez-prog.github.io/Gimnasio-Negociador/.

## Actualizar
Cambiar los archivos en `main` y subir el número de `CACHE` en `sw.js` para que el teléfono descargue la versión nueva.

## Datos
El avance se guarda solo en el teléfono (localStorage, clave `gimnasio-negociador-v1`). No se envía a ningún servidor. Usar "Guardar respaldo" antes de cambiar de celular y "Restaurar" en el nuevo.
