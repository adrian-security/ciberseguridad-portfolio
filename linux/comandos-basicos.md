# Mis primeros comandos de Linux

Estoy aprendiendo Linux para ciberseguridad.

## 1. pwd
Muestra el directorio actual.

## 2. ls
Muestra los archivos y carpetas.

## 3. whoami
Muestra el nombre del usuario actual.

## 4. cd
Permite cambiar de directorio.

### Ejemplo:

cd Documentos

Para volver al directorio anterior:

cd ..

## 5. mkdir
Permite crear una carpeta.

### Ejemplo:

mkdir Practicas

## 6. touch
Permite crear un archivo vacío o actualizar la fecha de modificación de un archivo existente.

### Ejemplo:

touch notas.txt

Crea un archivo llamado notas.txt.

## 7. cp
Copia archivos o directorios de una ubicación a otra.

### Ejemplo:

cp notas.txt copia.txt

Crea una copia del archivo notas.txt con el nombre copia.txt.

Para copiar una carpeta y todo su contenido:

cp -r Practicas Practicas_copia

## 8. rm
Permite eliminar archivos o directorios.

### Ejemplo para eliminar un archivo:

rm notas.txt

Elimina el archivo llamado notas.txt.

### Ejemplo para eliminar varios archivos:

rm archivo1.txt archivo2.txt

Elimina los dos archivos indicados.

### Ejemplo para eliminar una carpeta con contenido:

rm -r Practicas

Elimina la carpeta Practicas y todos los archivos y subcarpetas que contiene.

### Ejemplo para preguntar antes de eliminar:

rm -i notas.txt

Solicita confirmación antes de eliminar el archivo.

#### Importante: el comando rm elimina archivos y carpetas. Hay que utilizarlo con cuidado porque Linux no suele enviar estos elementos a la papelera.

rm: elimina archivos.

rm -r: elimina carpetas con contenido.

rm -i: solicita confirmación.

rm -ri: solicita confirmación al eliminar los elementos de una carpeta.


## 9. mv
Mueve archivos o directorios, y también se utiliza para renombrarlos.

### Ejemplo para cambiar el nombre:

mv notas.txt apuntes.txt

### Ejemplo para mover un archivo:

mv apuntes.txt Documentos/


## 10. cat
Muestra el contenido de un archivo en la terminal o concatena varios archivos.

### Ejemplo:

cat notas.txt

Es útil para consultar rápidamente archivos de configuración, registros y documentos de texto.

## 11. grep
Busca patrones de texto o cadenas específicas dentro de archivos o en la salida de otros comandos.

### Ejemplo:

grep "error" registro.txt

Busca la palabra error dentro del archivo registro.txt y muestra las líneas donde aparece.

Para buscar sin distinguir entre mayúsculas y minúsculas:

grep -i "error" registro.txt

Es especialmente útil en ciberseguridad para analizar registros (logs) y localizar posibles errores o actividades sospechosas.

## 12. find 
Permite buscar archivos y directorios dentro de una ubicación determinada.

### Ejemplo para buscar archivo: 

find ~ -name "notas.txt"

Busca un archivo llamado notas.txt dentro del directorio personal y sus subdirectorios.

### Ejemplo para buscar archivos por extensión:

find . -name "*.txt"

Busca exclusivamente archivos con extensión .txt.

### Ejemplo para buscar únicamente archivos:

find . -type f -name "*.txt"

Busca exclusivamente archivos con extensión .txt.

### Ejemplo para buscar directorios:

find ~ -type d -name "Logs"

Busca directorios llamados Logs dentro del directorio personal.

#### Elementos importantes:

find: permite buscar archivos y dirtectorios
.: representas el directorio actual.
~: representa el directorio personal.
-name: permite buscar por nombre.
-type f: busca únicamente archivos.
-type d: busca únicamente directorios.
*: comodín que representa cualquier conjunto de caracteres.

#### Aplicación en ciberseguridad
Es útil para localizar archivos de configuración, registros (logs), scripts y otros archivos que pueden ser necesarios durante el análisis de un sistema. 


## Lo que he aprendido
He practicado estos comandos en mi máquina virtual Ubuntu.
Estos comandos me permiten moverme por Linux, gestionar archivos y carpetas, consultar información y buscar contenido dentro de archivos.
