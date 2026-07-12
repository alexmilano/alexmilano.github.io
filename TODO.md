# TODO — pendientes de la v2 (para Alex)

- [ ] **Substack**: crear la publicación "Consecuencias" y reemplazar la constante `SUBSTACK_URL` en `index.html` (busca el comentario `// TODO: reemplazar con la URL real del Substack`). Hoy apunta a `alexmilano` como placeholder. Nota: el form usa redirect a `https://<url>.substack.com/subscribe?email=…` en vez del iframe embed de Substack — el embed no se puede estilizar y rompía la estética terminal; si prefieres el iframe, es un cambio pequeño.
- [ ] **Reviews del libro**: sustituir las 2 quotes marcadas como `PLACEHOLDER` en `index.html` (busca el comentario `<!-- TODO: reemplazar con reviews reales de Amazon -->`) por reviews reales de Amazon, en ES y EN.
- [ ] **Fotos de prensa en máxima resolución**: subir los originales a `/press/photos/` (ver `press/photos/README.md`) y actualizar los links `[descargar]` de `press.html`. Hoy apuntan a las versiones de `/uploads/` (~1 MB).
- [ ] **OG image**: las páginas no tienen `og:image`; elegir una foto (o la portada del libro) y añadirla a las 3 páginas para mejores previews al compartir.
