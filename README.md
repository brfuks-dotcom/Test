# Test

Páginas estáticas publicadas via GitHub Pages (deploy automático a cada push na `main`).

## 🏆 [`torneio.html`](torneio.html) — Chaveamento Nintendo Switch Sports

Aplicativo web para organizar campeonatos dos jogos do Nintendo Switch Sports.

- **Modalidades**: as 8 do jogo — Boliche, Tênis, Badminton, Vôlei, Futebol, Espada (Chambara), Golfe e Basquete — mais um campo livre para qualquer outro jogo.
- **Participantes**: nome + foto opcional — toque no quadrado 📷 para escolher da galeria ou tirar na hora no celular. A imagem é recortada e redimensionada no próprio navegador; sem foto, gera um avatar com as iniciais. Dá para trocar a foto depois clicando no avatar de quem já está na lista.
- **Dois formatos**: *chave eliminatória* (confrontos 1 x 1) ou *pontuação corrida* (todos jogam juntos e o placar decide). Boliche e golfe já abrem em pontuação corrida e as demais modalidades em chave, mas dá para trocar a qualquer momento.
- **Pontuação corrida**: sorteia a ordem de jogo, você digita a pontuação final de cada um e a classificação se atualiza sozinha. O campeão é anunciado quando todos tiverem pontuado; empate na liderança é sinalizado em vez de eleger um vencedor arbitrário.
- **Critério de vitória** por modalidade: no boliche vence quem faz mais pontos; no golfe, quem faz menos tacadas (aceita valores negativos, abaixo do par). O critério é ajustável por um seletor.
- **Limite de jogadores por partida**: o golfe comporta 4 por partida, então a competição não inicia com mais que isso — o limite vale só na pontuação corrida, em que todos jogam juntos.
- **Sorteio aleatório** das chaves. Quando o número de participantes não é potência de 2, alguns recebem **BYE** e avançam direto.
- **Avanço da chave**: toque no ✓ do vencedor da partida — ou digite o placar dos dois, que quem fizer mais pontos avança sozinho. O vencedor sobe para a rodada seguinte; tocar de novo no ✓ desfaz o resultado e invalida as fases posteriores que dependiam dele.
- **Placar** por partida (opcional, mas define o vencedor quando preenchido nos dois lados), disputa de 3º lugar e pódio com campeão, vice e terceiro.
- **Histórico**: com a final decidida, salve o campeonato. A aba *Histórico* lista todos os campeonatos já realizados, com data, modalidade, pódio e a chave completa de cada um. Inclui exportar/importar backup em JSON.
- **Ranking geral**: soma todos os campeonatos salvos e mostra títulos, vices, 3º lugares, vitórias, derrotas e aproveitamento de cada participante.
- Tudo é salvo no navegador (`localStorage`) — dá para fechar e voltar depois. Botão de impressão para gerar a chave em papel.

Não depende de servidor nem de bibliotecas externas: é um único arquivo HTML.

## 🕵️ [`dicionario-mentiroso.html`](dicionario-mentiroso.html) — Dicionário Mentiroso

Jogo de festa para jogar passando o celular entre os participantes.

- A cada rodada, sorteia-se uma palavra rara do dicionário embutido. Todos os jogadores, exceto quem sorteou, escrevem uma definição falsa tentando soar convincente.
- Todos votam em qual definição, entre as falsas e a verdadeira, acham que é a real.
- **Pontuação**: quem engana outro jogador (recebe voto na sua definição falsa) ganha 1 ponto por voto; quem acerta a definição real ganha 2 pontos; se ninguém acertar, quem sorteou a palavra ganha 3 pontos de bônus.
- Suporta qualquer número de jogadores a partir de 3, com placar persistente entre rodadas e tela final com o vencedor.
- Visual com tema de dossiê/interrogatório, com suporte a tema claro e escuro.

Não depende de servidor nem de bibliotecas externas: é um único arquivo HTML.

## 🎲 [`index.html`](index.html) — Dashboard Yatzi Analytics

Dashboard de estatísticas das partidas de Yatzi.
