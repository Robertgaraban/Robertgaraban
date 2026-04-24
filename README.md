# Robert Garaban

**Software Developer · Naval Engineer · Maritime Domain Specialist**  
Barcelona, España

Ingeniero naval y desarrollador de software. Construyo sistemas de gestión marítima, pipelines documentales con IA, herramientas de diseño naval asistido por LLM y agentes de IA especializados en el dominio STCW/DPC.

Graduado en la **Facultat de Nàutica de Barcelona (UPC)** · Fundador técnico de **[HydroAbyss](https://hydroabyss.com)**

---

## Proyectos

### 🚢 HydroAbyss — Sistema de gestión escuela náutica
Sistema completo de gestión operativa para escuela náutica (España). Cubre matrícula, alumnos, cursos STCW, certificaciones, pagos e instructores.

**Stack:** PHP · HTML · JavaScript · MySQL  
**Estado:** Producción activa · live site en [hydroabyss.com](https://hydroabyss.com)  
→ [`hydroabyss-showcase`](https://github.com/Robertgaraban/hydroabyss-showcase) · código fuente disponible bajo solicitud

---

### ⚓ ABYSS STCW — Plataforma SaaS de formación marítima
Versión moderna y multi-tenant de HydroAbyss. Arquitectura SaaS con separación de escuelas, autenticación por roles, API REST y frontend React.

**Stack:** React · Node.js · Express · PostgreSQL  
**Estado:** Desarrollo activo  
→ [`abyss-stcw-brief`](https://github.com/Robertgaraban/abyss-stcw-brief) · código fuente disponible bajo solicitud

---

### 🇧🇷 JJR Solutions — Sistema de gestión marítima (Brasil)
Sistema operativo en producción para escuela de formación marítima en Brasil. Gestiona alumnos, cursos, certificaciones DPC, pagos e instructores bajo el marco regulatorio de la Autoridade Marítima brasileña.

**Stack:** PHP procedural avanzado · MySQL · jQuery EasyUI  
**Estado:** Producción activa en [jjrsolutions.site](https://jjrsolutions.site/system/session/)  
**Proceso:** Modernización en curso hacia plataforma ABYSS (Etapas 0–6 completadas)  
→ [`jjr-showcase`](https://github.com/Robertgaraban/jjr-showcase) · código fuente disponible bajo solicitud

---

### 📄 Generador de Manuales HydroAbyss
Pipeline documental que genera los 21 manuales STCW de la escuela en PDF y DOCX con calidad institucional, versionado automático y trazabilidad normativa. Extracción desde PDF/DOCX originales (con OCR fallback), normalización de contenido y compilación mediante Pandoc + LaTeX.

**Stack:** Python 3 · Pandoc · Tectonic (LaTeX) · Bash  
**Cobertura:** 19/21 cursos STCW completos · próximo ciclo de revalidación: junio 2026  
→ [`manual-generator-showcase`](https://github.com/Robertgaraban/manual-generator-showcase) · código fuente disponible bajo solicitud

---

### 💼 Sistema de Nóminas
Sistema de gestión de nóminas con cálculo de devengos, deducciones, generación de recibos y reporting.

**Stack:** JavaScript · Node.js · MySQL  
**Estado:** Producción  
→ [`nominas-showcase`](https://github.com/Robertgaraban/nominas-showcase) · código fuente disponible bajo solicitud

---

### 🤖 Agentes IA — HydroAbyss & ABYSS STCW
Agentes de IA especializados con flujos de trabajo y reglas de dominio marítimo definidas, adaptados e integrados en los sistemas HydroAbyss y ABYSS STCW. Operan en producción para generación de manuales STCW, auditoría de calidad documental, control de paridad normativa y tareas de desarrollo. Cada sistema tiene su propio contexto de agente (`AGENT.md`) y skills reutilizables.

**Enfoque:** Agentes multi-rol con personalidad y entregables definidos, adaptados al marco regulatorio STCW / DGMM / DPC  
**Integración:** Embebidos en el pipeline del Generador de Manuales y en los workflows de ABYSS STCW  
**Estado:** Producción activa en ambos sistemas  
→ [`agents-showcase`](https://github.com/Robertgaraban/agents-showcase) · definiciones completas disponibles bajo solicitud

---

### ⚙️ LLM + Diseño Naval — HydroAbyss RF-4
Integración de LLMs con Fusion 360 y AutoCAD (via MCP) para generar planos técnicos navales desde especificaciones estructuradas. Proyecto ejecutado: catamarán autónomo HydroAbyss RF-4 (4.80 m, doble casco GFRP, propulsión eléctrica, sensores LiDAR + GNSS + AIS), diseñado como unidad de validación de algoritmos de navegación autónoma costera. TFG presentado en la Facultat de Nàutica de Barcelona (UPC).

**Stack:** Python · Fusion 360 API · AutoCAD MCP · AutoLISP · Claude / OpenAI · ArduPilot  
**Proyecto ejecutado:** Catamarán HydroAbyss RF-4 — especificación completa + modelo CAD + planos técnicos  
→ [`naval-design-llm-showcase`](https://github.com/Robertgaraban/naval-design-llm-showcase) · materiales técnicos disponibles bajo solicitud

---

### 📐 Skill: Maquetación TFG FNB/UPC
Skill de IA para formatear TFG/TFM según la normativa oficial de la Facultat de Nàutica de Barcelona (FNB/UPC). Aplica estilos Word, estructura obligatoria, tipografía, paginación, citación ISO 690 y figuras/tablas — sin reescribir el contenido del autor. Incluye pipeline de scripts de auditoría y limpieza. Parte del ecosistema de agentes HydroAbyss.

**Stack:** Python · Markdown · Word (python-docx) · Scripts de auditoría  
→ [`tfg-skill-showcase`](https://github.com/Robertgaraban/tfg-skill-showcase) · skill disponible bajo solicitud

---

### 🧮 Cálculo de Estructuras Navales
Notebooks de ingeniería naval: cálculo estructural, estabilidad y resistencia aplicados a embarcaciones.

**Stack:** Python · Jupyter Notebooks  
→ [`Calculo-de-Estructuras-Navales-FNB`](https://github.com/Robertgaraban/Calculo-de-Estructuras-Navales-FNB)

---

## Stack general

```
Backend     PHP · Node.js · Express · Python
Frontend    React · HTML · JavaScript · jQuery
Bases datos MySQL · PostgreSQL
Docs        Pandoc · LaTeX (Tectonic) · Markdown
CAD / Naval Fusion 360 API · AutoCAD MCP · AutoLISP · ezdxf · ArduPilot
Agentes IA  Agentes multi-rol · Skills reutilizables · AGENT.md por sistema
LLM         Claude (Anthropic) · OpenAI · MCP servers
DevOps      Linux VPS · Bash · Git
Dominio     STCW · DGMM · DPC · COLREGs · Naval architecture · Formación marítima
```

---

## Sobre el repositorio

Cada proyecto tiene dos capas: un **brief técnico público** (este repositorio y los showcases) y un **repositorio privado** con el código fuente completo, accesible como colaborador bajo solicitud.

| Showcase público | Repositorio privado |
|---|---|
| [hydroabyss-showcase](https://github.com/Robertgaraban/hydroabyss-showcase) | `hydroabyss` |
| [abyss-stcw-brief](https://github.com/Robertgaraban/abyss-stcw-brief) | `abyss-stcw-private` |
| [jjr-showcase](https://github.com/Robertgaraban/jjr-showcase) | `jjrsolutions.site` |
| [manual-generator-showcase](https://github.com/Robertgaraban/manual-generator-showcase) | `manual-generator-private` |
| [nominas-showcase](https://github.com/Robertgaraban/nominas-showcase) | `nominas-private` |
| [agents-showcase](https://github.com/Robertgaraban/agents-showcase) | `agents-private` |
| [naval-design-llm-showcase](https://github.com/Robertgaraban/naval-design-llm-showcase) | `naval-design-private` |
| [tfg-skill-showcase](https://github.com/Robertgaraban/tfg-skill-showcase) | `tfg-skill-private` |

**Para acceso a código fuente:** robertgaraban@gmail.com — Asunto: `[Acceso repo privado] <nombre-repo>`  
**LinkedIn:** [linkedin.com/in/robertgaraban](https://linkedin.com/in/robertgaraban)

---

*Formación marítima · Tecnología · Gestión operativa*
