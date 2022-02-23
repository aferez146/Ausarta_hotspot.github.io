**Bienvenido a la herramienta de gestión de usuarios de Wifi**

Con esta herramienta está pensada para la creación y gestión de usuarios para el uso de wifi en espacios como hoteles, bares, restaurantes, etc... aquí podrá conocer el funcionamiento básico y consultar posibles dudas.

### Conceptos Básicos

Para la gestión de usuarios wifi con la herramienta, tenemos tres apartados muy importantes que están dentro de la opción **Hotspot**:
1. Perfil del Usuario
2. Usuarios
3. Usuarios en línea

Estos tres apartados son los apartados principales que se usarán en el día a día de la herramienta:
![](https://raw.githubusercontent.com/aferez146/Gestion-HotSpot/gh-pages/gif_tablero.gif)

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Perfil de Usuario

En esta sección se gestionan los diferentes perfiles de usuario con sus limitaciones,conexiones compartidas, ratio subida/bajada y el modo de expirar cada usuario. Las configuraciones más importantes, son:
1.  Nombre: Nombre del perfil a utilizar.
2.  Shared Users: Número de dispositivos máximos que se conectan al wifi en ese perfil.
3.  Rate limit: El límite de velocidad de subida y bajada en Mbps.
4.  Modo expirado: El modo en el que los usuarios caducan, pueden ser:
          1.  Remove: El usuario se elimina.
          2.  Notice: El usuario no se elimina
          3.  Record: Guarda el precio de cada sesión (si lo tuviera)
          
por ejemplo si tenemos un hotel y queremos que las habitaciones tengan un límite de bajada de 5 Mb y otro de subida 10 Mb, también queremos que se conecten 10 dispositivos diferentes y queremos que el usuario se elimine al consumir su plazo, estas acciones se configuran en este menú. 

![image](https://raw.githubusercontent.com/aferez146/Gestion-HotSpot/gh-pages/perfil_usuario.PNG "Perfil_Usuarios")

### Usuarios

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.


### Usuarios en línea
