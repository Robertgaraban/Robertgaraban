<div align="center">

# Robert Garaban

**Software Architect · DevOps · Naval Engineer · Maritime Domain Specialist**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-robertgaraban-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/robertgaraban)
[![Email](https://img.shields.io/badge/Email-robertgaraban%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:robertgaraban@gmail.com)
[![HydroAbyss](https://img.shields.io/badge/HydroAbyss-hydroabyss.com-0077B6?style=for-the-badge&logo=anchor&logoColor=white)](https://hydroabyss.com)
![Location](https://img.shields.io/badge/📍_Barcelona-España-E31010?style=for-the-badge)

</div>

Ingeniero naval y arquitecto de software. Diseño y despliego sistemas SaaS de gestión marítima en producción, pipelines documentales con IA, herramientas de diseño naval asistido por LLM y agentes de IA especializados en el dominio STCW/DPC. Cada sistema va de la arquitectura al servidor.

Graduado en la **Facultat de Nàutica de Barcelona (UPC)** · Fundador técnico de **[HydroAbyss](https://hydroabyss.com)**

---

## 🛠️ Stack Tecnológico

<div align="center">

### Backend & API
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![RBAC](https://img.shields.io/badge/RBAC-Auth_Layer-6A0DAD?style=for-the-badge)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=for-the-badge&logo=socketdotio&logoColor=white)

### Frontend
![React](https://img.shields.io/badge/React_18-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Radix UI](https://img.shields.io/badge/Radix_UI-161618?style=for-the-badge&logo=radixui&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white)

### Bases de Datos
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

### DevOps & Infraestructura
![Linux](https://img.shields.io/badge/Linux_VPS-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![PM2](https://img.shields.io/badge/PM2-2B037A?style=for-the-badge&logo=pm2&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

### Pipeline Documental
![Pandoc](https://img.shields.io/badge/Pandoc-000000?style=for-the-badge&logo=pandoc&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX_(Tectonic)-008080?style=for-the-badge&logo=latex&logoColor=white)
![pdfplumber](https://img.shields.io/badge/pdfplumber+pymupdf-3776AB?style=for-the-badge&logo=python&logoColor=white)
![python-docx](https://img.shields.io/badge/python--docx-2B579A?style=for-the-badge&logo=microsoftword&logoColor=white)
![Markdown](https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)

### IA & LLM
![Claude](https://img.shields.io/badge/Claude_(Anthropic)-D97706?style=for-the-badge&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![MCP](https://img.shields.io/badge/MCP_(Model_Context_Protocol)-FF6B35?style=for-the-badge)

### CAD & Ingeniería Naval
![Fusion 360](https://img.shields.io/badge/Fusion_360_(Python_API)-FF6C00?style=for-the-badge&logo=autodesk&logoColor=white)
![AutoCAD](https://img.shields.io/badge/AutoCAD_LT+AutoLISP-E51937?style=for-the-badge&logo=autodesk&logoColor=white)
![ezdxf](https://img.shields.io/badge/ezdxf_(headless_DXF)-3776AB?style=for-the-badge&logo=python&logoColor=white)
![ArduPilot](https://img.shields.io/badge/ArduPilot-02569B?style=for-the-badge)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

</div>

---

## 🏗️ Arquitectura & DevOps

### ABYSS — Plataforma SaaS full-stack en producción

Stack React 18 + Vite · Node.js + Express · PostgreSQL · Socket.IO · Nginx · PM2 · VPS

```mermaid
flowchart TD
    A["Usuarios"] --> B["Navegador"]
    B --> C["React 18 + Vite SPA\nJavaScript / JSX"]
    C --> D["UI Layer\nTailwind CSS + Radix UI + Framer Motion"]
    C --> E["Client Services\nfetch + sendBeacon + /api"]
    E -->|HTTPS + JSON + JWT / cookies| F["Node.js + Express API\nJavaScript"]
    F --> G["Middleware Auth + RBAC\nJWT + requirePermission"]
    G --> H["Business Services\nalumnos · cursos · facturación · certs · SGC"]
    H -->|SQL via pg| I["PostgreSQL"]
    H --> J["Node.js Workers\ncomunicaciones · recordatorios · jobs programados"]
    I -->|LISTEN / NOTIFY| K["Socket.IO /ws\nReal-time Layer"]
    K -->|WebSocket + JWT| C
    F --> L["Nginx + PM2 + VPS\nReverse Proxy · Supervisión · Deploy"]
```

---

### Infraestructura VPS — Topología de despliegue

```mermaid
flowchart TD
    Internet["Internet"] --> Nginx["Nginx\nReverse Proxy / TLS"]
    Nginx -->|"/"| SPA["React SPA\nAssets estáticos"]
    Nginx -->|"/api"| API["Node.js + Express\nAPI REST · PM2"]
    Nginx -->|"/ws"| WS["Socket.IO\nReal-time · PM2"]
    API --> Workers["Node.js Workers\nPM2 · cron · cola de jobs"]
    API --> DB["PostgreSQL\nBase de datos operativa"]
    Workers --> DB
    DB -->|LISTEN/NOTIFY| WS
    API --> Smoke["Deploy Scripts\nSmoke checks · Rollback"]
```

---

### Plataforma Multi-Tenant — ABYSS (expansión geográfica)

```mermaid
flowchart TD
    ABYSS["ABYSS Core\nPlataforma SaaS"]
    ABYSS --> T1["STCW España\nTenant · DGMM/MITMA"]
    ABYSS --> T2["JJR Solutions Brasil\nTenant · DPC/Autoridade Marítima"]
    T1 --> CONF1["Tenant Pack ES\nconfig · roles · certificados DGMM"]
    T2 --> CONF2["Tenant Pack BR\nconfig · CPF/CNPJ · reportes DPC"]
    ABYSS --> LIFECYCLE["Lifecycle unificado\nLead → Alumno → Cert → Factura"]
    ABYSS --> SGC["SGC Analytics\nKPI snapshots · tendencias · auditoría ISO"]
```

---

### Pipeline Documental — Generador de Manuales STCW

```mermaid
flowchart TD
    SRC["Fuentes PDF/DOCX\noriginales STCW"]
    SRC --> EXT["extract_content.py\nOCR fallback: pdfplumber + pymupdf"]
    EXT --> RAW["raw/extracted_*.md\n(solo consulta)"]
    RAW --> MANUAL["manual.md\nÚNICA fuente editable"]
    MANUAL --> COMPILE["compilar.sh\nPandoc ≥ 3.0 + Tectonic (LaTeX)"]
    COMPILE --> PDF["output/activo/\nPDF institucional (versión estable)"]
    COMPILE --> DOCX["output/activo/\nDOCX institucional (versión estable)"]
    COMPILE --> HIST["output/versiones/vN/\nHistórico + metadata.json (trazabilidad)"]
    PIPELINE["pipeline_curso.py\nComando único: ingesta → compilación → QA"]
    PIPELINE --> EXT
    PIPELINE --> COMPILE
```

---

### Integración Agentes IA — Arquitectura de dominio

```mermaid
flowchart TD
    SISTEMA["Sistema\nHydroAbyss / ABYSS STCW"]
    SISTEMA --> AGENT_DIR[".agent/\nContexto del sistema"]
    AGENT_DIR --> AGENT_MD["AGENT.md\nReglas · dominio · restricciones"]
    AGENT_DIR --> SKILLS["skills/\nFlujos reutilizables por tarea"]
    SKILLS --> SKILL1["generar_manual/SKILL.md\ningesta → compilación → QA"]
    SKILLS --> SKILL2["[otras skills]/\nauditoría · paridad DPC · control calidad"]
    SISTEMA --> SCRIPTS["scripts/\nPipeline determinista Python/Bash"]
    SISTEMA --> PROMPTS["docs/PROMPT_MAESTRO_*.md\nPrompts estándar por tarea recurrente"]
    AGENT_MD --> RULE1["Paridad normativa DPC\nregla no negociable"]
    AGENT_MD --> RULE2["Preservar histórico\nsin modificar datos operativos"]
    AGENT_MD --> RULE3["Dominio DGMM vs DPC\ndiferenciación España/Brasil"]
```

---

### LLM + CAD — Diseño Naval RF-4

```mermaid
flowchart TD
    SPEC["Especificación técnica estructurada\nMarkdown · parámetros RF-4"]
    SPEC --> LLM["LLM\nClaude / OpenAI GPT"]
    LLM -->|"Python API"| F360["Fusion 360\nModelo 3D paramétrico\ndoble casco GFRP"]
    LLM -->|"stdio JSON-RPC"| MCP["Python MCP Server"]
    MCP -->|"File IPC"| ACAD["AutoCAD LT\nmcp_dispatch.lsp (AutoLISP)"]
    MCP -->|"headless"| EZDXF["ezdxf\nDXF sin AutoCAD"]
    F360 --> OUT3D["Modelo 3D\nExportación vistas técnicas"]
    ACAD --> OUT2D["Planos 2D\nDXF + PDF"]
    EZDXF --> OUT2D
    OUT3D --> REVIEW["Revisión iterativa\nLLM + Ingeniero"]
    OUT2D --> REVIEW
    REVIEW --> FINAL["Output final\nPDF + DXF + Modelo 3D · TFG FNB/UPC"]
```

---

## 🚀 Proyectos Destacados

### 🚢 HydroAbyss — Plataforma marítima & escuela náutica

> Plataforma de negocio en producción: web de autoridad, captación de leads y sistema interno de gestión para escuela náutica (España). Arquitectura estática-first, backend PHP selectivo, contenido técnico multilingüe STCW.

![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Status](https://img.shields.io/badge/Estado-Producción_activa-brightgreen?style=flat-square)

🌐 Live: [hydroabyss.com](https://hydroabyss.com) · 📂 [`hydroabyss-showcase`](https://github.com/Robertgaraban/hydroabyss-showcase)

---

### ⚓ ABYSS STCW — Plataforma SaaS de formación marítima

> SaaS operativo con 5+ años de iteración en producción. 18 módulos: alumnos, cursos, certificaciones, facturación, portal alumno, comunicaciones, SGC/ISO. Arquitectura multi-tenant con tenant packs por país. Real-time via Socket.IO + PostgreSQL LISTEN/NOTIFY. Despliegue VPS con Nginx + PM2.

![React](https://img.shields.io/badge/React_18-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white)
![JWT](https://img.shields.io/badge/JWT+RBAC-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx+PM2-009639?style=flat-square&logo=nginx&logoColor=white)
![Status](https://img.shields.io/badge/Estado-Producción_activa-brightgreen?style=flat-square)

📂 [`abyss-stcw-brief`](https://github.com/Robertgaraban/abyss-stcw-brief)

---

### 🇧🇷 JJR Solutions — Sistema de gestión marítima (Brasil)

> Sistema operativo en producción para escuela de formación marítima en Brasil. Gestiona alumnos, cursos, certificaciones DPC, pagos e instructores bajo el marco regulatorio de la Autoridade Marítima brasileña. Integrado como segundo tenant de la plataforma ABYSS. Migración en 7 etapas completadas (hardening B→D→C→A).

![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=flat-square&logo=jquery&logoColor=white)
![Linux](https://img.shields.io/badge/VPS_Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Status](https://img.shields.io/badge/Estado-Producción_activa-brightgreen?style=flat-square)
![Modernización](https://img.shields.io/badge/Modernización-Etapas_0–6_✓-orange?style=flat-square)

🌐 Live: [jjrsolutions.site](https://jjrsolutions.site/system/session/) · 📂 [`jjr-showcase`](https://github.com/Robertgaraban/jjr-showcase)

---

### 📄 Generador de Manuales HydroAbyss

> Pipeline documental que genera los 21 manuales STCW en PDF y DOCX con calidad institucional, versionado automático y trazabilidad normativa. Extracción desde PDF/DOCX originales (con OCR fallback: pdfplumber + pymupdf) y compilación mediante Pandoc + Tectonic (LaTeX). Comando único por curso o ejecución masiva de lote.

![Python](https://img.shields.io/badge/Python_3-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandoc](https://img.shields.io/badge/Pandoc-000000?style=flat-square)
![LaTeX](https://img.shields.io/badge/Tectonic_(LaTeX)-008080?style=flat-square&logo=latex&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![OCR](https://img.shields.io/badge/OCR-pdfplumber+pymupdf-3776AB?style=flat-square&logo=python&logoColor=white)
![Cobertura](https://img.shields.io/badge/Cobertura_STCW-19%2F21_cursos-blueviolet?style=flat-square)

📂 [`manual-generator-showcase`](https://github.com/Robertgaraban/manual-generator-showcase)

---

### 💼 Sistema de Nóminas

> Sistema interno de gestión de nóminas, fichajes y control financiero por proyecto. Frontend React SPA + PHP REST API + MySQL. Kiosko de fichaje móvil con GPS. Control financiero por proyecto/semana. Módulo de reportes operativos.

![React](https://img.shields.io/badge/React_18-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![PHP](https://img.shields.io/badge/PHP_REST_API-777BB4?style=flat-square&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![Status](https://img.shields.io/badge/Estado-Producción-brightgreen?style=flat-square)

🌐 Live: [nomina.atlantechmarine.com](https://nomina.atlantechmarine.com) · 📂 [`nominas-showcase`](https://github.com/Robertgaraban/nominas-showcase)

---

### 🤖 Agentes IA — HydroAbyss & ABYSS STCW

> Agentes de IA especializados con flujos de trabajo y reglas de dominio marítimo. Operan en producción para generación de manuales STCW, auditoría documental y control de paridad normativa. Arquitectura: AGENT.md (contexto del sistema) + skills reutilizables + pipeline determinista Python/Bash. Dominio cubierto: STCW · DGMM (España) · DPC (Brasil).

![Claude](https://img.shields.io/badge/Claude_(Anthropic)-D97706?style=flat-square)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-FF6B35?style=flat-square)
![Dominio](https://img.shields.io/badge/Dominio-STCW%20%7C%20DGMM%20%7C%20DPC-0077B6?style=flat-square)
![Status](https://img.shields.io/badge/Estado-Producción_activa-brightgreen?style=flat-square)

📂 [`agents-showcase`](https://github.com/Robertgaraban/agents-showcase)

---

### ⚙️ LLM + Diseño Naval — HydroAbyss RF-4

> Integración de LLMs con Fusion 360 (Python API) y AutoCAD LT (via servidor MCP + AutoLISP) para generar planos técnicos navales desde especificaciones estructuradas. **Proyecto ejecutado:** Catamarán autónomo HydroAbyss RF-4 (4.80 m, doble casco GFRP, propulsión eléctrica 800 W, sensores LiDAR Ouster OS1-32 + GNSS RTK + AIS, autopiloto ArduPilot + MPC adaptativo, COLREGs-compliant). TFG presentado en la Facultat de Nàutica de Barcelona (UPC).

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Fusion 360](https://img.shields.io/badge/Fusion_360_(Python_API)-FF6C00?style=flat-square&logo=autodesk&logoColor=white)
![AutoCAD](https://img.shields.io/badge/AutoCAD_LT%2BAutoLISP-E51937?style=flat-square)
![MCP](https://img.shields.io/badge/MCP_stdio_JSON-RPC-FF6B35?style=flat-square)
![Claude](https://img.shields.io/badge/Claude_(Anthropic)-D97706?style=flat-square)
![ArduPilot](https://img.shields.io/badge/ArduPilot+MPC-02569B?style=flat-square)
![TFG](https://img.shields.io/badge/TFG-FNB%2FUPC-8B0000?style=flat-square)

📂 [`naval-design-llm-showcase`](https://github.com/Robertgaraban/naval-design-llm-showcase)

---

### 📐 Skill: Maquetación TFG FNB/UPC

> Skill de IA para formatear TFG/TFM según la normativa oficial de la Facultat de Nàutica de Barcelona (FNB/UPC). Aplica estilos Word, estructura obligatoria, tipografía, paginación, citación ISO 690 y figuras/tablas — sin reescribir el contenido del autor.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Markdown](https://img.shields.io/badge/Markdown-000000?style=flat-square&logo=markdown&logoColor=white)
![Word](https://img.shields.io/badge/python--docx_(Word)-2B579A?style=flat-square&logo=microsoftword&logoColor=white)

📂 [`tfg-skill-showcase`](https://github.com/Robertgaraban/tfg-skill-showcase)

---

### 🧮 Cálculo de Estructuras Navales

> Notebooks de ingeniería naval: cálculo estructural, estabilidad y resistencia aplicados a embarcaciones.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter_Notebooks-F37626?style=flat-square&logo=jupyter&logoColor=white)

📂 [`Calculo-de-Estructuras-Navales-FNB`](https://github.com/Robertgaraban/Calculo-de-Estructuras-Navales-FNB)

---

## 🖥️ Capacidades como Arquitecto & DevOps

| Área | Evidencia |
|---|---|
| **Arquitectura SaaS multi-tenant** | ABYSS: tenant packs por país (España/Brasil), RBAC, lifecycle unificado, bootstrap por config |
| **Full-stack en producción** | React 18 + Vite · Node.js + Express · PostgreSQL · JWT · Socket.IO |
| **Despliegue VPS Linux** | Nginx (reverse proxy) · PM2 (supervisión de procesos) · scripts de deploy/rollback · smoke checks |
| **Real-time** | Socket.IO `/ws` sobre PostgreSQL `LISTEN/NOTIFY`, autenticación WebSocket con JWT |
| **Workers asincrónicos** | Node.js workers (`.js`/`.mjs`) para colas de comunicaciones, recordatorios, jobs programados |
| **Hardening de producción** | Post-mortems documentados · resolución de incidentes de autenticación · controles de workers · paridad normativa DPC |
| **Integración LLM + herramientas** | MCP stdio JSON-RPC · Fusion 360 Python API · AutoCAD AutoLISP · ezdxf headless |
| **Pipeline documental CI-style** | Pandoc + Tectonic · versionado automático · OCR fallback · QA por curso · ejecución en lote |
| **Agentes IA en producción** | AGENT.md por sistema · skills reutilizables · reglas de dominio no negociables · gate de calidad |
| **Dominio regulatorio** | STCW · DGMM/MITMA (España) · DPC/Autoridade Marítima (Brasil) · ISO/SGC |

---

## 📊 GitHub Stats

<div align="center">

![Robert's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Robertgaraban&show_icons=true&theme=dark&hide_border=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Robertgaraban&layout=compact&theme=dark&hide_border=true)

</div>

---

## 🗂️ Repositorios

Cada proyecto tiene dos capas: un **brief técnico público** (este repositorio y los showcases) y un **repositorio privado** con el código fuente completo, accesible como colaborador bajo solicitud.

| Proyecto | Showcase público | Estado |
|---|---|---|
| 🚢 HydroAbyss | [hydroabyss-showcase](https://github.com/Robertgaraban/hydroabyss-showcase) | ![](https://img.shields.io/badge/-Producción-brightgreen?style=flat-square) |
| ⚓ ABYSS STCW | [abyss-stcw-brief](https://github.com/Robertgaraban/abyss-stcw-brief) | ![](https://img.shields.io/badge/-Producción_activa-brightgreen?style=flat-square) |
| 🇧🇷 JJR Solutions | [jjr-showcase](https://github.com/Robertgaraban/jjr-showcase) | ![](https://img.shields.io/badge/-Producción-brightgreen?style=flat-square) |
| 📄 Manual Generator | [manual-generator-showcase](https://github.com/Robertgaraban/manual-generator-showcase) | ![](https://img.shields.io/badge/-Producción-brightgreen?style=flat-square) |
| 💼 Nóminas | [nominas-showcase](https://github.com/Robertgaraban/nominas-showcase) | ![](https://img.shields.io/badge/-Producción-brightgreen?style=flat-square) |
| 🤖 Agentes IA | [agents-showcase](https://github.com/Robertgaraban/agents-showcase) | ![](https://img.shields.io/badge/-Producción-brightgreen?style=flat-square) |
| ⚙️ Naval Design LLM | [naval-design-llm-showcase](https://github.com/Robertgaraban/naval-design-llm-showcase) | ![](https://img.shields.io/badge/-Completado-8A2BE2?style=flat-square) |
| 📐 TFG Skill | [tfg-skill-showcase](https://github.com/Robertgaraban/tfg-skill-showcase) | ![](https://img.shields.io/badge/-Producción-brightgreen?style=flat-square) |

**Para acceso a código fuente:** contacto disponible en los badges de la cabecera — Asunto: `[Acceso repo privado] <nombre-repo>`

---

<div align="center">

*Arquitectura · DevOps · Formación marítima · Tecnología · Gestión operativa*

</div>
