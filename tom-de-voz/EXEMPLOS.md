# Exemplos de Uso — Tom de Voz

## Modo Criticar

**Prompt do usuário:**
> "Avalie esse texto para o Instagram: 'A Cent oferece soluções financeiras inovadoras que permitem ao usuário maximizar seus retornos através de uma plataforma intuitiva e de fácil utilização.'"

**O que o agente faz:**
Consulta `consultar_marca(tema="tom-de-voz")` e identifica os problemas:
- ❌ "soluções financeiras inovadoras" — linguagem genérica e corporativa
- ❌ "maximizar retornos" — jargão financeiro que a marca evita
- ❌ "plataforma intuitiva e de fácil utilização" — redundante e sem personalidade

**Output esperado:**
```
✅ Pontos em conformidade
- A ideia central (facilidade + investimento) está alinhada ao posicionamento da Cent

⚠️ Pontos de atenção
- Vocabulário corporativo ("soluções financeiras inovadoras") destoa do tom humano e direto da marca
- "Maximizar retornos" é jargão que intimida o público-alvo da Cent
- Sem energia, sem personalidade — poderia ser de qualquer banco

💡 Sugestões de melhoria
- "Guardar dinheiro ficou mais simples. Com a Cent, você começa do zero e vai ficando mais ousado no seu ritmo."
```

---

## Modo Ajustar

**Prompt do usuário:**
> "Esse texto está muito formal para um push notification. Ajuste: 'Prezado cliente, informamos que sua rentabilidade mensal foi atualizada. Acesse o aplicativo para visualizar.'"

**O que o agente faz:**
Identifica o canal (push notification), consulta `consultar_marca(tema="tom-de-voz")` e reescreve.

**Output esperado:**
```
Texto ajustado:
"Seu dinheiro rendeu este mês 🎉 Abre o app pra ver quanto cresceu."

O que foi mudado:
- Removido "Prezado cliente" — muito formal para push
- "Rentabilidade atualizada" → "seu dinheiro rendeu" — mais humano e concreto
- Adicionado emoji para calibrar ao canal (push) e ao tom energizante da marca
- CTA direto e informal ("Abre o app") no lugar de "acesse o aplicativo"
```

---

## Modo Criar

**Prompt do usuário:**
> "Crie uma legenda para o Instagram comemorando que a Cent chegou a 100 mil clientes. Público: jovens de 20-35 anos."

**O que o agente faz:**
Consulta `consultar_marca(tema="tom-de-voz")` e `consultar_marca(tema="plataforma-de-marca")` para entender o posicionamento e as personas.

**Output esperado:**
```
Texto criado:
"100 mil pessoas que decidiram que o dinheiro delas merecia mais do que a poupança.
Obrigado por confiar que dá pra começar do jeito que você pode — e ir ficando mais ousado junto com a gente. 🌱"

Nota de tom:
Celebração sem exagero — o número é real, mas o foco é no significado dele para o cliente.
Tom empático e energizante, com linguagem direta e sem jargão financeiro.
```
