# Guía de estilo — introducciones IMRaD de ingeniería

Este archivo contiene ejemplos de frases, transiciones y párrafos que definen el tono correcto para las introducciones. Úsalo como referencia antes de redactar.

---

## Tono general

El tono ideal combina:
- **Precisión técnica** — los conceptos se nombran correctamente
- **Claridad narrativa** — cualquier persona con nivel preparatoria puede seguir el hilo
- **Formalidad relajada** — académico pero no denso, no usa palabras rebuscadas sin necesidad
- **Voz activa preferida** — "El modelo permite..." en lugar de "Es posible que sea permitido..."

No suena como enciclopedia. Suena como alguien que sabe mucho y lo explica bien.

---

## Frases de apertura que funcionan

✅ Bien:
- "Cuando giramos el volante de un automóvil, pocas veces pensamos en toda la ciencia y precisión mecánica que hacen posible ese movimiento."
- "Cada vez que una vacuna llega a un centro de salud en perfectas condiciones, detrás existe toda una cadena logística que trabajó para mantenerla a la temperatura correcta."
- "La pregunta parece simple: ¿por qué un objeto cae? Sin embargo, responderla con precisión requiere entender las mismas leyes que permiten predecir el movimiento de los planetas."

❌ Evitar:
- "La transferencia de calor es un fenómeno importante en ingeniería."
- "En este trabajo se estudiarán los siguientes conceptos:"
- "El objetivo de esta introducción es explicar..."

---

## Transiciones entre párrafos

Usar frases que conecten la idea anterior con la siguiente:

- "A partir de este principio, es posible entender por qué..."
- "Comprender este mecanismo resulta fundamental para lo que sigue..."
- "Este comportamiento no ocurre de forma aislada — está directamente relacionado con..."
- "Lo anterior establece la base para introducir el concepto central de este trabajo:..."
- "Con esta base conceptual, el siguiente paso es definir con precisión..."
- "En este contexto, [concepto] emerge como la herramienta que permite..."

---

## Cómo introducir conceptos técnicos

No hacer: definición seca → ejemplo
Sí hacer: situación → necesidad del concepto → definición → relación con lo anterior

Ejemplo ❌:
> "La Ley de Fourier establece que el flujo de calor es proporcional al gradiente de temperatura."

Ejemplo ✅:
> "Para cuantificar con qué rapidez el calor atraviesa las paredes del contenedor, se recurre a la Ley de Fourier, que relaciona el flujo de calor con el gradiente de temperatura y con la conductividad térmica del material. En esencia, esta ley dice que cuanto mayor es la diferencia de temperatura entre dos puntos, y cuanto más conductor es el material que los separa, más rápido fluye el calor entre ellos."

---

## Cómo justificar simplificaciones

El modelo siempre tiene límites. Explicarlos así:

> "El alcance de este análisis se limita a la conducción de calor a través de sólidos. Por esta razón, los efectos de convección y radiación no se modelan en esta primera etapa, con el fin de trabajar con un modelo más controlado y enfocado en el mecanismo que tiene mayor influencia en la selección de materiales y espesores del contenedor."

---

## Cómo cerrar la introducción

El cierre siempre anuncia la estructura del resto del documento. No es un resumen — es un mapa:

> "El reporte se organiza de la siguiente manera: primero se describen los métodos empleados, incluyendo el montaje experimental, la formulación del modelo y el procedimiento de simulación. Después se presentan los resultados obtenidos. Finalmente, se discuten las implicaciones físicas e ingenieriles de los resultados y su utilidad para comprender el comportamiento térmico del sistema estudiado."

---

## Ejemplos de párrafos de contexto real (estilo de referencia)

### Contexto amplio que conecta a la aplicación real:
> "La transferencia de calor es un fenómeno cotidiano: ocurre cuando una bebida caliente se enfría sobre una mesa, cuando un cubo de hielo se derrite fuera del congelador o cuando un recipiente no logra conservar su contenido a la misma temperatura por mucho tiempo. En todos estos casos, la energía térmica fluye de manera natural desde la región con mayor temperatura hacia la de menor temperatura hasta que el sistema tiende al equilibrio térmico. Aunque este proceso parece simple en la vida diaria, comprenderlo es fundamental en ingeniería, ya que muchos sistemas dependen precisamente de controlar qué tan rápido entra o sale calor."

### Justificación de herramienta computacional:
> "El marco conceptual anterior permite enlazar la observación experimental con la formulación del modelo y con la simulación numérica desarrollada en SolidWorks Flow Simulation — herramienta que el propio fabricante describe como una solución de dinámica de fluidos computacional integrada en SOLIDWORKS 3D CAD para estudiar flujos y transferencia de calor en diseños de ingeniería (Dassault Systèmes, s. f.)."

---

## Longitudes de referencia por sección

Para una introducción de 2 cuartillas (~500 palabras):
- Gancho + contexto amplio: ~80 palabras
- Relevancia + aplicación real: ~80 palabras
- Marco conceptual (2-4 conceptos): ~220 palabras
- Planteamiento + objetivo + simplificaciones: ~70 palabras
- Cierre con estructura: ~50 palabras

Para 1 cuartilla (~250 palabras): reducir marco conceptual a los 2 conceptos más importantes.
Para 3+ cuartillas: expandir marco conceptual con más profundidad en cada concepto y sus relaciones.

---

## Lo que nunca debe aparecer

- Listas con viñetas dentro de la introducción (es prosa continua)
- Subtítulos dentro de la introducción
- Oraciones que empiecen con "En conclusión" o "En resumen" (eso va en Discusión)
- Frases vacías como "Este trabajo es muy importante porque..."
- Referencias inventadas o con datos no verificados sin `[CITAR]`
