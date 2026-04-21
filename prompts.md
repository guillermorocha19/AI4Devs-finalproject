> Detalla en esta sección los prompts principales utilizados durante la creación del proyecto, que justifiquen el uso de asistentes de código en todas las fases del ciclo de vida del desarrollo. Esperamos un máximo de 3 por sección, principalmente los de creación inicial o  los de corrección o adición de funcionalidades que consideres más relevantes.
Puedes añadir adicionalmente la conversación completa como link o archivo adjunto si así lo consideras


## Índice

1. [Descripción general del producto](#1-descripción-general-del-producto)
2. [Arquitectura del sistema](#2-arquitectura-del-sistema)
3. [Modelo de datos](#3-modelo-de-datos)
4. [Especificación de la API](#4-especificación-de-la-api)
5. [Historias de usuario](#5-historias-de-usuario)
6. [Tickets de trabajo](#6-tickets-de-trabajo)
7. [Pull requests](#7-pull-requests)

---

## 1. Descripción general del producto

**Prompt 1: Instrucciones iniciales**

> Eres un Product Manager Senior especializado en productos de datos y herramientas de desarrollo. Tu tarea es crear un documento PRD completo y estructurado en formato Markdown para una aplicación web de monitorización del uso de IA por parte de desarrolladores.
>
> ---
>
> ## Contexto del Producto
>
> La aplicación web tiene tres objetivos principales:
> 1. **Potenciar el uso de la IA** entre los desarrolladores del equipo.
> 2. **Obtener KPIs de productividad** derivados del uso de herramientas de IA.
> 3. **Detectar fricciones** en el uso de la IA para mejorar la experiencia.
>
> Toda la información sobre el uso de IA se consultará a través de la **API de LiteLLM**.
>
> ---
>
> ## Tu Rol y Comportamiento
>
> - Actúa como un PM Senior riguroso y metódico.
> - Trabaja **fase a fase**, sin avanzar a la siguiente hasta completar y validar la actual.
> - **Antes de iniciar o finalizar cada fase**, identifica las preguntas clave que necesitas responder y pregúntaselas al usuario de forma clara y concisa.
> - No asumas información que no ha sido proporcionada; prefiere preguntar.
> - Todas tus respuestas y el documento final deben estar en **español**.
>
> ---
>
> ## Fases del PRD
>
> Completa el PRD siguiendo estrictamente este orden de fases:
>
> **Fase 1 — Investigación y Análisis de Mercado**
> Incluye: contexto del sector, análisis de competidores, tendencias relevantes, oportunidades y amenazas.
>
> **Fase 2 — Casos de Uso**
> Incluye: identificación de usuarios (personas), escenarios de uso principales, flujos de usuario y criterios de aceptación.
>
> **Fase 3 — Modelado de Datos**
> Incluye: entidades principales, atributos, relaciones, y diagrama conceptual del modelo de datos.
>
> **Fase 4 — Diseño a Alto Nivel**
> Incluye: arquitectura del sistema, componentes principales, integración con la API de LiteLLM, y decisiones técnicas relevantes.
>
> **Fase 5 — Documento PRD Final**
> Consolida todas las fases anteriores en un único documento PRD estructurado y completo en formato Markdown.
>
> ---
>
> ## Estructura del Documento PRD Final
>
> ```
> # PRD: [Nombre del Producto]
> ## 1. Resumen Ejecutivo
> ## 2. Objetivos del Producto
> ## 3. Investigación y Análisis de Mercado
> ## 4. Usuarios Objetivo y Casos de Uso
> ## 5. Requisitos Funcionales
> ## 6. Requisitos No Funcionales
> ## 7. Modelado de Datos
> ## 8. Diseño a Alto Nivel
> ## 9. KPIs y Métricas de Éxito
> ## 10. Riesgos y Dependencias
> ## 11. Hoja de Ruta (Roadmap)
> ```
>
> ---
>
> ## Instrucciones de Inicio
>
> Antes de comenzar la Fase 1, formula al usuario las preguntas necesarias para obtener el contexto inicial del producto. Como mínimo, considera preguntar sobre: el tamaño y perfil del equipo de desarrolladores, las herramientas de IA que usan actualmente, el entorno técnico existente, restricciones de presupuesto o tiempo, y cualquier restricción regulatoria o de privacidad relevante.

**Prompt 2: Reescritura completa sin matices técnicos**

> Reescribe estas historias quitando cualquier matiz técnico (ejemplo: no mencionames LiteLLM, ni hablamos de Base de Datos). Las historias deben ser 100% funcionales. 0 técnicas. Extiende este comportamiento a todas las historias que hayas escrito. Cuando lo hayas hecho, volvemos a repasar desde donde estamos ahora

**Prompt 3: Actualización de PRD con decisiones tomadas en refinamiento de backlog**

> En el fichero PRD_AI_Monitoring.md adjunto tienes todo el PRD del sistema AI Monitoring. Y en el fichero Backlog.md la construcción del backlog inicial basado en el PRD estructurado en épicas e historias. Durante el refinamiento del backlog se tomaron decisiones que afectan al PRD. Analiza ambos documentos y genera un nuevo fichero PRD modificando sólo y exclusivamente aquellas partes afectadas por el refinamiento. No modifiques ni generes otro backlog. Hazme un resumen con los cambios. Puedes preguntarme lo que necesites para conseguir tu objetivo

---

## 2. Arquitectura del Sistema

### **2.1. Diagrama de arquitectura:**

**Prompt 1:**

**Prompt 2:**

**Prompt 3:**

### **2.2. Descripción de componentes principales:**

**Prompt 1:**

**Prompt 2:**

**Prompt 3:**

### **2.3. Descripción de alto nivel del proyecto y estructura de ficheros**

**Prompt 1:**

**Prompt 2:**

**Prompt 3:**

### **2.4. Infraestructura y despliegue**

**Prompt 1:**

**Prompt 2:**

**Prompt 3:**

### **2.5. Seguridad**

**Prompt 1:**

**Prompt 2:**

**Prompt 3:**

### **2.6. Tests**

**Prompt 1:**

**Prompt 2:**

**Prompt 3:**

---

### 3. Modelo de Datos

**Prompt 1:**

**Prompt 2:**

**Prompt 3:**

---

### 4. Especificación de la API

**Prompt 1:**

**Prompt 2:**

**Prompt 3:**

---

### 5. Historias de Usuario

**Prompt 1:**

**Prompt 2:**

**Prompt 3:**

---

### 6. Tickets de Trabajo

**Prompt 1:**

**Prompt 2:**

**Prompt 3:**

---

### 7. Pull Requests

**Prompt 1:**

**Prompt 2:**

**Prompt 3:**
