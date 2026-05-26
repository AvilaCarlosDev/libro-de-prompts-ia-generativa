# Libro de Prompts: Documentando el Proceso Creativo con IA Generativa

> **Proyecto Final** — AI for Professionals @ 4Geeks Academy

## Introduccion

Este Libro de Prompts documenta el proceso creativo completo del proyecto **"El Despertar de la IA"**, una narrativa visual interactiva que explora la evolucion de la inteligencia artificial a traves de tres eras: Caveman, Superpowers y Cyber Neo.

Este documento sirve como diario creativo y registro sistematico de todas las interacciones con herramientas de IA generativa durante el desarrollo del proyecto.

---

## Resumen del Proyecto

**Que cree:** Un sitio web interactivo narrativo con 3 eras tematicas (Caveman, Superpowers, Cyber Neo) que cuenta la evolucion de la IA generativa de forma visual y creativa.

**Objetivo:** Demostrar el uso efectivo de herramientas de IA generativa para producir contenido creativo original.

**Herramientas:** ChatGPT, Krea.ai, Runway ML, Live Portrait, Gamma.app, Claude AI.

**Demo:** https://avilacarlosdev.github.io/ai-generativa-proyecto-final/

---

## Seccion 1: Conceptualizacion con ChatGPT

### Prompt 1.1 - Concepto del Proyecto

**Herramienta:** ChatGPT 4o
**Fecha:** Mayo 2026
**Prompt:**
"Necesito crear un proyecto creativo para un curso de IA generativa. Quiero que sea un sitio web narrativo que cuente la historia de la evolucion de la IA desde sus origenes primitivos hasta el futuro ciberpunk. Dame un concepto creativo con 3 eras tematicas y nombre para el proyecto."

**Resultado:** Surgio el concepto "El Despertar de la IA" con las 3 eras: Caveman (origen primitivo), Superpowers (era actual), Cyber Neo (futuro). La estructura narrativa clara permitio organizar todo el proyecto.

**Observaciones:** ChatGPT genero estructuras conceptuales solidas pero las descripciones eran genericas. Se necesitaron varias iteraciones para obtener el nivel de detalle deseado.

---

### Prompt 1.2 - Narrativas de Cada Era

**Herramienta:** ChatGPT 4o
**Prompt:**
"Para la era 'Caveman' del proyecto, escribe 3 parrafos narrativos que describan los primeros algoritmos, sistemas expertos y modelos de lenguaje primitivos, usando metaforas de la era de las cavernas. El tono debe ser epico y poetico."

**Resultado:** Se obtuvieron narrativas evocadoras que conectaban la computacion primitiva con imagenes de hombres primitivos descubriendo el fuego. Muy efectivo para el estilo visual del sitio.

**Iteraciones realizadas:**
- Primer intento: Demasiado tecnico, poco poetico
- Segunda iteracion: Anadiendo "usa metaforas visuales y lenguaje epico"
- Tercer intento: Resultado final con el balance correcto

---

## Seccion 2: Generacion de Ideas Visuales con Krea.ai

### Prompt 2.1 - Paleta de Colores Caveman

**Herramienta:** Krea.ai
**Prompt:**
"Dark cave background with prehistoric paintings, warm earth tones, brown sienna wheat colors, primitive AI algorithms visualized as cave paintings, cinematic lighting, 8k quality"

**Resultado:** Se obtuvieron paletas de color que inspiraron el diseno CSS del proyecto: marrones (#2d1b00), siennas (#8b4513), y tonos trigo (#f5deb3).

**Observaciones:** Krea.ai es excelente para establecer la estetica visual. Las imagenes generadas sirvieron como referencia directa para el diseno.

---

### Prompt 2.2 - Estilo Cyber Neo

**Herramienta:** Krea.ai
**Prompt:**
"Cyberpunk city 2047, neon green (#00ffcc) circuit grid, neural network visualization, dark background #000510, AI nodes and connections, futuristic technology aesthetic, blade runner inspired"

**Resultado:** Imagenes que capturaron perfectamente la estetica del modulo Cyber Neo: fondo negro, grilla de neon verde, circuitos luminosos.

**Iteraciones:**
- Iteracion 1: Sin referencia de color especifica - resultado generico azul/morado
- Iteracion 2: Con codigos hex especificos #00ffcc - resultado mucho mas preciso y utilizable

---

### Prompt 2.3 - Era Superpowers

**Herramienta:** Krea.ai
**Prompt:**
"Superhero digital era, vibrant orange #ff6b35 to purple gradient, energy powers visualization, digital hero silhouette, glowing aura, comic book style meets digital art"

**Resultado:** Paleta vibrante naranja-purpura que definio la seccion Superpowers del sitio web.

---

## Seccion 3: Animaciones con Runway ML

### Prompt 3.1 - Animacion de Particulas

**Herramienta:** Runway ML (Gen-2)
**Prompt de imagen de entrada:** Krea.ai output - caveman era
**Prompt de texto:**
"Slow camera pan over prehistoric cave paintings that gradually transform into glowing circuit boards, particles of light, smooth transition, 4 seconds"

**Resultado:** Animacion de 4 segundos que muestra la transicion de pinturas rupestres a circuitos electronicos.

**Observaciones:** Runway requiere imagenes de entrada de alta calidad. La combinacion con Krea.ai como fuente de imagenes fue muy efectiva.

---

## Seccion 4: Animacion Facial con Live Portrait

### Prompt 4.1 - Personaje Narrador

**Herramienta:** Live Portrait (HuggingFace)
**Imagen base:** Retrato estilo pinturas rupestres generado en Krea.ai
**Configuracion:** 
- Expression scale: 1.2
- Motion scale: 0.8
- FPS: 25

**Resultado:** El personaje "Groog el programador primitivo" cobro vida para narrar el origen de los algoritmos.

**Observaciones:** Live Portrait funciona mejor con retratos frontales bien iluminados. Imagenes de perfil o con oclusiones producen artefactos visuales.

---

## Seccion 5: Desarrollo Web con Claude AI

### Prompt 5.1 - Estructura HTML/CSS

**Herramienta:** Claude AI (Anthropic)
**Prompt:**
"Crea un sitio web HTML/CSS/JS con 3 secciones tematicas: Caveman (colores marrones), Superpowers (naranja/purpura), Cyber Neo (neon verde). Debe tener navegacion fija, animaciones suaves, cards con hover effects, barra de progreso animada y diseno responsive."

**Resultado:** Codigo HTML completo y funcional con todas las secciones. El sitio paso de concepto a implementacion en una sola sesion.

**Iteraciones:**
- Primera version: Sin animaciones CSS
- Segunda version: Con animaciones float, glow y progress bar
- Version final: Con todas las secciones pulidas y responsive design

---

## Seccion 6: Presentacion con Gamma.app

### Prompt 6.1 - Documentacion Interactiva

**Herramienta:** Gamma.app
**Prompt:**
"Crea una presentacion sobre 'El Despertar de la IA' con estructura: portada impactante, 3 eras (Caveman/Superpowers/Cyber Neo), herramientas utilizadas, proceso creativo, resultados y conclusiones. Estilo futurista con colores neon."

**Resultado:** Presentacion interactiva de 12 diapositivas que complementa el sitio web con mas contexto narrativo.

---

## Observaciones Finales

### Fortalezas de la IA Generativa
- ChatGPT: Excelente para narrativas y conceptualizacion inicial
- Krea.ai: Muy preciso con referencias de color especificas (codigos hex)
- Runway ML: Transiciones suaves y cinematograficas
- Claude AI: Ideal para generacion de codigo complejo y funcional

### Limitaciones Encontradas
- Krea.ai: Prompts vagos producen resultados genericos
- Runway ML: Requiere imagenes de entrada de alta calidad
- Live Portrait: Solo funciona bien con retratos frontales
- ChatGPT: Primera respuesta suele ser muy generica

### Lecciones Aprendidas
1. Los prompts especificos (con colores, medidas, referencias) producen mejores resultados
2. La iteracion es clave - casi ningun prompt produce el resultado ideal en el primer intento
3. Combinar herramientas (Krea.ai + Runway) produce resultados superiores
4. Documentar cada iteracion ayuda a entender que cambios producen que mejoras

### Reflexion sobre el Proceso
Trabajar con IA generativa transforma el proceso creativo. Ya no se trata de ejecutar habilidades tecnicas sino de comunicar vision de forma precisa. El prompt es el nuevo pincel, y aprender a usarlo efectivamente es el arte moderno.

La IA no reemplaza la creatividad humana - la amplifica. El resultado final es una co-creacion donde la vision humana guia y la IA ejecuta con precision sobrehumana.

---

## Autor

**Carlos Avila** ([@AvilaCarlosDev](https://github.com/AvilaCarlosDev))

**Proyecto:** https://avilacarlosdev.github.io/ai-generativa-proyecto-final/

*Proyecto Final — AI for Professionals @ 4Geeks Academy | Mayo 2026*
