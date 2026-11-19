# Cómo publicar en GitHub Pages

1. En tu repo `Reel-tuna-antes-despues` (rama `main`) sube estos 2 archivos a la RAÍZ:
   - `index.html`
   - `songs.json`
2. Tus mp3 ya están en la carpeta `canciones/`. No hace falta moverlos.
3. Activa Pages: Settings → Pages → Source: "Deploy from a branch" → Branch: `main` / carpeta `/ (root)` → Save.
4. Espera 1–2 minutos y abre: https://dretcmu.github.io/Reel-tuna-antes-despues/

## Agregar una canción nueva
1. Sube el mp3 a la carpeta `canciones/`.
2. Edita `songs.json` y agrega una línea nueva (con coma entre elementos):

    { "name": "Nombre que quieres ver", "file": "canciones/nombre-exacto-del-archivo.mp3" }

El nombre del archivo debe coincidir EXACTO (mayúsculas, tildes y espacios).
