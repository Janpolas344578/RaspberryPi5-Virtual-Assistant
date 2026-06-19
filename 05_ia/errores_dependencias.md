# Resolución de Dependencias

## Error

```text
ModuleNotFoundError:
No module named 'sentence_transformers'
```

### Archivo involucrado

```python
from sentence_transformers import SentenceTransformer
```

### Solución

```powershell
pip install sentence-transformers
```

---

## Error posterior

```text
ERROR: Could not install packages due to an OSError: [Errno 22] Invalid argument
```

### Observaciones

La instalación de sentence-transformers descargó:

- torch
- transformers
- tokenizers
- safetensors
- networkx
- sympy

pero la instalación finalizó con error.

### Verificación

```powershell
pip show sentence-transformers
```

Resultado:

```text
Package(s) not found
```