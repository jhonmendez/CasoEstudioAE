# FinData Credit — Proceso AS-IS

## 1. Propósito
Representar el estado inicial de referencia del proceso de originación de crédito antes de la transformación propuesta.

## 2. Flujo AS-IS

```mermaid
flowchart LR
    A[Cliente solicita crédito] --> B[Captura manual de datos]
    B --> C[Revisión de documentos]
    C --> D[Consulta de fuentes]
    D --> E[Consolidación manual]
    E --> F[Análisis de riesgo]
    F --> G[Decisión]
    G --> H[Desembolso o notificación]
```

## 3. Características
- Captura de información con intervención manual.
- Revisión manual de documentos.
- Consulta de información desde fuentes separadas.
- Consolidación manual de información.
- Evaluación con alta intervención humana.
- Tiempos de respuesta elevados.
- Trazabilidad limitada del flujo completo.

## 4. Problemas identificados
- Actividades repetitivas.
- Información dispersa.
- Riesgo de error humano.
- Dependencia de actividades manuales.
- Baja visibilidad integral del proceso.
- Dificultad para responder en tiempo real.
- Experiencia digital inconsistente.

## 5. Relación con la estrategia
Este estado dificulta cumplir la estrategia de FinData de ofrecer crédito rápido, evaluación automatizada y decisiones en tiempo real.
