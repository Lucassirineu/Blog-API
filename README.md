# Blog API 🚀

Projeto desenvolvido a fins de estudo para colocar os conhecimentos adquiridos na plataforma balta.io em prática usando **ASP.NET Core** e **Entity Framework Core** para gerenciar um sistema de blog. Inclui autenticação segura, gerenciamento de usuários, upload de imagens e CRUD de categorias, seguindo boas práticas de desenvolvimento.

---

## 🌟 **Destaques do Projeto**

- **Segurança:** Autenticação JWT e criptografia de senhas.
- **Boas Práticas:** Uso de migrations, tratamento de exceções e padrão MVC.
- **Escalabilidade:** Pronto para evoluir com testes, logs e monitoramento.

---

## 📂 **Estrutura do Projeto**

- **Controllers:** Endpoints da API (Account, Category, etc.).
- **Models:** Entidades do banco de dados (User, Category, Post, etc.).
- **Data:** Configuração do contexto do banco de dados e migrations.
- **Services:** Lógica de negócio (TokenService, etc.).
- **ViewModels:** Modelos para validação e transferência de dados.

---

## ⚙️ **Funcionalidades**

- **Autenticação JWT:** Segurança robusta com tokens JWT para acesso aos recursos.
- **Cadastro e Login de Usuários:** Registro e autenticação de usuários com geração automática de senhas seguras.
- **Upload de Imagem de Perfil:** Permite aos usuários adicionar ou alterar a imagem do perfil.
- **CRUD de Categorias:** Criação, leitura, atualização e exclusão de categorias.
- **Tratamento de Exceções:** Respostas claras e personalizadas para erros.
- **Migrations com Code First:** Gerenciamento eficiente do banco de dados.

---

## 🛠️ **Tecnologias Utilizadas**

- **ASP.NET Core**
- **Entity Framework Core**
- **SQL Server**
- **JWT (JSON Web Tokens)**
- **Docker** (opcional para containerização)
- **Postman** (para teste dos endpoints)

---

## 📦 **Pacotes Utilizados**

- **Microsoft.AspNetCore.Authentication.JwtBearer**  
  Para autenticação JWT.

- **Microsoft.AspNetCore.Authentication**  
  Para funcionalidades básicas de autenticação.

- **Microsoft.EntityFrameworkCore.Design**  
  Para gerenciar migrations e design-time do Entity Framework Core.

- **Microsoft.EntityFrameworkCore.SqlServer**  
  Para integração com SQL Server.

- **SecureIdentity**  
  Para geração segura de senhas e hash.
