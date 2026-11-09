# Packs de Bedrock (Geyser)

Todos los packs de Bedrock se sirven por CDN (jsDelivr sobre esta rama, URL fijada al commit) desde
`resource-pack-urls` del `config.yml` del Geyser del proxy (Proxy-bedrock 45d07dcb). La carpeta local `/packs` del proxy
ya NO debe tener estos packs (mismo UUID dos veces = conflicto).

- Formato: `.zip` (jsDelivr sirve `.mcpack` como `application/octet-stream` y Bedrock/Geyser solo aceptan `application/zip`).
- Para cambiar un pack: subir la versión del manifest, reemplazar el `.zip` aquí, commit + push, poner el nuevo
  `@<commit>` en su URL de `resource-pack-urls` y reiniciar Geyser (`geyser stop`, el panel lo levanta).

URL: `https://cdn.jsdelivr.net/gh/lcaballerot/minetoy-packs@<commit>/bedrock/<pack>.zip`

| pack | bytes |
|---|---|
| GeyserDisplayEntityPack.zip | 40440 |
| caballero.zip | 1628245 |
| minetoy_cannabis.zip | 3851584 |
| minetoy_caramelos.zip | 55944 |
| minetoy_cielo_spawn.zip | 12519 |
| minetoy_colocon.zip | 206478 |
| minetoy_dj.zip | 6289005 |
| minetoy_emojis.zip | 6288 |
| minetoy_emotes.zip | 261249 |
| minetoy_flyorb.zip | 85181 |
| minetoy_formularios.zip | 75018 |
| minetoy_hex.zip | 69369 |
| minetoy_iconos.zip | 37090 |
| minetoy_jefes.zip | 6555566 |
| minetoy_letra.zip | 41878 |
| minetoy_mte.zip | 94426 |
| minetoy_musica_halloween.zip | 2699165 |
| minetoy_parca.zip | 10778805 |
| minetoy_protecciones.zip | 8230 |
| minetoy_radio.zip | 764081 |
| minetoy_sombreros.zip | 115377 |
| minetoy_sonidos.zip | 81757 |
| minetoy_staff.zip | 150365 |
| minetoy_tunicas.zip | 11024 |
| minetoy_vehiculos.zip | 958684 |
| minetoy_versalitas.zip | 17899 |
| minetoy_zombis.zip | 1079662 |
