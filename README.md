# Odoo
Comandos odoo :

-- Ps - servicios


-- netstat, que es?: netstat es un programa dirigido con órdenes ejecutadas en la línea de comandos que entrega estadísticas básicas sobre la totalidad de las actividades de red.

-- Unos ejemplos de los comandos de netstat:

  - El comando mas utilizado: netstat -a. El cual enumera  los puertos abiertos
  - netstat -e : Estadísticas de interfaz (paquetes de datos recibidos y enviados, etc.)
  - netstat -i : Abrir el menú general de netstat
  - netstat -n : Visualización numérica de direcciones y números de puerto


--Comandos docker
   - docker compose up. Es la manera de ejecutar el contenedor 
   - docker compose down. Sirve para borrar el contenedor
   - docker compose stop. Sirve parar el contenedor
   - docker compose start. Sirve para poner en marcha el contenedor de nuevo una vez este parado

--Instalacion de odoo:
   
   - Paso 1: configurar el fichero .yml y conectarlo a la base de datos,para eso debereis crear una carpeta,   donde vayas hacer el projecto, y dentro crear el projecto de paython, y el punto yml tambien dentro con la siguiente configuracion. 
  
   ![Captura de pantalla de 2023-01-20 12-43-57](https://user-images.githubusercontent.com/91197896/213687904-e7eaf73b-5c1b-464a-a9e9-469746497724.png)
   
   - Paso 2: el siguiente paso consiste en la conexion a la base de datos postgres, para ello en el yml como se    muestra en la captura anterior, se ha configurado tales datos como el puerto el usuario la contraseña etc. 
   a continuacion, mostrare captura de donde acceder.
   
   ![Captura de pantalla de 2023-01-20 13-02-54](https://user-images.githubusercontent.com/91197896/213690889-a46cf2a0-a858-4aac-b1a1-5a4a7b0687b8.png)
   
   - Una vez accedamos a esa zona selecionaremos en el + la base de datos postgres psql, os saldra una pantalla de la singuiente manera donde rellenar con los datos necesarios.
   
   
   ![Captura de pantalla de 2023-01-20 13-15-15](https://user-images.githubusercontent.com/91197896/213693075-92001239-1290-4e5b-89ab-d43d8d0861dd.png)
    
    
   - Paso 3: Tras esto con los comandos que tenemos arriba anotados iniciamos el contenedor y procedemos a isntalar odoo, siguiendo todos los paso pertinentes

    

   
   
  
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
