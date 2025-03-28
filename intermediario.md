# Resumo

Implementar uma API RESTful com autenticação e autorização via JWT.

Deverá ser realizado um crud completo para o seguinte contexto.

Operações do CRUD a ser implementadas:
* Criar
* Ler
* Atualizar
* Deletar

Eu como usuário gostaria de cadastrar `projetos` e cada projeto pode ter N `funcionários` e cada `funcionário` pode ter N `projetos`.

Eu como usuário gostaria de:
* Listar projetos com seus respectivos funcionários (apenas para usuários autenticados).
* Atualizar um projeto e seus funcionários (apenas para usuários autenticados e que tenham permissão de edição).
* Deletar um projeto e seus funcionários (apenas para usuários autenticados e que tenham permissão de exclusão).

**Atributos obrigátorios para as entidades:**

* Projeto:  (nome, data_criacao, descricao, data_inicio, data_fim)
* Funcionario: (nome, cpf, email, salario, data_nascimento, cargo, telefone)
 
**Requisitos de autenticação e autorização:**

* A API deve gerar um token JWT para usuários autenticados.
* A API deve validar o token JWT em todas as requisições.
* A API deve ter permissões de edição e exclusão para cada usuário.
* A API deve permitir que usuários autenticados e com permissão de edição atualizem um projeto e seus funcionários.
* A API deve permitir que usuários autenticados e com permissão de exclusão excluam um projeto e seus funcionários.

**Regras de negocio:**

* Ao salvar um funcionário, a API deve verificar se o CPF informado é válido e único.
* Ao salvar um projeto, a API deve verificar se o nome do projeto é único.