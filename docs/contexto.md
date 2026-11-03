# Contexto

Durante um estágio em tecnologia, recebemos uma solicitação para investigar dúvidas de clientes no pagamento via Pix. Ao escanear o QR Code, o aplicativo bancário apresentava uma solicitação de autorização de cobrança automática.

O objetivo era entender o comportamento e contribuir com informações para a equipe esclarecer dúvidas e avaliar possíveis melhorias no checkout. O trabalho teve caráter de aprendizado e apoio à investigação.

## Escopo disponível

Tivemos acesso ao Stripe Dashboard para consultar pagamentos, assinaturas, faturas, produtos, metadados e registros de eventos. Também consultamos a documentação e o suporte da Stripe.

O estudo não incluiu auditoria do código ou da arquitetura interna. Não reproduzimos a integração neste repositório, não implementamos APIs e não realizamos uma correção de código.

## Pergunta central

Qual era a relação, se existente, entre a configuração de faturamento observada e a solicitação apresentada pelo banco?

Essa pergunta permaneceu sem resposta definitiva. Uma assinatura no gateway e uma autorização bancária são conceitos distintos; a presença de uma não comprova a existência ou a causa da outra.
