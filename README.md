# SharpX
# Plataforma Web Inteligente para la Prevención de Ludopatía y Análisis Estadístico

## Problema y objetivo

### Problema
El auge de las plataformas de apuestas digitales y la proliferación de "pseudotipsters" en redes sociales han impulsado conductas impulsivas y desinformación financiera en jóvenes universitarios en México. La falta de herramientas técnicas accesibles impide calcular el Valor Esperado ($EV$) y reconocer sesgos cognitivos como la persecución de pérdidas, derivando en pérdidas patrimoniales y ludopatía digital recurrente.

### Objetivo
Desarrollar e implementar en la plataforma SharpX un módulo con evaluación semántica por IA y cálculo de Valor Esperado ($EV$) que obligue a la justificación analítica de pronósticos, logrando reducir al menos en un 30% las decisiones de juego impulsivas en la cohorte piloto durante el ciclo académico 2026B.

### Siguiente paso
Diseñar y validar el esquema de base de datos relacional y los endpoints de la API REST para el registro estructurado de apuestas simuladas y la captura obligatoria de la justificación técnica previa.

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
