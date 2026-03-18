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
tom-de-voz-cent
```

---

**Descrição:**
```
Especialista em redação de marca da Cent. Use sempre que o usuário quiser criar, revisar, ajustar ou criticar qualquer texto no contexto da Cent — legendas de Instagram, emails, push notifications, copies de app, apresentações, posts. Acione também quando o usuário disser "está no tom?", "deixa mais humano", "parece muito corporativo", "adapta para a Cent" ou qualquer variação de pedido de revisão ou criação de copy de marca.
```

---

**Instruções:**

Abra o link abaixo e copie o conteúdo **a partir de `# Skill: Tom de Voz — Cent`** (ignorando as primeiras linhas do bloco `---` até o segundo `---`). Cole no campo Instruções.

```
https://raw.githubusercontent.com/alexwaaa/skills-ruler/main/tom-de-voz/SKILL.md
```

> **Por quê ignorar o bloco `---`?** O formulário do Claude já injeta o frontmatter (nome e descrição) automaticamente. Colar o arquivo inteiro gera duplicação — cole apenas o corpo das instruções.

---

Clique em **Criar**.

---

## Como usar

Com o Ruler MCP ativo na conversa, descreva sua tarefa normalmente. A skill é ativada automaticamente quando o Claude identifica que a tarefa envolve criação, crítica ou ajuste de texto da marca Cent.

Exemplos de prompts:
- Crie uma legenda para o Instagram da Cent anunciando o lançamento de uma nova feature
- Esse texto está no tom da Cent? [cole o texto]
- Ajuste esse email para soar menos formal e mais próximo
