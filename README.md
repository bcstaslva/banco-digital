# Banco Digital

## Descrição

O **Banco Digital** é uma aplicação backend desenvolvida em Java com Spring Boot, focada em simular operações bancárias básicas, como criação de contas, depósitos, saques e transferências entre usuários. O projeto aplica conceitos de programação orientada a objetos (herança, polimorfismo, encapsulamento) e utiliza JPA para persistência de dados, sendo ideal para demonstrar habilidades em desenvolvimento backend.

## Funcionalidades

- Criação de contas bancárias com informações de usuário (nome, CPF, saldo inicial).
- Operações de depósito e saque com validação de saldo.
- Transferências entre contas com verificação de fundos.
- Consulta de saldo e histórico de transações.
- Endpoints REST para gerenciar contas e transações.

## Tecnologias Utilizadas

- **Java**: Linguagem principal para lógica de negócios.
- **Spring Boot**: Framework para criação de APIs REST.
- **JPA/Hibernate**: Persistência de dados com banco H2.
- **Postman**: Testes de endpoints.
- **Git**: Versionamento do código.
- **Maven**: Gerenciamento de dependências.

## Pré-requisitos

- Java 17 ou superior
- Maven 3.8+
- Postman (para testes)
- Git

## Instalação e Execução

1. Clone o repositório:
   ```bash
   git clone https://github.com/bcstaslva/banco-digital.git
   ```
2. Navegue até o diretório do projeto:
   ```bash
   cd banco-digital
   ```
3. Compile e execute com Maven:
   ```bash
   mvn spring-boot:run
   ```
4. Acesse a API em `http://localhost:8080`.
5. Importe a coleção do Postman (disponível em `/docs/postman-collection.json`) para testar os endpoints.

## Endpoints Principais

- `POST /contas`: Cria uma nova conta.
- `POST /transacoes/deposito`: Realiza um depósito.
- `POST /transacoes/saque`: Realiza um saque.
- `POST /transacoes/transferencia`: Transfere entre contas.
- `GET /contas/{id}/saldo`: Consulta saldo.

## Como Contribuir

1. Faça um fork do repositório.
2. Crie uma branch para sua feature (`git checkout -b feature/nova-funcionalidade`).
3. Commit suas alterações (`git commit -m 'Adiciona nova funcionalidade'`).
4. Push para a branch (`git push origin feature/nova-funcionalidade`).
5. Abra um Pull Request.

## Autor

Bruno Costa da Silva  
[GitHub](https://github.com/bcstaslva) | [E-mail](mailto:bcstaslva@gmail.com)
