Um projeto focado na criação de testes end-to-end de forma simples, visando o treinamento dessa cultura de testes.

## 🤓 Antes de começar

O objetivo deste projeto é que você analise um código já existente e desenvolva testes para ele. Para isso, você precisa ter:

- Node.js instalado na máquina.
- Um editor de código, como Visual Studio Code.
- Conhecimento básico de HTML, CSS e JavaScript.
- Familiaridade com manipulação do DOM e eventos em JavaScript.
- Noções de como configurar e executar um servidor local para desenvolvimento. Recomendamos que use a extensão do live-server.

Para instalar as dependências:

Utilize `npm install` e depois para rodar os testes `npx playwright test`

Caso tenha dúvidas sobre algum desses tópicos, entre em contato conosco [discord](https://codante.io/#:~:text=PRO-,Entre%20na%20Comunidade,-Junte%2Dse%20%C3%A0)! 


## 🔨 Requisitos

### Requisito 1
Crie os seguintes testes:
- Verificar se o dropdown carrega corretamente com as opções `['Todos', 'Frutas', 'Comidas', 'Doces']`.
- Verificar se ao selecionar 'Frutas', mostra as 3 opções existentes `['Maçã', 'Banana', 'Laranja']`.
- Verificar se ao selecionar 'Comidas', mostra as 5 opções existentes `['Frango Grelhado (100g)', 'Arroz Cozido (100g)', 'Pizza', 'Hambúrguer', 'Sushi']`.
- Verificar se ao selecionar 'Doces', mostra as 3 opções existentes `['Sorvete', 'Bolo', 'Chocolate']`.


### Requisito 2
Para o requisito 2, crie os seguintes testes:
- Verificar se o dropdown carrega corretamente com as opções de frutas `['Limão', 'Laranja', 'Morango']` e destilados `['Rum', 'Vodka', 'Gin']`.
- Verificar se ao selecionar 'Limão' e 'Rum', o drink correto `Daiquiri` é exibido com a descrição e imagem corretas.
- Verificar se ao selecionar 'Laranja' e `Vodka`, o drink correto `Screwdriver` é exibido com a descrição e imagem corretas.
- Verificar se ao selecionar 'Morango' e `Gin`, o drink correto `Strawberry Martini` é exibido com a descrição e imagem corretas.

### Requisito 3
Nesse último requisito, crie os seguintes testes:
- Verificar se a lista de alimentos carrega corretamente.
- Verificar se ao selecionar um alimento, ele é adicionado à lista de selecionados.
- Verificar se ao selecionar múltiplos alimentos, o total de calorias é atualizado corretamente.
- Verificar se ao remover um alimento, o total de calorias é atualizado corretamente.

Se quiser ir além, crie outros testes!


## 👉🏽 Sobre esse mini-projeto

### O que você irá praticar:

#### Testes com playwright

- Automação com testes end-to-end
- Validação de Conteúdo Visual

#### Javascript

- Leitura e entendimento do código alheio
- Manipulação do DOM
- Eventos e funções

### Pré requisitos

- Conhecimento básico de HTML, CSS e JavaScript.
- Experiência com bibliotecas de testes end-to-end, como Playwright ou Cypress.
- Familiaridade com manipulação do DOM e eventos em JavaScript.
- Noções de como configurar e executar um servidor local para desenvolvimento.
