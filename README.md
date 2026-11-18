# My ArQ

App web para levantar los puntos GPS de un terreno desde el celular: guarda cada esquina promediando lecturas, dibuja el terreno y calcula área y perímetro (m², varas², manzanas, cuerdas). Exporta a KML y CSV (con coordenadas UTM y GTM).

La app es `index.html`, sin dependencias ni internet para funcionar. Los archivos de iconos (`apple-touch-icon.png`, `icon-*.png`, `favicon-64.png`) y `manifest.webmanifest` deben subirse junto a ella.

## Uso

1. Publica este repositorio con Netlify (o GitHub Pages) para tener un enlace https. El GPS del navegador solo funciona con https.
2. Abre el enlace en Safari en el iPhone y acepta el permiso de ubicación (Mientras se usa, con Ubicación precisa).
3. Toca **Activar GPS**, ve a cada esquina y toca **Guardar punto**.

Para tener el icono en la pantalla de inicio: Safari › Compartir › Añadir a pantalla de inicio.

Mantén Safari abierto y la pantalla encendida mientras mides.

## Precisión

El GPS de un celular suele errar entre 3 y 10 m por punto. Sirve para estimar área y hacer un croquis. Para escrituras o trámites se necesita un levantamiento topográfico con equipo de precisión.
