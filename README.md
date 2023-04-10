# Boas-Vindas ao meu Teste Prático!

Esta é uma API para simular um cardápio on-line!

Para as configurações da aplicação, utilizei:
<br />

- TypeScript
- NodeJS
- Express
- Sequelize
- JWT (para autenticação)
- MySQL
- MongoDB (Mongoose)

Para rodar o projeto localmente:

- Criar um repositório local
- Ir no repositório do GitHub, em `<Code>`, e copiar a chave SSH ou URL
- Executar um 'git clone' no repositório local
- Rodar o comando 'npm install' para instalar todas as dependências
- Acessar o 'http://localhost:3000/' a partir de alguma plataforma para usar a API (Postman, Imsonia ou qualquer outra)
- Utilizar as rotas a seguir:
  - POST /auth/login: Para o acesso dos ADMs na API
  - GET /category: para listar todas as categorias de produtos
  - GET /product: para listar todos os produtos
  - GET /product/'id': para listar um produto a partir de um id específico
  - POST /product: com o body da requisição contendo:
    - Nome
    - Descrição
    - Preço
  - PATCH /product/'id': para alterar um produto que já existe no Banco de Dados
  - DELETE /product/'id': para excluir um produto do Banco de Dados
