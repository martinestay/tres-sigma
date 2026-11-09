# Tres Sigma

Juego de repaso para **Física Computacional II** (USACH, 2026), con la materia de las clases 1 a 6 y las tareas 1 a 6: terminal y Git, Python, ciclos y condicionales, funciones, clases y decoradores, NumPy y broadcasting, Matplotlib, pandas, lectura/escritura de archivos, imágenes y fotometría.

Incluye 251 ejercicios de completar código, 250 de opción múltiple, 40 programas para ordenar, 53 comandos de terminal y 33 figuras para depurar.

Todo el juego está en `index.html`, un solo archivo. Se abre en cualquier navegador; solo necesita internet para cargar las fuentes.

## Modos

- **Completar código**: llena los espacios del código contra el reloj.
- **Completar código en grupo**: turnos con reloj y vidas compartidas.
- **Depurar gráficos**: el código se ejecuta línea a línea y la figura se construye en vivo; encuentra el error y corrígelo.
- **Duelo**: 1 contra 1 o por equipos en el mismo teclado (Q W E R contra U I O P).
- **Contra la IA**: compites ronda a ronda contra uno de cuatro rivales simulados, cada uno con su forma de razonar y su dificultad: Gemini Argón (nivel 1, visual), GPT 6 Astra (nivel 2, veloz e intuitiva), Fable 5.1 (nivel 3, metódica, paso a paso) y Grok Heavy (nivel 4, tres agentes que votan; en las preguntas de física manda su agente de Física, que nunca se equivoca). Ves su razonamiento en vivo, pero su respuesta queda oculta hasta que contestas. *Los rivales son simulados: el juego no se conecta a ningún modelo real.*
- **Caza alucinaciones**: una IA responde con total seguridad, pero a veces inventa. Decides si tiene razón o tocas la función que no existe; al final ves tu precisión y exhaustividad. Las 128 funciones inventadas se comprobaron contra NumPy, pandas y Matplotlib reales.
- **Entrena tu modelo**: tus respuestas son el dataset. Repartes lotes de entrenamiento entre 4 temas y tu modelo compite solo en una liga contra los cuatro rivales.
- **Consejo de IAs**: gastas 100 tokens en consultar a las IAs y apuestas tu confianza con una regla de puntaje cuadrática; al final ves si estás bien calibrado.
- **Predecir la salida**: anticipa el resultado del código sin ejecutarlo.
- **Ordenar el programa**: ordena las líneas; se acepta cualquier orden que Python ejecutaría bien.
- **Comandos de terminal**: Unix, conda y Git.
- **Simulacro de prueba**: 15 preguntas en 12 minutos, nota de 1,0 a 7,0.

Vidas a elección: muerte súbita (1), 3, 5 o ilimitadas. Los récords se guardan solo en el navegador de cada persona.

Al terminar cada partida aparece un repaso con las preguntas que fallaste, su respuesta y su explicación. En el inicio, cada tema muestra tu porcentaje de aciertos, y el juego sugiere practicar los dos temas más débiles.

## Publicar con GitHub Pages

En el repositorio: **Settings → Pages**, «Source» = rama `main`, carpeta `/ (root)`. Queda en `https://TU-USUARIO.github.io/tres-sigma/`.

---

Creado por Martín Estay Valdés con la ayuda de Claude Opus 5.5, de Anthropic.
