# Huella

Web oficial de Huella, la app de cuidado de perros para dueños en España. Es un sitio estático pensado para GitHub Pages.

## Páginas

| Archivo | Contenido |
|---------|-----------|
| `index.html` | Portada: logo, los dos perros, funciones, prueba cerrada y Huella Plus |
| `images/` | Logo de la app y la ilustración del yorkshire y el teckel |
| `privacidad.html` | Política de privacidad |
| `terminos.html` | Términos de uso |
| `seguridad-infantil.html` | Estándares de seguridad infantil |
| `eliminar-datos.html` | Cómo borrar o solicitar la eliminación de datos |
| `tag.html` | Ficha pública de emergencia (la abre el QR de la app) |

## Cómo verla en local

Desde esta carpeta:

```bash
python3 -m http.server 8000
```

Abre [http://127.0.0.1:8000/](http://127.0.0.1:8000/). No hace falta instalar dependencias.

## Publicación

La web vive en GitHub Pages, en la rama `main`:

https://silviojuan-bit.github.io/huella-legal/

Al fusionar cambios en `main`, esa misma dirección muestra la portada nueva. Las páginas legales no cambian de ruta, así que los enlaces de Google Play siguen valiendo.
