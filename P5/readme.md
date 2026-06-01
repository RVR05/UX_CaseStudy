## Practica 5: 

### 5.a Reclutamiento de usuarios 
![Método UX](img/usability-testing.png)
-----


Nuestro caso B pertenece al grupo DIU3.ColesterMax, cuyo repositorio tiene el siguiente enlace https://github.com/DIUGrupoColesterMax/UX_CaseStudyColesterMax. Su caso se trata sobre el estudio de la experiencia de usuario en plataformas relacionadas con restaurantes de tipo burger.


| Usuarios | Sexo/Edad     | Ocupación   |  Exp.TIC    | Caso
| ------------- | -------- | ----------- | ----------- | ----
| P1  | H / 21   | Estudiante  | Alta    | A 
| P2  | H / 21   | Estudiante  | Alta    | A 
| P3  | H / 21   | Estudiante  | Alta    | A
| P4  | M / 26   | Activos  | Media/Alta   | B 
| P5  | M / 50   | Estudiante  | Media   | B 
| P6  | H / 26   | Activos  | Media/Alta   | B 
| P7  | M / 55   | Activos     | Baja    | B 
| P8  | H / 28   | Activos  | Alta   | B 
| P9  | H / 67   | Jubilado  | Baja   | A 
| P10 | M / 41   | Activos  | Media   | A 



### 5.b Diseño de las pruebas 
![Método UX](img/usability-testing.png) 
-----

Para la evaluacion de la propuesta realizaremos dos pruebas de usabilidad, en ellas los participantes deberan completar una serie de tareas. El obejtivo es ver como interactuan con la interfáz.

Prueba 1: Consulta de carta y busqueda de informacion sobre alérgenos

En esta prueva el usuario debera acceder a la carta del restaurante y posteriormente debera comprobar si los producto contienen alguna informacíon de los alérgenos o si hay alguna página donde haya información sobre estos. El objetivo es evaluar que la carta y la consulta de los alérgenos es visible y facil.

Prueba 2: Realizar una reserva

En esta tarea el usuario debera acceder al apartado de reservas y completar el formulario correspondiente. Aqui valoramos la faclidad para encontrar la seccion de reservas, comprobar la facilidad para realizarla y ver si el proceso de reserva resulta rapido


### 5.c Cuestionario SUS
![Método UX](img/Survey.png) 
----

Para la evalación SUS, vamos a utilizar la siguiente plantilla, donde 1 implica totalmente en desacuerdo y 5 totalmente de acuerdo. Se valoran puntos como el agrado con la web, si la volvería a usar, la facilidad con la que la usa, si estaba comodo el usuario... Se ha utilizado excel, se ha rellenado a mano el cuestionario y se han obtenido los valores utilizando funciones de excel para calcular los valores. El formato es el siguiente:

---

| #  | PREGUNTAS | 1 | 2 | 3 | 4 | 5 |
|----|-----------|:-:|:-:|:-:|:-:|:-:|
| 1  | Creo que me gustará visitar con frecuencia este website | | | | | |
| 2  | Encontré el website innecesariamente complejo | | | | | |
| 3  | Pensé que era fácil utilizar este website | | | | | |
| 4  | Creo que necesitaría del apoyo de un experto para recorrer el website | | | | | |
| 5  | Encontré las funciones del website bastante bien integradas | | | | | |
| 6  | Pensé que había demasiada inconsistencia en el website | | | | | |
| 7  | Imagino que la mayoría de las personas aprenderían muy rápidamente a utilizar el website | | | | | |
| 8  | Encontré el website muy grande al recorrerlo | | | | | |
| 9  | Me sentí muy confiado en el manejo del website | | | | | |
| 10 | Necesito aprender muchas cosas antes de manejarse en el website | | | | | |

---

Como nuestros usuarios deben realizar dos tareas en la web, tras cada una de estas rellenan un cuestionario SUS de forma que en total saldran 20 cuestionarios.

Tras la realización de las pruebas se han obtenido los siguientes resultados individuales:

#### Resultados Individuales del Cuestionario SUS

Para obtener los resultados se ha hecho uso del algoritmo de cálculo estandarizado de la escala SUS visto en clase y contemplado en diversas guias:

  - Suma todos los impares y luego a la suma restale 1 por cada pregunta impar
  - Multiplica 5 por cada pregunta par y a ello restale la sumatoria de los pares
  - Para finalizar suma ambos resultados y multiplica por 2.5, con ello obtienes un valor sobre 100, que no es un porcentaje pero indica bastante bien el estado/usabilidad de la pagina

A continuación se detallan las respuestas numéricas limpias (escala del 1 al 5) obtenidas para cada una de las 10 preguntas del cuestionario System Usability Scale (SUS), junto con la puntuación final calculada para cada participante.

| Caso | Participante | Q1 | Q2 | Q3 | Q4 | Q5 | Q6 | Q7 | Q8 | Q9 | Q10 | Puntuación SUS |
| :---: | :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| **Caso A** | P1 - 1 | 5 | 1 | 5 | 1 | 5 | 1 | 5 | 1 | 5 | 1 | **100.0** |
| **Caso A** | P1 - 2 | 5 | 1 | 5 | 1 | 5 | 1 | 5 | 1 | 5 | 1 | **100.0** |
| **Caso A** | P2 - 1 | 5 | 1 | 5 | 1 | 5 | 1 | 5 | 1 | 5 | 1 | **100.0** |
| **Caso A** | P2 - 2 | 5 | 1 | 5 | 1 | 5 | 1 | 5 | 1 | 5 | 1 | **100.0** |
| **Caso A** | P3 - 1 | 5 | 1 | 5 | 2 | 5 | 1 | 5 | 1 | 5 | 1 | **97.5** |
| **Caso A** | P3 - 2 | 5 | 1 | 5 | 1 | 5 | 1 | 5 | 1 | 5 | 1 | **100.0** |
| **Caso A** | P9 - 1 | 3 | 3 | 3 | 3 | 2 | 3 | 4 | 3 | 2 | 3 | **47.5** |
| **Caso A** | P9 - 2 | 4 | 2 | 3 | 3 | 3 | 2 | 5 | 3 | 2 | 3 | **60.0** |
| **Caso A** | P10 - 1 | 4 | 2 | 4 | 2 | 4 | 2 | 4 | 1 | 4 | 3 | **75.0** |
| **Caso A** | P10 - 2 | 4 | 2 | 4 | 1 | 3 | 4 | 4 | 1 | 3 | 2 | **70.0** |
| **Caso B** | P4 - 1 | 4 | 2 | 2 | 1 | 4 | 1 | 5 | 3 | 5 | 1 | **80.0** |
| **Caso B** | P4 - 2 | 5 | 1 | 5 | 2 | 5 | 1 | 4 | 2 | 4 | 1 | **90.0** |
| **Caso B** | P5 - 1 | 3 | 3 | 4 | 2 | 4 | 1 | 4 | 2 | 4 | 2 | **72.5** |
| **Caso B** | P5 - 2 | 2 | 2 | 4 | 2 | 5 | 1 | 4 | 3 | 4 | 2 | **72.5** |
| **Caso B** | P6 - 1 | 5 | 3 | 3 | 1 | 5 | 2 | 5 | 3 | 3 | 2 | **75.0** |
| **Caso B** | P6 - 2 | 5 | 1 | 5 | 1 | 5 | 1 | 2 | 2 | 5 | 1 | **90.0** |
| **Caso B** | P7 - 1 | 2 | 3 | 2 | 3 | 3 | 3 | 3 | 3 | 2 | 3 | **42.5** |
| **Caso B** | P7 - 2 | 3 | 4 | 2 | 4 | 2 | 3 | 2 | 3 | 3 | 4 | **35.0** |
| **Caso B** | P8 - 1 | 5 | 2 | 4 | 1 | 4 | 1 | 4 | 2 | 4 | 1 | **85.0** |
| **Caso B** | P8 - 2 | 5 | 2 | 3 | 1 | 3 | 1 | 4 | 2 | 4 | 1 | **80.0** |


Media Caso A: 85.00 

Media Caso B: 72.25

Obtenidos los resultados, se puede ver claramente que para estas tareas nuestra página (el caso A) ha resultado ser superior, además se pueden extraer las siguientes conclusiones:

1. **Influencia del perfil y la experiencia del usuario:** En el Caso A se observa una brecha muy marcada según la habilidad digital de los participantes. Los bloques de usuarios P1, P2 y P3 (perfiles más jóvenes o con mayores habilidades informáticas, correspondientes al intratesting) valoraron la experiencia con puntuaciones perfectas o casi perfectas (100 y 97.5). Sin embargo, las notas sufren una caída notable en los usuarios P9 y P10, con menor pericia informatica y mayores edades.

2. **Comportamiento general y puntos críticos:** Por su parte, el Caso B se muestran unas notas más estables, el problema principal resulto en el usuario P7, cuyas valoraciones descendieron de forma drástica hasta un 42.5 y 35.0. Probablemente el participante 7 aunque no demasiado mayor, si que presentaba una habilidad tic baja, lo que resultó en algún bloqueo puntual, que clarifica el mapa de calor correspondiente.

Como conclusión, **el Caso A ofrece una experiencia global mejor y más intuitiva**.


### 5.d A/B Testing
![Método UX](img/ABtesting.png) 
-----


Pasamos a realizar una tabla comparativa entre los dos casos:

| Métrica          | Caso A      | Caso B      |
|------------------|-------------|-------------|
| Media SUS        | 85          | 72.25       |
| Eval Lingüística | Excelente   | Buena       |
| Max Score        | 100.0       | 90          |
| Min Score        | 47.5        | 35          |


Tras el analisis del cuestionario SUS, podemoos concluir que el Caso A supera al caso B, y ademas es el ganador con una media de 85. Esto deja ver que la interfaz diseñada es solida y consistente  ante una experiencia de usuario notablemente variable (maximo de 100 y minimo de 47.5). Por otro lado, el caso B obtiene una media de 72.25, que refleja un buen resultado pero inferior, on una evaluacion linguística también positiva pero evidencia un rango de puntuaciones mas limitado, lo que sugiere margen de mejora en diversos aspectos

### 5.e Aplicación del método Eye Tracking 
![Método UX](img/eye-tracking.png)
----

#### Diseño del experimento y reclutamiento de usuarios

El experimento de Eye Traking se diseñó con el objetivo de analizar el comportamiento visual de los usuarios al interactuar con la interfaz. Para ello se definieron las dos tareas explicadas anteriormente

- **Prueba 1:** Consulta de carta y busqueda de informacion sobre alérgenos
- **Prueba 2:** Realizar una reserva

Se reclutaron una serie de participantes, asegurandonos que teniamos una variedad respresentativa de distintos perfiles.

#### Gazemap

La herramienta que hemos utilizado para este experimento es Gazemap, una plataforma de Eye Traking basada en webcam que permite registrar los movimentos oculares de los participantes.

#### Resultados del experimento

A continuación se muestran los mapas de calor generados para cada participante y prueba:

 
**Participante 1**
 
**Prueba 1: Buscar carta y alergenos**
 
| | |
|:---:|:---:|
| ![P1 Prueba 1 - img 1](./P5/P1_1.1.jpg) | ![P1 Prueba 1 - img 2](./P5/P1_1.2.jpg) |
 
**Prueba 2: Realizar una reserva**
 
| | |
|:---:|:---:|
| ![P1 Prueba 2 - img 1](./P5/P1_2.1.jpg) | ![P1 Prueba 2 - img 2](./P5/P1_2.2.jpg) |
 
 
**Participante 2**
 
**Prueba 1: Buscar carta y alergenos**
 
| | |
|:---:|:---:|
| ![P2 Prueba 1 - img 1](./P5/P2_1.1.jpg) | ![P2 Prueba 1 - img 2](./P5/P2_1.2.jpg) |
 
**Prueba 2: Realizar una reserva**
 
| | |
|:---:|:---:|
| ![P2 Prueba 2 - img 1](./P5/P2_2.1.jpg) | ![P2 Prueba 2 - img 2](./P5/P2_2.2.jpg) |
 
 
**Participante 3**
 
**Prueba 1: Buscar carta y alergenos**
 
| | |
|:---:|:---:|
| ![P3 Prueba 1 - img 1](./P5/P3_1.1.jpg) | ![P3 Prueba 1 - img 2](./P5/P3_1.2.jpg) |
 
**Prueba 2: Realizar una reserva**
 
| | |
|:---:|:---:|
| ![P3 Prueba 2 - img 1](./P5/P3_2.1.jpg) | ![P3 Prueba 2 - img 2](./P5/P3_2.2.jpg) |
 
 
**Participante 4**
 
**Prueba 1: Buscar carta y alergenos**
 
| | |
|:---:|:---:|
| ![P4 Prueba 1 - img 1](./P5/P4_1.1.jpg) | ![P4 Prueba 1 - img 2](./P5/P4_1.2.jpg) |
 
**Prueba 2: Realizar una reserva**
 
| | |
|:---:|:---:|
| ![P4 Prueba 2 - img 1](./P5/P4_2.1.jpg) | ![P4 Prueba 2 - img 2](./P5/P4_2.2.jpg) |
 
 
**Participante 5**
 
**Prueba 1: Buscar carta y alergenos**
 
| | |
|:---:|:---:|
| ![P5 Prueba 1 - img 1](./P5/P5_1.1.jpg) | ![P5 Prueba 1 - img 2](./P5/P5_1.2.jpg) |
 
**Prueba 2: Realizar una reserva**
 
| | |
|:---:|:---:|
| ![P5 Prueba 2 - img 1](./P5/P5_2.1.jpg) | ![P5 Prueba 2 - img 2](./P5/P5_2.2.jpg) |
 
 
**Participante 6**
 
**Prueba 1: Buscar carta y alergenos**
 
| | |
|:---:|:---:|
| ![P6 Prueba 1 - img 1](./P5/P6_1.1.jpg) | ![P6 Prueba 1 - img 2](./P5/P6_1.2.jpg) |
 
**Prueba 2: Realizar una reserva**
 
| | |
|:---:|:---:|
| ![P6 Prueba 2 - img 1](./P5/P6_2.1.jpg) | ![P6 Prueba 2 - img 2](./P5/P6_2.2.jpg) |
 
 
**Participante 7**
 
**Prueba 1: Buscar carta y alergenos**
 
| | |
|:---:|:---:|
| ![P7 Prueba 1 - img 1](./P5/P7_1.1.jpg) | ![P7 Prueba 1 - img 2](./P5/P7_1.2.jpg) |
 
**Prueba 2: Realizar una reserva**
 
| | |
|:---:|:---:|
| ![P7 Prueba 2 - img 1](./P5/P7_2.1.jpg) | ![P7 Prueba 2 - img 2](./P5/P7_2.2.jpg) |
 
 
**Participante 8**
 
**Prueba 1: Buscar carta y alergenos**
 
| | |
|:---:|:---:|
| ![P8 Prueba 1 - img 1](./P5/P8_1.1.jpg) | ![P8 Prueba 1 - img 2](./P5/P8_1.2.jpg) |
 
**Prueba 2: Realizar una reserva**
 
| | |
|:---:|:---:|
| ![P8 Prueba 2 - img 1](./P5/P8_2.1.jpg) | ![P8 Prueba 2 - img 2](./P5/P8_2.2.jpg) |
 
 
**Participante 9**
 
**Prueba 1: Buscar carta y alergenos**
 
| | |
|:---:|:---:|
| ![P9 Prueba 1 - img 1](./P5/P9_1.1.jpg) | ![P9 Prueba 1 - img 2](./P5/P9_1.2.jpg) |
 
**Prueba 2: Realizar una reserva**
 
| | |
|:---:|:---:|
| ![P9 Prueba 2 - img 1](./P5/P9_2.1.jpg) | ![P9 Prueba 2 - img 2](./P5/P9_2.2.jpg) |
 
 
**Participante 10**
 
**Prueba 1: Buscar carta y alergenos**
 
| | |
|:---:|:---:|
| ![P10 Prueba 1 - img 1](./P5/P10_1.1.jpg) | ![P10 Prueba 1 - img 2](./P5/P10_1.2.jpg) |
 
**Prueba 2: Realizar una reserva**
 
| | |
|:---:|:---:|
| ![P10 Prueba 2 - img 1](./P5/P10_2.1.jpg) | ![P10 Prueba 2 - img 2](./P5/P10_2.2.jpg) |
 

### 5.f Usability Report de B
![Método UX](img/usability-report.png) 
-----

[Usability Report](./P5/Usability-Report.md)

Paa finalizar, hemos elaborao un Usability Report especifico sobre el caso B para el grupo DIU3.ColesterMax.

En el se han sintetizado todos los resultados obtenidos a lo largo de todas las fases de evaluacion, mediante cuestionarios SUS, pruebas A/B, eye Tracking y los fallos de accesibilidad identificados con Lighthouse y WAVE. A partir de estos datos se plantean una serie de mejoras enfocadas en la estructura semantica, la claridad de la información y la reducción de fricciones en la navegación.

<br>


>>> Opinión FINAL del proceso de desarrollo de diseño siguiendo metodología UX y valoración (positiva /negativa) de los resultados obtenidos. ¿Qué se puede mejorar? Recuerda que este tipo de texto se debe eliminar del template que se os proporciona 
