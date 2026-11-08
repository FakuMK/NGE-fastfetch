# fastfetch-nge-config

[![fastfetch](https://img.shields.io/badge/fastfetch-2.x-blue?style=for-the-badge)](https://github.com/fastfetch-cli/fastfetch)
[![JSONC](https://img.shields.io/badge/config-jsonc-yellow?style=for-the-badge)](https://github.com/fastfetch-cli/fastfetch)

Configuración de **fastfetch** con temática **Neon Genesis Evangelion** — HUD de NERV, paleta Unit-01 + NERV, etiquetas en japonés e inglés.

## Vista previa

Banner tipo HUD de NERV con módulos de sistema organizados en secciones: **PILOT**, **SYSTEM**, **HARDWARE** y **EXTRAS**, con paleta de colores, barras personalizadas y módulos custom (`SYNC`, `PALETTE`).

## Instalación

Descarga el paquete desde los [releases](https://github.com/FakuMK/NGE-fastfetch/releases) y extraelo:

```bash
# Descargar el paquete
wget https://github.com/FakuMK/NGE-fastfetch/releases/latest/download/fastfetch-nge-config.tar.gz

# Extraer
tar xzf fastfetch-nge-config.tar.gz

# Instalar la configuración
mkdir -p ~/.config/fastfetch
cp nge.jsonc ~/.config/fastfetch/config.jsonc

# Ejecutar
fastfetch
```

O directamente, sin instalar:

```bash
tar xzf fastfetch-nge-config.tar.gz
fastfetch --config nge.jsonc
```

El archivo `fastfetch-nge-config.tar.gz` ya contiene `nge.jsonc` (la configuración) y un `README.md` con instrucciones de uso local.

## Módulos

| Sección | Módulos |
|---------|---------|
| **PILOT** | User@Host |
| **SYSTEM** | OS, Kernel, Uptime, Packages, Shell, WM, Terminal |
| **HARDWARE** | CPU, GPU, RAM, Disk, Battery, Display |
| **EXTRAS** | Date, Loadavg, Processes, Sync, Palette |

## Personalización

Edita `nge.jsonc` para cambiar colores, módulos o el banner ASCII. La configuración usa el [esquema oficial de fastfetch](https://github.com/fastfetch-cli/fastfetch/raw/dev/doc/json_schema.json).

## Screenshots

<img width="952" height="1030" alt="fast-evangelion" src="https://github.com/user-attachments/assets/7339e354-22df-4a92-a939-227c2cc66dac" />


## Requisitos

- [fastfetch](https://github.com/fastfetch-cli/fastfetch) ≥ 2.70

Hecho con ❤️ por facu
