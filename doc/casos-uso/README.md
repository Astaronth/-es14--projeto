Fazer Pedido - versão 

Caso de uso primário

Atores

Cliente

Pré-condição:

O usuário deve ter feito "log-in" e obtido autorização do sistema

Fluxo de Eventos (caminho básico):

O caso de uso começa quando o cliente seleciona "fazer pedido".
O cliente fornece seu nome e endereço.
Se o cliente fornece apenas o CEP, o sistema coloca automaticamente o a cidade e o estado.
O cliente fornece os códigos do produto. (veja alternativa)
O sistema devolve as descrições e o preço de cada produto. (Ponto de extensão - Produto em Oferta)
O sistema calculará os valores totais para cada produto fornecido. (Ponto de extensão - Cliente Especial)
O cliente fornece as informações sobre cartão de crédito.
O cliente submete os dados ao sistema.
O sistema verifica as informações fornecidas, marca o pedido como "pendente" e envia as informações de pagamento para o sistema de contabilidade e pagamento.
Quando o pagamento é confirmado, o pedido é marcado como "confirmado" e o número de pedido (NP) é dado ao cliente.
Veja fluxo de eventos secundários ou alternativos

Pós-condição:

O pedido deve ter sido gravado no sistema e marcado como confirmado.
