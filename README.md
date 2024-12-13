# CRUD com Node.js, MySQL, Express e Bootstrap

Um sistema CRUD completo para gerenciamento de dados, utilizando Node.js no backend com MySQL, CORS e Express, e um frontend estilizado com Bootstrap.

## Funcionalidades

- **Criação de registros**: Adicione novos dados no banco.
- **Leitura de registros**: Consulte dados existentes.
- **Atualização de registros**: Edite informações de registros.
- **Exclusão de registros**: Remova registros do sistema.

## Tecnologias Utilizadas

### Backend
- [Node.js](https://nodejs.org/)
- [Express](https://expressjs.com/)
- [MySQL](https://www.mysql.com/)
- [CORS](https://www.npmjs.com/package/cors)

### Frontend
- [Bootstrap](https://getbootstrap.com/)

## Pré-requisitos

- Node.js e npm instalados.
- MySQL instalado e configurado.

## Como Configurar o Projeto

1. Clone o repositório:

   ```bash
   git clone https://github.com/seuusuario/nome-do-repositorio.git
   ```

2. Navegue até o diretório do projeto:

   ```bash
   cd nome-do-repositorio
   ```

3. Instale as dependências do backend:

   ```bash
   npm install
   ```

4. Configure o banco de dados:

   - Crie um banco de dados no MySQL.
   - Importe o arquivo `schema.sql` (se disponível) para criar as tabelas.
   - Atualize as credenciais do banco no arquivo `config.js` ou similar.

5. Inicie o servidor backend:

   ```bash
   node app.js
   ```

6. Abra o arquivo `index.html` no navegador para acessar o frontend.

## Estrutura do Projeto

```plaintext
.
├── backend
│   ├── server.js          # Arquivo principal do servidor
├── frontend
│   ├── index.html      # Página principal do frontend
│   ├── css             # Estilos adicionais
│   └── js              # Scripts para interações
└── README.md           # Documentação do projeto
```

## Como Usar

1. Acesse a interface no navegador (arquivo `index.html`).
2. Utilize as opções para criar, visualizar, editar ou excluir registros.
3. O backend processa as requisições e interage com o banco de dados MySQL.

## Melhorias Futuras

- Adicionar autenticação de usuários.
- Implementar paginação no frontend.
- Criar um sistema de upload de arquivos.
- Migrar para um framework frontend moderno (React, Vue, etc.).

## Contribuição

Contribuições são bem-vindas! Abra um pull request ou reporte problemas na aba de issues.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---

### Autor

**Hélcio Humberto**  
[LinkedIn](https://www.linkedin.com/helciohumberto) | [GitHub](https://github.com/helciohumberto)
