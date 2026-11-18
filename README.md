# SiniestroAI México | Escalabilidad, FinOps y gobernanza responsable

Se presenta un caso de estudio simulado de una plataforma de IA en la nube para apoyar la gestión de siniestros de seguros de automóviles en México.

## Objetivo y alcance

Evaluar una arquitectura de referencia (**AS-IS**) y proponer su rediseño (**TO-BE**) para mejorar la escalabilidad vertical y horizontal, optimizar la inferencia y controlar costos bajo principios **FinOps**, manteniendo objetivos de nivel de servicio (**SLA**). El proyecto también incorpora una auditoría ética, técnica y legal, evaluación de equidad algorítmica (*fairness*) y un plan de escalamiento responsable.

El caso emplea el nombre ficticio **Protekta Next** y toma como referencia cifras de negocio aportadas por una aseguradora real mexicana. La arquitectura, los costos comparativos, las pruebas de desempeño y las métricas de sesgo son **escenarios académicos simulados.**

## Archivos del repositorio

| Archivo | Descripción |
|---|---|
| [`Actividad9.pdf`](Actividad9.pdf) | **Reporte técnico principal.** Explica el contexto y las fuentes, el diagnóstico AS-IS, el diseño TO-BE, el modelo de demanda, las decisiones de escalabilidad y FinOps, la auditoría de IA responsable y el plan de implementación de 16 semanas. Incluye diagramas de arquitectura, conclusiones y glosario. |
| [`AnexoTecnico.pdf`](AnexoTecnico.pdf) | **Anexo técnico cuantitativo.** Presenta supuestos y fórmulas, escenarios de demanda, métricas de latencia, throughput, uso de CPU/GPU y SLA, comparación de costos AS-IS/TO-BE, matrices de confusión y evaluación de fairness y sesgos. |
| [`DiagramaDeArquitectura.pdf`](DiagramaDeArquitectura.pdf) | **Diagramas de Arquitectura.** Presenta la arquitectura AS-IS y la propuesta TO-BE.|
| [`README.md`](README.md) | Presentación del proyecto y guía breve del contenido del repositorio. |

## Metodología resumida

1. **Dimensionamiento:** se parte de los volúmenes de siniestros de 2024 y 2025 aportados para el estudio y de supuestos explícitos sobre elegibilidad para IA y número de imágenes por expediente.
2. **Rediseño cloud:** se comparan limitaciones de una arquitectura centralizada con una propuesta modular, orientada a eventos, con procesamiento asíncrono y escalamiento automático.
3. **Evaluación FinOps y SLA:** se modelan capacidad, rendimiento y costos, diferenciando metas propuestas de mediciones reales.
4. **Responsible AI:** se analizan riesgos de privacidad, explicabilidad, trazabilidad y equidad, con controles de supervisión humana y criterios de aprobación del despliegue.

## Consideraciones de interpretación

- Las comparaciones de costos son **estimaciones sintéticas** y no cotizaciones definitivas de un proveedor cloud.
- Las métricas de rendimiento y fairness ilustran métodos de evaluación; **no constituyen pruebas ejecutadas ni evidencias de sesgos reales**.
- La propuesta tiene fines exclusivamente académicos.

## Cómo consultar el proyecto

Comenzar por **`Actividad9.pdf`** para comprender el problema, las decisiones y las conclusiones. Consultar después **`AnexoTecnico.pdf`** para revisar los supuestos, tablas y cálculos que respaldan el análisis.
