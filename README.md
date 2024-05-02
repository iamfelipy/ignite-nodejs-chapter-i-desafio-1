# API "Criação de tarefas associadas a usuários"

Este projeto de Node.js com Express, desenvolvido para meu portfólio, permite a criação de usuários e o gerenciamento de tarefas associadas a eles. Com uma API simples e eficiente, os usuários podem facilmente criar, visualizar, atualizar e excluir tarefas. Além disso, o projeto inclui testes automatizados usando o framework Jest, garantindo a confiabilidade e estabilidade da aplicação.

## Tecnologias Utilizadas

- NODE
- JAVASCRIPT
- EXPRESS
- JEST

## Funcionalidades

1. Cadastro de Usuário:
- O sistema deve permitir que um novo usuário seja criado.
- O sistema não deve permitir a criação de um novo usuário quando o nome de usuário já existe.
2. Gerenciamento de Tarefas (Todo):
- O sistema deve ser capaz de listar todas as tarefas de um usuário.
- O sistema deve permitir a criação de uma nova tarefa para um usuário.
- O sistema deve permitir a atualização de uma tarefa existente.
- O sistema não deve permitir a atualização de uma tarefa que não existe.
- O sistema deve permitir marcar uma tarefa como concluída.
- O sistema não deve permitir marcar uma tarefa que não existe como concluída.
- O sistema deve permitir excluir uma tarefa.
- O sistema não deve permitir excluir uma tarefa que não existe.

## Testes

1. Teste de Criação de Usuário:
- Testar se é possível criar um novo usuário com dados válidos.
- Testar se não é possível criar um novo usuário com um nome de usuário que já existe no sistema.
2. Teste de Gerenciamento de Tarefas (Todo):
- Testar se é possível listar todas as tarefas de um usuário.
- Testar se é possível criar uma nova tarefa para um usuário.
- Testar se é possível atualizar uma tarefa existente.
- Testar se não é possível atualizar uma tarefa que não existe.
- Testar se é possível marcar uma tarefa como concluída.
- Testar se não é possível marcar uma tarefa que não existe como concluída.
- Testar se é possível excluir uma tarefa.
- Testar se não é possível excluir uma tarefa que não existe.

## Instalação e execução do projeto

Clone o projeto

```bash
  git clone https://github.com/iamfelipy/ignite-nodejs-chapter-i-desafio-1
```

Entre no diretório do projeto

```bash
  cd  ignite-nodejs-chapter-i-desafio-1
```

Instale as dependências

```bash
  npm install
```

Inicie o servidor

```bash
  npm run dev
```
