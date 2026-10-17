# 🎱 Sinuca da Galera

Sinuca de 8 bolas com **poderes** e personagens, no estilo do 8 Ball Pool. Jogue contra a CPU ou em 2 jogadores no mesmo teclado. Um único arquivo (`index.html`), sem dependências.

## Controles
| Tecla | Ação |
|---|---|
| A / D, W / S ou setas | Gira o taco em volta da bola branca (Shift esquerdo = ajuste fino) |
| Rodela "MIRA FINA" (lado direito) | Arraste em círculo (mouse ou toque) pra girar o taco bem devagar: uma volta da rodela ≈ 12,6° do taco. A roda do mouse sobre ela dá passos de ~0,1° |
| Espaço | Trava a mira e abre o ajuste de força; Espaço de novo dá a tacada |
| Q / E | Diminui / aumenta a força |
| Enter | Ativa o poder (quando a barra está cheia e piscando) |
| M | Liga/desliga o som |
| Esc | Volta ao menu |

## Personagens e poderes
- **Marcelo – Ímã:** a bola atingida curva em direção à caçapa mais próxima.
- **Bahia – Sorte:** +30% de chance de derrubar uma bola extra.
- **Prado – Mira precisa:** guia completo da mira e tacada sem erro.
- **Obata – Persuasão:** o rival tem 25% de chance de errar a tacada.
- **Vini – Foco:** a mira melhora a cada tacada (com limite); o poder dá precisão total.
- **Felipe Ori – Salto:** a bola branca salta por cima da primeira bola.

A barra de poder enche com as tacadas (+34%) e com as bolas derrubadas (+20% cada), e **pisca** quando está carregada.

## Ajustes de jogo (no topo do `index.html`)
- `F` e `C`: atrito das bolas (menor = a bola corre mais). `VMIN`/`VSPAN`: velocidade da tacada fraca/forte.
- `PK`: posição e raio de captura das caçapas.
