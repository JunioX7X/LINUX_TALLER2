Taller 2: Fundamentos de Manejo de Archivos y Directorios en Linux
Este documento describe los pasos realizados en el Taller 2 de Sistemas Operativos, enfocado en el manejo de archivos y directorios en Linux, así como el uso básico del editor de texto vi. El taller se divide en dos partes: manejo de archivos y directorios mediante comandos en la terminal y uso del editor vi.
Parte 1: Manejo de Archivos y Directorios
En esta sección se realizaron una serie de operaciones básicas para la creación, manipulación y eliminación de archivos y directorios en un sistema Linux utilizando la terminal.
Pasos Realizados

Crear carpetasSe crearon dos directorios llamados ejercicios1 y ejercicios2.  
mkdir ejercicios1 ejercicios2


Entrar al directorio ejercicios1Se navegó al directorio ejercicios1.  
cd ejercicios1


Crear un archivo con nanoSe creó un archivo llamado file1.dat utilizando el editor nano y se escribió el texto "Hola mundo".  
nano file1.dat


Copiar el archivo a ejercicios2El archivo file1.dat se copió dos veces al directorio ejercicios2 con nombres diferentes: file1_copia1.dat y file1_copia2.dat.  
cp file1.dat ../ejercicios2/file1_copia1.dat
cp file1.dat ../ejercicios2/file1_copia2.dat


Verificar contenido de directoriosSe utilizó el comando ls para listar los archivos en el directorio actual y se probó el comando sl (que no es un comando estándar en Linux, probablemente un error tipográfico o un comando no instalado).  
ls
sl


Mostrar contenido de los archivosSe mostró el contenido de los archivos file1_copia1.dat y file1_copia2.dat utilizando cat.  
cat ../ejercicios2/file1_copia1.dat
cat ../ejercicios2/file1_copia2.dat


Crear una carpeta y mover un archivoSe creó un directorio llamado mover y se movió el archivo file1_copia1.dat a este directorio, renombrándolo como file1_movido.dat.  
mkdir mover
mv ../ejercicios2/file1_copia1.dat mover/file1_movido.dat


Crear una copia de seguridadSe creó una copia de seguridad del archivo file1_copia2.dat con el nombre file1_copia2.dat.backup.  
cp ../ejercicios2/file1_copia2.dat ../ejercicios2/file1_copia2.dat.backup


Eliminar archivos con un patrónSe eliminaron todos los archivos que coincidieran con el patrón file1_copia* en el directorio ejercicios2.  
rm ../ejercicios2/file1_copia*


Eliminar una carpetaSe eliminó el directorio mover junto con su contenido.  
rm -r mover



Resumen de Comandos Utilizados



Acción
Comando
Descripción



Crear carpetas
mkdir ejercicios1 ejercicios2
Crea dos directorios.


Copiar archivo
cp file1.dat ../ejercicios2/file1_copia1.dat
Copia el archivo y cambia su nombre.


Eliminar archivos
rm file1_copia*
Elimina varios archivos a la vez con patrón.


Eliminar carpeta
rm -r mover
Elimina una carpeta y su contenido.


Capturas de Pantalla
Las capturas de pantalla correspondientes a esta parte se encuentran en los archivos:

image1.jpeg
image2.jpeg
image3.jpeg
image4.jpeg

Parte 2: Editor vi
En esta sección se exploraron comandos básicos del editor de texto vi para la edición de archivos.
Tabla de Referencia de Comandos de vi



Acción
Comando o Tecla
Descripción



Entrar en modo inserción
i
Inicia la edición en el lugar del cursor.


Salir del modo inserción
Esc
Regresa al modo comando.


Guardar y salir
:wq
Guarda los cambios y sale del editor.


Guardar sin salir
:w
Guarda los cambios sin salir del editor.


Salir sin guardar
:q!
Sale del editor sin guardar cambios.


Mover el cursor
Flechas del teclado
Navega por el archivo.


Borrar una línea
dd
Elimina la línea donde está el cursor.


Deshacer último cambio
u
Revierte el último cambio realizado.


Buscar una palabra
/palabra
Busca una palabra en el archivo.


Capturas de Pantalla
Las capturas de pantalla correspondientes al uso de vi se encuentran en los archivos:

image5.jpeg
image6.jpeg
image7.jpeg
image8.jpeg

Conclusión
Este taller permitió practicar comandos fundamentales para la gestión de archivos y directorios en Linux, así como familiarizarse con el editor de texto vi. Los ejercicios realizados son esenciales para adquirir habilidades básicas en la administración de sistemas operativos basados en Linux.
