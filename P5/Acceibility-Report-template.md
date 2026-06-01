# Accesibility Report (template)

<img src="https://img.uxcel.com/cdn-cgi/image/format=auto/practices/wcag-principles-overview-1742315821212/a-1742315821212-2x.jpg" alt="usability Download png" style="height:200px" />

## 1. Ficha Técnica del Informe

Antes de entrar en detalles, define el alcance.

- **Nombre del proyecto:** Diseño B DIU3.ColesterMax.
- **Normativa de referencia:** WCAG 2.1, Nivel AA, Nivel A
- **Herramientas utilizadas:** Lighthouse, WAVE.
- **Fecha de la auditoría:** 31 de Mayo del 2026.


## 2. Puntuaciones Globales (Métricas Automáticas)

**Lighthouse Accessibility Score:** 77/100

Lighthouse ha puntuado con un 77 sobre 100 para el prototipo de Goiko Finder en la categoria de Accesibilidad, colocando al prototipo Goiko Finder en la zona amarilla, lo que indica que cumple con una parte significativa de los estandares para que las personas con discapacidades visuales, motoras o cognitivas puedan navegar sin barreras. Esto se traduce en que el sitio cuenta con una estructura, un uso correcto de componentes. Sin embargo hay cosas que impiden llegar a la zona verde, como la ausencia de textos alternativos, lo que impide a los usuarios con discapacidad visual del contenido.
 
**WAVE Summary:** Número de errores críticos, alertas y errores de contraste.

<img width="365" height="810" alt="image" src="https://github.com/user-attachments/assets/3c9e9d24-48a4-479d-8bfa-30e5d32dc13f" />

- Numero de errores criticos: 0
- Alertas: 4
- Errores de contraste: 0
- AIM Score 9.9 / 10

Tras el analisis en WAVE, Goiko Finder obtiene un 9,9 sobre 10, lo que indica una gran excelencia. La herramienta no ha detectado nignun error critnico ni errores de contraste, lo que indica que se hace un buen diseño de imagenes y elementos visuales. No obstante si ha detectado 4 alertas por la ausencia de encabezados, la falta de regiones de paginas definidas y la presencia de un elemento <noscript>. 


## 3. Análisis por Principios (POUR)

Para que el informe sea profesional, agrupa los fallos según los 4 principios de la accesibilidad:

<img src="https://cdn.sanity.io/images/r115idoc/production/e745ae232e5e6760c1392354021aed4eecc4627d-1920x1080.png" alt="usability Download png" style="height:200px" />

### A. Perceptible

- **Hallazgo:** "Ausencia de descripciones en tarjetas visuales. El prototipo utiliza tarjetas con imagenes de hamburguesas y restauranes. Sin embargo la informacion clae (precio, alergenos, tiempo de espera), se presenta unicamente con iconos y etiquetas pequeñas, sin que exista una alternativa. Asi mismo la págna carece de estructura de encabezados, confirmado por WAVE con la alerta No heading structure". Criterio WCAG:1.3.1 (Nivel A) y 1.3.3 (Nivel AA)
- **Impacto:** Un usuario con discapacidad visual recibe la información de cada tarjeta sin contexto jerárquico sin saber si el dato que escucha corresponde a un precio, una distancia o un tiempo de espera,
- **Solución:** Complementar cada icono informativo con un aria-label que describa explícitamente su significado por ejemplo aria-label="Tiempo de espera: 15 minutos"



### B. Operable

- **Hallazgo:** "Ausencia de regiones de página. WAVE alerta de la ausencia de <header>, <main>, <nav>, <footer>. Al ser una SPA React construida con <div> anidados sin roles ARIA, los usuarios de teclado o lector de pantalla no pueden saltar directamente a la sección que les interesa y deben recorrer la página entera elemento a elemento.". Criterio WCAG: 2.4.1 Evitar Bloques (Nivel A) y 2.4.3 (Nivel AA)
- **Impacto:** Un usuario que navega con teclado debe pulsar Tab a través de todos los elementos antes de alcanzar el contenido principal, lo que resulta frustrante en una página con muchos elementos interactivos como tarjetas y botones.
- **Solución:** Añadir <main>, <nav> y <footer> semánticos en los contenedores e implementar un skip link como primer elemento del DOM.

---

- **Hallazgo:** "Enlaces que redirigen fuera del prototipo sin advertencia. Algunos botones llevan al usuario a paginas externas, como la web oficial de Goiko, sin informarle de que abandonará la aplicación. Esto ocurre por ejemplo en el boton de reserva, llevando al usuario directamente a la web real de Goiko.". Criterio WCAG: 2.4.4 Propósito de los enlaces (Nivel AA)
- **Impacto:** El usuario puede desorientarse al ser trasladado a un contexto completamente diferente sin haberlo esperado, rompiendo el flujo de navegación y generando confusión sobre donde se encuentra.
- **Solución:** Indicar explícitamente en la etiqueta del enlace que abre una página externa o bien simular la accion de reserva dentro del propio prototipo para mantener la coherencia de la experiencia.



### C. Comprensible

- **Hallazgo:** "Ausencia de encabezados. WAVE confirma que la página no utiliza una jerarquía de encabezados `<h1>`, `<h2>`, `<h3>`. El contenido está presentado con estilos visuales sin semántica, por lo que secciones como la carta, los restaurantes o las ofertas no están bien diferenciadas a nivel estructural." Criterio WCAG: 1.3.1 (Nivel A)
- **Impacto:** Los lectores de pantalla no pueden ofrecer al usuario un índice ni permitirle saltar entre bloques. Un usuario con discapacidad visual escucha el contenido como una secuencia plana sin poder distinguir dónde termina una sección y empieza otra.
- **Solución:** Establecer un `<h1>` único por vista y `<h2>` para cada sección principal como Restaurantes, Carta u Ofertas, asegurando que el orden sea siempre descendente y no se salten niveles.



### D. Robusto

- **Hallazgo:** "Elemento <noscript> y ausencia de roles ARIA, WAVE reporta 0 elementos ARIA. Al estar generada con Figma Make, los componentes interactivos como botones, filtros y tarjetas no exponen su tipo ni estado" Criterio WCAG: 4.1.2 (Nivel A)
- **Impacto:** Los lectores de pantalla no pueden identificar el rol de los elementos interactivos, haciendo la interfaz opaca para usuarios con discapacidad visual. Un botón de filtro o una tarjeta de restaurante son indistinguibles entre sí, lo que impide una navegacion autónoma 
- **Solución:** Añadir role, aria-label donde corresponda en los componentes React, en las tarjetas interactivas, y proporcionar un mensaje de fallback útil en el <noscript>.





## 4. Tabla de Hallazgos y Prioridades

Organiza los errores técnicos de forma que el equipo sepa qué arreglar primero.



| **ID**     | **Prioridad** | **Criterio WCAG**                        | **Error detectado** | **Recomendación Técnica** |
| ---------- | ------------- | ---------------------------------------- | ----------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| **ACC-01** | **Alta**      | 1.3.1 Informacion y relaciones (Nivel A) | Iconos sin etiqueta textual en tarjetas (precio, alergenos, distancia)                                                                                                    | Añadir `aria-label` a cada icono` |
| **ACC-02** | **Alta**      | 2.4.1 Evitar bloques (Nivel A)           | Ausencia de etiquetas semanticas `<main>`, `<nav>`, `<footer>`| Añadir roles semánticos e implementar un *skip link* como primer elemento del DOM |
| **ACC-03** | **Alta**      | 2.4.4 Proposito de los enlaces (Nivel AA) | Boton de reserva redirige a la webde Goiko sin advertencia | Añadir `aria-label="Reservar abre en nueva pestaña"` o simular la reserva dentro |
| **ACC-04** | **Media**     | 1.3.1 Informacion y relaciones (Nivel A) | Sin jerarquia de encabezados `<h1>`, `<h2>`, `<h3>` en ninguna seccionn | Establecer `<h1>` y `<h2>` para cada sección principal |
| **ACC-05** | **Media** | 4.1.2 Nombre, funcion (Nivel A) | 0 elementos ARIA en toda la aplicación, componentes sin rol semantico | Añadir `role`, `aria-label` y `aria-expanded` en botones y tarjetas React |




## 5. Conclusiones y Declaración de Conformidad

Resume el estado actual:

- **¿Es el sitio accesible?**

El protitpo Goiko Finder cumple de forma parcial con el nivel AA de WCAG 2.1. Los resultados de las herramientas automatizadas son positivos, 77/100 en Lighthouse y 9.9/10 en AIM Score en WAVE sin errores criticos. A pesar de que esto nos de indicios de una web solida, la ausencia de etiquetas semánticas, la falta de jerarquias, los encales que redirigen sin ningun tipo de advertencia a páginas externa y la ausencia total de roles ARIA en los componentes, suponen barreras para usuarios que dependen de tecnologias asistidas.

- **Próximos pasos:**

1. Incorporar aria-label en todos los iconos informativos de las diversas tarjetas (precio, alergenos, tiempo...) y establecer a traves de `<h1>` y `<h2>` una jerarquia por secciones. Con estas dos mejoras estariamos abordand los ACC-01 y ACC-04

2. Añadir etiquetas semántcias a los contenedores del layaut (`<nav>` y `<footer>`) e implementar un *skip link* para permitir a los usuarios que naveguen solo por teclado ir directamente al contenido principal sin teenr que pasar por todos los elementos previos. Aqui resolvemos el ACC-02.

3. Corregir la presencia de botones con enlaces a páginas externa, como por ejemplo el de reaizar una reserva, añadiendo o una explicación de que el usuario va a abanonar el prototipo para acceder a otra página o directamente no tener este tipo de enlaces y hacer esas tareas dentro del prototipo.












