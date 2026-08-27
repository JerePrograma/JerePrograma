# Jeremías Rivelli

### Java Backend Developer · Software Engineer

**Java 8/17/21 · Spring Boot · REST APIs · PostgreSQL · Integrations · Legacy Modernization**

Backend developer enfocado en **sistemas de negocio, APIs, integraciones e integridad de datos**.

Trabajo profesionalmente con Java y, en paralelo, desarrollo productos y laboratorios técnicos donde profundizo en **Spring Boot, Kafka, sistemas transaccionales, testing, observabilidad y Generative AI/RAG**.

La prioridad no es acumular tecnologías: es entender el problema, modelar correctamente el dominio, preservar contratos e invariantes y construir soluciones que puedan mantenerse.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Jeremías_Rivelli-0A66C2?logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/rivelli-jeremias/)
[![Portfolio](https://img.shields.io/badge/Portfolio-jereprograma.com-111111?logo=googlechrome\&logoColor=white)](https://jereprograma.com/)
[![GitHub](https://img.shields.io/badge/GitHub-JerePrograma-181717?logo=github\&logoColor=white)](https://github.com/JerePrograma)
[![YouTube](https://img.shields.io/badge/YouTube-JerePrograma-FF0000?logo=youtube\&logoColor=white)](https://www.youtube.com/@JerePrograma)

---

## Sobre mí

Soy desarrollador Java Backend con trayectoria hands-on desde 2023, combinando:

* experiencia profesional en plataformas Java empresariales;
* desarrollo backend con Spring Boot y APIs REST;
* mantenimiento y modernización incremental de sistemas legacy;
* desarrollo independiente de productos end-to-end;
* testing, troubleshooting e integración de sistemas;
* proyectos técnicos con Kafka y arquitecturas event-driven;
* desarrollo aplicado de sistemas GenAI, RAG y agentes.

Actualmente trabajo evolucionando una plataforma Java empresarial basada en **Liferay, Struts, JSP, JDBC y PostgreSQL/PLpgSQL**, interviniendo reglas de negocio, estados, persistencia, transacciones, documentos, correo y reportería, con especial atención a preservar contratos y comportamiento existente.

En proyectos modernos trabajo principalmente con **Java 17/21, Spring Boot, Spring Security, PostgreSQL, Flyway, Docker y testing automatizado**.

También construyo aplicaciones de IA generativa como extensión de sistemas backend: **RAG, embeddings, pgvector, retrieval híbrido, grounding, tool calling y agentic workflows**.

---

## Qué tipo de problemas trabajo

### Backend y sistemas de negocio

* APIs REST y contratos entre sistemas.
* Reglas de negocio y workflows basados en estados.
* Persistencia relacional y límites transaccionales.
* Autenticación y autorización.
* Validación e integridad de datos.
* Idempotencia y deduplicación.
* Integraciones con servicios externos.
* Procesamiento síncrono y asíncrono.
* Testing unitario, integración y E2E.
* Troubleshooting sobre sistemas existentes.

### Legacy y modernización incremental

No todo sistema necesita ser reescrito.

Parte de mi trabajo profesional consiste en comprender aplicaciones Java existentes y evolucionarlas sin romper comportamiento histórico:

* Java legacy;
* Liferay;
* Struts;
* JSP;
* JDBC;
* PL/pgSQL;
* JasperReports;
* Ant;
* Tomcat;
* refactors incrementales;
* preservación de contratos y compatibilidad.

### Sistemas transaccionales e integraciones

En proyectos propios implementé flujos relacionados con:

* OAuth2;
* JWT;
* signed webhooks;
* pagos;
* conciliación;
* idempotencia;
* deduplicación;
* reservas de stock;
* importación de movimientos;
* trazabilidad de operaciones;
* validación de contratos externos.

### Event-driven

Experiencia práctica a nivel de proyectos con:

* Apache Kafka;
* Spring Kafka;
* producers / consumers;
* consumer groups;
* KRaft;
* procesamiento asíncrono;
* idempotencia;
* deduplicación;
* Testcontainers;
* Java 21 Virtual Threads.

### Generative AI / RAG / Agents

La IA es un **diferenciador complementario a mi base backend**, no un reemplazo de ella.

He construido proyectos con:

* LLM APIs;
* OpenRouter;
* Ollama;
* document ingestion;
* chunking;
* embeddings;
* `nomic-embed-text`;
* PostgreSQL + `pgvector`;
* semantic search;
* hybrid retrieval;
* reranking / MMR;
* citations;
* evidence grounding;
* structured outputs;
* SSE streaming;
* tool calling;
* agent loops;
* structured planners;
* session memory;
* iteration limits;
* validation y fallbacks.

---

# Proyectos seleccionados

## Copiloto Tributario

**Generative AI · RAG · OpenRouter · Ollama · PostgreSQL/pgvector · SSE · Docker**

Asistente orientado a responder utilizando información recuperada desde documentación y evidencia disponible.

### Implementación

* Pipeline de ingestión, normalización y chunking de documentos.
* Embeddings locales mediante Ollama y `nomic-embed-text`.
* Persistencia vectorial con PostgreSQL y `pgvector`.
* Recuperación semántica e híbrida.
* Reranking y diversificación mediante MMR.
* Construcción de contexto para generación.
* Citas y validación de evidencia.
* Generación mediante OpenRouter.
* Streaming con Server-Sent Events.
* Tool calling.
* Structured outputs y validación de respuestas.

**Repositorio:**
https://github.com/JerePrograma/copiloto-tributario

---

## Laburen Agent

**LLM Agents · Tool Calling · RAG · PostgreSQL · Streaming · Structured Planning**

Proyecto orientado a automatización mediante agentes capaces de razonar sobre un dominio y ejecutar herramientas reales.

### Implementación

* Loop agéntico:

```text
LLM
 ↓
Planner / decisión estructurada
 ↓
Tool execution
 ↓
Resultado
 ↓
Continuación o respuesta final
```

* Herramientas con lectura y modificación de estado.
* Contratos estructurados para ejecución.
* Memoria y contexto de sesión.
* RAG.
* Límites de iteración.
* Manejo de errores y fallbacks.
* Follow-ups.
* Validación de resultados antes de continuar el flujo.

**Repositorio:**
https://github.com/JerePrograma/laburen-agent

---

## RIU Backend

**Java 21 · Spring Boot · Spring Kafka · Kafka KRaft · PostgreSQL/Oracle · Testcontainers · Docker**

Challenge técnico utilizado como laboratorio de backend orientado a eventos.

### Implementación

* Producer y consumer Kafka.
* Procesamiento asíncrono.
* Controles de idempotencia y deduplicación.
* Kafka ejecutándose con KRaft.
* Persistencia relacional.
* Separación por capas / ports and adapters.
* Integration testing mediante Testcontainers.
* Cobertura automatizada.
* Uso de Virtual Threads de Java 21.

> Kafka forma parte de mi experiencia práctica de proyecto; no lo presento como años de experiencia productiva empresarial.

**Repositorio:**
https://github.com/JerePrograma/RIU-Backend-Jeremias-Rivelli

---

## Shekinah

**React · TypeScript · Cloudflare Pages Functions · D1 · R2 · Mercado Pago · Mercado Libre · Dux · Playwright**

E-commerce con integraciones externas y flujos transaccionales.

### Mercado Pago

* Checkout.
* Webhooks.
* Verificación de firma.
* Validación de referencia externa.
* Validación de importe, moneda y contexto.
* Idempotencia de eventos.
* Conciliación antes de modificar estado del pedido.

### Mercado Libre

* OAuth2.
* Protección mediante `state` de un solo uso.
* Almacenamiento cifrado de tokens.
* Refresh de credenciales.
* Sincronización de catálogo e inventario.
* Webhooks.
* Reconciliación.
* Reservas de stock.

### Calidad

* Migraciones D1.
* Rate limiting.
* Autenticación administrativa.
* Pruebas unitarias.
* Playwright E2E.
* CI mediante GitHub Actions.

**Repositorio:**
https://github.com/JerePrograma/shekinah

---

## Gestudio / CRM Platform

**Java 21 · Spring Boot · PostgreSQL · Flyway · Spring Security · Testcontainers · ArchUnit · Micrometer · Prometheus**

Producto propio de gestión y automatización comercial.

### Backend

* Modelado de dominios de negocio.
* REST APIs.
* Persistencia relacional.
* Autenticación y autorización.
* Migraciones con Flyway.
* Validaciones.
* Procesamiento de workflows administrativos.

### Calidad y observabilidad

* JUnit.
* Mockito.
* Testcontainers.
* ArchUnit.
* Spring Actuator.
* Micrometer.
* Prometheus.
* Quality gates.
* CI automatizado.

**Repositorio:**
https://github.com/JerePrograma/Gestudio

---

## HogarIA

**Java 21 · Spring Boot · PostgreSQL · Flyway · Spring Security/JWT · React · TypeScript · Docker**

Sistema de gestión de finanzas personales orientado a consistencia e importación de movimientos.

### Implementación

* Ingresos y egresos.
* Transferencias.
* Importación de movimientos.
* Normalización.
* Deduplicación persistente.
* Claves de origen.
* Idempotencia.
* Conciliación.
* Reglas de integridad financiera.

**Repositorio:**
https://github.com/JerePrograma/HogarIA

---

<details>
<summary><strong>Otros proyectos</strong></summary>

### cjprestamos

Sistema de gestión de préstamos construido con **Java 21, Spring Boot, PostgreSQL, Flyway, JPA y React/TypeScript**.

Incluye:

* personas;
* préstamos;
* generación de cuotas;
* cronogramas;
* pagos;
* imputación de operaciones;
* archivos;
* trazabilidad.

https://github.com/JerePrograma/cjprestamos

### PresupuestadorFlete

Aplicación full stack para gestión de presupuestos y logística.

**Java 17 · Spring Boot 3.4 · Spring Security/JWT · JPA · MySQL · React/Ionic · TypeScript · Docker**

Incluye separación de DTOs, mappers, servicios, casos de uso y dominio, frontend React/Ionic, OpenAPI, Google Maps y testing automatizado.

https://github.com/JerePrograma/PresupuestadorFlete

</details>

---

# Stack técnico

## Backend

![Java](https://img.shields.io/badge/Java-8%20%7C%2017%20%7C%2021-ED8B00?logo=openjdk\&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?logo=springboot\&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?logo=springsecurity\&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?logo=hibernate\&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?logo=apachemaven\&logoColor=white)

* Java 8 / 17 / 21
* Spring Boot
* Spring Framework
* Spring Web
* Spring Security
* REST APIs
* JPA / Hibernate
* JDBC
* Bean Validation
* Maven
* Ant

## Datos

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql\&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql\&logoColor=white)

* PostgreSQL
* MySQL
* SQL
* PL/pgSQL
* Flyway
* Oracle en proyectos/contextos específicos
* Cloudflare D1
* PostgreSQL `pgvector`

## Testing y calidad

* JUnit
* Mockito
* Spring Test
* MockMvc
* Testcontainers
* JaCoCo
* Vitest
* Testing Library
* Cypress
* Playwright
* ArchUnit

## Infraestructura y delivery

![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker\&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions\&logoColor=white)

* Docker
* Docker Compose
* Nginx
* GitHub Actions
* CI/CD
* Cloudflare Pages
* Cloudflare Pages Functions
* Cloudflare D1 / R2

## Observabilidad

* Spring Actuator
* Micrometer
* Prometheus
* health endpoints
* logs y telemetría de ejecución

## Frontend

![React](https://img.shields.io/badge/React-20232A?logo=react\&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript\&logoColor=white)

* React
* TypeScript
* JavaScript
* Vite
* Axios
* React Router
* Ionic / Capacitor
* Redux Toolkit

---

# Cómo trabajo

Intento que las decisiones técnicas puedan explicarse en términos de **problemas e invariantes**, no solamente de frameworks.

Cuando trabajo sobre un sistema, normalmente presto especial atención a:

1. **Contratos**

   * qué comportamiento existente no debe romperse;
   * qué espera cada consumidor;
   * dónde existen efectos secundarios.

2. **Integridad de datos**

   * estados válidos;
   * transacciones;
   * constraints;
   * idempotencia;
   * deduplicación.

3. **Failure modes**

   * qué ocurre si un servicio externo falla;
   * qué puede reintentarse;
   * qué operaciones necesitan conciliación;
   * qué sucede frente a procesamiento duplicado.

4. **Testing**

   * unit tests para lógica aislada;
   * integration tests cuando importa infraestructura real;
   * E2E para recorridos críticos.

5. **Mantenibilidad**

   * responsabilidades claras;
   * cambios pequeños y verificables;
   * documentación de decisiones relevantes;
   * modernización incremental cuando reescribir no aporta valor.

---

# Experiencia profesional

Actualmente trabajo como **Desarrollador Java en Systemcorp**, evolucionando una plataforma empresarial Java legacy.

Previamente trabajé como backend developer en **iSUR Empresa Consultora** y **1K3**, además de haber desarrollado software de forma independiente y productos full stack.

Mi experiencia combina dos contextos que considero particularmente útiles:

```text
Sistemas existentes
    ↓
Comprender reglas y contratos
    ↓
Modificar con seguridad
    ↓
Preservar compatibilidad
```

y:

```text
Producto nuevo
    ↓
Modelar dominio
    ↓
Diseñar API y persistencia
    ↓
Implementar seguridad e integraciones
    ↓
Testear
    ↓
Desplegar y mantener
```

---

# Educación

### Ingeniería Informática

**Universidad Nacional de Mar del Plata**
2025 — actualidad

### Especialización Back-End Java

**Alura Latam / Oracle Next Education**
2024 — 2025

---

# Idiomas

* **Español:** nativo
* **Inglés:** C1 Advanced — EF SET 70/100, junio de 2026

---

# Actualmente profundizando

Mi foco actual está en seguir aumentando profundidad en:

* diseño de backend Java;
* sistemas distribuidos;
* mensajería y event-driven architectures;
* concurrencia en Java;
* resiliencia;
* observabilidad;
* integration testing;
* evolución de sistemas legacy;
* diseño y evaluación de sistemas RAG/agénticos.

No considero una tecnología parte de mi experiencia fuerte solamente por haberla estudiado: intento incorporarla a proyectos donde pueda **implementarla, probarla y defender las decisiones tomadas**.

---

# Contacto

* **LinkedIn:** [linkedin.com/in/rivelli-jeremias](https://www.linkedin.com/in/rivelli-jeremias/)
* **Portfolio:** [jereprograma.com](https://jereprograma.com/)
* **GitHub:** [github.com/JerePrograma](https://github.com/JerePrograma)
* **YouTube:** [JerePrograma](https://www.youtube.com/@JerePrograma)
* **Email:** [jeremias.j.riv@gmail.com](mailto:jeremias.j.riv@gmail.com)

---

> **Backend Java como base. Integraciones, sistemas transaccionales y GenAI como áreas de profundidad aplicada.**
