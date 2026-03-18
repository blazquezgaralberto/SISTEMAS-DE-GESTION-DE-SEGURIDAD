# 🗺️ Plan Director de Seguridad

## 📋 Índice

1. [Introducción](#1-introducción)
   - 1.1 [Objetivos](#11-objetivos)
   - 1.2 [Caso de estudio](#12-caso-de-estudio)
2. [Fases del Plan Director de Seguridad](#2-fases-del-plan-director-de-seguridad)
   - [Fase 1 — Definición del alcance](#fase-1--definición-del-alcance)
   - [Fase 2 — Conocer la situación actual](#fase-2--conocer-la-situación-actual-de-la-entidad)
   - [Fase 3 — Definir proyectos, iniciativas y actividades](#fase-3--definir-los-proyectos-iniciativas-y-actividades)
   - [Fase 4 — Clasificar y priorizar actividades](#fase-4--clasificar-y-priorizar-los-proyectos-iniciativas-y-actividades)
   - [Fase 5 — Aprobación del plan](#fase-5--aprobación-del-plan)
   - [Fase 6 — Puesta en marcha del plan](#fase-6--puesta-en-marcha-del-plan)
3. [Plan de Acciones resultante](#3-plan-de-acciones-resultante)
4. [ENS vs ISO 27001/27002 — Similitudes y diferencias](#4-ens-rd-3112022-vs-iso-2700127002--similitudes-y-diferencias)
5. [Bibliografía](#5-bibliografía)

---

## 1. Introducción

### 1.1 Objetivos

El objetivo de esta actividad es aprender a diseñar un **Plan Director de Seguridad (PDS)**, llevando a cabo las siguientes tareas:

1. Desarrollar de forma justificada cada una de las fases del PDS.
2. Describir el plan de acciones resultante con el máximo detalle posible.
3. Describir similitudes y diferencias entre el **ENS (RD 311/2022)** y las **ISO 27001/27002** aplicadas al PDS.

### 1.2 Caso de estudio

La organización seleccionada es el **Ayuntamiento de un municipio ficticio**.

**Motivación:** Respuesta a un incidente de seguridad reciente de acceso no autorizado al servidor de base de datos.

El Ayuntamiento dispone de una oficina con un CPD que aloja:

| Activo | Servicios prestados |
|---|---|
| **Servidor web** | Solicitudes y trámites administrativos, portal de noticias, pago de impuestos, cita previa |
| **Servidor de correo** | Correo interno del personal, notificaciones a ciudadanos, atención al ciudadano y agentes externos |
| **Servidor de bases de datos** | Almacenamiento de datos sensibles de ciudadanos, trámites y procesos municipales |

---

## 2. Fases del Plan Director de Seguridad

---

### Fase 1 — Definición del alcance

#### Organización y motivación

- **Organización:** Ayuntamiento de un municipio.
- **Motivación:** Incidente de acceso no autorizado al servidor de BBDD que ha evidenciado vulnerabilidades en la infraestructura TI.
- **Objetivo general:** Establecer un marco integral para identificar, evaluar y mitigar riesgos en la gestión de la información y la infraestructura tecnológica del Ayuntamiento.

#### Acotación del alcance

**Infraestructura tecnológica incluida:**

- Servidor web: trámites administrativos, portal de noticias, módulo de pago de impuestos, sistema de cita previa.
- Servidor de correo: correo interno, notificaciones a ciudadanos, atención al ciudadano y agentes externos.
- Servidor de bases de datos: datos sensibles de ciudadanos, trámites y procesos municipales.

**Procesos y servicios críticos:**
- Gestión de trámites administrativos.
- Módulo de pagos de impuestos.
- Notificaciones a ciudadanos.
- Almacenamiento de datos sensibles.

**Exclusiones del alcance:** Seguridad física no relacionada directamente con la infraestructura TI, y procesos administrativos que se desarrollen íntegramente fuera del entorno digital.

#### Identificación de responsables

| Responsable | Funciones principales |
|---|---|
| **Administrador de Base de Datos** | Supervisión de integridad y seguridad de datos, control de acceso, cifrado, auditorías, copias de seguridad y recuperación ante desastres |
| **Administrador de Sistemas Web** | Configuración y mantenimiento del servidor web, monitoreo de tráfico, SSL/TLS, gestión de copias de seguridad |
| **Administrador de TI** | Gestión del servidor de correo, filtros de seguridad, políticas de retención, capacitación del personal |
| **Jefe de Tecnología de la Información** | Supervisión general de aplicaciones y servicios, políticas de uso, coordinación, evaluaciones de riesgo |

#### Modelo de madurez

| Nivel | Significado |
|---|---|
| **NA** | No aplica implementar el control |
| **N0** | Inexistente — Control no aplicado |
| **N1** | Inicial — Aplicación inicial sin comprobar o con configuración por defecto |
| **N2** | Repetible — Control reproducible con configuración mínima |
| **N3** | Definido — Medida definida, aplicada, configurada y procedimental |
| **N4** | Administrado — Control gestionado y medible |
| **N5** | Optimizado — Medida optimizada |

#### Identificación y valoración inicial de controles (referencia ENS)

| Activo | Control | Artículo ENS de referencia |
|---|---|---|
| **Servidor web** | Control de acceso — MFA | Art. 12.6.e: Medidas de control de acceso |
| | Monitorización — IDS | Art. 10.1: Registro y vigilancia |
| | Copias de seguridad diarias | Art. 26: Plan de copias de seguridad |
| **Servidor de correo** | Filtrado de spam y malware | Art. 8.4: Protección ante malware |
| | Política de retención de correo | Art. 22: Conservación de la información |
| **Servidor de BBDD** | Control de acceso con roles y permisos | Art. 17: Autorización y control de accesos |
| | Cifrado en reposo y en tránsito | Art. 22: Conservación de la información |
| **Infraestructura de redes** | Firewall perimetral | Art. 19: Adquisición de productos de seguridad |
| **Aplicaciones y servicios** | Actualizaciones y parches regulares | Art. 21: Integridad y actualización del sistema |
| **Política de seguridad** | Establecimiento de normas de tratamiento | Art. 12: Política de seguridad y requisitos mínimos |

#### Análisis de cumplimiento

| Activo | Control | Nivel actual | Nivel objetivo |
|---|---|---|---|
| **Servidor Web** | Control de acceso | N0 — Sin sistema de gestión de acceso | N3 — Sistema MFA implementado |
| | Monitorización de seguridad | N3 — Sistema de monitorización existente | N3 — Sin cambios necesarios |
| | Copia de seguridad | N0 — Sin sistema automatizado | N3 — Sistema de backups regular, automático y monitorizado |
| **Servidor de Correo** | Filtrado de spam y malware | N0 — Sin sistema de filtrado | N3 — Sistema de filtrado de contenido implementado |
| | Política de retención | N3 — Sistema de almacenado existente | N3 — Sin cambios necesarios |
| **Servidor de BBDD** | Control de acceso | N0 — Sin sistema robusto de gestión de accesos | N3 — Sistema con roles y permisos granulares |
| | Cifrado de datos | N0 — Sin medidas de cifrado | N3 — Sistema de cifrado implementado |
| **Infraestructura de redes** | Firewall | N0 — Sin firewall perimetral | N3 — Firewall perimetral protegiendo la red interna |
| **Aplicaciones y servicios** | Actualizaciones | N0 — Sin control periódico de actualizaciones | N3 — Sistema de actualizaciones periódicas implementado |
| **Política de seguridad** | Política de seguridad | N0 — Sin política definida | N3 — Política definida, aprobada y accesible |

#### Análisis de riesgos

##### Amenazas identificadas por activo

**Servidor Web:**
- Ataques DDoS que interrumpan el acceso al servicio.
- Acceso no autorizado por vulnerabilidades en la aplicación.
- Inyección SQL que comprometa la base de datos de solicitudes.
- Phishing dirigido a usuarios para obtener credenciales.
- Suplantación de identidad del sitio web (desinformación).
- Malware distribuido a usuarios que acceden al portal.
- Ataques Man-in-the-Middle en el módulo de pago de impuestos.
- Robo de credenciales a través de formularios no seguros.

**Servidor de correo electrónico:**
- Phishing que comprometa cuentas de correo interno.
- Malware adjunto en correos electrónicos.
- Acceso no autorizado por contraseñas débiles.
- Manipulación e interceptación de notificaciones a ciudadanos.
- Spam que sature el sistema.
- Falsificación de consultas e ingeniería social.

**Servidor de bases de datos:**
- Acceso no autorizado a datos sensibles.
- Fugas de datos por infraestructura mal configurada.
- Pérdida de datos críticos por fallos o ausencia de copias de seguridad.
- Inyección de comandos.

##### Mapa de riesgos potenciales (PRE-Control)

> **Escala:** Baja (B) · Media (M) · Alta (A)

| Amenaza | Activo afectado | Probabilidad | Impacto | Riesgo |
|---|---|:---:|:---:|:---:|
| Ataques DDoS | Servidor Web | A | A | 🔴 Alto |
| Acceso no autorizado (Vulnerabilidades) | Servidor Web / BBDD | M | A | 🔴 Alto |
| Inyección SQL | Servidor Web | M | A | 🔴 Alto |
| Phishing (Credenciales) | Servidor Web / Correo | M | A | 🔴 Alto |
| Robo de credenciales (Pago de Impuestos) | Servidor Web | M | A | 🔴 Alto |
| Acceso no autorizado (BBDD) | Servidor BBDD | B | A | 🔴 Alto |
| Fugas de datos | Servidor BBDD | B | A | 🔴 Alto |
| Pérdida de datos (BBDD) | Servidor BBDD | M | A | 🔴 Alto |
| Inyección de comandos (BBDD) | Servidor BBDD | B | A | 🔴 Alto |
| Suplantación de identidad | Servidor Web | M | M | 🟠 Medio |
| Interrupciones del servicio | Servidor Web | M | M | 🟠 Medio |
| Malware/Virus | Servidor Web | M | M | 🟠 Medio |
| Ataques MitM (Pago de Impuestos) | Servidor Web | B | A | 🟠 Medio |
| Pérdida de datos financieros | Servidor Web | B | A | 🟠 Medio |
| Phishing (Correo Interno) | Servidor Correo | M | M | 🟠 Medio |
| Malware en correo | Servidor Correo | M | M | 🟠 Medio |
| Acceso no autorizado (Correo) | Servidor Correo | M | M | 🟠 Medio |
| Spam/Correos no deseados | Servidor Correo | A | B | 🟠 Medio |
| Falsificación de consultas | Servidor Correo | M | M | 🟠 Medio |
| Ataques de ingeniería social | Servidor Correo | M | M | 🟠 Medio |
| Manipulación de notificaciones | Servidor Correo | B | M | 🟢 Bajo |
| Interceptación de notificaciones | Servidor Correo | B | M | 🟢 Bajo |

##### Mapa de riesgos residuales (POST-Control)

| Amenaza | Activo afectado | Probabilidad | Impacto | Riesgo |
|---|---|:---:|:---:|:---:|
| Ataques DDoS | Servidor Web | M | M | 🟠 Medio |
| Acceso no autorizado (Vulnerabilidades) | Servidor Web / BBDD | B | M | 🟢 Bajo |
| Inyección SQL | Servidor Web | B | M | 🟢 Bajo |
| Phishing (Credenciales) | Servidor Web / Correo | B | M | 🟢 Bajo |
| Todas las demás amenazas | Todos los activos | B | B | 🟢 Bajo |

---

### Fase 2 — Conocer la situación actual de la entidad

#### Análisis de proyectos en curso y futuros

Se realizarán entrevistas para identificar proyectos en curso y futuros, abordando:
- Estado de desarrollo de proyectos actuales.
- Necesidades tecnológicas de proyectos futuros.
- Planes de expansión de servicios digitales para ciudadanos.
- Dependencias tecnológicas que garanticen la continuidad.

#### Comité Responsable de Seguridad

| Miembro | Rol |
|---|---|
| Administrador de Base de Datos | Miembro técnico |
| Administrador de Sistemas Web | Miembro técnico |
| Administrador de TI | Miembro técnico |
| Jefe de Tecnología de la Información | Coordinador del comité |

El comité tomará decisiones basándose en: presupuesto disponible, registro de incidentes, priorización de procesos críticos y cumplimiento del **ENS**.

#### Priorización de procesos críticos

| Proceso crítico | Dimensiones a proteger |
|---|---|
| Gestión de trámites administrativos | Disponibilidad e integridad |
| Pago de impuestos | Confidencialidad y seguridad de datos financieros |
| Notificaciones a ciudadanos | Autenticidad e integridad de las comunicaciones |
| Almacenamiento de datos personales sensibles | Seguridad y confidencialidad |

#### Orientación de las medidas de control

- Los controles sobre **procesos críticos** se implementarán en plazos **cortos** y con presupuesto prioritario.
- Los controles sobre procesos menos críticos se implementarán en un **segundo plano**, con plazos más amplios.
- El énfasis recae en el cumplimiento normativo y en la protección de la **confidencialidad, integridad y disponibilidad** de los datos.

---

### Fase 3 — Definir los proyectos, iniciativas y actividades

#### Escalas de valoración

**Coste (tiempo y recursos):**
- **Bajo:** Pocos días, coste reducido, sin dificultad presupuestaria.
- **Medio:** Algunas semanas, puede presionar el presupuesto si se acumulan controles similares.
- **Alto:** Varios meses, coste elevado que puede impedir la implantación de otras medidas.

**Complejidad:**
- **Bajo:** Aplicable por el personal técnico interno sin soporte externo.
- **Medio:** Aplicable internamente, pero requiere asesoría de proveedor externo.
- **Alto:** Debe ser externalizado a un servicio especializado.

#### Estimación de costes por control

| Control | Tiempo | Gasto | Complejidad | Coste total |
|---|:---:|:---:|:---:|:---:|
| Control de Acceso (BBDD) | Medio | Alto | Alto | 🔴 Alto |
| Firewall | Alto | Alto | Alto | 🔴 Alto |
| Filtrado de Spam y Malware | Medio | Medio | Bajo | 🟠 Medio |
| Política de Retención de Correo | Medio | Bajo | Medio | 🟠 Medio |
| Control de Acceso (Servidores) | Medio | Medio | Medio | 🟠 Medio |
| Cifrado de Datos | Alto | Medio | Medio | 🟠 Medio |
| Política de Seguridad | Medio | Bajo | Medio | 🟠 Medio |
| Copia de Seguridad | Bajo | Bajo | Bajo | 🟢 Bajo |
| Actualizaciones | Bajo | Bajo | Bajo | 🟢 Bajo |

#### Actividades a implementar

| ID | Actividad | Descripción |
|---|---|---|
| **01** | Desarrollar e implementar una política de seguridad | Política que incluya: compromiso de la Dirección, uso de email e Internet, uso de dispositivos móviles y protección de datos |
| **02** | Desplegar un plan de concienciación en seguridad de la información | Sesiones de formación y concienciación para personal operativo y Dirección |
| **03** | Política de copias de seguridad | Análisis de la información corporativa e implantación de un sistema automatizado de copias con restauraciones periódicas |
| **04** | Política de tratamiento de información | Sistema que contemple etiquetado, acceso, destrucción, almacenamiento y cifrado |
| **05** | Política de accesos | Definición de una política de control de accesos a los sistemas TIC |
| **06** | Mejora en la gestión de incidentes | Definición, documentación e implantación de un proceso de gestión de incidentes de seguridad |
| **07** | Desarrollar un Plan de continuidad TIC | Implantación de IDS, firewall perimetral y plan de actualización de hardware y software |

---

### Fase 4 — Clasificar y priorizar los proyectos, iniciativas y actividades

#### Categorización de actividades

Las actividades están ordenadas por **urgencia e impacto directo** (quick wins primero):

| ID | Actividad | Categoría | Descripción |
|---|---|---|---|
| **01** | Desarrollar un Plan de continuidad TIC | Técnico | Implantación de IDS, firewall perimetral y plan de actualización de hardware y software |
| **02** | Política de accesos | Organizativo / Técnico | Definir una política de control de accesos a los sistemas TIC |
| **03** | Desarrollar e implementar una política de seguridad | Organizativo / Procedimental | Política con compromiso de la Dirección, uso de tecnologías y protección de datos |
| **04** | Desplegar un plan de concienciación | Organizativo | Sesiones de formación para personal operativo y Dirección |
| **05** | Política de tratamiento de información | Procedimental / Técnico | Etiquetado, acceso, destrucción, almacenamiento y cifrado de información |
| **06** | Mejora en la gestión de incidentes | Organizativo / Procedimental / Técnico | Proceso de gestión y respuesta a incidentes de seguridad |
| **07** | Política de copias de seguridad | Procedimental / Técnico | Sistema automatizado de copias con restauraciones periódicas |

#### Verificación de costes (Fase 3 → Fase 4)

| Actividad | Controles relacionados | Tiempo | Gasto | Complejidad | Coste total | Verificación |
|---|---|:---:|:---:|:---:|:---:|---|
| 01. Plan de continuidad TIC | Firewalls, Actualizaciones | Alto | Alto | Alto | 🔴 Alto | Sin cambios — Alta inversión en hardware/software de seguridad |
| 02. Política de accesos | Control de accesos | Medio | Alto | Alto | 🔴 Alto | Sin cambios — Inversión elevada en infraestructura de acceso |
| 03. Política de seguridad | Política de seguridad | Medio | Bajo | Medio | 🟠 Medio | Sin cambios — Medida de coste medio |
| 04. Plan de concienciación | Política de Seguridad, Filtrado Spam | Medio | Medio | Bajo | 🟠 Medio | Sin cambios — Esfuerzo en formación e implantación de controles simples |
| 05. Política de tratamiento | Cifrado de datos | Alto | Medio | Medio | 🟠 Medio | Sin cambios — Complejidad y tiempo consistentes |
| 06. Gestión de incidentes | Control de Accesos, Firewalls | Medio | Medio | Medio | 🟠 Medio | Sin cambios — Coste de mejora en gestión de incidentes mantenido |
| 07. Política de copias | Copia de seguridad | Bajo | Bajo | Bajo | 🟢 Bajo | Sin cambios — Actividad de bajo coste y esfuerzo |

> ✅ No se han producido cambios significativos entre las estimaciones de las Fases 2, 3 y 4. El presupuesto y recursos previstos inicialmente se mantienen válidos.

---

### Fase 5 — Aprobación del plan

El PDS debe ser aprobado por el **equipo directivo** de la entidad, que dotará de los recursos necesarios para la implantación de los distintos proyectos.

#### Registro de revisiones

| Versión | Fecha | Autor | Descripción | Estado | Aprobado por | Fecha de aprobación |
|---|---|---|---|---|---|---|
| 1.0 | 25/01/2025 | Álvaro Vázquez Pacheco | Primera propuesta de PDS | Borrador | Jesús F. De Francisco Granda | 26/01/2025 |
| 1.1 | 26/01/2025 | Jesús F. De Francisco Granda | Segunda propuesta de PDS | Documento final | Alberto Blázquez García | 27/01/2025 |
| 1.2 | 28/01/2025 | Alberto Blázquez García | Última propuesta de PDS | Documento final revisado | MUSTIC - Equipo 12 | 28/01/2025 |

---

### Fase 6 — Puesta en marcha del plan

Todas las tareas serán supervisadas por el **Jefe de Tecnología de la Información**, con reuniones semanales para reportar avances y gestionar cambios no previstos.

#### Tabla de asignación de actividades

| ID | Actividad | Responsable/s asignado/s |
|---|---|---|
| **01** | Desarrollar un Plan de continuidad TIC | Administrador de TI |
| **02** | Política de accesos | Administrador de Base de Datos |
| **03** | Desarrollar e implementar una política de seguridad | Administrador de TI · Administrador de BBDD · Administrador de Sistemas Web |
| **04** | Desplegar un plan de concienciación | Jefe de Tecnología de la Información |
| **05** | Política de tratamiento de información | Administrador de Sistemas Web |
| **06** | Mejora en la gestión de incidentes | Administrador de TI |
| **07** | Política de copias de seguridad | Administrador de BBDD · Administrador de Sistemas Web |

---

## 3. Plan de Acciones resultante

El Plan de Acciones recoge las actividades concretas para mitigar riesgos y alinear la organización con **ISO/IEC 27001** y el **ENS (RD 311/2022)**.

---

### Acción 1 — Desarrollo e implementación de una política de seguridad

**Contenido:**
- Compromiso formal de la Dirección en la protección de datos e infraestructura.
- Normas de uso seguro de correo, Internet y dispositivos móviles.
- Directrices de protección de datos sensibles.
- Procedimientos de gestión de incidentes.

**Acciones clave:** Redacción del documento con el Comité de Seguridad → Difusión y capacitación del personal → Sistema de revisión periódica.

| Campo | Detalle |
|---|---|
| **Prioridad** | Alta |
| **Responsable** | Jefe de TI + Comité de Seguridad |
| **Plazo** | 1–2 meses |

---

### Acción 2 — Gestión de copias de seguridad automatizadas

**Contenido:**
- Sistema automatizado de copias de seguridad diarias con capacidad de recuperación ante desastres.
- Almacenamiento cifrado de datos y sus copias.
- Pruebas periódicas de restauración.

**Acciones clave:** Implementación de software especializado → Definición de frecuencia y política de retención → Pruebas de restauración en entornos controlados.

| Campo | Detalle |
|---|---|
| **Prioridad** | Muy alta |
| **Responsable** | Administrador de BBDD + Administrador de Sistemas Web |
| **Plazo** | 1 mes |

---

### Acción 3 — Desarrollo de un plan de continuidad TIC

**Contenido:**
- Despliegue de IDS y firewalls para protección perimetral.
- Actualización de hardware y software para garantizar integridad y disponibilidad.

**Acciones clave:** Configuración de herramientas avanzadas (firewalls, IDS/IPS) → Evaluación de riesgos en infraestructura física y lógica → Simulacros con lecciones aprendidas y reajuste del plan.

| Campo | Detalle |
|---|---|
| **Prioridad** | Alta |
| **Responsable** | Administrador de TI |
| **Plazo** | 3–4 meses |

---

### Acción 4 — Implementación de políticas de control de acceso

**Contenido:**
- MFA en sistemas críticos.
- Roles y permisos granulares en servidores y bases de datos.

**Acciones clave:** Configuración de políticas de acceso → Auditorías regulares de detección de accesos no autorizados → Revisión y ajuste periódico de permisos.

| Campo | Detalle |
|---|---|
| **Prioridad** | Alta |
| **Responsable** | Administrador de BBDD + Administrador de Sistemas Web |
| **Plazo** | 2 meses |

---

### Acción 5 — Programa de concienciación y formación

**Contenido:**
- Formación para reconocer phishing y malware.
- Manejo seguro de información confidencial.

**Acciones clave:** Sesiones presenciales y virtuales → Distribución de guías y materiales de referencia → Evaluaciones periódicas de concienciación.

| Campo | Detalle |
|---|---|
| **Prioridad** | Media |
| **Responsable** | Jefe de Tecnología de la Información |
| **Plazo** | Continuo (inicio en el primer mes) |

---

### Acción 6 — Política de tratamiento de la información

**Contenido:**
- Clasificación y etiquetado de datos según sensibilidad.
- Cifrado obligatorio en tránsito y en reposo.
- Protocolos de eliminación segura de información.

**Acciones clave:** Software de clasificación y etiquetado → Cifrado automático de BBDD y correos → Auditorías de cumplimiento.

| Campo | Detalle |
|---|---|
| **Prioridad** | Media |
| **Responsable** | Administrador de Sistemas Web |
| **Plazo** | 3 meses |

---

### Acción 7 — Mejora en la gestión de incidentes

**Contenido:**
- Detección, registro y respuesta estructurada a incidentes de ciberseguridad.
- Respuesta rápida y efectiva ante emergencias.
- Análisis de incidentes previos (lecciones aprendidas).

**Acciones clave:** Adopción de un SIEM → Creación de equipo de respuesta rápida → Simulacros periódicos de crisis.

| Campo | Detalle |
|---|---|
| **Prioridad** | Alta |
| **Responsable** | Administrador de TI + Comité de Seguridad |
| **Plazo** | 2 meses |

---

### Acción 8 — Revisión y ajuste continuo

**Acciones clave:** Reuniones semanales del Comité de Seguridad → Actualización de políticas y controles tras auditorías e incidentes → Informes de progreso trimestrales.

| Campo | Detalle |
|---|---|
| **Prioridad** | Media |
| **Responsable** | Comité de Seguridad |
| **Frecuencia** | Continua |

---

## 4. ENS (RD 311/2022) vs ISO 27001/27002 — Similitudes y diferencias

### Similitudes

| Aspecto | ENS (RD 311/2022) | ISO 27001/27002 | Aplicación en este PDS |
|---|---|---|---|
| **Ciclo PDCA** | Art. 27 — Mejora continua del proceso de seguridad | Eje central del SGSI | Incluido en "Revisión y Ajuste Continuo" con reuniones periódicas |
| **Política de seguridad** | Cap. III — Política de seguridad obligatoria, alineada con RGPD | Definir política de seguridad como parte del SGSI | Acción prioritaria (Acción 1), con compromiso de Dirección y gestión de riesgos |
| **Gestión de riesgos** | Art. 14 — Identificación, evaluación y tratamiento de riesgos | ISO 27001 Anexo A — Proceso estructurado de riesgos | Tablas de riesgos potenciales y residuales, y Plan de Continuidad TIC |
| **Protección de la información** | Art. 22 — Cifrado obligatorio, especialmente en administración pública | Control 8.24 — Uso de la criptografía | Cifrado en reposo y en tránsito en la Acción 6 |
| **Controles técnicos y organizativos** | Anexo II — IDS, firewalls, planes de formación | Anexo A — Protección perimetral, formación y sensibilización | Implantación de IDS/firewalls (Acción 3) y Plan de Concienciación (Acción 5) |
| **Clasificación de activos** | Anexo II, punto 2 — Identificar, categorizar y proteger activos | Control 5.9 — Inventario de activos por criticidad | Política de tratamiento de información con clasificación y etiquetado (Acción 6) |

### Diferencias

| Aspecto | ENS (RD 311/2022) | ISO 27001/27002 | Aplicación en este PDS |
|---|---|---|---|
| **Enfoque y alcance** | Exclusivo para el **sector público español** y sus proveedores; requisitos obligatorios por niveles de seguridad | Aplicable a **cualquier organización** en cualquier sector o país; mayor flexibilidad | El PDS se centra en el Ayuntamiento (sector público) pero integra flexibilidad de las ISO para priorizar según presupuesto |
| **Cumplimiento normativo** | Obligatorio; directamente vinculado a RGPD, LOPDGDD y leyes españolas | Voluntario; compatible con RGPD pero la certificación es una elección | El ENS es la referencia obligatoria, aunque el PDS adopta principios generalizables de las ISO |
| **Especificidad técnica** | Controles específicos adaptados al entorno público (ej. Art. 12.6.e sobre acceso) | Guía genérica de controles que cada organización adapta | Se alinean controles específicos del ENS con el Anexo A de ISO 27001 |
| **Adaptación al contexto nacional** | Diseñado para el contexto jurídico español; obligatorio para administraciones públicas | No vinculado a ningún contexto legal concreto; aplicable globalmente | Foco principal en el ENS por tratarse de Administración Pública; flexibilidad de las ISO para adaptar controles a la capacidad del Ayuntamiento |
| **Modelo de madurez** | No define un modelo de madurez formal; establece requisitos mínimos por niveles | Permite medir el estado de madurez del SGSI | El PDS usa un modelo de madurez (N0–N5), más alineado con los principios de mejora de las ISO |

### Conclusiones

El **ENS** y las **ISO 27001/27002** comparten principios fundamentales — protección de la información y enfoque basado en riesgos — pero difieren en ámbito y obligatoriedad.

En este PDS se han integrado **ambos enfoques**:

- ✅ La **rigurosidad y obligatoriedad del ENS** garantiza el cumplimiento del marco normativo español.
- ✅ La **flexibilidad y buenas prácticas de las ISO** permiten gestionar la seguridad de forma eficaz y adaptada a los recursos del Ayuntamiento.

Esta combinación hace el PDS más robusto, normativo e internacionalmente alineado.

---

## 5. Bibliografía

- AENOR. (2023). *ISO 27001*. Plataforma AENORMAS. https://plataforma-aenormas-aenor-com.eu1.proxy.openathens.net/standard/UNE/N0071764
- AENOR. (2023). *ISO 27002*. Plataforma AENORMAS. https://plataforma-aenormas-aenor-com.eu1.proxy.openathens.net/standard/UNE/N0071321
- Jefatura del Estado. (2018). *Ley Orgánica de Protección de Datos (LOPD)*. BOE. https://www.boe.es/buscar/pdf/2018/BOE-A-2018-16673-consolidado.pdf
- Jefatura del Estado. (2022). *Esquema Nacional de Seguridad (ENS)*. BOE. https://www.boe.es/buscar/act.php?id=BOE-A-2022-7191
- Parlamento Europeo. (2016). *Reglamento General de Protección de Datos (RGPD)*. BOE. https://www.boe.es/doue/2016/119/L00001-00088.pdf
- Nordpass. (s.f.). *Most Common Passwords List*. https://nordpass.com/es/most-common-passwords-list/
