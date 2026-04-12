# 📌 Sistema de Tarefas - API REST
## 🚀 Sobre o projeto
Este é um projeto de API REST desenvolvido com Spring Boot para gerenciamento de tarefas.
A aplicação permite realizar operações básicas de CRUD:

- Criar tarefas
- Listar tarefas
- Atualizar tarefas
- Deletar tarefas
---
## 🛠 Tecnologias utilizadas
- Java
- Spring Boot
- Spring Data JPA
- H2 Database
- Maven
---
🔗 Endpoints
📌 Criar tarefa:
POST /tarefas
📌 Listar tarefas:
GET /tarefas
📌 Atualizar tarefa:
PUT /tarefas/{id}
📌 Deletar tarefa:
DELETE /tarefas/{id}
---
## ▶️ Como executar o projeto
1. Clonar o repositório
2. Abrir no IntelliJ
3. Rodar a classe principal (DemoApplication.java)
4. Acessar:
http://localhost:8080/tarefas
---
📄 Exemplo de JSON:
{
  "descricao": "Estudar Java",
  "concluida": false
}

Autor: Leandro G. G. Eusébio
