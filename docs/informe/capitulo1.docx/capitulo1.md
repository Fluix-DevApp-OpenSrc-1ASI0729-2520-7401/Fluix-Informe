# 1.1.1. Descripción de la Startup

**Fluix** es una startup tecnológica enfocada en la gestión integral y en tiempo real de líquidos para hogares y empresas. Nuestra plataforma, **Droplet**, combina sensores de nivel, caudal y calidad (p. ej., temperatura, densidad y opcionales como pH o conductividad), conectividad IoT y una capa de analítica, alertas e históricos para monitorear consumos, capacidades y condiciones de cada tanque o línea.

Basado en un modelo modular y sostenible, Fluix se adapta a escenarios residenciales —control de cisternas, consumo y detección de fugas— y empresariales/industriales —cervecerías, almacenamiento de combustibles u otros procesos— mediante módulos de medición e integraciones según el caso.

La innovación de Fluix radica en la integración de datos en tiempo real con automatización y analítica predictiva para anticipar reabastecimientos, prevenir riesgos y optimizar decisiones. Cuando un sensor detecta cambios (descenso abrupto de nivel, caudal anómalo, temperatura fuera de rango o variaciones de densidad), envía una señal a la plataforma para actualizar dashboards, disparar alertas y registrar trazabilidad.

**Misión:** Ser el puente entre personas y operaciones con sus fluidos críticos, optimizando el uso, la seguridad y la sostenibilidad en tiempo real. Con **Droplet** facilitamos el monitoreo automatizado de nivel, consumo y calidad —desde el hogar hasta la planta industrial—, generando ahorros, continuidad operativa y tranquilidad.

**Visión:** Convertirnos en la plataforma líder de gestión inteligente de líquidos en los próximos 5 años, impulsando hogares e industrias más eficientes y seguras mediante soluciones IoT y de analítica escalables y sostenibles que se adapten a diferentes líquidos y requisitos operativos.

---

# 1.2. Solution Profile — Resumen ejecutivo

- **Producto:** **Droplet**, app web/móvil de monitoreo y gestión de líquidos en tiempo real.
- **Componentes:** sensores de nivel, caudal y calidad; conectividad IoT; analítica; alertas; históricos; APIs para integraciones (ERP/CMMS/BMS).
- **Para quién:** hogares con tanques/cisternas; empresas de bebidas, combustibles y otros procesos.
- **Qué hace:** visibilidad de nivel/consumo/condiciones; alertas por umbrales; predicción de reabastecimiento; reportes; operación multi‑tanque y multi‑sitio.
- **Propuesta de valor:** menos desperdicio y mermas; continuidad operativa; mayor seguridad; mejores decisiones basadas en datos.
- **Diferenciadores:** modularidad multi‑líquido; analítica predictiva; despliegue simple con integradores; experiencia de uso clara.
- **KPIs de éxito (ejemplos):** stockouts/mes, mermas, tiempo en rondas manuales, desviaciones de parámetros, activación/retención/CSAT.

---

# 1.2.1. Antecedentes y problemática

**Qué (What):**
- Falta de visibilidad en tiempo real sobre nivel, consumo y condiciones del líquido.
- Costos por desperdicio (fugas, sobrellenado, evaporación no controlada).
- Paradas por desabastecimiento y riesgos por parámetros fuera de rango.
- Información fragmentada en lecturas manuales o sistemas no integrados.

**Cuándo (When):**
- Picos de consumo (turnos críticos).
- Etapas sensibles de proceso (fermentación, mezclas, transferencia, despacho).
- Eventos de riesgo (ascenso de temperatura, caída abrupta de nivel).

**Uso del producto (¿Cuándo lo usa el cliente?):**
- Planificar consumos/producción.
- Monitorear en tiempo real y recibir alertas.
- Auditar históricos (costos, mermas, cumplimiento).

**Dónde (Where):**
- Hogares con tanques/cisternas.
- Operaciones con múltiples tanques (agua de proceso, bebidas, combustibles u otros líquidos permitidos).
- Sitios sin instrumentación IoT o con instrumentación aislada y no integrada.

**Quién (Who):**
- Hogar: propietarios/administradores de vivienda.
- Empresa: jefes de planta, mantenimiento, calidad, EHS y logística; gerencias que buscan control de costos.
- Integradores/técnicos: despliegue de sensores y gateways.

**A quién afecta:**
- Usuarios residenciales y organizaciones que dependen de líquidos críticos para su operación.

**Quién lo utilizará:**
- Propietarios/administradores de viviendas; operadores, supervisores y responsables de mantenimiento/calidad; integradores que configuran y dan soporte.

**Por qué (Why):**
- Ausencia de medición continua y datos fragmentados o tardíos que impiden actuar a tiempo.
- Falta de umbrales, analítica y predicción que deriva en decisiones reactivas.

**Qué llevó al usuario a esta situación:**
- Dependencia de rondas manuales, hojas de cálculo y alarmas locales sin correlación ni trazabilidad centralizada.

**Cómo (How):**
- Sensores de nivel/caudal/calidad conectados a **Droplet** vía gateway/wi‑fi/LTE.
- App con dashboards, alertas, reportes e integraciones (ERP/CMMS/BMS) mediante API.

**Cómo nos conocerán:**
- Casos de uso (hogar, bebidas, combustibles), contenido educativo, pilotos con integradores y alianzas con distribuidores de sensores.

**Cuánto (How much):**
- Línea base por cliente con: frecuencia de stockouts, tiempo de rondas manuales, mermas/consumo no planificado y desviaciones de parámetros críticos por periodo.

---

# 1.2.2. Lean UX Process

Se adopta Lean UX para orientar el diseño hacia outcomes medibles, con ciclos Build–Measure–Learn:
1) Definir outcomes y métricas (↓ stockouts/mermas/tiempos de verificación; ↑ cumplimiento de parámetros y satisfacción).
2) Convertir supuestos en hipótesis comprobables.
3) Ejecutar experimentos rápidos: prototipos de interfaz, pilotos con 1–3 tanques, pruebas de alertas y predicción de reabastecimiento.
4) Instrumentar: eventos (p. ej., `tank.level_reading`, `alarm.triggered`, `refill.predicted`), dashboards y encuestas (CSAT/NPS).
5) Decidir: iterar, priorizar módulos (p. ej., calidad) o profundizar integraciones.

---

## 1.2.2.1. Lean UX Problem Statements

- El estado actual de la gestión de líquidos se ha centrado en lecturas manuales y datos fragmentados, generando desperdicio, riesgos operativos y paradas por desabastecimiento.
- Los productos/servicios existentes no unifican medición en tiempo real, alertas y predicción en una plataforma simple que se adapte a diferentes líquidos y escenarios.
- Nuestro producto abordará esta brecha mediante **Droplet**, que integra sensores de nivel/caudal/calidad, alertas configurables, analítica e históricos y predicción de reabastecimiento en una sola app.
- Enfoque inicial: hogares con tanques de agua y pymes de bebidas (pilotos de 1–3 tanques por sitio) para validar valor y escalabilidad.
- Éxito: reducción de stockouts y mermas, disminución del tiempo de verificación manual, aumento del uso activo y mejora en satisfacción.

---

## 1.2.2.2. Lean UX Assumptions

**Users**
- Residencial: propietarios/administradores que buscan ahorro, control y tranquilidad.
- Empresas/industria: jefes de planta, mantenimiento, calidad, EHS y logística que priorizan continuidad, seguridad y trazabilidad.
- Integradores técnicos: valoran despliegue simple, soporte remoto y margen de servicio.

**User Outcomes**
- Residencial: ver nivel/consumo y recibir alertas; reducir sorpresas en factura y planificar recargas.
- Bebidas: mantener temperatura/densidad en rango; reducir descarte y mejorar trazabilidad por lote/tanque.
- Combustibles/otros: evitar sobrellenado; detectar variaciones anómalas; obtener reportes de cumplimiento auditables.

**Suposiciones de Negocio**
- Existe demanda por una solución modular que unifique monitoreo multi‑líquido con analítica/predicción.
- Diferenciación por simplicidad de uso, configuración guiada por caso y escala (de 1 a muchos tanques).
- Modelo SaaS por tanque/mes y/o servicios de despliegue con integradores es viable.

**Suposiciones de Usuarios (preguntas guía)**
- ¿Quién utiliza nuestra plataforma? Hogares y organizaciones con líquidos críticos para su operación.
- ¿Cómo se integra en la rutina? Como panel de control y sistema de alertas que reduce rondas manuales y reacciones tardías.
- ¿Qué desafíos aborda? Falta de visibilidad, datos no integrados, parámetros fuera de rango y sorpresas por desabastecimiento.
- ¿Qué imagen deseamos proyectar? Eficiencia, confiabilidad e innovación aplicadas a gestión de líquidos.
- ¿Propósito fundamental? Facilitar la monitorización, prevención y decisión en el ciclo de gestión de líquidos.
- ¿Funcionalidades destacadas? Monitoreo en tiempo real, alertas por umbrales, predicción de reabastecimiento, reportes e históricos e integraciones.

---

## 1.2.2.3. Hipótesis (Lean UX)

> Formato: *Si implementamos [intervención], entonces lograremos [resultado esperado]; lo verificaremos cuando [indicador + umbral + ventana temporal].*

**Hipótesis 1 — Reducción de faltantes (stockouts)**
- Si habilitamos **alertas por umbrales** y **predicción de agotamiento**,  
- entonces disminuirán los eventos de **quedarse sin líquido**,  
- lo verificaremos cuando el número de **stockouts por mes** se reduzca ≥ 40 % respecto a la línea base durante 8 semanas, en pilotos con **n ≥ 10 tanques** (al menos en 2–3 sitios).

**Hipótesis 2 — Menos tiempo en rondas manuales**
- Si proporcionamos **tableros en tiempo real** que sustituyan parte de las verificaciones presenciales,  
- entonces caerá el **tiempo semanal** dedicado a rondas,  
- lo verificaremos cuando el autorreporte de horas por semana y los registros de acceso muestren una disminución ≥ 30 % sostenida por 6 semanas.

**Hipótesis 3 — Control de parámetros críticos (bebidas)**
- Si configuramos alertas de **temperatura** y **densidad** en etapas sensibles,  
- entonces disminuirán las lecturas **fuera de rango**,  
- lo verificaremos cuando el porcentaje de desviaciones caiga ≥ 50 % frente a la línea base en 2 ciclos de producción consecutivos.

**Hipótesis 4 — Ahorro por fugas y mermas**
- Si aplicamos **detección temprana** (caída de nivel/caudal anómalo) y **comparativas históricas**,  
- entonces bajará el **consumo no planificado**,  
- lo verificaremos cuando el consumo ajustado por estacionalidad disminuya 15–25 % en 3 meses, en **n ≥ 20 instalaciones**.

**Hipótesis 5 — Adopción y satisfacción**
- Si implementamos un **onboarding guiado** con **plantillas de umbrales** por caso de uso,  
- entonces aumentará la **activación temprana** y la **satisfacción del usuario**,  
- lo verificaremos cuando la **activación a los 14 días** sea ≥ 60 %, la **retención a los 60 días** sea ≥ 40 % y la **satisfacción promedio** sea ≥ 4.5/5, con **tasa de respuesta a encuestas ≥ 40 %** en el **cohorte piloto**.

---

# 1.3. Segmentos objetivo

## 1) Hogares con tanques/cisternas (Residencial)
**Descripción:** Viviendas que almacenan agua en cisternas o tanques elevados y requieren visibilidad de nivel, consumo y posibles fugas, así como alertas y predicción de reabastecimiento.
**Sexo:** Masculino y femenino.
**Edades:** 18–34, 35–54 y 55+.
**Nivel socioeconómico:** Principalmente Clases C y D, con presencia en Clase B (viviendas con mayor consumo: jardines, piscinas, riego).
**Satisfacción de necesidades:**
- Monitoreo de nivel en tiempo real.
- Detección de fugas (caudal anómalo).
- Alertas por umbrales.
- Comparativas de consumo por periodos.
- Predicción de recarga.

## 2) Pymes de bebidas (cervecerías artesanales y microcervecerías)
**Descripción:** Operaciones con múltiples tanques que requieren control de temperatura y densidad en etapas críticas, visibilidad de niveles/caudales y trazabilidad por lote para asegurar calidad y continuidad operativa.
**Sexo:** Masculino y femenino (roles operativos, producción, calidad).
**Edades:** Predominantemente 25–54.
**Nivel socioeconómico:** se clasifica por tamaño de empresa (micro, pequeña, mediana) y vertical (bebidas).
**Satisfacción de necesidades:**
- Medición de nivel/caudal/temperatura/densidad.
- Alertas por desviaciones y tableros en tiempo real.
- Históricos por lote y soporte a auditorías.
- Reducción de desperdicio, reprocesos y tiempos de verificación manual.
- Predicción de reabastecimientos de insumos.

## 3) Operadores de combustibles y almacenamiento (estaciones/depósitos)
**Descripción:** Negocios que administran tanques de combustible u otros líquidos energéticos y demandan monitoreo confiable de nivel, variaciones de temperatura/densidad, sobrellenado y pérdidas no previstas, con reportes auditables.
**Sexo:** Masculino y femenino (operaciones, mantenimiento, EHS).
**Edades:** 25–54.
**Nivel socioeconómico:** se segmenta por tamaño de operación (número de tanques/sitios) y regulación vigente.
**Satisfacción de necesidades:**
- Alertas de seguridad (umbrales de sobrellenado, variaciones anómalas).
- Reportes de cumplimiento y trazabilidad de eventos.
- Monitoreo remoto multi‑sitio.
- Disminución de riesgos operativos, pérdidas y paradas.
