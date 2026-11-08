# fastfetch-nge-config

[![fastfetch](https://img.shields.io/badge/fastfetch-2.x-blue?style=for-the-badge)](https://github.com/fastfetch-cli/fastfetch)
[![JSONC](https://img.shields.io/badge/config-jsonc-yellow?style=for-the-badge)](https://github.com/fastfetch-cli/fastfetch)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

Configuración de **fastfetch** con temática **Neon Genesis Evangelion** — HUD de NERV, paleta Unit-01 + NERV, etiquetas en japonés e inglés.

## Vista previa

Banner tipo HUD de NERV con módulos de sistema organizados en secciones: **PILOT**, **SYSTEM**, **HARDWARE** y **EXTRAS**, con paleta de colores, barras personalizadas y módulos custom (`SYNC`, `PALETTE`).

## Instalación

```bash
git clone https://github.com/FakuMK/NGE-fastfetch.git
cd fastfetch-nge-config
mkdir -p ~/.config/fastfetch
cp nge.jsonc ~/.config/fastfetch/config.jsonc
fastfetch
```

O directamente, sin instalar:

```bash
fastfetch --config nge.jsonc
```

## Módulos

| Sección | Módulos |
|---------|---------|
| **PILOT** | User@Host |
| **SYSTEM** | OS, Kernel, Uptime, Packages, Shell, WM, Terminal |
| **HARDWARE** | CPU, GPU, RAM, Disk, Battery, Display |
| **EXTRAS** | Date, Loadavg, Processes, Sync, Palette |

## Personalización

Edita `nge.jsonc` para cambiar colores, módulos o el banner ASCII. La configuración usa el [esquema oficial de fastfetch](https://github.com/fastfetch-cli/fastfetch/raw/dev/doc/json_schema.json).

## Requisitos

- [fastfetch](https://github.com/fastfetch-cli/fastfetch) ≥ 2.70

Hecho con ❤️ por facu
