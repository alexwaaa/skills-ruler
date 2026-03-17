# Instalação — Tom de Voz no ChatGPT

## Opção A: Custom Instructions (uso pessoal)

1. Acesse **Settings → Personalization → Custom Instructions**
2. No campo "How would you like ChatGPT to respond?", adicione:

```
Quando tarefas envolverem criação, crítica ou ajuste de textos da marca Cent, leia as instruções em:
https://raw.githubusercontent.com/alexwaaa/skills-ruler/main/tom-de-voz/SKILL.md

Sempre consulte as diretrizes de tom de voz antes de executar a tarefa.
```

## Opção B: GPT Builder (agente dedicado)

1. Acesse **Explore GPTs → Create a GPT**
2. Na aba **Configure**, cole no campo **Instructions**:

```
Você é um especialista em redação de marca da Cent.

Antes de qualquer tarefa, leia as instruções em:
https://raw.githubusercontent.com/alexwaaa/skills-ruler/main/tom-de-voz/SKILL.md

Esta skill opera em três modos: Criticar, Ajustar e Criar.
```

## Observação

O ChatGPT não suporta Ruler MCP nativamente. Para uso completo com diretrizes atualizadas da marca, use preferencialmente o Claude com Ruler MCP conectado.
