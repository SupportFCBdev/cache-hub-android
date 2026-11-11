# Cache Hub para Android

APK de la app Cache Hub para las tablets de la tienda Caché Perfumes.

Este repositorio solo guarda las versiones publicadas (Releases). El código de la app no está aquí.

## Descargar

La última versión está en [Releases → Latest](https://github.com/SupportFCBdev/cache-hub-android/releases/latest): es el archivo `cache-hub-<versión>.apk`.

Las tablets se actualizan solas: la app lee el `version.json` de la última versión y ofrece instalarla encima, sin perder la sesión. Las betas (etiquetas `android-vX.Y.Z-beta.N`) salen como prerelease y la app no las ofrece; se instalan a mano para probarlas.

## No subir nada a mano

Cada versión la publica GitHub Actions: compila, firma con la clave de la empresa, comprueba la firma y sube el APK con su `version.json`. Un APK subido a mano y firmado con otra clave no se instala encima del anterior: habría que desinstalar la app en cada tablet.
