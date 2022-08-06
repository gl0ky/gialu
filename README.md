![](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fwww.mvps.net%2Fdocs%2Fwp-content%2Fuploads%2F2019%2F02%2Farch-linux.png&f=1&nofb=1)
![](https://img.shields.io/github/stars/gl0ky/gialu) ![](https://img.shields.io/github/forks/gl0ky/gialu) ![](https://img.shields.io/github/tag/gl0ky/gialu) ![](https://img.shields.io/github/license/gl0ky/gialu) ![](https://img.shields.io/github/issues/gl0ky/gialu) ![](https://img.shields.io/twitter/url?url=https%3A%2F%2Fgithub.com%2Fgl0ky%2Fgialu)

# Guia de instalacion de Arch Linux - UEFI

Hola! 😘 en esta guia aprenderemos a instalar la distribucion de **Arch Linux** desde cero 100% a mano en sistemas **UEFI😎**, pronto hare una guia para sistemas **BIOS/MBR**, se habla mucho por ahi de la complejidad de la instalacion de este sistema, pero realmente si entendemos lo que estamos haciendo no es nada complicado, solo hay que tener siertas cosas en cuenta para que todo salga bien😂

> I use arch btw.

## Recomendaciones importantes👀

1. Recomiendo al 100% hacer este proceso en una maquina virtual antes de hacerlo en local😶.
2. Revisar cada comando varias veces antes de presionar enter😢.
3. No copies y pegues comandos, entiende lo que haces🙈.
4. Si no entiendes algo, ahi tienes internet! sientete libre de buscar, papi google siempre tendra las respuestas, no te quedes con dudas!😊
5. Preparate mentalmente.😏


**TABLA DE CONTENIDOS**

- [Guia de instalacion de Arch Linux - UEFI](#guia-de-instalacion-de-arch-linux---uefi)
  * [Recomendaciones importantes👀](#recomendaciones-importantes--)
  * [1. Crear medio de instalacion💿.](#1-crear-medio-de-instalacion--)

## 1. Crear medio de instalacion💿.

Primero crearemos una USB booteable para la instalacion de nuestro sistema, para esto vamos a necesitar:

- Memoria USB 4GB o mas.
- ISO del sistema operativo Arch Linux 64 bits.
- Programa para crear USB booteable (Rufus).

Nos dirigimos a la pagina de Rufus: https://rufus.ie/es/, descargaremos el instalador del programa para poder crear nuestro medio de instalacion

> **Nota:** Omitiremos este paso en caso de que fueramos a hacer una instalacion en una maquina virtual.

![](https://github.com/gl0ky/gialu/blob/master/arch-install/images/rufus-1.png?raw=true)

Luego descargaremos la ISO de Arch linux: https://archlinux.org/


Nos dirigimos al apartado de descargas en el panel superior.

![](https://github.com/gl0ky/gialu/blob/master/images/iso-1.png?raw=true)

Seleccionamos cualquiera de los links en el apartado de World Wide.

![](https://github.com/gl0ky/gialu/blob/master/images/iso-2.png?raw=true)

Descargamos la imagen de 64 Bits del sistema operativo.

![](https://github.com/gl0ky/gialu/blob/master/images/iso-3.png?raw=true)

Bien, luego que tengamos esto, procederemos con la creacion del medio de instalacion.

> **Nota:** en caso de instalar en una maquina virtual, no necesitamos crear un medio de instalacion, con descargar la ISO de arch sera suficiente ;).

1. Primero instalamos el programa para crear el medio de instalacion, Rufus.

 *Ejecutas el programa y next, next, next lol.*

2. Conectamos el USB, abrimos Rufus, y seleccionamos nuestra memoria USB en el menu de seleccion.

 ![](https://github.com/gl0ky/gialu/blob/master/images/booteable-1.png?raw=true)

3. Seleccionamos la ubicacion donde descargamos la ISO de nuestro Arch.

 ![](https://github.com/gl0ky/gialu/blob/master/images/booteable-2.png?raw=true)
 
 ![](https://github.com/gl0ky/gialu/blob/master/images/booteable-3.png?raw=true)

4. Seleccionamos el esquema de particiones GPT.

 ![](https://github.com/gl0ky/gialu/blob/master/images/booteable-4.png?raw=true)
 
5. Elegimos un nombre para nuestro medio de instalacion, y seleccionamos empezar.
 
 ![](https://github.com/gl0ky/gialu/blob/master/images/booteable-5.png?raw=true)
  
6. Especificamos que queremos escribir la imagen en modo ISO.

  ![](https://github.com/gl0ky/gialu/blob/master/images/booteable-6.png?raw=true)
