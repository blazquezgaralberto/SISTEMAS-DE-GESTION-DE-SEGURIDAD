# 📜 Política de Seguridad y Reglamento — SGSI

## 📋 Índice

1. [Introducción](#1-introducción)
   - 1.1 [Objetivos](#11-objetivos)
   - 1.2 [Caso de estudio](#12-caso-de-estudio)
2. [Reglamento de buenas prácticas](#2-reglamento-de-buenas-prácticas)
   - 2.1 [Introducción](#21-introducción)
   - 2.2 [Alcance](#22-alcance)
   - 2.3 [Uso de recursos de comunicación](#23-uso-de-recursos-de-comunicación)
   - 2.4 [Uso de información y datos](#24-uso-de-información-y-datos)
   - 2.5 [Uso y mantenimiento de equipamiento](#25-uso-y-mantenimiento-de-equipamiento-hardware-y-software)
   - 2.6 [Roles, funciones y responsabilidades](#26-roles-funciones-y-responsabilidades)
   - 2.7 [Marco normativo y regulatorio](#27-marco-normativo-y-regulatorio)
3. [Normativa sobre copias de seguridad y respaldo del CPD](#3-normativa-sobre-copias-de-seguridad-y-respaldo-del-cpd)
   - 3.1 [Objetivo](#31-objetivo)
   - 3.2 [Alcance](#32-alcance)
   - 3.3 [Directrices generales](#33-directrices-generales)
   - 3.4 [Procedimientos operativos](#34-procedimientos-operativos)
   - 3.5 [Roles y responsabilidades](#35-roles-y-responsabilidades)
   - 3.6 [Seguridad física](#36-seguridad-física)
   - 3.7 [Cumplimiento y auditorías](#37-cumplimiento-y-auditorías)
   - 3.8 [Documentación relacionada](#38-documentación-relacionada)
4. [Programa de concienciación y formación](#4-programa-de-concienciación-y-formación-al-personal-y-terceros)
   - 4.1 [Audiencia](#41-audiencia)
   - 4.2 [Contenido](#42-contenido)
   - 4.3 [Metodología y herramientas](#43-metodología-y-herramientas)
   - 4.4 [Frecuencia](#44-frecuencia)
   - 4.5 [Evaluación y medición de la eficacia](#45-evaluación-y-medición-de-la-eficacia)
   - 4.6 [Concienciación continua](#46-concienciación-continua)
5. [Bibliografía](#5-bibliografía)

---

## 1. Introducción

### 1.1 Objetivos

El objetivo de esta actividad es aprender a diseñar políticas y procedimientos dentro de un **SGSI**, elaborando los siguientes documentos sobre una organización de caso de uso:

1. Reglamento de buenas prácticas en el uso de recursos TIC.
2. Normativa específica de copias de seguridad y respaldo del CPD.
3. Programa de concienciación y formación al personal y terceros.

### 1.2 Caso de estudio

La empresa analizada dispone de una **plataforma de alquiler de apartamentos vacacionales** con los siguientes componentes:

| Componente | Descripción |
|---|---|
| **Plataforma web** | Permite a propietarios publicar anuncios y a clientes reservar mediante pasarela de pago |
| **Software de compraventa** | Apoyado en un servidor web y un servidor de bases de datos |
| **Software de correo** | Incluye cliente de correo, boletines y servidor de correo electrónico |
| **Mensajería instantánea** | Canal de comunicación entre inquilinos, propietarios y personal de asistencia |
| **CPD** | Centro de datos en la oficina principal que aloja todos los servidores y equipamiento |
| **Estructura organizativa** | Departamentos de atención al cliente, administración y técnico. Cada empleado dispone de un portátil |

---

## 2. Reglamento de buenas prácticas

### 2.1 Introducción

Este apartado establece las normas y directrices que deben seguir todos los empleados de la organización para garantizar la **seguridad, integridad y eficiencia** en el uso de los recursos TIC.

### 2.2 Alcance

Las disposiciones de este reglamento son aplicables a **todos los empleados** de la empresa en lo que respecta al uso adecuado de los recursos organizativos.

### 2.3 Uso de recursos de comunicación

- Utilizar el correo electrónico y la mensajería instantánea **únicamente para fines laborales**.
- Los gestores de boletines deben asegurar que el contenido esté **alineado con los intereses organizativos**.
- Queda **prohibido** el envío de correos no solicitados (spam).
- Cualquier mensaje sospechoso debe ser **reportado inmediatamente** al equipo técnico y al comité de seguridad.

### 2.4 Uso de información y datos

**Confidencialidad:**
- Prohibida la revelación de información corporativa a personas ajenas a la organización.
- No compartir credenciales de acceso con terceros.
- Toda la información generada por los trabajadores debe almacenarse en **la red corporativa**, nunca en equipos locales.

**Gestión de contraseñas:**

| Requisito | Detalle |
|---|---|
| Longitud mínima | 12 caracteres |
| Complejidad | Al menos: 1 mayúscula, 1 minúscula, 1 número, 1 carácter especial |
| Restricciones | No puede contener el nombre de usuario ni fecha de nacimiento |
| Verificación | Contraste contra base de datos de contraseñas más comunes (Nordpass) |
| Caducidad | Cambio obligatorio cada 3 meses |
| Historial | Prohíbe contraseñas que difieran en menos de 4 caracteres de la anterior |
| Almacenamiento | Prohibido guardar contraseñas de forma escrita o accesible por terceros |

**Cumplimiento legal:**
- Seguir las políticas de protección de datos según **LOPD** y **RGPD**.
- La información de clientes debe tratarse con máxima confidencialidad y usarse solo para los fines descritos en la política de privacidad.
- Al cesar la actividad de un trabajador, eliminar la cuenta corporativa y revocar accesos tras un período prudencial.

### 2.5 Uso y mantenimiento de equipamiento hardware y software

- Prohibido el uso de equipos corporativos para fines personales.
- Seguir el procedimiento del departamento técnico para actualizaciones y mantenimiento.
- Autenticación obligatoria mediante **usuario + contraseña + MFA**.
- Prohibida la instalación de software no autorizado.
- Revisión anual de equipos por el departamento técnico.
- Bloquear la pantalla o llevar el equipo al abandonar el puesto de trabajo.
- Prohibido conectar el equipo a **redes públicas o no fiables**.
- Prohibido conectar dispositivos de almacenamiento externos no validados por el departamento técnico.
- El equipo es **personal e intransferible**.
- La conexión remota a la red corporativa se realizará siempre mediante **VPN**.
- Apagar el equipo al finalizar la jornada laboral.
- Notificar cualquier anomalía al equipo técnico.
- El acceso a servidores y bases de datos está restringido **exclusivamente al departamento técnico**.

### 2.6 Roles, funciones y responsabilidades

| Rol | Responsabilidades | Máximo Responsable |
|---|---|---|
| **Departamento Técnico** | Gestión de versiones, actualizaciones, mantenimiento y gestión de incidencias | CTO |
| **Departamento de Administración** | Uso responsable de los recursos acorde al reglamento interno | COO |
| **Responsable de Ciberseguridad** | Auditoría periódica del reglamento, registro y análisis de anomalías e incidentes | CISO |

### 2.7 Marco normativo y regulatorio

El cumplimiento de las normas está sujeto al siguiente marco legal y normativo:

| Normativa | Descripción |
|---|---|
| **LOPD** (2018) | Ley Orgánica de Protección de Datos — España |
| **RGPD** (2016) | Reglamento General de Protección de Datos — UE |
| **ISO 27001** (2023) | Sistema de Gestión de Seguridad de la Información |
| **ISO 27002** (2023) | Controles de Seguridad de la Información |

Se realizarán **auditorías internas periódicas** por parte del comité de seguridad para asegurar el cumplimiento por parte de todo el personal. El responsable deberá mantenerse actualizado ante posibles cambios normativos.

---

## 3. Normativa sobre copias de seguridad y respaldo del CPD

### 3.1 Objetivo

Establecer directrices y procedimientos para la correcta gestión de las **copias de seguridad y el respaldo del CPD**, garantizando la continuidad del negocio, la recuperación ante incidentes y el cumplimiento normativo.

### 3.2 Alcance

Esta normativa aplica a:

- Todos los **servidores del CPD**: plataforma web de alquiler, software de compraventa, software de correo y boletines, y sistema de mensajería.
- Las **bases de datos** asociadas a dichos sistemas.
- Los **equipos portátiles** de los empleados de los departamentos de atención al cliente, administración y técnico.
- El almacenamiento físico y el respaldo en la nube.

### 3.3 Directrices generales

#### Periodicidad y tipo de respaldo

| Frecuencia | Tipo | Contenido |
|---|---|---|
| **Diaria** | Incremental | Bases de datos transaccionales (reservas, mensajes, pagos) |
| **Semanal** | Diferencial | Sistemas operativos y configuraciones de servidores |
| **Mensual** | Completo | Todos los sistemas y datos |

#### Redundancia de ubicación — Regla 3-2-1

Se mantendrán **al menos 3 copias** en ubicaciones diferentes:

| Copia | Tipo | Ubicación |
|---|---|---|
| 1ª | Almacenamiento físico | CPD de la oficina principal |
| 2ª | Almacenamiento externo | Centro de datos secundario (instalaciones externas) |
| 3ª | Nube | Servicio certificado ISO 27001 |

#### Cifrado y control de acceso

- Todas las copias se cifrarán con **AES-256**.
- Acceso restringido al **personal autorizado del departamento técnico**.
- **MFA obligatorio** para acceder a los sistemas de backup.
- **Registro con firma de certificado electrónico** de toda gestión (quién, cuándo y qué — trazabilidad completa).

#### Política de retención

| Tipo | Retención mínima |
|---|---|
| Diarias | 7 días |
| Semanales | 6 semanas |
| Mensuales | 12 meses |
| Anuales | 5 años (para cumplimiento legal y auditorías) |

### 3.4 Procedimientos operativos

#### PO-001: Creación de copias de seguridad
- **Responsable:** Personal nombrado del departamento técnico.
- **Cometidos:**
  - Programar tareas de respaldo mediante software automatizado (Veeam, Acronis o equivalente).
  - Verificar diariamente la correcta ejecución de las tareas.
  - Registrar todas las operaciones en un registro de auditoría.
- **Periodicidad:** Según directrices del apartado 3.3.

#### PO-002: Almacenamiento de las copias
- **Responsable:** Personal nombrado del departamento técnico.
- **Cometidos:**
  - **Local:** NAS con RAID 6.
  - **Nube:** Servicio con replicación geográfica (AWS S3, Azure Blob Storage o equivalente).
  - **Físico:** Discos externos o cintas LTO en caja fuerte ignífuga dentro del CPD.
- **Periodicidad:** Según directrices del apartado 3.3.

#### PO-003: Pruebas de restauración
- **Responsable:** Responsable de Ciberseguridad.
- **Cometidos:**
  - **Mensual:** Restauración de datos críticos.
  - **Trimestral:** Restauración completa de sistemas críticos.
  - Documentar resultados y resolver los errores detectados.

#### PO-004: Gestión de incidentes
- **Responsable:** Personal nombrado del departamento técnico.
- **Cometidos:**
  - Activar el plan de recuperación a la mayor brevedad posible.
  - Restaurar sistemas desde las copias más recientes disponibles.
  - Informar inmediatamente al Responsable de Ciberseguridad y al Comité de Crisis.

### 3.5 Roles y responsabilidades

| Rol | Responsabilidades |
|---|---|
| **Departamento Técnico** | Gestión, ejecución y monitoreo de backups. Pruebas de restauración. Mantenimiento de hardware y software de respaldo. |
| **Departamento de Administración** | Asegurar los recursos financieros necesarios. Supervisar el cumplimiento de las políticas. |
| **Responsable de Ciberseguridad** | Auditoría periódica de los procesos de backup. Actualización de la normativa ante estándares y riesgos emergentes. |

### 3.6 Seguridad física

1. Acceso a instalaciones restringido con **MFA y control biométrico**.
2. Las copias locales se almacenarán en **cajas fuertes certificadas**.
3. Las ubicaciones secundarias y externas deberán cumplir medidas de seguridad física **equivalentes a las primarias**.

### 3.7 Cumplimiento y auditorías

1. La normativa será **revisada y actualizada anualmente** por el Responsable de Ciberseguridad.
2. Se realizarán **auditorías semestrales** para verificar:
   - Correcta ejecución de las copias de seguridad.
   - Disponibilidad y accesibilidad de los respaldos.
   - Cumplimiento de las políticas definidas.
3. En caso de no conformidades, se comunicará a Dirección con la mayor brevedad, indicando causas y posibles soluciones.

### 3.8 Documentación relacionada

- Políticas de Seguridad de la Información.
- Plan de Recuperación ante Desastres (DRP).
- Plan de Continuidad del Negocio (BCP).

---

## 4. Programa de concienciación y formación al personal y terceros

Un programa de concienciación tiene como finalidad **educar a los colaboradores** en seguridad de la información para que sean capaces de identificar y responder a amenazas.

**Objetivos del programa:**
- Crear conciencia sobre la importancia de proteger la información de clientes y de la empresa.
- Capacitar al personal para identificar y responder a amenazas de seguridad.
- Garantizar que los terceros con acceso a la infraestructura estén alineados con las políticas de seguridad.

### 4.1 Audiencia

La formación se adaptará según el perfil de cada grupo:

| Audiencia | Tipo de formación |
|---|---|
| **Personal técnico** (desarrolladores, técnicos de sistemas) | Formación avanzada: seguridad de sistemas, bases de datos, programación segura, infraestructuras TI. Posibilidad de formación externa pagada. |
| **Personal administrativo y atención al cliente** | Amenazas comunes (phishing), protección de datos, uso seguro de herramientas y dispositivos corporativos. |
| **Terceros** (proveedores y contratistas) | Cumplimiento de políticas internas, manejo de información confidencial, uso de plataformas de acceso remoto seguras. |

### 4.2 Contenido

#### 4.2.1 Fundamentos de ciberseguridad

- **Gestión de contraseñas seguras:** Creación de contraseñas robustas, implementación de MFA y gestión de accesos.
- **Protección de datos personales y confidenciales:** Principios RGPD, clasificación y manejo adecuado de la información.
- **Reconocimiento de ciberataques:** Identificación de phishing, ransomware, malware y otros ataques comunes.
- **Ingeniería social:** Tácticas psicológicas de los atacantes y cómo evitar ser víctima.

#### 4.2.2 Uso seguro de herramientas y dispositivos

- **Correo electrónico y mensajería:** Gestión segura de comunicaciones y prevención de phishing.
- **Dispositivos móviles y portátiles:** Cifrado, protección ante robo o pérdida y buenas prácticas de uso.
- **Plataformas de pago:** Protección de datos financieros y uso de protocolos seguros en transacciones.

#### 4.2.3 Manejo de incidentes de seguridad

- **Detección y notificación:** Identificar señales de posibles brechas de seguridad y seguir los pasos de notificación.
- **Procedimientos de respuesta:** Guías de actuación ante los distintos tipos de incidentes trabajados.

#### 4.2.4 Formación específica para terceros y proveedores

- **Acceso remoto seguro:** Uso de VPNs, herramientas de acceso remoto y principio de acceso mínimo necesario.
- **Alineación con políticas internas:** Formación sobre los procedimientos de la empresa que los terceros deben cumplir.

### 4.3 Metodología y herramientas

| Metodología | Descripción |
|---|---|
| **Módulos e-learning** | Aprendizaje interactivo a ritmo propio, con distintos niveles de exigencia y evaluaciones periódicas |
| **Simulaciones de ataques** | Simulaciones controladas de phishing o ingeniería social para medir la respuesta real del personal |
| **Talleres prácticos** | Sesiones presenciales o virtuales con actividades interactivas para aplicar los conocimientos |
| **Juegos de rol** | Escenarios de crisis reales de la empresa para practicar respuestas coordinadas |
| **Newsletters** | Boletines periódicos con nuevas amenazas, incidentes resueltos y recomendaciones |

### 4.4 Frecuencia

| Momento | Acción formativa |
|---|---|
| **Incorporación** | Módulos iniciales de concienciación obligatorios para todo empleado y tercero |
| **Cada 3-6 meses** | Revisiones periódicas para el personal o ante cambios significativos en la empresa |
| **Ante nuevas amenazas** | Sesiones específicas sobre nuevos riesgos o vulnerabilidades identificadas |

### 4.5 Evaluación y medición de la eficacia

| Mecanismo | Descripción |
|---|---|
| **Cuestionarios y evaluaciones** | Miden el nivel de comprensión y la satisfacción con el contenido y nivel impartido |
| **Simulaciones de phishing** | Correos simulados de ataque para evaluar la respuesta real; los resultados ajustan el programa |
| **Revisión de incidentes** | Análisis de los incidentes notificados para identificar áreas que requieren mayor formación |

> ✅ El programa se considerará **exitoso** cuando el trabajador haya adquirido las competencias que previamente no tenía y se cumplan los objetivos pactados.

### 4.6 Concienciación continua

Más allá de la formación estructurada, se implementará un programa de concienciación continua que incluirá:

- **Campañas de concienciación:** Pósters, flyers y comunicaciones por correo electrónico distribuidos en puntos físicos y digitales de la empresa como recordatorio de buenas prácticas.
- **Concursos y recompensas:** Incentivos para fomentar la participación activa y reconocer el desempeño destacado en materia de seguridad.

---

## 5. Bibliografía

- AENOR. (2023). *ISO 27001*. Plataforma AENORMAS. https://plataforma-aenormas-aenor-com.eu1.proxy.openathens.net/standard/UNE/N0071764
- AENOR. (2023). *ISO 27002*. Plataforma AENORMAS. https://plataforma-aenormas-aenor-com.eu1.proxy.openathens.net/standard/UNE/N0071321
- Jefatura del Estado. (2018). *Ley Orgánica de Protección de Datos (LOPD)*. BOE. https://www.boe.es/buscar/pdf/2018/BOE-A-2018-16673-consolidado.pdf
- Parlamento Europeo. (2016). *Reglamento General de Protección de Datos (RGPD)*. BOE. https://www.boe.es/doue/2016/119/L00001-00088.pdf
- Nordpass. (s.f.). *Most Common Passwords List*. https://nordpass.com/es/most-common-passwords-list/
