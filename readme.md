# 📚 Book API

Uma API RESTful completa, eficiente e didática para o gerenciamento de livros, desenvolvida em **Python** com **FastAPI**. A aplicação permite realizar operações de cadastro, consulta, atualização e remoção de obras literárias de forma simples e rápida.

## 👤 Autor

- **Desenvolvedor:** Lorenzo Müller Cardoso
- **Projeto:** API de Gerenciamento de Livros

## 🛠️ Tecnologias Utilizadas

- **Linguagem:** Python 3+
- **Framework Web:** FastAPI
- **ORM / Banco de Dados:** SQLAlchemy
- **Validação de Dados:** Pydantic
- **Formato de Resposta:** JSON

## 🚀 Rotas da API

A API conta com as 5 rotas principais do padrão REST:

| Método | Rota | Descrição | Status de Sucesso |
|---|---|---|---|
| `GET` | `/livros` | Retorna a lista completa de todos os livros cadastrados. | `200 OK` |
| `GET` | `/livros/{id_livro}` | Busca e retorna os detalhes de um livro específico pelo ID. | `200 OK` |
| `POST` | `/livros` | Cadastra um novo livro no banco de dados. | `201 Created` |
| `PUT` | `/livros/{id_livro}` | Atualiza todas as informações de um livro existente. | `200 OK` |
| `DELETE` | `/livros/{id_livro}` | Remove permanentemente um livro do sistema pelo ID. | `200 OK` / `204 No Content` |

## 📖 Documentação Interativa (Swagger & ReDoc)

Graças ao **FastAPI**, a API conta com documentação interativa gerada automaticamente. Após iniciar o servidor localmente, você pode acessá-la através do seu navegador nas rotas `/docs` (Swagger UI) ou `/redoc` (ReDoc).

📌 *Projeto desenvolvido para fins didáticos e demonstrativos.*