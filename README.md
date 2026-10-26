# Portafolio · Rolando Álvarez

Sitio estático (HTML y CSS, sin compilar) con mi perfil y dos casos de proyecto:

| Página | Contenido |
|---|---|
| `index.html` | Portada: perfil, proyectos, experiencia, habilidades y contacto |
| `proyectos/enorden.html` | EnOrden · gestión para iglesias (enordenapp.cl) |
| `proyectos/xv-launcher.html` | XV Launcher · launcher Android para la radio de mi Subaru XV |
| `assets/estilo.css` | Estilos compartidos (modo claro y oscuro automático) |
| `assets/img/` | Capturas de cada proyecto |

## Verlo en el computador

Abre `index.html` con doble clic.

## Publicarlo en GitHub Pages

1. Crea un repositorio en GitHub llamado **`TU-USUARIO.github.io`** (con tu usuario exacto).
   Así la dirección queda como `https://TU-USUARIO.github.io`.
2. Sube **todo el contenido de esta carpeta** a la raíz del repositorio, incluido el archivo
   `.nojekyll`. Puedes arrastrar los archivos en la web de GitHub (*Add file → Upload files*) o usar Git:
   ```bash
   git init
   git add .
   git commit -m "Portafolio"
   git branch -M main
   git remote add origin https://github.com/TU-USUARIO/TU-USUARIO.github.io.git
   git push -u origin main
   ```
3. En el repositorio: **Settings → Pages → Build and deployment**: *Source* = **Deploy from a branch**,
   *Branch* = **main** y carpeta **/ (root)**. Guarda.
4. Espera uno o dos minutos y abre `https://TU-USUARIO.github.io`.

> Si prefieres otro nombre de repositorio (por ejemplo `portafolio`), la dirección será
> `https://TU-USUARIO.github.io/portafolio/`. Los enlaces son relativos, así que funciona igual.

## Antes de publicar

- En `index.html`, sección **Contacto**, quita el comentario y completa tus enlaces de GitHub y LinkedIn.
- El sitio no incluye datos personales sensibles del CV (RUT, dirección, previsión). Mantenlo así.
