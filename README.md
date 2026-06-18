# 📦 Sistema de Controle de Estoque

Sistema desenvolvido para gerenciamento de estoque de produtos, permitindo o cadastro, consulta, atualização e remoção de itens de forma simples e eficiente.

## 🎯 Objetivo

Facilitar o controle de produtos armazenados, garantindo organização, rastreabilidade e praticidade no gerenciamento do estoque.

## 🚀 Funcionalidades

### Produtos
- Cadastrar produtos
- Listar produtos
- Buscar produto por ID
- Atualizar informações de produtos
- Excluir produtos

### Estoque
- Registrar entradas e saídas
- Controlar quantidade disponível
- Consultar localização dos produtos
- Visualizar informações do estoque

### Sistema
- Integração com banco de dados MySQL
- API REST para comunicação com o Front-end
- Persistência de dados utilizando Spring Data JPA
- Validação de dados

## 🛠 Tecnologias Utilizadas

### Back-end
- Java 21
- Spring Boot
- Spring Data JPA
- Maven

### Banco de Dados
- MySQL

### Ferramentas
- Docker
- Postman
- Git
- GitHub

## 📂 Estrutura do Projeto

```text
src
 ├── controller
 ├── service
 ├── repository
 ├── model
 ├── dto
 └── config
```

## ⚙️ Configuração

### Clonar o projeto

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
```

### Configurar o banco de dados

Edite o arquivo:

```properties
application.properties
```

Exemplo:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/estoque
spring.datasource.username=root
spring.datasource.password=senha

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

### Executar o projeto

```bash
mvn spring-boot:run
```

Ou:

```bash
./mvnw spring-boot:run
```

## 🔗 Endpoints Principais

### Produtos

| Método | Endpoint |
|----------|----------|
| GET | /produtos |
| GET | /produtos/{id} |
| POST | /produtos |
| PUT | /produtos/{id} |
| DELETE | /produtos/{id} |

### Estoque

| Método | Endpoint |
|----------|----------|
| GET | /estoque |
| GET | /estoque/{id} |
| POST | /estoque |
| PUT | /estoque/{id} |
| DELETE | /estoque/{id} |

## 👨‍💻 Desenvolvedor

**Pietro Siqueira**

Estudante de Desenvolvimento de Sistemas pelo SENAI, com foco em desenvolvimento Full Stack, APIs REST, Java, Spring Boot, React e Next.js.
