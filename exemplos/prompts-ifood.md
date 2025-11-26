# Exemplos Práticos de Prompts para iFood Gen AI Plat

Este documento contém exemplos detalhados de prompts otimizados para uso na plataforma Gen AI Plat do iFood, focando nos principais casos de uso identificados na arquitetura da plataforma: geração automática de descrições, otimização de preços, análise de dados operacionais, detecção de anomalias, campanhas de marketing personalizadas, comunicação inteligente com clientes, sistemas de recomendação híbridos e otimização de inventário.

**Casos de Uso Prioritários do Gen AI Plat:**
- **Geração de Conteúdo**: Descrições de pratos, campanhas de marketing, comunicações personalizadas
- **Análise de Dados**: Previsão de demanda, detecção de fraudes, insights operacionais
- **Otimização Operacional**: Precificação dinâmica, recomendações inteligentes, gestão de inventário
- **Experiência do Cliente**: Suporte automatizado, notificações contextuais, personalização

**Características Técnicas Consideradas:**
- Integração nativa com sistemas do iFood
- Suporte a múltiplos modelos de IA (Grok, Cohere, outros)
- Escalabilidade para milhões de operações diárias
- Conformidade com regulamentações brasileiras (LGPD)
- Foco em resultados de negócio mensuráveis

## 🏪 Prompts para Otimização de Catálogos e Cardápios

### Prompt 1: Geração Automática de Descrições de Pratos
```
Persona: Você é um especialista em copywriting para gastronomia brasileira no iFood
Contexto: Um restaurante de culinária mineira quer otimizar suas descrições de pratos para aumentar as taxas de conversão
Tarefa: Gere descrições atraentes e otimizadas para SEO para os seguintes pratos:

1. Feijoada Completa (R$ 45,90)
2. Tropeiro Mineiro (R$ 32,90)
3. Tutu de Feijão (R$ 28,90)

Formato: Para cada prato, forneça:
- Título otimizado (máximo 60 caracteres)
- Descrição atrativa (100-150 palavras)
- Palavras-chave relevantes para busca
- Elementos visuais sugeridos
- Benefícios nutricionais destacados

Restrições:
- Linguagem brasileira contemporânea
- Foco em ingredientes frescos e tradicionais
- Ênfase em experiência gastronômica
- Compatível com mobile (descrições concisas)
```

### Prompt 2: Otimização de Preços Baseada em Dados
```
Persona: Analista de pricing e revenue optimization do iFood
Contexto: Dados reais de performance de um restaurante de comida japonesa em São Paulo
Tarefa: Analise os dados fornecidos e sugira otimizações de preço para maximizar revenue

Dados disponíveis:
- Sushi Hot: R$ 28,90 | Taxa de conversão: 4.2% | Margem atual: 35%
- Combinado 30 peças: R$ 52,90 | Taxa de conversão: 6.1% | Margem atual: 42%
- Temaki Salmão: R$ 24,90 | Taxa de conversão: 3.8% | Margem atual: 38%

Benchmark de mercado:
- Preço médio sushi hot: R$ 32,00
- Preço médio combinado: R$ 48,00
- Preço médio temaki: R$ 22,00

Objetivos:
- Aumentar margem geral para 45%
- Manter competitividade no mercado
- Maximizar percepção de valor premium

Formato: Para cada item, forneça:
1. Preço otimizado recomendado
2. Justificativa baseada em dados
3. Impacto projetado na margem
4. Estratégia de comunicação do preço
```

## 📊 Prompts para Análise de Dados e Insights Operacionais

### Prompt 3: Previsão de Demanda por Bairro
```
Persona: Cientista de dados do iFood especializado em forecast de demanda
Contexto: Dados históricos de pedidos por bairro em Belo Horizonte durante o período de volta às aulas
Tarefa: Desenvolva um modelo de previsão de demanda para otimizar alocação de entregadores

Dados disponíveis:
- Histórico de 6 meses por bairro
- Padrões horários de pico
- Correlação com eventos locais (shows, jogos, feriados)
- Impacto de condições climáticas
- Dados demográficos por região

Variáveis a considerar:
- Volume de pedidos por hora
- Tempo médio de entrega
- Taxa de cancelamento
- Satisfação do cliente por região

Formato: Forneça um relatório completo incluindo:
1. Padrões identificados nos dados históricos
2. Fatores externos que impactam a demanda
3. Modelo de previsão recomendado
4. Recomendações operacionais específicas
5. Métricas de monitoramento do modelo

Restrições: Foque em soluções implementáveis no Gen AI Plat do iFood
```

### Prompt 4: Detecção de Anomalias em Pedidos
```
Persona: Analista de fraud prevention do iFood
Contexto: Sistema de detecção automática de pedidos suspeitos usando machine learning
Tarefa: Analise padrões de comportamento do usuário e identifique pedidos com alto risco de fraude

Perfil do usuário analisado:
- Histórico: 45 pedidos nos últimos 6 meses
- Valor médio: R$ 67,90
- Frequência: 2-3 pedidos por semana
- Horários típicos: 19h-21h (dias úteis)
- Métodos de pagamento: Cartão de crédito (80%), PIX (20%)

Pedido suspeito atual:
- Valor: R$ 245,90 (acima do padrão)
- Horário: 14h30 (fora do padrão usual)
- Endereço: Diferente do histórico (mesmo bairro)
- Método: Novo cartão de crédito
- Itens: Produtos premium não usuais

Critérios de avaliação:
- Desvio do padrão histórico
- Risco de chargeback
- Probabilidade de pedido legítimo
- Ações recomendadas (aprovar, revisar, bloquear)

Formato: Relatório de análise de risco incluindo:
1. Score de confiança (0-100)
2. Fatores de risco identificados
3. Probabilidade de fraude estimada
4. Recomendação de ação
5. Medidas preventivas sugeridas
```

## 🎨 Prompts para Geração de Conteúdo e Marketing

### Prompt 5: Campanhas de Reactivação de Usuários
```
Persona: Especialista em growth marketing do iFood com foco em retenção
Contexto: Usuário inativo há 45 dias, último pedido foi de comida italiana, valor médio R$ 52, perfil: jovem profissional 25-35 anos
Tarefa: Crie uma campanha personalizada de reactivação em 3 etapas (email + push + SMS)

Estrutura da campanha:
1. **Email de Reativação** (Dia 1)
   - Linha de assunto atraente
   - Corpo personalizado com recomendações
   - Call-to-action claro
   - Elementos visuais sugeridos

2. **Push Notification** (Dia 3)
   - Mensagem curta e impactante
   - Oferta personalizada baseada no histórico
   - Urgência limitada no tempo

3. **SMS de Última Chance** (Dia 7)
   - Mensagem concisa (máximo 140 caracteres)
   - Desconto progressivo
   - Link direto para pedido

Requisitos de personalização:
- Use dados demográficos do usuário
- Referencie último pedido e preferências
- Inclua ofertas contextuais (horário, localização)
- Mantenha tom amigável e não invasivo

Formato: Campanha completa pronta para implementação no sistema de marketing do iFood
```

### Prompt 6: Otimização de Descrições de Restaurantes
```
Persona: SEO specialist e copywriter para plataformas de delivery
Contexto: Restaurante recém-cadastrado no iFood precisa de descrição otimizada para aparecer nas buscas
Tarefa: Otimize a descrição do restaurante baseada nas melhores práticas de SEO e conversão

Dados do restaurante:
Nome: Burger Lab São Paulo
Especialidade: Hambúrgueres gourmet artesanais
Público-alvo: Jovens adultos 20-35 anos, foodies
Localização: Vila Madalena, SP
Diferencial: Ingredientes orgânicos, combinações inovadoras
Preço médio: R$ 38-55

Descrição atual (muito básica):
"Hambúrgueres artesanais feitos com ingredientes frescos"

Otimização requerida:
1. **Título otimizado** (máximo 60 caracteres)
2. **Descrição principal** (150-200 palavras)
3. **Palavras-chave estratégicas** (primárias e secundárias)
4. **Elementos de conversão** (benefícios, urgência, prova social)
5. **Chamadas para ação** (CTA) específicas

Critérios de sucesso:
- Aparecer nas buscas por "hambúrguer artesanal SP"
- Taxa de click-through > 3%
- Conversão para pedido > 15%
- Linguagem alinhada com o público jovem
```

## 💬 Prompts para Comunicação e Suporte ao Cliente

### Prompt 7: Respostas Personalizadas para Reclamações
```
Persona: Especialista em customer success do iFood com foco em resolução de conflitos
Contexto: Cliente reclamou sobre pedido atrasado (45 minutos além do previsto), restaurante já confirmou que comida está pronta
Tarefa: Gere uma resposta personalizada que resolva a situação e recupere a confiança do cliente

Perfil do cliente:
- Primeiro pedido no iFood
- Valor do pedido: R$ 87,50
- Tipo de comida: Comida japonesa
- Status: VIP (pedidos acima de R$ 50)
- Histórico: Sem reclamações anteriores

Elementos obrigatórios na resposta:
1. **Empatia imediata** - Reconheça o problema e demonstre compreensão
2. **Explicação clara** - Justifique o atraso sem culpar o restaurante
3. **Solução concreta** - Ofereça compensação adequada ao perfil do cliente
4. **Ação preventiva** - Garanta que não acontecerá novamente
5. **Oferta adicional** - Proponha algo extra para compensar

Parâmetros de compensação:
- Para pedidos até R$ 50: Cupom de R$ 15
- Para pedidos R$ 50-100: Cupom de R$ 25 + frete grátis
- Para pedidos acima R$ 100: Cupom de R$ 35 + frete grátis

Formato: Resposta completa pronta para envio, incluindo saudação personalizada e assinatura profissional
```

### Prompt 8: Notificações Contextuais de Status
```
Persona: UX writer especializado em notificações móveis para apps de delivery
Contexto: Sistema de notificações inteligentes do iFood que se adapta ao contexto do usuário
Tarefa: Crie um conjunto de notificações personalizadas para diferentes estágios do pedido

Cenário: Usuário pediu comida italiana em domicílio, valor R$ 67,90, horário de pico (19h)

Sequência de notificações:

1. **Confirmação de Pedido** (Imediata)
   - Confirme que pedido foi recebido
   - Mostre tempo estimado realista
   - Incentive acompanhar pelo app

2. **Atualização de Preparo** (Aos 10 minutos)
   - Informe que restaurante iniciou preparo
   - Destaque itens especiais do pedido
   - Mantenha engajamento positivo

3. **Saiu para Entrega** (Quando efetivamente sair)
   - Nome e foto do entregador
   - Tempo real de chegada
   - Opção de contato direto

4. **Chegou no Destino** (Quando chegar)
   - Código de verificação
   - Instruções para recebimento
   - Lembrete da avaliação

Personalização baseada em:
- Valor do pedido (VIP vs regular)
- Tipo de comida (quentinha vs fria)
- Horário (pico vs normal)
- Histórico de comportamento

Formato: Para cada notificação, forneça:
- Texto principal (máximo 120 caracteres)
- Título da notificação
- Sugestões de emoji e ícones
- Ações disponíveis (se aplicável)
```

## 🚀 Prompts para Inovação e Otimização Operacional

### Prompt 9: Sistema de Recomendação Híbrido
```
Persona: Data scientist especializado em sistemas de recomendação para e-commerce
Contexto: O iFood quer implementar um sistema de recomendação que combine múltiplas fontes de dados para aumentar o valor médio do pedido
Tarefa: Desenhe uma arquitetura completa de sistema de recomendação híbrido

Componentes obrigatórios:
1. **Dados de Entrada**
   - Histórico de pedidos do usuário
   - Comportamento de navegação
   - Preferências explícitas (avaliações, favoritos)
   - Dados contextuais (hora, localização, clima)

2. **Mecanismos de Recomendação**
   - Collaborative filtering (usuários similares)
   - Content-based filtering (itens similares)
   - Popularity-based (trending items)
   - Context-aware (baseado em situação)

3. **Lógica Híbrida**
   - Como combinar diferentes abordagens
   - Peso dinâmico baseado no contexto
   - Fallback strategies para cold start

4. **Personalização Avançada**
   - Segmentação de usuários (novos vs recorrentes)
   - Adaptação em tempo real
   - Diversificação de recomendações

5. **Métricas de Sucesso**
   - Aumento no valor médio do pedido
   - Taxa de click-through das recomendações
   - Tempo de descoberta de novos itens
   - Satisfação do usuário

Formato: Arquitetura técnica completa com diagramas descritivos e justificativas para cada componente
```

### Prompt 10: Otimização de Inventário com Previsão
```
Persona: Supply chain analyst do iFood especializado em otimização de inventário
Contexto: Restaurante parceiro enfrenta perdas por excesso de estoque e falta de ingredientes populares
Tarefa: Implemente um sistema de previsão de demanda por ingrediente para otimizar compras e reduzir desperdício

Dados disponíveis:
- Histórico de vendas por prato (últimos 12 meses)
- Sazonalidade por ingrediente
- Tempo de validade dos produtos
- Custo de descarte vs custo de falta
- Dados externos (clima, eventos locais, feriados)

Modelo requerido:
1. **Previsão de Demanda**
   - Por ingrediente individual
   - Por prato composto
   - Considerando sazonalidade e eventos

2. **Otimização de Compras**
   - Quantidade ideal por pedido
   - Frequência de reposição
   - Margem de segurança

3. **Redução de Perdas**
   - Alertas de sobre-estoque
   - Sugestões de uso alternativo
   - Otimização de porções

4. **Dashboard de Controle**
   - Métricas em tempo real
   - Alertas automáticos
   - Relatórios de performance

Benefícios esperados:
- Redução de 30% em perdas por vencimento
- Aumento de 15% na eficiência de compras
- Melhoria de 25% na disponibilidade de itens populares

Formato: Sistema completo com lógica de negócio, alertas, e métricas de acompanhamento
```

---

## 📝 Templates de Prompt

### Template Básico
```
Persona: [Defina o papel do Grok]
Contexto: [Situação específica do iFood]
Tarefa: [O que você precisa que seja feito]
Formato: [Como quer a resposta estruturada]
Restrições: [Limites ou regras específicas]
```

### Template Avançado
```
Como [especialista específico], [descrição da tarefa complexa].
Considere [contexto adicional importante].
Forneça [formato específico da resposta].
Certifique-se de [restrições ou requisitos especiais].
Baseie suas recomendações em [fonte de dados ou conhecimento específico].
```

---

*Estes exemplos podem ser adaptados conforme suas necessidades específicas. Lembre-se de testar diferentes variações para obter os melhores resultados.*
