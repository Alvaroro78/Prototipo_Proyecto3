# Bitácora · Icesi Live Arena

Registro de cómo se construyó el proyecto, paso a paso. Cada entrada se escribe **mientras** se trabaja, no al final. Anota también lo que no funcionó.

## Cómo se escribe una entrada

- **Paso:** número y nombre corto (por ejemplo `0.1 · Estructura`).
- **Rama y commits:** la rama de trabajo y los mensajes de commit de ese paso.
- **Escribí:** qué creé o cambié, en una o dos frases.
- **Me detuve porque:** la duda, el error o la decisión que me hizo parar.
- **Decidí:** la opción que elegí y por qué (y la que descarté).
- **Sigue:** qué viene después.

## Entradas - Paso 0

### 0.1 · Estructura

- **Rama y commits:** `chore/estructura` · `chore: agrega .gitignore` · `chore: agrega código base del profesor en codigo base/` · `docs: actualiza bitácora del paso 0.1` · merge a `develop` con `--no-ff`.
- **Escribí:** el `.gitignore` con lo que generan Gradle e IntelliJ, y después el código base del profesor dentro de `codigo base/`, con su `settings.gradle`, `build.gradle` y el wrapper de Gradle.
- **Me detuve porque:**
    - No sabía qué poner en `.gitignore`.
    - Creé la rama con nombre de feature y la cambié a `chore/` porque la estructura no es un requerimiento del enunciado.
    - Intenté usar `gradle wrapper` y el comando `gradle` no estaba instalado. Luego `winget install Gradle.Gradle` no encontró el paquete. La tarea `wrapper` de IntelliJ tampoco funcionó.
- **Decidí:**
    - Usar el código base del profesor como punto de partida, porque el enunciado lo pide como base de la entrega.
    - Tomar el wrapper de Gradle del código base en vez de generarlo, porque es una herramienta y no código del proyecto.
    - Ignorar solo lo que generan Gradle e IntelliJ, y dejar lo de Node para el frontend.
    - Trabajar con ramas por tarea, aunque sea un equipo de uno, para que el historial se vea ordenado en GitHub.
- **Sigue:** 0.2 · corrección de concurrencia en `lockSeat`, en la rama `fix/concurrencia-lockseat`.
 