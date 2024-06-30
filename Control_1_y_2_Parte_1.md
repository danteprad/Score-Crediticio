<table width='99%'>
<tr>
<td bgcolor='#560553'> 

# <font color='#FFFFFF'> **SCORE-CREDITICIO** </font>

</td>
</tr>
</table>

### Datos generales:

- Curso: Data Science Fundamentals
- Docente: Bch. Ms. Jordan King Rodriguez Mallqui
- Grupo: 4
- Control: 1 y 2

### Resumen:

|CATEGORÍA           |CASO DE USO                 |DECISIÓN     |INCERTIDUMBRE   |RESULTADO    |
|--------------------|----------------------------|-------------|----------------|-------------|
|Gestión de riesgos  |Modelo de Score crediticio  |(Respuesta)  |Riesgo de mora  |(Respuesta)  |

<table width='99%'>
<tr>
<td bgcolor='#1ABC9C'> 

## <font color='#FFFFFF'> **I. Elección del Problema (2 puntos):** </font>

</td>
</tr>
</table>

### a. Seleccione una aplicación relevante para una industria (puede ser del listado de la lámina 12 de la sesión 01, o una propia).

Modelo de Score crediticio

### b. Identifique la categoría y el caso de uso correspondiente (Ver lámina 23 de la sesión 01).

Categoría: Gestión de riesgos
Caso de uso: Modelo de score crediticio

<table width='99%'>
<tr>
<td bgcolor='#E74C3C'> 

## <font color='#FFFFFF'> **II. Análisis del Problema (2 puntos):** </font>

</td>
</tr>
</table>

### a. Identifique las decisiones clave, métricas y palancas relevantes para el problema seleccionado.

**<u>Desiciones clave para el Banco de acuerdo al score crediticio:</u>**
- El límite de la máxima cantidad de dinero que se le otorgara a una persona en su tarjeta de crédito.

- El monto máximo de monto de dinero de prestamo hipotecario,personal,automotriz y comercial que se le otorgara a un cliente.

**<u>Las metricas que debe tomar en cuenta el Banco para tomar la decisión del credito:</u>**
- Consumos mensuales, trimestrales de dinero utilizado en tiendas de retail mediante tarjeta de credito para un cliente.

- Cantidad de cuentas de crédito pagadas a tiempo,atrasadas,las cuentas en cobranza y las que no se pagaron, considerando el monto del credito.

- Ingresos mensuales, trimestrales, semestrales y anuales en las cuentas bancarias de la persona que desea adquirir un crédito en el banco.

- Monto total de la deuda que tiene actualmente la persona y de forma historica ya sea de años anteriores de forma mensual, trimestral, semestral y anual. 

- Proporción de crédito utilizado en comparación con el crédito disponible qur tiene actualmente.

- Cantidad de créditos que tiene actualmente y de forma histórica, como tarjetas de crédito, préstamos hipotecarios, préstamos para automóviles y comerciales.

**<u>Palancas relevantes:</u>**
- Los préstamos hipotecarios se otorgan con base en el valor del inmueble como garantía, lo que reduce el riesgo para el banco y permite ofrecer tasas de interés más bajas y plazos más largos.

- Los préstamos personales para la compra de vehiculos con el valor del vehiculo como grantía.

- Los préstamos empresariales en el sector Telecomunicaciones, Mineras, Energía, Construcción e inmobiliarias, Metalmecánica, Agroindustria,Retail, Consumo Masivo y Pesqueria que necesitan conseguir bienes necesarios como maquinarias e insumos para sus operaciones sin realizar un desembolso inicial significativo, lo cual puede ser muy beneficioso para la gestión financiera y la planificación a largo plazo de pagos con intereses asequibles.

### b. Describa el papel de la incertidumbre y los resultados esperados.

**<u>Incertidumbre</u>**

La incertidumbre en nuestro proyecto está definida como el riesgo de que un cliente entre en mora con el pago del préstamo que tiene con nuestra entidad finciera. Esta incertidumbre está influenciada, entre otros, por los siguientes factores:

- **Complejidad y precisión de los datos:** La calidad de los datos históricos de crédito puede variar significativamente. Los datos incompletos, errores de entrada o inconsistencias pueden afectar la precisión del modelo.

- **Cambios en la situación económica:** Factores macroeconómicos como recesiones, tasas de desempleo u otros cambios económicos pueden impactar la capacidad de pago de los clientes y no siempre están completamente capturados en la data disponible.

- **Cambios en el comportamiento del cliente:** Cambios en el comportamiento financiero o personal del cliente que no están reflejados en los datos históricos pueden afectar la capacidad de pago y aumentar la incertidumbre en el modelo.

- **Eventos inesperados:** Eventos externos imprevistos, como desastres naturales, pandemias u otros eventos catastróficos, pueden tener un impacto repentino en la capacidad de pago de los clientes y no pueden ser previstos por modelos basados únicamente en datos históricos.

- **Cambios en las políticas y regulaciones:** Cambios en las políticas gubernamentales o regulaciones financieras pueden alterar el entorno operativo y afectar indirectamente la capacidad de los clientes para cumplir con sus obligaciones financieras.

**<u>Resultados esperados</u>**

- **Predicciones de riesgo:** Se espera que el modelo pueda proporcionar predicciones cuantitativas sobre la probabilidad de que un cliente incumpla con sus pagos.

- **Mejora de la toma de decisiones:** Los resultados esperados incluyen mejorar la capacidad para evaluar y mitigar el riesgo crediticio al tomar decisiones informadas basadas en las predicciones del modelo.

- **Optimización de políticas:** Se espera que los resultados del proyecto ayuden a ajustar las políticas de crédito, segmentación de clientes y las estrategias de gestión de riesgos para mejorar la rentabilidad y reducir las pérdidas por incumplimientos.

<table width='99%'>
<tr>
<td bgcolor='#FFC300'> 

## <font color='#FFFFFF'> **III. Propuesta del Caso de Negocio (6 puntos):** </font>

</td>
</tr>
</table>

### a. Proponga una solución de Machine Learning para el problema identificado.

Ante la incertidumbre presentadas e eventos inesperados que ocasionen que cliente no cumpla con los pagos pactados con el banco, se propone un modelo de Credit Scoring (Modelo seguimiento), un modelo de machine learning que determine la probabilidad que un cliente  sea propensos a caer en default o incumplimiento de pago. Para bordar con este problema, se considera este proceso:

**<u>Recopilación de Datos</u>**

- Recopilar información relevante para el análisis son: Información demográfica, historial de crediticio, Información financiera (ingresos, deudas activas) y datos de comportamiento de productos financieros del cliente.

**<u>Procesamiento de Datos</u>**

- Tratamiento de datos para prepararlos para el modelo, limpieza de datos, codificación de variables categóricas y creación de variables a partir de variables existentes.

**<u>Selección de Modelo</u>**

- En los Credit Scoring, se consideran el modelo de Árboles de Decisión y Ensamblajes (Random Forest, Gradient Boosting) debido que maneja bien las características categóricas y las interacciones no lineales.

**<u>Entrenamiento del Modelo</u>**

- Se procede a dividir la data procesada en grupo de entrenamiento y un grupo de prueba, con el fin de entrenar el modelo utilizando el grupo de entrenamiento.

**<u>Evaluación de Modelo</u>**

- Usando el grupo de prueba, se usará métricas que evalúen el rendimiento del modelo. Por ejemplo: Exactitud, Precisión y Recall y AUC-ROC.
  
**<u>Interpretabilidad del Modelo</u>**

- En el contexto de credit scoring, es crucial entender cómo el modelo toma decisiones. Herramientas como SHAP (Shapley Additive Explanations) pueden ayudar a explicar las predicciones del modelo.

**<u>Implementación y Monitoreo</u>**

- Implementar el modelo en un entorno de producción y monitorear su rendimiento en el tiempo. Asegurarse de que el modelo sigue siendo válido y actualizarlo regularmente con nuevos datos.
  
![Scikit-learn algorithm cheat-sheet](https://miro.medium.com/v2/resize:fit:4244/format:webp/1*2NR51X0FDjLB13u4WdYc4g.png)

<p align="center">
  <em>Fuente: <a href="https://rubialesalberto.medium.com/tipos-de-algoritmos-en-data-science-da947132c8e7">rubialesalberto.medium.com</a></em>
</p>

### b. Liste y responda las preguntas clave siguiendo el framework: ¿Qué?, ¿Y entonces qué?, ¿Y ahora qué?

Análisis del “Qué”
1. ¿Cómo se mide el score crediticio en tu empresa?
En nuestra empresa, el score crediticio se mide utilizando un modelo basado en el algoritmo FICO Score. Este modelo toma en cuenta los siguientes factores:
•	Historial de pagos, cantidad adeudada, duración del historial de crédito, nuevo crédito, tipos de crédito utilizados.
2. ¿Es esta la mejor manera de hacerlo?
El uso del modelo FICO Score es ampliamente aceptado y utilizado en la industria, sin embargo, hay áreas de mejora.
3. ¿Cuál es el impacto en las ganancias y pérdidas?
El score crediticio tiene un impacto significativo en las ganancias y pérdidas de la empresa:
•	Ganancias:
o	Tasas de Interés: Clientes con puntajes más altos suelen recibir tasas de interés más bajas, lo que puede atraer más clientes de calidad.
o	Productos Financieros: Ofrecimiento de productos financieros personalizados basados en el puntaje de crédito, incrementando la satisfacción y retención del cliente.
•	Pérdidas:
o	Moras y Default: Clientes con puntajes bajos tienen una mayor probabilidad de incurrir en mora o default, lo que aumenta las pérdidas por deudas incobrables.
o	Costo de Recuperación: Gastos asociados a la recuperación de deudas, incluyendo acciones legales y agencias de cobranza.

Análisis del “Entonces Qué”
Acciones:
•	Evaluación del Modelo FICO: Analizar el rendimiento del modelo FICO actual para identificar sus fortalezas y debilidades.
•	Incorporación de Datos Adicionales: Considerar variables adicionales como datos transaccionales, incluidas transacciones de crédito y débito; pagos de alquiler y servicios públicos; datos de redes sociales; datos de comportamiento del sitio web, datos de encuesta o entrevista.
•	Uso de Machine Learning: Implementar modelos de machine learning más avanzados, como Random Forest o Gradient Boosting, que puedan captar patrones complejos en los datos.
Impacto Esperado:
•	Una evaluación más completa y precisa del riesgo crediticio de los clientes.
•	Inclusión de factores relevantes que reflejen mejor la capacidad de pago de los clientes.
¿Cómo se utilizará la puntuación (score crediticio)?
•	Campaña de créditos para clientes que tengan mejor score crediticio
•	Envío de notificaciones para el pago de cuotas
Impacto Esperado:
•	Aumento en la puntualidad de pagos y una reducción en la morosidad.
•	Mejora en la relación cliente-empresa al proporcionar valor añadido a los clientes.
Análisis del “Ahora Qué”
¿Qué necesitas de cualquier persona en la empresa involucrada en el proceso de toma de decisiones y operativo?
Información precisa y oportuna
¿Necesitas aprobación de Legal o Finanzas?
Al menos uno de ellos
¿Producto está de acuerdo con el cambio propuesto?
Sí
¿Cuándo se lanzará la campaña?
El siguiente semestre

¿Marketing está listo para lanzarla?
Está en proceso

### c. Considere las suposiciones necesarias y elija la métrica adecuada.

*<u>Las suposiciones</u>*
1.	Asumimos  que las variables utilizadas en el modelo de score crediticio para la nueva campaña propuesta son independientes: rentabilidad por cliente, costo de campaña por cliente, morosidad en el periodo entre otras.
2.	Las variables siguen distribuciones específicas según el momento o periodo analizado.
3.	Las relaciones entre las variables y el comportamiento crediticio de los individuos analizados son estables a lo largo del periodo semestral analizado.
4.	Asumimos  que los riesgos asociados con diferentes niveles de score crediticio son proporcionales a las predicciones del modelo.

*<u> Métrica Elegida:</u>*
Necesitamos una métrica mesurable, procesable, relevante y oportuna, por lo cual elegimos :
*Rentabilidad (Profit & Loss): * Porque evalúa cómo el modelo contribuye al rendimiento financiero de la institución, considerando el equilibrio entre riesgo y retorno.
En esta primera etapa y después podremos ir incorporando otras sub métricas

### d. Estime el valor monetario incremental basado en las suposiciones y la acción o palanca implementada.

Una vez planteado las palancas y la implementación de modelo ML al proyecto, realizamos la estimación del valor monetario.

Costo de campaña (A,X) = B * Campaña(A(X))*R

∆ Costo de Campaña (A, línea base, X) = B * ∆ Campaña(A; X, línea base)*R

-	Costo de campaña por cliente (R): S/.5
-	Base de usuarios con créditos (B): 200
-	Tasa de costo de campaña mensual: 10%
-	Nuevo modelo de ML reduce la tasa de costo de campaña en 4%

**<u>Falsos Positivos</u>**

-	Palancas costosas aplicadas a usuarios que no iban a caer en default.
  
Ejemplo: 200 usuarios reciben 10% de descuento de interés (i), 190 iban a cumplir el pago.
Costo: 10*10%*5= 5

**<u>Falsos Negativos</u>**

-	Costo de oportunidad por predicciones erróneas. Usuario que caer default y no fueron detectados: 10
  Costo: 10*5=50


|CONCEPTO                     |Valores en Soles |
|-----------------------------|-----------------|
|Costo de campaña sin modelo  |100              |
|Costo de campaña con modelo  |60               |
|Ahorro del nuevo modelo      |40               |
|Costo de falsos positivos    |5                |
|Costo de falsos negativos    |50               |

