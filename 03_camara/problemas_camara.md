# Problemas Comunes de Cámara

## Error: Camera frontend has timed out

Mensaje:

```text
Camera frontend has timed out!
Please check that your camera sensor connector is attached securely.
```

### Posibles causas

- Cable CSI mal conectado.
- Cámara parcialmente desconectada.
- Conector invertido.
- Inicialización incorrecta del sensor.

### Observación

En esta prueba el error apareció temporalmente:

```bash
rpicam-still -o prueba.jpg
```

Posteriormente la cámara volvió a funcionar correctamente sin cambios físicos.

### Verificación

```bash
rpicam-hello
```

```bash
rpicam-still -o prueba2.jpg
```