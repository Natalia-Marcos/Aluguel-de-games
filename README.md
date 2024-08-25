# 🎮 AluGames - Aluguel de Boardgames

Bem-vindo ao **AluGames**! Este projeto foi desenvolvido para gerenciar o aluguel de boardgames em uma interface interativa. Você pode ver o status atual dos jogos e alternar entre as opções de "Alugar" e "Devolver" de forma dinâmica.

## 🎨 Tecnologias Utilizadas

- **HTML**: Estrutura da página.
- **CSS**: Estilização e layout dos itens do dashboard.
- **JavaScript**: Lógica de funcionamento para alterar o status dos jogos e atualizar a interface.

## 🛠️ Funcionalidades

- **Alugar e Devolver Jogos**: Clique no botão de um jogo para alternar seu status entre "Alugar" e "Devolver".
- **Atualização Visual**: A imagem do jogo e o botão de ação são atualizados dinamicamente para refletir o status atual (disponível ou alugado).

## 💻 Como Funciona

1. **Identificação do Jogo**: O jogo é identificado pelo seu `id` no HTML, permitindo que as mudanças sejam aplicadas ao item correto na interface.
2. **Alteração de Status**: A função `alterarStatus(id)` em JavaScript verifica se o jogo está alugado ou disponível. Dependendo do estado atual, ela adiciona ou remove classes CSS específicas e altera o texto do botão.
3. **Manipulação de DOM**: Utilizando `querySelector`, os elementos da interface (como a imagem e o botão) são selecionados e modificados conforme necessário para refletir o status do jogo.

## 📸 Screenshot

![Dashboard de Aluguel de Jogos](https://github.com/user-attachments/assets/28d846cf-cb84-4000-aee7-3461e0c74486)

*Adicione aqui uma captura de tela do projeto.*

## 📝 Observações

- **Classes Dinâmicas**: A função utiliza classes CSS como `dashboard__item__img--rented` e `dashboard__item__button--return` para alterar o estilo visual do jogo conforme o status.
- **Atualização do Botão**: O texto do botão alterna entre "Alugar" e "Devolver", oferecendo uma experiência de usuário intuitiva.
- **Responsividade**: O layout é adaptado para diferentes tamanhos de tela, garantindo acessibilidade em dispositivos móveis.

## 🚀 Como Executar

Para visualizar e testar o projeto, basta abrir o arquivo `index.html` no seu navegador.

## 🖼️ Design

O design do projeto é moderno e atrativo, com elementos visuais como linhas divisoras e hachuras que complementam a interface, proporcionando uma experiência agradável ao usuário.

---

Feito com ❤️ por Natália
