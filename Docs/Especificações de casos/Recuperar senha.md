## Recuperar senha

| ITEM | VALUE |
| --- | --- |
| UseCase | Recuperar senha |
| Summary | Ação responsável pela recuperação de senha do usuário caso o mesmo tenha esquecido/perdido. |
| Actor | Usuário |
| Precondition | 1. Ter um usuário cadastrado no sistema; <br>2. Ter esquecido/perdido a senha. |
| Postcondition | 1. Senha alterada com sucesso. |
| Base Sequence | 1. O usuário irá inserir o email da conta que ele quer recuperar a senha; <br> 2. O sistema irá validar o email inserido; <br> 3. O usuário irá solicitar a recuperação de senha; <br> 4. O sistema irá enviar um email com o link de recuperação da senha; <br> 5. O usuário irá inserir uma nova senha e a confirmação da senha; <br> 6. O usuário irá finalizar a ação. |
| Branch Sequence | 1.1 O usuário não existe: <br> 1. Caso o usuário não exista o sistema irá disparar que o email inserido é inválido e o usuário terá que informar um email válido. <br> 1.2 Confirmação de senha inválida: <br> 1. Caso o usuário informe a confirmação de senha e a própria não esteja de acordo com a senha informada, o sistema irá informar o erro e o usuário terá que preencher o campo novamente. |
| Exception Sequence | 1. O sistema não enviará o email pois a conta não é reconhecida no sistema. |
| Sub UseCase | Enviar e-mail de recuperação |
| Note |  |