# Articulos/Categorias Jesús Varela Grela

El proyecto consta de una pagina web donde puedes visualizar articulos y categorias 
 también tienes la opción de agregar un articulo o editar uno ya creado y eliminar los que estan guardados en la base de datos

## Instrucciones

Este proyecto es muy simple, primero tenemos que crear una base de datos, colocar en el Xammp/htdocs la carpeta que queramos iniciar en el servidor con el CMD (Symfony server:start)
Despues tendremos que escribir en el navegador localhost:8000/ y tendremos que navegar por la interfaz, cada boton te marca lo que hace :
    • El botón editar te permitirá cambiar los datos.
    • El botón agregar añadirá datos a la base de datos
    •  El botón borrar borrara los datos
    • El botón ver te permitirá ver con mas detalles los datos.
Si clicamos en alguno de los articulos nos dejara visualizar.


### Pre-requisitos 

    • XAMMP : Carpeta en ruta de xampp | C:/xampp/htdocs
    • SYMFONY : php bin/console doctrine:database:create | php bin/console doctrine:schema:update –force
    • CMD :  Ruta del proyecto | symfony server:start

```

```

### Instalación 

Colocaremos  la carpeta el proyecto en la ruta:

C:/xampp/htdocs

Crear la base de datos(poner nombre categoria)
php bin/console doctrine:database:create

Actualizarla

php bin/console doctrine:schema:update –force

Iniciar servidor(en la ruta al proyecto)

symfony server:start

Entrar(numero que salga por pantalla en el cmd por defecto 8000)
localhost:8000/


## Ejecutando las pruebas 

Si agregamos un articulo debería poder observarse en la categoria pertinente y si editamos observaremos los cambios y al borrar deberia desaparecer.

### Tecnologias Utilizadas

    • Symfony
    • PHP 
    • CSS
    • Visual Studio
    • XAMPP

### Autor

Jesus Varela Grela



## Licencia

Apache

## Con️tribuir

    • compartir el archivo y mencionar al creador y la referencia si la utilizais.
    
    • Si queréis ayudar podéis intentar  mejorar el código.
