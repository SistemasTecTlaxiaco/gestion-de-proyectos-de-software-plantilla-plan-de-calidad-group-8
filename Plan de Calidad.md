# PLAN DE CALIDAD DEL SOFTWARE

## Sistema de apoyo para vendedores de tenates artesanales de palma

**Lugar:** Heroica Ciudad de Tlaxiaco, Oaxaca  
**Metodología:** eduScrum  
**Sprint:** 2 — Gestión de Calidad  
**Product Owner:** José Alfredo Román Cruz  
**Periodo:** Agosto – Diciembre 2026

---

# 1. Introducción

El presente Plan de Calidad establece los criterios, actividades, métricas y pruebas que se utilizarán para asegurar la calidad del software desarrollado para apoyar a vendedores y artesanas de tenates de palma de la Heroica Ciudad de Tlaxiaco, Oaxaca.

El plan se construye a partir de las historias de usuario definidas en el backlog del proyecto y considera las condiciones particulares de la región Mixteca, especialmente la necesidad de contar con una solución sencilla, comprensible y capaz de operar bajo condiciones de conectividad limitada.

La calidad no se considera únicamente como la ausencia de errores técnicos. Para este proyecto también implica que las funcionalidades respondan a las necesidades reales de las artesanas, que la información registrada sea confiable, que las operaciones puedan verificarse y que la solución no introduzca una complejidad innecesaria para las personas usuarias.

La actividad de calidad se desarrolla mediante un uso crítico de herramientas de Inteligencia Artificial. La IA se utiliza como apoyo para proponer criterios de calidad, riesgos, pruebas y métricas, mientras que la decisión final sobre qué elementos se incorporan al Plan de Calidad corresponde al equipo.

---

# 2. Objetivos de calidad

## 2.1 Objetivo general

Garantizar que el software desarrollado para apoyar la gestión de los tenates artesanales sea funcional, confiable, verificable y adecuado para las condiciones reales de las personas que lo utilizarán en la Heroica Ciudad de Tlaxiaco y su región.

## 2.2 Objetivos específicos

1. Verificar que cada historia de usuario cumpla sus criterios de aceptación antes de considerarse terminada.
2. Reducir la cantidad de errores encontrados después de finalizar una historia mediante actividades de prevención y revisión temprana.
3. Diseñar funcionalidades que puedan utilizarse de manera sencilla por personas con diferentes niveles de experiencia digital.
4. Considerar la conectividad limitada de la región Mixteca como una condición de calidad del sistema.
5. Mantener consistencia en la información registrada sobre piezas, ventas, precios y características de los tenates.
6. Evitar que el sistema muestre información inventada o resultados que no puedan justificarse con los datos registrados.
7. Documentar las pruebas realizadas para cada historia de usuario.
8. Medir el esfuerzo utilizado para prevenir errores y corregirlos posteriormente.
9. Mantener trazabilidad entre historia de usuario, criterio de aceptación, prueba, resultado y corrección.
10. Aplicar principios de calidad relacionados con la gestión y desarrollo de procesos de software tomando como referencia CMMI y MoProSoft.

---

# 3. Alcance del Plan de Calidad

El Plan de Calidad cubre las siguientes historias de usuario:

| ID | Historia | Fase |
|---|---|---|
| HU01 | Registro de tiempo y costo para determinar un precio mínimo | Producción / tejido → Valorización y precio |
| HU02 | Registro de existencias y ventas del tianguis | Punto de venta físico |
| HU03 | Catálogo digital de tenates | Visibilidad y venta digital |
| HU04 | Registro de características de los tenates terminados | Control del producto |

El plan cubre:

- Revisión de historias de usuario.
- Criterios de aceptación.
- Pruebas funcionales.
- Pruebas de datos.
- Pruebas de conectividad.
- Revisión de usabilidad.
- Prevención de errores.
- Corrección de errores.
- Medición del costo de calidad.
- Trazabilidad.
- Revisión de resultados.
- Uso crítico de Inteligencia Artificial.
- Actualización del tablero eduScrum.

---

# 4. Principios de calidad aplicados

## 4.1 Calidad desde la prevención

El equipo buscará detectar problemas antes de implementar completamente una funcionalidad.

Se realizarán las siguientes actividades:

- Revisar una historia antes de programarla.
- Revisar criterios de aceptación antes de desarrollar.
- Definir las reglas de cálculo antes de implementar la funcionalidad correspondiente.
- Revisar qué sucede cuando no existen datos.
- Definir las validaciones de los datos.
- Considerar la falta de conexión desde el diseño.
- Revisar las propuestas generadas mediante IA antes de incorporarlas.

## 4.2 Verificación mediante evidencia

No se considerará suficiente afirmar que una funcionalidad funciona. Cada historia deberá contar con evidencia de revisión o prueba.

Las evidencias pueden ser:

- Capturas de pantalla.
- Resultado de una prueba.
- Registro de datos.
- Video de funcionamiento.
- Registro del tablero.
- Reporte de error y corrección.
- Resultado de una revisión.
- Registro de horas de prevención y corrección.

## 4.3 Adaptación al contexto real

El sistema deberá considerar que las personas usuarias pueden utilizar teléfonos móviles y encontrarse en lugares donde la conexión a Internet sea limitada o intermitente.

Por ello, cuando una historia requiera información previamente registrada, se evaluará si los datos necesarios pueden mantenerse disponibles localmente.

## 4.4 Simplicidad

Las funcionalidades deberán evitar pasos innecesarios.

No se busca agregar funciones solamente porque sean técnicamente posibles. Cada funcionalidad deberá justificar su utilidad para la persona que realiza la actividad artesanal o comercial.

---

# 5. Relación con CMMI y MoProSoft

El Plan de Calidad utiliza CMMI y MoProSoft como referencias para estructurar las actividades de planeación, seguimiento, verificación y mejora del proceso de desarrollo.

La integración de ambos modelos se adapta al tamaño y características del proyecto universitario.

## 5.1 Aplicación de CMMI

Para este proyecto se consideran los siguientes principios:

- Gestión de requisitos.
- Planificación del desarrollo.
- Verificación de productos de trabajo.
- Medición del desempeño.
- Gestión de riesgos.
- Análisis y corrección de problemas.
- Mejora del proceso.

| Práctica | Aplicación en el proyecto |
|---|---|
| Gestión de requisitos | Cada historia tendrá criterios de aceptación verificables. |
| Verificación | Cada historia será sometida a pruebas antes de marcarse como terminada. |
| Medición | Se registrarán horas de prevención y corrección. |
| Gestión de riesgos | Se considerarán conectividad, errores de datos, duplicados y usabilidad. |
| Análisis de problemas | Los errores encontrados se registrarán antes de corregirse. |
| Mejora | Los resultados del Sprint se utilizarán para mejorar el siguiente Sprint. |

CMMI se utiliza como referencia porque promueve la mejora de capacidades y del desempeño mediante prácticas que pueden adaptarse a los objetivos de una organización.

## 5.2 Aplicación de MoProSoft

MoProSoft se utiliza como referencia para organizar las actividades de desarrollo, gestión y evaluación del proyecto.

En este proyecto se adapta mediante:

- Planeación del trabajo.
- Definición de responsabilidades.
- Seguimiento de avances.
- Gestión de requisitos.
- Gestión de riesgos.
- Evaluación de resultados.
- Documentación de evidencias.
- Mejora continua.

La aplicación no consiste en copiar un proceso empresarial completo, sino en adaptar sus principios a las dimensiones y necesidades del proyecto universitario.

MoProSoft se encuentra formalizado en la familia de normas NMX-I-059 y contempla procesos relacionados con la gestión de proyectos y el desarrollo y mantenimiento de software.

---

# 6. Historias de usuario y criterios de calidad

# 6.1 HU01 — Registro de tiempo y costo de elaboración

## Historia

**Como** artesana tejedora de tenates de palma en Tlaxiaco,  
**quiero** registrar el tiempo de tejido y el costo de la palma de cada pieza,  
**para** fijar un precio mínimo que no me haga perder dinero cuando me regatean.

## Objetivo de calidad

Garantizar que el sistema registre correctamente el tiempo y el costo de la palma y que utilice únicamente los datos disponibles para realizar el cálculo del precio mínimo.

## Criterios de aceptación

**CA01.1 — Registro del tiempo:**  
Dado que estoy registrando un tenate, cuando introduzco el tiempo de tejido, entonces el sistema guarda ese tiempo asociado a la pieza.

**CA01.2 — Registro del costo:**  
Dado que conozco cuánto pagué por la palma utilizada, cuando registro el costo, entonces el sistema guarda ese valor asociado a la pieza.

**CA01.3 — Cálculo del precio mínimo:**  
Dado que tengo registrados los datos necesarios, cuando consulto el precio mínimo, entonces el sistema muestra un valor calculado mediante la fórmula definida por el equipo.

**CA01.4 — Información incompleta:**  
Dado que falta un dato necesario para calcular el precio mínimo, cuando intento realizar el cálculo, entonces el sistema indica qué dato falta y no muestra un precio inventado.

## Riesgos

- Introducción incorrecta del tiempo.
- Introducción incorrecta del costo.
- Error en la fórmula.
- Pérdida de datos.
- Cálculo realizado con información incompleta.
- Confusión entre costo de material y precio de venta.

## Pruebas

| Prueba | Acción | Resultado esperado |
|---|---|---|
| P01 | Registrar 5 horas de tejido | El sistema guarda 5 horas. |
| P02 | Registrar costo de palma | El costo queda asociado a la pieza. |
| P03 | Registrar datos completos | Se genera el precio mínimo. |
| P04 | Omitir un dato obligatorio | El sistema indica qué dato falta. |
| P05 | Introducir un valor inválido | El sistema rechaza el dato. |
| P06 | Consultar un registro guardado sin conexión | La información previamente guardada permanece disponible. |

## Métricas

- Porcentaje de registros guardados correctamente.
- Número de errores de cálculo.
- Número de datos inválidos detectados.
- Horas de prevención.
- Horas de corrección.

## Meta

100 % de los criterios de aceptación aprobados, 0 errores conocidos en la fórmula final y 100 % de los datos obligatorios validados antes del cálculo.

---

# 6.2 HU02 — Control de productos para el tianguis

## Historia

**Como** artesana que vende en el tianguis semanal de Tlaxiaco,  
**quiero** registrar cuántos tenates tengo disponibles y cuántos vendí cada día de mercado,  
**para** saber qué reponer antes del siguiente tianguis.

## Objetivo de calidad

Garantizar que las cantidades disponibles y las ventas registradas sean consistentes y permitan conocer las existencias reales.

## Criterios de aceptación

**CA02.1 — Registro de existencias:**  
Dado que tengo tenates disponibles para vender, cuando registro las piezas, entonces el sistema muestra correctamente la cantidad disponible.

**CA02.2 — Registro de ventas:**  
Dado que vendo un tenate, cuando registro la venta, entonces la cantidad disponible se actualiza correctamente.

**CA02.3 — Consulta de existencias:**  
Dado que existen ventas registradas, cuando consulto las existencias, entonces puedo conocer cuántas piezas quedan.

**CA02.4 — Consulta histórica:**  
Dado que existen registros de mercados anteriores, cuando selecciono un día, entonces puedo consultar las cantidades registradas para ese día.

## Riesgos

- Registrar una venta dos veces.
- Registrar una cantidad negativa.
- Perder registros de ventas.
- Mostrar una existencia incorrecta.
- No poder consultar información previamente guardada.

## Pruebas

| Prueba | Acción | Resultado esperado |
|---|---|---|
| P01 | Registrar 10 tenates | El inventario muestra 10. |
| P02 | Registrar venta de 1 tenate | El inventario disminuye a 9. |
| P03 | Registrar venta superior al inventario | El sistema evita una cantidad inválida. |
| P04 | Consultar un mercado anterior | Se muestran los datos registrados. |
| P05 | Consultar información previamente guardada sin conexión | Los datos disponibles localmente continúan visibles. |

## Métricas

- Exactitud del inventario.
- Número de errores de registro.
- Número de duplicados.
- Horas de prevención.
- Horas de corrección.

## Meta

100 % de las operaciones de inventario correctamente actualizadas, 0 cantidades negativas y 0 duplicados conocidos en las pruebas finales.

---

# 6.3 HU03 — Catálogo digital de tenates

## Historia

**Como** artesana de la Casa de la Artesana y el Artesano de Santa María Yucuhiti,  
**quiero** publicar foto, medida y precio de mis tenates en un catálogo compartido,  
**para** que compradores fuera de Tlaxiaco encuentren mi trabajo sin depender solo del tianguis.

## Objetivo de calidad

Garantizar que los productos publicados contengan información suficiente, sean visibles correctamente y no permanezcan disponibles cuando ya fueron vendidos.

## Criterios de aceptación

**CA03.1 — Publicación:**  
Dado que tengo un tenate terminado, cuando decido publicarlo, entonces aparece en el catálogo con fotografía, medida y precio.

**CA03.2 — Disponibilidad:**  
Dado que un tenate ya fue vendido, cuando actualizo su estado, entonces deja de mostrarse como disponible.

**CA03.3 — Publicación desde teléfono:**  
Dado que quiero publicar un tenate desde mi teléfono, cuando inicio el registro, entonces puedo completar la publicación en un máximo de 3 pasos.

**CA03.4 — Consulta del producto:**  
Dado que un comprador consulta un producto, cuando abre su información, entonces puede visualizar fotografía, medida, precio y disponibilidad.

## Riesgos

- Fotografía que no se carga.
- Información incompleta.
- Precio incorrecto.
- Producto vendido que continúa apareciendo disponible.
- Dificultades de uso desde teléfono.
- Dependencia excesiva de conexión.

## Pruebas

| Prueba | Acción | Resultado esperado |
|---|---|---|
| P01 | Publicar un producto completo | El producto aparece correctamente. |
| P02 | Intentar publicar sin precio | El sistema solicita el dato faltante. |
| P03 | Marcar producto como vendido | El producto deja de aparecer como disponible. |
| P04 | Publicar desde teléfono | La publicación se completa en máximo 3 pasos. |
| P05 | Abrir catálogo con conexión limitada | El sistema maneja correctamente la situación y no pierde información registrada. |

## Métricas

- Porcentaje de publicaciones correctas.
- Porcentaje de productos con información completa.
- Número de errores de disponibilidad.
- Número de errores de carga.
- Tiempo requerido para publicar.
- Horas de prevención.
- Horas de corrección.

## Meta

100 % de productos publicados con datos obligatorios, 100 % de productos vendidos correctamente identificados como no disponibles y máximo 3 pasos para publicar desde teléfono.

---

# 6.4 HU04 — Registro de características de los tenates terminados

## Historia

**Como** artesana productora de tenates,  
**quiero** registrar las características de cada tenate terminado, como su tipo, medida, material y precio,  
**para** llevar un control de mis productos y contar con información lista para su venta.

## Objetivo de calidad

Garantizar que la información registrada de cada tenate terminado sea completa, correcta y consistente, permitiendo identificar el producto antes de publicarlo o venderlo.

## Criterios de aceptación

**CA04.1 — Registro del producto:**  
Dado que tengo un tenate terminado, cuando registro sus características, entonces el sistema guarda correctamente la información del producto.

**CA04.2 — Información obligatoria:**  
Dado que existen datos obligatorios para identificar el producto, cuando intento guardar el registro sin alguno de ellos, entonces el sistema indica qué información falta.

**CA04.3 — Validación de datos:**  
Dado que estoy registrando las características del tenate, cuando introduzco una medida o precio inválido, entonces el sistema rechaza el dato y solicita corregirlo.

**CA04.4 — Consulta del producto:**  
Dado que existe un tenate registrado, cuando consulto su información, entonces el sistema muestra correctamente sus características almacenadas.

## Riesgos

- Registrar medidas incorrectas.
- Registrar un precio incorrecto.
- Guardar información incompleta.
- Registrar productos duplicados.
- Pérdida de información.
- Dificultad para capturar datos desde el teléfono.
- Problemas ocasionados por conectividad limitada.
- Mostrar información diferente a la almacenada.

## Pruebas

| Prueba | Acción | Resultado esperado |
|---|---|---|
| P01 | Registrar un tenate completo | El sistema guarda correctamente sus características. |
| P02 | Registrar un tenate sin medida | El sistema solicita la medida faltante. |
| P03 | Registrar un tenate sin precio | El sistema solicita el precio faltante. |
| P04 | Introducir un precio o medida inválida | El sistema rechaza el dato. |
| P05 | Consultar un tenate registrado | Se muestran correctamente sus características. |
| P06 | Consultar un producto previamente guardado sin conexión | La información disponible localmente permanece accesible. |

## Métricas

- Porcentaje de productos registrados correctamente.
- Porcentaje de registros completos.
- Número de datos inválidos detectados.
- Número de productos duplicados.
- Número de errores de información.
- Tiempo promedio de registro.
- Horas de prevención.
- Horas de corrección.

## Meta de calidad

- 100 % de los datos obligatorios correctamente validados.
- 0 productos duplicados conocidos en la prueba final.
- 100 % de las consultas deben mostrar correctamente la información almacenada.
- 100 % de los criterios de aceptación aprobados.

---

# 7. Adaptación a la conectividad limitada de la Mixteca

La conectividad limitada se considera un requisito de calidad transversal.

| Necesidad | Medida de calidad |
|---|---|
| Pérdida temporal de conexión | No perder datos que ya hayan sido guardados localmente. |
| Registro durante una interrupción | Permitir registrar información sin depender necesariamente de una conexión continua, cuando la arquitectura final lo permita. |
| Recuperación de conexión | Sincronizar posteriormente la información pendiente. |
| Consulta de datos previamente guardados | Mantener disponibles localmente los datos necesarios. |
| Errores de sincronización | Evitar duplicar registros durante la sincronización. |
| Conexión lenta | Evitar cargas innecesariamente pesadas. |
| Fotografías | Considerar compresión para reducir consumo de datos. |

**Criterio transversal:** el sistema no deberá perder información previamente guardada únicamente porque se interrumpa temporalmente la conexión.

---

# 8. Calidad de usabilidad

Debido a que el sistema estará dirigido a personas que pueden tener diferentes niveles de experiencia con herramientas digitales, la usabilidad será considerada como parte de la calidad.

- Los campos deberán utilizar nombres comprensibles.
- Los mensajes de error deberán indicar qué debe corregirse.
- No deberán solicitarse datos que no sean necesarios.
- Las acciones principales deberán ser visibles.
- El flujo de registro deberá ser corto.
- La aplicación deberá ser utilizable desde un teléfono.
- Los resultados deberán presentarse de manera comprensible.

## Prueba de usabilidad

Se propone realizar una prueba con una persona relacionada con la actividad artesanal.

### Actividades

1. Registrar un tenate.
2. Registrar tiempo de tejido.
3. Registrar costo de palma.
4. Consultar información.
5. Registrar una venta.
6. Publicar un producto.

### Se registrará

- Si pudo completar la actividad.
- En qué paso tuvo dificultades.
- Qué explicación necesitó.
- Cuánto tiempo tardó.
- Qué cambio propuso.

---

# 9. Plan de prevención y corrección

El objetivo es detectar y prevenir errores antes de que lleguen a etapas posteriores del desarrollo.

El índice de prevención se calculará mediante:

**Índice de prevención = Horas de prevención / (Horas de prevención + Horas de corrección) × 100**

## Actividades de prevención

### HU01

- Revisar la historia y criterios.
- Validar los datos necesarios para el cálculo.
- Revisar la fórmula antes de programarla.
- Diseñar casos de prueba con valores conocidos.

### HU02

- Definir reglas para cantidades.
- Validar que las ventas no produzcan inventarios negativos.
- Revisar la consistencia de las operaciones.
- Diseñar pruebas de duplicados.

### HU03

- Revisar campos obligatorios.
- Validar el flujo de publicación desde teléfono.
- Revisar el estado de disponibilidad.
- Considerar conectividad limitada.

### HU04

- Definir los campos obligatorios del producto.
- Establecer reglas para validar medida y precio.
- Revisar el formato de los datos.
- Diseñar pruebas para registros incompletos y duplicados.
- Revisar el comportamiento ante conectividad limitada.

## Actividades de corrección

### HU01

- Corregir errores de cálculo.
- Corregir errores de validación.
- Repetir las pruebas.

### HU02

- Corregir errores de actualización de inventario.
- Corregir registros duplicados.
- Repetir pruebas de operaciones.

### HU03

- Corregir errores de publicación.
- Corregir disponibilidad incorrecta.
- Repetir pruebas desde teléfono.

### HU04

- Corregir errores de captura o validación.
- Corregir registros incompletos.
- Corregir duplicados.
- Repetir las pruebas de consulta.
- Verificar nuevamente la información almacenada.

---

# 10. Estimación de horas de prevención y corrección

| Historia | Prevención | Corrección | Total | Índice de prevención |
|---|---:|---:|---:|---:|
| HU01 | 3 h | 2 h | 5 h | 60 % |
| HU02 | 2.5 h | 1.5 h | 4 h | 62.5 % |
| HU03 | 3.5 h | 2.5 h | 6 h | 58.3 % |
| HU04 | 3 h | 2 h | 5 h | 60 % |
| **Total** | **12 h** | **8 h** | **20 h** | **60 %** |

Estas cantidades son **estimaciones iniciales de planeación y no resultados reales**. Deberán sustituirse por las horas realmente registradas durante el Sprint.

---

# 11. Costo de la calidad

## 11.1 Costos de prevención

Son las horas utilizadas antes de que aparezca un error.

- Revisión de historias.
- Diseño de criterios de aceptación.
- Diseño de pruebas.
- Revisión de arquitectura.
- Revisión de datos.
- Análisis de conectividad.
- Revisión con usuarios.

## 11.2 Costos de evaluación

- Pruebas funcionales.
- Pruebas de integración.
- Pruebas de usabilidad.
- Pruebas de datos.
- Revisión de criterios de aceptación.

## 11.3 Costos de fallas internas

- Corrección de código.
- Corrección de datos.
- Repetición de pruebas.
- Corrección de criterios.

## 11.4 Costos de fallas externas

- Pérdida de información.
- Precio calculado incorrectamente.
- Inventario incorrecto.
- Producto vendido mostrado como disponible.
- Información incorrecta de las características de un tenate.

---

# 12. Estimación económica del Costo de Calidad

Para realizar una estimación cuantitativa se utilizará un costo interno de referencia de **$100 MXN por hora de trabajo del equipo**.

Este valor es un supuesto académico de cálculo y deberá sustituirse por el valor definido por el equipo si el docente establece otro criterio.

| Historia | Prevención | Evaluación | Fallas internas | Fallas externas | Costo estimado |
|---|---:|---:|---:|---:|---:|
| HU01 | $300 | $200 | $200 | $100 | $800 |
| HU02 | $250 | $150 | $150 | $100 | $650 |
| HU03 | $350 | $250 | $250 | $150 | $1,000 |
| HU04 | $300 | $200 | $200 | $100 | $800 |
| **Total** | **$1,200** | **$800** | **$800** | **$450** | **$3,250** |

Los valores anteriores son **estimaciones académicas**, no gastos reales.

---

# 13. Métricas generales del Plan de Calidad

| Métrica | Fórmula | Meta |
|---|---|---|
| Cumplimiento de criterios | Criterios aprobados / criterios totales × 100 | 100 % |
| Cobertura de pruebas | Criterios probados / criterios totales × 100 | 100 % |
| Índice de prevención | Horas de prevención / horas totales × 100 | ≥ 60 % inicialmente |
| Errores críticos | Número de errores críticos | 0 |
| Errores de cálculo | Número de errores encontrados | 0 al cierre |
| Datos incompletos | Registros incompletos / registros totales × 100 | ≤ 5 % |
| Duplicados | Registros duplicados / registros totales × 100 | 0 % en prueba final |
| Criterios de conectividad aprobados | Criterios aprobados / criterios de conectividad × 100 | 100 % |
| Historias terminadas | Historias que cumplen Definition of Done / historias seleccionadas × 100 | 100 % |

---

# 14. Matriz de trazabilidad

| Historia | Criterio | Prueba | Resultado | Evidencia |
|---|---|---|---|---|
| HU01 | CA01.1 | P01 | Pendiente | Por registrar |
| HU01 | CA01.2 | P02 | Pendiente | Por registrar |
| HU01 | CA01.3 | P03 | Pendiente | Por registrar |
| HU01 | CA01.4 | P04 | Pendiente | Por registrar |
| HU02 | CA02.1 | P01 | Pendiente | Por registrar |
| HU02 | CA02.2 | P02 | Pendiente | Por registrar |
| HU02 | CA02.3 | P04 | Pendiente | Por registrar |
| HU02 | CA02.4 | P04 | Pendiente | Por registrar |
| HU03 | CA03.1 | P01 | Pendiente | Por registrar |
| HU03 | CA03.2 | P03 | Pendiente | Por registrar |
| HU03 | CA03.3 | P04 | Pendiente | Por registrar |
| HU03 | CA03.4 | P05 | Pendiente | Por registrar |
| HU04 | CA04.1 | P01 | Pendiente | Por registrar |
| HU04 | CA04.2 | P02/P03 | Pendiente | Por registrar |
| HU04 | CA04.3 | P04 | Pendiente | Por registrar |
| HU04 | CA04.4 | P05/P06 | Pendiente | Por registrar |

---

# 15. Gestión de defectos

Cuando se encuentre un defecto, se registrará como mínimo:

| Campo | Descripción |
|---|---|
| ID | Identificador del defecto |
| Historia | Historia afectada |
| Criterio | Criterio de aceptación relacionado |
| Descripción | Explicación del problema |
| Severidad | Crítica / Alta / Media / Baja |
| Fecha | Fecha de detección |
| Responsable | Integrante encargado de la corrección |
| Horas de corrección | Tiempo utilizado |
| Estado | Abierto / En corrección / Corregido / Cerrado |
| Evidencia | Captura o resultado de prueba |

## 15.1 Clasificación de defectos

| Severidad | Descripción | Ejemplo |
|---|---|---|
| Crítica | Impide utilizar una función principal o provoca pérdida importante de información. | Pérdida de registros de ventas. |
| Alta | Una función principal produce información incorrecta. | Precio mínimo calculado incorrectamente. |
| Media | Una función funciona parcialmente pero requiere corrección. | No se muestra correctamente un dato secundario. |
| Baja | Problema visual o menor que no impide realizar la actividad. | Texto con formato incorrecto. |

---

# 16. Uso crítico de Inteligencia Artificial

La Inteligencia Artificial se utiliza como herramienta de apoyo para analizar las historias de usuario y proponer elementos de calidad.

El proceso será:

**Historia de usuario**  
↓  
**Prompt de IA**  
↓  
**Propuesta de criterios, riesgos y pruebas**  
↓  
**Revisión del equipo**  
↓  
**Comparación con CMMI / MoProSoft**  
↓  
**Revisión del contexto Mixteco**  
↓  
**Corrección de propuestas**  
↓  
**Aprobación del equipo**  
↓  
**Incorporación al Plan de Calidad**

La IA no sustituye las decisiones del equipo. Toda propuesta deberá ser revisada antes de convertirse en requisito o actividad del proyecto.

---

# 17. Prompt principal utilizado para la auditoría de calidad

**Prompt:**

> Actúa como auditor de calidad de software para un proyecto universitario desarrollado mediante eduScrum.
>
> Analiza la siguiente historia de usuario real del backlog y genera un plan de calidad aplicable al proyecto:
>
> **Historia:**  
> [Colocar aquí la historia de usuario completa]
>
> **Criterios de aceptación:**  
> [Colocar aquí los criterios de aceptación completos]
>
> El análisis debe considerar explícitamente:
>
> - CMMI.
> - MoProSoft.
> - Gestión de requisitos.
> - Verificación.
> - Gestión de riesgos.
> - Medición de calidad.
> - Mejora continua.
> - Prevención de errores.
> - Corrección de errores.
> - Contexto real de artesanas y vendedores de tenates de palma en Tlaxiaco, Oaxaca.
> - Región Mixteca.
> - Conectividad limitada o intermitente.
> - Uso desde teléfonos móviles.
> - Posibles errores de captura.
> - Necesidad de información confiable.
> - Tiempo disponible del Sprint.
> - Responsable de validar las propuestas.
>
> Separa claramente las actividades en:
>
> ### PREVENCIÓN
>
> Indica las actividades que deben realizarse antes de que aparezca un error.
>
> Para cada actividad indica:
>
> - Actividad.
> - Responsable.
> - Evidencia.
> - Horas estimadas.
>
> ### CORRECCIÓN
>
> Indica las actividades que deberán realizarse cuando se detecte un error.
>
> Para cada actividad indica:
>
> - Actividad.
> - Responsable.
> - Evidencia.
> - Horas estimadas.
>
> Después genera:
>
> 1. Riesgos de calidad.
> 2. Criterios de aceptación verificables.
> 3. Casos de prueba.
> 4. Validaciones de datos.
> 5. Pruebas relacionadas con conectividad.
> 6. Métricas cuantificables.
> 7. Horas estimadas de prevención.
> 8. Horas estimadas de corrección.
> 9. Índice de prevención.
> 10. Actividades que puedan convertirse en tarjetas del tablero eduScrum.
>
> No inventes necesidades que no estén relacionadas con la historia.
>
> Diferencia claramente entre una propuesta generada por IA y una decisión que debe ser validada por el equipo.
>
> No presentes las estimaciones como resultados reales.

---

# 18. Prompts específicos por historia

## HU01

> Actúa como auditor de calidad de software.
>
> Analiza esta historia:
>
> **Como artesana tejedora de tenates de palma en Tlaxiaco, quiero registrar el tiempo de tejido y el costo de la palma de cada pieza, para fijar un precio mínimo que no me haga perder dinero cuando me regatean.**
>
> Considera CMMI, MoProSoft, conectividad limitada, uso desde teléfono y datos confiables.
>
> Propón:
>
> 1. Riesgos de calidad.
> 2. Criterios de aceptación verificables.
> 3. Casos de prueba.
> 4. Datos inválidos que deben rechazarse.
> 5. Métricas.
> 6. Consideraciones de conectividad limitada.
> 7. Actividades de prevención.
> 8. Actividades de corrección.
> 9. Horas estimadas de prevención y corrección.
> 10. Tarjetas que deberían agregarse al tablero.
>
> No inventes una fórmula de precio si no está definida. Indica qué decisiones debe tomar el equipo.

## HU02

> Actúa como auditor de calidad de software.
>
> Analiza esta historia:
>
> **Como artesana que vende en el tianguis semanal de Tlaxiaco, quiero registrar cuántos tenates tengo disponibles y cuántos vendí cada día de mercado, para saber qué reponer antes del siguiente tianguis.**
>
> Propón:
>
> 1. Riesgos.
> 2. Criterios verificables.
> 3. Casos de prueba.
> 4. Validaciones de cantidades.
> 5. Pruebas de consistencia del inventario.
> 6. Consideraciones de conectividad limitada.
> 7. Métricas.
> 8. Prevención.
> 9. Corrección.
> 10. Horas de prevención y corrección.
> 11. Actividades que puedan convertirse en tarjetas del tablero.
>
> Diferencia claramente las propuestas de IA de los requisitos que debe validar el equipo.

## HU03

> Actúa como auditor de calidad de software.
>
> Analiza esta historia:
>
> **Como artesana de la Casa de la Artesana y el Artesano de Santa María Yucuhiti, quiero publicar foto, medida y precio de mis tenates en un catálogo compartido, para que compradores fuera de Tlaxiaco encuentren mi trabajo sin depender solo del tianguis.**
>
> Evalúa:
>
> 1. Riesgos.
> 2. Criterios de aceptación.
> 3. Pruebas funcionales.
> 4. Pruebas desde teléfono.
> 5. Pruebas con conectividad limitada.
> 6. Validación de fotografías.
> 7. Validación de disponibilidad.
> 8. Métricas cuantificables.
> 9. Actividades de prevención.
> 10. Actividades de corrección.
> 11. Horas de prevención y corrección.
>
> No agregues funcionalidades de pago o blockchain si la historia no las requiere.

## HU04

> Actúa como auditor de calidad de software.
>
> Analiza esta historia:
>
> **Como artesana productora de tenates, quiero registrar las características de cada tenate terminado, como su tipo, medida, material y precio, para llevar un control de mis productos y contar con información lista para su venta.**
>
> **Criterios de aceptación:**
>
> - CA04.1 Registro del producto.
> - CA04.2 Información obligatoria.
> - CA04.3 Validación de datos.
> - CA04.4 Consulta del producto.
>
> Considera:
>
> 1. CMMI.
> 2. MoProSoft.
> 3. Contexto de artesanas productoras de tenates en Tlaxiaco.
> 4. Conectividad limitada de la región Mixteca.
> 5. Uso desde teléfono.
> 6. Datos confiables.
> 7. Errores de captura.
> 8. Registros duplicados.
> 9. Prevención frente a corrección.
>
> Propón:
>
> - Riesgos de calidad.
> - Criterios de aceptación verificables.
> - Casos de prueba.
> - Validaciones de medida y precio.
> - Pruebas de información incompleta.
> - Pruebas de consulta.
> - Pruebas de conectividad.
> - Métricas cuantificables.
> - Actividades de prevención.
> - Actividades de corrección.
> - Responsable de cada actividad.
> - Evidencia necesaria.
> - Horas estimadas de prevención.
> - Horas estimadas de corrección.
> - Tarjetas que deben crearse en el tablero eduScrum.
>
> No agregues funciones que no sean necesarias para registrar y controlar las características de los tenates.

---

# 19. Revisión crítica de las propuestas de IA

No todas las propuestas generadas por IA deberán incorporarse automáticamente.

El equipo deberá revisar:

| Pregunta | Decisión |
|---|---|
| ¿La propuesta corresponde a la necesidad de la historia? | Sí / No |
| ¿Puede verificarse objetivamente? | Sí / No |
| ¿Es aplicable al contexto de Tlaxiaco? | Sí / No |
| ¿Considera conectividad limitada? | Sí / No |
| ¿Introduce una función innecesaria? | Sí / No |
| ¿Contradice una decisión previa del equipo? | Sí / No |
| ¿Puede probarse? | Sí / No |
| ¿Debe incorporarse al Plan de Calidad? | Sí / No |

---

# 20. Registro de decisiones sobre IA

| Historia | Propuesta de IA | Decisión del equipo | Justificación |
|---|---|---|---|
| HU01 | Validar datos antes de calcular | Aprobada | Evita cálculos con información incompleta. |
| HU01 | Inventar un precio cuando falten datos | Rechazada | El sistema no debe inventar información. |
| HU02 | Evitar cantidades negativas | Aprobada | Mantiene consistencia del inventario. |
| HU03 | Máximo 3 pasos para publicar | Aprobada | Es verificable y corresponde al uso desde teléfono. |
| HU04 | Validar campos obligatorios antes de guardar | Aprobada | Evita registros incompletos. |
| HU04 | Rechazar medidas o precios inválidos | Aprobada | Permite mantener datos confiables. |
| HU04 | Consultar información previamente registrada sin conexión | Aprobada | Se adapta a la conectividad limitada. |
| HU04 | Agregar funciones no relacionadas con el registro del producto | Rechazada | No corresponde al alcance de la historia. |

---

# 21. Criterios de salida del Sprint de Calidad

Para considerar terminado el Sprint de Calidad:

- Las cuatro historias tienen criterios de calidad definidos.
- Cada criterio tiene al menos una prueba asociada.
- Las pruebas pueden producir un resultado verificable.
- Se han identificado riesgos.
- Se han estimado horas de prevención y corrección.
- Se ha estimado el Costo de Calidad.
- Se han considerado las limitaciones de conectividad.
- Las propuestas de IA han sido revisadas por el equipo.
- Las decisiones del equipo están documentadas.
- Cada actividad de calidad tiene responsable.
- Las actividades de calidad se reflejan en el tablero.
- El tablero se actualiza durante la sesión y no solamente al final.

Conforme cada historia recibe criterios de calidad validados, el eduScrum Master deberá mover la tarea de **“En revisión de IA”** a **“Aprobado por el equipo”**.

---

# 22. Actualización del tablero eduScrum

El flujo de trabajo será:

**POR HACER**  
↓  
**EN REVISIÓN DE IA**  
↓  
**REVISIÓN DEL EQUIPO**  
↓  
**APROBADO POR EL EQUIPO**  
↓  
**PRUEBAS**  
↓  
**CORRECCIÓN**  
↓  
**TERMINADO**

Una historia no podrá pasar directamente de **“En revisión de IA”** a **“Terminado”**.

Primero deberá existir evidencia de que los criterios fueron revisados y las pruebas correspondientes fueron ejecutadas.

## Tarjetas de calidad

Cada actividad propuesta en el Plan de Calidad deberá convertirse en una tarea del tablero.

| Tarjeta | Responsable | Evidencia |
|---|---|---|
| Revisar criterios HU01 | Integrante asignado | Criterios aprobados |
| Diseñar pruebas HU01 | Integrante asignado | Casos de prueba |
| Validar inventario HU02 | Integrante asignado | Resultado de prueba |
| Probar publicación HU03 | Integrante asignado | Captura |
| Definir campos obligatorios HU04 | Integrante asignado | Lista de campos |
| Validar precio y medida HU04 | Integrante asignado | Resultado de prueba |
| Probar consulta HU04 | Integrante asignado | Captura |
| Probar HU04 sin conexión | Integrante asignado | Evidencia de funcionamiento |
| Corregir defectos encontrados | Integrante asignado | Reporte de corrección |

El **eduScrum Master** deberá actualizar el estado de estas tarjetas durante la sesión conforme se realicen las actividades.

---

# 23. Definition of Done

Una historia podrá considerarse terminada cuando:

- La historia está claramente definida.
- Los criterios de aceptación han sido aprobados.
- Los criterios de calidad están documentados.
- Las pruebas han sido ejecutadas.
- No existen defectos críticos abiertos.
- Los defectos de alta prioridad han sido corregidos o justificados.
- Los datos han sido validados.
- La funcionalidad ha sido revisada desde el contexto del usuario.
- Se ha evaluado la condición de conectividad cuando corresponde.
- La documentación está actualizada.
- La evidencia está almacenada.
- El equipo ha aprobado el resultado.
- El eduScrum Master ha actualizado el tablero.

---

# 24. Riesgos generales de calidad

| Riesgo | Probabilidad | Impacto | Respuesta |
|---|---|---|---|
| Conectividad limitada | Alta | Alta | Diseñar y probar almacenamiento local cuando corresponda. |
| Datos incorrectos | Media | Alta | Validación de entradas. |
| Pérdida de información | Media | Alta | Persistencia y pruebas de recuperación. |
| Baja experiencia digital | Media | Media | Pruebas de usabilidad con usuarios reales. |
| Error en cálculo de precio | Media | Alta | Pruebas con valores conocidos y revisión de fórmula. |
| Inventario inconsistente | Media | Alta | Validaciones y pruebas de operaciones. |
| Producto vendido mostrado disponible | Media | Alta | Prueba específica de actualización de disponibilidad. |
| Registros duplicados | Media | Media | Validaciones de integridad. |
| Información incompleta de producto | Media | Alta | Campos obligatorios y validaciones. |
| Dependencia excesiva de Internet | Alta | Alta | Evaluar funcionalidades offline y sincronización. |

---

# 25. Mejora continua

Al finalizar el Sprint se analizarán los resultados obtenidos.

El equipo responderá:

1. ¿Qué errores se encontraron?
2. ¿Cuántos fueron prevenidos?
3. ¿Cuántos requirieron corrección?
4. ¿Cuánto tiempo se utilizó en prevención?
5. ¿Cuánto tiempo se utilizó en corrección?
6. ¿Qué pruebas detectaron los errores?
7. ¿Qué errores pudieron haberse prevenido?
8. ¿Qué cambios deben realizarse al proceso?
9. ¿Qué criterios deben modificarse?
10. ¿Qué aprendizajes deben aplicarse al siguiente Sprint?

---

# 26. Registro de resultados reales

| Historia | Prevención real | Corrección real | Defectos encontrados | Defectos corregidos | Resultado |
|---|---|---|---|---|---|
| HU01 | Pendiente | Pendiente | Pendiente | Pendiente | Pendiente |
| HU02 | Pendiente | Pendiente | Pendiente | Pendiente | Pendiente |
| HU03 | Pendiente | Pendiente | Pendiente | Pendiente | Pendiente |
| HU04 | Pendiente | Pendiente | Pendiente | Pendiente | Pendiente |

**Importante:** las estimaciones de horas y costos no deben presentarse como resultados reales. Esta tabla deberá completarse después de ejecutar las actividades del Sprint.

---

# 27. Conclusión

El presente Plan de Calidad adapta las actividades de calidad a las necesidades concretas del proyecto de software para vendedores y artesanas de tenates de palma de la Heroica Ciudad de Tlaxiaco.

El plan no considera la calidad únicamente desde el punto de vista técnico, sino que también contempla las condiciones reales de uso, principalmente la conectividad limitada, el uso desde teléfonos móviles, la necesidad de información confiable y la importancia de que las funcionalidades sean comprensibles para las personas usuarias.

Las cuatro historias del backlog cuentan con criterios de aceptación, riesgos, pruebas y métricas específicas. Esto permite establecer una relación directa entre la necesidad del usuario y la comprobación de calidad.

También se incorpora una medición cuantitativa de las horas de prevención frente a las horas de corrección para cada historia, así como una estimación del Costo de la Calidad.

La aplicación de CMMI y MoProSoft permite organizar las actividades de requisitos, planificación, verificación, medición, gestión de riesgos y mejora continua, adaptándolas al contexto del proyecto universitario.

La Inteligencia Artificial se utiliza como herramienta de apoyo para generar propuestas de calidad, pero el equipo mantiene la responsabilidad de revisar, validar, adaptar o rechazar dichas propuestas.

Finalmente, el tablero eduScrum permite convertir las actividades de calidad en tareas reales con responsables y evidencias, asegurando que el proceso de calidad se lleve a cabo durante el Sprint y no solamente al finalizarlo.

---

# 28. Estado de aprobación

| Elemento | Estado |
|---|---|
| Historias revisadas | Completado |
| Criterios de aceptación | Completado |
| Criterios de calidad | Completado |
| Casos de prueba | Propuestos |
| Métricas | Definidas |
| Costo de Calidad | Estimado |
| Horas de prevención | Estimadas |
| Horas de corrección | Estimadas |
| Adaptación a conectividad limitada | Incluida |
| CMMI | Integrado como referencia de proceso |
| MoProSoft | Integrado como referencia de gestión |
| Uso crítico de IA | Documentado |
| Actividades para tablero | Definidas |
| Validación con usuarios reales | Pendiente de evidencia |
| Ejecución real de pruebas | Pendiente |
| Actualización final del tablero eduScrum | Pendiente de ejecución del equipo |

---

# 29. Aprobación del equipo

Antes de presentar el documento como evidencia final, el equipo deberá revisar y aprobar los criterios, métricas, estimaciones, pruebas y actividades del tablero.

| Integrante | Revisión | Aprobación | Fecha |
|---|---|---|---|
| Maritza Garcia Sanchez | Pendiente | Pendiente | __________ |
| Paola Rosario Ayala | Pendiente | Pendiente | __________ |
| Ariadna Belen Bernabe Juarez | Pendiente | Pendiente | __________ |
| Mayra Gonzalez Lita | Pendiente | Pendiente | __________ |

---

# 30. Nota final

Las estimaciones económicas, horas de prevención/corrección y resultados marcados como “Pendiente” no deben presentarse como datos reales hasta que el equipo los haya medido o validado.

El Plan de Calidad deberá actualizarse durante el Sprint conforme se ejecuten las pruebas y actividades. El eduScrum Master deberá reflejar el avance real en el tablero.

---

# 31. Fuentes bibliográficas

CMMI Institute. (2026). *What is CMMI?* ISACA/CMMI Institute.  
https://cmmiinstitute.com/cmmi/intro-3

CMMI Institute. (2026). *CMMI*. ISACA/CMMI Institute.  
https://www.cmmiinstitute.com/cmmi

CMMI Institute. (2026). *CMMI Adoption Guidance*. ISACA/CMMI Institute.  
https://cmmiinstitute.com/resource-files/public/v2-0-materials/cmmi-v2-0-adoption-and-transition-guide

Normalización y Certificación NYCE, S.C. (2026). *Inspección de Proceso de Desarrollo de Software – NMX-I-059/02-NYCE-2016 (MoProSoft).*  
https://nyce.org.mx/inspeccion-de-software-moprosoft-nmx-i-059-02-nyce-2016/

Normalización y Certificación NYCE, S.C. (2021). *Acervo Normativo NYCE: NMX-I-059-2-NYCE-2016, Tecnologías de la Información – Software – Modelos de Procesos y Evaluación para Desarrollo y Mantenimiento de Software – Parte 2: Requisitos de Procesos (MoProSoft).*  
https://www.nyce.org.mx/wp-content/uploads/2021/03/Acervo-Normativo-NYCE-23-03-2021.pdf

Equipo del proyecto. (2026). *Plan de Calidad — Proyecto de Tenates Artesanales | eduScrum Sprint 2.* Documento de trabajo del proyecto.
