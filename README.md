# Mostrar Versiones (Instalacion Windows 11)

Cuando te descargas una iso de Windows o creas un medio de instalación puede ser que no te deje elegir que versión de Windows quieres instalar (Home, Pro, Education, etc)

Para solucionar este problema, hay que añadir un archivo ei.cfg a la carpeta 'sources' del usb que vamos a utilizar para la instalacion.

![image](https://github.com/alvarodelburgoperez/Mostrar_Versiones_Windows_11/assets/114286823/a1a85f5f-e780-433a-a043-a190170a2307)


Con este archivo, al iniciar la instalacion de Windows te va a detectar las diferentes versiones para que elijas la que desees.


## Archivo ei.cfg


[EditionID]
Professional
[Channel]
Retail
