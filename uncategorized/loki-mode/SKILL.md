---
name: loki-mode
description: |
  Sistema de autonomía de agentes AI con constitución y benchmarks.
  Workspace completo para crear agentes autónomos con gobernanza.
metadata:
  model: haiku
risk: unknown
source: community
---

## ⚠️ Workspace Standalone

**Esta NO es una skill simple** - es un workspace completo que debe ejecutarse en su propio contexto.

## Ubicación Actual

```
C:\Users\Windows 11\Documents\programacion\personal\skills\repos_skills\loki-mode
```

## Cómo Usar

```bash
# Navega al workspace
cd C:\Users\Windows 11\Documents\programacion\personal\skills\repos_skills\loki-mode

# Inicia el workspace
qwen-code .
```

## Qué es Loki Mode

Sistema de autonomía para agentes AI que incluye:
- **Constitución de agentes**: Reglas de gobernanza y comportamiento
- **Benchmarks**: Tests de rendimiento y autonomía
- **Integraciones**: Conexión con herramientas externas
- **Demo**: Ejemplos de uso
- **Documentación completa**: Guías de implementación

## Estructura

```
loki-mode/
├── autonomy/          # Configuración de autonomía
│   ├── .loki/
│   ├── CONSTITUTION.md
│   └── run.sh
├── benchmarks/        # Tests de rendimiento
├── demo/             # Ejemplos de uso
├── docs/             # Documentación
├── examples/         # Casos de uso
├── integrations/     # Integraciones externas
├── scripts/          # Scripts de utilidad
└── tests/            # Tests automatizados
```

## Comandos Disponibles

Dentro del workspace:
```bash
# Ejecutar agente
./autonomy/run.sh

# Correr benchmarks
cd benchmarks && ./run-benchmarks.sh

# Ver documentación
cat docs/README.md
```

## Relacionado

- `ai-agents-architect` - Arquitectura de agentes
- `autonomous-agents` - Agentes autónomos
- `voice-agents` - Agentes de voz
