# spanish-research-grants

Skill de Claude Code para preparar propuestas de investigación dirigidas a las principales convocatorias públicas de financiación en España.

Desarrollado por Pablo Zulet Fraile (cardiólogo, Hospital Clínico San Carlos, Madrid).

## Qué hace

Proporciona una guía completa y práctica para abordar solicitudes de financiación del sistema español de I+D+i, cubriendo las dos agencias principales:

### ISCIII (Instituto de Salud Carlos III)
- **Proyectos PI** — Proyectos de Investigación en Salud (programa estrella del ISCIII)
- **Proyectos DTS** — Desarrollo Tecnológico en Salud
- **Infraestructuras ICI** — Equipamiento científico de uso compartido
- **Recursos humanos:**
  - PFIS / i-PFIS (predoctorales)
  - Río Hortega (post-MIR)
  - Sara Borrell (postdoctoral)
  - Miguel Servet I y II (estabilización)
  - Juan Rodés (clínico-investigador)
  - Intensificación (complemento asistencial)
- **Redes y centros:** RICORS, CIBER, plataformas (SCReN, PNBB, PRB)

### AEI (Agencia Estatal de Investigación)
- **Proyectos PGC** — Proyectos de Generación de Conocimiento (Tipo A, B, I)
- **Ramón y Cajal** — Tenure-track de excelencia
- **Juan de la Cierva** — Formación e Incorporación postdoctoral
- **FPI** — Contratos predoctorales vinculados a proyectos PGC
- **Consolidación investigadora** — Post-Ramón y Cajal
- **Prueba de Concepto** — Transferencia de resultados

## Qué incluye la guía

- Criterios de evaluación detallados (ISCIII: Equipo 30 + Calidad 15 + Viabilidad 15; AEI: evaluación ANEP por pares)
- Estrategia de redacción de la memoria científico-técnica
- Preparación del CVA (Currículum Vitae Abreviado)
- Elaboración de presupuestos y cronogramas
- Errores frecuentes y cómo evitarlos
- Calendario orientativo de convocatorias
- Plantillas para secciones comunes (difusión, aspectos éticos, compromiso del centro)

## Cómo usar

```
/spanish-research-grants
```

Indica la convocatoria a la que quieres presentarte y Claude te guiará en la preparación de la solicitud.

Ejemplos:
- "Necesito preparar un proyecto PI para el ISCIII"
- "Quiero redactar la memoria científico-técnica para un PGC tipo B"
- "Ayúdame con el CVA para la convocatoria de Sara Borrell"
- "Revisa mi presupuesto para un proyecto PI coordinado"

## Archivos

```
skills/spanish-research-grants/
├── SKILL.md                              — Guía principal (1100+ líneas)
├── references/
│   ├── isciii_guidelines.md             — Normativa y requisitos ISCIII
│   ├── isciii_pi_projects.md            — Detalle de proyectos PI
│   ├── isciii_human_resources.md        — Contratos de personal ISCIII
│   ├── isciii_networks.md               — RICORS, CIBER, plataformas
│   ├── aei_guidelines.md               — Normativa y requisitos AEI
│   ├── aei_pgc_projects.md             — Detalle de proyectos PGC
│   ├── aei_human_resources.md           — RyC, JdC, FPI, consolidación
│   ├── evaluation_criteria.md           — Criterios de puntuación
│   ├── cva_guide.md                     — Guía para el CVA
│   └── README.md                        — Índice de referencias
└── assets/
    ├── memoria_cientificotecnica_template.md  — Plantilla de memoria
    ├── resumen_ejecutivo_template.md          — Plantilla de resumen
    ├── presupuesto_template.md                — Plantilla de presupuesto
    ├── cva_isciii_template.md                 — Plantilla CVA ISCIII
    ├── pi_project_template.md                 — Plantilla proyecto PI
    └── pgc_project_template.md                — Plantilla proyecto PGC
```

## Disclaimer

Esta guía proporciona orientación general basada en convocatorias recientes. **No sustituye la lectura de la convocatoria oficial vigente.** Los criterios, plazos e importes pueden cambiar cada año.

Fuentes oficiales:
- [BOE](https://www.boe.es) — Publicación oficial
- [ISCIII](https://www.isciii.es) — Convocatorias sanitarias
- [AEI](https://www.aei.gob.es) — Convocatorias generales

---

© 2026 Pablo Zulet Fraile. Uso libre con atribución.
