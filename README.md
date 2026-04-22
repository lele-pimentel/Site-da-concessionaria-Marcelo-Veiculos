## Sobre o Projeto

Este projeto foi desenvolvido para a disciplina de Ferramentas de Desenvolvimento para Web da Fatec São Caetano do Sul, ministrada pelo professor Veríssimo.

O objetivo é implementar um sistema de gerenciamento de estoque de veículos explorando conceitos de abstração, manipulação de objetos e métodos de array em JavaScript.

## Requisitos Atendidos

###  Evolução do Objeto (Abstração)

Foram adicionados os campos Preco e Cor a estrutura do objeto veiculo. A interface HTML foi atualizada para capturar esses dados no cadastro de novos veiculos.

### Logica de Negocios (Filtros)

Implementada funcao de busca que filtra o estoque por Marca. O resultado e atualizado dinamicamente na tabela inferior sem recarregar a pagina.

### Metodos de Array

Utilizada a Higher-Order Function forEach() para criar uma rotina de Reajuste de Precos. O usuario pode aplicar uma porcentagem de aumento em todos os itens do estoque de uma so vez.

## Tecnologias Utilizadas

- HTML5 para estrutura da interface
- CSS3 para estilizacao e layout responsivo
- JavaScript para logica de negocio e manipulacao do DOM
- Metodos de array: forEach, filter, find

## Funcionalidades

- Cadastro de veiculos com marca, modelo, ano, preco e cor
- Exibicao de estoque em tabela dinamica
- Filtro por marca com atualizacao instantanea
- Reajuste percentual de preco para todo o estoque
