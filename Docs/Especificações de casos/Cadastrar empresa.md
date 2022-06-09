<html>
<body>
<!--StartFragment--><h2>Cadastrar empresa</h2>


Item | Value
-- | --
UseCase | Castrar empresa
Sumary | Ação responsavel pelo cadastro de uma empresa no sistema. O cadastro será realizado divisão de estágio pelo formulário de cadastro de empresas. A empresa irá solicitar a divisão o cadastro.
Actor | Divisão de Estágio
Precondition | 1. A empresa deve ter feito contato com a divisão;<br>2. A empresa deve ter CNPJ ativo;<br>3. A empresa não pode está cadastrada no sistema.<br>
Postcondition | 1. A empresa é cadastrada no sistema.
Base Sequence | 1. A empresa entrará em contato com a divisão de estágio;<br>2. A divisão de estágio irá preencher o formulário de cadastro;<br>3. O Sistema irá validar os campos preenchidos pelo usuário;<br>4. O cadastro será efetuado pelo sistema.<br>
Branch Sequence | 1.1 Os dados não foram totalmente preenchidos.<br>  1. O sistema irá informar que há campos faltando indicando-os com a cor vermelha.<br>1.2 Os dados não são validos.<br>  1. O sistema irá informar que há campos com dados invalidos indicando-os com a cor vermelha.<br>1.3 O sistema não conseguiu finalizar o cadastro<br>  1. O sistema irá informar que o cadastro não foi finalizado<br>  2. O erro é conhecido<br>    1. O sistema irá informar o motivo <br>  3. O erro não é conhecido<br>     1. O sistema irá informar que a causa é desconhecida
Excetion Sequence | 1. O cadastro não será realizado caso:<br>  1. Caso a conexão seja perdida durante o processo;<br>  2. Os dados preenchidos estejam incorretos;<br>  3. Os dados preenchidos estão faltando (formulário incompleto).
Sub UseCase |  
Note |  


<!--EndFragment-->
</body>
</html>
