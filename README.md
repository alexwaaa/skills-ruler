# skills-ruler

Skills de marca da Cent para agentes de IA. Cada skill especializa um agente em uma tarefa específica de criação, análise ou validação de materiais alinhados às diretrizes da marca.

## Como funciona

Cada skill é uma **habilidade casca** instalada no seu agente de IA. A casca é leve — ela define o papel do agente e aponta para as instruções completas neste repositório. Quando a skill evolui, todos os agentes já consomem a versão atualizada automaticamente, sem reinstalação.

## Pré-requisito

Todas as skills dependem do **Ruler MCP** conectado ao seu agente. O Ruler MCP é o servidor oficial de marca da Cent — ele fornece as diretrizes, documentos e assets que as skills consomem.

Configure o Ruler MCP em:
```
https://web-production-ee615a.up.railway.app/mcp
```

## Skills disponíveis

| Skill | O que faz | Status |
|---|---|---|
| [tom-de-voz](./tom-de-voz/) | Cria, critica e ajusta textos com o tom de voz da Cent | ✅ Ativa |
| [geracao-imagem](./geracao-imagem/) | Cria, critica e ajusta prompts de geração de imagem alinhados à marca | ✅ Ativa |
| [layout-check](./layout-check/) | Avalia layouts com score 0-100% por categoria de marca | 🔜 Em breve |
| [consumer](./consumer/) | Mapeia fluxos de nurture, emails e segmentação por persona | 🔜 Em breve |
| [compliance](./compliance/) | Valida materiais publicitários contra regulações de fintech | 🔜 Em breve |

## Como instalar uma skill

Cada skill tem uma pasta `/install` com instruções específicas para cada plataforma:

```
[skill]/
└── install/
    ├── claude.md       ← Claude (claude.ai)
    ├── chatgpt.md      ← ChatGPT
    ├── gemini.md       ← Gemini
    ├── midjourney.md   ← Midjourney
    ├── photoshop.md    ← Adobe Photoshop
    └── figma.md        ← Figma
```

Acesse a pasta da skill desejada e siga o guia da sua plataforma.
