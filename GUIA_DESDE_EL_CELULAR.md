# Clima Seguro — compilar desde el celular

Este proyecto incluye un flujo de GitHub Actions que compila automáticamente el APK.

1. Crea/inicia sesión en una cuenta de GitHub.
2. Crea un repositorio nuevo (puede ser privado).
3. Sube todos los archivos y carpetas de este proyecto, incluyendo `.github/workflows/build-apk.yml`.
4. Abre la pestaña **Actions** del repositorio.
5. Entra en **Compilar Clima Seguro APK** y pulsa **Run workflow** si aparece.
6. Espera a que termine el trabajo con marca verde.
7. Abre la ejecución terminada y baja el artefacto **ClimaSeguro-APK**.
8. Descomprime el artefacto y encontrarás `app-debug.apk` para instalarlo en tu Android.

No necesitas Android Studio en el celular: la compilación se realiza en GitHub Actions. El flujo usa Java 17 y Gradle 8.10.
