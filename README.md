# SharpX
# Plataforma Web Inteligente para la Prevención de Ludopatía y Análisis Estadístico

## 1. Problema
El auge de las plataformas de apuestas digitales y la proliferación de "pseudotipsters" en redes sociales han impulsado comportamientos impulsivos y desinformación financiera en jóvenes universitarios. La falta de herramientas técnicas accesibles impide calcular el Valor Esperado (EV) y reconocer patrones de riesgo conductual (como la persecución de pérdidas), derivando en pérdidas patrimoniales y ludopatía digital.

## 2. Objetivos
### Objetivo General
Desarrollar una plataforma web inteligente que integre cálculo probabilístico de Valor Esperado (EV) y asistencia conductual mediante Inteligencia Artificial para mitigar la toma de decisiones impulsivas y prevenir la ludopatía en apostadores deportivos en México.

### Objetivos Particulares
1. Diseñar la arquitectura de software y el modelo de datos relacional para el registro estructurado de operaciones de apuestas, métricas de rendimiento y trazabilidad del perfil del usuario.
2. Implementar un motor algorítmico que procese cuotas de APIs deportivas para calcular el Valor Esperado (EV) y el rendimiento estadístico (Yield y Efectividad).
3. Integrar un agente conversacional basado en Modelos de Lenguaje (LLM) con directivas éticas de juego responsable y validación semántica de justificación técnica previa a cada registro.
4. Validar la efectividad del sistema y la usabilidad de la interfaz mediante pruebas de estrés algorítmico, auditorías de prompts preventivos y simulaciones de usuario.

## 3. Alcance
* Cobertura inicial en fútbol profesional (Liga MX y principales ligas internacionales) con cuotas obtenidas vía API REST.
* Motor automatizado de cálculo de Valor Esperado ($EV = (Probabilidad \times Cuota) - 1$).
* Dashboard financiero con métricas de Bankroll, Yield, ROI y tasa de acierto.
* Módulo de Justificación Obligatoria asistido por IA para filtrar entradas impulsivas.
* Módulo de autenticación y gestión de perfil de usuario.

## 4. Fuera de Alcance
* No procesa transacciones con dinero real (no es casa de apuestas ni procesador de pagos).
* No genera pronósticos automáticos infalibles ni garantiza ganancias.
* No incluye deportes secundarios en esta fase (carreras de caballos, esports o ligas menores no estandarizadas).
* No sustituye atención médica o terapia psicológica formal contra la ludopatía severa.

## 5. MVP (Minimum Viable Product)
Una aplicación web funcional donde el usuario puede registrar su bankroll inicial, consultar el Valor Esperado (EV) de un partido de fútbol seleccionado, ingresar un pronóstico pasando por la validación de la IA (que bloquea o alerta justificaciones impulsivas) y visualizar en su panel personal el impacto real en su Yield y balance general.
