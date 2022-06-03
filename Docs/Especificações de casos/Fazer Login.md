## Fazer login

| ITEM | VALUE |
| --- | --- |
| UseCase | Fazer login |
| Summary | Este caso de uso é responsável por descrever como o usuário irá entrar no sistema. |
| Actor | Usuário |
| Precondition | 1. Ter um cadastro no sistema. |
| Postcondition | 1. O usuário poderá acessar o sistema. |
| Base Sequence | 1. O usuário irá informar seu email e senha; <br> 2. O sistema irá validar o email e senha informado; <br> 3. O usuário irá entrar no sistema. |
| Branch Sequence | 1.1 Email ou senha inválido: <br> 1. Caso o email ou senha senjam inválidos, o sistema irá disparar uma mensagem de erro e o usuário terá que informar esses campos novamente. |
| Exception Sequence | 1. Email ou senha inválidos o usuário não acessa o sistema. |
| Sub UseCase |  |
| Note |  |