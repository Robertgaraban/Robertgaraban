# Robert Garaban

**Software Developer · Naval Engineer · AI Systems Architect**  
Barcelona, España · robertgaraban@gmail.com  
[LinkedIn](https://linkedin.com/in/robertgaraban) · [HydroAbyss](https://hydroabyss.com)

Ingeniero naval y desarrollador de software. Construyo sistemas de gestión marítima en producción real, pipelines documentales con IA, y arquitecturas de agentes especializados en el dominio STCW/DPC. Graduado en la **Facultat de Nàutica de Barcelona (UPC)** · Fundador técnico de **HydroAbyss**.

---

## Trayectoria — de 0 a producción

```
2020  Formación intensiva en desarrollo web (HTML, CSS, JS, Node.js, Angular) — Bootcamp Toti, Brasil
      Primeros proyectos: ADTIME, Angola CLI
      Stack inicial: JavaScript · Node.js · Angular · HTML/CSS

2022  Fundación HydroAbyss — Sistema de gestión náutica en producción (España)
      Primer sistema real: PHP · MySQL · jQuery · VPS Linux
      JJR Solutions Brasil — Sistema PHP legacy en producción activa
      Rol: desarrollador full-stack + arquitecto de dominio

2023  Integración de LLMs en flujos de trabajo productivos
      ChatGPT (OpenAI) → primeras automatizaciones documentales
      Generador de Manuales STCW: Python + Pandoc + LaTeX
      Rol: arquitecto de pipelines documentales con IA

2024  Escala de uso de IA: Claude (Anthropic) · Cursor · múltiples modelos en paralelo
      Agentes especializados en producción (AGENT.md + skills)
      Diseño naval asistido por LLM: Fusion 360 API + AutoCAD MCP
      TFG UPC/FNB: catamarán autónomo RF-4 — LLM-driven naval architecture
      Rol: arquitecto de agentes IA + ingeniero naval

2025  Modernización ABYSS STCW: React · Node.js · Express · PostgreSQL (SaaS multi-tenant)
      Claude Code + MCP servers en workflows de desarrollo diario
      Rol: arquitecto de plataforma SaaS + AI-augmented developer

2026  Portafolio técnico consolidado: 8 sistemas en producción o desarrollo activo
      Stack de agentes IA maduro: multi-rol, multi-modelo, con entregables definidos
```

---

## Proyectos en producción

### 🚢 HydroAbyss — Sistema de gestión escuela náutica
Sistema completo de gestión operativa para escuela náutica (España). Matrícula, alumnos, cursos STCW, certificaciones DGMM, pagos e instructores.

**Stack:** PHP · HTML · JavaScript · MySQL · VPS Linux  
**Estado:** Producción activa · [hydroabyss.com](https://hydroabyss.com)  
→ [`hydroabyss-showcase`](https://github.com/Robertgaraban/hydroabyss-showcase) · código fuente disponible bajo solicitud (`hydroabyss`)

---

### 🇧🇷 JJR Solutions — Sistema de gestión marítima (Brasil)
Sistema legacy PHP en producción para escuela de formación marítima. Gestiona alumnos, cursos, certificaciones DPC, pagos e instructores bajo normativa de la Autoridade Marítima brasileña (DPC).

**Stack:** PHP procedural avanzado · MySQL · jQuery EasyUI  
**Estado:** Producción activa en [jjrsolutions.site](https://jjrsolutions.site/system/session/)  
**Proceso:** Modernización hacia ABYSS (Etapas 0–6 completadas)  
→ [`jjr-showcase`](https://github.com/Robertgaraban/jjr-showcase) · código fuente disponible bajo solicitud (`jjrsolutions.site`)

---

### ⚓ ABYSS STCW — Plataforma SaaS de formación marítima
Versión moderna y multi-tenant de HydroAbyss. SaaS con separación de escuelas por país, autenticación por roles, API REST y frontend React.

**Stack:** React · Node.js · Express · PostgreSQL  
**Estado:** Desarrollo activo  
→ [`abyss-stcw-brief`](https://github.com/Robertgaraban/abyss-stcw-brief) · código fuente disponible bajo solicitud (`abyss-stcw-private`)

---

### 📄 Generador de Manuales HydroAbyss
Pipeline documental que genera los 21 manuales STCW en PDF y DOCX con calidad institucional, versionado automático y trazabilidad normativa. Extracción desde PDF/DOCX originales con OCR fallback, normalización y compilación Pandoc + LaTeX.

**Stack:** Python 3 · Pandoc · Tectonic (LaTeX) · Bash · OCR  
**Cobertura:** 19/21 cursos STCW · revalidación: junio 2026  
→ [`manual-generator-showcase`](https://github.com/Robertgaraban/manual-generator-showcase) · código fuente disponible bajo solicitud (`manual-generator-private`)

---

### 💼 Sistema de Nóminas
Sistema de gestión de nóminas con cálculo de devengos, deducciones, generación de recibos y reporting.

**Stack:** JavaScript · Node.js · MySQL  
**Estado:** Producción  
→ [`nominas-showcase`](https://github.com/Robertgaraban/nominas-showcase) · código fuente disponible bajo solicitud (`nominas-private`)

---

### 🤖 Agentes IA — HydroAbyss & ABYSS STCW
Agentes de IA especializados en producción: generación de manuales STCW, auditoría documental, paridad normativa y tareas de desarrollo. Arquitectura propia con `AGENT.md` por sistema y skills reutilizables.

**Modelos en uso:** Claude (Anthropic) · OpenAI GPT · multi-modelo por tarea  
**Herramientas:** Claude Code · Cursor · MCP servers propios  
**Estado:** Producción activa en HydroAbyss y ABYSS STCW  
→ [`agents-showcase`](https://github.com/Robertgaraban/agents-showcase) · definiciones disponibles bajo solicitud (`agents-private`)

---

### ⚙️ LLM + Diseño Naval — HydroAbyss RF-4
Integración de LLMs con Fusion 360 (Python API) y AutoCAD (via MCP) para generar planos navales desde especificaciones estructuradas. Proyecto ejecutado: catamarán autónomo RF-4 (4.80 m, GFRP, propulsión eléctrica, LiDAR + GNSS + AIS + ArduPilot). TFG — Facultat de Nàutica de Barcelona (UPC).

**Stack:** Python · Fusion 360 API · AutoCAD MCP · AutoLISP · Claude / OpenAI · ArduPilot  
→ [`naval-design-llm-showcase`](https://github.com/Robertgaraban/naval-design-llm-showcase) · materiales disponibles bajo solicitud (`naval-design-private`)

---

### 📐 Skill: Maquetación TFG FNB/UPC
Skill de IA para formatear TFG/TFM según normativa oficial FNB/UPC. Aplica estilos Word, estructura, tipografía, paginación, ISO 690 — sin reescribir contenido. Con pipeline de scripts de auditoría.

**Stack:** Python · python-docx · Markdown · Scripts de auditoría  
→ [`tfg-skill-showcase`](https://github.com/Robertgaraban/tfg-skill-showcase) · disponible bajo solicitud (`tfg-skill-private`)

---

### 🧮 Cálculo de Estructuras Navales
Notebooks de ingeniería naval: cálculo estructural, estabilidad y resistencia.

**Stack:** Python · Jupyter Notebooks  
→ [`Calculo-de-Estructuras-Navales-FNB`](https://github.com/Robertgaraban/Calculo-de-Estructuras-Navales-FNB)

---

## Stack técnico completo

### Backend
```
PHP (procedural avanzado — legacy en producción)
Node.js · Express (REST APIs, middleware)
Python 3 (pipelines, scripts, automaciones, CAD integration)
MySQL · PostgreSQL (modelado relacional, migraciones, auditoría)
```

### Frontend
```
React (SaaS multi-tenant, componentes funcionales, hooks)
HTML · CSS · JavaScript (vanilla y jQuery)
jQuery EasyUI (sistemas legacy en producción)
```

### DevOps & Infraestructura
```
VPS Linux (Ubuntu) — administración, particionado de entornos, nginx
Git · GitHub (control de versiones, branching, private/public split)
Bash (scripts de build, automatización, pipelines CI manuales)
Flujo oficial: local → build → homologación → corte → rollback
Backups, migraciones controladas, rollback documentado
```

### Diseño CAD / Ingeniería Naval
```
Autodesk Fusion 360 (Python API — modelado paramétrico 3D)
AutoCAD LT + AutoLISP + MCP server (planos 2D, DXF)
ezdxf (generación headless de planos DXF)
ArduPilot / Mission Planner (navegación autónoma USV)
```

### Documentación & Compilación
```
Pandoc + Tectonic (LaTeX) — generación PDF/DOCX institucional
Markdown estructurado como fuente única de verdad documental
OCR (fallback para extracción de contenido legacy)
```

### Inteligencia Artificial & Agentes
```
Claude (Anthropic) — claude-3, claude-opus-4, claude-sonnet-4
  · Claude Code — CLI agentic coding, workflows de desarrollo diario
  · MCP servers propios: autocad-mcp, Fusion 360, tools personalizados
  · Agentes con AGENT.md por sistema + SKILL.md por tarea

ChatGPT / OpenAI API — GPT-4, integración en pipelines documentales

Cursor — IDE asistido por IA, desarrollo de sistemas en producción

Gemini (Google) — evaluación comparativa y tareas específicas

Arquitectura de agentes propia:
  · AGENT.md — contexto, reglas y personalidad del agente por sistema
  · SKILL.md — entregables definidos, criterio de cierre por tarea
  · Multi-modelo: Claude + OpenAI según la tarea
  · Agentes en producción real (no prototipos de laboratorio)
```

### Dominio marítimo
```
STCW (Standards of Training, Certification and Watchkeeping)
DGMM / MITMA (España) — normativa de certificaciones y reportes
DPC — Diretoria de Portos e Costas (Brasil) — reportes regulatorios
COLREGs — navegación autónoma, evasión de colisiones
CPF · CNPJ · Identidade (documentación brasileña)
DNI · CIF (documentación española)
```

---

## Roles desempeñados

**Arquitecto de software** — Diseño de sistemas desde legacy PHP hasta SaaS multi-tenant moderno. Decisiones de migración, separación de dominios, estrategia pública/privada de repositorios.

**Desarrollador full-stack** — Backend PHP y Node.js, frontend React y jQuery, bases de datos MySQL y PostgreSQL. Sistemas en producción real con histórico de años.

**Arquitecto de agentes IA** — Diseño de flujos con LLMs en producción: AGENT.md como contexto de agente, SKILL.md como definición de tarea, multi-modelo, multi-rol, con entregables definidos y criterio de cierre.

**DevOps** — Administración VPS, nginx, particionado de entornos (España/Brasil en mismo servidor), pipelines de build y rollback, backups y migraciones controladas.

**Ingeniero naval** — Diseño naval asistido por LLM, integración LLM↔CAD, especificación técnica de USV autónomo (RF-4), navegación autónoma (ArduPilot, COLREGs), TFG UPC/FNB.

---

## Repos públicos y acceso a código fuente

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

**Contacto para acceso:** robertgaraban@gmail.com — Asunto: `[Acceso repo privado] <nombre-repo>`

---

*Formación marítima · Tecnología · Gestión operativa · IA en producción*
