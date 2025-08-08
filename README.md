# Teste Técnico - Tamy AI 🍽️

## Sobre a Tamy AI

Somos uma foodtech que está revolucionando o mercado de bares e restaurantes com uma plataforma de analytics friendly com inteligência artificial. Nosso produto entrega insights e automações que aumentam a margem, otimizam custos e ajudam donos a tomar decisões mais inteligentes.

## 🎯 Objetivo

Avaliar suas habilidades práticas com nossa stack e capacidade de entender o contexto de negócio de restaurantes no Brasil.

## 📋 Desafio: Sistema de Pedidos Simples

Crie um sistema básico de gestão de pedidos para um restaurante.

### Funcionalidades Obrigatórias

1. **Autenticação simples** - Login/registro básico
2. **CRUD de Produtos** - Nome, preço, categoria (comida/bebida/sobremesa)
3. **Criar Pedido** - Adicionar produtos, calcular total, definir pagamento (PIX/Cartão/Dinheiro)
4. **Dashboard** - Faturamento do dia, quantidade de pedidos, ticket médio
5. **Lista de Pedidos** - Visualizar pedidos com status

### 🛠️ Stack Obrigatória

**Backend:**
- NestJS + TypeScript
- PostgreSQL (ou SQLite)
- MikroORM
- JWT para auth

**Frontend:**
- Next.js 14 + TypeScript
- Tailwind CSS + Shadcn UI
- React Hook Form + Zod

### 📊 Dados de Exemplo

```typescript
const produtos = [
  { nome: "X-Burger", preco: 25.90, categoria: "comida" },
  { nome: "Coca-Cola", preco: 6.50, categoria: "bebida" },
  { nome: "Pudim", preco: 8.90, categoria: "sobremesa" }
];
```

## 🎨 Interface

### Páginas Mínimas
1. **Login** - Autenticação simples
2. **Dashboard** - Métricas principais
3. **Produtos** - Lista e formulário
4. **Novo Pedido** - Interface para criar pedido
5. **Pedidos** - Lista de pedidos

### Design
- Use Tailwind CSS + Shadcn UI
- Interface limpa e intuitiva
- Responsivo para tablet/desktop

## 📝 Critérios de Avaliação

### ✅ Obrigatório (Eliminatório)
- [ ] Projeto roda sem erros
- [ ] Todas as funcionalidades básicas funcionam
- [ ] Código em TypeScript
- [ ] Uso correto das tecnologias especificadas

### ⭐ Diferencial
- [ ] Interface bem polida
- [ ] Tratamento de erros
- [ ] Validações com Zod
- [ ] 1-2 testes básicos
- [ ] Código limpo e organizado

### 🚀 Extra (Opcional)
- [ ] Real-time com WebSocket
- [ ] Sistema de notificações
- [ ] Filtros no dashboard
- [ ] Considerações de UX para restaurantes

## ⏱️ Tempo Estimado: 2-3 horas

## 📤 Entrega

1. **Repositório GitHub** com código completo
2. **README.md** explicando:
   - Como rodar o projeto
   - Estrutura do código
   - Funcionalidades implementadas

## ❌ O que NÃO fazer

- Não over-engineer - mantenha simples
- Não implemente features desnecessárias
- Não use bibliotecas não especificadas
- Não ignore o contexto de restaurante brasileiro
- Não deixe o projeto sem rodar

## 💡 Dicas

- Foque na qualidade, não na quantidade
- Teste o fluxo completo antes de entregar
- Documente decisões importantes
- Considere o contexto de uso (restaurante)

## 🎯 O que Avaliamos

- **Capacidade técnica** com nossa stack
- **Entendimento do negócio** e contexto
- **Qualidade do código** e boas práticas
- **Capacidade de organização** e documentação

---

**Boa sorte! 🍕✨**

*Dúvidas? Entre em contato conosco!*

## ❓ FAQ

**Q: Posso usar outras bibliotecas?**
A: Use apenas as especificadas. Foque na qualidade com as ferramentas definidas.

**Q: Preciso implementar todas as funcionalidades?**
A: Sim, as obrigatórias são eliminatórias. Os diferenciais são pontos extras.

**Q: Posso usar SQLite em vez de PostgreSQL?**
A: Sim, para facilitar o desenvolvimento.

**Q: O que fazer se não conseguir terminar?**
A: Entregue o que conseguir funcionando. Qualidade > quantidade.
