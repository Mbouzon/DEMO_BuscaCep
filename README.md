# DEMO_BuscaCep
Demo utilizando o componente BuscaCep que a partir de um código postal(CEP) recupera os dados de endereçamento.
    
### Pré-Requisitos
- Acesso a internet para buscar os dados da ECT(Empresa Brasileira de Correios e Telégrafos)
- Activities Packages do repositório Connect:
  - UiPathTeam.BuscaCep.Activities
- Activities Packages do repositório Official:
  - UiPath.System.Activities
  - UiPath.UIAutomation.Activities
  
### Resultados
- A atividade BznUiPath.Activities.BuscaCep retorna o objeto BznUiPath.Activities.Address populado com os seguintes dados:
  - Bairro
  - CEP
  - Complemento
  - Gia
  - Ibge
  - Localidade
  - Logradouro
  - UF
  - Unidade
