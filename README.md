# Robert Garaban

**Software Developer · Naval Engineer · Maritime Domain Specialist**  
Barcelona, España

Ingeniero naval y desarrollador de software. Construyo sistemas de gestión marítima, pipelines documentales con IA, herramientas de diseño naval asistido por LLM y agentes de IA especializados en el dominio STCW/DPC.

Graduado en la **Facultat de Nàutica de Barcelona (UPC)** · Fundador técnico de **[HydroAbyss](https://hydroabyss.com)**

---

## Proyectos

### 🚢 HydroAbyss — Sistema de gestión escuela náutica
Sistema completo de gestión operativa para escuela náutica (España). Matrícula, alumnos, cursos STCW, certificaciones, pagos e instructores.

**Stack:** PHP · HTML · JavaScript · MySQL  
**Estado:** Producción activa · [hydroabyss.com](https://hydroabyss.com)  
→ [`hydroabyss-showcase`](https://github.com/Robertgaraban/hydroabyss-showcase) · código fuente disponible bajo solicitud

---

### ⚓ ABYSS STCW — Plataforma SaaS de formación marítima
Versión moderna y multi-tenant de HydroAbyss. Arquitectura SaaS, separación de escuelas, autenticación por roles, API REST y frontend React.

**Stack:** React · Node.js · Express · PostgreSQL  
→ [`abyss-stcw-brief`](https://github.com/Robertgaraban/abyss-stcw-brief) · código fuente disponible bajo solicitud

---

### 🇧🇷 JJR Solutions — Sistema de gestión marítima (Brasil)
Sistema operativo en producción para escuela de formación marítima en Brasil. Gestión de alumnos, cursos, certificaciones DPC, pagos e instructores bajo el marco regulatorio de la Autoridade Marítima brasileña (DPC).

**Stack:** PHP procedural avanzado · MySQL · jQuery EasyUI  
**Estado:** Producción activa · [jjrsolutions.site](https://jjrsolutions.site/system/session/)  
**Proceso:** Modernización hacia ABYSS (Etapas 0–6 completadas)  
→ [`jjr-showcase`](https://github.com/Robertgaraban/jjr-showcase) · código fuente disponible bajo solicitud

---

### 📄 Generador de Manuales HydroAbyss
Pipeline documental que genera los 21 manuales STCW en PDF y DOCX con versionado automático y trazabilidad normativa. Extracción desde PDF/DOCX originales con OCR fallback, normalización y compilación Pandoc + LaTeX.

**Stack:** Python 3 · Pandoc · Tectonic (LaTeX) · Bash  
**Cobertura:** 19/21 cursos STCW · revalidación junio 2026  
→ [`manual-generator-showcase`](https://github.com/Robertgaraban/manual-generator-showcase) · código fuente disponible bajo solicitud

---

### 💼 Sistema de Nóminas
Sistema de gestión de nóminas con cálculo de devengos, deducciones, generación de recibos y reporting.

**Stack:** JavaScript · Node.js · MySQL  
→ [`nominas-showcase`](https://github.com/Robertgaraban/nominas-showcase) · código fuente disponible bajo solicitud

---

### 🤖 Agentes IA — HydroAbyss & ABYSS STCW
Agentes de IA especializados con reglas de dominio marítimo, integrados en producción en HydroAbyss y ABYSS STCW. Generación de manuales STCW, auditoría de calidad documental, control de paridad normativa DPC.

**Enfoque:** Agentes multi-rol adaptados al marco STCW / DGMM / DPC  
**Estado:** Producción activa  
→ [`agents-showcase`](https://github.com/Robertgaraban/agents-showcase) · definiciones disponibles bajo solicitud

---

### ⚙️ LLM + Diseño Naval — HydroAbyss RF-4
Integración de LLMs con Fusion 360 y AutoCAD (MCP) para generar planos navales desde especificaciones estructuradas. Proyecto ejecutado: catamarán autónomo HydroAbyss RF-4 (4.80 m, doble casco GFRP, propulsión eléctrica, LiDAR + GNSS + AIS). TFG presentado en la Facultat de Nàutica de Barcelona (UPC).

**Stack:** Python · Fusion 360 API · AutoCAD MCP · AutoLISP · Claude / OpenAI · ArduPilot  
→ [`naval-design-llm-showcase`](https://github.com/Robertgaraban/naval-design-llm-showcase) · materiales técnicos bajo solicitud

---

### 📐 Skill: Maquetación TFG FNB/UPC
Skill de IA para formatear TFG/TFM según la normativa oficial de FNB/UPC. Estilos Word, estructura obligatoria, citación ISO 690, pipeline de auditoría. Parte del ecosistema de agentes HydroAbyss.

→ [`tfg-skill-showcase`](https://github.com/Robertgaraban/tfg-skill-showcase)

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

La mayor parte del código está en repositorios **privados** por confidencialidad operativa (sistemas en producción real). Cada proyecto público es un brief técnico con arquitectura, stack, estado y política de acceso.

**Para revisión técnica:** robertgaraban@gmail.com  
**LinkedIn:** [linkedin.com/in/robertgaraban](https://linkedin.com/in/robertgaraban)

---

*Formación marítima · Tecnología · Gestión operativa · Diseño naval*