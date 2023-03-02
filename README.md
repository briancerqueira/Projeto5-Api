# projeto-5-individual-Api



# [ API ] Jogos e consoles
### ðŸ“‘ DescriÃ§Ã£o
Desenvolvimento da <em>**API REST**</em> no **padrÃ£o MVC** que retorna informaçoess das entidades de um mundo de jogos e consoles operacionados por empresas. **CRUD**: ``Desenvolvedor``, ``Consumidores``, ``Jogos``, ``Console``.




**[ Tecnologias ]**

<samp>
  
- <em>Node.js</em> | <em>SQLite3</em> | <em>Express</em> | <em>Insomnia</em> | <em>CORS</em> | <em>npm</em> | <em>Nodemon</em>
  
</samp>

<details>
<summary>  
  <strong>Estrutura do DiretÃ³rio</strong>
</summary>
<br>

```
src/
â”œâ”€ controllers/
â”‚  â”œâ”€ DesenvolvedoresController.js
â”‚  â”œâ”€ JogosController.js
â”‚  â”œâ”€ ConsumidoresController.js
â”‚  â””â”€ ConsoleController.js
â”œâ”€ dao/
â”‚  â”œâ”€ DesenvolvedorDAO.js
â”‚  â”œâ”€ Jogo.js
â”‚  â”œâ”€ ConsumidorDAO.js
â”‚  â””â”€ ConsoleDAO.js
â”œâ”€ models/
â”‚  â”œâ”€ Desenvolvedor.js
â”‚  â”œâ”€ Jogos.js
â”‚  â”œâ”€ Consumidores.js
â”‚  â””â”€ Consoles.js
â”œâ”€ database/
â”‚  â”œâ”€ create-and-populate.js
â”‚  â”œâ”€ config.js
â”‚  â””â”€ database.db
â”œâ”€ routes/
â”‚  â”œâ”€ Console.js
â”‚  â”œâ”€ Consumidores.js
â”‚  â”œâ”€ Jogos.js
â”‚  â””â”€ Desenvolvedores.js
â””â”€ main.js
```

</details>


### ðŸŽ² Iniciando o Projeto


<samp>
  
> **Warning** 
> PrÃ©-Requisitos: Git, Node.js e um editor de cÃ³digo.

</samp>


# Acesse o servidor
$ <http://localhost:6020>

