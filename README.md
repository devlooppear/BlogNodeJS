# BlogNodeJS
Esta é uma aplicação de blog construída usando Node.js e Express.js. Permite aos usuários visualizar postagens de blog, navegar por categorias e gerenciar o conteúdo do blog por meio de um painel de administração.

## Recursos
Autenticação de usuário usando passport.js
MongoDB para armazenamento de dados
Handlebars como mecanismo de templates
Mensagens de flash para exibir mensagens de sucesso e erro
Operações CRUD para gerenciar postagens de blog e categorias
Instalação

- Clone o repositório;

Instale as dependências:

```javascript
npm install
```
Configure o banco de dados MongoDB. Atualize a URL de conexão do MongoDB no arquivo `app.js`:

```javascript
mongoose.connect('mongodb://127.0.0.1:27017/blogapp')
```

## Inicie a aplicação:

```javascript
npm start
```

Abra seu navegador e acesse: http://localhost:8081, para acessar o aplicativo de blog.

## Uso

- Página inicial: Visualize a lista de postagens de blog ordenadas por data em ordem decrescente.
- Postagem individual: Clique em uma postagem para visualizar seu conteúdo completo.
Categorias: Navegue por postagens por categoria.
- Painel de administração: Acesse o painel de administração visitando http://localhost:8081/admin. Aqui, você pode gerenciar postagens e categorias, criar novas postagens, editar postagens existentes, excluir postagens, criar categorias, etc.

## Dependências

- bcryptjs
- body-parser
- bootstrap
- connect-flash
- express
- express-handlebars
- express-session
- handlebars
- mongoose
- passport
- passport-local
