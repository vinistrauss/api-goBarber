# ALGUNS ENSINAMENTOS

<font color="blue"> <h3> COMANDOS BÁSICOS DO DOCKER </h3> </font>

```
  docker ps : Lista todos os containers ativos
  docker ps -a: Lista todos os containers ativos e inativos
  docker stop <id ou name> : Para o container
  docker rm <id ou name>: exclue o container
  docker start <id ou name>: reinicia o container
  docker logs <id ou name>: exibe o log dos container

```

<font color="gray"> <h3> COMANDOS BÁSICOS DO MIGGRATION </h3> </font>

```
  yarn add sequelize-cli -D
  criar -  yarn sequelize migration:create --name=create-users
  adicionar  - yarn sequelize db:migrate
  excluir uma anterior - yarn sequelize db:migrate:undo
  excluir todas - yarn sequelize db:migrate:undo:all
  excluir um específica - yarn sequelize db:migrate:undo:all --to XXXXXXXXX-create-users.js

```

<font color="purple"> <h3> COMANDOS BÁSICOS O ESLINT </h3> </font>

```
  yarn add eslint
  yarn eslint --init
  yarn add prettier eslint-config-prettier eslint-plugin-prettier -D
  yarn eslint --fix src --ext .js

```

<font color="yellow"> <h3> MÉTODOS QUE UM CONTROLLER PODE TER </h3> </font>

```
  index() - listagem de usuários
  show() - exibir um unico usuário
  store() - cadastrar usuário
  update() - atualizar usuário
  delete() - deletar usuário

  ALÉM desses métodos tem que ser da mesma entidade

```
