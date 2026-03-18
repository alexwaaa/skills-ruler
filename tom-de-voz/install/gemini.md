# Instalação — Tom de Voz no Gemini

## Opção A: Gems (agente dedicado)

1. Acesse **Gemini → Gems → Create a Gem**
2. Cole no campo de instruções o conteúdo completo do arquivo `SKILL.md`, disponível em:

```
https://raw.githubusercontent.com/alexwaaa/skills-ruler/main/tom-de-voz/SKILL.md
```

Abra o link, selecione tudo (Cmd+A ou Ctrl+A) e cole no campo.

> **Recomendado:** colar o conteúdo diretamente, sem depender da URL em tempo de execução. Nem todos os modelos conseguem acessar links externos de forma confiável.

---

## Observação

O Gemini não suporta Ruler MCP nativamente. Sem essa integração, o agente não consegue consultar as diretrizes oficiais de tom de voz em tempo real — ele operará apenas com o conteúdo colado nas instruções.

Para uso completo com diretrizes sempre atualizadas, use o Claude com Ruler MCP conectado.
