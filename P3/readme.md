# DIU - Practica 3, entregables

- Moodboard (diseño visual + logotipo)   
- Landing Page
- Mockup: LAYOUT HI-FI
- Publicación del Case Study


### 3.a Moodboard
![Método UX](img/moodboard.png)
-----

El logotipo es el siguiente 

<img width="329" height="314" alt="logo" src="https://github.com/user-attachments/assets/02cae642-3dda-4bac-82b7-ea811dfbc022" />


[Moodboard25 (Copia).pdf](https://github.com/user-attachments/files/27574420/Moodboard25.Copia.pdf)



### 3.b Landing Page
![Método UX](img/landing-page.png) 
----

<img width="1850" height="4419" alt="landing page" src="https://github.com/user-attachments/assets/553bb3f9-22a0-4faf-a2d0-24c61e86a16a" />


El landing page es la carta de presentación de nuestro local. El objetivo principal, lo que queremos que deje bien claro, son nuestros valores y quienes somos, qué nos diferencia. Luego hemos aportado contenido secundario, como una bienvenida o invitación a ver el menú, a realizar una reserva así como información varia sobre el local (horarios...).

Este es el enlace de figma para acceder al recurso interactivo: https://slash-edit-31597285.figma.site


### 3.c Guidelines
![Método UX](img/guidelines.png) 
----

Para crear los guidelines nos hemos valido de dos cosas:
  - Tokes y variables gloables, tanto para la paleta de colores, como para configuraciones de texto, nos facilitarán pues la modificacion simultanea de un atributo de un conjunto de componentes
    facilitando el trabajo enormemente.
  - Hemos utilizado el principio del atomic design, diseñando primeramente los componentes "átomos" luego moleculas, organismos... hasta llegar a formar un patrón.

[Enlace al figma con los marcos y componentes](https://www.figma.com/design/j8LniI2NHwNljPANwfE8wN/Sin-t%C3%ADtulo?node-id=0-1&t=qTN9bh70es4QwFnT-1)

Estos son nuestros componentes:

<img width="1685" height="1024" alt="componentes atomic design" src="https://github.com/user-attachments/assets/34936fd6-19b2-4dff-a84e-dedac0cc2413" />






En cuanto a los foundations tenemos:

- Paleta: se ha definido una rampa cromática completa incluyendo estados de interaccion hover y active tanto para variantes claras como oscuras

- Tipografia: se ha aplicado una jerarquia tipografica clara visible en todos los componenes

- Grid: Se ha utilizado AutoLayout de Figma para estructurar todos los componentes con un sistema de espaciado consistente


Los atomos: 

- Botón: Se han creado dos variantes mediante la función de variantes de Figma: botón y boton_alternativo. Ambos incluyen tres estados de tamaño o jerarquía, lo que permite reutilizarlos en contextos distintos

- Inputs de formulario: Átomos de campo de texto reutilizados en los formularios de contacto y reserva, con etiqueta (label) y campo de valor (value).
  
- Iconos y Redes Sociales: conjunto de iconos atómicos para las redes sociales (Facebook, X, Instagram, YouTube). También se usan iconos funcionales de teléfono, ubicación y email en la sección de información directa.
  
- Avatar: Átomo de perfil de usuario presente de forma consistente en el extremo derecho del header en todas las páginas

Las moleculas: 

- Plato: Molécula compuesta por imagen del plato, nombre y descripción. Se reutiliza de forma sistemática en la página de Carta.

- Card de reseña: Molécula formada por el átomo de estrellas, un título y el cuerpo de la reseña. Se despliegan tres instancias en la página de inicio con valoraciones reales.
  
- Moléculas de lista con checkboxes para filtrar los platos de la carta por categoría (Ramen, Entrantes, Bebidas, Postres) y por atributo dietético (Picante, Sin gluten, Vegano, Sin F.secos).

- Componente de Contacto Molécula que agrupa los datos de contacto directo: teléfono, ubicación y email.
  
- Componente de Fechas: Molécula de selección de fecha y hora
  
- Carrusel: Molécula de presentación visual con imagen destacada utilizada en la página de inicio para mostrar algunos platos del menú.


Los organimos:

- Header / Navbar: Organismo que integra el logotipo, el nombre del restaurante, la barra de navegación con cinco destinos (Inicio, ¿Quiénes somos?, Contacto, Carta, Reserva) y el avatar de usuario. Se repite de forma idéntica en todas las páginas.
  
- Footer: Organismo compuesto por los iconos de redes sociales centrados, una línea divisoria y tres enlaces textuales (Ayuda, Copyright, Preguntas frecuentes) distribuidos en los extremos. Presente en todas las páginas.


- Hero Section: Organismo de portada que combina la imagen de fondo del restaurante, el carrusel de platos a la izquierda, el titular principal, el subtexto descriptivo y el botón "Contempla Nuestro Menú"
  
- Formulario de contacto: Organismo de recogida de datos formado por (Nombre, Apellidos, Email, Mensaje) y el botón de envío, con encabezado "Déjanos tu mensaje".
  
- Sección de Carta: Organismo que combina las cards de platos en una cuadrícula de dos columnas, las imágenes decorativas laterales y los paneles de Categorías y Filtros.


Los patrones: 

- Página de Reserva: Patrón de flujo de reserva que ofrece dos caminos al usuario: identificarse y seleccionar fecha/hora directamente, o rellenar un formulario de solicitud sin necesidad de cuenta. Esto responde a distintos perfiles de usuario.

- Página de Contacto: Patrón de contacto multicanal que combina el formulario de mensaje, la información directa (teléfono, dirección, email), el mapa de ubicación y los horarios.
  
- Página ¿Quiénes somos?: Patrón de presentación de marca que alterna bloques de texto con imágenes del local y del producto, construyendo la narrativa e identidad del restaurante.


### 3.d Mockup
![Método UX](img/mockup.png) 
----


<img width="1440" height="1667" alt="Inicio (1)" src="https://github.com/user-attachments/assets/d9bcbe73-164c-48d4-8fa0-ba7593513842" />

<img width="1440" height="1184" alt="Quienes somos" src="https://github.com/user-attachments/assets/dd32e3ef-762c-4efd-b78a-7052ae246d48" />



<img width="1440" height="1024" alt="Contacto" src="https://github.com/user-attachments/assets/2c4ea3f9-444b-4cf2-ad0e-b8e93a54c175" />


<img width="1440" height="1024" alt="Carta" src="https://github.com/user-attachments/assets/0224cc98-639a-4c9d-b4e9-81ebcaa38a3e" />


<img width="1440" height="1223" alt="Reservas" src="https://github.com/user-attachments/assets/7ce4ffa9-8981-484f-bc70-c705206dfa7e" />

[Acceso al recurso interactivo](https://www.figma.com/proto/j8LniI2NHwNljPANwfE8wN/Sin-t%C3%ADtulo?node-id=40-331&t=JKTLs73cPNA4EQrb-1&scaling=min-zoom&content-scaling=fixed&page-id=35%3A3522)


<br>

