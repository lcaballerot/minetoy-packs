<div align="center">

> 🇬🇧 **[Read this in English → README.en.md](README.en.md)**

# ᴍɪɴᴇᴛᴏʏ » **Packs**

**Los packs de recursos del servidor MineToy, uno por versión de Minecraft.**

[![Minecraft](https://img.shields.io/badge/minecraft-1.21%20%E2%86%92%2026.3-6eff4a?style=for-the-badge&logo=minecraft&logoColor=white)](#cómo-funciona)
[![Releases](https://img.shields.io/badge/descargas-releases-CDB4FF?style=for-the-badge)](https://github.com/lcaballerot/minetoy-packs/releases)

</div>

---

## ¿Qué es esto?

Aquí solo se publican los packs que el servidor manda a cada jugador al entrar. No hace falta bajarlos a mano: el
servidor detecta la versión del cliente y le manda lo suyo.

## Cómo funciona

| Fichero de la Release | Quién lo recibe |
|---|---|
| `base-<hash>.zip` | Todos: el contenido propio de MineToy. Un cliente **26.3** recibe solo esto. |
| `delta-<versión>-<hash>.zip` | Solo los clientes de esa versión: lo de Minecraft que les falta hasta 26.3. |

- Cada Release lleva por etiqueta un hash corto de su contenido: mismo contenido, misma etiqueta, nada que volver a bajar.
- Los zips son deterministas: si un pack no cambia, su SHA-1 tampoco y el juego reutiliza el que ya tiene.
- El SHA-1 de cada fichero está en las notas de su Release.

---

<div align="center">

### Estadísticas

Visitas a este repositorio

<img src="https://api.visitorbadge.io/api/visitors?path=lcaballerot%2Fminetoy-packs&label=visitas&labelColor=%23333333&countColor=%23CDB4FF&style=for-the-badge&labelStyle=upper" alt="Visitas">

© MineToy

</div>
