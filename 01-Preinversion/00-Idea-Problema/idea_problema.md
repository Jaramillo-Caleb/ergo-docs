# Idea de Proyecto

**Nombre del proyecto:** Ergo
**Autor(es):** Caleb Josué Jaramillo Rendón, Rubén Darío Cárdenas Espinosa  
**Fecha:** 12/10/2026
**Versión:** 0.1
**Cambios de esta versión:** Primera versión

---

## Problema que resuelve

El mantenimiento prolongado de posturas estáticas e inadecuadas frente a pantallas de ordenador provoca trastornos musculoesqueléticos (TME) progresivos, principalmente molestias cervicales, dorsales y lumbares. A esto se suma la pérdida de productividad derivada de la fatiga física y la falta de pausas activas oportunas durante las jornadas continuas frente al computador.

## ¿Quién lo tiene?

Trabajadores remotos (teletrabajadores) y estudiantes de educación superior que pasan jornadas intensivas (más de 6 a 8 horas diarias) frente al computador de escritorio o portátil en puestos de trabajo no estandarizados, operando frecuentemente en equipos con recursos de hardware limitados.

## Evidencia de que el problema existe

1. **Datos oficiales de salud laboral:** Según el Consejo de Seguridad de Colombia (2023), los trastornos musculoesqueléticos representan la gran mayoría de las enfermedades profesionales diagnosticadas en el país.
2. **Literatura científica regional:** Múltiples estudios en entornos latinoamericanos documentan una alta prevalencia de dolor cervical, dorsal y lumbar en estudiantes universitarios y teletrabajadores expuestos a pantallas sin supervisión ergonómica.
3. **Limitaciones de las soluciones actuales de software:**
   - *Alto consumo de recursos:* Soluciones comerciales como SitApp demandan entre 6,5% y 21% de CPU y más de 1 GB de RAM, ralentizando equipos de gama media/baja.
   - *Riesgos de privacidad:* Dependen de arquitecturas en la nube que transmiten datos biométricos sensibles de la cámara a servidores remotos.
   - *Fragmentación:* Tratan la postura, la productividad y el descanso como herramientas aisladas que interrumpen el flujo de trabajo.

## Descripción breve de la solución

Proponer una aplicación de escritorio ligera que aproveche la cámara web estándar del computador para analizar la postura del usuario en tiempo real mediante visión por computador y alertarlo cuando se encorve, integrando a su vez un temporizador de productividad (tipo Pomodoro) y pausas activas para estructurar descansos saludables a lo largo del día.

## Potencial de innovación

- **Privacidad desde el diseño:** Se plantea que el análisis de la cámara se ejecute completamente en el equipo local (*edge computing*), sin requerir conexión a internet ni enviar vídeo a servidores en la nube.
- **Integración ergonomía + productividad:** Unificar en una sola herramienta la corrección postural y la gestión del tiempo de trabajo, evitando que el usuario deba tener múltiples programas abiertos para cuidarse y concentrarse.
- **Enfoque en bajo consumo:** Diseñar el sistema desde el inicio con algoritmos eficientes para que pueda ejecutarse en computadores convencionales de gama media o baja sin congelar el equipo ni interferir con las aplicaciones de trabajo diarias.

---

### Historial de versiones

| Versión | Fecha | Qué cambió |
|---------|-------|------------|
| 0.1 | 12/10/2026 | Primera versión |
