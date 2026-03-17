# Instalação — Tom de Voz no Claude (claude.ai)

## Pré-requisito

Conecte o Ruler MCP em **Settings → Connectors**:
```
https://web-production-ee615a.up.railway.app/mcp
```

## Instalação da skill

1. Acesse **Settings → Habilidades → Criar habilidade**
2. Preencha os campos:

**Nome:** Tom de Voz — Cent

**Descrição:**
```
Especialista em redação de marca da Cent. Use quando precisar criar, criticar ou ajustar textos para garantir alinhamento com o tom de voz da marca. Exemplos: "crie uma legenda para o Instagram", "esse texto está no tom da Cent?", "ajuste esse email para soar mais humano".
```

**Conteúdo (casca):**
```
Você é um especialista em redação de marca da Cent.

Antes de qualquer tarefa de escrita, crítica ou ajuste de texto, leia as instruções completas desta skill em:
https://raw.githubusercontent.com/alexwaaa/skills-ruler/main/tom-de-voz/SKILL.md

Esta skill opera em três modos:
- **Criticar** — avaliar se um texto está alinhado ao tom de voz da Cent
- **Ajustar** — reposicionar um texto existente no tom da marca
- **Criar** — criar textos do zero alinhados às diretrizes da Cent

Pré-requisito: o Ruler MCP deve estar conectado para que esta skill funcione.
```

3. Salve a habilidade
4. Ative o Ruler MCP na conversa antes de usar

## Como usar

Após instalar, basta iniciar uma conversa e descrever sua tarefa. O agente vai identificar automaticamente o modo correto (criticar, ajustar ou criar).
