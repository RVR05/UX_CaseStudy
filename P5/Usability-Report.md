# Usability Report



<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRF017nhV-TFmNER2OM8UbXtdN6xwAKBYrv0i6onNfKu6Yn0BV0RK6aiOroeXl73LSY-B0&usqp=CAU" alt="usability Download png" style="height:150px" />

### Evaluación de usabilidad del proyecto  [NOMBRE PROYECTO]

31/05/2026

[img Proyecto]

[Enlace a GITHUB del proyecto](https://github.com/DIUGrupoColesterMax/UX_CaseStudyColesterMax)

### Realizado por:  

Informe realizado por Equipo DIU1.LosPsicomotronic




## 1 RESUMEN EJECUTIVO  (Executive Summary)

### Objetivo:

El objetivo de nuestro usability report es la evaluación de la usabilidad y accesibilidad del prototipo web proporcionado por DIU3.ColesterMax. En este informe se recopilan tanto datos numéricos (como las puntuaciones del test SUS) como comportamientos visuales (mediante el Eye Tracking) para detectar fallos de diseño, problemas de navegación o barreras de accesibilidad.

### Metodología:

Para realizar este estudio, la metodología se basa en una combinación de técnicas de evaluación de usabilidad. En concreto, se han utilizado tres fundamentales:

  - Test A/B (Prueba comparativa de tareas): Se han diseñado 2 grupos divesos de participantes (5 en cada uno) dedicados a comparar este proyecto con otros (como el nuestro)
    
  - Cuestionario SUS: Es una herramienta cuantitativa estándar de 10 preguntas. Los usuarios rellenan el test justo al terminar las tareas, luego los resultados pasan por un algoritmo y se calcula la puntuación SUS, que nos permite transformar esa subjetividad en una puntuación numérica.

  - Análisis de Eye Tracking (usando la herramienta GazeMapping): Es una prueba que registra de forma visual el comportamiento real del usuario. Permite obtener mapas de calor para comprobar qué elementos llaman la atención, cuáles se ignoran por completo...

### Principales Hallazgos:

  - El primero y más importante es que la mayoría de usuarios consideran que la página es demasiado grande, tiene demasiados elementos, o se distraen con demasiada facilidad. Lo que difilcuta la navegación y reduce la accesibilidad en personas con problemas como TDAH...
   
  - Otro hallazgo fue que con la sobrecarga de la página muchos elementos pasaban desapercibidos, zonas como el mapa, algunas ofertas... O el header, que apenas se percibió

  - Por último un punto que se ha valorado como muy crítico por parte de los usuarios aunque el test o el heatmap no lo refleje lo suficientemente bien, es que la pagina de reservas los llevaba a otro sitio web, con un dominio y estéticas diferentes, lo que aunque no impedía la realización de la tarea, si que los confundía.

### Resultado Global:

La puntuación final obtenida para este proyecto en el cuestionario SUS es de 72.25. Esta refleja que pese a que la página es bastante buena y los usuarios son capaces de navegar con facilidad y completar las diversas tareas, sin embargo, quedan mejoras por hacer, priorizar la presentación de las operaciones funcionales, para que gente mayor pueda verlas antes o reducir el tamaño de la pagina para que se quede más simplificado y directo.


## 2. Metodología y Reclutamiento

### Perfil de los participantes:

Los perfiles de los participantes escogidos son muy variados, seleccionando tipo de participantes, asegurando así diversidad en edad, género y nivel de experiencia tecnológica. Desde empleadas del hogar con edad avanzada, hasta jóvenes estudiantes.

### Escenario de la prueba:

Los participantes interactuaron con el prototipo de Goiko Finder completando dos tareas:

  - Prueba 1 — Consulta de carta y búsqueda de información sobre alérgenos: el usuario accede a la carta del restaurante y localiza la información de alérgenos. Evalúa visibilidad y accesibilidad de esta sección.
    
  - Prueba 2 — Realizar una reserva: el usuario localiza el apartado de reservas y completa el formulario. Evalúa la facilidad para encontrar la sección y la fluidez del proceso.
    
### Herramientas:

Las herramientas utilizadas se listan a continuación:

  - GazeMapping: plataforma de Eye Tracking basada en webcam para registro de movimientos oculares y generación de mapas de calor.
  - Tally: recogida del cuestionario SUS digital, aunque no lo usamos directamente, nos basamos en el.
  - Excel: cálculo y verificación de las puntuaciones SUS mediante el algoritmo estándar.

## 3. Resultados del Cuestionario SUS (Datos Cuantitativos)

[Aquí se muestran datos del análisis multivariable de SUS] 

- **Comparativa A vs. B:** Un gráfico de barras comparando la puntuación final de ambos diseños.
- **Desglose por ítems:** Identifica qué preguntas del SUS tuvieron peor puntuación (por ejemplo, si la pregunta 2 sobre "complejidad" fue muy alta en el Diseño B).

Valoración numérica del SUS - 


## 4. Análisis de Eye Tracking (Datos Biométricos)

[Presenta la evidencia visual del comportamiento del usuario]

- **Heatmaps (Mapas de calor):** Incluye las capturas de GazeMapping. Comenta si los usuarios miraron los **POI** (Puntos de Interés) definidos.
- **Zonas de Silencio:** Identifica elementos importantes que fueron totalmente ignorados.
- **Hallazgo clave:** Ejemplo: "El 80% de los usuarios ignoró el botón de CTA debido a su ubicación en el margen inferior".

## 5. Auditoría de Accesibilidad

Sintetiza el cumplimiento técnico y normativo.

- **Puntuación Automática:** (Lighthouse/WAVE).
- **Principales barreras:** Lista los errores críticos (contraste, falta de etiquetas, etc.) y cómo afectan a los usuarios con discapacidad.

## 6. Conclusiones y Recomendaciones (Actionable Insights)

No te limites a decir qué está mal; di cómo arreglarlo. Clasifica las recomendaciones por prioridad:

| **Prioridad**      | **Hallazgo**                                                 | **Recomendación de Mejora**                                  |
| ------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| **Alta (Crítica)** | Ej. El SUS indica alta complejidad y el Eye Tracking muestra confusión en el menú. | Simplificar la arquitectura de información y aumentar el tamaño de las fuentes. |
| **Media**          | Ej. Los usuarios no ven el botón de registro rápidamente.        | Cambiar el color del CTA a uno de mayor contraste según WCAG. |
| **Baja**           | Ej. El logo no redirige a la home.                               | Añadir el enlace estándar al logotipo en la cabecera.        |



