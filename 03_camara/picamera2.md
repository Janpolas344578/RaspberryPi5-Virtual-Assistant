# Instalación de Picamera2

## Instalar paquete

```bash
sudo apt install python3-picamera2 -y
```

## Verificar instalación

```bash
python3 -c "from picamera2 import Picamera2; print('OK')"
```

## Ver paquete instalado

```bash
dpkg -l | grep picamera2
```