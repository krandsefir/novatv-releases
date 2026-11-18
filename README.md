# NovaTV — Versiones publicadas y Releases

Este repositorio **solo aloja las versiones compiladas y releases de NovaTV** (Windows x64, Linux y Android APK). **No contiene código fuente.**

NovaTV lo consulta automáticamente sin necesidad de autenticación para comprobar si hay actualizaciones disponibles:
- API pública de GitHub: https://api.github.com/repos/krandsefir/novatv-releases/releases/latest

## Contenido de cada versión (X.Y.Z)

| Archivo | Plataforma | Descripción |
|---|---|---|
| 
ovatv-windows-x64.zip | Windows 10/11 x64 | Ejecutable 
ovatv.exe y dependencias (libmpv, vcpkg DLLs). |
| 
ovatv-linux-x64.tar.gz | Linux x64 | Binario de escritorio y modo --mcp. |
| 
ovatv-debug.apk | Android 7+ (API 24+) | App móvil nativa con Media3 / ExoPlayer y libnovatv_jni.so. |
| ules.json | Todas | Configuración de dominios dinámicos y reglas de canales / servidores. |

---

*Nota: El código fuente del proyecto se mantiene de forma privada en krandsefir/novatv.*
