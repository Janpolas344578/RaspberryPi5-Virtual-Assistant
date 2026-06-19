# Errores Comunes

## Archivo de imagen inexistente

### Error

```text
ValueError: File dog.4007.jpg does not exist
```

### Causa

La imagen especificada en el script no existe o la ruta es incorrecta.

### Solución

Verificar:

```python
image_path = "dog.4007.jpg"
```

Confirmar que el archivo existe:

```bash
ls
```

o usar una ruta absoluta.