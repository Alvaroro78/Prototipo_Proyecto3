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

- **Rama y commits:** `chore/estructura` · `chore: agrega .gitignore`
- **Escribí:** el `.gitignore` con las carpetas que crean Gradle e IntelliJ.
- **Me detuve porque:** no sabía qué poner en `.gitignore`. Creé una rama con nombre de feature y la cambié a `chore/` porque no es un requerimiento del enunciado.
- **Decidí:** ignorar solo lo que generan Gradle e IntelliJ. Lo de Node lo agrego cuando empecemos el frontend.
- **Sigue:** crear la bitácora, `settings.gradle` y `build.gradle`.