# STCA - Sistema de Telemonitorización Cardiológica Ambulatoria (DBT2)

## Descripción del Proyecto
Este repositorio contiene los prototipos HTML/CSS de las interfaces para el Agente "Triage Cardio" y el seguimiento de pacientes con Diabetes Mellitus tipo 2 (DBT2).

El objetivo del sistema es automatizar el triage de emails y garantizar la adherencia al seguimiento pautado, especialmente en poblaciones de bajos ingresos.

## Estructura de Prototipos
- **INTERPF_MEDICO/**: Interfaz del Cardiólogo (Ficha de Ingreso y Seguimiento). Contiene la estructura de datos para la evaluación clínica.
- **INTERPAC_PACIENTE/**: Interfaz del Paciente (Visualización de Objetivos e Indicaciones).
- ## 🔗 Prototipos Publicados (GitHub Pages)

- [Ficha de Ingreso y Seguimiento (INTERPF - MÉDICO)] (./INTERPF_MEDICO/index-pf.html)
- [Plataforma del Paciente (INTERPAC)] (./INTERPAC_PACIENTE/index-pac.html)

## Próximos Pasos (Para el Desarrollador)
1.  **Integración de Backend:** Conectar estas interfaces a un backend seguro (Python/AWS Lambda/Azure) que implemente la lógica de alertas del Agente.
2.  **Lógica Crítica:** Implementar la lógica del Semáforo de Riesgo y el **código de alerta por falta de contacto (DBT2)**.
3.  **Seguridad:** Asegurar el cumplimiento de las normativas de privacidad de datos de salud.
