INSTRUCCIONES BÁSICAS

config - archivo de configuracion de codeigniter
base_url -> Direccion para que salga la pagina
index: el index, para que no salga (porque si no es localhost/index.php/login o localhost/index.php/añadirLibro)
.htaccess: solucion buscada por internet para quitar index.php.

controller: el que se encarga de controlar (modelo vista-controlador), de hacer todas las acciones que el usuario no ve.
$this -> referencia a un objeto que puede ser view (vista), input(algun campo)
biblioteca_model: el que recibe y envia informacion a la base de datos
views: vistas, las distintas ventanas que se observan, PHP y HTML

$data donde guardas informacion en forma de array, para pasarla del controlador a la vista.

INSTRUCCIONES FUNCIONAMIENTO

Acceder mediante url a localhost/login
Una vez dentro nos saldrá un menú para loguearnos, podemos entrar como -u admin -p admin
La funcionalidad de la aplicación es poder ver una base de datos de una biblioteca con comandos sql
Se pueden añadir libros o ver lo que tenemos con los mismos comandos de sql, pero con una interfaz gráfica
También podemos añadir libros a la biblioteca desde localhost/añadirLibro con la interfaz de la web

TUTORIALES UTILIZADOS

Sobretodo me ha ayudado un amigo que trabaja con CodeIgniter diariamente, le pedí soporte y estuvimos en una charla de voz haciendo
el proyecto mientras me explicaba los fallos que me iban surgiendo.
El proyecto es un ejercicio de 2ºDAI cuando él estudiaba, me recomendó hacerlo porque es sencillo.
Por último destacar que el proyecto se realizó en Windows10 con XAMP, algo que me resultó más asequible al principio, al no tener que
lidiar tanto con mySQL por cuenta propia y estuviese más automatizado.
