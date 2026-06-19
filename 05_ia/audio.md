# Diagnóstico de Audio

## Error observado

```text
Error querying device -1
```

## Síntomas

- Wake Word no inicia correctamente.
- Grabación PTT falla.
- El agente permanece en espera.

## Posibles causas

- Micrófono no conectado.
- Micrófono no seleccionado como dispositivo predeterminado.
- Configuración incorrecta de sounddevice.
- Problema de permisos ALSA.

## Verificación recomendada

```bash
arecord -l
```

```bash
aplay -l
```

```bash
python -c "import sounddevice as sd; print(sd.query_devices())"
```