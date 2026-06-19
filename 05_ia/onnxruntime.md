# ONNX Runtime

## Advertencia observada

```text
Specified provider 'CUDAExecutionProvider' is not in available provider names
```

## Explicación

La Raspberry Pi no dispone de CUDA.

ONNX Runtime ejecutará inferencias utilizando CPU.

## Proveedores detectados

```text
CPUExecutionProvider
AzureExecutionProvider
```

## Impacto

La funcionalidad sigue operando normalmente utilizando CPU.