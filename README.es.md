# Hoja de referencia: comandos de FFmpeg · FFmpeg Cheatsheet

> 🌍 [中文](README.md) · [Português](README.pt.md)

Una **hoja de referencia de una sola página** con los comandos de FFmpeg que de verdad se usan: 28 comandos, y cada uno responde solo dos preguntas — **qué hace y un comando listo para copiar y pegar**. Transcodificación, compresión, extracción de audio, GIF, recortes, marcas de agua, streaming y procesamiento por lotes. Sin relleno.

## Para quién es

Creadores de video, desarrolladores, ingenieros de operaciones y cualquiera que haya sufrido con formatos de audio y video. Si cada vez que usas FFmpeg tienes que buscar los parámetros, esta hoja te devuelve el copiar-pegar.

## Cómo usarla

1. Ve directo a **[CHEATSHEET.md](CHEATSHEET.md)** — el cuerpo de la referencia, legible para desarrolladores de cualquier idioma.
2. Instala FFmpeg primero:
   ```bash
   brew install ffmpeg          # macOS
   sudo apt install ffmpeg     # Debian/Ubuntu
   ```
3. Cada comando se puede copiar y ejecutar tal cual; solo cambia `input.mp4` / `output.mp4` por tus archivos.

## Qué incluye

| Categoría | Contenido |
|---|---|
| 📦 Instalación | Instalación y verificación de versión y códecs |
| 🔄 Transcodificación | Cualquier formato→MP4, MP4→WebM, MKV→MP4 sin recodificar |
| 🗜️ Compresión | Compresión CRF, presets, codificación en dos pasadas |
| 🎵 Extraer audio | A MP3 / M4A, extracción sin recodificar |
| 🖼️ Video a GIF | Método de paleta en dos pasos, adiós a los GIF pixelados |
| ✂️ Recortar y unir | Recorte rápido y preciso, concatenación sin pérdidas |
| 📐 Escalar y recortar | `scale`, proporciones automáticas, `crop` |
| 🎞️ Fotogramas | Miniatura, video a secuencia de imágenes, reemplazar audio |
| 💧 Marcas de agua y subtítulos | Logo con `overlay`, subtítulos quemados, texto |
| 📡 Streaming | Plantilla de publicación RTMP |
| 🔁 Por lotes | Bucles `for` para transcodificar o extraer audio en masa |

Todos los comandos usan sintaxis real de FFmpeg, verificada parámetro por parámetro.

## Documentación oficial

- https://ffmpeg.org/documentation.html

## Contribuciones bienvenidas

¿Un comando incorrecto, una traducción mejorable o una receta mejor? Los *pull requests* son bienvenidos. Mantén el formato (qué hace / comando / etiquetas) y **verifica que el comando funcione antes de enviarlo**.

## Licencia

MIT © 2026 Guangyi Zhao. Ver [LICENSE](LICENSE).
