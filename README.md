# 🎬 AI Vision Studio - I Am Movie Make

> Generador de videos cinematográficos 100% offline. Sin APIs. Sin conexión. Totalmente local.

![Versión](https://img.shields.io/badge/Versión-1.0.0-blue)
![Estado](https://img.shields.io/badge/Estado-Activo-green)
![Offline](https://img.shields.io/badge/Modo-100%25%20Offline-brightgreen)
![Puerto](https://img.shields.io/badge/Puerto-9090-orange)

**AI Vision Studio** es una herramienta web que funciona completamente sin conexión a internet. Genera videos con efectos de cámara y movimientos cinematográficos directamente en tu navegador, sin enviar datos a servidores externos.

---

## ✨ Características

- 🔒 **100% Offline:** Funciona sin internet. Privacidad total.
- 🚫 **Sin APIs:** No requiere conexiones externas ni claves API.
- 💻 **Procesamiento Local:** Todo se ejecuta en tu navegador.
- 🖼️ **Image-to-Video:** Convierte imágenes en videos animados
- 🎥 **Control de Cámara:** Pan, Zoom, Orbit, Dolly y más movimientos
- 🎨 **Estilos Cinematográficos:** Múltiples presets de estilo
- ⏱️ **Duración Personalizable:** Videos de 5 segundos o más
- 📐 **Múltiples Resoluciones:** Desde 720p hasta 4K Full HD
- 🎞️ **Control de FPS:** 24, 30, 60 FPS
- 📹 **Video Sequencer:** Crea secuencias de video complejas
- 💾 **Galería Local:** Gestiona tus videos generados
- 🌙 **Modo Oscuro:** Interfaz moderna y elegante

---

## 🛠️ Tecnologías

- **Frontend:** HTML5 + CSS3 + JavaScript Vanilla
- **Video Processing:** Canvas API + WebCodecs API
- **UI Framework:** Tailwind CSS
- **Almacenamiento:** LocalStorage / IndexedDB
- **Despliegue:** GitHub Pages (funciona offline después de cargar)

---

## 🚀 Instalación y Uso

### Opción 1: GitHub Pages (Recomendado)
Simplemente visita: [https://ferplex.github.io/iamoviemake/](https://ferplex.github.io/iamoviemake/)

La aplicación se carga una vez y luego funciona offline.

### Opción 2: Local

```bash
# Clona el repositorio
git clone https://github.com/ferplex/iamoviemake.git
cd iamoviemake

# Opción A: Servidor Python
python -m http.server 9090

# Opción B: Servidor Node.js
npx http-server -p 9090

# Opción C: Servidor PHP
php -S localhost:9090