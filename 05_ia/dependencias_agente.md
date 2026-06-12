# Dependencias del Asistente Virtual

## Objetivo

Instalar las librerías necesarias para el funcionamiento del asistente virtual local en Raspberry Pi.

---

## Audio

### sounddevice

Captura y reproducción de audio mediante micrófono y altavoces.

```bash
pip install sounddevice
```

---

## Procesamiento Numérico

### NumPy

Operaciones matemáticas y manejo de arreglos numéricos.

```bash
pip install numpy
```

### SciPy

Procesamiento avanzado de señales y análisis científico.

```bash
pip install scipy
```

---

## Detección de Palabra de Activación

### OpenWakeWord

Permite activar el asistente mediante una palabra clave.

```bash
pip install openwakeword
```

---

## Inferencia ONNX

### ONNX Runtime

Motor de ejecución para modelos de inteligencia artificial optimizados.

```bash
pip install onnxruntime
```

---

## Modelos de Lenguaje

### Ollama

Comunicación con modelos locales ejecutados mediante Ollama.

```bash
pip install ollama
```

---

## Búsquedas en Internet

### DuckDuckGo Search

Permite realizar búsquedas web desde Python.

```bash
pip install duckduckgo-search
```

---

## Procesamiento de Imágenes

### Pillow

Manipulación y procesamiento de imágenes.

```bash
pip install Pillow
```

---

## Instalación Completa

```bash
pip install sounddevice
pip install numpy
pip install scipy
pip install openwakeword
pip install onnxruntime
pip install ollama
pip install duckduckgo-search
pip install Pillow
```

---

## Verificación

Ver todos los paquetes instalados:

```bash
pip list
```