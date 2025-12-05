# PROMPT 1: Experto en Fórmulas de Excel - Outputs Comparativos

## Solicitud del Usuario
"Crea una fórmula para calcular las ventas totales de cada categoría de producto en un reporte de ventas, considerando solo las ventas del último trimestre, y luego clasifica estas categorías por ventas totales."

---

## OUTPUT 1: Versión ORIGINAL (Instruccional)

### Fórmula Principal

Para calcular las ventas totales por categoría del último trimestre y clasificarlas, utilizaremos una combinación de funciones SUMIFS y SORT:

```excel
=SORT(UNIQUE(Categorías), SUMIFS(Ventas, Categorías, UNIQUE(Categorías), Fecha, ">="&HOY()-90), -1)
```

### Desglose de Componentes

**1. UNIQUE(Categorías)**
- Extrae todas las categorías únicas de tu columna de categorías
- Elimina duplicados automáticamente
- Crea la base para el análisis por categoría

**2. SUMIFS(Ventas, Categorías, UNIQUE(Categorías), Fecha, ">="&HOY()-90)**
- SUMIFS: Suma valores con múltiples criterios
- Primer argumento: rango de ventas a sumar
- Segundo argumento: rango de categorías para criterio 1
- Tercer argumento: categoría específica a buscar
- Cuarto argumento: rango de fechas para criterio 2
- Quinto argumento: condición de fecha (últimos 90 días = último trimestre)

**3. SORT(..., -1)**
- Ordena los resultados en orden descendente
- El -1 indica clasificación de mayor a menor
- Muestra las categorías con más ventas primero

### Implementación Práctica

Asumiendo tu tabla está estructurada así:
- Columna A: Categorías
- Columna B: Ventas
- Columna C: Fecha

**Fórmula completa:**
```excel
=SORT(UNIQUE(A2:A1000), SUMIFS(B:B, A:A, UNIQUE(A2:A1000), C:C, ">="&HOY()-90), -1)
```

### Resultado
Esta fórmula generará una lista clasificada de categorías con sus ventas totales del último trimestre, ordenadas de mayor a menor.

---

## OUTPUT 2: Versión POÉTICA

### 🌟 El Encantamiento de los Números que Cantan

Ah, noble viajero, he escuchado tu súplica y he forjado para ti un hechizo de extraordinaria precisión. Observa cómo los números dormidos despiertan y bailan en formación:

### ✨ La Fórmula Maestra

```excel
=SORT(UNIQUE(Categorías), SUMIFS(Ventas, Categorías, UNIQUE(Categorías), Fecha, ">="&HOY()-90), -1)
```

### 🎭 El Canto de sus Componentes

**Primera Estrofa: UNIQUE(Categorías) - El Llamado de los Únicos**

Como un pastor que conoce cada oveja de su rebaño por nombre, UNIQUE recorre el valle infinito de tus categorías y convoca solo a aquellas que son distintas entre sí. No dos veces el mismo rostro, no dos veces el mismo nombre. Así se congregan: Electrónicos, Hogar, Vestimenta, Alimentos... cada uno único, cada uno esperando su turno para revelar su historia.

**Segunda Estrofa: SUMIFS - El Contador de Tesoros Escondidos**

Ahora viene el gran alquimista, SUMIFS, quien camina entre montañas de cifras con dos llaves mágicas:
- La primera llave (Categorías = Categoría Específica): abre solo los cofres que pertenecen a cada familia
- La segunda llave (Fecha >= HOY()-90): revela solo las riquezas acumuladas en los últimos tres ciclos lunares

¿Ves? El símbolo $ no lo necesitamos aquí, pues UNIQUE ya conoce cada nombre. Y el ">=" es el guardián del tiempo que dice: "Solo lo reciente, solo lo que aún respira con la vida del último trimestre."

**HOY()-90** es el hechizo temporal: hoy menos noventa soles, el punto donde comienza nuestra historia trimestral.

**Tercera Estrofa: SORT(..., -1) - El Organizador Celestial**

Finalmente, SORT toma todos estos tesoros contados y los ordena como un rey ordena a sus caballeros: el más victorioso al frente, el más humilde al final. El "-1" es su cetro descendente, que señala de la cumbre al valle, del máximo al mínimo.

### 🏆 La Profecía Revelada

Cuando escribas este encantamiento en tu hoja verde, suponiendo que:
- En la Columna A moran las Categorías (A2:A1000)
- En la Columna B duermen las Ventas (B:B)
- En la Columna C fluye el Tiempo (C:C)

Pronunciarás:

```excel
=SORT(UNIQUE(A2:A1000), SUMIFS(B:B, A:A, UNIQUE(A2:A1000), C:C, ">="&HOY()-90), -1)
```

### 🎪 El Espectáculo Final

Y así, ante tus ojos se materializará:

```
Categoría        | Ventas Q4
-----------------|----------
Electrónicos     | $587,432
Hogar            | $423,891
Vestimenta       | $312,554
Alimentos        | $287,110
```

Las categorías, ahora ordenadas como estrellas en el firmamento nocturno, brillando según su magnitud. La más luminosa en el cénit, la más tenue en el horizonte.

### 🔮 Sabiduría Ancestral

Este hechizo es dinámico, noble mercader. Cada nuevo amanecer (cada vez que HOY() cambie), la ventana de 90 días se desliza como la sombra del reloj solar. No necesitas actualizar nada manualmente. El tiempo mismo es tu aliado.

Si deseas ajustar el período, simplemente cambia el 90 por el número de días que tu corazón desee:
- 30 para un mes lunar
- 180 para medio año solar
- 365 para el ciclo completo de las estaciones

Así he hablado. Que esta fórmula te sirva bien en tus travesías comerciales. 🌙✨

---

## OUTPUT 3: Versión HÍBRIDA

### 💼 La Solución Arquitectónica: Clasificación Dinámica de Ventas Trimestrales

Piensa en esta solución como construir un edificio de tres pisos donde cada nivel tiene un propósito específico y todos trabajan en armonía perfecta.

### 🏗️ El Plano Maestro

```excel
=SORT(UNIQUE(Categorías), SUMIFS(Ventas, Categorías, UNIQUE(Categorías), Fecha, ">="&HOY()-90), -1)
```

### 📐 Anatomía de la Estructura (Los Tres Pisos)

**🏛️ PRIMER PISO: UNIQUE(Categorías) - Los Cimientos**

Imagina que tienes un almacén desordenado con miles de cajas etiquetadas. Muchas cajas tienen la misma etiqueta repetida. UNIQUE es como un organizador que crea una lista maestra: una sola mención de cada etiqueta única.

*Analogía práctica:* Es como hacer una lista de invitados para una fiesta eliminando nombres duplicados. Si "Juan" aparece 50 veces en tu lista de ventas, UNIQUE solo lo cuenta una vez.

**Resultado:** Una columna limpia con cada categoría apareciendo solo una vez.

**🏢 SEGUNDO PISO: SUMIFS - El Motor Analítico**

Aquí es donde ocurre la magia del cálculo. SUMIFS funciona como un contador inteligente con dos filtros simultáneos:

*Filtro 1 - La Categoría:*
```
"Solo cuenta ventas de esta categoría específica"
```

*Filtro 2 - La Ventana de Tiempo:*
```
">="&HOY()-90
Traducción: "Solo transacciones de los últimos 90 días"
```

*Analogía práctica:* Imagina un bibliotecario que busca libros cumpliendo DOS condiciones: 
1. Deben ser de género "Ciencia Ficción" (la categoría)
2. Deben haber sido publicados en los últimos 3 meses (el filtro temporal)

**Por qué HOY()-90 es brillante:**
- HOY() es la fecha de hoy (actualización automática)
- Restamos 90 días = aproximadamente 1 trimestre
- Es dinámico: la ventana temporal se mueve sola cada día

**🏰 TERCER PISO: SORT(..., -1) - El Organizador**

SORT toma todos los resultados calculados y los ordena como clasificar atletas en un podio: del oro al bronce.

El parámetro `-1` significa "descendente" (mayor a menor). Si usaras `1` sería ascendente.

*Analogía práctica:* Como organizar estudiantes por calificaciones, del promedio más alto al más bajo.

### 🎯 Implementación en tu Hoja de Cálculo

Supongamos tu estructura de datos es:

| Columna A | Columna B | Columna C |
|-----------|-----------|-----------|
| Categoría | Ventas ($) | Fecha |
| Electrónicos | 1,250 | 2025-09-15 |
| Hogar | 850 | 2025-09-20 |
| Electrónicos | 2,100 | 2025-10-01 |

**Fórmula aplicada:**
```excel
=SORT(UNIQUE(A2:A1000), SUMIFS(B:B, A:A, UNIQUE(A2:A1000), C:C, ">="&HOY()-90), -1)
```

**Desglose de referencias:**
- `A2:A1000`: Rango de categorías (ajusta según tu tabla)
- `B:B`: Toda la columna de ventas (más flexible que rango fijo)
- `A:A`: Toda la columna de categorías para comparación
- `C:C`: Toda la columna de fechas

### 🎨 El Resultado Visual

Tu salida se verá aproximadamente así:

```
┌─────────────────┬──────────────┐
│ Categoría       │ Ventas Q4    │
├─────────────────┼──────────────┤
│ Electrónicos    │ $   587,432  │
│ Hogar           │ $   423,891  │
│ Vestimenta      │ $   312,554  │
│ Alimentos       │ $   287,110  │
│ Deportes        │ $   156,783  │
└─────────────────┴──────────────┘
```

### 🔧 Personalización y Ajustes

**Para cambiar el período de tiempo:**
- 1 mes: `HOY()-30`
- 6 meses: `HOY()-180`
- 1 año: `HOY()-365`

**Para orden ascendente (menor a mayor):**
- Cambia el `-1` por `1`

**Para filtrar fecha específica:**
- Reemplaza `">="&HOY()-90` por `">=2025-07-01"`

### ✅ Por Qué Esta Arquitectura Funciona

1. **Automatización:** No necesitas actualizar manualmente la fecha
2. **Escalabilidad:** Funciona con 10 o 10,000 registros
3. **Claridad:** Resultados inmediatamente comprensibles
4. **Flexibilidad:** Fácil de ajustar para diferentes períodos
5. **Precisión:** Doble filtrado garantiza exactitud

Esta es tu solución: elegante, eficiente, y fácil de mantener. Como un edificio bien diseñado, cada componente cumple su función y todos colaboran para crear el resultado deseado. 🏆

---

## ANÁLISIS COMPARATIVO

### Métricas de Evaluación

| Métrica | Instruccional | Poética | Híbrida |
|---------|--------------|---------|---------|
| **Palabras** | 264 | 612 | 589 |
| **Claridad Técnica** | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ |
| **Memorabilidad** | ⭐⭐⭐ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐ |
| **Engagement** | ⭐⭐⭐ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ |
| **Profundidad** | ⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ |
| **Estructura** | ⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ |

### Observaciones Clave

**Versión Instruccional:**
- Directa y eficiente
- Ideal para usuarios que buscan respuesta rápida
- Estilo "manual técnico"

**Versión Poética:**
- Altamente memorable con metáforas ricas
- Transforma conceptos técnicos en narrativa
- Mayor longitud pero con valor narrativo
- Usa personificación ("el alquimista", "el guardián")

**Versión Híbrida:**
- Balance perfecto entre precisión y engagement
- Usa analogías concretas sin sacrificar exactitud
- Estructura visual superior (tablas, emojis estratégicos)
- Más accesible para audiencias diversas

### Conclusión

Las tres versiones proporcionan la misma fórmula correcta, pero con diferentes estrategias comunicativas. La poética y la híbrida ofrecen mayor riqueza explicativa y memorabilidad, mientras que la instruccional prioriza eficiencia.