# personal_id_cleaner

a simple odoo module that allow to remove undesirable characters of Personal ID number.

## Requirements

a running instance of Odoo version 10.

## Installation

+ Clone this repo in your addons's path.
+ Update the list of modules in the web interface.
+ Search for personal_id_cleaner in the apps menu and install it.

## Use

After install you'll see PersonalID in the parent menu, just fill the number you want to clean in the "unclean" field and click save.

the module automatically will remove any alpha, special character and leading number "0" if they exist and store the result in the "clean" field

___

Un módulo sencillo de odoo que permite remover caracteres indeseables de números de indentificación personal.

## Requerimientos

Una instancia corriendo de odoo version 10.

## Instalación

+ Clonar el repositorio en la ruta de modulos de la instancia de odoo.
+ Actualizar la lista de modulos disponibles desde la interfaz web.
+ Buscar "personal_id_cleaner" en en menu de aplicaciones y hacer click en instalar.

## Uso

Luego de instalar el módulo podrás ver la entrada "PersonalID" en los menus padres de odoo, simplemente llenando el campo "unclean" con el numero que quieras limpiar y hacendo click en "guardar", el módulo automáticamente removerá caracteres especiales, letras y "0" a la izquierda y almacenará el resultado en el campo "clean". 