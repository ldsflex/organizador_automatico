# Organizador_automatico:

Organiza los archivos de la carpeta 'Descargas' cada vez que inicias sesión

El código pertenece al usuario Lengrube: https://github.com/Lengrube/ordenar_carpetas.git

He quitado los input del código para que el mismo sea autónomo y no necesite interactuar con el usuario.

Para que el mismo funcione deberá crear las siguientes subcarpetas en su carpeta de descargas: 'Audios', 'Comprimidos', 'Ejecutables', 'Imagenes', 'Otros', 'Texto', 'Videos'

Luego de crear las carpetas ejecute el código para comprobar que funciona correctamente.

El siguiente paso será crear un archivo .bat para que se ejecute el script de python cada vez que iniciamos sesión en nuestro sistema.

## Creando Archivo .bat:
  El archivo .bat es quien va a ejectur las lineas de comando en el cmd 
  
  Crear un archivo de texto con el bloc de notas que contenga tu *ruta al fichero Python.exe* seguido de la *ruta al script de python.* 
  
  Mi ejemplo: 
  
  ![Screenshot1](https://user-images.githubusercontent.com/80787415/137638290-64e89f6e-81ba-43a6-871d-870bd55795b4.PNG)

  Ahora guardamos el archivo .bat en la carpeta donde tenemos nuestro script (en mi caso tanto el .bat como el script de python se llaman 'main')
  
  Lo último que nos queda será automatizar la tarea con el 'Programador de tareas' de Windows.
  
  ## Programador de tareas:
  
  Abrimos el programa > 'Crear tarea...' > Aquí le ponemos un nombre y una descripción de lo que realizará el script.
  
  En la pestaña 'Desencadenadores' > 'Nuevo' > Y seleccionamos la opción 'Al iniciar sesión'
  
  Lo siguiente es ir a la pestaña 'Acciones' > 'Nueva' > En programa o script ponemos la ruta de nuestro archivo .bat 
  
  Pueden modificar la pestaña 'Condiciones' a su gusto.
  
  Eso sería todo, ahora cada vez que inicien sesión los archivos descargados se organizarán automaticamente.
  
  
  
