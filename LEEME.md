# Smoky Producción — Landing

Web de la productora de eventos. Un solo archivo `index.html` (HTML/CSS/JS, sin build).

**En vivo:** https://www.smokyproduccion.cl

## Estructura
```
smoky-produccion/
├── index.html      ← la web completa
├── favicon.png     ← ícono de la pestaña
├── og-image.jpg    ← vista previa al compartir el link
├── robots.txt      ← permite que Google la indexe
├── sitemap.xml     ← le dice a Google qué páginas hay
├── galeria/        ← fotos generales (img_NN.jpg)
├── eventos/        ← fotos por evento (ev_<evento>_NN.jpg)
├── logos/          ← logos de los clientes
└── LEEME.md        ← este archivo
```

## Cómo trabajar en ella
1. Abrí VS Code → Archivo → Abrir carpeta → elegí `smoky-produccion`.
2. Terminal integrada: `Ctrl + Ñ`.
3. Escribí `claude` y Enter.
4. Pedile los cambios hablando normal, por ejemplo:
   - "agregá un evento nuevo a la sección Experiencias"
   - "cambiá el número de WhatsApp del contacto"

## Ver la web mientras trabajás
Instalá la extensión **Live Server** en VS Code, click derecho sobre
`index.html` → "Open with Live Server". Se refresca sola al guardar.

## Publicar los cambios
```
git add -A && git commit -m "lo que cambiaste" && git push
```
Vercel la actualiza sola en menos de un minuto.

## Al agregar fotos o videos
Achicarlos ANTES de guardarlos en git (una foto de iPhone pesa 3-5 MB y para
web sobra con 1920px de ancho). Si no, el repositorio se vuelve pesado y no
hay forma de aligerarlo después.

## Fotos que hoy no se usan
Estas están en `galeria/` y `eventos/` pero no aparecen en el sitio:
`img_01, img_03, img_04, img_05, img_06, img_07`,
`ev_anonuevo_mandarin_03, ev_anonuevo_mandarin_04`,
`ev_monti_anonuevo_01, ev_monti_anonuevo_02`,
`ev_vendimia_monti_01, ev_vendimia_monti_05`.
Se dejaron por si sirven más adelante.
