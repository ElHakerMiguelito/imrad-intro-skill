# IMRaD Intro — Skill para Claude

Skill para Claude que genera introducciones académicas en formato IMRaD para trabajos de ingeniería universitaria, especialmente del Tec de Monterrey.

## ¿Qué hace?

Te guía paso a paso para redactar introducciones que suenan como las escribiría un académico, no un estudiante. El flujo es:

1. **Contexto** — te hace preguntas sobre tu trabajo antes de hacer nada
2. **Fuentes** — busca referencias reales y verificables en APA 7, tú las apruebas
3. **Redacción** — genera la intro con citas, ecuaciones si aplican, y cierre explícito

Las introducciones siguen estructura de embudo: gancho → problema real → física → modelo → objetivo → estructura del reporte.

## ¿Cómo instalarla?

1. Abre [claude.ai](https://claude.ai) y ve a **Settings → Custom instructions**
2. Copia todo el contenido de `SKILL.md` y pégalo ahí
3. Guarda los cambios

Desde ese momento, en cualquier chat nuevo escribe `/intro` para activarla.

## Comandos disponibles

| Comando | Efecto |
|---|---|
| `/intro` o `/imrad` | Inicia o reinicia desde el principio |
| `más larga` / `más corta` | Ajusta la extensión de la intro ya redactada |
| `más formal` / `más sencilla` | Ajusta el nivel de lenguaje |
| `más citas` | Busca fuentes adicionales |
| `sin referencias` | Redacta sin sección de referencias (modo borrador) |
| `solo fuentes` | Solo ejecuta la búsqueda de fuentes, sin redactar |
| `redactar ya` | Salta directo a redacción con lo que ya tienes |

## Contexto de diseño

Diseñada para materias de física aplicada a ingeniería donde se pide un reporte en formato IMRaD. La skill asume que el trabajo combina modelado matemático, simulación o experimento con un problema real de ingeniería.

Desarrollada por un estudiante de Ingeniería en Innovación y Desarrollo en el Tec de Monterrey.
