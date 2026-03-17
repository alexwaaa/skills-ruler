# Exemplos de Uso — Geração de Imagem

## Modo Criticar

**Prompt do usuário:**
> "Avaliei essa imagem gerada para um post: mulher sorrindo em frente a um fundo branco neutro, segurando um cartão de crédito para a câmera."

**O que o agente faz:**
Consulta `consultar_marca(tema="fotografia")` e `listar_assets(tipo="imagens")` para comparar com referências da marca.

**Output esperado:**
```
✅ Pontos em conformidade
- Presença de pessoa representando o público da Cent
- Expressão positiva alinhada ao tom energizante da marca

⚠️ Pontos de atenção
- Fundo branco neutro é genérico — a Cent evita ambientes estéreis
- Pose "segurando produto para câmera" é artificial e de stock photo
- A imagem comunica "produto bancário" em vez de "conquista pessoal"

💡 Sugestões
- Substituir o fundo por um ambiente cotidiano e autêntico (café, escritório em casa, espaço urbano)
- Remover a pose com cartão — mostrar a pessoa em um momento natural de rotina ou conquista
- Referência de estilo: [URLs das imagens da marca retornadas por listar_assets]
```

---

## Modo Ajustar

**Prompt do usuário:**
> "Ajuste esse prompt para o Midjourney: 'young woman smiling, holding credit card, white background, professional photo'"

**O que o agente faz:**
Consulta as diretrizes, identifica os problemas e reescreve.

**Output esperado:**
```
Prompt ajustado (Midjourney):
young Brazilian woman in her late 20s, casual authentic moment at home or urban cafe, 
natural expression of quiet confidence, warm vibrant colors aligned with modern fintech 
brand palette, clean composition with breathing room, candid lifestyle photography style, 
natural lighting, --ar 4:5 --style raw --v 6

O que foi mudado:
- Removido "holding credit card" — pose artificial, de stock photo
- Substituído "white background" por ambiente cotidiano autêntico
- Adicionado "candid lifestyle photography" para guiar o estilo
- Adicionado parâmetros técnicos do Midjourney (ar, style, version)
- Especificado perfil demográfico alinhado ao público da Cent
```

---

## Modo Criar (agente sem geração de imagem)

**Prompt do usuário:**
> "Preciso de uma imagem para o Instagram da Cent mostrando o momento em que alguém percebe que seu investimento cresceu. Vou usar o Midjourney."

**O que o agente faz:**
Consulta `consultar_marca(tema="fotografia")`, `listar_assets(tipo="imagens")` e `listar_assets(tipo="mural")`, e cria o prompt completo.

**Output esperado:**
```
Prompt criado (Midjourney):
young Brazilian man in his late 20s, sitting at kitchen table with phone in hand, 
subtle expression of pleasant surprise and satisfaction, morning light through window, 
warm tones with vibrant accents, authentic casual home environment, 
lifestyle photography, candid moment, clean composition, 
--ar 1:1 --style raw --v 6 --q 2

Como usar:
1. Acesse midjourney.com ou o Discord do Midjourney
2. Use o comando /imagine e cole o prompt acima
3. Gere 4 variações e escolha a que melhor captura o momento autêntico

Referências visuais da marca para calibrar sua escolha:
[URLs retornadas por listar_assets — imagens de referência da Cent]
```

---

## Modo Criar (agente com geração de imagem)

**Prompt do usuário:**
> "Crie uma imagem para o Instagram da Cent: jovem celebrando uma conquista financeira."

**O que o agente faz:**
Consulta as diretrizes, cria o prompt internamente e gera a imagem diretamente.

**Output esperado:**
```
[imagem gerada]

Prompt usado:
young Brazilian woman, early 30s, quiet joyful expression of personal achievement, 
urban outdoor setting, warm natural light, vibrant brand-aligned colors, 
candid lifestyle photography, clean composition --ar 1:1

Se quiser ajustes, me diga o que mudar — posso gerar novas variações.
```
