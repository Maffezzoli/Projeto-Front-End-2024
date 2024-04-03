## Requisitos em linguagem natural
- O sistema deve ser fácil de usar, para que até mesmo funcionários
   inexperientes possam operá-lo com facilidade.
- A interface do sistema deve ser amigável e intuitiva,
   proporcionando uma experiência agradável ao usuário.
- Os funcionários devem poder acessar os formulários enviados pelos clientes através da aba "Serviço",
  facilitando o gerenciamento e acompanhamento das solicitações.
-  Deve haver uma funcionalidade de "Histórico de Ações" que permita aos funcionários visualizarem as modificações realizadas no sistema,
   oferecendo transparência e rastreabilidade das atividades realizadas.
- Os funcionários devem ter a capacidade de baixar as imagens enviadas pelos clientes em formato PDF,
  facilitando o acesso e a manipulação desses documentos para futuras referências ou ações.
## Requisitos Funcionais:
**RF01**:  O sistema deve incluir uma área dedicada para organizar os quatro tipos de formulários: Calibrations, Clinic Dosimetries, Preclinic Dosimetries e Radiosynoviorthesis. Essa organização visa simplificar a navegação e facilitar o acesso aos formulários relevantes para os usuários. <br>
**RF02**:  O sistema deve permitir a atualização do andamento do pedido em três estados distintos: "Em análise", "Sendo processado" e "Concluído". Essa funcionalidade visa fornecer uma visão clara do progresso de cada pedido dentro do sistema. <br>
**RF03**:  Interface acoplada na área de análise dos formulários para atualização do andamento do pedido (RF02).<br>
**RF04**:  O sistema deve ser capaz de catalogar e armazenar todas as modificações realizadas nos formulários e em outras instâncias da API. Isso inclui, mas não se limita a, alterações nos dados dos formulários, criação ou exclusão de registros, e quaisquer outras interações relevantes.
## Requisitos não Funcionais:
**RNF01**:  O sistema deve ser desenvolvido para utilizar a API existente da Dosimagem, integrando-se de forma eficaz para aproveitar as funcionalidades e dados disponíveis nessa API.
