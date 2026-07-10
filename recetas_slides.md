# Recetas de slides · Nivel 11 (2º de Preparatoria) · Ciclo 2026-2027

Una receta por sesión. Cada diapositiva corresponde a un bloque del Playbook: kickoff y showcase llevan 4; tronco y taller llevan 5.
Uso: copia el bloque de código de la sesión y pégalo en Gamma junto con la instrucción de estilo.

Instrucción de estilo de la etapa (prepa):

> Visual Style: "Professional Minimal. Large fonts, high contrast, clean backgrounds, no decorative elements. Format: Visual support for live class." Audience & Tone: "Target Audience: Young adults 15-18. Tone: Professional, industry-grade, zero gamification, no exclamation marks. Spanish (Mexico)."

## Índice

- [E1S1 · Kickoff · Expedición 1 (4 diapositivas)](#e1s1)
- [E1S2 · Tronco · Anatomía de un Agente (5 diapositivas)](#e1s2)
- [E1S3 · Tronco · Herramientas para Agentes (5 diapositivas)](#e1s3)
- [E1S4 · Tronco · Construir un MVP (5 diapositivas)](#e1s4)
- [E1S5 · Taller de ramas · el toque del proyecto (5 diapositivas)](#e1s5)
- [E1S6 · Pulido + Showcase 1 (4 diapositivas)](#e1s6)
- [E2S1 · Kickoff · Expedición 2 (4 diapositivas)](#e2s1)
- [E2S2 · Tronco · Director de Intención (5 diapositivas)](#e2s2)
- [E2S3 · Tronco · Auditor de Confianza (5 diapositivas)](#e2s3)
- [E2S4 · Taller de ramas (5 diapositivas)](#e2s4)
- [E2S5 · Taller de ramas · el toque del proyecto (5 diapositivas)](#e2s5)
- [E2S6 · Pulido + Showcase 2 (4 diapositivas)](#e2s6)
- [E3S1 · Kickoff · Expedición 3 (4 diapositivas)](#e3s1)
- [E3S2 · Taller de ramas (5 diapositivas)](#e3s2)
- [E3S3 · Taller de ramas (5 diapositivas)](#e3s3)
- [E3S4 · Taller de ramas (5 diapositivas)](#e3s4)
- [E3S5 · Taller de ramas · el toque del proyecto (5 diapositivas)](#e3s5)
- [E3S6 · Pulido + Showcase 3 (4 diapositivas)](#e3s6)

---

<a id="e1s1"></a>
## E1S1 · Kickoff · Expedición 1

Playbook fuente: https://gnius-club.github.io/T4G_H2_PB/e1s1/

```
[Intention: Abrir la Expedicion con la consigna y el encuadre inspirador.]
[Layout Strategy: Hero]
### Inspiración y encuadre
# Kickoff · Expedición 1
## Inspiración, onboarding y bautizo del proyecto

*   Arranca el primer proyecto del año: hoy eliges un problema real que te importe.
*   Los proyectos que verás son alcanzables: fueron construidos por equipos como el tuyo.

[IMAGE: An inspiring gallery wall of real student-built tech projects, photos pinned like a mission-control board without any text overload. Perspective: Isometric. Lighting: Bright neutral studio. Context: Minimal professional educational workspace. Emotion: Focus and clarity. All labels in Spanish.]

---

[Intention: La entrevista es de Xolo; una pregunta por turno.]
### Entrevista con Xolo

*   Xolo conduce con una pregunta por turno.
*   El problema queda confirmado en tus palabras antes de avanzar.
*   Responde con calma: no hay respuestas incorrectas, hay contexto.

---

[Intention: Bautizo del proyecto y presentacion de ramas desbloqueadas.]
### Bautizo y pre-elección de ramas

*   Nombra tu proyecto: nombre y apellido de producto.

Ramas desbloqueadas en esta Expedición:

*   **Proto-Agente:** "Tu primer agente no necesita código: necesita un propósito y una herramienta."
*   **Razonamiento ReAct:** "Antes de programar el bucle, apréndete el paso: pensar, actuar, observar."
*   **Hipótesis Clave:** "Toda idea esconde una apuesta. Encuéntrala antes de que te cueste el año."

---

[Intention: Cierre formal del kickoff con los proyectos bautizados.]
### Cierre del kickoff

*   Cada proyecto se presenta por su nombre frente al grupo.
*   La Expedición 1 queda oficialmente iniciada.
*   Xolo deja el arranque escrito en proyecto.md.

[IMAGE: A clean roster board showing freshly named student projects, each with a name tag, group standing ready. Perspective: Isometric. Lighting: Bright neutral studio. Context: Minimal professional educational workspace. Emotion: Focus and clarity. All labels in Spanish.]
```

---

<a id="e1s2"></a>
## E1S2 · Tronco · Anatomía de un Agente

Playbook fuente: https://gnius-club.github.io/T4G_H2_PB/e1s2/

```
[Intention: Abrir la sesion con el objetivo y el arranque autonomo con Xolo.]
[Layout Strategy: Hero]
### Encendido
# Anatomía de un Agente
## Un chatbot conversa; un agente actúa. La diferencia son tres piezas.

*   **Objetivo:** Entender y armar un agente de IA — LLM + herramientas + memoria — y convertir un chatbot que responde en un actor que ejecuta tareas con un propósito claro.
*   **Arranque:** Accede a Gnius Space e inicia con Xolo; retoma tu proyecto desde la última línea de memoria.
*   **Skill Card de hoy:** `Anatomía de un Agente`
*   **Herramientas:** Laptop / navegador + Custom GPTs

[IMAGE: A student workspace with a learning platform open, showing a skill card highlighted and a chat with an AI tutor resuming a project. Perspective: Isometric. Lighting: Bright neutral studio. Context: Minimal professional educational workspace. Emotion: Focus and clarity. All labels in Spanish.]

---

[Intention: Anclar el concepto clave; el grupo observa la demo en vivo del Mentor.]
### Demo

*   **Concepto ancla:** Un chatbot es una recepcionista que solo contesta el teléfono: sabe mucho, pero no se levanta del escritorio. Un agente es un asistente con llaves de la oficina: escucha la petición, decide qué hacer, usa las herramientas del edificio y anota lo que hizo para la próxima vez.
*   **Observa:** el Mentor de Cancha construye en vivo. Detecta el error a propósito y piensa qué falta antes de que lo corrija.

---

[Intention: Practica guiada con niveles de reto diferenciados.]
### Manos a la obra

Avanza la lección con Xolo: explicación corta, práctica, retroalimentación.

1.  **Newbie:** Identifico las tres piezas en un agente que me muestran y explico qué hace cada una.
2.  **Guru:** Convierto un chatbot en actor: le defino propósito, una herramienta y qué registra en memoria.
3.  **Wizard:** Diseño en papel un agente completo para una tarea real de mi proyecto, con el recorrido de la tarea trazado de punta a punta.

**Demuestra que lo tienes:** Explica con tus palabras las tres piezas de un agente y da un ejemplo concreto de qué pasa si falta cada una.

---

[Intention: Captura de evidencia y cierre persistido.]
### Registro

*   **Evidencia:** Diagrama de la anatomía del agente del equipo: las tres piezas etiquetadas, el propósito en una frase y el recorrido de una tarea real trazado con flechas.
*   **Cierre:** Registra tu avance en Gnius Space; Xolo confirma y tu logro queda escrito en proyecto.md.

---

[Intention: Reflexion critica e intercambio entre pares.]
### Brújula

*   **Piensa (30 seg):** Si un agente puede actuar sin pedirte permiso a cada paso, ¿qué tareas de tu semana le confiarías completas y cuáles jamás? ¿Qué dice ese límite sobre lo que valoras?
*   **En pareja (2 min):** comparte tu respuesta y muestra tu avance.
*   **Al grupo (2 min):** conclusiones y cierre del Mentor de Cancha.

[IMAGE: Two students discussing at a clean desk while a class board shows a single open question, sober and thoughtful scene. Perspective: Isometric. Lighting: Bright neutral studio. Context: Minimal professional educational workspace. Emotion: Focus and clarity. All labels in Spanish.]
```

---

<a id="e1s3"></a>
## E1S3 · Tronco · Herramientas para Agentes

Playbook fuente: https://gnius-club.github.io/T4G_H2_PB/e1s3/

```
[Intention: Abrir la sesion con el objetivo y el arranque autonomo con Xolo.]
[Layout Strategy: Hero]
### Encendido
# Herramientas para Agentes
## Tu agente tiene cerebro. Esta es la parte donde le das manos.

*   **Objetivo:** Escribir funciones simples en Python y definir su esquema JSON (function calling) para que el LLM pueda usarlas — entendiendo que diseñar buenas herramientas es ingeniería de contexto.
*   **Arranque:** Accede a Gnius Space e inicia con Xolo; retoma tu proyecto desde la última línea de memoria.
*   **Skill Card de hoy:** `Herramientas para Agentes`
*   **Herramientas:** Laptop / navegador + Python · JSON

[IMAGE: A student workspace with a learning platform open, showing a skill card highlighted and a chat with an AI tutor resuming a project. Perspective: Isometric. Lighting: Bright neutral studio. Context: Minimal professional educational workspace. Emotion: Focus and clarity. All labels in Spanish.]

---

[Intention: Anclar el concepto clave; el grupo observa la demo en vivo del Mentor.]
### Demo

*   **Concepto ancla:** El esquema JSON es la etiqueta de una caja de herramientas cerrada: el LLM no ve el interior (tu código), solo lee la etiqueta. Si la etiqueta dice 'martillo' pero adentro hay un desarmador, o si dice 'herramienta multiusos' sin más, el agente elegirá mal — y la culpa no es del agente.
*   **Observa:** el Mentor de Cancha construye en vivo. Detecta el error a propósito y piensa qué falta antes de que lo corrija.

---

[Intention: Practica guiada con niveles de reto diferenciados.]
### Manos a la obra

Avanza la lección con Xolo: explicación corta, práctica, retroalimentación.

1.  **Newbie:** Escribo una función simple en Python y su esquema JSON con ayuda de la guía de Xolo.
2.  **Guru:** Diseño el esquema para que el agente elija bien mi herramienta entre varias disponibles.
3.  **Wizard:** Conecto dos o más herramientas a un agente y depuro una llamada incorrecta ajustando solo el esquema.

**Demuestra que lo tienes:** Explica por qué la descripción del esquema JSON es más importante para el agente que el código de la función, y qué pasa cuando la descripción es vaga.

---

[Intention: Captura de evidencia y cierre persistido.]
### Registro

*   **Evidencia:** Captura de la función en Python junto a su esquema JSON, más una llamada real del agente donde se ve qué argumentos eligió — con una nota de qué ajuste del esquema destrabó el comportamiento.
*   **Cierre:** Registra tu avance en Gnius Space; Xolo confirma y tu logro queda escrito en proyecto.md.

---

[Intention: Reflexion critica e intercambio entre pares.]
### Brújula

*   **Piensa (30 seg):** El LLM elige herramientas leyendo descripciones escritas por humanos. Si el poder de un agente depende de qué tan bien escribes, ¿la programación se volvió también un oficio de redacción?
*   **En pareja (2 min):** comparte tu respuesta y muestra tu avance.
*   **Al grupo (2 min):** conclusiones y cierre del Mentor de Cancha.

[IMAGE: Two students discussing at a clean desk while a class board shows a single open question, sober and thoughtful scene. Perspective: Isometric. Lighting: Bright neutral studio. Context: Minimal professional educational workspace. Emotion: Focus and clarity. All labels in Spanish.]
```

---

<a id="e1s4"></a>
## E1S4 · Tronco · Construir un MVP

Playbook fuente: https://gnius-club.github.io/T4G_H2_PB/e1s4/

```
[Intention: Abrir la sesion con el objetivo y el arranque autonomo con Xolo.]
[Layout Strategy: Hero]
### Encendido
# Construir un MVP
## No construyas el producto: construye el experimento que prueba si vale la pena.

*   **Objetivo:** Levantar la primera versión usable de la solución (MVP) con el agente como motor, definir la hipótesis clave y ponerla a prueba con feedback real.
*   **Arranque:** Accede a Gnius Space e inicia con Xolo; retoma tu proyecto desde la última línea de memoria.
*   **Skill Card de hoy:** `Construir un MVP`
*   **Herramientas:** Laptop / navegador + Lovable

[IMAGE: A student workspace with a learning platform open, showing a skill card highlighted and a chat with an AI tutor resuming a project. Perspective: Isometric. Lighting: Bright neutral studio. Context: Minimal professional educational workspace. Emotion: Focus and clarity. All labels in Spanish.]

---

[Intention: Anclar el concepto clave; el grupo observa la demo en vivo del Mentor.]
### Demo

*   **Concepto ancla:** Un MVP es el probador de una tienda de ropa, no la tienda: existe para que el cliente se pruebe UNA prenda y decidas si fabricarla en serio. Construir login y página de inicio antes de validar es decorar los aparadores de una tienda que quizá nunca abra.
*   **Observa:** el Mentor de Cancha construye en vivo. Detecta el error a propósito y piensa qué falta antes de que lo corrija.

---

[Intention: Practica guiada con niveles de reto diferenciados.]
### Manos a la obra

Avanza la lección con Xolo: explicación corta, práctica, retroalimentación.

1.  **Newbie:** Construyo en Lovable el camino que prueba mi hipótesis, aunque parte del resultado sea manual.
2.  **Guru:** Pongo el MVP frente a usuarios reales y mido la métrica de mi hipótesis clave.
3.  **Wizard:** Decido con evidencia entre iterar, ajustar hipótesis o pivotar, y ejecuto la decisión en el MVP.

**Demuestra que lo tienes:** Explica qué es lo único que un MVP debe contener y por qué construir de más antes de validar es el error más caro.

---

[Intention: Captura de evidencia y cierre persistido.]
### Registro

*   **Evidencia:** Enlace al MVP en Lovable junto a la hipótesis clave escrita y la tabla de resultados: cuántos usuarios probaron, cuántos completaron la acción clave y qué decisión tomó el equipo.
*   **Cierre:** Registra tu avance en Gnius Space; Xolo confirma y tu logro queda escrito en proyecto.md.

---

[Intention: Reflexion critica e intercambio entre pares.]
### Brújula

*   **Piensa (30 seg):** Si la primera versión de tu producto te da orgullo, probablemente la lanzaste tarde. ¿Qué es más valioso: seis meses puliendo en secreto o seis días aprendiendo en público?
*   **En pareja (2 min):** comparte tu respuesta y muestra tu avance.
*   **Al grupo (2 min):** conclusiones y cierre del Mentor de Cancha.

[IMAGE: Two students discussing at a clean desk while a class board shows a single open question, sober and thoughtful scene. Perspective: Isometric. Lighting: Bright neutral studio. Context: Minimal professional educational workspace. Emotion: Focus and clarity. All labels in Spanish.]
```

---

<a id="e1s5"></a>
## E1S5 · Taller de ramas · el toque del proyecto

Playbook fuente: https://gnius-club.github.io/T4G_H2_PB/e1s5/

```
[Intention: Abrir el taller con el objetivo y el arranque autonomo con Xolo.]
[Layout Strategy: Hero]
### Encendido
# Taller de ramas · el toque del proyecto
## Catálogo abierto · elige tu rama

*   **Objetivo:** avanzar la lección de tu rama e integrarla a tu proyecto en esta misma sesión.
*   **Arranque:** Accede a Gnius Space e inicia con Xolo; retoma tu proyecto desde la última línea de memoria.
*   **Skill Card de hoy:** la de tu rama.

[IMAGE: A branching catalog of project skill cards fanned out on a screen, each card with a distinct icon, student choosing one. Perspective: Isometric. Lighting: Bright neutral studio. Context: Minimal professional educational workspace. Emotion: Focus and clarity. All labels in Spanish.]

---

[Intention: El Mentor abre el abanico del catalogo; cada gancho es textual.]
### Demo

El abanico del catálogo abierto en esta Expedición:

*   **Proto-Agente:** "Tu primer agente no necesita código: necesita un propósito y una herramienta."
*   **Razonamiento ReAct:** "Antes de programar el bucle, apréndete el paso: pensar, actuar, observar."
*   **Hipótesis Clave:** "Toda idea esconde una apuesta. Encuéntrala antes de que te cueste el año."

---

[Intention: Practica de taller con estandar de peticiones con contexto.]
### Manos a la obra

*   Avanza la lección de tu rama con Xolo: explicación, práctica, retroalimentación.
*   Pide con las tres piezas: qué quiero, qué intenté, qué pasó.
*   Puedes pedir trabajar directamente en tu proyecto en cualquier momento.

---

[Intention: Captura de evidencia y cierre persistido.]
### Registro

*   **Evidencia de tu rama:** foto o video corto del sistema operando, con el nombre del proyecto visible.
*   **Cierre:** Registra tu avance en Gnius Space; Xolo confirma y el avance queda escrito en proyecto.md.

---

[Intention: Reflexion critica e intercambio entre pares.]
### Brújula

*   **Piensa (30 seg):** Cada equipo tomó una ruta distinta y todos avanzaron. ¿Qué observaste en la solución de otro equipo que reformula tu propio enfoque?
*   **En pareja (2 min):** comparte tu respuesta y muestra tu avance.
*   **Al grupo (2 min):** conclusiones y cierre del Mentor de Cancha.

[IMAGE: Different student teams working on visibly different projects side by side, sharing observations at a clean board. Perspective: Isometric. Lighting: Bright neutral studio. Context: Minimal professional educational workspace. Emotion: Focus and clarity. All labels in Spanish.]
```

---

<a id="e1s6"></a>
## E1S6 · Pulido + Showcase 1

Playbook fuente: https://gnius-club.github.io/T4G_H2_PB/e1s6/

```
[Intention: Preparar el cierre publico: repaso y ensayo.]
[Layout Strategy: Hero]
### Repaso y ensayo del pitch
# Pulido + Showcase 1
## Cierre público de la Expedición 1

*   **Consigna:** Repaso del glosario vivido, guion del pitch, demo pública y archivo de la Expedición
*   Repasa el glosario vivido: los términos que tu equipo usó de verdad este trimestre.

[IMAGE: A rehearsal scene: student team practicing a short pitch in front of a simple timer and a projector, calm and professional. Perspective: Isometric. Lighting: Bright neutral studio. Context: Minimal professional educational workspace. Emotion: Focus and clarity. All labels in Spanish.]

---

[Intention: La estructura del pitch, elemento por elemento.]
### Presentaciones

Estructura del pitch:

1.  **El problema:** Qué problema atienden y su relevancia.
2.  **La demo:** La solución operando en vivo.
3.  **Lo que aprendimos:** Una capacidad dominada y un obstáculo superado.
4.  **El moonshot:** La proyección de la solución.

---

[Intention: Los reconocimientos del trimestre y su criterio.]
### Trofeos del trimestre

*   **Ejecución Más Sólida:** La implementación técnica más consistente del periodo.
*   **Sistema Más Confiable:** La mejor validación: prueba sistemática, datos y decisión fundamentada.
*   **Mejor Presentación:** La exposición que mejor articuló problema, solución y aprendizaje.

Los nombres de los trofeos están en validación con el equipo creativo.

---

[Intention: Ceremonia de archivo; la historia se congela, nada se borra.]
### Archivo de la Expedición

*   La historia de tu proyecto se congela tal como quedó — nada se borra.
*   El archivo es ceremonia: el grupo despide la Expedición con su proyecto completo.
*   Tras el archivo viene el kickoff de la Expedición 2.

[IMAGE: A project timeline being sealed into a clean digital archive drawer, sober interface, sense of completion without celebration props. Perspective: Isometric. Lighting: Bright neutral studio. Context: Minimal professional educational workspace. Emotion: Focus and clarity. All labels in Spanish.]
```

---

<a id="e2s1"></a>
## E2S1 · Kickoff · Expedición 2

Playbook fuente: https://gnius-club.github.io/T4G_H2_PB/e2s1/

```
[Intention: Abrir la Expedicion con la consigna y el encuadre inspirador.]
[Layout Strategy: Hero]
### Inspiración y encuadre
# Kickoff · Expedición 2
## Desbloqueo de nuevas ramas y decisión: evolucionar o replantear el proyecto

*   Tu proyecto anterior quedó archivado como historia. Hoy decides: evolucionarlo o replantear desde cero — ambas rutas valen.
*   Los proyectos que verás son alcanzables: fueron construidos por equipos como el tuyo.

[IMAGE: An inspiring gallery wall of real student-built tech projects, photos pinned like a mission-control board without any text overload. Perspective: Isometric. Lighting: Bright neutral studio. Context: Minimal professional educational workspace. Emotion: Focus and clarity. All labels in Spanish.]

---

[Intention: La entrevista es de Xolo; una pregunta por turno.]
### Entrevista con Xolo

*   Xolo conduce con una pregunta por turno.
*   Xolo conduce la decisión (evolucionar o replantear) y el re-bautizo.
*   Responde con calma: no hay respuestas incorrectas, hay contexto.

---

[Intention: Bautizo del proyecto y presentacion de ramas desbloqueadas.]
### Bautizo y pre-elección de ramas

*   Nombra tu proyecto: nombre y apellido de producto.

Ramas desbloqueadas en esta Expedición:

*   **Orquestador en Python:** "El bucle deja el papel: ahora es un script que corre de verdad."
*   **Memoria del Agente:** "Un agente sin memoria hace la misma tarea por primera vez, todos los días."
*   **Datos vía API:** "Tu agente ya razona. Ahora hay que alimentarlo con datos frescos del mundo."
*   **Automatización Inteligente:** "Los flujos en línea recta se acabaron: aquí los caminos se bifurcan."

---

[Intention: Cierre formal del kickoff con los proyectos bautizados.]
### Cierre del kickoff

*   Cada proyecto se presenta por su nombre frente al grupo.
*   La Expedición 2 queda oficialmente iniciada.
*   Xolo deja el arranque escrito en proyecto.md.

[IMAGE: A clean roster board showing freshly named student projects, each with a name tag, group standing ready. Perspective: Isometric. Lighting: Bright neutral studio. Context: Minimal professional educational workspace. Emotion: Focus and clarity. All labels in Spanish.]
```

---

<a id="e2s2"></a>
## E2S2 · Tronco · Director de Intención

Playbook fuente: https://gnius-club.github.io/T4G_H2_PB/e2s2/

```
[Intention: Abrir la sesion con el objetivo y el arranque autonomo con Xolo.]
[Layout Strategy: Hero]
### Encendido
# Director de Intención
## Dirigir un agente es decidir qué sabe, qué puede tocar y cómo razona.

*   **Objetivo:** Aplicar ingeniería de contexto a agentes: diseñar qué información, herramientas y memoria recibe el agente y su flujo de razonamiento (patrón ReAct), orquestado con Python.
*   **Arranque:** Accede a Gnius Space e inicia con Xolo; retoma tu proyecto desde la última línea de memoria.
*   **Skill Card de hoy:** `Director de Intención`
*   **Herramientas:** Laptop / navegador + ReAct · Python

[IMAGE: A student workspace with a learning platform open, showing a skill card highlighted and a chat with an AI tutor resuming a project. Perspective: Isometric. Lighting: Bright neutral studio. Context: Minimal professional educational workspace. Emotion: Focus and clarity. All labels in Spanish.]

---

[Intention: Anclar el concepto clave; el grupo observa la demo en vivo del Mentor.]
### Demo

*   **Concepto ancla:** El director técnico de un equipo no juega el partido: decide la alineación (herramientas), da la información del rival (contexto), define la estrategia (flujo de razonamiento) y ve el partido para ajustar. Si el equipo pierde, el director no grita 'jueguen mejor' — cambia alineación, información o estrategia.
*   **Observa:** el Mentor de Cancha construye en vivo. Detecta el error a propósito y piensa qué falta antes de que lo corrija.

---

[Intention: Practica guiada con niveles de reto diferenciados.]
### Manos a la obra

Avanza la lección con Xolo: explicación corta, práctica, retroalimentación.

1.  **Newbie:** Sigo una corrida ReAct real e identifico cada fase: razonar, actuar, observar.
2.  **Guru:** Diseño el paquete completo de un agente — información, herramientas, memoria — y su bucle en pseudocódigo.
3.  **Wizard:** Orquesto el agente en Python de punta a punta y depuro una corrida fallida encontrando el paso exacto de la desviación.

**Demuestra que lo tienes:** Describe el patrón ReAct con tus palabras y explica por qué darle a un agente más herramientas y más contexto puede empeorar su desempeño.

---

[Intention: Captura de evidencia y cierre persistido.]
### Registro

*   **Evidencia:** Captura del pseudocódigo del bucle junto al script de orquestación en Python y una corrida real anotada: en qué paso razonó, qué herramienta invocó y dónde estuvo el ajuste decisivo.
*   **Cierre:** Registra tu avance en Gnius Space; Xolo confirma y tu logro queda escrito en proyecto.md.

---

[Intention: Reflexion critica e intercambio entre pares.]
### Brújula

*   **Piensa (30 seg):** Un agente hereda tus decisiones de diseño: sabe lo que elegiste contarle y puede tocar lo que elegiste darle. ¿Qué revelan tus elecciones de contexto sobre cómo entiendes el problema?
*   **En pareja (2 min):** comparte tu respuesta y muestra tu avance.
*   **Al grupo (2 min):** conclusiones y cierre del Mentor de Cancha.

[IMAGE: Two students discussing at a clean desk while a class board shows a single open question, sober and thoughtful scene. Perspective: Isometric. Lighting: Bright neutral studio. Context: Minimal professional educational workspace. Emotion: Focus and clarity. All labels in Spanish.]
```

---

<a id="e2s3"></a>
## E2S3 · Tronco · Auditor de Confianza

Playbook fuente: https://gnius-club.github.io/T4G_H2_PB/e2s3/

```
[Intention: Abrir la sesion con el objetivo y el arranque autonomo con Xolo.]
[Layout Strategy: Hero]
### Encendido
# Auditor de Confianza
## Tu agente puede actuar. Ahora la pregunta seria: ¿qué le impides hacer?

*   **Objetivo:** Hacer agentes robustos y seguros: detectar prompt injection, diseñar guardrails, colocar puntos de control humano (HITL) y aplicar privacidad por diseño.
*   **Arranque:** Accede a Gnius Space e inicia con Xolo; retoma tu proyecto desde la última línea de memoria.
*   **Skill Card de hoy:** `Auditor de Confianza`
*   **Herramientas:** Laptop / navegador + Guardrails · HITL

[IMAGE: A student workspace with a learning platform open, showing a skill card highlighted and a chat with an AI tutor resuming a project. Perspective: Isometric. Lighting: Bright neutral studio. Context: Minimal professional educational workspace. Emotion: Focus and clarity. All labels in Spanish.]

---

[Intention: Anclar el concepto clave; el grupo observa la demo en vivo del Mentor.]
### Demo

*   **Concepto ancla:** Un banco no confía en la honestidad del cajero: pone una bóveda con dos llaves, cámaras y montos que requieren firma del gerente. Los guardrails son la bóveda, el HITL es la firma del gerente y la privacidad por diseño es que el cajero de ventanilla no tenga la llave de las cajas fuertes.
*   **Observa:** el Mentor de Cancha construye en vivo. Detecta el error a propósito y piensa qué falta antes de que lo corrija.

---

[Intention: Practica guiada con niveles de reto diferenciados.]
### Manos a la obra

Avanza la lección con Xolo: explicación corta, práctica, retroalimentación.

1.  **Newbie:** Identifico en un agente dado un riesgo concreto y propongo el guardrail que lo cierra.
2.  **Guru:** Diseño guardrails y un punto de control humano para las acciones irreversibles de mi agente.
3.  **Wizard:** Ejecuto una prueba de inyección contra mi propio agente y documento qué resistió, qué falló y qué ajusté.

**Demuestra que lo tienes:** Explica la diferencia entre pedirle a un agente que se porte bien y ponerle un guardrail, y da un ejemplo de acción que siempre exige control humano.

---

[Intention: Captura de evidencia y cierre persistido.]
### Registro

*   **Evidencia:** Tabla de seguridad del agente: riesgos identificados, guardrail que cierra cada uno, acciones bajo control humano y resultado de la prueba de inyección propia.
*   **Cierre:** Registra tu avance en Gnius Space; Xolo confirma y tu logro queda escrito en proyecto.md.

---

[Intention: Reflexion critica e intercambio entre pares.]
### Brújula

*   **Piensa (30 seg):** Toda herramienta poderosa de la historia llegó antes que sus frenos: el auto antes del cinturón, la red antes de la contraseña. Con agentes, ustedes pueden diseñar los frenos ANTES del choque. ¿Qué freno le falta al agente que más usas?
*   **En pareja (2 min):** comparte tu respuesta y muestra tu avance.
*   **Al grupo (2 min):** conclusiones y cierre del Mentor de Cancha.

[IMAGE: Two students discussing at a clean desk while a class board shows a single open question, sober and thoughtful scene. Perspective: Isometric. Lighting: Bright neutral studio. Context: Minimal professional educational workspace. Emotion: Focus and clarity. All labels in Spanish.]
```

---

<a id="e2s4"></a>
## E2S4 · Taller de ramas

Playbook fuente: https://gnius-club.github.io/T4G_H2_PB/e2s4/

```
[Intention: Abrir el taller con el objetivo y el arranque autonomo con Xolo.]
[Layout Strategy: Hero]
### Encendido
# Taller de ramas
## Catálogo abierto · elige tu rama

*   **Objetivo:** avanzar la lección de tu rama e integrarla a tu proyecto en esta misma sesión.
*   **Arranque:** Accede a Gnius Space e inicia con Xolo; retoma tu proyecto desde la última línea de memoria.
*   **Skill Card de hoy:** la de tu rama.

[IMAGE: A branching catalog of project skill cards fanned out on a screen, each card with a distinct icon, student choosing one. Perspective: Isometric. Lighting: Bright neutral studio. Context: Minimal professional educational workspace. Emotion: Focus and clarity. All labels in Spanish.]

---

[Intention: El Mentor abre el abanico del catalogo; cada gancho es textual.]
### Demo

El abanico del catálogo abierto en esta Expedición:

*   **Proto-Agente:** "Tu primer agente no necesita código: necesita un propósito y una herramienta."
*   **Razonamiento ReAct:** "Antes de programar el bucle, apréndete el paso: pensar, actuar, observar."
*   **Orquestador en Python:** "El bucle deja el papel: ahora es un script que corre de verdad."
*   **Memoria del Agente:** "Un agente sin memoria hace la misma tarea por primera vez, todos los días."
*   **Datos vía API:** "Tu agente ya razona. Ahora hay que alimentarlo con datos frescos del mundo."
*   **Hipótesis Clave:** "Toda idea esconde una apuesta. Encuéntrala antes de que te cueste el año."
*   **Automatización Inteligente:** "Los flujos en línea recta se acabaron: aquí los caminos se bifurcan."

---

[Intention: Practica de taller con estandar de peticiones con contexto.]
### Manos a la obra

*   Avanza la lección de tu rama con Xolo: explicación, práctica, retroalimentación.
*   Pide con las tres piezas: qué quiero, qué intenté, qué pasó.
*   Puedes pedir trabajar directamente en tu proyecto en cualquier momento.

---

[Intention: Captura de evidencia y cierre persistido.]
### Registro

*   **Evidencia de tu rama:** foto o video corto del sistema operando, con el nombre del proyecto visible.
*   **Cierre:** Registra tu avance en Gnius Space; Xolo confirma y el avance queda escrito en proyecto.md.

---

[Intention: Reflexion critica e intercambio entre pares.]
### Brújula

*   **Piensa (30 seg):** Cada equipo tomó una ruta distinta y todos avanzaron. ¿Qué observaste en la solución de otro equipo que reformula tu propio enfoque?
*   **En pareja (2 min):** comparte tu respuesta y muestra tu avance.
*   **Al grupo (2 min):** conclusiones y cierre del Mentor de Cancha.

[IMAGE: Different student teams working on visibly different projects side by side, sharing observations at a clean board. Perspective: Isometric. Lighting: Bright neutral studio. Context: Minimal professional educational workspace. Emotion: Focus and clarity. All labels in Spanish.]
```

---

<a id="e2s5"></a>
## E2S5 · Taller de ramas · el toque del proyecto

Playbook fuente: https://gnius-club.github.io/T4G_H2_PB/e2s5/

```
[Intention: Abrir el taller con el objetivo y el arranque autonomo con Xolo.]
[Layout Strategy: Hero]
### Encendido
# Taller de ramas · el toque del proyecto
## Catálogo abierto · elige tu rama

*   **Objetivo:** avanzar la lección de tu rama e integrarla a tu proyecto en esta misma sesión.
*   **Arranque:** Accede a Gnius Space e inicia con Xolo; retoma tu proyecto desde la última línea de memoria.
*   **Skill Card de hoy:** la de tu rama.

[IMAGE: A branching catalog of project skill cards fanned out on a screen, each card with a distinct icon, student choosing one. Perspective: Isometric. Lighting: Bright neutral studio. Context: Minimal professional educational workspace. Emotion: Focus and clarity. All labels in Spanish.]

---

[Intention: El Mentor abre el abanico del catalogo; cada gancho es textual.]
### Demo

El abanico del catálogo abierto en esta Expedición:

*   **Proto-Agente:** "Tu primer agente no necesita código: necesita un propósito y una herramienta."
*   **Razonamiento ReAct:** "Antes de programar el bucle, apréndete el paso: pensar, actuar, observar."
*   **Orquestador en Python:** "El bucle deja el papel: ahora es un script que corre de verdad."
*   **Memoria del Agente:** "Un agente sin memoria hace la misma tarea por primera vez, todos los días."
*   **Datos vía API:** "Tu agente ya razona. Ahora hay que alimentarlo con datos frescos del mundo."
*   **Hipótesis Clave:** "Toda idea esconde una apuesta. Encuéntrala antes de que te cueste el año."
*   **Automatización Inteligente:** "Los flujos en línea recta se acabaron: aquí los caminos se bifurcan."

---

[Intention: Practica de taller con estandar de peticiones con contexto.]
### Manos a la obra

*   Avanza la lección de tu rama con Xolo: explicación, práctica, retroalimentación.
*   Pide con las tres piezas: qué quiero, qué intenté, qué pasó.
*   Puedes pedir trabajar directamente en tu proyecto en cualquier momento.

---

[Intention: Captura de evidencia y cierre persistido.]
### Registro

*   **Evidencia de tu rama:** foto o video corto del sistema operando, con el nombre del proyecto visible.
*   **Cierre:** Registra tu avance en Gnius Space; Xolo confirma y el avance queda escrito en proyecto.md.

---

[Intention: Reflexion critica e intercambio entre pares.]
### Brújula

*   **Piensa (30 seg):** Cada equipo tomó una ruta distinta y todos avanzaron. ¿Qué observaste en la solución de otro equipo que reformula tu propio enfoque?
*   **En pareja (2 min):** comparte tu respuesta y muestra tu avance.
*   **Al grupo (2 min):** conclusiones y cierre del Mentor de Cancha.

[IMAGE: Different student teams working on visibly different projects side by side, sharing observations at a clean board. Perspective: Isometric. Lighting: Bright neutral studio. Context: Minimal professional educational workspace. Emotion: Focus and clarity. All labels in Spanish.]
```

---

<a id="e2s6"></a>
## E2S6 · Pulido + Showcase 2

Playbook fuente: https://gnius-club.github.io/T4G_H2_PB/e2s6/

```
[Intention: Preparar el cierre publico: repaso y ensayo.]
[Layout Strategy: Hero]
### Repaso y ensayo del pitch
# Pulido + Showcase 2
## Cierre público de la Expedición 2

*   **Consigna:** Repaso del glosario vivido, guion del pitch, demo pública y archivo de la Expedición
*   Repasa el glosario vivido: los términos que tu equipo usó de verdad este trimestre.

[IMAGE: A rehearsal scene: student team practicing a short pitch in front of a simple timer and a projector, calm and professional. Perspective: Isometric. Lighting: Bright neutral studio. Context: Minimal professional educational workspace. Emotion: Focus and clarity. All labels in Spanish.]

---

[Intention: La estructura del pitch, elemento por elemento.]
### Presentaciones

Estructura del pitch:

1.  **El problema:** Qué problema atienden y su relevancia.
2.  **La demo:** La solución operando en vivo.
3.  **Lo que aprendimos:** Una capacidad dominada y un obstáculo superado.
4.  **El moonshot:** La proyección de la solución.

---

[Intention: Los reconocimientos del trimestre y su criterio.]
### Trofeos del trimestre

*   **Ejecución Más Sólida:** La implementación técnica más consistente del periodo.
*   **Sistema Más Confiable:** La mejor validación: prueba sistemática, datos y decisión fundamentada.
*   **Mejor Presentación:** La exposición que mejor articuló problema, solución y aprendizaje.

Los nombres de los trofeos están en validación con el equipo creativo.

---

[Intention: Ceremonia de archivo; la historia se congela, nada se borra.]
### Archivo de la Expedición

*   La historia de tu proyecto se congela tal como quedó — nada se borra.
*   El archivo es ceremonia: el grupo despide la Expedición con su proyecto completo.
*   Tras el archivo viene el kickoff de la Expedición 3.

[IMAGE: A project timeline being sealed into a clean digital archive drawer, sober interface, sense of completion without celebration props. Perspective: Isometric. Lighting: Bright neutral studio. Context: Minimal professional educational workspace. Emotion: Focus and clarity. All labels in Spanish.]
```

---

<a id="e3s1"></a>
## E3S1 · Kickoff · Expedición 3

Playbook fuente: https://gnius-club.github.io/T4G_H2_PB/e3s1/

```
[Intention: Abrir la Expedicion con la consigna y el encuadre inspirador.]
[Layout Strategy: Hero]
### Inspiración y encuadre
# Kickoff · Expedición 3
## Empatía profunda con el beneficiario y desbloqueo total del catálogo

*   Tu proyecto anterior quedó archivado como historia. Hoy decides: evolucionarlo o replantear desde cero — ambas rutas valen.
*   Los proyectos que verás son alcanzables: fueron construidos por equipos como el tuyo.

[IMAGE: An inspiring gallery wall of real student-built tech projects, photos pinned like a mission-control board without any text overload. Perspective: Isometric. Lighting: Bright neutral studio. Context: Minimal professional educational workspace. Emotion: Focus and clarity. All labels in Spanish.]

---

[Intention: La entrevista es de Xolo; una pregunta por turno.]
### Entrevista con Xolo

*   Xolo conduce con una pregunta por turno.
*   Xolo conduce la decisión (evolucionar o replantear) y el re-bautizo.
*   Responde con calma: no hay respuestas incorrectas, hay contexto.

---

[Intention: Bautizo del proyecto y presentacion de ramas desbloqueadas.]
### Bautizo y pre-elección de ramas

*   Nombra tu proyecto: nombre y apellido de producto.

Ramas desbloqueadas en esta Expedición:

*   **Kit del Constructor:** "De la idea a algo usable en días, no en meses: ese es el kit."
*   **Iterar el MVP:** "El primer feedback no es un examen: es el mapa de la siguiente versión."
*   **Descifrador de Deseos:** "Los usuarios no piden lo que más los enamoraría: hay que descifrarlo."
*   **Agente Seguro:** "El blindaje deja la teoría: hoy le ponen guardrails a SU agente."
*   **Producto con Agente:** "La integración final: un MVP donde el agente no es demo — es motor."

---

[Intention: Cierre formal del kickoff con los proyectos bautizados.]
### Cierre del kickoff

*   Cada proyecto se presenta por su nombre frente al grupo.
*   La Expedición 3 queda oficialmente iniciada.
*   Xolo deja el arranque escrito en proyecto.md.

[IMAGE: A clean roster board showing freshly named student projects, each with a name tag, group standing ready. Perspective: Isometric. Lighting: Bright neutral studio. Context: Minimal professional educational workspace. Emotion: Focus and clarity. All labels in Spanish.]
```

---

<a id="e3s2"></a>
## E3S2 · Taller de ramas

Playbook fuente: https://gnius-club.github.io/T4G_H2_PB/e3s2/

```
[Intention: Abrir el taller con el objetivo y el arranque autonomo con Xolo.]
[Layout Strategy: Hero]
### Encendido
# Taller de ramas
## Catálogo abierto · elige tu rama

*   **Objetivo:** avanzar la lección de tu rama e integrarla a tu proyecto en esta misma sesión.
*   **Arranque:** Accede a Gnius Space e inicia con Xolo; retoma tu proyecto desde la última línea de memoria.
*   **Skill Card de hoy:** la de tu rama.

[IMAGE: A branching catalog of project skill cards fanned out on a screen, each card with a distinct icon, student choosing one. Perspective: Isometric. Lighting: Bright neutral studio. Context: Minimal professional educational workspace. Emotion: Focus and clarity. All labels in Spanish.]

---

[Intention: El Mentor abre el abanico del catalogo; cada gancho es textual.]
### Demo

El abanico del catálogo abierto en esta Expedición:

*   **Proto-Agente:** "Tu primer agente no necesita código: necesita un propósito y una herramienta."
*   **Razonamiento ReAct:** "Antes de programar el bucle, apréndete el paso: pensar, actuar, observar."
*   **Orquestador en Python:** "El bucle deja el papel: ahora es un script que corre de verdad."
*   **Memoria del Agente:** "Un agente sin memoria hace la misma tarea por primera vez, todos los días."
*   **Datos vía API:** "Tu agente ya razona. Ahora hay que alimentarlo con datos frescos del mundo."
*   **Kit del Constructor:** "De la idea a algo usable en días, no en meses: ese es el kit."
*   **Iterar el MVP:** "El primer feedback no es un examen: es el mapa de la siguiente versión."
*   **Descifrador de Deseos:** "Los usuarios no piden lo que más los enamoraría: hay que descifrarlo."
*   **Agente Seguro:** "El blindaje deja la teoría: hoy le ponen guardrails a SU agente."
*   **Producto con Agente:** "La integración final: un MVP donde el agente no es demo — es motor."
*   **Hipótesis Clave:** "Toda idea esconde una apuesta. Encuéntrala antes de que te cueste el año."
*   **Automatización Inteligente:** "Los flujos en línea recta se acabaron: aquí los caminos se bifurcan."

---

[Intention: Practica de taller con estandar de peticiones con contexto.]
### Manos a la obra

*   Avanza la lección de tu rama con Xolo: explicación, práctica, retroalimentación.
*   Pide con las tres piezas: qué quiero, qué intenté, qué pasó.
*   Puedes pedir trabajar directamente en tu proyecto en cualquier momento.

---

[Intention: Captura de evidencia y cierre persistido.]
### Registro

*   **Evidencia de tu rama:** foto o video corto del sistema operando, con el nombre del proyecto visible.
*   **Cierre:** Registra tu avance en Gnius Space; Xolo confirma y el avance queda escrito en proyecto.md.

---

[Intention: Reflexion critica e intercambio entre pares.]
### Brújula

*   **Piensa (30 seg):** Cada equipo tomó una ruta distinta y todos avanzaron. ¿Qué observaste en la solución de otro equipo que reformula tu propio enfoque?
*   **En pareja (2 min):** comparte tu respuesta y muestra tu avance.
*   **Al grupo (2 min):** conclusiones y cierre del Mentor de Cancha.

[IMAGE: Different student teams working on visibly different projects side by side, sharing observations at a clean board. Perspective: Isometric. Lighting: Bright neutral studio. Context: Minimal professional educational workspace. Emotion: Focus and clarity. All labels in Spanish.]
```

---

<a id="e3s3"></a>
## E3S3 · Taller de ramas

Playbook fuente: https://gnius-club.github.io/T4G_H2_PB/e3s3/

```
[Intention: Abrir el taller con el objetivo y el arranque autonomo con Xolo.]
[Layout Strategy: Hero]
### Encendido
# Taller de ramas
## Catálogo abierto · elige tu rama

*   **Objetivo:** avanzar la lección de tu rama e integrarla a tu proyecto en esta misma sesión.
*   **Arranque:** Accede a Gnius Space e inicia con Xolo; retoma tu proyecto desde la última línea de memoria.
*   **Skill Card de hoy:** la de tu rama.

[IMAGE: A branching catalog of project skill cards fanned out on a screen, each card with a distinct icon, student choosing one. Perspective: Isometric. Lighting: Bright neutral studio. Context: Minimal professional educational workspace. Emotion: Focus and clarity. All labels in Spanish.]

---

[Intention: El Mentor abre el abanico del catalogo; cada gancho es textual.]
### Demo

El abanico del catálogo abierto en esta Expedición:

*   **Proto-Agente:** "Tu primer agente no necesita código: necesita un propósito y una herramienta."
*   **Razonamiento ReAct:** "Antes de programar el bucle, apréndete el paso: pensar, actuar, observar."
*   **Orquestador en Python:** "El bucle deja el papel: ahora es un script que corre de verdad."
*   **Memoria del Agente:** "Un agente sin memoria hace la misma tarea por primera vez, todos los días."
*   **Datos vía API:** "Tu agente ya razona. Ahora hay que alimentarlo con datos frescos del mundo."
*   **Kit del Constructor:** "De la idea a algo usable en días, no en meses: ese es el kit."
*   **Iterar el MVP:** "El primer feedback no es un examen: es el mapa de la siguiente versión."
*   **Descifrador de Deseos:** "Los usuarios no piden lo que más los enamoraría: hay que descifrarlo."
*   **Agente Seguro:** "El blindaje deja la teoría: hoy le ponen guardrails a SU agente."
*   **Producto con Agente:** "La integración final: un MVP donde el agente no es demo — es motor."
*   **Hipótesis Clave:** "Toda idea esconde una apuesta. Encuéntrala antes de que te cueste el año."
*   **Automatización Inteligente:** "Los flujos en línea recta se acabaron: aquí los caminos se bifurcan."

---

[Intention: Practica de taller con estandar de peticiones con contexto.]
### Manos a la obra

*   Avanza la lección de tu rama con Xolo: explicación, práctica, retroalimentación.
*   Pide con las tres piezas: qué quiero, qué intenté, qué pasó.
*   Puedes pedir trabajar directamente en tu proyecto en cualquier momento.

---

[Intention: Captura de evidencia y cierre persistido.]
### Registro

*   **Evidencia de tu rama:** foto o video corto del sistema operando, con el nombre del proyecto visible.
*   **Cierre:** Registra tu avance en Gnius Space; Xolo confirma y el avance queda escrito en proyecto.md.

---

[Intention: Reflexion critica e intercambio entre pares.]
### Brújula

*   **Piensa (30 seg):** Cada equipo tomó una ruta distinta y todos avanzaron. ¿Qué observaste en la solución de otro equipo que reformula tu propio enfoque?
*   **En pareja (2 min):** comparte tu respuesta y muestra tu avance.
*   **Al grupo (2 min):** conclusiones y cierre del Mentor de Cancha.

[IMAGE: Different student teams working on visibly different projects side by side, sharing observations at a clean board. Perspective: Isometric. Lighting: Bright neutral studio. Context: Minimal professional educational workspace. Emotion: Focus and clarity. All labels in Spanish.]
```

---

<a id="e3s4"></a>
## E3S4 · Taller de ramas

Playbook fuente: https://gnius-club.github.io/T4G_H2_PB/e3s4/

```
[Intention: Abrir el taller con el objetivo y el arranque autonomo con Xolo.]
[Layout Strategy: Hero]
### Encendido
# Taller de ramas
## Catálogo abierto · elige tu rama

*   **Objetivo:** avanzar la lección de tu rama e integrarla a tu proyecto en esta misma sesión.
*   **Arranque:** Accede a Gnius Space e inicia con Xolo; retoma tu proyecto desde la última línea de memoria.
*   **Skill Card de hoy:** la de tu rama.

[IMAGE: A branching catalog of project skill cards fanned out on a screen, each card with a distinct icon, student choosing one. Perspective: Isometric. Lighting: Bright neutral studio. Context: Minimal professional educational workspace. Emotion: Focus and clarity. All labels in Spanish.]

---

[Intention: El Mentor abre el abanico del catalogo; cada gancho es textual.]
### Demo

El abanico del catálogo abierto en esta Expedición:

*   **Proto-Agente:** "Tu primer agente no necesita código: necesita un propósito y una herramienta."
*   **Razonamiento ReAct:** "Antes de programar el bucle, apréndete el paso: pensar, actuar, observar."
*   **Orquestador en Python:** "El bucle deja el papel: ahora es un script que corre de verdad."
*   **Memoria del Agente:** "Un agente sin memoria hace la misma tarea por primera vez, todos los días."
*   **Datos vía API:** "Tu agente ya razona. Ahora hay que alimentarlo con datos frescos del mundo."
*   **Kit del Constructor:** "De la idea a algo usable en días, no en meses: ese es el kit."
*   **Iterar el MVP:** "El primer feedback no es un examen: es el mapa de la siguiente versión."
*   **Descifrador de Deseos:** "Los usuarios no piden lo que más los enamoraría: hay que descifrarlo."
*   **Agente Seguro:** "El blindaje deja la teoría: hoy le ponen guardrails a SU agente."
*   **Producto con Agente:** "La integración final: un MVP donde el agente no es demo — es motor."
*   **Hipótesis Clave:** "Toda idea esconde una apuesta. Encuéntrala antes de que te cueste el año."
*   **Automatización Inteligente:** "Los flujos en línea recta se acabaron: aquí los caminos se bifurcan."

---

[Intention: Practica de taller con estandar de peticiones con contexto.]
### Manos a la obra

*   Avanza la lección de tu rama con Xolo: explicación, práctica, retroalimentación.
*   Pide con las tres piezas: qué quiero, qué intenté, qué pasó.
*   Puedes pedir trabajar directamente en tu proyecto en cualquier momento.

---

[Intention: Captura de evidencia y cierre persistido.]
### Registro

*   **Evidencia de tu rama:** foto o video corto del sistema operando, con el nombre del proyecto visible.
*   **Cierre:** Registra tu avance en Gnius Space; Xolo confirma y el avance queda escrito en proyecto.md.

---

[Intention: Reflexion critica e intercambio entre pares.]
### Brújula

*   **Piensa (30 seg):** Cada equipo tomó una ruta distinta y todos avanzaron. ¿Qué observaste en la solución de otro equipo que reformula tu propio enfoque?
*   **En pareja (2 min):** comparte tu respuesta y muestra tu avance.
*   **Al grupo (2 min):** conclusiones y cierre del Mentor de Cancha.

[IMAGE: Different student teams working on visibly different projects side by side, sharing observations at a clean board. Perspective: Isometric. Lighting: Bright neutral studio. Context: Minimal professional educational workspace. Emotion: Focus and clarity. All labels in Spanish.]
```

---

<a id="e3s5"></a>
## E3S5 · Taller de ramas · el toque del proyecto

Playbook fuente: https://gnius-club.github.io/T4G_H2_PB/e3s5/

```
[Intention: Abrir el taller con el objetivo y el arranque autonomo con Xolo.]
[Layout Strategy: Hero]
### Encendido
# Taller de ramas · el toque del proyecto
## Catálogo abierto · elige tu rama

*   **Objetivo:** avanzar la lección de tu rama e integrarla a tu proyecto en esta misma sesión.
*   **Arranque:** Accede a Gnius Space e inicia con Xolo; retoma tu proyecto desde la última línea de memoria.
*   **Skill Card de hoy:** la de tu rama.

[IMAGE: A branching catalog of project skill cards fanned out on a screen, each card with a distinct icon, student choosing one. Perspective: Isometric. Lighting: Bright neutral studio. Context: Minimal professional educational workspace. Emotion: Focus and clarity. All labels in Spanish.]

---

[Intention: El Mentor abre el abanico del catalogo; cada gancho es textual.]
### Demo

El abanico del catálogo abierto en esta Expedición:

*   **Proto-Agente:** "Tu primer agente no necesita código: necesita un propósito y una herramienta."
*   **Razonamiento ReAct:** "Antes de programar el bucle, apréndete el paso: pensar, actuar, observar."
*   **Orquestador en Python:** "El bucle deja el papel: ahora es un script que corre de verdad."
*   **Memoria del Agente:** "Un agente sin memoria hace la misma tarea por primera vez, todos los días."
*   **Datos vía API:** "Tu agente ya razona. Ahora hay que alimentarlo con datos frescos del mundo."
*   **Kit del Constructor:** "De la idea a algo usable en días, no en meses: ese es el kit."
*   **Iterar el MVP:** "El primer feedback no es un examen: es el mapa de la siguiente versión."
*   **Descifrador de Deseos:** "Los usuarios no piden lo que más los enamoraría: hay que descifrarlo."
*   **Agente Seguro:** "El blindaje deja la teoría: hoy le ponen guardrails a SU agente."
*   **Producto con Agente:** "La integración final: un MVP donde el agente no es demo — es motor."
*   **Hipótesis Clave:** "Toda idea esconde una apuesta. Encuéntrala antes de que te cueste el año."
*   **Automatización Inteligente:** "Los flujos en línea recta se acabaron: aquí los caminos se bifurcan."

---

[Intention: Practica de taller con estandar de peticiones con contexto.]
### Manos a la obra

*   Avanza la lección de tu rama con Xolo: explicación, práctica, retroalimentación.
*   Pide con las tres piezas: qué quiero, qué intenté, qué pasó.
*   Puedes pedir trabajar directamente en tu proyecto en cualquier momento.

---

[Intention: Captura de evidencia y cierre persistido.]
### Registro

*   **Evidencia de tu rama:** foto o video corto del sistema operando, con el nombre del proyecto visible.
*   **Cierre:** Registra tu avance en Gnius Space; Xolo confirma y el avance queda escrito en proyecto.md.

---

[Intention: Reflexion critica e intercambio entre pares.]
### Brújula

*   **Piensa (30 seg):** Cada equipo tomó una ruta distinta y todos avanzaron. ¿Qué observaste en la solución de otro equipo que reformula tu propio enfoque?
*   **En pareja (2 min):** comparte tu respuesta y muestra tu avance.
*   **Al grupo (2 min):** conclusiones y cierre del Mentor de Cancha.

[IMAGE: Different student teams working on visibly different projects side by side, sharing observations at a clean board. Perspective: Isometric. Lighting: Bright neutral studio. Context: Minimal professional educational workspace. Emotion: Focus and clarity. All labels in Spanish.]
```

---

<a id="e3s6"></a>
## E3S6 · Pulido + Showcase 3

Playbook fuente: https://gnius-club.github.io/T4G_H2_PB/e3s6/

```
[Intention: Preparar el cierre publico: repaso y ensayo.]
[Layout Strategy: Hero]
### Repaso y ensayo del pitch
# Pulido + Showcase 3
## Cierre público de la Expedición 3

*   **Consigna:** Repaso del glosario vivido, guion del pitch, demo pública y archivo de la Expedición
*   Repasa el glosario vivido: los términos que tu equipo usó de verdad este trimestre.

[IMAGE: A rehearsal scene: student team practicing a short pitch in front of a simple timer and a projector, calm and professional. Perspective: Isometric. Lighting: Bright neutral studio. Context: Minimal professional educational workspace. Emotion: Focus and clarity. All labels in Spanish.]

---

[Intention: La estructura del pitch, elemento por elemento.]
### Presentaciones

Estructura del pitch:

1.  **El problema:** Qué problema atienden y su relevancia.
2.  **La demo:** La solución operando en vivo.
3.  **Lo que aprendimos:** Una capacidad dominada y un obstáculo superado.
4.  **El moonshot:** La proyección de la solución.

---

[Intention: Los reconocimientos del trimestre y su criterio.]
### Trofeos del trimestre

*   **Ejecución Más Sólida:** La implementación técnica más consistente del periodo.
*   **Sistema Más Confiable:** La mejor validación: prueba sistemática, datos y decisión fundamentada.
*   **Mejor Presentación:** La exposición que mejor articuló problema, solución y aprendizaje.

Los nombres de los trofeos están en validación con el equipo creativo.

---

[Intention: Ceremonia de archivo; la historia se congela, nada se borra.]
### Archivo de la Expedición

*   La historia de tu proyecto se congela tal como quedó — nada se borra.
*   El archivo es ceremonia: el grupo despide la Expedición con su proyecto completo.
*   Tras el archivo cierra el ciclo: el recorrido completo del año queda escrito.

[IMAGE: A project timeline being sealed into a clean digital archive drawer, sober interface, sense of completion without celebration props. Perspective: Isometric. Lighting: Bright neutral studio. Context: Minimal professional educational workspace. Emotion: Focus and clarity. All labels in Spanish.]
```
