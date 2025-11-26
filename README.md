# Oracle & iFood: friendly repo

Time iFood, sejam bem-vindos!

Este espaço é dedicado a desenvolvedores e usuários de negócio do iFood que desejam explorar o potencial da Inteligência Artificial Generativa através dos serviços da Oracle Cloud Infrastructure (OCI), seja no iFood Gen AI Plat utilizando nossos LLMs disponíveis por lá, ou diretamente via cloud em novos projetos.

Contem sempre com o time Oracle para empreender projetos de AI. Queremos fazer coisas incríveis com o iFood.

## 🎯 Sobre Este Repositório

Este repositório serve como um **ponto de encontro** entre as equipes técnicas e de negócio do iFood e o time de IA da Oracle. Aqui você encontrará:

- Guia e casos de uso para Grok Code Fast I em contextos de desenvolvimento de software
- Guia e casos de uso para modelos Grok no iFood Gen AI Plat
- Guia e casos de uso para modelos Cohere no iFood Gen AI Plat
- Exemplos de Prompts para contextos iFood
- Links diversos de documentações Oracle que possam ser interessante
- Contatos com o time Oracle

---

## 🤖 SEÇÃO 1: MODELOS GROK 4 NO IFOOD GEN AI PLAT

### Versatilidade e Performance Avançada
Os modelos Grok 4 (Base, Fast Reasoning, No-Reasoning) são líderes em versatilidade e criatividade, oferecendo equilíbrio perfeito entre análise, geração de conteúdo e processamento eficiente.

**Modelos disponíveis:**
- 🎨 **Grok 4 Base**: Criatividade e raciocínio geral equilibrado
- ⚡ **Grok 4 Fast Reasoning**: Análise rápida e decisões ágeis
- 🎯 **Grok 4 No-Reasoning**: Execução direta e processamento de alto volume

**[Ver guia completo dos modelos Grok 4 →](grok4-models-ifood.md)**

---

## 🤖 SEÇÃO 2: GROK CODE FAST I - DESENVOLVIMENTO DE SOFTWARE

### O Poder da IA para Desenvolvimento
Grok Code Fast I é um modelo revolucionário otimizado para desenvolvimento de software, oferecendo velocidade excepcional e qualidade superior no código gerado.

**Características principais:**
- ⚡ **Velocidade ultra-rápida**: Respostas em milissegundos
- 🛠️ **Multi-linguagem**: Suporte para 50+ linguagens
- 🔍 **Análise inteligente**: Detecção automática de bugs e vulnerabilidades
- 📚 **Documentação automática**: Código auto-documentado e bem estruturado

**[Ver guia completo de desenvolvimento →](grok-code-fast-1.md)**

---

## 🧠 SEÇÃO 3: MODELOS COHERE AVANÇADOS NO IFOOD GEN AI PLAT

### Command A e Embed 4: Estado da Arte em IA Generativa
Os modelos Cohere Command A (conversação avançada) e Embed 4 (embeddings multimodais) oferecem capacidades de última geração para processamento de linguagem natural e busca semântica inteligente.

**Modelos disponíveis:**
- 🎯 **Cohere Command A**: Conversação avançada, RAG otimizado, agentes inteligentes
- 🔍 **Cohere Embed 4**: Embeddings multimodais (texto + imagem), busca semântica de alta precisão

**[Ver guia completo dos modelos Cohere →](cohere-new-models-ifood.md)**

---

## 🚀 SEÇÃO 4: EXEMPLOS DE PROMPTS PARA CENÁRIOS DO IFOOD

### 4.1 Geração Automática de Descrições de Pratos
**Caso de Uso Real do Gen AI Plat**: Otimização de catálogos com descrições SEO-friendly

**Prompt Otimizado:**
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

### 4.2 Otimização de Preços Baseada em Dados
**Caso de Uso Real do Gen AI Plat**: Precificação dinâmica inteligente

**Prompt Analítico:**
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

### 4.3 Previsão de Demanda por Bairro
**Caso de Uso Real do Gen AI Plat**: Forecast operacional para delivery

**Prompt de Forecast:**
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

### 4.4 Detecção de Anomalias em Pedidos
**Caso de Uso Real do Gen AI Plat**: Fraud prevention inteligente

**Prompt de Análise de Risco:**
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

---

## 📚 SEÇÃO 6: LINKS DE DOCUMENTAÇÃO ORACLE

### Documentação Principal de IA Generativa
- **[Documentação-Mãe de Gen AI](https://lnkd.in/dABCrk3U)**: Portal completo com tudo sobre Inteligência Artificial Generativa na Oracle

### Modelos de Linguagem e APIs
- **[LLMs Fundacionais via API](https://lnkd.in/de6cdeEp)**: Acesso aos modelos como Grok da xAI e outros através da Oracle Cloud
- **[Serviço de Agentes Gerenciados](https://lnkd.in/dxHbid8U)**: Perfeito para agentes com poucas ferramentas especializadas
- **[Oracle LangChain Integration](https://lnkd.in/d5CzpK-t)**: Fork do LangChain otimizado para serviços Oracle

### Bancos de Dados com IA
- **[Oracle AI Database 26ai](https://lnkd.in/daQVnKCx)**: Apresentação do banco mais contemporâneo da Oracle
- **[Documentação 26ai](https://lnkd.in/diaeg7Fr)**: Guia técnico completo do Oracle Database 26ai
- **[HeatWave MySQL](https://lnkd.in/dqGG59Zd)**: Oracle MySQL de altíssima disponibilidade

### Plataformas e Integrações
- **[AI Data Platform](https://lnkd.in/dgqhhkyf)**: Plataforma lançada no AI World 2024 que integra todos os recursos de IA
- **[Guardrails para Agentes](https://lnkd.in/dGHzYW3q)**: Documentação de proteções e controles para modelos e agentes
- **[LiteLLM Integration](https://lnkd.in/dfv_BrAd)**: Integração com LiteLLM (Y Combinator W23) para pipelines multimodelo

### Recursos de Capacitação
- **[Oracle Certification Portal](https://www.oracle.com/education/certification/)**: Todas as certificações disponíveis
- **Certificações Essenciais**: Oracle Cloud Infrastructure Foundations Associate, Oracle Cloud AI Foundations Associate
- **Certificações Avançadas**: Oracle Cloud Infrastructure Architect Professional, Oracle Cloud Infrastructure Generative AI Professional
- **[Oracle MyLearn](https://www.oracle.com/br/education/mylearn/)**: Plataforma de aprendizado personalizada
- **[Oracle Guided Learning](https://www.oracle.com/br/education/guided-learning/)**: Orientação no aplicativo para adoção digital

---

## 🤝 SEÇÃO 7: ENTRE EM CONTATO

Vamos criar coisas novas e first of a kind juntos? Nossa equipe está disponível para colaborar com você!

**Entre em contato conosco:**

- **Evandro Melo**: [evandro.melo@oracle.com](mailto:evandro.melo@oracle.com)
- **Daniel Gandolfi**: [daniel.gandolfi@oracle.com](mailto:daniel.gandolfi@oracle.com)

**Como queremos colaborar:**
- Consultoria técnica em implementação de IA
- Prospecção conjunta de oportunidades
- Demonstrações personalizadas dos serviços Oracle
- Suporte na criação de prompts e casos de uso
- Integração com sistemas existentes do iFood
- Avaliações de LLMs de fronteiras
- Desenvolvimento de SLMs
- Construção de prompts em conjunto para iFood Gen AI Plat

---

## 🎥 SEÇÃO 8: VÍDEOS SOBRE SOLUÇÕES ORACLE

### 1. IA Generativa na OCI & Fine-Tuning
(Prioridade: Canal Oracle Developers) Estes vídeos cobrem a teoria e a prática (hands-on) usando o serviço de GenAI da OCI.

#### Agentic AI Workflows in Oracle Integration with OCI Generative AI
**Canal: Oracle Developers**  
**Conteúdo**: Tutorial prático (Novembro 2025) sobre como criar agentes de IA e integrar fluxos de trabalho.  
**[Assistir ao vídeo](https://www.youtube.com/results?search_query=Agentic+AI+Workflows+in+Oracle+Integration+with+OCI+Generative+AI)**

#### Fine-tuning LLMs in OCI Generative AI Playground
**Canal: Oracle Developers**  
**Conteúdo**: Passo a passo específico para ajuste fino (fine-tuning) de modelos dentro do console da OCI.  
**[Assistir ao vídeo](https://www.youtube.com/results?search_query=Fine-tuning+LLMs+in+OCI+Generative+AI+Playground)**

#### Getting Started with Oracle Select AI
**Canal: Oracle Developers**  
**Conteúdo**: Focado em usar GenAI com seu banco de dados (Text-to-SQL) e geração aumentada (RAG).  
**[Assistir ao vídeo](https://www.youtube.com/results?search_query=Getting+Started+with+Oracle+Select+AI)**

### 2. Construção de Prompts para Cohere
(Prioridade: Parceria Oracle + Conteúdo Técnico) Como a Cohere é parceira nativa da Oracle, o conteúdo técnico mais profundo sobre prompts geralmente vem dos especialistas da própria Cohere ou de integrações mostradas pela Oracle.

#### Advanced RAG by Jay Alammar (Cohere) + Parameter-Efficient Fine-Tuning
**Canal: AWS / Cohere (Apresentado por Jay Alammar, uma autoridade na área)**  
**Conteúdo**: Essencial para entender como estruturar prompts para RAG, técnica muito usada na OCI.  
**[Assistir ao vídeo](https://www.youtube.com/results?search_query=Advanced+RAG+by+Jay+Alammar+Cohere)**

#### Cohere Prompt Tuner: Optimize Prompts Like a Pro
**Canal: AI Anytime (Recomendado pela comunidade técnica)**  
**Conteúdo**: Tutorial sobre a ferramenta de otimização automática de prompts da Cohere.  
**[Assistir ao vídeo](https://www.youtube.com/results?search_query=Cohere+Prompt+Tuner+Optimize+Prompts+Like+a+Pro)**

### 3. Construção de Prompts para Grok 4
(Fonte: Comunidade Técnica / xAI) O canal Oracle Developers não cobre Grok. Selecionei os tutoriais técnicos mais recentes e diretos.

#### How to Get the Grok 4 System Prompt
**Conteúdo**: Análise do prompt de sistema do Grok 4, crucial para entender a "personalidade" e como instruí-lo melhor.  
**[Assistir ao vídeo](https://www.youtube.com/results?search_query=How+to+Get+the+Grok+4+System+Prompt)**

#### Ultimate GROK 4 Guide: How to Use GROK For Beginners
**Conteúdo**: Guia completo cobrindo os modos de operação e melhores práticas de prompt.  
**[Assistir ao vídeo](https://www.youtube.com/results?search_query=Ultimate+GROK+4+Guide+How+to+Use+GROK+For+Beginners)**

### 4. Novidades do Oracle AI World 2026
(Prioridade: Canal Oracle Developers) As novidades futuras são frequentemente discutidas nas sessões de "Coaching" e updates mensais do canal.

#### Oracle Developer Coaching: November News Edition
**Canal: Oracle Developers**  
**Conteúdo**: Cobre anúncios recentes (como Oracle Database 26ai) e o roadmap que leva aos eventos de 2026.  
**[Assistir ao vídeo](https://www.youtube.com/results?search_query=Oracle+Developer+Coaching+November+News+Edition)**

---



*Este repositório é mantido pela equipe Oracle High Tech e destina-se exclusivamente ao ecossistema iFood. Para sugestões ou contribuições, entre em contato conosco.*
