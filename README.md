# 🐧 Taller 2 - Comandos Básicos de Linux

Este repositorio contiene los ejercicios realizados para familiarizarse con los comandos básicos de Linux, incluyendo el manejo de archivos, directorios y el uso del editor **vi**.

---

## 📁 Parte 1: Manejo de Archivos y Directorios

### 🛠️ Comandos Utilizados

| Acción | Comando | Descripción |
|--------|---------|-------------|
| Crear carpetas | `mkdir ejercicios1 ejercicios2` | Crea dos directorios nuevos |
| Navegar a carpeta | `cd ejercicios1` | Entra en la carpeta `ejercicios1` |
| Crear archivo con nano | `nano file1.dat` | Crea y edita un archivo con el texto "Hola mundo" |
| Copiar archivo | `cp file1.dat ../ejercicios2/file1_copia1.dat` | Copia el archivo con un nuevo nombre |
| Listar archivos | `ls` | Muestra el contenido del directorio |
| Mostrar contenido | `cat file1_copia1.dat` | Muestra el contenido del archivo |
| Crear carpeta y mover archivo | `mkdir mover` y `mv file1_copia1.dat mover/file1_movido.dat` | Crea una carpeta y mueve el archivo |
| Crear copia de seguridad | `cp file1_copia2.dat file1_copia2.dat.backup` | Crea una copia con extensión `.backup` |
| Eliminar archivos con patrón | `rm file1_copia*` | Elimina todos los archivos que coincidan con el patrón |
| Eliminar carpeta y contenido | `rm -r mover` | Elimina la carpeta y todo su contenido |

---

## ✏️ Parte 2: Editor vi

### 📋 Comandos Básicos de vi

| Acción | Comando o Tecla |
|--------|------------------|
| Entrar en modo inserción | `i` |
| Salir del modo inserción | `Esc` |
| Guardar y salir | `:wq` |
| Guardar sin salir | `:w` |
| Salir sin guardar | `:q!` |
| Mover el cursor | Flechas del teclado |
| Borrar una línea | `dd` |
| Deshacer último cambio | `u` |
| Buscar una palabra | `/palabra` |

---

## 🖼️ Capturas de Pantalla

Las capturas de pantalla de los ejercicios realizados se encuentran en la carpeta `media/` del documento original.

---

## ✅ Conclusión

Este taller permitió practicar y reforzar el uso de comandos esenciales de Linux para la gestión de archivos y directorios, así como el manejo básico del editor **vi**, herramienta fundamental para cualquier usuario de sistemas basados en Unix.

---

> 🐚 ¡Hecho con mucho amor por la terminal!
