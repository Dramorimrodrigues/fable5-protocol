# 🧠 Fable5 Protocol

> Protocolo de raciocínio profundo para o Claude — pensamento adaptativo, planejamento explícito, auto-teste e coerência em tarefas longas.

[![Claude Skill](https://img.shields.io/badge/Claude-Skill-orange?logo=anthropic)](https://claude.ai)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Language: PT-BR](https://img.shields.io/badge/Language-PT--BR-green.svg)](fable5-protocol.md)

---

## O que é o Fable5 Protocol?

O **Fable5 Protocol** é uma skill para o Claude que transforma o comportamento do modelo para operar com raciocínio profundo e estruturado. Em vez de responder diretamente a qualquer tarefa, o Claude com o Fable5 ativo passa por um ciclo completo de raciocínio antes de entregar qualquer output.

Fable5 tem três características definidoras:
- 🎯 **Thoroughm** — executa com profundidade, não pula etapas
- 🔍 **Proactive** — antecipa problemas antes que eles apareçam
- ✅ **Auto-testável** — verifica o próprio trabalho antes de entregar

---

## Como funciona

O protocolo ativa o seguinte ciclo de raciocínio:

```
PENSAR → PLANEJAR → EXECUTAR → VERIFICAR → REFLETIR
```

Ao final de respostas complexas, o Claude entrega automaticamente:

```
✅ Entregue: [o que foi feito]
⚠️ Incertezas: [o que não está garantido]
🔄 Próximos passos: [o que ainda pode ou deve acontecer]
```

---

## Instalação

1. Abra o [Claude](https://claude.ai)
2. Vá em **Configurações → Skills** (ou **Projetos**)
3. Crie uma nova skill
4. Cole o conteúdo do arquivo [`fable5-protocol.md`](fable5-protocol.md) como prompt da skill
5. Salve com o nome `fable5-protocol`

---

## Uso

Após instalar, ative o protocolo de duas formas:

**Pelo nome da skill:**
```
/fable5-protocol [sua tarefa aqui]
```

**Pelos atalhos de ativação:**

| Comando | Efeito |
|---------|--------|
| `fable5` | Ciclo completo ativo |
| `pense fundo` | PENSAR explícito antes de qualquer resposta |
| `concatena` | Modo de análise documental encadeada |
| `vibe` | Modo de geração iterativa de código |
| `auto-teste` | Verificação ativa do output atual antes de entregar |

---

## Casos de uso ideais

- 📄 **Análise de múltiplos documentos** — o protocolo encadeia os documentos mantendo contexto total
- 💻 **Vibe Coding** — gera código em blocos verificáveis com revisão contra o objetivo original
- ⚖️ **Tarefas jurídicas e analíticas** — extrai, sintetiza e identifica contradições entre documentos
- 🔄 **Qualquer tarefa complexa** — onde uma resposta direta seria superficial

---

## Estrutura do repositório

```
fable5-protocol/
├── README.md              # Este arquivo
└── fable5-protocol.md     # O protocolo completo (instale este)
```

---

## Licença

MIT — use, adapte e compartilhe livremente.

---

*Criado por [@Dramorimrodrigues](https://github.com/Dramorimrodrigues)*
