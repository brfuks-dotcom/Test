# Test

Páginas estáticas publicadas via GitHub Pages (deploy automático a cada push na `main`).

## 🏆 [`torneio.html`](torneio.html) — Chaveamento Nintendo Switch Sports

Aplicativo web para montar torneios eliminatórios dos jogos do Nintendo Switch Sports.

- **Modalidades**: as 8 do jogo — Boliche, Tênis, Badminton, Vôlei, Futebol, Espada (Chambara), Golfe e Basquete — mais um campo livre para qualquer outro jogo.
- **Participantes**: nome + foto opcional — toque no quadrado 📷 para escolher da galeria ou tirar na hora no celular. A imagem é recortada e redimensionada no próprio navegador; sem foto, gera um avatar com as iniciais. Dá para trocar a foto depois clicando no avatar de quem já está na lista.
- **Sorteio aleatório** das chaves. Quando o número de participantes não é potência de 2, alguns recebem **BYE** e avançam direto.
- **Avanço automático**: clique no vencedor de cada partida e ele sobe para a rodada seguinte. Clicar de novo desfaz o resultado e invalida as fases posteriores que dependiam dele.
- **Placar opcional** por partida, disputa de 3º lugar e pódio com campeão, vice e terceiro.
- **Histórico**: com a final decidida, salve o campeonato. A aba *Histórico* lista todos os campeonatos já realizados, com data, modalidade, pódio e a chave completa de cada um. Inclui exportar/importar backup em JSON.
- **Ranking geral**: soma todos os campeonatos salvos e mostra títulos, vices, 3º lugares, vitórias, derrotas e aproveitamento de cada participante.
- Tudo é salvo no navegador (`localStorage`) — dá para fechar e voltar depois. Botão de impressão para gerar a chave em papel.

Não depende de servidor nem de bibliotecas externas: é um único arquivo HTML.

## 🎲 [`index.html`](index.html) — Dashboard Yatzi Analytics

Dashboard de estatísticas das partidas de Yatzi.
