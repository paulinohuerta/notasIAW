# Script en perl notas.pl
Con este script mostraremos los datos de un fichero el cual contiene prefijo:nota:alumno, filtrando por el prefijo de la asignatura todas las filas que sean de esa asignatura.

# Script en perl notasformu.pl
Con el script notasformu obtendremos lo mismo pero nos mostrara dos formularios, el primero para decir nuestro nombre y el segundo para decir la asignatura que queremos obtener los datos.

Para poder ejecutarlo necesitas:

  - Servidor apache funcionando
  - Modulo cgi-bin habilitado y funcionando
  - Copiar el archivo notas.pl a la carpeta /usr/lib/cgi-bin
  - Copiar el archivo notas.txt a la home de nuestro usuario.
###### Si nuestro usuario no se llama usuario debemos editar el codigo donde nos dira el codigo (Viene la siguiente linea:Cambia esta linea si tu nombre de usuario no es USUARIO) poniendo la ruta de donde se encuentre nuestro fichero notas.txt


_En mi caso no he conseguido hacerlo funcionar del todo, ya que a la hora de mostrarme la solucion, me muestra el 2 formulario junto a la solucion._
