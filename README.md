# Clima Seguro 2.0

App Android educativa para consultar temperaturas reales por ciudad y acceder a avisos oficiales del SENAMHI.

## Datos
- Temperatura actual y máxima: Open-Meteo, consultada por Internet.
- Avisos meteorológicos: página oficial de SENAMHI dentro de la app.
- Ciudades incluidas: Pacasmayo, Trujillo, Chiclayo, Piura, Tumbes y Lima.

## Compilar
Abre el proyecto en Android Studio y ejecuta:
`./gradlew assembleDebug`

APK:
`app/build/outputs/apk/debug/app-debug.apk`

Nota: los avisos oficiales se muestran desde SENAMHI; no se inventan niveles de riesgo.
