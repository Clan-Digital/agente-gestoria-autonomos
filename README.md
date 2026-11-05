# Agentes de Clan Digital

Catálogo de plugins de Claude con los agentes de IA de Clan Digital. Cada agente se instala en la cuenta de Claude del cliente: sus datos se quedan en sus cuentas.

## Instalar (en la app de escritorio de Claude, pestaña Code)

```
/plugin marketplace add <usuario-github>/agentes-clan-digital
/plugin install agente-gestoria@agentes-clan-digital
```

Después, escribe `/instalar-agente-gestoria` y sigue los pasos.

## Agentes

| Plugin | Qué hace | Comandos |
|---|---|---|
| `agente-gestoria` | Contabilidad e impuestos para autónomos: rutina diaria que lleva el Excel, busca facturas y avisa por email. | `/instalar-agente-gestoria`, `/revisar-agente-gestoria` |

## Para Clan Digital

- Sube `version` en `plugins/<agente>/.claude-plugin/plugin.json` en cada cambio que deba llegar a los clientes, y apúntalo en el Registro de cambios de Notion.
- Aquí no van nunca datos de clientes ni claves.
