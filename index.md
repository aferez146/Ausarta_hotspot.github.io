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
          
2. Generar Voucher: Similar al anterior, en este caso sirve para añadir bloques de usuarios:
![image](https://raw.githubusercontent.com/aferez146/Gestion-HotSpot/gh-pages/ad_voucher.PNG "Add_voucher")

          1.Cantidad: Cantidad de usuarios que se van a crear.
          2.Modo usuarios: Si el usuario a crear tiene usuario y contraseña o si el usuario es igual a la contraseña.
          3.Longitud del código: Longitud del nombre del usuario a crear.
          4.Prefijo: El prefijo que contendra el usuario, por ejemplo "User".
          5.Caracteres: Los caracteres que se rellenan después del prefijo, es una secuencia aleatoria de letras o números y letras.
          6.Perfil: El perfil creado que se ajusta a ese usuario.
          7.Límite de datos: Si queremos que el usuario tenga una cuota máxima de datos, por ejemplo 5 Gb.
          8.Comentario: Aqui se debe poner un comentario con la siguiente nomenclatura "-dd/mm/aaaa", por ejemplo "-24/02/2022", este campo nos será útil para poder imprimir los tickets wifi generados.

Ejemplo de uso:


![](https://github.com/aferez146/Gestion-HotSpot/blob/gh-pages/gif5.gif?raw=true.gif)



### Imprimir Tickets
Para imprimir tickets, en primer lugar se debe filtrar por el comentario hecho anteriormente, una vez filtrado por comentario, se puede imprimir el ticket de tres maneras diferentes:
1. Por defecto: Se imprime el ticket sin código QR y con una tarjeta que se puede personalizar.
2. QR: Se imprime una tarjeta que se puede personalizar con un código QR.
3. Small: Se imprimen las credenciales del wifi en texto plano, sin tarjeta.

Ejemplo de uso:
![](https://github.com/aferez146/Gestion-HotSpot/blob/gh-pages/gif5.gif?raw=true.gif)

