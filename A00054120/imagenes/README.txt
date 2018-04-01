### Examen 1
**Universidad ICESI**  
**Curso:** Sistemas Operativos  
**Docente:** Laura Isabella Tabares P.  
**Tema:** Comandos de Linux, Virtualización  
**Correo:** laura.tabares@correo.icesi.edu.co

### Objetivos
* Conocer y emplear comandos de Linux para la realización de tareas administrativas
* Virtualizar un sistema operativo

### Prerrequisitos
* Virtualbox o WMWare
* Imagen de sistema operativo de debian 9

### Pasos para la validación de la imagen.
1. Descargar Debian 9 y saber la ubicación de la carpeta donde lo descargó.
2. usar desde la terminal de windows los comandos: powershell -->  ir a la carpeta donde esta la imagen del sistema operativo y luego, Get-FileHash .\debian-9.4.0-amd64-netinst.iso
3. buscar el CheckSum del algoritmo SHA256: https://cdimage.debian.org/debian-cd/current/amd64/iso-cd/SHA256SUMS
4. Comparar.
5. De igual manera se puede comprar los otros algoritmos: SHA1, SHA512... En mi caso solo comparé SHA1 Y SHA256

--- para ssh
explicación: https://wiki.debian.org/es/SSH
apt-get install openssh-client
apt-get install openssh-server
service shh start

y funciono con putty!!!

### Actividades
1. Incluir nombre, código (5%)
2. Ortografía y redacción cuando sea necesario (5%)
3. Descargue la imagen de instalación del sistema operativo debian 9 version y realice una comprobación de la imagen. Indique los pasos y presente capturas de pantallas de la validación de la imagen (10%)
4. Realice la instalación del sistema operativo debian server 9. Indique los pasos de la instalación (10%). Muestre por medio de comandos de Linux información del sistema operativo. No incluya capturas de pantalla de la instalación. Incluya capturas de pantalla o la salida en formato shell markdown de los comandos empleados.
5. Realice la configuración de una interfaz tipo puente o privada. Muestre como puede acceder a la maquina a través de putty (Windows) ó SSH (Linux) (10%)
6. Realice la instalación de git y tig. Indique los pasos y presente capturas de pantalla de la instalación. La evidencia de la instalación debe incluir una captura de pantalla de tig con el historial de los commits realizados para la solución del examen (10%)
7. Exporte la máquina virtual creada e importela en una de las máquinas de la sala de sistemas. Presente capturas de pantalla y los pasos empleados (20%). Esta máquina virtual será empleada para futuras prácticas.
8. Realice un cuadro comparativo entre CentOS7 y Debian 9. Incluya al menos 10 características (20%)
9. El informe debe ser subido a un repositorio de github en formato README.md. El repositorio de github debe ser un fork de https://github.com/ICESI-Training/so-exam1 y para la entrega deberá hacer un Pull Request (PR) respetando la estructura definida. La url del repositorio de github debe incluirse en el informe (10%)  

### Nota
* Cada commit debe seguir la buenas prácticas indicadas en clase
* No se recibiran exámenes que no sean mezclados automáticamente por la herramienta icesi-gm-tool
* El examen es individual, cualquier copia anula el examen

### Referencias
* https://www.debian.org/  