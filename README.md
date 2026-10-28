# Qual o seu partido?

Teste rápido, em linguagem simples, para descobrir quais partidos políticos brasileiros mais se aproximam do seu jeito de pensar. Foi feito para quem nunca teve contato com política conseguir responder.

## Como funciona

- 15 frases sobre economia, trabalho, segurança, costumes e meio ambiente.
- Para cada frase, a pessoa escolhe de "Concordo muito" a "Discordo muito", ou pula.
- As respostas geram uma posição em dois eixos:
  - **Economia:** mais Estado ↔ mais mercado
  - **Costumes:** progressista ↔ conservador
- O resultado compara essa posição com a de 19 partidos e mostra os 3 mais próximos, um mapa e o ranking completo.
- No final, dá para baixar uma imagem do resultado nos formatos Feed (1080 × 1350) e Story (1080 × 1920) do Instagram, ou copiar um texto pronto.

## Equilíbrio

- As frases se dividem igualmente entre ideias associadas à esquerda e à direita.
- As descrições dos partidos são neutras.
- As posições dos partidos são aproximadas, baseadas em programas oficiais e no histórico de votações. Todo partido tem alas internas diferentes.
- O teste não é recomendação de voto.

## Publicar com GitHub Pages

1. Abra **Settings → Pages** neste repositório.
2. Em **Source**, escolha **Deploy from a branch**.
3. Selecione a branch **main** e a pasta **/ (root)** e salve.
4. Em alguns minutos o teste fica disponível em `https://amauridomingoos.github.io/qual-o-seu-partido/`.

## Arquivos

- `index.html`: o teste completo, em um único arquivo (HTML, CSS e JavaScript), sem dependências além das fontes do Google Fonts.

## Atualizar as posições dos partidos

As posições ficam na lista `P` dentro do `index.html`. Cada partido tem:

- `e`: economia, de -1 (mais Estado) a 1 (mais mercado)
- `c`: costumes, de -1 (progressista) a 1 (conservador)
- `n`: número de legenda
- `f`: federação, quando houver
- `d`: descrição curta
