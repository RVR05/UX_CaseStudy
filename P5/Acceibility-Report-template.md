# Accesibility Report (template)

<img src="https://img.uxcel.com/cdn-cgi/image/format=auto/practices/wcag-principles-overview-1742315821212/a-1742315821212-2x.jpg" alt="usability Download png" style="height:200px" />

## 1. Ficha Técnica del Informe

Antes de entrar en detalles, define el alcance.

- **Nombre del proyecto:** Diseño B DIU3.ColesterMax.
- **Normativa de referencia:** WCAG 2.1, Nivel AA.
- **Herramientas utilizadas:** Lighthouse, WAVE.
- **Fecha de la auditoría:** 31 de Mayo del 2026.


## 2. Puntuaciones Globales (Métricas Automáticas)

- **Lighthouse Accessibility Score:** 77/100

Lighthouse ha puntuado con un 77 sobre 100 para el prototipo de Goiko Finder en la categoria de Accesibilidad, colocando al prototipo Goiko Finder en la zona amarilla, lo que indica que cumple con una parte significativa de los estandares para que las personas con discapacidades visuales, motoras o cognitivas puedan navegar sin barreras. Esto se traduce en que el sitio cuenta con una estructura, un uso correcto de componentes. Sin embargo hay cosas que impiden llegar a la zona verde, como la ausencia de textos alternativos, lo que impide a los usuarios con discapacidad visual del contenido.
 
- **WAVE Summary:** Número de errores críticos, alertas y errores de contraste.

<img width="365" height="810" alt="image" src="https://github.com/user-attachments/assets/3c9e9d24-48a4-479d-8bfa-30e5d32dc13f" />

* Numero de errores criticos: 0
* Alertas: 4
* Errores de contraste: 0
* AIM Score 9.9 / 10

Tras el analisis en WAVE, Goiko Finder obtiene un 9,9 sobre 10, lo que indica una gran excelencia. La herramienta no ha detectado nignun error critnico ni errores de contraste, lo que indica que se hace un buen diseño de imagenes y elementos visuales. No obstante si ha detectado 4 alertas por la ausencia de encabezados, la falta de regiones de paginas definidas y la presencia de un elemento <noscript>. 


## 3. Análisis por Principios (POUR)

Para que el informe sea profesional, agrupa los fallos según los 4 principios de la accesibilidad:

<img src="https://cdn.sanity.io/images/r115idoc/production/e745ae232e5e6760c1392354021aed4eecc4627d-1920x1080.png" alt="usability Download png" style="height:200px" />

### A. Perceptible

- **Hallazgo:** "Falta de texto alternativo en imágenes decorativas".
- **Impacto:** Los usuarios con discapacidad visual no reciben contexto de la imagen.
- **Solución:** Añadir atributo `alt=""` o una descripción funcional.



### B. Operable

- **Hallazgo:** "Indicador de foco invisible en el menú".
- **Impacto:** Un usuario que navega con teclado no sabe dónde está situado.
- **Solución:** Definir un estilo CSS para `:focus` con alto contraste.



### C. Comprensible

- **Hallazgo:** "Los mensajes de error de formulario no son claros".
- **Impacto:** El usuario no sabe cómo corregir el campo para avanzar.
- **Solución:** Vincular el error con el input mediante `aria-describedby`.



### D. Robusto

- **Hallazgo:** "IDs duplicados en el código HTML".
- **Impacto:** Los lectores de pantalla pueden saltarse contenido o confundir elementos.
- **Solución:** Validar el HTML y asegurar identificadores únicos.



El informe deberá organizar los resultados en esta 4 categorias: 

| **Categoría**    | **Qué analizar (Ejemplos)**                                  |
| ---------------- | ------------------------------------------------------------ |
| **Perceptible**  | Contraste de colores, texto alternativo en imágenes (`alt`), subtítulos. |
| **Operable**     | Navegación por teclado, tiempo suficiente para leer, evitar destellos. |
| **Comprensible** | Idioma de la página definido, formularios claros, errores fáciles de corregir. |
| **Robusto**      | Código limpio (HTML válido) para que los lectores de pantalla funcionen. |

Un ejemplo de resultado sería: 

* **Perceptible:**  
  * Error detectado: **Falta de contraste en el botón de reservar**.
  * **Criterio WCAG incumplido:** "Criterio 1.4.3 - Contraste mínimo".
  * **Impacto:** "Los usuarios con visión baja no pueden identificar la acción principal".
  * **Recomendación de mejora:** "Cambiar el color del texto de gris claro a negro (#000000)".

El informe debería dar una **valoracion general de accesibilidad** e incluir al menos **2-3 resultados identificados y clasificados adecuadamente**. 





## 4. Tabla de Hallazgos y Prioridades

Organiza los errores técnicos de forma que el equipo sepa qué arreglar primero.

| **ID**     | **Prioridad** | **Criterio WCAG**          | **Error detectado**                  | **Recomendación Técnica**     |
| ---------- | ------------- | -------------------------- | ------------------------------------ | ----------------------------- |
| **ACC-01** | **Crítica**   | 1.4.3 Contraste            | Texto gris sobre fondo blanco.       | Cambiar a color #333333.      |
| **ACC-02** | **Alta**      | 1.1.1 Contenido no textual | Icono de "Cerrar" sin etiqueta.      | Añadir `aria-label="Cerrar"`. |
| **ACC-03** | **Media**     | 2.4.1 Evitar bloques       | No hay enlace "Saltar al contenido". | Implementar un *Skip Link*.   |







## 5. Conclusiones y Declaración de Conformidad

Resume el estado actual:

- **¿Es el sitio accesible?** (Ej: "El sitio cumple parcialmente con el nivel AA, pero presenta barreras críticas en el proceso de compra").
- **Próximos pasos:** Lista de 3 acciones inmediatas para mejorar la puntuación.













