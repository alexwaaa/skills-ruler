# Instalação — Geração de Imagem no Claude (claude.ai)

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
geracao-imagem-cent
```

---

**Descrição:**
```
Diretor de arte especializado na identidade visual da Cent. Use para criar prompts de geração de imagem, criticar imagens existentes ou ajustar prompts alinhados às diretrizes fotográficas da marca. Exemplos, como criar uma imagem para o Instagram da Cent, avaliar se um prompt está alinhado à marca, ajustar um prompt para o Midjourney.
```

---

**Instruções:**

Cole o conteúdo completo do arquivo `SKILL.md` desta skill, disponível em:
```
https://raw.githubusercontent.com/alexwaaa/skills-ruler/main/geracao-imagem/SKILL.md
```

Abra o link, selecione tudo (Cmd+A) e cole no campo Instruções.

---

Clique em **Criar**.

---

## Como usar

Com o Ruler MCP ativo na conversa, descreva sua tarefa normalmente. A skill é ativada automaticamente quando o Claude identifica que a tarefa envolve geração, crítica ou ajuste de imagens da marca Cent.

Exemplos de prompts:
- Crie uma imagem para o Instagram da Cent mostrando um momento de conquista financeira
- Esse prompt está alinhado à identidade visual da Cent? [cole o prompt]
- Ajuste esse prompt para o Midjourney seguindo as diretrizes da marca
