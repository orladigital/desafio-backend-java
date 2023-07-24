# Resumo

Implementar uma API RESTful.

Deverá ser realizado um crud parcial para o seguinte contexto.

Operações do CRUD a ser implementadas: 
* Criar
* Ler

Eu como usuário gostaria de cadastrar `projetos` e cada projeto pode ter N `funcionários` e cada `funcionário` pode ter N `projetos`. 

Eu como usuário gostaria de listar projetos com seus respectivos funcionários.

**Atributos obrigátorios para as entidades:**

* Projeto:  (nome, data_criacao)
* Funcionario: (nome, cpf, email, salario)

# Instruções

- Usar java 11+
- Spring Boot ou Quarkus
- Usar Banco de dados relacional (não usar banco em memória)
- Documentar execução da aplicação
- Seguir o padrão RESTful
- Seguir Normalização do Banco de Dados
- Realizar testes unitários/integrados
- Enviar o código para o github
