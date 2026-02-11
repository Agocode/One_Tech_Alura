# telecom_challenger_2
Telecom X - Análisis de Evasión de Clientes 2da parte
Informe de Análisis de Churn de Clientes
Introducción
Este informe se basa en el análisis de los datos de clientes para identificar los factores clave que influyen en la cancelación de servicios (churn). Se han evaluado dos modelos de aprendizaje automático, Regresión Logística y Random Forest, para predecir el churn y entender la importancia de las diferentes variables.

📊 Rendimiento de los Modelos
Ambos modelos, tanto la Regresión Logística como el Random Forest, mostraron un buen rendimiento en la predicción de la cancelación de clientes.

Regresión Logística: Es un modelo lineal que mide la dirección e impacto de cada factor. Su rendimiento fue sólido, lo que sugiere que las relaciones entre las variables y el churn son en gran medida lineales.

Random Forest: Un modelo de conjunto no lineal que tiende a ser más robusto y a capturar interacciones complejas entre variables. Aunque ambos modelos se desempeñaron bien, Random Forest suele ser más preciso al identificar la importancia de las variables.

La evaluación detallada de ambos modelos, incluyendo métricas como Precisión, Recall y F1-Score, así como la Matriz de Confusión, mostró que ambos son viables para la predicción, pero el análisis de la importancia de las variables del modelo de Random Forest es particularmente útil para entender los factores de churn.

💡 Factores Clave que Influyen en la Cancelación (Churn)
Basándonos en el análisis de importancia de variables de los modelos, los factores que más influyen en la decisión de un cliente de cancelar son:

Tiempo de Permanencia (Tenure): Esta es la variable más crítica. Los clientes con menos tiempo de permanencia (tenure) son significativamente más propensos a cancelar. La probabilidad de churn disminuye drásticamente a medida que los clientes permanecen más tiempo con el servicio. Esto es un indicio de que los primeros meses son un periodo de alto riesgo.

Tipo de Contrato: Los clientes con contratos mes a mes tienen una tasa de cancelación mucho más alta que aquellos con contratos de uno o dos años. La flexibilidad de estos contratos facilita la salida del cliente si no está satisfecho.

Cargos Totales (Total Charges): Los clientes con un gasto total acumulado más bajo tienden a cancelar con mayor frecuencia. Esto puede estar relacionado con el poco tiempo de permanencia o con planes de servicio de menor costo.

Servicios Adicionales: La ausencia de servicios como seguridad online o respaldo técnico está fuertemente correlacionada con la cancelación. Ofrecer servicios de valor añadido parece ser un factor de retención importante.

Métodos de Pago: Los clientes que pagan con cheque electrónico muestran una mayor tendencia a cancelar. Este patrón podría estar relacionado con la demografía o el comportamiento de los usuarios de este método de pago.

📈 Estrategias de Retención Propuestas
Con base en estos hallazgos, se proponen las siguientes estrategias para reducir la tasa de cancelación:

Focalización en Nuevos Clientes:

Acción: Implementar programas de bienvenida y seguimiento intensivo durante los primeros 6 meses.

Justificación: Dado que la tenencia (tenure) es el factor más importante, los esfuerzos deben concentrarse en asegurar que los nuevos clientes tengan una experiencia positiva desde el principio. Ofrecer soporte proactivo y revisar la satisfacción del servicio puede ser clave.

Incentivar Contratos a Largo Plazo:

Acción: Ofrecer descuentos o beneficios especiales a los clientes que opten por contratos de uno o dos años en lugar de los de mes a mes.

Justificación: Los clientes con contratos mensuales son los más propensos a irse. Convertir estos contratos en planes de mayor permanencia podría anclar a los clientes y reducir el churn.

Promoción de Servicios de Valor Añadido:

Acción: Promover activamente servicios como seguridad online, protección de dispositivos y soporte técnico a clientes que actualmente no los tienen.

Justificación: La inclusión de servicios adicionales actúa como un ancla para los clientes. Al hacer que la oferta sea más completa y difícil de replicar por la competencia, se aumenta la lealtad.

Optimización de Métodos de Pago:

Acción: Analizar la experiencia de los clientes que utilizan cheques electrónicos y buscar soluciones para mejorarla. Podría tratarse de un problema de usabilidad o una oportunidad para dirigir a estos clientes a métodos de pago más convenientes y seguros, ofreciendo un pequeño incentivo.
