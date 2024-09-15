

# Instalar Anaconda en Linux

* Descargar en el directorio home (personal) /home/ficovh (Linux) /Users/isavalladolid (mac)

```
    wget https://repo.anaconda.com/archive/Anaconda3-2024.06-1-Linux-x86_64.sh
```
* Ejecutar desde la terminal:
  ```
    $ bash Anaconda3-2024.06-1-Linux-x86_64.sh
  ```
* Clonar el repositorio de trabajo.
  ```  
    $ git clone https://github.com/esjimenezro/mebo2024.git
  ```

* cambiar al directorio mebo2024 del repositorio
  ```
    $ cd mebo2024
  ```
* Instalar los paquetes requeridos por mebo204
  ```
    $ conda env update  -f environment_v4.yml 
  ```
* Activar el entorno, en este caso mebo2024_v4

  ```
	$ conda activate  mebo2024_v4
  ```
* Mostrara el prompt de la terminal de la sifuiente manera, en mi caso, el usuario es ficovh y el nombre 
  del host o computadora es Thinkpad-X270, esto cambia en casa computadora.
  ``` 
	(mebo2024_v4) ficovh@ThinkPad-X270:~/mebo2024 $
  ```
* cona list muestra los paquetes instalados en el entorno 
  ```
   $ conda list
  ```
* En este punto ya puedes ejecutar jupyter notebook y abrir tus archivos

Enjoy.;-)
