# Configuración del Entorno en Windows

## Navegación en PowerShell

### Error

```powershell
cd /d D:\IPN\ProyectoAsistenteVirtual\Repositorio\AsistRCoral
```

PowerShell no acepta la sintaxis `/d` utilizada por CMD.

### Solución

```powershell
Set-Location D:\IPN\ProyectoAsistenteVirtual\Repositorio\AsistRCoral
```

o

```powershell
cd D:\IPN\ProyectoAsistenteVirtual\Repositorio\AsistRCoral
```