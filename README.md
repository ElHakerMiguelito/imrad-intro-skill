# imrad-intro

Skill para Claude Code que genera introducciones académicas en formato IMRaD para trabajos de ingeniería universitaria, especialmente del Tec de Monterrey.

## Estructura

```
imrad-intro/
├── SKILL.md                    # Skill principal
└── references/
    └── estilos-intro.md        # Guía de tono y frases de referencia
```

## ¿Qué hace?

Guía el proceso completo de redacción en tres fases:

1. **Contexto** — preguntas dirigidas sobre el trabajo antes de investigar
2. **Fuentes** — búsqueda de referencias reales en APA 7, con aprobación del usuario
3. **Redacción** — intro con citas verificables, ecuaciones si aplican, y cierre explícito

Las introducciones siguen estructura de embudo: gancho → problema real → física → modelo → objetivo → estructura del reporte.

## Instalación

### Claude Code (recomendado)

Copia la carpeta completa a tu directorio de skills:

```bash
# macOS / Linux
cp -r imrad-intro ~/.claude/skills/

# Windows
xcopy /E imrad-intro %USERPROFILE%\.claude\skills\imrad-intro\
```

### Claude.ai (instrucciones personalizadas)

1. Abre [claude.ai](https://claude.ai) → **Settings → Custom instructions**
2. Copia el contenido de `SKILL.md` y pégalo ahí
3. Guarda los cambios

> **Nota:** Con este método `references/estilos-intro.md` no estará disponible. La Fase 2 funcionará pero sin calibración de tono automática.

## Uso

Escribe `/intro` o `/imrad` en cualquier chat para activar la skill.

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

Diseñada para materias de física aplicada a ingeniería donde se pide un reporte en formato IMRaD. Asume que el trabajo combina modelado matemático, simulación o experimento con un problema real de ingeniería.

Desarrollada por un estudiante de Ingeniería en el Tec de Monterrey.
