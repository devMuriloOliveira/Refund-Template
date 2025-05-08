# Projeto de Reembolso

Este é um site simples de reembolso desenvolvido com JavaScript. O propósito principal deste projeto é praticar conceitos importantes de JavaScript, como manipulação do DOM, eventos, formatação de valores e cálculos. 

## Funcionalidades

- **Adicionar Despesas**: O usuário pode adicionar uma nova despesa, informando o nome da despesa, a categoria e o valor.
- **Visualizar Total**: O valor total das despesas é calculado automaticamente e exibido no topo da página.
- **Remover Itens**: O usuário pode remover despesas da lista clicando no ícone de remover ao lado de cada item.
- **Formatação de Valores**: O valor das despesas é formatado como moeda brasileira (BRL) automaticamente.
- **Validação de Valores**: Apenas valores válidos são considerados para os cálculos e a atualização do total.

## Funcionalidades Técnicas Usadas

- **Manipulação do DOM**: Usada para criar, modificar e remover elementos HTML dinamicamente.
- **Eventos**: O site captura interações do usuário, como o envio do formulário e o clique para remover itens da lista.
- **Formatação de Moeda**: O valor das despesas é formatado no formato de moeda brasileiro (R$) usando `toLocaleString`.
- **Cálculos**: O total das despesas é atualizado em tempo real ao adicionar ou remover itens.
- **Validação**: O código valida se o valor das despesas é um número válido antes de realizar cálculos.

## Como Usar

1. Adicione o nome da despesa no campo "Despesa".
2. Selecione a categoria da despesa no campo "Categoria".
3. Insira o valor da despesa no campo "Valor".
4. Clique em "Adicionar" para registrar a despesa na lista.
5. O valor total será atualizado automaticamente.
6. Para remover uma despesa, clique no ícone de remoção ao lado da despesa.

## Tecnologias Usadas

- **HTML**: Estrutura do site.
- **CSS**: Estilização da página.
- **JavaScript**: Funcionalidades interativas e manipulação do DOM.
