# Tablero de priorización

## Bloque 1

| Campo | Valor |
|---|---|
| Causa | Los pequeños empresarios enfrentan una alta variabilidad de la TRM debido a cambios económicos nacionales e internacionales. |
| Fase DT origen (E/D/I) | Definir: se establece que las decisiones se toman con base en el valor actual del dólar, sin suficiente capacidad para anticipar sus variaciones futuras. |
| Insight de empatía | Me preocupa que el dólar aumente mis costos, porque los cambios de la TRM me generan incertidumbre |
| Supuesto central | Si los pequeños empresarios comprenden la variabilidad de la TRM y los factores económicos nacionales e internacionales que la afectan, entonces podrán anticipar cambios de la TRM al tomar decisiones financieras. |
| Pregunta analítica | ¿Qué relación existe entre la comprensión de la variabilidad de la TRM y de los cambios económicos nacionales e internacionales que la afectan, y la capacidad de los pequeños empresarios para anticipar los cambios de la TRM en sus decisiones financieras? |
| Variables (nombres exactos) | 1.Precisión en la anticipación de la dirección de la TRM.<br>2. Comprensión de la variabilidad de la TRM y de los cambios económicos nacionales e internacionales que la afectan.<br>3. Capacidad de los pequeños empresarios para anticipar los cambios de la TRM en sus decisiones financieras.<br>4. Fecha<br>5. Año<br>6. Mes<br>7. TRM_promedio<br>8. TRM_minima<br>9. TRM_maxima<br>10. TRM_cierre<br>11. Variacion_mensual_%<br>12. Variacion_anual_%<br>13. Volatilidad_3m_%<br>14. Volatilidad_12m_%<br>15. Tendencia_3m_%<br>16. observaciones<br>17. ipc_colombia<br>18. tasa_politica_monetaria<br>19. fed_funds_rate<br>20. wti_usd<br>21. dxy<br>22. direccion_trm<br>23. direccion_trm_anticipada<br>24. anticipacion_correcta |
| Tipo (Outcome / Explic / Control / Segmento) | 1. Indicador KPI<br>2. Explicativa<br>3. Outcome<br>4. Segmento<br>5. Segmento<br>6. Segmento<br>7. Explicativa<br>8. Explicativa<br>9. Explicativa<br>10. Explicativa<br>11. Explicativa<br>12. Explicativa<br>13. Explicativa<br>14. Explicativa<br>15. Explicativa<br>16. Control<br>17. Explicativa<br>18. Explicativa<br>19. Explicativa<br>20. Explicativa<br>21. Explicativa<br>22. Explicativa<br>23. Explicativa<br>24. Control |
| Cálculo / Transformación | |
| Métrica (nombre + fórmula) | **Precisión en la anticipación de la dirección de la TRM.<br>`(Periodos anticipados correctamente / Total de periodos evaluados) × 100`** |
| Periodo / Segmento | Mensual: Una vez al mes. |
| Patrón esperado (si cierta) | 0.6 |
| Condición refutación | **≤52%** |
| Valor esperado para usuario/ciudadano | Mayor confianza y seguridad para anticipar los movimientos de la TRM y tomar decisiones financieras con menor incertidumbre. |
| Riesgo si falsa | Pérdida de tiempo y recursos en una anticipación poco precisa. |
| Acción si confirma | Usar el análisis de la TRM para definir la próxima compra o pago en dólares. |
| Acción si refuta | Suspender el uso del modelo de anticipación y revisar las variables utilizadas. |
| Experimento analítico mínimo (query + visual 1 línea) | |
| Estado (V/A/R) | |

## Bloque 2

| Campo | Valor |
|---|---|
| Causa | Los pequeños empresarios reciben información económica de múltiples fuentes que dificulta interpretar conjuntamente los factores que afectan la TRM. |
| Fase DT origen (E/D/I) | Definir: se delimita que la dificultad no es solo recibir información, sino interpretarla y relacionarla para comprender cómo puede cambiar la TRM. |
| Insight de empatía | Veo y escucho mucha información sobre el dólar, pero tengo dificultades para interpretarla y entender cómo puede cambiar la TRM |
| Supuesto central | Si los pequeños empresarios consultan e interpretan información de diferentes fuentes sobre la TRM, entonces podrán identificar con mayor facilidad los factores económicos relacionados con sus variaciones. |
| Pregunta analítica | ¿Cómo se relaciona el número de fuentes de información económica consultadas por los pequeños empresarios con su capacidad para interpretar conjuntamente los factores que afectan la TRM? |
| Variables (nombres exactos) | 1. Porcentaje de variabilidad de la TRM explicado por los factores económicos analizados.<br>2. Número de fuentes de información económica consultadas por los pequeños empresarios.<br>3. Capacidad de los pequeños empresarios para interpretar conjuntamente los factores que afectan la TRM.<br>4. TRM_promedio<br>5. Variacion_mensual_%<br>6. ipc_colombia<br>7. tasa_politica_monetaria<br>8. fed_funds_rate<br>9. wti_usd<br>10. dxy |
| Tipo (Outcome / Explic / Control / Segmento) | 1. Indicador KPI<br>2. Explicativa<br>3. Outcome<br>4. Explicativa  <br>5. Explicativa  <br>6. Explicativa  <br>7. Explicativa  <br>8. Explicativa  <br>9. Explicativa  <br>10. Explicativa |
| Cálculo / Transformación | |
| Métrica (nombre + fórmula) | **Porcentaje de variabilidad de la TRM explicado por los factores económicos analizados.<br>`R² × 100`** |
| Periodo / Segmento | Trimestral: Cada tres meses |
| Patrón esperado (si cierta) | 0.5 |
| Condición refutación | **≤42%** |
| Valor esperado para usuario/ciudadano | Mayor claridad para comprender los factores que explican los cambios de la TRM y tomar decisiones con información confiable. |
| Riesgo si falsa | Inversión de recursos en factores que no explican la TRM. |
| Acción si confirma | Identificar los factores económicos que más influyen en la TRM antes de realizar una operación en dólares. |
| Acción si refuta | Descartar los factores con baja relación con la TRM y buscar nuevas variables explicativas. |
| Experimento analítico mínimo (query + visual 1 línea) | |
| Estado (V/A/R) | |

## Bloque 3

| Campo | Valor |
|---|---|
| Causa | Los pequeños empresarios toman decisiones sobre sus operaciones en dólares principalmente a partir del comportamiento actual de la TRM. |
| Fase DT origen (E/D/I) | Definir: se establece que las decisiones se toman con base en el valor actual del dólar, sin suficiente capacidad para anticipar sus variaciones futuras. |
| Insight de empatía | Consulto diariamente el precio del dólar y ajusto mi presupuesto cuando cambia la TRM, porque quiero saber cuándo me conviene pagar o comprar. |
| Supuesto central | Si los pequeños empresarios identifican las variaciones de la TRM, entonces podrán ajustar oportunamente sus decisiones de compra, pago y presupuesto en dólares. |
| Pregunta analítica | ¿De qué manera las variaciones de la TRM se reflejan en las decisiones de compra, pago y presupuesto en dólares de los pequeños empresarios colombianos? |
| Variables (nombres exactos) | 1. Porcentaje de periodos con variaciones significativas de la TRM detectados mediante el comportamiento histórico.<br>2. Variaciones de la TRM.<br>3. Decisiones de compra, pago y presupuesto en dólares de los pequeños empresarios colombianos.<br>4. TRM_promedio<br>5. Variacion_mensual_%<br>6. Volatilidad_3m_%<br>7. Volatilidad_12m_% |
| Tipo (Outcome / Explic / Control / Segmento) | 1. Indicador KPI<br>2. Explicativa<br>3. Outcome<br>4. Explicativa  <br>5. Explicativa  <br>6. Explicativa  <br>7. Explicativa |
| Cálculo / Transformación | |
| Métrica (nombre + fórmula) | **Porcentaje de periodos con variaciones significativas de la TRM detectados mediante el comportamiento histórico.<br>`(Periodos con variación significativa / Total de periodos evaluados) × 100`** |
| Periodo / Segmento | Mensual: Una vez al mes. |
| Patrón esperado (si cierta) | 0.8 |
| Condición refutación | **≤70%** |
| Valor esperado para usuario/ciudadano | Mayor tranquilidad y capacidad de reaccionar oportunamente ante variaciones significativas de la TRM, reduciendo el riesgo de pérdidas en operaciones en dólares. |
| Riesgo si falsa | Aumento del riesgo de sobrecostos por reaccionar tarde a cambios de la TRM. |
| Acción si confirma | Revisar la TRM antes de realizar una compra o pago en dólares y ajustar la decisión según su variación. |
| Acción si refuta | Revisar el criterio de variación significativa y ajustar el método de detección. |
| Experimento analítico mínimo (query + visual 1 línea) | |
| Estado (V/A/R) | |

# Ficha de Indicador

## Bloque 1

| Paso | Campo | Valor |
|---|---|---|
| — | Supuesto central | Si los pequeños empresarios comprenden la variabilidad de la TRM y los factores económicos nacionales e internacionales que la afectan, entonces podrán anticipar cambios de la TRM al tomar decisiones financieras. |
| Paso 1: Objetivo del Indicador | ¿QUÉ HAGO? (Acción) | Analizar el comportamiento y la variabilidad histórica de la TRM para identificar patrones de aumento, disminución y estabilidad que puedan servir como referencia para anticipar sus movimientos. |
| Paso 1: Objetivo del Indicador | ¿CÓMO LO HAGO? (Método) | Utilizando los datos mensuales de la TRM entre 2015 y 2025, calculando variaciones mensuales y anuales, tendencias y medidas de volatilidad para comparar diferentes periodos del comportamiento del dólar. |
| Paso 1: Objetivo del Indicador | ¿PARA QUÉ LO HAGO? (Propósito) | Para identificar patrones y periodos de mayor riesgo cambiario que permitan a los pequeños empresarios contar con información útil para anticipar posibles movimientos de la TRM y planificar sus operaciones en dólares. |
| Paso 2: Factor Crítico | Aspecto específico a Medir | El comportamiento, la variabilidad y la identificación de patrones en los cambios de la TRM que puedan utilizarse como referencia para anticipar su dirección futura. |
| Paso 2: Factor Crítico | Público objetivo (Para quién) | Pequeños empresarios colombianos que realizan compras, pagos o adquieren productos e insumos en dólares. |
| Paso 2: Factor Crítico | Dimensión (Marca una) | Eficacia (¿Logra el resultado?) |
| Paso 3: Fórmula | **Nombre del indicador** | **Precisión en la anticipación de la dirección de la TRM.** |
| Paso 3: Fórmula | Numerador (Variable Y) | Número de periodos del conjunto de prueba en los que el modelo anticipa correctamente si la TRM aumentará o disminuirá. |
| Paso 3: Fórmula | Denominador (Población) | Total de periodos del conjunto de prueba utilizados para evaluar la capacidad de anticipación de la TRM. |
| Paso 3: Fórmula | Fórmula (Matemática) | `(Periodos anticipados correctamente / Total de periodos evaluados) × 100` |
| Paso 3: Fórmula | Prueba de estrés | Se evaluará el indicador en periodos de baja, media y alta volatilidad de la TRM, especialmente durante episodios de fuertes aumentos o disminuciones. Se compararán los resultados para determinar si los patrones históricos continúan siendo útiles para anticipar la dirección de la TRM bajo condiciones de mayor incertidumbre. |
| Paso 4: Unidad | Tipo (Marca una) | Porcentaje (%) |
| Paso 5: Fuentes | Frecuencia de medición | Mensual: Una vez al mes. |
| Paso 5: Fuentes | Fuente de datos (Verificación) | Base_TRM_Mensual_2015_2025_en_Colombia |
| Paso 6: Seguimiento | Línea base (Patrón actual) | 0.4427 |
| Paso 6: Seguimiento | Patrón esperado (Meta) | 0.6 |
| Paso 6: Seguimiento | **Condición de refutación (Fallo)** | **≤52%** |

## Bloque 2

| Paso | Campo | Valor |
|---|---|---|
| — | Supuesto central | Si los pequeños empresarios consultan e interpretan información de diferentes fuentes sobre la TRM, entonces podrán identificar con mayor facilidad los factores económicos relacionados con sus variaciones. |
| Paso 1: Objetivo del Indicador | ¿QUÉ HAGO? (Acción) | Analizar la relación existente entre las variaciones de la TRM y los principales factores económicos nacionales e internacionales que pueden influir en su comportamiento. |
| Paso 1: Objetivo del Indicador | ¿CÓMO LO HAGO? (Método) | Comparando la evolución mensual de la TRM con variables como el IPC, las tasas de interés, el precio del petróleo y el DXY, utilizando análisis estadístico para identificar la intensidad y dirección de sus relaciones. |
| Paso 1: Objetivo del Indicador | ¿PARA QUÉ LO HAGO? (Propósito) | Para determinar qué factores económicos presentan una mayor relación con los cambios de la TRM y generar información que facilite la interpretación de sus movimientos por parte de los pequeños empresarios. |
| Paso 2: Factor Crítico | Aspecto específico a Medir | El grado de relación y capacidad explicativa de los factores económicos nacionales e internacionales frente a las variaciones observadas en la TRM durante el periodo de análisis. |
| Paso 2: Factor Crítico | Público objetivo (Para quién) | Pequeños empresarios colombianos que realizan compras, pagos o adquieren productos e insumos en dólares. |
| Paso 2: Factor Crítico | Dimensión (Marca una) | Eficacia (¿Logra el resultado?) |
| Paso 3: Fórmula | **Nombre del indicador** | **Porcentaje de variabilidad de la TRM explicado por los factores económicos analizados.** |
| Paso 3: Fórmula | Numerador (Variable Y) | Variabilidad de la TRM explicada conjuntamente por las variables económicas incluidas en el modelo estadístico. |
| Paso 3: Fórmula | Denominador (Población) | Variabilidad total observada de la TRM durante el periodo de análisis. |
| Paso 3: Fórmula | Fórmula (Matemática) | `R² × 100` |
| Paso 3: Fórmula | Prueba de estrés | Se estimará el modelo en un periodo de condiciones económicas normales y posteriormente se evaluará su capacidad explicativa durante periodos de alta volatilidad de la TRM. Se comparará el R² obtenido en ambos escenarios para determinar si los factores económicos mantienen su capacidad explicativa ante cambios fuertes del mercado. |
| Paso 4: Unidad | Tipo (Marca una) | Porcentaje (%) |
| Paso 5: Fuentes | Frecuencia de medición | Trimestral: Cada tres meses |
| Paso 5: Fuentes | Fuente de datos (Verificación) | Base_TRM_Mensual_2015_2025_en_Colombia |
| Paso 6: Seguimiento | Línea base (Patrón actual) | No establecida. |
| Paso 6: Seguimiento | Patrón esperado (Meta) | 0.5 |
| Paso 6: Seguimiento | **Condición de refutación (Fallo)** | **≤42%** |

## Bloque 3

| Paso | Campo | Valor |
|---|---|---|
| — | Supuesto central | Si los pequeños empresarios identifican las variaciones de la TRM, entonces podrán ajustar oportunamente sus decisiones de compra, pago y presupuesto en dólares. |
| Paso 1: Objetivo del Indicador | ¿QUÉ HAGO? (Acción) | Identificar los periodos en los que la TRM presenta variaciones significativas y determinar la frecuencia e intensidad con que ocurren estos cambios. |
| Paso 1: Objetivo del Indicador | ¿CÓMO LO HAGO? (Método) | Analizando las variaciones mensuales, las tendencias y las medidas de volatilidad de la TRM entre 2015 y 2025, clasificando los periodos según la magnitud de sus movimientos. |
| Paso 1: Objetivo del Indicador | ¿PARA QUÉ LO HAGO? (Propósito) | Para identificar momentos de mayor exposición al riesgo cambiario que puedan afectar los costos de compras, pagos e insumos denominados en dólares de los pequeños empresarios. |
| Paso 2: Factor Crítico | Aspecto específico a Medir | La frecuencia, magnitud y comportamiento de las variaciones significativas de la TRM como aproximación al nivel de exposición al riesgo cambiario de los pequeños empresarios. |
| Paso 2: Factor Crítico | Público objetivo (Para quién) | Pequeños empresarios colombianos que realizan compras, pagos o adquieren productos e insumos en dólares. |
| Paso 2: Factor Crítico | Dimensión (Marca una) | Eficacia (¿Logra el resultado?) |
| Paso 3: Fórmula | **Nombre del indicador** | **Porcentaje de periodos con variaciones significativas de la TRM detectados mediante el comportamiento histórico.** |
| Paso 3: Fórmula | Numerador (Variable Y) | Número de periodos en los que la variación de la TRM supera el umbral establecido a partir de su comportamiento histórico. |
| Paso 3: Fórmula | Denominador (Población) | Total de periodos mensuales evaluados durante 2015–2025. |
| Paso 3: Fórmula | Fórmula (Matemática) | `(Periodos con variación significativa / Total de periodos evaluados) × 100` |
| Paso 3: Fórmula | Prueba de estrés | Se aplicará el indicador a los periodos de mayor volatilidad registrados entre 2015 y 2025 y se comparará con periodos de comportamiento estable. Se verificará si el método permite detectar consistentemente los movimientos cambiarios considerados significativos. |
| Paso 4: Unidad | Tipo (Marca una) | Porcentaje (%) |
| Paso 5: Fuentes | Frecuencia de medición | Mensual: Una vez al mes. |
| Paso 5: Fuentes | Fuente de datos (Verificación) | Base_TRM_Mensual_2015_2025_en_Colombia |
| Paso 6: Seguimiento | Línea base (Patrón actual) | 0.3053 |
| Paso 6: Seguimiento | Patrón esperado (Meta) | 0.8 |
| Paso 6: Seguimiento | **Condición de refutación (Fallo)** | **≤70%** |
