## Cadastro de Usuários

Este projeto consiste em Crud com cadastro de pessoas feito em NodeJS e armazenando os dados no banco MongoDB.

### Funcionalidades
- Listagem dos usuários cadastrados.

- Criação dos usuários através da interface, os armazenando no banco de dados automaticamente.

- Edite as informações dos usuários.

- Exclua os dados de determinados usuários através da interface, removendo-os do banco de dados automaticamente.

### Configuração 
Crie um arquivo .env na raiz do projeto e substitua os valores abaixo pelos dados do seu banco de dados:

```bash
MONGO_HOST=databaseURL
MONGO_DATABASE=databaseName
```

### 🖥️ Instalação

1. Clone este repositório
```bash
git clone https://github.com/matheusmatosr/cadastro_usuarios.git
```

Abra o terminal e faça os seguintes códigos:
  
2. Para instalar as dependências

```bash
npm install
```

3. Para rodar o projeto:

```bash
npm start
```

Após rodar os comandos acima, acesse o projeto através da url: http://localhost:3000/
