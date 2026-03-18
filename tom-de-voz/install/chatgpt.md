# Instalação — Tom de Voz no ChatGPT

## Opção A: Custom Instructions (uso pessoal)

1. Acesse **Settings → Personalization → Custom Instructions**
2. No campo "How would you like ChatGPT to respond?", cole o conteúdo completo do arquivo `SKILL.md` desta skill, disponível em:

```
https://raw.githubusercontent.com/alexwaaa/skills-ruler/main/tom-de-voz/SKILL.md
```

Abra o link, selecione tudo (Cmd+A ou Ctrl+A) e cole no campo.

> **Recomendado:** colar o conteúdo diretamente, sem depender da URL em tempo de execução. Nem todos os modelos conseguem acessar links externos de forma confiável.

---

## Opção B: GPT Builder (agente dedicado)

1. Acesse **Explore GPTs → Create a GPT**
2. Na aba **Configure**, cole no campo **Instructions** o conteúdo completo do arquivo `SKILL.md`:

```
https://raw.githubusercontent.com/alexwaaa/skills-ruler/main/tom-de-voz/SKILL.md
```

---

## Observação

O ChatGPT não suporta Ruler MCP nativamente. Sem essa integração, o agente não consegue consultar as diretrizes oficiais de tom de voz em tempo real — ele operará apenas com o conteúdo colado nas instruções.

Para uso completo com diretrizes sempre atualizadas, use o Claude com Ruler MCP conectado.
