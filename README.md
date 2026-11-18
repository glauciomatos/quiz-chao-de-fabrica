# Quiz Chão de Fábrica

Quiz de revisão ao vivo para a UC Fundamentos dos Processos de Produção (Aulas 1 a 4).

- **Professor:** abra o site no computador do projetor. A tela mostra o QR Code, a lista de alunos e conduz as perguntas.
- **Alunos:** leem o QR Code com o celular, digitam o nome e respondem.
- O ranking é calculado no navegador do professor. As mensagens passam por um servidor MQTT público e gratuito.

As questões ficam em `questions.js`.

## Salas

- `/` — SENAI · Fundamentos dos Processos de Produção (Quiz Chão de Fábrica)
- `/gestao-de-vendas/` — ESPM · Tecnólogo em Gestão Comercial · Gestão de Vendas

Cada sala tem `questions.js` e `icons.js` próprios; o motor do jogo (`app.js`) é compartilhado e lê os textos de `window.QUIZ`.
