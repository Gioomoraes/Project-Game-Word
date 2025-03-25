# **Game Word Guessing**

Este é um projeto simples de jogo de adivinhar palavras, focado em aprendizado e aprimoramento de habilidades com **React**. O jogo permite ao usuário adivinhar palavras por meio de letras escolhidas, e a cada palavra acertada, o jogo avança mostrando novas palavras, mantendo um sistema de pontuação e possibilitando o reinício do jogo. Este projeto foi criado a partir de auxilio do curso Udemy para aprendizado do react.

## **Objetivo ⭐**

Este projeto foi criado com o objetivo de testar e aprofundar o conhecimento em React, utilizando conceitos como:

- **useState** e **useEffect** para gerenciar o estado do jogo e a renderização condicional dos componentes.
- **useCallback** para otimização das funções de escolha de palavras e categorias.
- Simulação de um sistema de rotas, alterando o componente com base no estado do jogo (início, jogo em andamento, e fim).

## **Funcionalidades ⚙️**

- **Escolha de palavras**: O jogo escolhe aleatoriamente uma palavra de uma lista, baseada em categorias.
- **Adivinhação de letras**: O usuário tenta adivinhar as letras da palavra.
- **Pontuação**: O jogador ganha pontos a cada palavra corretamente adivinhada.
- **Progressão do jogo**: O jogo avança para uma nova palavra depois de acertar todas as letras.
- **Reinício do jogo**: O jogo pode ser reiniciado a qualquer momento.

## **Tecnologias Usadas 💻**

- **JavaScript** 
- **React**: Biblioteca para construção da interface do usuário.
- **Hooks**:
  - `useState`: Para gerenciar o estado do jogo, incluindo a palavra escolhida, as letras adivinhadas, a pontuação e o estado do jogo.
  - `useEffect`: Para verificar se o jogo terminou (quando as tentativas se esgotam) ou se o jogador venceu (quando todas as letras foram adivinhadas).
  - `useCallback`: Para otimizar a função que escolhe uma palavra e categoria aleatória.

## **Como Rodar o Projeto ✔️**

1. Clone o repositório:
   ```bash
   git clone https://github.com/Gioomoraes/Project-Game-Word.git
   ```
2. Acesse o diretório do projeto:
   ```bash
   cd Project-Game-Word
   ```
3. Instale as dependências:
   ```bash
   npm install
   ```
4. Inicie
   ```bash
   npm start
   ```
   O projeto estará disponível no navegador em http://localhost:3000.

## **Licença 🔐**

Este projeto está sob a [MIT License](LICENSE).

## Autora 💜

- [@Gioomoraes](https://github.com/Gioomoraes)
