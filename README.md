# Analisis-de-embudo-y-retencion-para-MercadoLibre
Understand at what stage of the process users are lost and how their retention can be improved over time.
Entender en qué etapa del proceso se pierden usuarios y cómo se puede mejorar su retención a lo largo del tiempo.

**Objetivo:**  Mapear el embudo de conversión completo, identificar los principales puntos de fuga y evaluar la retención de usuarios por cohortes.

### Herramientas

<aside>
🛠 SQL | Visualización de Datos | Google Sheets

</aside>

### Preguntas clave

1. ¿En qué etapa se pierden más usuarios?
2. ¿Qué tan bien se retiene a los usuarios a lo largo del tiempo?
3. ¿Cómo varía esta pérdida y cómo se comporta la retención por país?

### Metodología

- Se construyó el embudo de conversión multietapa en SQL usando CTEs, posteriormente, se calculan las tasas de conversión entre pasos para detectar caídas.
- Se analiza la retención de usuarios por cohortes para luego, simular mejoras en conversión o retención.
- Por último se validaron resultados y se comunicaron hallazgos ejecutivos.

### Hallazgos y recomendaciones

- La etapa Add_to_cart, es la etapa que tiene mayor pérdida de los usuarios. Además, después del día 21 tiene mayor pérdida de usuarios en general.
- El país a destacar es Uruguay, el cual tiene una retención muy estable en la mayoría de pasos.

Se recomienda como acción inmediata: implementar un programa de onboarding mejorado en los días 21 y 28, ya que ahí ocurre la mayor pérdida. Analizar qué factores diferenciaron a las cohortes de marzo/julio (¿campañas específicas? ¿mejoras en la app?). Y como objetivo: elevar la retención D14 de cohortes futuras al nivel de marzo (56.8%+).

### Visualizaciones destacadas

Uso de Heatmaps para identificar inmediatamente dónde está la retención baja y dónde está la retención alta y para la comparación de cohortes.

1. Embudo general por país

![image.png](attachment:978c6171-5bc6-4fc5-9535-4b0924f576c4:image.png)

1. Retención por país

![image.png](attachment:37185ff1-e09c-486e-aa5d-b325c6f2443e:image.png)

1. Retención por cohorte

![image.png](attachment:2e1e096a-ab30-4527-9141-03f90077cbc0:image.png)

Explora más detalles del proyecto en
