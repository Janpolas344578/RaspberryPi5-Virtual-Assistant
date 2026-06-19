# Instalación de Ollama en Windows

## Instalación

```powershell
irm https://ollama.com/install.ps1 | iex
```

## Verificar instalación

```powershell
ollama --version
```

Resultado:

```text
ollama version 0.30.10
```

## Descargar modelos

### Qwen 2.5

```powershell
ollama pull qwen2.5:1.5b
```

Tamaño aproximado:

```text
986 MB
```

### Moondream

```powershell
ollama pull moondream
```

Tamaño aproximado:

```text
1.7 GB
```