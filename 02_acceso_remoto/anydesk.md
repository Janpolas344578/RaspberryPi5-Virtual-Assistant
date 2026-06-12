# Instalación de AnyDesk

## Dependencias

```bash
sudo apt install ca-certificates curl apt-transport-https
```

## Agregar clave GPG

```bash
sudo install -m 0755 -d /etc/apt/keyrings

sudo curl -fsSL https://keys.anydesk.com/repos/DEB-GPG-KEY \
-o /etc/apt/keyrings/keys.anydesk.com.asc

sudo chmod a+r /etc/apt/keyrings/keys.anydesk.com.asc
```

## Agregar repositorio

```bash
echo "deb [signed-by=/etc/apt/keyrings/keys.anydesk.com.asc] https://deb.anydesk.com all main" | sudo tee /etc/apt/sources.list.d/anydesk-stable.list > /dev/null
```

## Instalar

```bash
sudo apt update
sudo apt install anydesk
```

## Verificar servicio

```bash
sudo systemctl status anydesk
```

## Habilitar inicio automático

```bash
sudo systemctl enable anydesk
sudo systemctl start anydesk
```

## Desinstalación

```bash
sudo apt remove anydesk
sudo apt purge anydesk
sudo apt autoremove -y
```