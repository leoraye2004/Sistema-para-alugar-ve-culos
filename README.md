# Sistema de Aluguel de Veículos

## Requisitos Funcionais
- **RF01**: Cadastro de usuários (clientes e administradores).
- **RF02**: Cadastro de veículos disponíveis para aluguel.
- **RF03**: Consulta de veículos por categoria, preço e disponibilidade.
- **RF04**: Reserva e confirmação de aluguel de veículos.
- **RF05**: Geração de relatórios sobre os alugueis realizados.
- **RF06**: Controle de status dos veículos (disponível, alugado, em manutenção).

## Requisitos Não Funcionais
- **RNF01**: Interface responsiva para dispositivos móveis e desktop.
- **RNF02**: Armazenamento dos dados em um banco de dados.
- **RNF03**: Autenticação e segurança dos dados dos usuários.
- **RNF04**: Boa performance no carregamento das páginas.
- **RNF05**: Código bem estruturado para facilitar futuras manutenções.

## Estratégias de Desenvolvimento
O sistema será desenvolvido utilizando uma arquitetura monolítica, pois trata-se de um sistema relativamente simples, onde a separação por módulos independentes não se faz necessária. Dessa forma, todo o back-end será centralizado em um único projeto utilizando **Node.js** e **Express**.

## Tecnologias Utilizadas e Justificativas

### Front-end
- **HTML, CSS e JavaScript**: Garantem uma interface responsiva e dinâmica, permitindo a interação do usuário com o sistema de forma intuitiva.

### Back-end
- **Node.js com Express**: Usado para a criação de uma API leve e eficiente, capaz de gerenciar as operações do sistema, como cadastro de usuários e veículos, reserva e geração de relatórios.

### Banco de Dados
- **MySQL**: Banco de dados relacional utilizado para armazenar as informações de usuários, veículos e transações de aluguel de forma estruturada e segura.

## Plano de Trabalho

- **Prototipagem Front-end**: Desenvolvimento do protótipo das páginas. - _Responsável: Wellerson_
- **Front-end**: Desenvolvimento da interface e interação com o usuário. - _Responsáveis: Ambos_
- **Back-end**: Criação das APIs para gerenciar usuários, veículos e reservas. - _Responsável: Wellerson_
- **Banco de Dados**: Estruturação do armazenamento dos dados. - _Responsável: Leo_
- **Autenticação**: Implementação do Firebase Authentication. - _Responsável: Leo_
- **Testes e Ajustes**: Verificação de bugs e otimização do sistema antes da apresentação. - _Responsáveis: Ambos_
