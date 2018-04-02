# Parcial 1
**Universidad Icesi**

**Nombre:** Laura Isabella Tabares P.

**Código:** A00054120

**Correo:** laura.tabares@correo.icesi.edu.co
 
**URL:** https://github.com/Lauraitp/so-exam1

_____

### Pasos para la validación de la imagen.
#### Punto 3

1. Descargar Debian 9 en (https://cdimage.debian.org/debian-cd/current/amd64/iso-cd/) y tener muy en cuenta la ubicación de la carpeta donde se descargó.


![](imagenes/Descargar.png)


Nota: Manera Nº 1 de realizar la validación de la imagen
2.1. Usar desde la terminal de windows los comandos:
```console
powershell
```
Luego,  ir a la carpeta donde esta la imagen del sistema operativo y utilizar el comando:

```console
Get-FileHash .\debian-9.4.0-amd64-netinst.iso
```
3.1. buscar el CheckSum del algoritmo SHA256: https://cdimage.debian.org/debian-cd/current/amd64/iso-cd/SHA256SUMS
4. Comparar.
De igual manera se puede comprar los otros algoritmos: SHA1

![](imagenes/verificadoCheckSumSHA1.png)


SHA256:

![](imagenes/verificadoCheckSumSHA256.png)



Forma Nº 2 de realizar la validación de los comandos:
2.2. Descargar la siguiente herramienta (https://download.cnet.com/MD5-SHA-Checksum-Utility/3001-2092_4-10911445.html) para comparar los checksums.
3.2. Una vez ejecutemos el instalador, buscamos la imagen (el .iso) y lo comparamos con el checksum que descargamos en el punto 2.1.
 
![](imagenes/VerificarChecksumMD5.png)

### Instalación

#### Punto 4


