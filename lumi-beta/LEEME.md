# Lumi Beta — APK de prueba independiente

Es una app NUEVA (id `mx.lumi.beta`, nombre "Lumi Beta"). Se instala junto a tu Lumi actual y NO toca sus datos.
Motivo: GitHub firma cada APK con una llave de depuración distinta; Android no deja actualizar encima y obligaría a desinstalar tu Lumi (y perder datos).

1. En GitHub crea un repositorio NUEVO llamado `lumi-beta`.
2. Sube todo el contenido de esta carpeta (Add file > Upload files): www, assets, package.json, capacitor.config.json, .gitignore.
3. Crea el flujo a mano: Add file > Create new file > nombre `.github/workflows/build-apk.yml`, pega el contenido de ese archivo (está en el zip) y Commit.
4. Pestaña Actions: espera la palomita verde (8 a 12 min). Descarga LumiBeta.apk desde Releases.
5. Para pasar tus datos: en tu Lumi actual, Ajustes > Copiar respaldo; en Lumi Beta, Ajustes > Restaurar desde texto.
