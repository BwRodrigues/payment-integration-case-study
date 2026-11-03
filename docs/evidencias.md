# Evidências e hipóteses

Este registro resume as observações informadas pelos participantes. Não disponibiliza dados brutos ou evidências corporativas e não constitui uma verificação independente do ambiente original.

## Fatos observados no relato

| Observação | O que permite afirmar |
| --- | --- |
| O aplicativo bancário solicitava autorização de cobrança automática após a leitura do QR Code | Esse era o comportamento investigado; sua causa não foi estabelecida |
| Havia uma assinatura trimestral ativa com próxima fatura programada no Dashboard | O sistema utilizava faturamento recorrente em pelo menos esse registro |
| Havia produtos associados a identificadores de planos e registros de criação por API | Existiam referências a planos e operações via API |
| Documentação e suporte foram consultados e as informações encaminhadas aos desenvolvedores | Houve organização e comunicação da investigação |

## Hipóteses levantadas

- O aplicativo poderia gerenciar os planos e integrar seus dados à Stripe.
- Parâmetros definidos pela integração poderiam ser relevantes para compreender o fluxo observado.

Essas hipóteses não identificam o parâmetro, componente ou responsável pela mensagem bancária.

## Informações não confirmadas

- A causa exata da solicitação de autorização.
- O vínculo entre a assinatura observada e o pagamento que originou a dúvida.
- A modalidade de Pix efetivamente utilizada naquele fluxo.
- O papel específico de cada participante no processamento da transação.
- A existência de um defeito no checkout ou no banco e qual alteração seria necessária.

Uma próxima fatura programada não comprova autorização bancária nem garante que uma cobrança futura será paga. Não houve correção de código ou validação de uma solução.
