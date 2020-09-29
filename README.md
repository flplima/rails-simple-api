# README
Minha primeira experiência com Ruby on Rails.
Feito apenas para fins de aprendizagem.

Essa API é um simples CRUD de filmes, persistindo os dados usando SQLite.

## Como começar
```bash
# clone este repositório
git clone https://github.com/flplima/rails-simple-api.git

# instale as dependências
bundle install

# execute as migrations no banco de dados
rails db:migrate

# preencha o banco com alguns dados
rails db:seed

# inicie o servidor de desenvolvimento
rails server
```

A API estará funcionando em [http://localhost:3000](http://localhost:3000)

| Rota | Função |
| ----------- | ----------- |
| GET /movies | Lista todos os filmes cadastrados |
| GET /movies/1 | Mostra 1 filme pelo id |
| POST /movies | Cadastra um novo filme |
| PATCH/PUT /movies/1 | Altera um filme pelo id |
| DELETE /movies/1 | Deleta um filme pelo id |

