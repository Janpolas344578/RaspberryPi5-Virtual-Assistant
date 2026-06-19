# Gestión de Modelos Ollama

## Modelos instalados

```bash
ollama list
```

### Gemma

```bash
ollama pull gemma3:1b
```

### Qwen

```bash
ollama pull qwen2.5:1.5b
```

### Moondream

```bash
ollama pull moondream
```

## Eliminar modelos

```bash
ollama rm gemma4:e2b
```

## Comparativa utilizada

| Modelo | Tamaño |
|----------|----------|
| gemma3:1b | 815 MB |
| qwen2.5:1.5b | 986 MB |
| moondream | 1.7 GB |

## Motivo del cambio

Se eliminó gemma4:e2b (7.2 GB) para reducir consumo de memoria y almacenamiento.