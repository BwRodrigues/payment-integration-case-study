# O que aprendi na prática

## Stripe Dashboard

Aprendi a navegar pelo painel, consultar transações e identificar formas de pagamento. A análise de assinaturas e faturas ajudou a entender ciclos de faturamento e a localizar próximas cobranças programadas. Produtos e metadados forneceram contexto sobre planos, sem revelar toda a lógica da aplicação.

## APIs e integrações

Tive uma compreensão inicial da comunicação entre aplicativo, backend e gateway de pagamento. Os registros de chamadas de API ajudaram a reconhecer operações realizadas por uma integração.

Estudei os conceitos de PaymentIntent, Checkout Session e assinaturas, além da finalidade de webhooks. Não implementei esses recursos. Também percebi que uma configuração exibida no Dashboard não descreve necessariamente todos os parâmetros definidos pelo backend.

## Meios de pagamento

Aprendi a distinguir pagamento avulso e faturamento recorrente e tive contato com o conceito de Pix Automático, que envolve autorização para pagamentos futuros conforme as condições do serviço.

A relação entre Stripe, EBANX e bancos trouxe dúvidas sobre as responsabilidades de cada participante. Ainda preciso aprofundar esse entendimento; não confirmei o papel de cada um no caso investigado.

Uma assinatura cadastrada não é a mesma coisa que uma autorização bancária. Essa distinção foi importante para não concluir que a recorrência observada explicava, sozinha, a mensagem no banco.

## Investigação técnica

Pratiquei a identificação de um comportamento inesperado, a organização de evidências e a formulação de hipóteses. Consultei documentação oficial e suporte técnico e organizei informações para os desenvolvedores.

A principal dificuldade foi relacionar registros de partes diferentes do fluxo com acesso limitado. Reconhecer esse limite ajudou a separar fatos, interpretações e dúvidas ainda abertas.

## Desenvolvimento profissional

O estágio reforçou a importância de perguntar antes de alterar, ter cuidado com produção e trabalhar de forma colaborativa. Comunicar uma dúvida com clareza também contribui para a equipe, mesmo quando não há uma solução confirmada.

Este estudo representa um passo no aprendizado, sem demonstrar domínio avançado de pagamentos ou experiência de implementação dessas APIs.
