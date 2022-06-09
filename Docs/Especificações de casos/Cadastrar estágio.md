## Cadastrar estágio

| ITEM | VALUE |
| --- | --- |
| UseCase | Cadastrar estágio |
| Summary | Ação responsável por aluno para cadastrar seu estágio na divisão de estágio atravez da página de cadastro onde preencherá os campos necessários. |
| Actor | Aluno, Divisão de estágio |
| Precondition | 1. Aluno deve estar logado; <br> 2. Estar matriculado na disciplina de Estágio Supervisionado;	<br> 3. Ter solicitado o cadastro de estagio para a divisão. |
| Postcondition | 1. Aluno tem Estágio cadastrado, com professor para avaliar e com documentos encaminhados; |
| Base Sequence | 1. Aluno preenche os campos solicitados; <br> 2. Entre os campos, o aluno deve escolher entre "Obrigatório" e "Não-Obrigatório". |
| Branch Sequence | 1. Campos não preenchidos: <br> 1.1 O sistema informa que os determinados campos não foram preenchidos e pede que o aluno preecha. <br><br> Informações pendentes: <br> 2.1 Será necessário um modelo de contrato para o cadastro da nova empresa.|
| Exception Sequence | 1. O aluno não preecheu os campos requisitados e um erro para os campos não preenchidos será lançado. <br> 2. O Aluno não poderá finalizar pois requer empresa. |
| Sub UseCase | Baixar modelo de contrato |
| Note |  |
