### Examen 1
**Universidad ICESI**  
**Curso:** Sistemas Operativos  
**Docente:** Laura Isabella Tabares P.  
**Tema:** Comandos de Linux, Virtualizaci�n  
**Correo:** laura.tabares@correo.icesi.edu.co

### Objetivos
* Conocer y emplear comandos de Linux para la realizaci�n de tareas administrativas
* Virtualizar un sistema operativo

### Prerrequisitos
* Virtualbox o WMWare
* Imagen de sistema operativo de debian 9

### Pasos para la validaci�n de la imagen.
1. Descargar Debian 9 y saber la ubicaci�n de la carpeta donde lo descarg�.
2. usar desde la terminal de windows los comandos: powershell -->  ir a la carpeta donde esta la imagen del sistema operativo y luego, Get-FileHash .\debian-9.4.0-amd64-netinst.iso
3. buscar el CheckSum del algoritmo SHA256: https://cdimage.debian.org/debian-cd/current/amd64/iso-cd/SHA256SUMS
4. Comparar.
5. De igual manera se puede comprar los otros algoritmos: SHA1, SHA512... En mi caso solo compar� SHA1 Y SHA256

--- para ssh
explicaci�n: https://wiki.debian.org/es/SSH
apt-get install openssh-client
apt-get install openssh-server
service shh start

y funciono con putty!!!

### Actividades
1. Incluir nombre, c�digo (5%)
2. Ortograf�a y redacci�n cuando sea necesario (5%)
3. Descargue la imagen de instalaci�n del sistema operativo debian 9 version y realice una comprobaci�n de la imagen. Indique los pasos y presente capturas de pantallas de la validaci�n de la imagen (10%)
4. Realice la instalaci�n del sistema operativo debian server 9. Indique los pasos de la instalaci�n (10%). Muestre por medio de comandos de Linux informaci�n del sistema operativo. No incluya capturas de pantalla de la instalaci�n. Incluya capturas de pantalla o la salida en formato shell markdown de los comandos empleados.
5. Realice la configuraci�n de una interfaz tipo puente o privada. Muestre como puede acceder a la maquina a trav�s de putty (Windows) � SSH (Linux) (10%)
6. Realice la instalaci�n de git y tig. Indique los pasos y presente capturas de pantalla de la instalaci�n. La evidencia de la instalaci�n debe incluir una captura de pantalla de tig con el historial de los commits realizados para la soluci�n del examen (10%)
7. Exporte la m�quina virtual creada e importela en una de las m�quinas de la sala de sistemas. Presente capturas de pantalla y los pasos empleados (20%). Esta m�quina virtual ser� empleada para futuras pr�cticas.
8. Realice un cuadro comparativo entre CentOS7 y Debian 9. Incluya al menos 10 caracter�sticas (20%)
9. El informe debe ser subido a un repositorio de github en formato README.md. El repositorio de github debe ser un fork de https://github.com/ICESI-Training/so-exam1 y para la entrega deber� hacer un Pull Request (PR) respetando la estructura definida. La url del repositorio de github debe incluirse en el informe (10%)  

### Nota
* Cada commit debe seguir la buenas pr�cticas indicadas en clase
* No se recibiran ex�menes que no sean mezclados autom�ticamente por la herramienta icesi-gm-tool
* El examen es individual, cualquier copia anula el examen

### Referencias
* https://www.debian.org/  