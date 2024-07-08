# open-firefox

```sh
sudo apt-get update
sudo apt-get install xdotool

```


```sh
#!/bin/bash
# Archivo: open_firefox.sh

# Espera 10 segundos para asegurarse de que el entorno de escritorio esté completamente cargado
sleep 10

# Abre Firefox
firefox &

# Espera unos segundos para asegurarse de que Firefox esté completamente abierto
sleep 5

# Envía la tecla F11 a Firefox para ponerlo en pantalla completa
xdotool search --onlyvisible --class firefox windowactivate --sync key F11

```

Tipear en linux *start* y elegir *start application*
