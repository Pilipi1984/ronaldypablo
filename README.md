# Web de Ronald y Pablo (Ciudad Real)

Landing page estática: no necesita servidor ni base de datos. Todo es gratuito.

## Contenido

- `index.html`: la página completa (diseño, textos y código).
- `fotos/`: carpeta para las fotos del antes y después.

## Publicarla gratis con GitHub Pages

1. Crea una cuenta en https://github.com (gratis).
2. Pulsa **New repository**, ponle un nombre (por ejemplo `ronaldypablo`) y márcalo como **Public**.
3. Pulsa **uploading an existing file** y sube `index.html` y la carpeta `fotos`.
4. Ve a **Settings > Pages**. En **Source** elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`. Guarda.
5. En uno o dos minutos la web estará en `https://TU-USUARIO.github.io/ronaldypablo/`.

## Añadir un trabajo a la galería

1. Haz las fotos del antes y del después desde el mismo ángulo.
2. Redúcelas gratis en https://squoosh.app (formato JPG, ancho de unos 1200 px) para que la web cargue rápido.
3. Sube las dos fotos a la carpeta `fotos/` del repositorio.
4. Abre `index.html` en GitHub (icono del lápiz) y busca la lista `TRABAJOS`. Copia una línea y cambia los textos y los nombres de las fotos:

```js
{titulo:'Reforma de baño', detalle:'Plato de ducha y alicatado nuevo',
 antes:'fotos/bano-2-antes.jpg', despues:'fotos/bano-2-despues.jpg'},
```

5. Pon los trabajos nuevos al principio de la lista para que se vean primero. Guarda con **Commit changes**.

Los 4 trabajos que vienen de serie son de ejemplo: bórralos o sustitúyelos por los reales. Mientras una foto no exista, la página muestra una imagen de relleno.

## Datos que hay que revisar en `index.html`

- Horario del pie de página (ahora: lunes a viernes, 8:00–19:00).
- Textos de la sección "Lo que te prometemos" y de las preguntas frecuentes: deben reflejar lo que Ronald y Pablo cumplen de verdad.
- Teléfono (676 51 93 10): aparece en la cabecera, el pie y el botón de WhatsApp.

## Para que os encuentren en Ciudad Real

- Crea gratis la ficha de **Google Business Profile** con el teléfono y la zona de trabajo.
- Añade la dirección de la web a esa ficha.
- Pide a los clientes satisfechos que dejen su opinión en Google.
