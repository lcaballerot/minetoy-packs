<div align="center">

> 🇪🇸 **[Leer en español → README.md](README.md)**

# ᴍɪɴᴇᴛᴏʏ » **Packs**

**The MineToy server's resource packs, one per Minecraft version.**

[![Minecraft](https://img.shields.io/badge/minecraft-1.21%20%E2%86%92%2026.3-6eff4a?style=for-the-badge&logo=minecraft&logoColor=white)](#how-it-works)
[![Releases](https://img.shields.io/badge/downloads-releases-CDB4FF?style=for-the-badge)](https://github.com/lcaballerot/minetoy-packs/releases)

</div>

---

## What is this?

This repository only publishes the packs the server sends to each player on join. There is no need to download them
by hand: the server detects the client's version and sends the right ones.

## How it works

| Release file | Who gets it |
|---|---|
| `base-<hash>.zip` | Everyone: MineToy's own content. A **26.3** client gets only this. |
| `delta-<version>-<hash>.zip` | Only clients of that version: the Minecraft content they lack up to 26.3. |

- Each Release is tagged with a short hash of its content: same content, same tag, nothing to download again.
- The zips are deterministic: if a pack does not change, neither does its SHA-1, and the game reuses the copy it has.
- Every file's SHA-1 is listed in its Release notes.

---

<div align="center">

### Statistics

Visits to this repository

<img src="https://api.visitorbadge.io/api/visitors?path=lcaballerot%2Fminetoy-packs&label=visits&labelColor=%23333333&countColor=%23CDB4FF&style=for-the-badge&labelStyle=upper" alt="Visits">

© MineToy

</div>
