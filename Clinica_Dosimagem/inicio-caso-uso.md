# Caso de Uso: Dosimagem

| **UC01 - Solicitar Serviço e Orçamento** |
|---|
| **Ator:** Cliente |
| **Descrição:** Este caso de uso descreve o processo em que o cliente solicita um serviço específico e recebe um orçamento para o tratamento das imagens desejadas. |
| **Evento Indicador:** Solicitação de serviço e orçamento. |
| **Pré-condições:**  O cliente selecionou o tipo de serviço desejado. |
| **Pós-condições:** Orçamento é gerado e exibido ao cliente. |

| **UC02 - Aceitar Orçamento e Efetuar Pagamento** |
|---|
| **Ator:** Funcionário |
| **Descrição:** Neste caso de uso, o funcionário aceita o orçamento previamente enviado ao cliente e registra o pagamento para iniciar o processo de tratamento das imagens. |
| **Evento Indicador:** Aceitação do orçamento e registro do pagamento. |
| **Pré-condições:**  Orçamento foi enviado e está aguardando aceitação. |
| **Pós-condições:** Orçamento é aceito, e o sistema registra o pagamento realizado pelo cliente. |

| **UC03 - Enviar Imagens para Tratamento** |
|---|
| **Ator:** Cliente |
| **Descrição:** Este caso de uso descreve o processo em que o cliente envia as imagens a serem tratadas para o funcionário da clínica por meio do sistema. |
| **Evento Indicador:** Envio das imagens para tratamento |
| **Pré-condições:**  Pagamento do orçamento foi confirmado. |
| **Pós-condições:** Imagens são enviadas ao funcionário da clínica. |

| **UC04 - Realizar Tratamento das Imagens** |
|---|
| **Ator:** Funcionário |
| **Descrição:** Aqui, o funcionário recebe as imagens enviadas pelo cliente e realiza o tratamento usando um software externo. |
| **Evento Indicador:** Tratamento das imagens realizado. |
| **Pré-condições:**  Imagens foram recebidas e estão prontas para o tratamento. |
| **Pós-condições:** Imagens são tratadas com sucesso. |

| **UC05 - Enviar Resultado do Tratamento** |
|---|
| **Ator:** Funcionário |
| **Descrição:** Neste caso de uso, o funcionário envia de volta para o cliente o resultado do tratamento das imagens após concluído o processo. |
| **Evento Indicador:** Envio do resultado do tratamento. |
| **Pré-condições:** <br> - Funcionário realizou o tratamento das imagens. <br> - Imagens foram tratadas com sucesso. |
| **Pós-condições:** Resultado do tratamento é enviado ao cliente. |

