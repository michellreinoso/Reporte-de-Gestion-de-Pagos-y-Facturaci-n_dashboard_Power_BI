**Reporte de Gestión de Pagos y Facturación_dashboard**

**Introducción:**
La base de datos “Herramientas de Visualización” contiene información relevante sobre el ciclo de
facturación y pagos de una empresa. La información disponible (incluyendo compañías, sucursales,
facturas y pagos) permiten realizar un análisis detallado de la operación financiera y la relación entre los
diferentes actores involucrados.
A partir de las variables principales, se busca realizar diversos análisis como:
● Identificación de facturas en mora (facturas vencidas sin pago),
● Análisis de montos facturados por sucursal o compañía,
● Comportamiento de pagos exitosos o fallidos en el tiempo,
● Tiempos promedio de pago y segmentación por cliente o tipo de contrato.

**Objetivo del análisis:**
El área de facturación necesita un reporte visual que ayude a analizar la situación de pagos, mora y
detectar patrones de inconsistencia.

**1. Tasa de Mora por Periodo:**
Contenido:
Este indicador revela la proporción de facturas que están atrasadas en cada ciclo de facturación. Se
considera que una factura está en atraso cuando no ha sido saldada o se abona después de su fecha
límite. Esta evaluación permite reconocer patrones de riesgo y medir la eficacia de las tácticas de cobro.
Análisis:
Altibajos extremos en los primeros años (2019–2021):
● Se notan niveles muy elevados de impago en meses como febrero y agosto de 2020 (100%).
● Asimismo, hay meses con una tasa del 0%, como en mayo de 2020 o noviembre de 2021.
● Estas fluctuaciones indican una falta de estabilidad o una base de datos limitada durante esos
años (bastan unos pocos casos para alterar drásticamente la tasa).
Inicio de estabilidad a partir de 2022:
● Desde octubre de 2022, la tasa de impago comienza a mantenerse entre el 40% y el 75%, lo que
sugiere un aumento en el volumen de datos o una mayor regularidad en los pagos.
● El mínimo en este periodo se registró en julio de 2023 (45. 69%), y el máximo en abril de 2024 (74.
14%).
Tendencia reciente:
● Durante 2024, la tasa de impago sigue siendo alta, permaneciendo en cifras por encima del 60%,
lo cual señala un empeoramiento en los pagos.
Conclusiones:
● La empresa experimentó problemas significativos de morosidad, especialmente en los últimos
dos años.
● La estabilidad en los valores más recientes sugiere una mejora en el control de datos, aunque no
en la gestión de cobros.
● La tasa de mora superior al 60% de forma sostenida representa un riesgo financiero alto y puede
comprometer la liquidez operativa.

Recomendaciones:
● Implementar políticas activas de cobranza, como notificaciones automáticas antes del
vencimiento o proveer de Incentivos por pronto pago (descuentos o beneficios)
● Segmentar a los clientes con mayor morosidad:
Clasificar clientes según su historial de pago y determinar si presentan mayor tendencia al
riesgo. Aplicar condiciones contractuales distintas (anticipos, garantías, etc.).
● Automatizar seguimiento de facturas:
Integrar dashboards en tiempo real que alerten sobre tendencias crecientes.
Usar modelos predictivos para anticipar morosidad.
● Revisar condiciones contractuales:
Revisar si los plazos de pago muy largos pueden alentar el retraso.
Evaluar si los términos actuales promueven o permiten el comportamiento moroso desde otras
áreas de la empresa.

**2. Top 10 Sucursales con Más Pagos Exitosos:**
Contenido: La gráfica representa el conjunto de las 10 sucursales con mayor cantidad monetaria de pagos
sin tomar en cuenta aquellos que hayan sido pagados después de la fecha de expiración, es decir,
excluyendo aquellas que entraron en periodo de mora. Tener en cuenta que se excluyeron todas aquellas
sucursales que no pertenecían a una compañía madre.

Análisis:
● En base a la gráfica podemos evidenciar que la Sucursal 3273 encabeza la lista con el mayor
número de pagos exitosos sin mora, seguida muy de cerca por la Sucursal 1937, por lo que se
coronaría como la sucursal con menor porcentaje de pagos en mora, seguida de la sucursal 1937,
siendo que ambas superan en gran valor al resto de sucursales.
● La sucursal 2256 también presenta un desempeño notable, aunque por debajo de las dos
primeras, ubicándose en un rango intermedio, al igual que las sucursales 1503, 1677, y 1849.
● Las Sucursales 364, 3411, 3516 y 1939 presentan los menores volúmenes dentro del top 10,
situándose alrededor de 0.4 a 0.5 millones de pagos, aun asi, se destacan dentro de las más de
mil sucursales.
Conclusiones:
● Como se mencionó anteriormente en la sección de contenido, no se incluyeron aquellas
sucursales que no pertenecían a una compañía madre, siendo que a nivel general, la acumulación
o suma de valores de todas estas compañías excluidas superaban con creces los valores de
pagos exitosos sin mora de las compañías pertenecientes a una compañía madre. Esto puede dar
indicios de que las sucursales independientes representan un mayor control de calidad sobre el
proceso de cobranza y recolección de pagos.
● Aparte de lo mencionado en el punto anterior, existe también una concentración del desempeño
en pocas sucursales. Las tres primeras agrupan una gran parte de los pagos exitosos, lo que
puede indicar una alta eficiencia o mayor volumen de clientes en esas zonas.
● La información y datos presentados también sugieren que ciertos factores locales (ya sea
ubicación, capacitación del personal, herramientas digitales, campañas locales, entre otros)
podrían estar influyendo en el éxito sin mora.
Recomendaciones:
● Realizar un proceso de observación y evaluación comparativa de aquellas sucursales que se
encuentran mas arriba en el top, o incluso, de algunas sucursales independientes, e identificar
qué procesos, personal o herramientas están utilizando que faciliten sus resultados exitosos y
favorables, y poner en práctica dichos procesos en aquellas sucursales con menor porcentaje de
pagos exitosos sin mora.
● Analizar el contexto de cada sucursal (nivel socioeconómico del área, acceso a servicios
digitales, cultura de pago) para adaptar estrategias localizadas.
● Establecer un seguimiento mensual o trimestral de este KPI (pagos exitosos sin mora) para
detectar tendencias y en base a estas, crear un plan de ejecución inmediata para Incentivar el
pago puntual, ya sea mediante canales digitales o automatizados u ofreciendo beneficios a
quienes paguen a tiempo.

**3. Sucursales con Facturación Incompleta:**
Contenido:
Gráfico de barras que muestra el total de sucursales con facturación incompleta por periodo de tiempo.
Análisis:
● Se observa un mayor número de sucursales sin factura en los periodos más recientes,
especialmente en junio 2024, octubre 2022 y abril 2024, con una tendencia decreciente en
periodos anteriores. Siendo que el pico más alto se presenta en junio del 2024, con mas de 35
sucursales sin facturas.
● A partir de 04-2023 en adelante, el número de sucursales disminuye drásticamente a menos de
10.
Conclusiones:
● Se observa una mejora sustancial en los procesos de facturación durante los últimos periodos,
esto puede indicar una mayor disciplina operativa o que se han implementado procesos de mejora
en controles internos, así como también la implementación de nuevas herramientas de
gestión/facturación.
● Las inconsistencias actuales podrían estar relacionadas con errores en el ingreso de datos,
problemas en la integración de sistemas o falta de seguimiento en los procesos administrativos
recientes. Las sucursales más afectadas deben ser revisadas con prioridad.
Recomendaciones:
Se recomienda implementar controles más estrictos sobre los registros de facturación en los últimos
periodos, así como auditorías mensuales que permitan detectar de forma temprana estas inconsistencias,
e implementar KPIs y métricas para futuras evaluaciones de este procedimiento.

**4. Empresas con Mayor Mora en los Últimos 3 Periodos:**
Contenido:
El gráfico muestra el Top 10 de empresas con mayor cantidad de facturas en mora durante los meses
de marzo, abril y mayo del 2024. Se visualiza la cantidad de facturas impagas por empresa.
Análisis:
Se observa que la empresa Company_166 lidera la lista con 14 facturas en mora, seguida por
Company_523 y Company_739, ambas con 13. El resto del top presenta entre 9 y 12 facturas pendientes,
lo que indica una concentración significativa de la mora en un grupo reducido de compañías. Esta
información es clave para priorizar acciones de cobranza.
Conclusiones:
● Un pequeño grupo de empresas representa una proporción importante de la mora reciente, lo que
puede tener impacto directo en la liquidez de la organización. Estas empresas podrían estar
enfrentando dificultades financieras o mostrando patrones de incumplimiento reiterado.
● La recurrencia de facturas en mora en un corto periodo puede representar un riesgo operativo y
financiero para la organización, especialmente si los montos de las facturas son elevados.
Recomendaciones:
● Analizar individualmente el top 10 de las empresas con mayor cantidad de facturas en mora,
conocer los motivos y razones de su ausencia de pagos y determinar si los impagos son por
problemas financieros, administrativos, disputas, etc, ya que esto nos facilitará las futuras
negociaciones.
● Es fundamental contactar a estas empresas que presentan mora para negociar pagos o
establecer planes de regularización. Asimismo, se sugiere realizar un análisis de riesgo crediticio
actualizado y aplicar políticas de facturación más estrictas para estos clientes en el futuro
cercano.

**Link Power BI web (archivo dinamico):**
https://app.powerbi.com/view?r=eyJrIjoiNjQyOGIwOWUtZGI3ZC00N2JhLWIyMDgtM2ZmOGY5MTlkNWI0IiwidCI6IjZjYTM0YWUxLTQ2NmYtNDRiYy1hN2FhLTBhYzVhNzhjNjFiMSIsImMiOjR9
