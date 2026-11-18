# ATAK BOB

> [Español](#atak-bob) · [English](#english-version)

Plataforma táctica ligera **C2 / Conciencia Situacional** para escritorio Windows (`.exe` portable) y tabletas o teléfonos Android (`.apk`), con soporte para **mapas personalizados**, **paquetes cartográficos calibrados (`.bobmap.json`)**, cuadrícula de 5 dígitos y **comunicaciones encriptadas extremo a extremo (E2EE + TLS SHA-256)** mediante host local (LAN / Tailscale / Tailscale Funnel).

---

## Capacidades incluidas en esta versión pública

- **Mapas Personalizados y Paquetes (`.bobmap.json`)**: Carga imágenes (`PNG`, `WEBP`, `JPG`) o paquetes `.bobmap.json` (con calibración afín 2D exacta y POIs integrados) desde el botón **`+ MAPAS`**, guardados localmente en el dispositivo tanto en escritorio como en Android.
- **Herramientas Tácticas Esenciales**:
  - Navegación (`SEL`, `SECTOR`), telemetría viva (`SECTOR` / `GRID` / `ESCALA`), `Ir a Grid` (`Ctrl+G`) y `+PLI`.
  - `PING`, `PLI`, `MARCA` (simbología NATO/CoT), `NOTA`, `ORDEN` (`CAS`, `SUP`, `QRF`, `MED`), `FRENTE` (`FLOT` / `FEBA` / `Phase Line` / `AO`), `AVANCE`, `MEDIR`, `TRAZO` (optimizado también para pantalla táctil en Android) y `BORRAR`.
- **Host Local + Cliente E2EE (`COMMS E2EE`)**:
  - En **Windows** puedes iniciar un servidor local encriptado (`wss://`) para tu escuadra vía red local Wi-Fi/LAN, Tailscale o Tailscale Funnel.
  - En **Windows y Android** los operadores se conectan con verificación de huella SHA-256, `PBKDF2-SHA256`, `AES-256-GCM` y Radio Táctica Encriptada.

> **Servidores Dedicados & Ediciones a Medida**: ¿Tu clan o unidad necesita un **Servidor Dedicado 24/7** siempre activo con dominio SSL, identidad visual propia o **funciones personalizadas** adaptadas a tu forma de operar? Contáctanos para diseñar tu solución a medida.

---

## Descarga e Instalación (Releases)

Ve a la pestaña **Releases** del repositorio y descarga el archivo para tu dispositivo:

- **Windows (PC)**: descarga `ATAK-BOB-Portable.exe` y ejecútalo directamente (no requiere instalación).
- **Android (Tableta / Teléfono)**: descarga `ATAK-BOB.apk` e instálalo en tu dispositivo Android.

---

## Cómo cargar mapas o paquetes `.bobmap.json`

1. Pulsa **`+ MAPAS`** en la barra superior.
2. Elige **`Seleccionar Imagen o Paquete (.bobmap.json)...`** y selecciona una imagen (`PNG`/`WEBP`/`JPG`) o un archivo de paquete `.bobmap.json`.
3. Pulsa **`Cargar Mapa`**. El mapa, su calibración de cuadrícula y sus puntos de interés quedarán guardados en el dispositivo.

---

<a id="english-version"></a>

# ATAK BOB (English)

Lightweight **C2 / Situational Awareness** tactical platform for Windows desktop (portable `.exe`) and Android tablets or phones (`.apk`), featuring **custom maps**, **calibrated map packages (`.bobmap.json`)**, 5-digit grid coordinates, and **end-to-end encrypted communications (E2EE + TLS SHA-256)** via local host (LAN / Tailscale / Tailscale Funnel).

---

## Included Features in This Public Release

- **Custom Maps & Map Packages (`.bobmap.json`)**: Load any image (`PNG`, `WEBP`, `JPG`) or calibrated `.bobmap.json` package (with exact 2D affine grid calibration and built-in POIs) from **`+ MAPAS`**, stored locally on both PC and Android devices.
- **Essential Tactical Toolset**:
  - Navigation (`SEL`, `SECTOR`), live coordinate telemetry (`SECTOR` / `GRID` / `SCALE`), Go to Grid (`Ctrl+G`), and `+PLI`.
  - `PING`, `PLI`, `MARCA` (NATO/CoT markers), `NOTA` (quick map notes), `ORDEN` (support requests: `CAS`, `SUP`, `QRF`, `MED`), `FRENTE` (`FLOT` / `FEBA` / `Phase Line` / `AO`), `AVANCE`, `MEDIR`, `TRAZO` (touch-optimized for Android screens & stylus), and `BORRAR`.
- **Local Host + E2EE Client (`COMMS E2EE`)**:
  - On **Windows**, host an encrypted local server (`wss://`) for your squad over LAN/Wi-Fi, Tailscale, or Tailscale Funnel.
  - On both **Windows & Android**, operators join via SHA-256 certificate pinning, `PBKDF2-SHA256`, `AES-256-GCM`, and Encrypted Tactical Radio chat.

> **Dedicated 24/7 Servers & Custom Editions**: Does your clan or unit need an always-on **24/7 Dedicated Server** with a custom SSL domain, your own unit branding, or **custom features** tailored to the way you operate? Contact us to build a custom solution.

---

## Download & Installation (Releases)

Open the repository's **Releases** tab and download the build for your device:

- **Windows (PC)**: download `ATAK-BOB-Portable.exe` and run it directly (portable, no installer required).
- **Android (Tablet / Phone)**: download `ATAK-BOB.apk` and install it on your Android device.

---

## How to Load Maps or `.bobmap.json` Packages

1. Click **`+ MAPAS`** on the top bar.
2. Select **`Seleccionar Imagen o Paquete (.bobmap.json)...`** and choose an image (`PNG`/`WEBP`/`JPG`) or a `.bobmap.json` package file.
3. Click **`Cargar Mapa`**. The map, grid calibration, and points of interest will remain saved on your device.

<!-- Nota: Solo dejo este proyecto para agrandar mi repositorio, denme chamba -->
