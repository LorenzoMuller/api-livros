📚 Book API
Uma API RESTful completa e eficiente para gerenciamento de livros, desenvolvida para facilitar o cadastro, consulta, atualização e remoção de obras literárias.

👤 Autoria
Desenvolvedor: Lorenzo Müller Cardoso

Projeto: API de Gerenciamento de Livros

🚀 Rotas da API
A API conta com as 5 rotas principais do padrão REST:

📖 1. Listar Todos os Livros
Método: GET

Rota: /livros

Descrição: Retorna a lista completa de todos os livros cadastrados no sistema.

🔍 2. Buscar Livro por ID
Método: GET

Rota: /livros/:id

Descrição: Busca e retorna os detalhes de um livro específico com base no ID informado.

➕ 3. Cadastrar Novo Livro
Método: POST

Rota: /livros

Descrição: Adiciona um novo livro ao banco de dados. Requer os dados da obra no corpo da requisição (body).

✏️ 4. Atualizar Livro
Método: PUT

Rota: /livros/:id

Descrição: Atualiza as informações de um livro existente identificado pelo seu ID.

🗑️ 5. Deletar Livro
Método: DELETE

Rota: /livros/:id

Descrição: Remove permanentemente um livro do sistema através do seu ID.

🛠️ Tecnologias Utilizadas
Linguagem: Python / JavaScript

Framework: Express

Formato de Resposta: JSON