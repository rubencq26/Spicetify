<img src= "[https://github.com/rubencq26/rubencq26/blob/main/d4mh6ry-6502ac89-97e3-4297-9a10-efcf023654ff.gif](https://spicetify.app/images/spicetify.png)" width = 50px >
<h1>Spicetify</h1>

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
