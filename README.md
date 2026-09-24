💰 Controle Financeiro

Sistema web para controle de finanças pessoais, com cadastro de categorias, lançamento de entradas e saídas, e cálculo automático de saldo.

Projeto desenvolvido como parte do meu portfólio de desenvolvedor web.

✨ Funcionalidades
CRUD completo de Categorias (criar, listar, editar, excluir)
CRUD completo de Transações (criar, listar, editar, excluir)
Cada transação é do tipo Entrada ou Saída, vinculada a uma categoria
Cálculo automático do saldo atual (soma das entradas menos as saídas)
Interface simples e responsiva feita com Thymeleaf
🛠️ Tecnologias utilizadas
Java 21
Spring Boot 4.1.1
Spring Data JPA
Thymeleaf
H2 Database (banco em memória)
Maven
🚀 Como rodar o projeto localmente

Pré-requisitos: Java 21 e Maven instalados (ou usar o Maven Wrapper incluso no projeto).

bash
# Clone o repositório
git clone https://github.com/ILG-Dev/controle-financeiro.git

# Entre na pasta do projeto
cd controle-financeiro

# Rode a aplicação
./mvnw spring-boot:run

A aplicação vai subir em http://localhost:8082.

📋 Estrutura do projeto
src/main/java/com/ilgdev/controlefinanceiro/
├── controller/     # Controllers (Categoria e Transação)
├── model/          # Entidades JPA (Categoria, Transacao)
├── repository/     # Repositórios Spring Data JPA
└── service/        # Regras de negócio (cálculo de saldo)

src/main/resources/templates/
├── categorias/     # Telas de listagem e formulário de categorias
├── transacoes/     # Telas de listagem e formulário de transações
└── menu.html        # Fragmento de navegação
📸 Screenshots
<img width="1920" height="1020" alt="{6DAAF9F9-1479-4ABB-A58F-8BA24F377CC4}" src="https://github.com/user-attachments/assets/d4fe2675-5007-4d8c-81a7-713db5ba1439" />
<img width="1920" height="1020" alt="{716CAFFA-119E-499B-9B24-57AF11ADEBFA}" src="https://github.com/user-attachments/assets/746bd9cb-d1ed-4c6f-98c0-2960d27bcccf" />
<img width="1920" height="1020" alt="{1B8BF69A-0044-42E1-85C9-FA4294D6B86A}" src="https://github.com/user-attachments/assets/db3b3237-dfee-426e-bdc4-a9a0dbc0d6be" />
<img width="1920" height="1020" alt="{596CBAE3-BC69-4DCF-96A8-F8B490D0E2CD}" src="https://github.com/user-attachments/assets/cc0a9863-2602-4f90-a2c1-f6bc0604e976" />

👤 Autor

Ivan Lopes Guimarães 📧 contato.ilg.dev@gmail.com 🔗 GitHub · LinkedIn

Projeto 3 de 3 do meu portfólio de desenvolvedor web. Confira também:

Sistema de Hamburgueria - https://github.com/ILG-Dev/hamburgueria-sistema

Site Pessoal - https://github.com/ILG-Dev/site-pessoal
