# Plano de Implementação

## Fase 1 - Fundação (2-3 semanas)

### Autenticação
- [x] Login com Google
- [ ] Login com Apple (MVP+1)
- [ ] Login com Facebook (MVP+1)

### Cursos
- [ ] Visualizador básico
- [ ] Sistema de progresso
- [ ] Certificados (MVP+1)

### Gamificação
- [ ] Sistema básico de Karma
- [ ] Implementação de Ligas
- [ ] Limites diários
- [ ] Eventos especiais (MVP+1)

### Pagamentos
- [ ] Integração com Stripe
- [ ] Sistema de divisão de receita
- [ ] Assinaturas (MVP+1)

## Fase 2 - Crescimento (2-3 semanas)

### Sistema de Afiliados
- [ ] Rastreamento básico
- [ ] Links combinados
- [ ] Dashboard de afiliados

### Leaderboards
- [ ] Rankings diários
- [ ] Rankings semanais
- [ ] Rankings mensais
- [ ] Categorias principais:
  - [ ] Karma
  - [ ] Cursos
  - [ ] Indicações

### Analytics
- [ ] Métricas básicas
- [ ] Dashboard em tempo real (MVP+1)
- [ ] Detecção de fraudes

## Fase 3 - Engajamento (2-3 semanas)

### Lives
- [ ] Streaming básico
- [ ] Sistema de gravação
- [ ] Quizzes ao vivo (MVP+1)

### Comunidade
- [ ] Feed social
- [ ] Sistema de comentários
- [ ] Sistema de moderação

### Notificações
- [ ] Push notifications
- [ ] E-mail notifications
- [ ] Notificações in-app

## Estrutura de Diretórios

```
src/
  ├── app/                    # Rotas e layouts
  ├── components/             # Componentes React
  │   ├── auth/              # Componentes de autenticação
  │   ├── courses/           # Componentes de cursos
  │   ├── gamification/      # Componentes de gamificação
  │   ├── leaderboard/       # Componentes de ranking
  │   └── marketplace/       # Componentes de marketplace
  ├── config/                # Configurações
  ├── contexts/              # Contextos React
  ├── hooks/                 # Hooks personalizados
  ├── lib/                   # Funções utilitárias
  ├── services/              # Serviços
  │   ├── analytics/         # Serviços de analytics
  │   ├── auth/             # Serviços de autenticação
  │   ├── gamification/     # Serviços de gamificação
  │   ├── marketplace/      # Serviços de marketplace
  │   └── payments/         # Serviços de pagamento
  ├── styles/               # Estilos globais
  └── types/                # Tipos TypeScript
```

## Métricas de Sucesso

### MVP (Mês 1)
- 50 usuários ativos
- 5 cursos publicados
- Taxa de conclusão > 30%
- Tempo médio no app > 10min

### Crescimento (Mês 3)
- 200 usuários ativos
- 20 cursos publicados
- Taxa de conclusão > 40%
- Tempo médio no app > 15min
- 10 afiliados ativos

### Consolidação (Mês 6)
- 500 usuários ativos
- 50 cursos publicados
- Taxa de conclusão > 50%
- Tempo médio no app > 20min
- 30 afiliados ativos
- GMV > R$50.000