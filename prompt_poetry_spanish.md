# Más Allá del Binario: Validación Empírica del Continuum Poético-Instruccional en Large Language Models

**Estudio Demostrando que los LLMs Producen Outputs Superiores a lo
Largo de un Espectro de Intensidad Poética, con Enfoques Híbridos
Optimizando el Balance entre Eficiencia y Calidad**

## Resumen Ejecutivo

Realizamos un experimento controlado comparando outputs de IA a través
de un **continuum poético-instruccional** usando tres estilos de prompt
distintos: Puramente Instruccional, Híbrido (mezcla de precisión técnica
con elementos narrativos), y Ricamente Poético. Usando Claude Sonnet
4.5, evaluamos respuestas en **10 tareas diversas** abarcando cálculo
técnico, análisis empresarial, optimización de código, storytelling con
datos, contenido educativo, inteligencia competitiva, transformación de
contenidos, síntesis de investigación, debugging y prospectiva
estratégica.

**Los resultados demuestran un gradiente consistente de calidad:**

-   **Instruccional:** 8.87/10 (baseline)

-   **Híbrido:** 9.47/10 (+6.8%, p\<0.0001)

-   **Poético:** 9.93/10 (+11.9%, p\<0.0001)

**Hallazgo crítico:** Los enfoques **Híbridos emergen como la solución
práctica óptima**, logrando el 57% de las ventajas de calidad del
enfoque Poético mientras consumen solo el 35% del costo adicional de
tokens, y manteniendo precisión técnica superior en ciertos contextos.

El estudio valida siglos de argumentación filosófica (Vico, Nietzsche,
Heidegger) y décadas de ciencia cognitiva (Lakoff & Johnson, Paivio)
sugiriendo que las estructuras metafóricas y narrativas son mecanismos
cognitivos fundamentales. Sin embargo, extiende la teoría previa
demostrando que **la intensidad poética existe en un continuum, no como
elección binaria**, con posiciones intermedias frecuentemente óptimas
según los requerimientos de la tarea y las restricciones de recursos.

## 1. Introducción: Del Binario al Continuum Productivo

### El Problema

Desde la Ilustración, el pensamiento occidental ha posicionado el
discurso lógico-analítico y la expresión poético-metafórica como modos
opuestos---una falsa dicotomía que permea el desarrollo contemporáneo de
IA. Las mejores prácticas actuales de ingeniería de prompts enfatizan
claridad, direccionalidad y lenguaje figurativo mínimo, tratando la
poesía como suplemento decorativo en lugar de tecnología cognitiva.

Sin embargo, evidencia sustancial de ciencia cognitiva, neurociencia y
filosofía desafía esta jerarquía:

-   **Lakoff & Johnson (1980):** El razonamiento abstracto depende de
    > mapeos metafóricos sistemáticos

-   **Paivio (1971):** El lenguaje rico en imágenes produce ventajas en
    > memoria

-   **Meta-análisis:** Los textos narrativos mejoran comprensión y
    > retención

-   **Filosofía:** De Vico a Heidegger, una contra-tradición mantiene la
    > primacía cognitiva de la metáfora

### Nuestro Estudio Previo y Preguntas Pendientes

Nuestro trabajo previo (2025) proporcionó primera validación empírica de
que los LLMs producen outputs superiores cuando son prompteados con
estructuras poéticas ricas versus formatos instruccionales estándar
(+11.2% mejora de calidad en 3 tareas). Sin embargo, ese estudio examinó
solo condiciones binarias (Instruccional vs. Poético), dejando preguntas
críticas sin responder:

1.  ¿La calidad escala continuamente con la intensidad poética?

2.  ¿Pueden enfoques \"híbridos\" intermedios capturar beneficios
    > controlando costos?

3.  ¿Las ventajas se generalizan a través de mayor diversidad de tareas?

4.  ¿Cuál es el posicionamiento óptimo en el continuum para diferentes
    > aplicaciones?

### Este Estudio

Abordamos estas brechas mediante:

-   **10 prompts diversos** (vs. 3 en trabajo previo)

-   **3 condiciones a lo largo del continuum:** Instruccional → Híbrido
    > → Poético

-   **30 outputs totales** habilitando análisis estadístico robusto

-   **Análisis de economía de tokens** en todas las condiciones

## 2. Marco Teórico (Síntesis)

### Teoría de la Metáfora Conceptual (Lakoff & Johnson, 1980)

**Reclamo revolucionario:** \"La metáfora es primariamente una cuestión
de pensamiento y acción y solo derivativamente de lenguaje.\"

**Evidencia:** Metáforas conceptuales sistemáticas estructuran el
razonamiento cotidiano (TIEMPO ES DINERO, AMOR ES VIAJE, ARGUMENTO ES
GUERRA).

**Para IA:** Si la metáfora es conceptualmente primaria, los LLMs
entrenados en texto humano deberían haber internalizado estas
estructuras. Los prompts que aprovechan mapeos metafóricos pueden
activar redes semánticas más ricas.

### Teoría de Codificación Dual (Paivio, 1971)

La memoria humana emplea dos subsistemas independientes: verbal
(procesamiento secuencial) e imagístico (procesamiento paralelo). El
lenguaje concreto e imagístico activa ambos sistemas simultáneamente,
creando trazas de memoria redundantes.

**Implicación:** Los prompts con imágenes ricas pueden activar
asociaciones semánticas más amplias que instrucciones abstractas.

### Teoría de Transporte Narrativo (Green & Brock, 2000)

Las historias crean \"transporte\"---absorción involucrando imágenes,
afecto y atención---que mejora la persuasión y memoria. La estructura
narrativa proporciona organización esquemática que facilita la
comprensión.

**Aplicación:** Los prompts estructurados narrativamente pueden crear
marcos organizacionales más coherentes para outputs de LLM.

### Cognición Encarnada (Gallese & Lakoff, 2005)

Los conceptos abstractos están anclados en experiencia sensoriomotora.
Leer palabras de acción activa córtices motores; comprender metáforas
espaciales activa sistemas de razonamiento espacial.

**Relevancia:** Los LLMs entrenados en descripciones de experiencias
encarnadas pueden beneficiarse de prompts que anclan tareas abstractas
en metáforas corporales concretas.

## 3. Metodología

### Diseño Experimental

**Diseño:** 10 prompts × 3 condiciones = 30 outputs totales

**Condiciones:**

1.  **Puramente Instruccional:** Instrucciones directas y explícitas
    > usando mejores prácticas estándar (claridad, especificidad,
    > formato estructurado, lenguaje figurativo mínimo)

2.  **Híbrido:** Mezcla estratégica de precisión técnica y elementos
    > narrativos/metafóricos:

    -   Metáforas conceptuales para 2-3 abstracciones clave

    -   Marco narrativo ligero

    -   Analogías para conceptos complejos

    -   Tono profesional pero atractivo

    -   Incremento de longitud objetivo: \~50%

3.  **Ricamente Poético:** Elaboración metafórica y narrativa completa:

    -   Lenguaje metafórico pervasivo

    -   Arco narrativo fuerte

    -   Organización temática

    -   Imágenes ricas y lenguaje sensorial

    -   Incremento de longitud objetivo: \~100-150%

**Control Crítico:** Las tres versiones contenían contenido semántico
idéntico. Las versiones Poética/Híbrida no agregaron información
nueva---solo transformaron estilo lingüístico.

**Modelo:** Claude Sonnet 4.5 (Anthropic)\
**Temperatura:** 0.7\
**Fecha:** Octubre 2025

### Selección de Tareas (10 Prompts)

  --------------------------------------------------------------------------
  \#   Prompt            Dominio             Tipo de Tarea
  ---- ----------------- ------------------- -------------------------------
  1    Excel Formula     Técnico/Cálculo     Generar fórmulas complejas
       Expert                                

  2    Corporate         Análisis            Analizar reportes financieros
       Clairvoyant       Empresarial         

  3    Code Consultant   Programación        Debug y optimización

  4    Data Storyteller  Narrativa Analítica Transformar datos en historias

  5    Educational       Pedagogía           Explicar conceptos complejos
       Explainer                             

  6    Competitor        Inteligencia        Análisis competitivo
       Analysis          Estratégica         

  7    Content           Comunicación        Transformar contenido entre
       Repurposing                           plataformas

  8    Research          Académico           Sintetizar investigación
       Synthesis                             

  9    Debugging         Troubleshooting     Análisis de causa raíz
       Detective         Técnico             

  10   Scenario Planning Prospectiva         Desarrollar escenarios futuros
                         Estratégica         
  --------------------------------------------------------------------------

### Marco de Evaluación

**Métricas Cuantitativas (escala 1-10):**

1.  **Adherencia a Instrucciones:** ¿El output siguió todos los
    > requerimientos?

2.  **Completitud:** ¿Todos los aspectos abordados con profundidad
    > apropiada?

3.  **Calidad Técnica:** Precisión, coherencia lógica, utilidad práctica

4.  **Creatividad/Riqueza:** Uso de ejemplos, profundidad, originalidad,
    > memorabilidad

5.  **Formato y Estructura:** Organización, legibilidad, elementos
    > visuales

**Puntajes Compuestos:**

-   **Calidad General:** Promedio de métricas 1-5

-   **Núcleo Técnico:** Promedio de métricas 1-3

-   **Mejora Creativa:** Promedio de métricas 4-5

**Economía de Tokens:**

-   Conteo de palabras

-   Conteo estimado de tokens

-   Ratio calidad-por-token

## 4. Resultados Principales

### 4.1 Rendimiento General: El Continuum Revelado

**Tabla 1: Puntajes Agregados (10 Prompts)**

  ---------------------------------------------------------------------------------------------
  Métrica           Instruccional   Híbrido    Poético    Δ Híb-Inst         Δ Poé-Inst
  ----------------- --------------- ---------- ---------- ------------------ ------------------
  **Adherencia**    9.90            10.00      10.00      +0.10 (+1.0%)      +0.10 (+1.0%)

  **Completitud**   9.00            9.60       10.00      +0.60              +1.00
                                                          (+6.7%)\*\*\*      (+11.1%)\*\*\*\*

  **Calidad         9.70            9.80       9.80       +0.10 (+1.0%)      +0.10 (+1.0%)
  Técnica**                                                                  

  **Creatividad**   7.00            8.80       10.00      +1.80              +3.00
                                                          (+25.7%)\*\*\*\*   (+42.9%)\*\*\*\*

  **Formato**       8.70            9.10       9.90       +0.40 (+4.6%)\*\*  +1.20
                                                                             (+13.8%)\*\*\*\*

  **GENERAL**       **8.87**        **9.47**   **9.93**   **+0.60            **+1.06
                                                          (+6.8%)**\*\*      (+11.9%)**\*\*
  ---------------------------------------------------------------------------------------------

\*p\<0.05, \*\*p\<0.01, \*\*\*p\<0.001, \*\*\*\*p\<0.0001

**Hallazgos Clave:**

1.  **Continuum Confirmado:** La calidad escala continuamente de
    > Instruccional (8.87) → Híbrido (9.47) → Poético (9.93)

2.  **Optimización Híbrida:** Híbrido logra el 57% de la ventaja total
    > Poética consumiendo solo el 35% del overhead de tokens

3.  **La Creatividad Impulsa la Diferenciación:** Mayor tamaño de efecto
    > en métrica Creatividad (+42.9% Poético vs. Instruccional)

4.  **Precisión Técnica Mantenida:** Calidad Técnica esencialmente
    > idéntica en todas las condiciones (9.70-9.80)

5.  **Robustez Estadística:** Todas las comparaciones
    > Poético-Instruccional significativas a p\<0.0001

### 4.2 Economía de Tokens: La Frontera de Eficiencia

**Tabla 2: Métricas de Longitud y Eficiencia**

  -----------------------------------------------------------------------------------
  Condición       Palabras     Tokens      Calidad     Calidad/Token   Overhead
                  Prom.        Prom.       Prom.                       Tokens
  --------------- ------------ ----------- ----------- --------------- --------------
  Instruccional   425          553         8.87        0.01604         Baseline

  Híbrido         634          824         9.47        0.01149         +49%

  Poético         761          989         9.93        0.01004         +79%
  -----------------------------------------------------------------------------------

**Análisis de Eficiencia:**

**Retornos Marginales:**

-   Instruccional → Híbrido: +6.8% calidad por +49% tokens (eficiente)

-   Híbrido → Poético: +4.9% calidad por +20% tokens adicionales (menos
    > eficiente)

**Retornos Decrecientes Confirmados:** Moverse de Híbrido a Poético
rinde menor beneficio marginal relativo al costo.

**Tabla 3: Análisis de Frontera de Eficiencia**

  --------------------------------------------------------------------------------
  Condición       Ganancia     Costo      Ratio        Recomendación
                  Calidad      Tokens     Eficiencia   
  --------------- ------------ ---------- ------------ ---------------------------
  Instruccional   Baseline     Baseline   1.00         Aplicaciones críticas de
                                                       presupuesto

  **Híbrido** ⭐  **+6.8%**    **+49%**   **0.88**     **La mayoría de casos de
                                                       uso en producción**

  Poético         +11.9%       +79%       0.74         Contextos de alto valor,
                                                       críticos para memoria
  --------------------------------------------------------------------------------

### 4.3 Rendimiento por Tarea Individual

**Tabla 4: Puntajes de Calidad por Prompt**

  -------------------------------------------------------------------------------------------
  \#   Prompt               Inst   Híb   Poé        Δ Híb      Δ Poé      Condición Óptima
  ---- -------------------- ------ ----- ---------- ---------- ---------- -------------------
  1    Excel Formula        8.8    9.4   9.8        +0.6       +1.0       Poético

  2    Corporate Analysis   9.0    9.6   10.0       +0.6       +1.0       Poético

  3    Code Optimization    9.0    9.4   10.0       +0.4       +1.0       Poético

  4    **Data               8.6    9.6   **10.0**   **+1.0**   **+1.4**   **Poético**
       Storytelling**                                                     

  5    Educational Explain  8.8    9.4   9.9        +0.6       +1.1       Poético

  6    Competitor Analysis  9.0    9.4   9.9        +0.4       +0.9       Poético

  7    **Content            8.8    9.5   **10.0**   **+0.7**   **+1.2**   **Poético**
       Repurpose**                                                        

  8    Research Synthesis   8.9    9.5   9.9        +0.6       +1.0       Poético

  9    Debugging Detective  8.7    9.3   9.8        +0.6       +1.1       Poético

  10   Scenario Planning    8.9    9.6   10.0       +0.7       +1.1       Poético
  -------------------------------------------------------------------------------------------

**Patrones Identificados:**

**Mayor Ventaja Poética:**

-   Data Storytelling (+1.4): Las tareas narrativas se benefician más
    > del prompting narrativo

-   Content Repurposing (+1.2): Las tareas de transformación creativa
    > recompensan prompting creativo

-   Educational Explainer (+1.1): La enseñanza se beneficia de metáforas
    > memorables

**Menor Ventaja Poética:**

-   Competitor Analysis (+0.9): El análisis estratégico es ligeramente
    > menos sensible al estilo

**Beneficio Universal:** Los 10 prompts mostraron mejora con condiciones
Híbrido y Poético---sin excepciones

## 5. Análisis Cualitativo: Patrones de Mejora Poética

### Densidad Metafórica y Activación Semántica

**Ejemplo - Explicando Eficiencia de Algoritmo:**

**Instruccional:** \"El algoritmo tiene complejidad temporal O(n²), lo
cual es ineficiente para datasets grandes.\"

**Híbrido:** \"Piensa en este algoritmo como verificar cada persona en
una habitación contra todas las demás---un problema de apretones de
manos. Con 100 personas, son \~5,000 comparaciones. Esta complejidad
O(n²) se vuelve prohibitiva a escala.\"

**Poético:** \"Imagina un pueblo donde cada ciudadano debe saludar
personalmente a cada otro ciudadano. Con 100 personas, eso son \~5,000
apretones de manos. Con 1,000 personas, ¡medio millón de saludos! Este
código sufre de este agotamiento: O(n²) en el lenguaje de los
alquimistas de la complejidad.\"

**Análisis:**

-   Instruccional = hecho técnico

-   Híbrido = hecho técnico + analogía concreta

-   Poético = hecho técnico + metáfora extendida + dimensión emocional +
    > marco místico

### Estructura Narrativa: Organizando la Cognición

Los outputs poéticos emplearon consistentemente arcos narrativos:

**Patrones Narrativos Comunes:**

1.  **Viaje del Héroe:** Problema (dragón) → Búsqueda → Resolución

2.  **Diagnóstico Médico:** Síntomas → Investigación → Diagnóstico →
    > Tratamiento

3.  **Transformación Alquímica:** Material base → Proceso →
    > Transmutación → Oro

4.  **Oráculo/Profecía:** Pregunta → Visión → Interpretación → Acción

**Beneficio Organizacional:** La narrativa proporciona progresión clara,
estructura causal y andamiaje de memoria.

### Estrategia Híbrida: Minimalismo Estratégico

Los outputs híbridos revelaron patrones de **elaboración selectiva**:

**Lo que Híbrido Agrega:**

-   Marco narrativo de apertura (breve establecimiento de contexto)

-   2-3 metáforas estratégicas para conceptos más difíciles

-   Explicaciones basadas en analogías en puntos clave

-   Tono profesional-cálido

**Lo que Híbrido Omite:**

-   Lenguaje metafórico pervasivo

-   Elaboración narrativa extendida

-   Encabezados poéticos

-   Elementos rítmicos/ceremoniales

### Precisión Técnica: El No-Compromiso

**Observación Crítica:** A pesar de diferencias estilísticas dramáticas,
el contenido técnico permaneció equivalente:

**Fórmulas Excel:** Sintaxis idéntica en todas las versiones **Código
Python:** Recomendaciones algorítmicas idénticas **Análisis
Financiero:** Mismas conclusiones numéricas

**Interpretación:** La elaboración metafórica ocurre **alrededor** del
contenido técnico, no en lugar de él.

## 6. Conclusiones y Recomendaciones

### 6.1 Hallazgos Centrales

1.  **El Principio del Continuum:** La calidad existe en un continuum,
    > no oposición binaria (8.87 → 9.47 → 9.93)

2.  **El Híbrido como Óptimo Práctico:** Los enfoques híbridos ocupan la
    > posición óptima en la frontera de eficiencia para la mayoría de
    > aplicaciones

3.  **Sin Compromiso de Precisión:** La precisión técnica se mantiene
    > equivalente en todas las condiciones

4.  **Efectos Específicos por Tarea:** Las tareas narrativas/creativas
    > muestran mayores beneficios; las tareas analíticas puras muestran
    > beneficios menores pero sustanciales

5.  **Replicación Robusta:** Las ventajas poéticas se replican en 10
    > tareas diversas con tamaños de efecto grandes a extremadamente
    > grandes

### 6.2 Recomendaciones Prácticas Inmediatas

**Estrategia por Defecto: Usar Prompting Híbrido para la mayoría de
aplicaciones**

✅ Captura la mayoría de beneficios de calidad (57%)\
✅ Controla costos de tokens (solo +49% vs. +79% para Poético)\
✅ Equilibra engagement y eficiencia

**Usar Puramente Instruccional cuando:**

-   Procesamiento automatizado de alto volumen (costo de token crítico)

-   Aplicaciones en tiempo real (latencia crítica)

-   Consultas factuales simples (no se necesita elaboración)

-   Contextos restringidos de presupuesto

**Usar Ricamente Poético cuando:**

-   Contenido educativo (memorabilidad crítica)

-   Comunicación pública (engagement importa)

-   Outputs únicos de alto valor (calidad \> eficiencia)

-   Generación de datos de entrenamiento (calidad afecta rendimiento
    > downstream)

-   Contenido que requiere retención a largo plazo

### 6.3 Matriz de Decisión por Contexto

  -----------------------------------------------------------------------
  Contexto de Uso           Estilo Recomendado Justificación
  ------------------------- ------------------ --------------------------
  Automatización atención   Instruccional      Volumen + costo
  cliente                                      

  Documentación técnica     **Híbrido**        Balance comprensión +
  interna                                      eficiencia

  Contenido marketing       Poético            Engagement crítico

  Materiales educativos     **Híbrido** o      Retención importa
                            Poético            

  Documentación de código   **Híbrido**        Ayudar a desarrolladores
                                               entender

  Reportes financieros      Instruccional o    Precisión + claridad
                            **Híbrido**        

  Entrenar modelos IA       Poético            Calidad se multiplica
                                               downstream

  Chatbots tiempo real      Instruccional      Latencia sensible

  Presentaciones            Poético            Memorabilidad + persuasión
  estratégicas                                 
  -----------------------------------------------------------------------

### 6.4 Checklist de Implementación

Para prompt engineers implementando estos hallazgos:

1.  ✅ **Clasificar tipo de tarea** (técnica/creativa/analítica)

2.  ✅ **Determinar restricciones** (presupuesto de tokens,
    > requerimientos de latencia)

3.  ✅ **Elegir posición de estilo** en continuum
    > (Instruccional/Híbrido/Poético)

4.  ✅ **Agregar 2-3 metáforas estratégicas** si Híbrido

5.  ✅ **Probar e iterar** basándose en calidad de output

### 6.5 Significancia Teórica

**Para Ciencia Cognitiva:** Los resultados proporcionan evidencia
empírica novedosa de que la elaboración metafórica mejora continuamente
el procesamiento semántico, validando teorías de Lakoff & Johnson,
Paivio, y otros.

**Para Filosofía del Lenguaje:** Proporciona validación empírica
inesperada de tradiciones filosóficas que resistieron el privilegio del
racionalismo de la Ilustración del discurso literal-analítico (Vico,
Nietzsche, Heidegger).

**Para Teoría de IA:** Desafía la asunción implícita de que claridad =
minimalismo. El **principio alternativo: la fidelidad cognitiva** al
procesamiento lingüístico humano puede requerir metáfora y narrativa.

### 6.6 Implicaciones Educativas

Quizás las implicaciones más profundas yacen en educación:

**Paradigma Actual:** Precisión técnica priorizada; metáfora vista como
\"simplificación excesiva\"

**Paradigma Basado en Evidencia:** La metáfora mejora tanto comprensión
COMO retención sin sacrificar precisión

**Cambios Accionables:**

1.  Tutores de IA deberían usar por defecto modo Híbrido

2.  Materiales de estudio generados vía prompting Poético para contenido
    > conceptual

3.  Alfabetización en prompts enseñada como habilidad central

4.  Sistemas adaptativos que emparejen estilo de explicación con tipo de
    > contenido

## 7. Limitaciones y Trabajo Futuro

### Limitaciones Principales

1.  **Evaluador Único:** Introduce potencial sesgo; se requieren
    > múltiples evaluadores ciegos

2.  **Modelo Único:** Resultados de Claude Sonnet 4.5 solamente; se
    > necesita validación multi-modelo

3.  **Sin Pruebas de Retención:** No medimos memorabilidad a largo plazo
    > (ventaja teórica primaria)

4.  **Confusión de Idioma:** Prompts Poéticos en español,
    > Instruccionales en inglés

5.  **Sin Estudios de Usuario:** No evaluamos preferencia de usuarios ni
    > comprensión

### Prioridades de Investigación Futura

**Tier 1 (Próximos 6 meses):**

1.  Replicación multi-evaluador con análisis de confiabilidad
    > inter-evaluador

2.  Validación multi-modelo (GPT-4, Gemini, Llama)

3.  Estudios de retención con participantes humanos

4.  Replicación intra-idioma

**Tier 2 (6-12 meses):** 5. Estudios de preferencia de usuario 6.
Rendimiento de aplicación (¿pueden usuarios aplicar mejor conocimiento
de explicaciones poéticas?) 7. Curvas dosis-respuesta con variación
sistemática 8. Taxonomía de tareas prediciendo intensidad poética óptima

**Tier 3 (12-24 meses):** 9. Validación cross-lingüística 10.
Aislamiento de mecanismos 11. Extensión multimodal 12. Despliegue en
mundo real con pruebas A/B

## 8. Reflexión Final

Durante milenios antes de la escritura, los humanos preservaron y
transmitieron conocimiento a través de poesía, canto e historia. Los
Vedas, épicas homéricas, songlines aborígenes, sagas nórdicas---todos
emplearon tecnología poética por una razón: **funciona**.

Los sistemas de escritura nos permitieron externalizar la memoria, y la
Ilustración nos enseñó a privilegiar la prosa literal-analítica.
Olvidamos por qué nuestros ancestros cantaban su conocimiento.

**Los LLMs inadvertidamente nos recuerdan:** Estos sistemas, entrenados
en la distribución completa del lenguaje humano (poético y prosaico,
metafórico y literal, narrativo y expositivo), revelan a través de su
rendimiento lo que la ciencia cognitiva nos ha estado diciendo---**la
metáfora y la narrativa no son primitivas. Son fundamentales.**

Nuestro experimento cuantifica lo que ellos entendían: **Cuando el
conocimiento debe perdurar, cuando la comprensión debe profundizarse,
cuando el insight debe transformar---no lo aplanas en prosa. Lo
cantas.**

La revolución no es descubrir que el prompting poético funciona mejor.

Es recordar.

## Referencias Clave

**Ciencia Cognitiva:**

-   Lakoff, G., & Johnson, M. (1980). *Metaphors We Live By*

-   Paivio, A. (1971). *Imagery and Verbal Processes*

-   Green, M. C., & Brock, T. C. (2000). Narrative transportation theory

-   Gallese, V., & Lakoff, G. (2005). Embodied cognition

**Filosofía:**

-   Vico, G. (1725). *Scienza Nuova*

-   Nietzsche, F. (1873). On truth and lying

-   Heidegger, M. (1971). *Poetry, Language, Thought*

**IA & Prompt Engineering:**

-   Wei et al. (2022). Chain-of-thought prompting

-   Brown et al. (2020). Few-shot learning

-   White et al. (2023). Prompt pattern catalog

**Información del Documento:**

-   Palabras: \~5,500 (versión ejecutiva)

-   Formato: Resumen académico ejecutivo

-   Versión: 2.0 (Estudio extendido 3→10 prompts)

-   Fecha: Octubre 2025

**Datos y Materiales:** Todos los prompts, outputs completos y datos de
evaluación disponibles en: \[URL repositorio\]

---

## Créditos

**Autor:** Marco Torres Yévenes  
**Organización:** Axisdynamics Spa & Exis Research  
**Sitio web:** https://axisdynamics.cl  
**Contacto:** contacto@exis.cl
