<h1><img src= "https://spicetify.app/images/spicetify.png" width = 50px > Spicetify</h1>


## Descargar:
Primero descarga spotify desde [aquí](https://download.scdn.co/SpotifySetup.exe)

Luego en la PowerShell de Windows copia esto
```powershell
iwr -useb https://raw.githubusercontent.com/spicetify/cli/main/install.ps1 | iex
```

```powershell
iwr -useb https://raw.githubusercontent.com/spicetify/marketplace/main/resources/install.ps1 | iex
```
Ahora tendras un marketPlace dentro de Spotify para descargar extensiones, busca **adblockify** e instalatelo

## Errores
Si para buscar canciones no funciona, en la PowerShell pon:
```powershell
spicetify config sidebar_config 0
```
```powershell
spicetify apply
```
