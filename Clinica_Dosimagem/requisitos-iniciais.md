## Requisitos em linguagem natural
- O sistema deve ser simples a ponto que funcionários inexperientes possam operá-lo.
- Interface amigável e intuitiva.
- O sistema deve permitir que os funcionários visualizem os formulários enviados pelos clientes por meio da aba "service".
- Os funcionários devem poder baixar as imagens enviadas pelo cliente, em formato de pdf.
## Requisitos Funcionais:
**RF01**: O sistema deve ter uma area que dedicada a organizar os 4 tipos de formulários(Calibrations, Clinic Dosimetries, Preclinic Dosimetries, Radiosymoviorthesis), de forma a descomplicar a navegação. <br>
**RF02**: Atualização do andamento do pedido em 3 estados ->Em análise -> Sendo processado -> Concluído. <br>
**RF03**: Interface acoplada na área de análise dos formulários para atualização do andamento do pedido (RF02).
## Requisitos não Funcionais:
**RNF01**: O sistema precisa ser feito para utilizar a api ja existente da Dosimagem.