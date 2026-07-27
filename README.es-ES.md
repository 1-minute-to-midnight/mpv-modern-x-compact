# mpv-modern-x-compact
Versión compacta de modern-x osc para mpv con una interfaz elegante tipo reproductor web

![preview](https://raw.githubusercontent.com/1-minute-to-midnight/mpv-morden-x-compact/main/preview.png)

# Cómo instalar
Coloca el archivo .lua en la carpeta "~~/scripts/" y elimina otros scripts de osc.

Establece el siguiente ajuste en mpv.conf :

`osc=no`

:warning: **Importante**: Instala la [fuente ModernX OSC](https://github.com/1-minute-to-midnight/mpv-morden-x-compact/raw/main/modernx-osc-icon.ttf) personalizada de [dexeonify](https://github.com/dexeonify/mpv-config/) para los iconos del OSC o crea una carpeta llamada `fonts` en la carpeta de configuración de mpv y coloca el archivo ttf allí.

# Configuración
Puedes cambiar varias opciones como el color de acento editando osc.conf, el cual debe colocarse en la carpeta "~~/script-opts/". El uso/creación de este archivo es opcional si deseas usar la configuración tal cual.
```
# Accent of the OSC and the title bar
osc_color=000000

# Color of the seekbar progress and handle
seekbarfg_color=E39C42

# Color of the remaining seekbar
seekbarbg_color=FFFFFF
```
Si deseas cambiar la altura de la barra de búsqueda o cambiar las posiciones de varios elementos:
Cerca de la línea 1675 verás varios títulos que indican cada elemento (Seekbar, Title, Playback control buttons etc.). Para mover los elementos horizontalmente (eje x), suma o resta valores a refX o a los valores x. Se puede realizar el mismo proceso con los valores y para moverlos verticalmente (eje y).

## Soporte de Miniaturas (Thumbnail Support)

Ve a [thumbfast](https://github.com/po5/thumbfast) y coloca thumbfast.lua en la carpeta scripts.
 
# Fuentes
- [Manrope](https://github.com/sharanda/manrope)

(Cambia osd-font en "~~mpv.conf" para que se vea como en la captura de pantalla)

# Créditos
- [Dexeonify's Personal Config](https://github.com/dexeonify/mpv-config)

- [Maoiscat's Modern Layout](https://github.com/maoiscat/mpv-osc-morden)

- [po5's Thumbfast Thumbnailer](https://github.com/po5/thumbfast)
