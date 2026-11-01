# Football Tracker — Wear OS (inicio)

Este repositorio contiene una **primera versión de prueba** de Football Tracker para relojes con Wear OS.

## Qué incluye
- Contador manual de goles, remates, pases y regates.
- Interfaz básica con botones táctiles.
- Proyecto Android nativo en Kotlin y Compose para Wear OS.

## Qué todavía no incluye
- No detecta automáticamente goles, pases ni regates.
- No mide todavía distancia, velocidad ni frecuencia cardíaca.
- Los contadores se reinician al cerrar la aplicación.
- No es compatible automáticamente con relojes de sistema propietario que no usen Wear OS.

## Requisitos para compilar
- Android Studio en una computadora.
- Android SDK y herramientas de compilación compatibles.
- Un reloj Wear OS o emulador para probar.

## Abrir y compilar
1. Descarga o clona este repositorio.
2. Abre la carpeta `football_tracker_wear` desde Android Studio.
3. Espera a que Gradle termine la sincronización.
4. Ejecuta la app en un emulador Wear OS o en un reloj conectado para depuración.

La instalación directa en un reloj depende del modelo y de su versión de Wear OS. Subir el proyecto a GitHub **no instala** la app en el reloj.

## Estructura
- `app/src/main/java/.../MainActivity.kt`: pantalla principal.
- `app/src/main/AndroidManifest.xml`: configuración de la app.
- `app/build.gradle.kts`: dependencias y configuración Android.
