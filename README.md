# Gestion-de-la-memoria
Este programa funciona bien si tienes un sistema basado en linux. Yo comparto un sistema windows y linux en mi ordenador por lo cual me funciona bien.
## Explicación para Windows
En cambio si tienes Windows deberás sustituir las librerias <sys/mman.h> y <sys/wait.h> por la libreria <Windows.h> y las funciones mmap con CreateFileMapping y MapViewOfFile y fork y wait con procesos de Windows como CreateProcess y WaitForSingleObject

Enlace al github:
- https://github.com/Pabmoren/Gesti-n-de-la-memoria.git
