# 📌 API de Gerenciamento de Tarefas

## 🚀 Sobre o projeto
Esta é uma API REST desenvolvida com Spring Boot para gerenciamento de tarefas.
A aplicação permite realizar operações completas de CRUD (Create, Read, Update, Delete), seguindo boas práticas de arquitetura em camadas:

- Controller (requisições HTTP)
- Service (regras de negócio)
- Repository (acesso ao banco)

## 🛠 Tecnologias utilizadas
- Java 21
- Spring Boot
- Spring Data JPA
- H2 Database
- Maven
- 
## 🧠 Arquitetura
Controller → Service → Repository → Banco de Dados

⚠️ Tratamento de erros
A API retorna respostas apropriadas:
404 → recurso não encontrado
200 → sucesso
Exemplo:
Tarefa não encontrada

## ▶️ Como executar o projeto
1. Clonar o repositório
2. Abrir no IntelliJ
3. Rodar a classe principal (DemoApplication.java)
4. Acessar:
http://localhost:8080/tarefas

📄 Exemplo de JSON:
{
  "descricao": "Estudar Java",
  "concluida": false
}

Autor: Leandro G. G. Eusébio

