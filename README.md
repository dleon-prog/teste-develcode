# Sistema de Criação de Pedidos de Compra

Esse é um teste meu "Deleon Leite" para uma vaga na develcode

## Funcionalidades

- Criação de pedidos de compra.
- Simulação de processamento de pagamento.
- Cancelamento automático de pedidos quando o pagamento falha.
- Arquitetura baseada em microsserviços e implementada com o padrão **Observer** para notificação de cancelamentos.

## Tecnologias Utilizadas

- **Node.js**: Plataforma de execução de JavaScript.
- **TypeScript**: Linguagem utilizada para tipagem estática e melhor organização do código.
- **Express**: Framework para criação de API REST.
- **Event-driven pattern**: Padrão Observer para

## Executar o teste
- npm install express @types/express typescript
- npx tsc
- node dist/index.js

## Testar
- curl -X POST http://localhost:3000/checkout/order -H "Content-Type: application/json" -d '{"amount": 100.0}'
