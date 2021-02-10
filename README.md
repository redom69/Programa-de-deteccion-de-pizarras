## Programa-de-detección-de-pizarras
# Explicación del proyecto
El objetivo de este proyecto es desarrollar un algoritmo que pueda reconocer una pizarra en una imagen. El funcionamiento del algoritmo es el siguiente, el algoritmo entrenara una red neuronal con 100 imágenes de esquinas de pizarras, de estas imágenes extraerá los puntos de interés y los almacenara en una base de datos.
Una vez tengamos la red neuronal entrenada y la base de datos de los puntos de interés, ya podemos pasar a la parte de la prueba del algoritmo. El algoritmo recorrerá un directorio de prueba con 40 imágenes en las que aparecen pizarras. Este comprobará donde está la pizarra, según el algoritmo, y después medirá la eficacia del algoritmo utilizando el algoritmo de Deep Learning, IoU. Si se ejecuta el proyecto mostrará las imágenes con el recuadro real de la pizarra y el que saca el algoritmo, se medirá también la eficacia del algoritmo desarrollado. Al final de la ejecución mostrara un mensaje de la media de detección de todas las pizarras en la carpeta de prueba.
# Ejecución del proyecto
Este archivo sirve como guía para ejecutar este proyecto. Voy a explicar la forma de ejecutarlo desde Colab, que es el IDE que utilice yo para desarrollar el proyecto.
Lo primero de todo que deberías hacer es clonaros el repositorio o descargaros el cuaderno de Jupiter en este caso. 

Una vez abierto el cuaderno en Colab deberéis de crear dos directorios, el directorio train y el directorio test. En ellos deberéis de introducir las imágenes respectivamente. También deberéis de introducir el archivo .txt en el directorio raíz, este archivo contendrá los puntos en los que se encuentran las esquinas de la pizarra de test.

Una vez introducidos los dos directorios y el archivo .txt ya podréis ejecutar el cuaderno y ver el resultado del proyecto.
