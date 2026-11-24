# Spring Security Aluno Online

API de gerenciamento acadêmico com Spring Boot, MySQL, autenticação JWT e associação de cada conta a um cadastro de aluno.

## Projeto

- API Spring Boot: [`Aluno_Online/api`](Aluno_Online/api)
- Instruções de instalação, configuração, execução e autenticação: [`Aluno_Online/api/README.md`](Aluno_Online/api/README.md)

## Segurança

As rotas exigem JWT Bearer, exceto cadastro, login e documentação Swagger. Os registros de aluno e suas matrículas são limitados ao aluno associado à conta autenticada. Disciplinas e professores são dados compartilhados; o projeto ainda não possui perfis diferentes para restringir suas operações.
