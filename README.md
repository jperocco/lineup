# Lineup Alerta

Página única (HTML + JavaScript, sem build) que escaneia todas as suas ligas do Sleeper numa semana e aponta titulares com projeção baixa ou de bye.

## Como usar

Abra o `index.html` no navegador (ou publique pelo GitHub Pages), digite seu username ou user_id do Sleeper e clique em **Escanear**.

- **Limite:** destaca titulares abaixo de 3, 5, 8 ou 10 pontos projetados.
- **Pontuação:** PPR completo, meio PPR ou Standard.
- **Semana:** deixe em branco para usar a semana atual da temporada.

## Limitações

- As projeções vêm do endpoint que o próprio app do Sleeper usa (`api.sleeper.com`), que não é oficial e pode mudar. Podem não bater com FantasyPros, ESPN etc.
- A pontuação é a padrão escolhida (PPR / meio / Standard), não a pontuação personalizada de cada liga.
- Na primeira execução a página baixa a lista de jogadores do Sleeper (~5 MB).
