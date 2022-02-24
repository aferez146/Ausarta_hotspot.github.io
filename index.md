**Bienvenido a la herramienta de gestión de usuarios de Wifi**

Con esta herramienta está pensada para la creación y gestión de usuarios para el uso de wifi en espacios como hoteles, bares, restaurantes, etc... aquí podrá conocer el funcionamiento básico y consultar posibles dudas.

### Conceptos Básicos

Para la gestión de usuarios wifi con la herramienta, tenemos tres apartados muy importantes que están dentro de la opción **Hotspot**:
1. Perfil del Usuario
2. Usuarios
3. Usuarios en línea

Estos tres apartados son los apartados principales que se usarán en el día a día de la herramienta:
![](https://raw.githubusercontent.com/aferez146/Gestion-HotSpot/gh-pages/gif_tablero.gif)

### Perfil de Usuario
![](https://raw.githubusercontent.com/aferez146/Gestion-HotSpot/gh-pages/gif_2.gif)
En esta sección se gestionan los diferentes perfiles de usuario con sus limitaciones,conexiones compartidas, ratio subida/bajada y el modo de expirar cada usuario. Las configuraciones más importantes, son:
1.  Nombre: Nombre del perfil a utilizar.
2.  Shared Users: Número de dispositivos máximos que se conectan al wifi en ese perfil.
3.  Rate limit: El límite de velocidad de subida y bajada en Mbps.
4.  Modo expirado: El modo en el que los usuarios caducan, pueden ser:

          +Remove: El usuario se elimina.
          
          +Notice: El usuario no se elimina
          
          +Record: Guarda el precio de cada sesión (si lo tuviera)
          

![image](https://raw.githubusercontent.com/aferez146/Gestion-HotSpot/gh-pages/perfil_usuario.PNG "Perfil_Usuarios")

por ejemplo si tenemos un hotel y queremos que las habitaciones tengan un límite de bajada de 5 Mb y otro de subida 10 Mb, también queremos que se conecten 10 dispositivos diferentes y queremos que el usuario se elimine al consumir su plazo, estas acciones se configuran en este menú. 

### Usuarios

En esta sección, se podrá agregar los usuarios que van a utilizar el wifi. Los usuarios se pueden añadir de dos maneras:
1. Añadir Usuario: Se añade los usuarios uno por uno, se deben rellenar los siguientes campos:
![image](https://raw.githubusercontent.com/aferez146/Gestion-HotSpot/gh-pages/ad_usser.PNG "Add_user")

          1.Nombre: Nombre del usuario del wifi.
          2.Password: Contraseña asignada para ese usuario.
          3.Perfil: El perfil creado que se ajusta a ese usuario.
          4.Límite de datos: Si queremos que el usuario tenga una cuota máxima de datos, por ejemplo 5 Gb.
          5.Comentario: Aqui se debe poner un comentario con la siguiente nomenclatura "-dd/mm/aaaa", por ejemplo "-24/02/2022", este campo nos será útil para poder imprimir los tickets wifi generados.
          



![](https://raw.githubusercontent.com/aferez146/Gestion-HotSpot/gh-pages/gif3.gif)



### Usuarios en línea
