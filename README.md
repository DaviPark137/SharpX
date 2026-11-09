# SharpX
### Plataforma Web Inteligente para la Prevención de Ludopatía y Análisis Estadístico

## 1. Problema y Objetivos

### Planteamiento del Problema
Hoy en día, el acceso inmediato a las apuestas deportivas en plataformas digitales lleva a que miles de usuarios —especialmente jóvenes universitarios con poca experiencia en análisis estadístico— tomen decisiones en cuestión de segundos guiados por impulsos emocionales, fanatismo o simples corazonadas, sin calcular probabilidades realistas ni medir el riesgo real de cada jugada. Esta falta de criterio provoca una mala gestión del *bankroll*, pérdidas económicas constantes y conductas asociadas a la ludopatía.

Aunque en internet abundan sitios de estadísticas, momios y hojas de registro, la información se encuentra dispersa y saturada de datos fríos. Actualmente, los usuarios no cuentan con una herramienta integrada que les ayude a calcular el Valor Esperado (**EV**) ni a evaluar la calidad de sus propias decisiones antes de apostar, impidiéndoles distinguir entre una jugada bien fundamentada con argumentos objetivos y un arranque impulsivo del momento.

### Objetivo General
Desarrollar una plataforma web inteligente orientada a la prevención de la ludopatía en la población universitaria con un enfoque en apuestas deportivas, mediante el uso de inteligencia artificial y herramientas de análisis estadístico.

### Objetivos Particulares
1. **Analizar** los patrones de comportamiento, hábitos de consumo y sesgos cognitivos asociados a las apuestas deportivas en la población estudiantil universitaria, mediante instrumentos de recolección de datos para determinar los parámetros críticos de riesgo y prevención de ludopatía.
2. **Diseñar** la arquitectura de software y los modelos algorítmicos basados en el cálculo de Valor Esperado (**+EV**) y detección de anomalías conductuales, estableciendo los criterios técnicos necesarios para la validación obligatoria de operaciones.
3. **Desarrollar** una plataforma web responsiva con módulos de gestión de riesgo, registro analítico de apuestas y asistencia con inteligencia artificial, adaptando la experiencia de usuario a las necesidades del entorno universitario.
4. **Evaluar** la efectividad de la plataforma en la mitigación de decisiones impulsivas y el desempeño financiero de los usuarios universitarios, contrastando métricas cuantitativas (*Yield*, *ROI*, frecuencia de apuestas) antes y después del uso del sistema.

---

## 2. Siguiente Paso Técnico
Diseñar y validar el esquema de base de datos relacional y los endpoints de la API REST para el registro estructurado de apuestas simuladas, el motor de cálculo de **+EV** y la captura obligatoria de la justificación analítica previa asistida por IA.

---

## 3. Alcance
* Cobertura inicial en fútbol profesional (Liga MX y principales ligas internacionales) con cuotas obtenidas vía API REST.
* Motor automatizado de cálculo de Valor Esperado: `EV = (Probabilidad × Cuota) - 1`.
* Dashboard financiero con métricas de *Bankroll*, *Yield*, *ROI*, tasa de acierto y frecuencia de apuestas.
* Módulo de Justificación Obligatoria asistido por IA para detectar anomalías conductuales y filtrar entradas impulsivas.
* Módulo de autenticación y gestión de perfil de usuario adaptado al entorno universitario.

---

## 4. Fuera de Alcance
* No procesa transacciones con dinero real (no es casa de apuestas ni procesador de pagos).
* No genera pronósticos automáticos infalibles ni garantiza ganancias.
* No incluye deportes secundarios en esta fase (carreras de caballos, esports o ligas menores no estandarizadas).
* No sustituye atención médica o terapia psicológica formal contra la ludopatía severa.

---

## 5. MVP (Minimum Viable Product)
Una aplicación web funcional donde el usuario universitario puede registrar su *bankroll* inicial, consultar el Valor Esperado (**EV**) de un partido de fútbol seleccionado, ingresar un pronóstico pasando obligatoriamente por la validación semántica de la IA (que alerta o frena justificaciones emocionales/impulsivas) y visualizar en su panel personal el impacto cuantitativo en su *Yield*, *ROI* y balance general.
