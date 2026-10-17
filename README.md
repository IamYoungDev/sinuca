# 🎱 Sinuca da Galera

Sinuca de 8 bolas com **personagens e habilidades**, no estilo do 8 Ball Pool. Jogue contra a CPU ou em 2 jogadores no mesmo teclado. Um único arquivo (`index.html`), sem dependências.

## Controles
| Tecla | Ação |
|---|---|
| A / D, W / S ou setas | Gira o taco em volta da bola branca (Shift esquerdo = ajuste fino) |
| Espaço | Trava a mira e abre o ajuste de força; Espaço de novo dá a tacada |
| Q / E | Diminui / aumenta a força |
| Enter | Ativa a habilidade **ativa** (barra cheia e piscando) |
| M | Liga/desliga o som |
| Esc | Volta ao menu |

A linha branca da mira é contínua até encostar numa bola ou parede.

## Habilidades
**Passivas** ficam ligadas a partida inteira. **Ativas** usam a barra de poder, que enche com as tacadas e bolas derrubadas e pisca quando está carregada. O poder dura uma tacada.

| Personagem | Passiva | Ativa |
|---|---|---|
| Marcelo | Ímã: a bola atingida é atraída para a caçapa mais próxima | Tabela: a linha da mira continua após bater nas laterais |
| Bahia | Sorte: 45% de a bola atingida rolar até cair numa caçapa | — |
| Prado | Mira firme: 60% menos erro na tacada | Trajetória: mostra o caminho pontilhado de toda a jogada |
| Obata | Persuasão: 25% de chance de o rival errar a tacada | Super força: tacada com o dobro de força |
| Vini | Foco: a mira melhora a cada tacada (com limite) | — |
| Felipe Ori | — | Salto: a bola branca pula por cima da primeira bola |

## Faltas
- Atingir primeiro a bola do rival: a menor bola do rival em mesa cai.
- Derrubar uma bola do rival: a menor bola do rival em mesa também cai.
- Branca na caçapa ou nenhum contato: passa a vez.
