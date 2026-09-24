Aula 2 - Making History
1. Acompanhar o pedido
História de usuário

Como cliente, quero acompanhar o status do meu pedido após a compra, para saber em que etapa ele está e quando será entregue.

Critérios de aceitação

Critério 1

Dado que o cliente realizou um pedido,
Quando acessar a tela de acompanhamento,
Então deverá visualizar o status atual do pedido.

Critério 2

Dado que o pedido mudou de etapa,
Quando o sistema atualizar o status,
Então o novo status deverá ser exibido para o cliente.

Critério 3

Dado que o pedido foi concluído,
Quando o cliente acessar o acompanhamento,
Então deverá visualizar que o pedido foi entregue.

2. Avisar item indisponível
História de usuário

Como restaurante, quero marcar um item do cardápio como indisponível, para evitar que clientes façam pedidos de produtos que não estão disponíveis.

Critérios de aceitação

Critério 1

Dado que um item está disponível no cardápio,
Quando o restaurante marcá-lo como indisponível,
Então o item deverá aparecer como indisponível para os clientes.

Critério 2

Dado que um item está marcado como indisponível,
Quando um cliente visualizar o cardápio,
Então não deverá conseguir adicioná-lo ao pedido.

Critério 3

Dado que o item voltou a estar disponível,
Quando o restaurante alterar seu status,
Então o item deverá voltar a poder ser selecionado pelos clientes.

3. Reportar problema durante a entrega
História de usuário

Como entregador, quero reportar um problema durante a entrega, para informar o restaurante sobre situações que possam impedir ou atrasar a entrega.

Critérios de aceitação

Critério 1

Dado que o entregador está realizando uma entrega,
Quando ocorrer um problema,
Então ele deverá conseguir acessar a opção de reportar problema.

Critério 2

Dado que o entregador abriu a opção de reportar problema,
Quando selecionar o tipo de problema e enviar o relato,
Então o sistema deverá registrar a ocorrência.

Critério 3

Dado que um problema foi registrado,
Quando o envio for concluído,
Então o restaurante deverá ser informado sobre a ocorrência.

Priorização - MoSCoW
Must Have - Deve ter
Acompanhar o status do pedido.
Marcar item do cardápio como indisponível.
Impedir que clientes adicionem itens indisponíveis ao pedido.
Permitir que o entregador registre um problema durante a entrega.
Registrar e comunicar o problema ao restaurante.
Should Have - Deveria ter
Atualizar automaticamente o status do pedido.
Permitir que o restaurante altere novamente um item para disponível.
Permitir que o entregador selecione diferentes tipos de problema.
Could Have - Poderia ter
Exibir uma previsão de horário de entrega ao cliente.
Permitir que o entregador adicione uma descrição ou observação ao problema.
Won't Have - Não terá neste momento
Sistema de chamada de vídeo entre entregador e restaurante.
Rastreamento do entregador em tempo real por GPS.
