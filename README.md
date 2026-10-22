# Estrelas da Ciência

Releitura de *Space Invaders* sobre mulheres na ciência. Cada rodada traz uma pergunta e quatro naves (A–D),
uma por alternativa. Atire na nave da resposta certa. Partida de 6 rodadas, até ~2 minutos.

- **Controles:** setas movem, espaço (ou Z) atira. Apelido: ↑↓ letra, → avança, ← apaga, Enter confirma, X pula.
- **Errar custa pontos, nunca a partida**, e a resposta certa aparece com uma linha de explicação.
- **Placar:** ao fim, envia a mensagem `PLACAR` ao fliperama (`window.parent.postMessage`). O jogo não guarda nada.
- **Banco de questões:** `questoes.json` (28 questões, 6 sorteadas por partida, sem repetir).
