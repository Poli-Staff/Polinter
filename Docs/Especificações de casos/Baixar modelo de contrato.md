## Baixar modelo de contrato

| ITEM | VALUE |
| --- | --- |
| UseCase |	Baixar modelo de contrato |
| Summary | Ação para baixar um modelo de contrato para a empresa se cadastrar na base de dados de empresas. |
| Actor |  |
| Precondition | 1. Começado o cadastro de estágio; <br> 2. Empresa solicitada não está cadastrada. |
| Postcondition | 1. Modelo de contrato gerado e baixado para o Aluno; |
| Base Sequence | 1. O Aluno solicita o download com as informações dejesadas; <br> 2. Modelo de contrato é baixado. |
| Branch Sequence | 1. Informações não preenchidas: <br> 1.1 Pede que o aluno preencha as informações e lança um erro de "Informações pendentes"; |
| Exception Sequence | 1. A operação não pode ser finalizada, requer campos preenchidos. |
| Sub UseCase |  |
| Note |  |
