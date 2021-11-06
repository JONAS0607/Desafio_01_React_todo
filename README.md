# Comandos da aplicação

- [x] `yarn` _iniciar o projeto depois de clonado_
- [x] `yarn test` _testar o projeto_
- [x] `yarn dev` _rodar o servidor em desenvolvimento_
- [] `yarn build` _rodar o servidor em produção_

### Passos do Desafio

1. Analizar de onde vem os dados, verificar as funções que chamam e atualizam esta passagem de dados
   1. Na página inicial verificamos que temos um input e um botão os dados devem ser colocados no input acionando assim a chamada de funções que vai passar os dados verificamos que a função onClick no botão chama a função `handleCreateNewTask()`
   1. No exercício pede que caso o valor do input esteja como vazio não executamos a função para isso colocamos o valor que vem do input em uma condicional `if (!newTaskTitle) return;` caso esteja vazio retorne true por causa da negação e depois retorne sem nenhuma ação
