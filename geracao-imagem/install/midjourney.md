# Instalação — Geração de Imagem no Midjourney

O Midjourney não suporta instruções permanentes de sistema. A skill funciona como um **gerador de prompts** — você usa o Claude com a skill instalada para criar o prompt, e depois cola no Midjourney para gerar a imagem.

## Fluxo de uso

1. No Claude (com skill instalada + Ruler MCP ativo):
   > "Crie um prompt para o Midjourney de [descrição da imagem]"

2. O Claude gera o prompt técnico e completo

3. No Midjourney, use o comando:
   > /imagine [cole o prompt aqui]

## Dicas de parâmetros Midjourney para a Cent

- `--ar 1:1` para posts quadrados (Instagram feed)
- `--ar 9:16` para stories e reels
- `--ar 4:5` para posts verticais
- `--style raw` para estilo fotográfico mais realista
- `--v 6` para a versão mais atual
