# Parcial 1
**Universidad Icesi**

**Nombre:** Laura Isabella Tabares P.

**Código:** A00054120

**Correo:** laura.tabares@correo.icesi.edu.co
 
**URL:** https://github.com/Lauraitp/so-exam1

_____

### Pasos para la validación de la imagen.
#### Punto 3
1. Descargar Debian 9 y tener muy en cuenta la ubicación de la carpeta donde se descargó.
![](imagenes/Descargar.png)
2. Usar desde la terminal de windows los comandos: powershell -->  ir a la carpeta donde esta la imagen del sistema operativo y luego, Get-FileHash .\debian-9.4.0-amd64-netinst.iso
3. buscar el CheckSum del algoritmo SHA256: https://cdimage.debian.org/debian-cd/current/amd64/iso-cd/SHA256SUMS
4. Comparar.
5. De igual manera se puede comprar los otros algoritmos: SHA1, SHA512... En mi caso solo comparé SHA1 Y SHA256.

