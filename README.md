# Exercício Concetos NodeJS

### Criado com base num template da Rocketseat.
- Testes de rotas
- Testes de funções Create, List, Update, Delete
- - PUT, GET, UPDATE, DELETE
- Desenvolido a função para realizar likes nos repositórios. Os quais não permite que se realize likes de forma manual. 

## Para baixar o projeto e rodar na máquina local
- Clique no botão Clone or download para abrir as opções para download
- Se for usar o git clone, execute o comando abaixo estando dentro de uma pasta à sua escolha:
```bash
  git clonse git@github.com:andrelinos/conceitos-nodejs.git 
```
- Aguarde finalizar o download / clone.
- Dentro d pasta do projeto, execute o comando abaixo e aguarde finalizar a instalação dos pacotes usados: 
```bash
  yarn
```
### Para rodar o projeto, execute o comando abaixo: 
```bash
  yarn dev
```

### Para rodar os testes, execute o comando abaixo: 
```bash
  yarn test 

  ou 

  yarn test --watchAll 
```
**Nota:** --watchAll executa os testes a cada vez que você salva o código. 

## Rotas da aplicação no execício

- CREATE / PUT: http://localhost:3333/repositories
- LIST / GET: http://localhost:3333/repositories
- EDIT / PUT: http://localhost:3333/repositories/id
- DELETE: http://localhost:3333/repositories/id

### Rota para dar Likes
- CREATE / PUT: http://localhost:3333/repositories/id/likes


### Notas sobre os testes
Watch Usage
 › Press f to run only failed tests.
 › Press o to only run tests related to changed files.
 › Press p to filter by a filename regex pattern.
 › Press t to filter by a test name regex pattern.
 › Press q to quit watch mode.
 › Press Enter to trigger a test run.

 ### Em outras palavras:
 Modo de executar os testes
  ›Pressione [f] para executar apenas testes com falha.
  ›Pressione [o] para executar apenas testes relacionados aos arquivos alterados.
  ›Pressione [p] para filtrar por um padrão de regex de nome de arquivo. 
  ›Pressione [t] para filtrar por um padrão regex de nome de teste.
  ›Pressione [q] para sair do modo.
  ›Pressione [Enter] para iniciar um teste.