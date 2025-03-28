# Formulário de Cadastro de Membros da Igreja

Este projeto é um formulário de cadastro de membros de uma igreja, desenvolvido com HTML e estilizado utilizando o framework **Tailwind CSS**. O formulário é responsivo e segue boas práticas de acessibilidade e design moderno.

## Funcionalidades

- **Campos de entrada**:
  - Nome Completo
  - Data de Nascimento
  - Email
  - Telefone (com validação de formato)
  - Endereço
  - Estado Civil (opções em um menu suspenso)
  - Ministério (opções em um menu suspenso)
  - Senha (com validação de comprimento mínimo)

- **Validações**:
  - Campos obrigatórios possuem o atributo `required`.
  - O campo de telefone aceita apenas números no formato `(XX) XXXXX-XXXX` com validação via `pattern` e `inputmode="numeric"`.
  - O campo de senha exige um mínimo de 8 caracteres.

- **Botões de ação**:
  - Botão de **Cadastrar** para enviar os dados.
  - Botão de **Limpar** para resetar o formulário.

## Tecnologias Utilizadas

- **HTML5**: Estrutura do formulário.
- **Tailwind CSS**: Framework CSS utilitário para estilização moderna e responsiva.

