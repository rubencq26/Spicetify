# Spicetify

## Descargar:
Primero descarga spotify desde [aquí](https://download.scdn.co/SpotifySetup.exe)

Luego en la PowerShell de Windows copia esto
```
iwr -useb https://raw.githubusercontent.com/spicetify/cli/main/install.ps1 | iex
```

```
iwr -useb https://raw.githubusercontent.com/spicetify/marketplace/main/resources/install.ps1 | iex
```
Ahora tendras un marketPlace dentro de Spotify para descargar extensiones, busca **adblockify** e instalatelo

## Errores
Si para buscar canciones no funciona, en la PowerShell pon:
```
spicetify config sidebar_config 0
```
```
spicetify apply
```
