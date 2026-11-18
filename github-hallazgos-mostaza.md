# Hallazgos GitHub - Herramientas de Mantenimiento Mostaza

**Fuente:** Repositorios de GitHub (CristianMerlo)  
**Fecha de extracción:** 2026-11-18  
**Total de repos relevados:** 21 (20 aplicables a Mostaza, excluyendo nutter_tools)

---

## Métodología

Se consultó la API de GitHub para obtener: nombre, fecha de creación, descripción, estructura de archivos y README de cada repositorio. Los repos se clasificaron por fecha de creación para asignarlos al período laboral correspondiente.

---

## Repositorios por Período

### 2025 Q1-Q2 (Mar 2025 – May 2025) — Jefe de Mantenimiento

| Repo | Fecha creación | Descripción |
|------|---------------|-------------|
| **Generador-de-OTs** | 2025-03-06 | Generador de Órdenes de Trabajo con asistente de base de conocimiento, manuales técnicos y módulo de informes. PWA con HTML/CSS/JS. |

---

### 2025 Q4 (Nov 2025) — Post período, pero relevante para contexto

| Repo | Fecha creación | Descripción |
|------|---------------|-------------|
| **ductos_propios_mostaza** | 2025-11-24 | Gestión y seguimiento de ductos propios de Mostaza. Scripts Python para importación de datos, comparación de locales, generación de links y análisis de frecuencias de proveedor. |

---

### 2026 Q1 (Mar 2026) — Gerente de Mantenimiento de Franquicias

| Repo | Fecha creación | Descripción |
|------|---------------|-------------|
| **dashboard_cafeteras** | 2026-03-24 | Dashboard interactivo para monitoreo de **108 cafeteras** (Cimbali y Melitta) en locales de cadena. Pipeline de datos desde Google Sheets → Python/ETL → JSON → frontend. Monitorea calidad del agua (PPM), equipos, filtros y semáforos automáticos. Exportación a Excel. |

---

### 2026 Q2 (Abr-Jun 2026) — Gerente de Mantenimiento de Franquicias

| Repo | Fecha creación | Descripción |
|------|---------------|-------------|
| **Generador_de_Informes_online** | 2026-04-28 | Generador de informes técnicos online (v13.10.3). PWA con sección de herramientas, JS/CSS modular, service worker y manifest. Permite a los técnicos generar informes estandarizados de mantenimiento. |
| **localizador-de-locales** | 2026-06-10 | Herramienta de localización de locales con base de datos CSV/Excel de locales actualizados y asignados. PWA con assets e imágenes. |

---

### 2026 Q3 (Ago-Sep 2026) — Gerente de Mantenimiento de Franquicias

| Repo | Fecha creación | Descripción |
|------|---------------|-------------|
| **cronograma-de-viajes-por-servicios-tecnicos** | 2026-08-07 | Generador de cronogramas de viajes para servicios técnicos, con base de conocimiento y exportación a HTML/PDF. |
| **M_Auditor** | 2026-09-19 | Módulo de auditoría técnica con contexto y dominio de visitas técnicas, muestras de informes y fuente de datos estructurada. |
| **mostaza-auditoria-tecnica** | 2026-09-20 | PWA de auditoría técnica con datos, documentación, prototipos y herramientas. Módulos JS/CSS, service worker y vendor. |
| **analisis-repuestos** | 2026-09-22 | Cruce mensual de repuestos vendidos a franquicias (NetSuite) contra evidencia de mantenimiento. Clasifica líneas en A (con evidencia) / B (sin evidencia). Pipeline ETL con scripts Python por mes. |
| **modulo-firma-digital** | 2026-09-22 | Automatización de firma digital de PDFs en macOS. Detecta posición de firma con visión computacional (brain_vision), convierte formatos y usa PDFKit nativo (Objective-C). |
| **Modulo-de-Auditoria-de-horas** | 2026-09-23 | Automatización del proceso de auditoría mensual de horas de mantenimiento técnico. Pipeline con scripts, reglas operativas y conciliación automatizada nocturna. |

---

### 2026 Q4 (Oct-Nov 2026) — Gerente de Mantenimiento de Franquicias

| Repo | Fecha creación | Descripción |
|------|---------------|-------------|
| **mtz_tecnico_franquicias_app** | 2026-10-02 | **RondaTracker** — Hub central del técnico de mantenimiento. Login con código personal, tracking de ubicación por antenas (coarse location), pings pasivos cada 30-60 min, perfilado automático de visitas por proximidad a locales y consolidado diario vía Bot de Telegram. Backend Python sin dependencias externas. |
| **modulo_horarios** | 2026-10-02 | Sistema de gestión de horarios mensuales con generación de propuestas, validación de planillas, bolsa de trabajo y aprobación automatizada. Incluye histórico y procesamiento cron. |
| **mtz_tecnico_web** | 2026-10-03 | PWA web central para técnicos de MTZ con app modular, manifest y service worker. Interfaz principal de acceso a herramientas. |
| **Franquicias_Historial_Mto** | 2026-10-16 | Historial de mantenimiento por franquicia con hub central, páginas web, módulo de rondas y sistema de informes. Instrucciones para agentes de IA. |
| **ingestor_correos_mtz** | 2026-10-16 | Espejo del correo corporativo de Mostaza (~5 meses de casillero) como base de consulta para aplicaciones externas. Script Python para sincronización. |
| **modulo-de-mensajeria-tecnicos** | 2026-10-24 | Sala de chat en tiempo real para reemplazar Telegram en conversaciones de mantenimiento. Servidor Python con frontend estático y despliegue automatizado. |
| **informes-para-entrenamiento** | 2026-10-26 | Corpus consolidado de **827 informes técnicos** extraídos de PDFs (mantenimiento, calidad de agua, relevamientos, auditorías, capacitaciones) en formato JSONL para entrenamiento de modelos de IA. |
| **mtz-asistente-tecnico** | 2026-10-31 | Asistente técnico **offline** con **491 fichas de 13 equipos** (base 1.4.0) y **216 locales**. Motor de conocimiento para consultas de mantenimiento incrustable en la PWA de los técnicos. |

---

## Resumen por Categoría

### 📊 Dashboards y Visualización
- **dashboard_cafeteras**: Monitoreo de 108 cafeteras con semáforos de calidad de agua
- **localizador-de-locales**: Base de datos de locales con geolocalización

### 📝 Generación de Documentos
- **Generador-de-OTs**: Órdenes de trabajo con base de conocimiento
- **Generador_de_Informes_online**: Informes técnicos estandarizados (v13.10.3)
- **modulo-firma-digital**: Firma automática de PDFs con visión computacional
- **cronograma-de-viajes-por-servicios-tecnicos**: Planificación de viajes técnicos

### 🔍 Auditoría y Análisis
- **M_Auditor**: Auditoría técnica con dominio de visitas
- **mostaza-auditoria-tecnica**: PWA de auditoría con prototipos
- **Modulo-de-Auditoria-de-horas**: Auditoría mensual de horas automatizada
- **analisis-repuestos**: Cruce ventas NetSuite vs evidencia de mantenimiento

### 💬 Comunicación y Colaboración
- **modulo-de-mensajeria-tecnicos**: Chat en tiempo real (reemplazo de Telegram)
- **ingestor_correos_mtz**: Espejo de correo corporativo para consulta

### 🤖 IA y Conocimiento
- **informes-para-entrenamiento**: 827 informes en JSONL para entrenamiento de IA
- **mtz-asistente-tecnico**: Asistente offline con 491 fichas técnicas
- **Franquicias_Historial_Mto**: Historial con instrucciones para agentes de IA

### 📱 Apps del Técnico (Suite Integrada)
- **mtz_tecnico_web**: PWA central de acceso
- **mtz_tecnico_franquicias_app (RondaTracker)**: Hub con tracking de rondas
- **modulo_horarios**: Gestión de horarios y propuestas
- **ductos_propios_mostaza**: Seguimiento de ductos propios

---

## Métricas Clave

- **20 herramientas** desarrolladas para Mostaza (Mar 2025 – Nov 2026)
- **13 herramientas** en el último trimestre (Oct-Nov 2026)
- **827 informes técnicos** consolidados para IA
- **491 fichas técnicas** de 13 equipos en asistente offline
- **108 cafeteras** monitoreadas en dashboard
- **216 locales** catalogados en base de datos
- **Stack tecnológico:** Python, HTML/CSS/JS vanilla, Go + SQLite, Objective-C, Google Sheets API, Telegram Bot API

---

## Excluidos del análisis Mostaza

- **nutter_tools**: Herramientas orientadas a marca Nutter (equipos), no específicas de Mostaza
- **Informe-de-Seguimiento-y-Minuta-GS**: Generador de minutas de reuniones con GS — proceso puntual, no herramienta de gestión continua
