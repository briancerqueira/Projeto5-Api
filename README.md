# Projeto INDIVIDUAL (05) , Plataforma Resilia 





# [ API ] FUTEBOL

Desenvolvimento de uma Api, que retorna as entidades em :  **CRUD**: ``Jogos``, ``Estádios``, ``Campeonatos``, ``Equipes``.




**[Tecnologias utilizadas ]**

<samp>
  
- <em>Node.js</em> | <em>SQLite3</em> | <em>Express</em> | <em>Insomnia</em> | <em>CORS</em> | <em>npm</em> | <em>Nodemon</em>
  
</samp>

<details>
<summary>  
  <strong>Estrutura do diretório</strong>
</summary>
<br>

```
src/
â”œâ”€ controllers/
â”‚  â”œâ”€ JogosController.js
â”‚  â”œâ”€ EstádiosController.js
â”‚  â”œâ”€ CampeonatosController.js
â”‚  â””â”€ EquipesController.js
â”œâ”€ dao/
â”‚  â”œâ”€ JogosDAO.js
â”‚  â”œâ”€ EstádiosDAO.js
â”‚  â”œâ”€ CampeonatosDAO.js
â”‚  â””â”€ EquipesDAO.js
â”œâ”€ models/
â”‚  â”œâ”€ Jogos.js
â”‚  â”œâ”€ Estádios.js
â”‚  â”œâ”€ Campeonatos.js
â”‚  â””â”€ Equipes.js
â”œâ”€ database/
â”‚  â”œâ”€ create-and-populate.js
â”‚  â”œâ”€ config.js
â”‚  â””â”€ database.db
â”œâ”€ routes/
â”‚  â”œâ”€ jogos.js
â”‚  â”œâ”€ estádios.js
â”‚  â”œâ”€ campeonatos.js
â”‚  â””â”€ equipes.js
â””â”€ main.js
```

</details>


### ðŸŽ² Iniciando o Projeto


<samp>
  
> **Warning** 
> Pré-Requisitos: Git, Node.js e um editor de cÃ³digo.

</samp>

## Rotas CRUD

 [ 1 ] <em>Jogos</em>

| Método | Rota | Descriçao |
| ------ | ----- | ----------- |
| **`GET`** | **/Jogos** | Retorna todos os Jogos. 
|  **`GET`** | **Jogos/id** | Retorna a um Jogo. 
|  **`POST`** | **/Jogos** | Cria um novo Jogo.  
|  **`PUT`** | **/Jogos/id** | Altera os dados de um Jogo.
|  **`DELETE`** | **/Jogos/id** | Remove um Jogo.
  
### [ 2 ] <em>Estádios</em>

| Método | Rota | Descriçao |
| ------ | ----- | ----------- |
|  **`GET`** | **/estádios** | Retorna todos os Estádios. 
|  **`GET`** | **/estádios/id** | Retorna um Estádio. 
|  **`POST`** | **/estádio** | Cria um novo Estádio.  
|  **`PUT`** | **/estádio/id** | Altera os dados do Estádio.
|  **`DELETE`** | **/estádio/id** | Remove o Estádio.
  
  
 [ 3 ] <em>A</em>

| Método | Rota | Descriçao |
| ------ | ----- | ----------- |
|  **`GET`** | **/campeonatos** | Retorna todos os campeonatos. |
|  **`GET`** | **/campeonatos/id** | Retorna um campeonato. |
|  **`POST`** | **/campeonatos** | Cria um novo campeonato.  |
|  **`PUT`** | **/campeonatos/id** | Altera os dados do campeonato.
|  **`DELETE`** | **/campeonatos/id** | Remove o campeonato.


 [ 4 ] <em>Equipamentos</em>

| Método | Rota | Descriçao |
| ------ | ----- | ----------- |
|  **`GET`** | **/Equipes** | Retorna todos as Equipes. |
|  **`GET`** | **/Equipe/id** |  Retorna uma Equipe. |
|  **`POST`** | **/Equipe** | Cria uma nova Equipe.  |
|  **`PUT`** | **/Equipe/id** | Altera os dados de uma equipe.
|  **`DELETE`** | **/Equipe/id** | Remove uma Equipe.
  

