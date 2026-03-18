# 🔐 Auditoría ISO 27001 — Gestión Empresarial y Alineamiento de la Ciberseguridad


## 📋 Índice

1. [Objetivo](#1-objetivo)
2. [Descripción del caso](#2-descripción-del-caso)
3. [Disciplina de valor de negocio prioritaria](#3-disciplina-de-valor-de-negocio-prioritaria)
4. [Acciones según COBIT 2019](#4-acciones-según-cobit-2019)
5. [Análisis de riesgos MAGERIT](#5-análisis-de-riesgos-magerit)
6. [Controles de seguridad ISO/IEC 27001:2022](#6-controles-de-seguridad-isoiec-270012022)
7. [Política de ciberseguridad](#7-política-de-ciberseguridad)
8. [Referencias](#8-referencias)

---

## 1. Objetivo

La realización de esta actividad tiene como objetivo saber identificar las disciplinas de valor que tiene la empresa objetivo, para posteriormente realizar el análisis de riesgos y trasladar todo este análisis previo a la certificación de la **ISO 27001**.

---

## 2. Descripción del caso

La empresa analizada se dedica a las **inversiones de terceras personas**, operando en bolsa con las inversiones de sus clientes locales. Dispone de **4 oficinas (A, B, C y D)**, siendo A la central.

### Infraestructura tecnológica

- Cada oficina cuenta con un **CPD** propio (la central dispone de dos).
- Los CPDs albergan servidores con aplicaciones de gestión, servicios y bases de datos de clientes, proveedores e históricos.
- Cada empleado dispone de **equipo fijo**, salvo los directores que utilizan **portátiles**.
- Se dispone de **tabletas** para firma de contratos y **smartphones** para visitas a clientes.
- Las redes locales están interconectadas mediante **VPN**.
- La **red WiFi** está distribuida en todas las oficinas.
- Los proveedores de servicios tienen acceso restringido a las redes que necesitan.

### Estructura organizativa

- Cada oficina tiene un **director** y diversos departamentos: servicios jurídicos, análisis de riesgos, recuperaciones, etc.
- En la **central** se ubican adicionalmente los jefes de departamento y el departamento de **RRHH**.
- Se cuenta con **proveedores de servicios técnicos** externos.

---

## 3. Disciplina de valor de negocio prioritaria

### Disciplina seleccionada

La disciplina de valor prioritaria identificada es la **Seguridad de la Información**, complementada con la **Seguridad en las Operaciones** y la **Gestión del Riesgo**.

### Justificación

La empresa maneja **datos financieros sensibles de clientes** (PII), lo que la hace especialmente vulnerable a ciberataques con graves consecuencias legales, financieras y reputacionales. Es necesario implementar medidas robustas de ciberseguridad y controles de acceso para mitigar los riesgos asociados a:

- La gestión de información confidencial de clientes.
- La continuidad de las operaciones financieras.
- El cumplimiento normativo aplicable.

---

## 4. Acciones según COBIT 2019

El marco **COBIT 2019** organiza las prácticas de gobierno y gestión de TI en cinco dominios principales:

| Dominio | Descripción |
|---------|-------------|
| **EDM** | Evaluar, Dirigir y Monitorear |
| **APO** | Alinear, Planificar y Organizar |
| **BAI** | Construir, Adquirir e Implementar |
| **DSS** | Entregar, Dar Servicio y Soportar |
| **MEA** | Monitorear, Evaluar y Valorar |

### Tabla de acciones específicas

| Valor de Negocio | Dominio COBIT | Subdominio | Acciones Específicas |
|---|---|---|---|
| **Alineación de Objetivos** | Principio COBIT | Habilitador de valor | Identificar objetivos estratégicos relacionados con confianza del cliente, integridad de operaciones y cumplimiento normativo. Mapear estos objetivos en metas de gobernanza de TI mediante los factores de diseño de COBIT. Establecer métricas de desempeño. |
| **Seguridad de la Información** | APO | APO01 - Gestión del Marco de Gobierno de TI | Establecer políticas de gobernanza de seguridad. Definir roles clave (CISO, CIO, auditores). |
| | APO | APO12 - Gestión del Riesgo de TI | Identificar riesgos de confidencialidad e integridad. Evaluaciones periódicas de riesgo. Análisis de amenazas y vulnerabilidades. |
| | APO | APO13 - Gestión de la Seguridad de la Información | Establecer políticas alineadas con ISO 27001. Implementar controles de acceso y segmentación de redes. Plan de concienciación. |
| | DSS | DSS04 - Gestión de la Continuidad | Desarrollar y probar DRP y BCP. Implementar backups frecuentes. |
| | DSS | DSS05 - Gestión de Seguridad de Servicios | Implementar MFA, PAM, SIEM, IDS/IPS, firewalls. Auditorías periódicas y pentesting. |
| | BAI | BAI03 - Gestión de la Arquitectura de TI | Cifrado de datos (TLS, AES-256). Implementar IAM, DLP, EDR, SOC. Segmentación de redes. |
| | MEA | MEA03 - Monitoreo de Conformidad | Revisar cumplimiento GDPR, PCI DSS. Auditorías periódicas. |
| **Seguridad en las Operaciones** | DSS | DSS01 - Gestión de Operaciones | Alta disponibilidad, copias de seguridad diarias, monitoreo de sistemas críticos. |
| | DSS | DSS02 - Gestión de Incidentes | Proceso de gestión de incidentes con playbooks. |
| | DSS | DSS04 - Gestión de Continuidad | DRP, simulacros, replicación en tiempo real. |
| | DSS | DSS06 - Optimización de Servicios | SLAs con terceros y proveedores. |
| | BAI | BAI06 - Gestión de Cambios | Documentar cambios, pruebas previas, revisiones por pares. |
| | APO | APO10 - Gestión de Proveedores | Evaluar seguridad de proveedores, cláusulas contractuales, supervisión de accesos. |
| | MEA | MEA01 - Monitoreo del Desempeño | KPIs de tiempo de respuesta, monitoreo de transacciones en tiempo real. |
| **Gestión del Riesgo** | APO | APO12 - Gestión de Riesgos | Marco formal basado en ISO 31000. Identificar y priorizar riesgos. Definir tolerancias. |
| | APO | APO14 - Gestión de la Seguridad | Análisis con MITRE ATT&CK. Planes de mitigación. Monitoreo de amenazas emergentes. |
| | MEA | MEA02 - Monitoreo de Controles Internos | Auditorías regulares, informes de cumplimiento automatizados, revisión con frameworks como NIST CSF. |
| | DSS | DSS02 - Gestión de Incidentes de TI | IRP con roles claros, escenarios de crisis (DDoS, ransomware, filtraciones). Contacto con reguladores. |
| | BAI | BAI10 - Gestión de Proyectos | Priorizar proyectos de ciberseguridad para cerrar brechas críticas. |

---

## 5. Análisis de riesgos MAGERIT

### Metodología

**MAGERIT** (Metodología de Análisis y Gestión de Riesgos de los Sistemas de Información) permite identificar, valorar y gestionar los riesgos a los que están expuestos los activos de información.

**Fórmula:** `RIESGO = IMPACTO × PROBABILIDAD`

### Escalas de valoración

| Nº | Probabilidad | Frecuencia | Impacto | Descripción |
|----|-------------|------------|---------|-------------|
| 5 | Muy frecuente | A diario | Muy alto | Determinante |
| 4 | Frecuente | Mensualmente | Alto | Significativo |
| 3 | Normal | Una vez al año | Medio | Importante |
| 2 | Poco frecuente | Cada varios años | Bajo | Relevante |
| 1 | Muy infrecuente | Cada varias décadas | Muy bajo | Poco relevante |

### Tabla de análisis de riesgos

| Tipo de Activo | Activo | Impacto (I) | Probabilidad (P) | Riesgo (I×P) | Justificación | Recomendaciones |
|---|---|:---:|:---:|:---:|---|---|
| **Información** | Base de datos de clientes | 5 | 4 | **20** 🔴 | Contiene PII. Amenazas de accesos no autorizados y fugas de información. | Cifrado AES-256, RBAC, auditorías de acceso |
| | Documentación confidencial | 4 | 3 | **12** 🟠 | Proyectos estratégicos cuya exposición compromete la ventaja competitiva. | — |
| | Informes financieros | 5 | 2 | **10** 🟡 | Alto impacto pero probabilidad menor gracias a controles existentes (ERP, cifrado). | — |
| **Tecnológicos** | Servidor de correo | 4 | 4 | **16** 🔴 | Vector crítico de phishing/malware. Vulnerable a configuraciones incorrectas. | Actualización de firmware, IDS/IPS, EDR en portátiles |
| | Firewalls perimetrales | 5 | 2 | **10** 🟡 | Alto impacto pero bien mantenidos, reduciendo la probabilidad de explotación. | — |
| | Equipos portátiles | 3 | 5 | **15** 🔴 | Frecuentemente expuestos fuera de la red segura; vulnerables al robo físico. | — |
| **Humanos** | Administradores | 5 | 4 | **20** 🔴 | Acceso privilegiado = objetivo clave para ingeniería social y robo de credenciales. | Formación continua, principio de menor privilegio, simulaciones de phishing |
| | Equipo de soporte | 3 | 3 | **9** 🟡 | Menor privilegio pero pueden ser manipulados para obtener acceso. | — |
| | Usuarios finales | 4 | 5 | **20** 🔴 | Alta probabilidad de error humano (phishing, contraseñas débiles). | — |
| **Físicos** | Data center | 5 | 3 | **15** 🔴 | Incendios, inundaciones, accesos no autorizados con impacto crítico. | Detección de incendios, controles biométricos, segmentación de redes CCTV |
| | Oficinas administrativas | 3 | 4 | **12** 🟠 | Robos o accesos físicos no autorizados pueden comprometer documentación. | — |
| | Sistemas de CCTV | 4 | 2 | **8** 🟢 | Riesgo de acceso remoto, pero moderado. | — |
| **Procesos** | Gestión de copias de seguridad | 5 | 3 | **15** 🔴 | Copias mal gestionadas pueden ser inutilizables ante desastres. | Automatización, pruebas periódicas, revisión semestral del BCP |
| | Respuesta a incidentes | 4 | 4 | **16** 🔴 | Procedimientos deficientes prolongan la recuperación ante ciberataques. | — |
| | Continuidad de negocio | 5 | 2 | **10** 🟡 | Un plan adecuado mitiga interrupciones críticas; probabilidad de activación baja. | — |
| **Relacionales** | Proveedores de TI | 5 | 3 | **15** 🔴 | Alta dependencia; una brecha en sus sistemas afecta directamente a la empresa. | Cláusulas de seguridad contractuales, auditorías de terceros, NDAs reforzados |
| | Clientes clave | 4 | 2 | **8** 🟢 | Exposición de datos puede dañar la relación comercial y reputación. | — |
| | Colaboradores externos | 3 | 4 | **12** 🟠 | Pueden manejar información sensible sin cumplir los estándares internos. | — |

> **Leyenda de riesgo:** 🔴 Alto (≥15) · 🟠 Medio-alto (12-14) · 🟡 Medio (9-11) · 🟢 Bajo (≤8)

---

## 6. Controles de seguridad ISO/IEC 27001:2022

Controles propuestos por categoría de amenaza, alineados con el **Anexo A de la ISO/IEC 27001:2022**:

| Categoría | Tipo de Amenaza | Control | Justificación | Referencia ISO 27001 |
|---|---|---|---|---|
| **Daños naturales** | Incendios, inundaciones y desastres que amenazan la infraestructura | Sistemas de detección de incendios y control de clima en el data center | El CPD debe contar con detectores de humo, sistemas de extinción y controles de temperatura para prevenir daños en servidores. | Anexo A.11.2.2 — Protección contra amenazas ambientales y naturales |
| | | Plan de contingencia en oficinas | Procedimientos claros de evacuación y recuperación para reducir el impacto de desastres. | Anexo A.17.1.2 — Implementación de planes de continuidad de negocio |
| **Amenazas industriales** | Fallos de infraestructura y problemas técnicos | Supervisión ambiental del CPD | Monitorear temperatura, humedad y energía para detectar anomalías que puedan provocar interrupciones. | Anexo A.11.2.3 — Seguridad en los equipos |
| | | Redundancias en sistemas críticos | Servidores y sistemas de backup con redundancias eléctricas y conexiones alternativas. | Anexo A.17.2.1 — Disponibilidad de sistemas |
| **Errores no intencionados** | Errores humanos o fallos accidentales en software/hardware | Copias de seguridad automáticas | Automatizar las copias de seguridad de la información crítica. | Anexo A.17.3.2 — Copia de seguridad |
| | | Formación y concienciación de empleados | Formación en políticas de ciberseguridad, simulaciones de ataques y campañas de concienciación. | Anexo A.7.2.2 — Concienciación, educación y formación en seguridad |
| **Ataques intencionados** | Ciberataques y actos maliciosos para obtener información crítica | Auditorías de accesos y monitorización | Revisión periódica de los accesos de usuarios y sus privilegios para detectar robos de credenciales. | Anexo A.9.2.5 — Revisión de derechos de acceso de los usuarios |
| | | Autenticación multifactor (MFA) | Control de acceso a sistemas críticos para reducir accesos no autorizados. | Anexo A.9.4.2 — Control de acceso a sistemas y aplicaciones |

---

## 7. Política de ciberseguridad

> *"La empresa garantizará la protección de toda la información sensible de clientes y proyectos mediante controles técnicos y organizativos, satisfaciendo los requisitos de confidencialidad e integridad. Los accesos a los sistemas serán gestionados por mecanismos de autenticación robustos y los datos serán cifrados y almacenados en la nube. Los empleados se formarán y seguirán las políticas para el manejo seguro de la información."*

---

## 8. Referencias

- [Resumen COBIT 2019 — Scribd](https://www.scribd.com/document/622786241/Resumen-Que-es-COBIT-2019)
- [COBIT 2019 — IAIA](https://iaia.org.ar/wp-content/uploads/2019/07/COBIT2019-IAIA.pdf)
- [MAGERIT — Administración Electrónica](https://administracionelectronica.gob.es/pae_Home/pae_Documentacion/pae_Metodolog/pae_Magerit.html)
- [ISO 27001 — ISMS Online](https://www.isms.online/iso-27001/)
- [ISO 27000 ES](https://www.iso27000.es/index.html)
