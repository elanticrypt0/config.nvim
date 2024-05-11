# Install

crear una carpeta en $HOME/.config/nvim

# Pasos en la instalación y configuración de un paquete

## 1. Agregar el paquete

en la carpeta nvim/lua/YOUR_USER_NAME/packer.lua agregar el paquete:

```lua
use('maker/packet/')
```


## 2. Cofiguración

crear el archivo de configuracion en


nvim/after/plugin/packet.lua

escribir las configuraciones ahí.

Luego ejecutar:
```vim
:so
:PackerSync
```


