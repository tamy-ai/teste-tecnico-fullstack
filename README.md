# Teste Técnico - Tamy AI 🍽️

## Sobre a Tamy AI

A Tamy AI é uma foodtech que está revolucionando o mercado de bares e restaurantes com uma plataforma de analytics friendly com inteligência artificial. Nosso produto entrega insights e automações que aumentam a margem, otimizam custos e ajudam donos a tomar decisões mais inteligentes.

## Objetivo do Teste

Este teste tem como objetivo avaliar suas habilidades práticas com as tecnologias que utilizamos no dia a dia, bem como sua capacidade de entender o contexto de negócio e implementar soluções que fazem sentido para o setor de restaurantes no Brasil.

## 🎯 Desafio: Sistema de Gestão de Pedidos

Você deve criar um sistema simples de gestão de pedidos para um restaurante, implementando as funcionalidades básicas que um dono de restaurante precisaria para gerenciar suas vendas.

### 📋 Funcionalidades Obrigatórias

1. **Cadastro de Produtos**
   - Nome, preço, categoria (bebida, comida, sobremesa)
   - Status ativo/inativo

2. **Registro de Pedidos**
   - Adicionar produtos ao pedido
   - Calcular total automaticamente
   - Definir método de pagamento (PIX, Cartão de Crédito, Dinheiro)
   - Status do pedido (pendente, em preparo, pronto, entregue)

3. **Dashboard de Vendas**
   - Faturamento do dia
   - Quantidade de pedidos
   - Ticket médio
   - Produtos mais vendidos
   - Métodos de pagamento mais utilizados

### 🛠️ Stack Obrigatória

**Backend:**
- NestJS + TypeScript
- PostgreSQL (ou SQLite para facilitar)
- MikroORM (ou TypeORM)
- JWT para autenticação

**Frontend:**
- Next.js 14 + TypeScript
- Tailwind CSS
- Shadcn UI
- SWR para data fetching
- React Hook Form + Zod

### 📊 Dados de Exemplo

Crie alguns dados de exemplo para testar o sistema:

```typescript
// Produtos de exemplo
const produtos = [
  { nome: "X-Burger", preco: 25.90, categoria: "comida" },
  { nome: "Batata Frita", preco: 12.50, categoria: "comida" },
  { nome: "Coca-Cola", preco: 6.50, categoria: "bebida" },
  { nome: "Pudim", preco: 8.90, categoria: "sobremesa" }
];

// Pedidos de exemplo (últimas 24h)
const pedidos = [
  { produtos: ["X-Burger", "Coca-Cola"], total: 32.40, metodoPagamento: "PIX", status: "entregue" },
  { produtos: ["Batata Frita", "Pudim"], total: 21.40, metodoPagamento: "cartao", status: "pronto" },
  // ... mais alguns pedidos
];
```

## 🎨 Interface

### Páginas Obrigatórias

1. **Login/Registro** - Autenticação simples
2. **Dashboard** - Visão geral das vendas
3. **Produtos** - CRUD de produtos
4. **Novo Pedido** - Interface para criar pedidos
5. **Histórico de Pedidos** - Lista de pedidos com filtros

### Design

- Use Tailwind CSS para estilização
- Implemente componentes do Shadcn UI
- Foque em uma interface limpa e intuitiva
- Considere que será usado em tablets/desktop no restaurante

## 🧪 Testes

Implemente pelo menos:
- 1 teste unitário para o service de produtos
- 1 teste unitário para o service de pedidos
- 1 teste de integração para a API de pedidos

## 📝 Critérios de Avaliação

### ✅ Obrigatório (Eliminatório)
- [ ] Projeto roda sem erros
- [ ] Todas as funcionalidades obrigatórias implementadas
- [ ] Código em TypeScript
- [ ] Uso correto das tecnologias especificadas
- [ ] Estrutura de projeto organizada

### ⭐ Diferencial
- [ ] Interface responsiva e bem polida
- [ ] Tratamento de erros adequado
- [ ] Validações com Zod
- [ ] Testes implementados
- [ ] Documentação da API
- [ ] Considerações de performance
- [ ] Código limpo e bem estruturado

### 🚀 Extra (Pontos Extras)
- [ ] Implementação de real-time (WebSocket)
- [ ] Sistema de notificações
- [ ] Exportação de relatórios
- [ ] Filtros avançados no dashboard
- [ ] Considerações de UX para restaurantes

## 📤 Entrega

1. **Repositório GitHub** com o código completo
2. **README.md** explicando:
   - Como rodar o projeto
   - Estrutura do código
   - Decisões técnicas tomadas
   - Funcionalidades implementadas

3. **Tempo estimado**: 4-6 horas

## 💡 Dicas

- Foque na qualidade do código, não na quantidade de features
- Considere o contexto de uso (restaurante brasileiro)
- Use boas práticas de desenvolvimento
- Documente decisões importantes
- Teste o fluxo completo antes de entregar

## 🎯 O que Avaliamos

- **Capacidade técnica** com as tecnologias
- **Entendimento do negócio** e contexto
- **Qualidade do código** e boas práticas
- **Capacidade de organização** e documentação
- **Criatividade** na solução de problemas

---

**Boa sorte! 🍕✨**

*Dúvidas? Entre em contato conosco!*
