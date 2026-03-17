# Instalação — Tom de Voz no Claude (claude.ai)

## Pré-requisito

Conecte o Ruler MCP em **Settings → Connectors → +** e cole a URL:
```
https://web-production-ee615a.up.railway.app/mcp
```

---

## Instalação da skill

Acesse **Settings → Habilidades → +** e preencha os três campos:

---

**Nome da skill:**
```
Tom de Voz — Cent
```

---

**Descrição:**
```
Especialista em redação de marca da Cent. Use quando precisar criar, criticar ou ajustar textos para garantir alinhamento com o tom de voz da marca. Exemplos: "crie uma legenda para o Instagram", "esse texto está no tom da Cent?", "ajuste esse email para soar mais humano".
```

---

**Instruções:**

Cole o conteúdo completo do arquivo `SKILL.md` desta skill, disponível em:
```
https://raw.githubusercontent.com/alexwaaa/skills-ruler/main/tom-de-voz/SKILL.md
```

Abra o link, selecione tudo (Cmd+A) e cole no campo Instruções.

---

Clique em **Criar**.

---

## Como usar

Com o Ruler MCP ativo na conversa, descreva sua tarefa normalmente. A skill é ativada automaticamente quando o Claude identifica que a tarefa envolve criação, crítica ou ajuste de texto da marca Cent.

Exemplos de prompts:
- "Crie uma legenda para o Instagram da Cent anunciando o lançamento de uma nova feature"
- "Esse texto está no tom da Cent? [cole o texto]"
- "Ajuste esse email para soar menos formal e mais próximo"
