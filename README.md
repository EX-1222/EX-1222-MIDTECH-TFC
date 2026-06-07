# EX-1222 — MIDTECH S.A. Asistente de ciberseguridad y compliance

Proyecto final de curso basado en n8n, Google Drive, RAG y un modelo LLM para construir un asistente de ciberseguridad y compliance aplicado al caso ficticio MIDTECH S.A.

## Objetivo

El objetivo del proyecto es construir un asistente capaz de consultar documentación preparada, recuperar contexto relevante y responder preguntas relacionadas con seguridad de la información, cumplimiento normativo y mejora continua.

## Capacidades del asistente

El asistente cubre cuatro capacidades principales:

1. Análisis de política de seguridad.
2. Gap analysis normativo frente a ISO 27001 y ENS.
3. Respuesta a preguntas de auditoría documental.
4. Propuestas de mejora priorizadas.

## Tecnologías utilizadas

- n8n para la automatización del workflow.
- Google Drive como repositorio documental.
- Simple Vector Store para recuperación documental.
- Embeddings para indexación de documentos.
- Modelo LLM para generación de respuestas.
- Prompts especializados por capacidad.

## Estructura del repositorio

```text
EX-1222-MIDTECH-TFC/
  workflow/
    workflow_midtech_final_PUBLICO_limpio_v2.json

  prompts/
    Prompts finales utilizados en el asistente.

  capturas/
    Evidencias principales del funcionamiento.

  docs/
    Documentación complementaria del proyecto.
