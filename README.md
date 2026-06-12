# Raspberry Pi Setup & AI Assistant Development

Repositorio de documentación y configuración utilizado durante el desarrollo de proyectos en Raspberry Pi, incluyendo instalación de herramientas, configuración del sistema operativo, acceso remoto, visión artificial, entornos Python, inteligencia artificial local y pruebas de hardware.

## Objetivo

Este repositorio sirve como bitácora técnica y guía de referencia para reproducir la configuración completa de una Raspberry Pi utilizada en proyectos de automatización, visión artificial e inteligencia artificial.

La documentación incluye procedimientos de instalación, comandos utilizados, configuraciones realizadas y pruebas ejecutadas durante el desarrollo.

---

## Hardware Utilizado

* Raspberry Pi
* Cámara oficial para Raspberry Pi
* Coral TPU (pendiente de documentar)
* ESP32 (pendiente de documentar)

---

## Software Utilizado

* Raspberry Pi OS
* Python 3
* Miniconda
* Entornos virtuales (venv)
* Picamera2
* Flask
* NumPy
* Ollama
* Git
* AnyDesk

---

## Estructura del Repositorio

```text
raspberry-pi-setup/
│
├── README.md
│
├── 01_sistema/
│   ├── actualizacion.md
│   ├── monitoreo.md
│   └── informacion_sistema.md
│
├── 02_acceso_remoto/
│   └── anydesk.md
│
├── 03_camara/
│   ├── pruebas_rpicam.md
│   ├── picamera2.md
│   └── aplicacion_camara.md
│
├── 04_python/
│   ├── venv.md
│   └── miniconda.md
│
├── 05_ia/
│   ├── ollama.md
│   ├── gemma.md
│   └── coral_tpu.md
│
├── 06_git/
│   └── github.md
│
└── scripts/
```

---

## Contenido Actual

### Sistema Operativo

* Actualización de paquetes
* Verificación de arquitectura
* Información del sistema
* Monitoreo de recursos

### Acceso Remoto

* Instalación de AnyDesk
* Configuración de servicios
* Desinstalación y limpieza

### Cámara Raspberry Pi

* Detección de cámaras
* Captura de imágenes
* Uso de rpicam-apps
* Uso de Picamera2

### Python

* Creación de entornos virtuales
* Instalación de dependencias
* Gestión de paquetes

### Inteligencia Artificial

* Instalación de Ollama
* Ejecución de modelos locales
* Preparación para integración con asistentes virtuales

---

## Convenciones

Cada documento incluye:

1. Objetivo de la actividad.
2. Comandos ejecutados.
3. Explicación técnica.
4. Resultados obtenidos.
5. Problemas encontrados y soluciones.

---

## Estado del Proyecto

En construcción.

La documentación se actualiza conforme se realizan nuevas configuraciones y pruebas sobre la Raspberry Pi.
