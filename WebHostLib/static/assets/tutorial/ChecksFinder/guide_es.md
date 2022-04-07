# Guia configuración para ChecksFinder

## Software Requerido

- ChecksFinder, descargable desde [la pagina de releases para el juego en Github](https://github.com/jonloveslegos/ChecksFinder/releases) (latest version)
- Archipelago, descargable desde [la pagina de releases de Archipelago](https://github.com/ArchipelagoMW/Archipelago/releases)
    - (seleccionar `ChecksFinder Client` durante la instalacion.)

## Configurando tu fichero YALM

### Que es un fichero YALM?

Leer la guia para configurar un fichero yalm basico en la guia de configuración de Archipelago: [Guia Básica de configuracion de multiworld](/tutorial/archipelago/setup/es)

### Donde obtengo un fichero YAML?

Puedes personalizar tu configuracion visitando la [Pagina de opciones de jugador para ChecksFinder](/games/ChecksFinder/player-settings)

### Generando una partida con ChecksFinder

**ChecksFinder es un juego que está pensado para ser jugado mientras juegas a otro juego! Es muy probable que tu juego se quede interrumpido durante un largo periodo de tiempo si lo juegas solo con otra persona!**

Cuando te unes a una sesión multiworld, se te pedira que entregues el fichero YALM al anfitrion de la sesion. El anfitrion unicamente debe generar e iniciar la partida MW incluyendo el fichero yalm suministrado.

### Conectarse al MultiServer

Primero ejecuta tanto ChecksFinder como CheckFinderClient (este ultimo esta situado en el directorio de Archipelago).

Una vez esten ambos iniciados, en CheckFinderClient introduce la direccion del anfitrion (archipelago.gg si es un juego hospedado en la web de archipelago, o la direccion IP del anfitrión en caso contrario), y el puerto en el que esta ejecutándose esa sesión (si el puerto de la sesión es el puerto por defecto de Archipelago (38281) no es necesario especificarlo) en el campo superior.

El cliente pedirá el usuario con el que quieres conectarte (es el valor de la opción "name" del fichero yalm), introdúcelo en el campo de texto en la parte inferior del cliente.

### Jugar al juego

Una vez la consola indique que te has unido a la sala, ya estas listo.
