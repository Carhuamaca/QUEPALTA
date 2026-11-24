# QUE PALTA — APK Android

Este repositorio genera el APK de Que Palta mediante GitHub Actions.

## Para generar el APK

1. Sube el archivo `QuePalta_Android_Source.zip` a la raíz de este repositorio.
2. El workflow **Build Que Palta APK** se ejecutará automáticamente al detectar ese archivo.
3. Cuando termine correctamente, abre la sección **Releases** del repositorio.
4. Descarga `app-debug.apk` del release más reciente.

También puedes abrir **Actions → Build Que Palta APK → Run workflow** para volver a compilarlo.

## Requisitos y alcance

- JDK 17, Android SDK API 36 y Gradle 8.13 se instalan en el runner de GitHub.
- La aplicación guarda el progreso localmente en SQLite, integra CameraX + ML Kit para leer QR y no requiere cuenta.
- El APK generado por este flujo es una compilación debug, adecuada para instalar y probar; no es una versión firmada para publicar en Google Play.
- La funcionalidad debe verificarse en un teléfono real (permisos de cámara, QR, persistencia y exportación).
