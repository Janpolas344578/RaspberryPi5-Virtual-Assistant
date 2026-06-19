# Pruebas del Agente Virtual

## Ejecución

```bash
python3 agent.py
```

## Flujo de arranque

1. Carga Wake Word.
2. Inicializa modelos.
3. Entra en modo espera.
4. Escucha activación.
5. Procesa audio.
6. Genera respuesta.

## Estado observado

```text
[INIT] Loading Wake Word...
[STATE] WARMUP
[STATE] IDLE
```

## Problema detectado

```text
Error querying device -1
```

El agente no pudo acceder a un dispositivo de entrada de audio válido.