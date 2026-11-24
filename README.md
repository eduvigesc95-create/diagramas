# GENIUS HORMO — Sitio principal

## Estructura
- `index.html`: página principal con acceso a los dos diagramas.
- `diagramas/consulta.html`: diagrama estratégico de Consulta.
- `diagramas/whoop-muse.html`: diagrama estratégico de WHOOP / MUSE.

## Publicar en GitHub y Vercel
1. Descomprime el ZIP.
2. Sube el contenido de la carpeta `genius-hormo-web` a un repositorio de GitHub.
3. En Vercel, selecciona **Add New → Project** y conecta ese repositorio.
4. Deja la configuración por defecto para un sitio estático (sin framework ni build command).
5. Pulsa **Deploy**. Vercel publicará `index.html` como página principal.

No muevas los archivos de la carpeta `diagramas`, porque los enlaces de la página principal apuntan a esas rutas relativas.
