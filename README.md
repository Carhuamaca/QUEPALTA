# QUE PALTA — Android 2.0

Aplicación Android para acompañar la integración social de estudiantes ingresantes con misiones progresivas, mapa de orientación, retos grupales, diario privado y progreso local.

## Generar el APK 2.0

1. Descarga el paquete `QuePalta_Android_Source_v3.zip` desde el chat.
2. Súbelo a la raíz de este repositorio, sin descomprimirlo y conservando exactamente ese nombre.
3. El workflow **Build Que Palta APK** se activará automáticamente.
4. Cuando termine correctamente, abre **Releases** y descarga el archivo `app-debug.apk` del release `quepalta-build-N`.

[Ver las compilaciones](https://github.com/Carhuamaca/QUEPALTA/actions)
[Ver los APK publicados](https://github.com/Carhuamaca/QUEPALTA/releases)

## Qué contiene la versión 2.0

- 12 misiones progresivas con XP, monedas e insignias.
- Inicio personalizado, niveles, racha y mascota con reacciones.
- Mapa esquemático de orientación de UPC Monterrico.
- Lector QR nativo mediante cámara Android.
- Diario emocional opcional y local.
- Retos colaborativos e invitaciones compartibles.
- Perfil editable, historial y exportación JSON.
- Administración local para crear y pausar misiones.
- Base SQLite local con migración desde la versión anterior.

## Límites importantes

El diario, perfil, avance, retos y misiones personalizadas se guardan localmente. Todavía no hay cuentas ni sincronización entre teléfonos. El panel de administración es local y no tiene control de acceso. El mapa es esquemático y no reemplaza el plano oficial del campus. Las misiones se registran mediante auto-reporte.

La compilación generada es un APK debug para pruebas e instalación directa; no es un paquete release firmado para Google Play.
