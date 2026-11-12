# 📚 ForgeOS — SOPs & 50 AI Prompts Library
*High-converting operational procedures and ready-to-use AI prompts for Freelancers and Micro-Agencies.*

---

## 📑 Seção 1: Standard Operating Procedures (SOPs)

### SOP 01: How to Qualify a New Lead
**Objetivo:** Filtrar leads desqualificados antes de gastar horas redigindo propostas personalizadas.
**Gatilho:** O prospect preenche o formulário de contato, envia direct ou solicita reunião.

#### Critérios BANT de Qualificação:
1. **Budget (Orçamento):** O cliente possui verba mínima viável para o serviço? (Ex: mínimo de $1.500 para projetos ou $2.500/mês para retainers).
2. **Authority (Autoridade):** A pessoa em contato é o tomador final de decisão ou tem acesso direto a ele?
3. **Need (Necessidade):** A dor do cliente está alinhada com seu serviço principal (core business)?
4. **Timing (Prazo):** A data de entrega esperada é factível sem comprometer a qualidade da sua operação?

#### Protocolo de Ação:
- [ ] Enviar formulário curto de qualificação (máximo 4 perguntas) antes de agendar qualquer call.
- [ ] Se o lead for qualificado: Enviar link do Cal.com / Calendly para call de descoberta de 20 minutos.
- [ ] Se o lead for desqualificado por orçamento: Enviar e-mail de declínio educado recomendando recursos gratuitos ou soluções de entrada.

---

### SOP 02: How to Send a Proposal
**Objetivo:** Apresentar propostas de alto impacto que fecham negócios sem disputa por preço.
**Gatilho:** Call de descoberta concluída com lead qualificado.

#### A Regra de Ouro da Apresentação:
> ⚠️ **Nunca envie apenas um PDF por e-mail.** Sempre agende uma call de 30 minutos para apresentar a proposta ao vivo ou envie um link com vídeo Loom interativo de 5 minutos explicando o raciocínio.

#### Estrutura em 5 Partes da Proposta:
1. **Diagnóstico do Problema:** Demonstre que você entendeu a dor e o objetivo do negócio melhor do que os concorrentes.
2. **Escopo da Solução:** Liste claramente o que será entregue (In-Scope) e o que NÃO está incluso (Out-of-Scope).
3. **Cronograma em Fases:** Roadmap visual dividido em semanas ou sprints com datas de aprovação.
4. **Opções de Investimento:** Apresente 3 opções (Essencial, Recomendado, Completo).
5. **Chamada para Ação Imediata:** Botão de aceite digital e emissão da fatura de entrada de 50%.

---

### SOP 03: Client Onboarding Process
**Objetivo:** Transmitir confiança imediata e coletar todos os acessos e assets em menos de 48 horas.
**Gatilho:** Contrato assinado e fatura de entrada confirmada.

#### Protocolo em 4 Etapas:
1. **D+0 (Imediato):** Enviar e-mail formal de boas-vindas com link do questionário de imersão e recibo de pagamento.
2. **D+1 (Coleta de Acessos):** Coletar arquivos vetoriais da marca (.SVG), acessos de hospedagem/CMS/API e criar canal exclusivo (Slack/WhatsApp).
3. **D+2 (Kickoff Call):** Realizar reunião de 45 minutos para alinhar canais de feedback e expectativas de entrega.
4. **D+3 (Setup do Workspace):** Liberar o Portal do Cliente no Notion e cadastrar o cronograma no ForgeOS.

---

### SOP 04: Handling Revision Requests
**Objetivo:** Preservar a margem de lucro e conter o escopo invisível (scope creep) mantendo o cliente satisfeito.
**Gatilho:** O cliente solicita alterações durante a entrega.

#### Regras de Ouro de Revisão:
1. **Consolidação Obrigatória:** Todas as alterações devem ser enviadas consolidadas por escrito (documento único ou comentários no Figma/Frame.io), nunca em áudios soltos ou mensagens picadas.
2. **Limite Contratual:** O escopo inclui até 2 rodadas completas de revisão. A terceira rodada é cobrada por hora ou taxa fixa.
3. **Diferença entre Ajuste e Novo Escopo:**
   - *Ajuste:* Mudança de cor, tipografia ou texto dentro do combinado.
   - *Novo Escopo:* Novas telas, novas integrações ou mudança radical de direção criativa.

#### Script de Resposta para Novo Escopo:
> *"Adoramos a ideia, [Nome do Cliente]! Ela traz muito valor para o produto. Como essa funcionalidade não estava prevista no escopo inicial do contrato, preparei um aditivo rápido:*
> *• Prazo adicional: +[X] dias úteis*
> *• Investimento adicional: $[Valor]*
> *Podemos seguir em frente com esse aditivo ou prefere priorizar o escopo atual e deixar essa evolução para uma fase posterior?"*

---

### SOP 05: Project Delivery & Handover
**Objetivo:** Concluir o projeto com excelência técnica, receber o saldo final e transformar o cliente em promotor da marca.
**Gatilho:** Aprovação da versão final pelo cliente.

#### Checklist de Handover:
1. **Organização Técnica:** Limpar camadas, nomes de arquivos, exportar ativos em alta resolução (.SVG, .PNG, .PDF).
2. **Vídeo Explicativo (Loom):** Gravar vídeo de até 5 minutos guiando o cliente sobre como usar, editar ou publicar o projeto.
3. **Compensação Financeira:** Emitir a fatura de encerramento do saldo restante. Liberar permissões de administrador somente após a confirmação do pagamento.
4. **Coleta de Depoimento & Upsell:** Enviar link de formulário de depoimento ou solicitar gravação rápida em vídeo, seguido da apresentação de um plano de suporte/retainer contínuo.

---

## 🤖 Seção 2: AI Prompts Library (50 Prompts Prontos para Uso)

### 🎯 Categoria 1: Prospection & Sales (Prompts 01 a 10)

#### Prompt 01: High-Converting Project Proposal Generator
```text
Atue como um estrategista comercial sênior especializado em serviços de alta renda para freelancers e microagências.
Crie uma proposta de projeto profissional e irresistível baseada nos seguintes dados:

- Nome do Cliente: [Client Name]
- Nicho / Mercado: [Niche/Industry]
- Principal Problema / Gargalo: [Client Problem]
- Solução Proposta: [Service/Solution]
- Investimento Sugerido: [Price/Investment]
- Prazo de Execução: [Timeline]

Estruture a proposta nas seguintes seções:
1. Diagnóstico do Cenário Atual (demonstre empatia e compreensão da dor do negócio)
2. Escopo Detalhado dos Entregáveis (especifique exatamente o que está incluso)
3. O que NÃO está incluso (Out-of-Scope explícito para evitar scope creep)
4. Cronograma de Entregas por Etapas (Fase 1 a Fase 3)
5. Opções de Investimento (Opção 1: À vista com bônus, Opção 2: Parcelado)
6. Próximo Passo Imediato para Iniciar o Projeto
```

#### Prompt 02: Cold Outreach Email to C-Level Decision Makers
```text
Você é um copywriter especialista em prospecção fria B2B de alta conversão.
Escreva um e-mail de abordagem fria (cold email) para o seguinte decisor:

- Nome do Decisor: [Decision Maker Name]
- Cargo: [Job Title, ex: CMO/CEO/Fundador]
- Nome da Empresa: [Company Name]
- O que nossa agência faz: [Our Service, ex: Desenvolvimento de landing pages de alta conversão em Webflow]
- Ponto Fraco Identificado na Empresa deles: [Specific Weakness, ex: Site atual não é responsivo e carrega em 5 segundos]
- Oferta Gratuita de Entrada (Lead Magnet / Teaser): [ex: Auditoria em vídeo de 3 minutos com 3 melhorias práticas]

Regras de Redação:
- Máximo de 120 palavras.
- Tom profissional, conciso e sem bajulação.
- Termine com uma pergunta de baixa fricção (CTA suave) convidando para ver o vídeo ou responder com um "sim".
```

#### Prompt 03: Price Objection Buster ("Your price is too high")
```text
Atue como um negociador consultivo para agências de serviços digitais.
Um cliente em potencial qualificado acabou de responder à nossa proposta comercial dizendo:
"Gostamos muito do seu trabalho e da equipe, mas achamos o valor de [Proposal Price] muito acima do nosso orçamento atual."

Escreva 3 opções de resposta profissional:
1. Opção Elegante com Redução de Escopo: Mantém o valor-hora alto, mas remove entregáveis secundários para caber no orçamento dele.
2. Opção com Condição Especial de Pagamento: Facilita o fluxo de caixa (ex: entrada menor + parcelas vinculadas a marcos).
3. Opção de Reafirmação do ROI: Demonstra matematicamente como o custo de NÃO resolver o problema é muito maior do que o preço cobrado.

Dados do Projeto:
- Serviço: [Service]
- Preço Proposto: [Proposal Price]
- Impacto Financeiro Esperado para o Cliente: [Expected Client ROI/Benefit]
```

#### Prompt 04: Elegant Follow-Up Sequence After Client Ghosting
```text
Você é um consultor de vendas para freelancers.
Crie uma sequência de 3 mensagens curtas de follow-up para um lead que recebeu nossa proposta de [Service] há 5 dias e parou de responder:

- Mensagem 1 (Dia 5 - Check-in Gentil): Verifica se restou alguma dúvida técnica sobre os entregáveis e valida se o prazo planejado ainda é prioritário.
- Mensagem 2 (Dia 9 - Agregação de Valor): Compartilha um exemplo rápido ou estudo de caso de um projeto similar sem cobrar resposta direta.
- Mensagem 3 (Dia 14 - Break-up Email / Encerramento de Contato): Avisa educadamente que estamos fechando a janela de disponibilidade da equipe para o mês e liberando a vaga para outro cliente. (Gera urgência genuína e frequentemente reativa o prospect).
```

#### Prompt 05: Value-First Audit & Pitch Teaser for Inbound Leads
```text
Você é um estrategista de aquisição de clientes.
Crie um roteiro de pitch em formato de mini-auditoria de 3 minutos para enviar a um cliente em potencial que entrou em contato pelo nosso site.

Dados do Lead:
- Cliente: [Client Name]
- Site / Rede Social: [Client URL/Profile]
- Nosso Serviço: [Service]

Estrutura do Roteiro:
1. Gancho Inicial (0-30s): Elogie um ponto forte legítimo da empresa dele.
2. Identificação da Oportunidade Oculta (30-90s): Aponte 2 erros críticos atuais que estão fazendo ele perder vendas/clientes.
3. Demonstração da Solução (90-150s): Mostre rapidamente a metodologia que usamos para resolver isso.
4. Chamada para Ação (150-180s): Convite para uma conversa de 15 minutos para ver o plano completo.
```

#### Prompt 06: Monthly Retainer Pitch for Past One-Off Clients
```text
Atue como um consultor de retenção e crescimento de agências.
Escreva um e-mail persuasivo para um ex-cliente para quem concluímos com sucesso o projeto [Past Project Name] há cerca de 60 dias.

Objetivo:
Apresentar uma proposta de Retainer Mensal Contínuo de [Retainer Service, ex: Otimização de conversão contínua, manutenção técnica e design sob demanda].

Argumentos Chave:
- Os ativos criados precisam de iteração e manutenção constante para não ficarem obsoletos.
- Ter nossa equipe com horas garantidas todo mês é mais barato e rápido do que contratar novos sprints avulsos.
- Apresente 2 pacotes mensais simples: Plano Essencial ($[Price 1]/mês) e Plano Crescimento ($[Price 2]/mês).
```

#### Prompt 07: Discovery Call Pre-Meeting Research & Question Generator
```text
Você é um diretor comercial experiente em vendas de serviços B2B.
Tenho uma reunião de descoberta de 30 minutos agendada com o seguinte prospect:

- Empresa: [Company Name]
- Nicho: [Niche]
- Perfil do Lead: [Prospect LinkedIn / Background]
- Nosso Serviço: [Service to Offer]

Gere:
1. 5 perguntas abertas de diagnóstico para descobrir a verdadeira dor financeira do cliente.
2. 3 perguntas estratégicas para descobrir quem são os tomadores de decisão e como o orçamento é aprovado.
3. 2 armadilhas comuns para evitar durante essa reunião com esse perfil de cliente.
```

#### Prompt 08: LinkedIn Personalized Connection Note & DM Opener
```text
Você é um especialista em prospecção no LinkedIn para profissionais criativos e técnicos.
Crie 3 modelos de mensagem de conexão no LinkedIn (menos de 300 caracteres) e 3 mensagens de acompanhamento (após aceite da conexão) para:

- Perfil Alvo: [Target Persona, ex: Fundadores de Startups SaaS B2B]
- Nosso Core: [Our Skill/Service, ex: Design de Produto e Prototipagem Figma]
- Ponto em Comum / Gancho: [Common Ground, ex: Post recente sobre novo lançamento ou crescimento da equipe]

Regra Fundamental:
Não tente vender na primeira mensagem. O objetivo é unicamente abrir uma conversa sincera sobre o desafio atual deles.
```

#### Prompt 09: High-Ticket Value Proposition & Elevator Pitch Refiner
```text
Atue como um posicionador de marcas de consultoria e agências premium.
Transforme a seguinte descrição genérica de serviços em uma Proposta Única de Valor (UVP) de alto padrão que justifique cobrar de 3x a 5x mais caro:

- Descrição Atual Genérica: [ex: Faço sites em WordPress e gerencio redes sociais]
- Público Alvo Ideal: [Target Audience]
- Maior Resultado Financeiro / Transformação que Geramos: [Big Result]

Entregue:
1. A Declaração de Posicionamento em 1 frase (Formato: "Nós ajudamos [Público] a alcançar [Resultado] através de [Método Único] sem [Maior Dor]").
2. Elevator Pitch de 30 segundos para reuniões de networking.
3. Headline institucional para colocar no topo da página de vendas.
```

#### Prompt 10: Inactive Client Re-engagement Campaign (6+ Months Dormant)
```text
Você é um especialista em reativação de carteira de clientes inativos.
Escreva um e-mail de reativação para uma lista de ex-clientes com quem não falamos há mais de 6 meses.

- Nosso Nome/Agência: [Agency Name]
- O que fizemos no passado: [Past Projects]
- Nova Metodologia / Novidade Operacional que Lançamos: [New Capability / Update]

O e-mail deve soar pessoal, caloroso e sem pressão de venda. O gancho principal deve ser conferir como o negócio deles performou nos últimos meses e oferecer uma sessão estratégica de 20 minutos gratuita para revisar os ativos atuais.
```

---

### 📋 Categoria 2: Briefing, Scope & Contracts (Prompts 11 a 20)

#### Prompt 11: Raw Meeting Transcript to Structured Scope Extractor
```text
Você é um gerente de projetos sênior (PMP) especializado em agências e consultorias digitais.
Analise as anotações brutas / transcrição da reunião com o cliente abaixo e transforme em um Briefing Técnico Executivo perfeitamente estruturado:

Anotações da Reunião:
[Cole aqui o texto ou transcrição da call]

Estrutura Obrigatória do Documento de Saída:
1. Objetivo Principal do Negócio (A meta número 1 que define o sucesso do projeto)
2. Lista Completa de Entregáveis Obrigatórios (In-Scope explícito)
3. O que NÃO será entregue nesta fase (Out-of-Scope explícito)
4. Dependências do Cliente (Arquivos, credenciais, aprovações necessárias)
5. Prazos e Marcos Críticos acordados
6. Riscos Técnicos ou de Negócio Identificados
```

#### Prompt 12: Bulletproof Statement of Work (SOW) Generator
```text
Atue como um especialista jurídico e de contratos para prestadores de serviços de tecnologia e design.
Crie uma Declaração de Trabalho (Statement of Work - SOW) completa e profissional pronta para anexar a um contrato de prestação de serviços com base nos seguintes dados:

- Contratante: [Client Legal Name]
- Contratado: [Your Name/Agency]
- Nome do Projeto: [Project Name]
- Descrição da Solução: [Detailed Solution]
- Entregáveis e Formatos: [Deliverables List]
- Fases de Validação e Critérios de Aceite: [Acceptance Criteria]
- Responsabilidades do Contratante: [Client Responsibilities]
- Valor Total e Condições de Pagamento: [Price & Terms]
```

#### Prompt 13: Explicit Out-of-Scope & Scope Creep Protection Clauses
```text
Você é um advogado corporativo especializado em contratos de prestação de serviços freelancers.
Escreva 4 cláusulas contratuais claras, rigorosas e em linguagem profissional para proteger nosso negócio contra pedidos fora do escopo (scope creep):

1. Cláusula de Limitação de Escopo: Define que qualquer solicitação não listada nominalmente no SOW constitui escopo adicional.
2. Cláusula de Procedimento de Solicitação de Mudança (Change Order): Estabelece que pedidos extras exigirão orçamento prévio e aprovação por escrito de custo e prazo adicionais antes de serem executados.
3. Cláusula de Limite de Revisões: Limita revisões a 2 rodadas consolidadas por entrega.
4. Cláusula de Dependências do Cliente: Isenta a agência de multas por atraso caso o cliente demore mais de 3 dias úteis para fornecer acessos ou feedbacks.
```

#### Prompt 14: Client Deep-Dive Onboarding Questionnaire Generator
```text
Você é um diretor de arte e estrategista de negócios.
Crie um formulário de imersão (briefing profundo) de 10 perguntas essenciais para enviar a um novo cliente do serviço [Service Name].

As perguntas devem cobrir:
- Contexto de negócio, modelo de monetização e metas financeiras dos próximos 12 meses.
- Identificação da persona real do cliente (dores, desejos, objeções de compra).
- Análise de 3 concorrentes diretos (o que eles fazem bem e o que fazem mal).
- Preferências visuais e referências estéticas que agradam e que desagradam.
- Critérios exatos que farão este projeto ser considerado um sucesso retumbante pela diretoria.
```

#### Prompt 15: Project Risk & Technical Dependency Assessment
```text
Atue como um diretor de operações técnicas (COO).
Avalie os seguintes dados de um novo projeto que estamos prestes a iniciar e gere uma Matriz de Riscos e Dependências Técnicas:

- Tipo de Projeto: [ex: Migração de e-commerce e redesign completo]
- Prazo Estimado: [Timeline]
- Ferramentas Envolvidas: [Tools, ex: Shopify, Klaviyo, Figma, APIs externas]
- Equipe Alocada: [Team Size]

Entregue:
1. Tabela com os 5 maiores riscos potenciais (Impacto: Alto/Médio/Baixo, Probabilidade: Alta/Média/Baixa).
2. Plano de Mitigação Preventivo para cada risco.
3. Lista de todas as dependências externas que precisamos validar antes do kickoff oficial.
```

#### Prompt 16: Milestone Roadmap & Sprint Breakdown Planner
```text
Você é um Agile Coach e Scrum Master sênior.
Divida o projeto [Project Name], com duração total de [Total Weeks, ex: 6 semanas], em um cronograma de Sprints quinzenais estruturados:

Para cada Sprint, defina:
- Nome do Sprint e Objetivo Principal
- Entregáveis Concretos do Período
- Data de Envio para Validação do Cliente
- Janela de Feedback do Cliente (SLA de 48h)
- Critério de Conclusão (Definition of Done)
```

#### Prompt 17: Non-Technical Executive Summary for Stakeholder Sign-Off
```text
Você é um consultor executivo que traduz termos técnicos para linguagem de negócios.
Escreva um Resumo Executivo de 1 página sobre o projeto [Project Name] voltado para a diretoria financeira (CFO) e investidores do cliente, que não entendem jargões técnicos.

Dados Técnicos:
[Descreva aqui o que será feito tecnicamente]

Foco do Documento:
- Explique claramente como essa entrega aumentará as vendas, reduzirá custos operacionais ou protegerá a empresa contra riscos de segurança.
- Destaque o prazo final de entrega e o investimento total em destaque visual.
```

#### Prompt 18: Deliverables Acceptance Criteria & QA Checklist
```text
Atue como um líder de garantia de qualidade (QA Lead).
Crie uma Lista de Critérios de Aceite (Acceptance Criteria) formal para a entrega do serviço [Service/Deliverable].

A lista deve permitir que tanto o cliente quanto nossa equipe marquem caixas de seleção objetivas para validar que a entrega está 100% em conformidade com o contrato antes da assinatura do termo de conclusão.
```

#### Prompt 19: Change Order & Scope Expansion Quote Generator
```text
Você é um gerente de contas de agência.
Um cliente ativo pediu as seguintes funcionalidades adicionais no meio do projeto [Project Name]:
[Descreva aqui os pedidos adicionais do cliente]

Escreva um Aditivo de Escopo (Change Order) formal e amigável contendo:
1. Descrição dos novos itens solicitados.
2. Estimativa de horas e impacto no cronograma geral (+[X] dias de extensão).
3. Valor do investimento adicional para a execução.
4. Campo para assinatura/aprovação digital do cliente para dar início imediato.
```

#### Prompt 20: Polite & Firm Request for Overdue Client Assets/Approvals
```text
Você é um gerente de sucesso do cliente.
O cliente [Client Name] está há mais de [Number of Days, ex: 7 dias] sem nos enviar os acessos/aprovações necessários para continuarmos o projeto [Project Name], o que está ameaçando a data final de entrega.

Escreva um e-mail educado, mas firme e profissional:
- Explique como a falta desses materiais trava a equipe de produção.
- Relembre cordialmente a cláusula contratual que estende automaticamente o prazo final em caso de atraso nas respostas do cliente.
- Forneça um link direto ou checklist simples para que ele envie tudo em menos de 5 minutos hoje mesmo.
```

---

### 🎨 Categoria 3: Content Creation, Copywriting & Design (Prompts 21 a 30)

#### Prompt 21: High-Converting Landing Page Copy (PAS + Benefit Matrix)
```text
Atue como um dos maiores copywriters de conversão do mundo (estilo direct-response).
Escreva a copy completa para a Landing Page do produto/serviço:

- Nome do Produto/Serviço: [Product/Service Name]
- Público Alvo: [Target Audience]
- Preço: [Price]
- Maior Dor do Cliente: [Main Pain Point]
- Solução / Mecanismo Único: [Unique Mechanism]

Estruture a copy nas seguintes seções:
1. Seção Hero: Headline impactante, subheadline clarificadora, 3 bullet points de benefícios e texto do CTA principal.
2. Seção do Problema (Agitação da Dor - Framework PAS): Descreva a frustração diária do cliente.
3. Seção da Solução: Apresente o método e por que ele é diferente das alternativas do mercado.
4. Seção de Entregáveis / O que você recebe: Lista detalhada com valor percebido de cada item.
5. Seção de Quebra de Objeções (FAQ com 5 perguntas críticas respondidas).
6. Seção de Garantia & Fechamento com CTA final.
```

#### Prompt 22: 30-Day B2B Thought-Leadership Content Calendar
```text
Você é um estrategista de conteúdo para LinkedIn e Twitter/X focado em gerar leads B2B para agências.
Crie um calendário editorial de 30 dias de publicações para o nicho [Niche/Service].

Estruture o calendário em uma tabela contendo:
- Dia (1 a 30)
- Pilar de Conteúdo (Autoridade Técnica, Estudo de Caso, Opinião Contraintuitiva, Bastidores da Agência, Chamada para Ação/Venda)
- Gancho / Título Chamativo
- Resumo do Conteúdo e Lição Principal
- Formato Recomendado (Carrossel, Texto Curto, Imagem + História, Vídeo)
```

#### Prompt 23: High-Impact 90-Second Video Script (VSL / Loom Pitch)
```text
Atue como um roteirista especializado em vídeos de vendas curtos (Short VSL / Loom).
Escreva um roteiro falado palavra por palavra para um vídeo de 90 segundos apresentando a solução [Solution Name] para [Target Audience].

Divida o roteiro em blocos de tempo:
- 00:00 - 00:15: Gancho visual e interrupção de padrão (chame a atenção para a maior dor).
- 00:15 - 00:40: Demonstração rápida da tela/método (mostre o resultado visual).
- 00:40 - 01:10: Comparação de custo (fazer do jeito antigo vs. fazer com nosso método).
- 01:10 - 01:30: Chamada para ação clara e direta para agendar uma conversa.
```

#### Prompt 24: Midjourney Photorealistic Brand Image Prompts Generator
```text
Você é um engenheiro de prompts especialista em Midjourney v6 para marcas de luxo e empresas corporativas.
Crie 5 prompts em inglês otimizados para gerar imagens fotorrealistas e sofisticadas para a marca do nicho [Industry/Niche].

Para cada prompt inclua:
- Sujeito e ação principal
- Estilo de iluminação (ex: soft cinematic morning light, Rembrandt lighting, neon rim light)
- Tipo de câmera e lente (ex: shot on Hasselblad H6D-100c, 85mm f/1.4 lens, photorealistic, 8k, award-winning commercial photography)
- Paleta de cores e atmosfera
- Parâmetros técnicos (--ar 16:9 ou --ar 1:1, --v 6.0, --style raw).
```

#### Prompt 25: High-Engagement 7-Slide Carousel Copy for LinkedIn/Instagram
```text
Atue como um criador de conteúdo viral para redes sociais corporativas.
Escreva a copy completa de um Carrossel de 7 slides sobre o tema: [Topic/Theme].

Estrutura dos Slides:
- Slide 1 (Capa): Headline magnética que faça o usuário querer deslizar para o lado.
- Slide 2: O maior erro que 90% das pessoas cometem ao tentar resolver isso.
- Slide 3: O conceito correto explicado de forma simples em 3 linhas.
- Slide 4: Passo prático 1 (com exemplo real).
- Slide 5: Passo prático 2 (com exemplo real).
- Slide 6: Resumo visual dos passos em uma frase marcante.
- Slide 7 (Final): Chamada para salvar o post, compartilhar e seguir o perfil para mais insights.
```

#### Prompt 26: 5-Part Email Nurture Sequence for Agency Inbound Leads
```text
Você é um estrategista de e-mail marketing direto.
Escreva uma sequência de 5 e-mails automáticos de nutrição para enviar a novos leads que baixaram nosso material gratuito ou solicitaram contato no site:

- E-mail 1 (Imediato): Entrega do prometido + Boas-vindas calorosas + Quem somos.
- E-mail 2 (Dia 2): A história de superação de um cliente que estava na mesma situação que o lead.
- E-mail 3 (Dia 4): O maior mito do nosso mercado desmistificado com dados.
- E-mail 4 (Dia 6): Bastidores do nosso método e por que ele entrega resultados consistentes.
- E-mail 5 (Dia 8): Convite exclusivo para uma sessão de diagnóstico de 20 minutos com nossa liderança técnica.
```

#### Prompt 27: High-Converting Button & CTA Microcopy Generator
```text
Atue como um especialista em UX Writing e CRO (Conversion Rate Optimization).
Crie 15 opções de microcopy de alta conversão para botões de chamada para ação (CTAs) para a página do serviço [Service Name].

Divida as 15 opções em:
- 5 CTAs focados em Valor e Ganho (ex: "Quero Aumentar Minhas Vendas Hoje")
- 5 CTAs focados em Baixo Risco / Sem Fricção (ex: "Verificar Disponibilidade Gratuita")
- 5 CTAs focados em Urgência e Exclusividade (ex: "Garantir Vaga no Sprint de [Mês]")
```

#### Prompt 28: Comprehensive Brand Voice & Tone Identity Guide
```text
Você é um estrategista de branding e comunicação corporativa.
Desenvolva o Guia de Voz e Tom de Marca para a empresa [Brand Name], que atua no mercado [Market/Niche].

Defina:
1. Os 3 Adjetivos de Personalidade da Marca (ex: Confiante, Provocativo, Rigoroso).
2. O que a marca É vs. O que a marca NÃO É (tabela comparativa).
3. Vocabulário Recomendado (palavras de poder) vs. Palavras Proibidas (jargões clichês).
4. Exemplos práticos de frases nos canais: Site, E-mail de Suporte e Redes Sociais.
```

#### Prompt 29: Headline & Hero Section A/B Testing Generator
```text
Atue como um especialista em testes de conversão (A/B Testing).
Gere 5 variações completas de Seção Hero (Título Principal, Subtítulo e Texto de Apoio) para a página [Service URL / Concept].

Variações Requeridas:
- Variação A: Focada em Benefício Direto e Ganho Financeiro.
- Variação B: Focada em Eliminação de Dor e Frustração.
- Variação C: Focada em Prova Social e Autoridade ("Como a empresa X alcançou Y").
- Variação D: Contraintuitiva / Quebra de Padrão ("Pare de fazer X se quiser alcançar Y").
- Variação E: Ultra-Específica e Quantitativa com números e prazos.
```

#### Prompt 30: High-Trust Client Case Study & Success Story Writer
```text
Você é um redator de estudos de caso para agências B2B de alto padrão.
Escreva um Estudo de Caso aprofundado e convincente baseado nas informações do projeto concluído abaixo:

- Nome do Cliente: [Client Name]
- Desafio Inicial: [Initial Challenge]
- Solução Implementada por Nós: [Our Solution]
- Resultados Quantitativos Alcançados: [Metrics, ex: +145% de conversão, $80k em novas vendas]
- Depoimento do Cliente: [Customer Quote]

Estruture o texto no clássico framework:
1. O Contexto do Cliente
2. O Ponto de Ruptura (Por que eles precisavam de ajuda imediata)
3. A Abordagem Estratégica da Nossa Agência
4. Os Resultados em Números
5. A Lição Principal para Outras Empresas do Setor
```

---

### 🛠️ Categoria 4: Development, Operations & QA (Prompts 31 a 40)

#### Prompt 31: Comprehensive Web Project Pre-Launch QA Checklist
```text
Atue como um engenheiro de QA (Garantia de Qualidade) sênior.
Crie um checklist exaustivo de testes pré-lançamento para uma aplicação web / site moderno no nicho [Project Type, ex: E-commerce / Landing Page / SaaS].

Divida o checklist em:
1. Testes de Responsividade & Cross-Browser (Mobile iOS/Android, Safari, Chrome, Edge).
2. Validação de Formulários & Rastreamento (Envio de dados, Webhooks para CRM, Google Tag Manager, Pixel).
3. Performance e Velocidade (Otimização de imagens WebP, lazy-loading, caching).
4. Links e Navegação (Páginas 404 personalizadas, links quebrados, favicon).
5. Segurança Básica (Certificado SSL ativo, headers de segurança, proteção de formulários contra spam).
```

#### Prompt 32: Plain-English User Documentation & Client How-To Guide
```text
Você é um redator técnico que se comunica com clareza cristalina para leigos.
Escreva um Guia Rápido de Uso para o cliente [Client Name] aprender a gerenciar e atualizar a solução que entregamos: [Deliverable, ex: Painel CMS de Blog no Webflow ou WordPress].

O guia deve ter:
- Passo a passo numerado com linguagem simples e livre de jargões de programação.
- Dicas de "Faça Isso" e avisos de "Cuidado para Não Fazer Isso".
- Respostas para as 3 dúvidas mais prováveis que o cliente terá no dia a dia.
```

#### Prompt 33: Technical & On-Page SEO Audit / Metadata Generator
```text
Atue como um especialista técnico em SEO (Search Engine Optimization).
Com base nas seguintes informações de página:
- URL / Título da Página: [Page Title]
- Objetivo da Página: [Page Goal]
- Palavra-Chave Principal: [Target Keyword]
- Palavras-Chave Secundárias: [Secondary Keywords]

Gere:
1. Meta Title otimizado (máximo 60 caracteres) com alto CTR.
2. Meta Description persuasiva (máximo 155 caracteres) com gatilho de clique.
3. Estrutura de Headings recomendada (H1, H2s e H3s com hierarquia correta).
4. Código JSON-LD de dados estruturados (Schema.org) pronto para injetar no cabeçalho da página.
```

#### Prompt 34: Web Performance & Core Web Vitals Optimization Checklist
```text
Você é um engenheiro de performance web especializado em Core Web Vitals do Google.
Analise os gargalos típicos de sites desenvolvidos em [Technology, ex: React/Next.js/WordPress/Webflow] e elabore um plano de ação em 5 etapas para alcançar nota 95+ no Google PageSpeed Insights:

Detalhamento Requerido:
- LCP (Largest Contentful Paint): Como reduzir para menos de 2.5s.
- INP (Interaction to Next Paint): Otimização de scripts e execução JS.
- CLS (Cumulative Layout Shift): Técnicas para zerar deslocamentos de layout.
```

#### Prompt 35: Web Accessibility (WCAG 2.1 AA) Compliance Audit Plan
```text
Atue como um auditor de acessibilidade digital certificado.
Crie um roteiro prático para validar se o projeto digital [Project Name] atende aos padrões de conformidade WCAG 2.1 nível AA.

Cubra os seguintes itens com critérios objetivos:
- Contraste de cores entre texto e fundo (mínimo 4.5:1).
- Navegação completa apenas via teclado (focus states visíveis).
- Textos alternativos (alt text) descritivos para todas as imagens informativas.
- Rótulos acessíveis para campos de formulário e botões de ícone.
```

#### Prompt 36: Client-Facing Version Release Notes & Changelog
```text
Você é um gerente de produto (Product Manager).
Escreva uma nota de atualização de versão (Changelog / Release Notes) elegante e amigável para enviar aos clientes da nossa plataforma / projeto [Project Name].

Atualizações Realizadas:
[Liste aqui os ajustes técnicos, novos recursos e correções de bugs da semana]

Tom de Voz:
Comemorativo, transparente e focado em como cada melhoria técnica torna a vida do usuário mais fácil e rápida.
```

#### Prompt 37: Relational Database Schema & Data Modeling Architect
```text
Atue como um arquiteto de banco de dados sênior.
Projete o modelo de dados relacional (schema) para uma aplicação de [Application Idea, ex: Sistema de agendamentos e faturamento para consultórios].

Entregue:
1. Lista de Entidades / Tabelas com suas respectivas chaves primárias e estrangeiras.
2. Campos essenciais e tipos de dados de cada tabela.
3. Diagrama textual de relacionamentos (1:1, 1:N, N:N).
4. Índices recomendados para otimização de consultas frequentes.
```

#### Prompt 38: User Testing Scenario & Usability Testing Protocol
```text
Você é um pesquisador sênior de UX (UX Researcher).
Crie um protocolo completo para conduzir 5 testes de usabilidade com usuários reais sobre o novo protótipo do projeto [Project Name].

Inclua:
- Roteiro de boas-vindas e consentimento do participante.
- 3 tarefas práticas baseadas em cenários da vida real (sem induzir o clique).
- Perguntas qualitativas pós-tarefa para medir a facilidade de uso percebida.
- Formulário de anotações para o observador registrar fricções e erros de navegação.
```

#### Prompt 39: Standardized Bug Report & Issue Triage Framework
```text
Atue como um líder de suporte técnico e engenharia.
Crie um modelo padronizado de Relato de Bugs (Bug Report) para clientes e membros da equipe preencherem quando encontrarem uma falha no sistema.

O modelo deve exigir obrigatoriamente:
- Título descritivo do problema
- Passos exatos para reproduzir a falha (1, 2, 3...)
- Comportamento Esperado vs. Comportamento Real Observado
- Ambiente (Navegador, Dispositivo, Sistema Operacional)
- Nível de Severidade (P1 Crítico - Sistema Parado até P4 Cosmético).
```

#### Prompt 40: Security Hardening & Automated Backup Checklist
```text
Você é um especialista em segurança de servidores e aplicações web (DevSecOps).
Crie um checklist de segurança e plano de continuidade de negócios para um projeto de cliente hospedado em [Hosting/Server, ex: AWS / Vercel / DigitalOcean / Hostinger]:

O plano deve cobrir:
1. Políticas de senhas fortes e autenticação de dois fatores (2FA) para todos os painéis.
2. Rotina de backups automatizados diários (retenção local e externa redundante).
3. Plano de Recuperação de Desastres (RTO e RPO definidos em caso de queda).
4. Procedimento para restauração de emergência em menos de 60 minutos.
```

---

### 📈 Categoria 5: Retention, Upsell & Monthly Reports (Prompts 41 a 50)

#### Prompt 41: Executive Monthly Performance & ROI Retainer Report
```text
Atue como um diretor de contas de agência de alta performance.
Escreva a estrutura de um Relatório Mensal Executivo de Resultados para um cliente que nos paga um retainer mensal de [Retainer Value, ex: $3.000/mês].

Dados do Mês:
- Cliente: [Client Name]
- Entregas Executadas: [Deliverables Completed]
- Métricas Chave do Mês: [Metrics, ex: Tráfego, Leads, Vendas, Uptime]
- Principais Desafios Superados: [Obstacles Overcome]

Estrutura do Relatório:
1. Resumo Executivo em 3 Frases (focado no retorno sobre o investimento).
2. Tabela de Entregáveis Concluídos vs. Metas Acordadas.
3. Gráfico / Destaque de Impacto nos Negócios do Cliente.
4. Próximas Prioridades Estratégicas para o Mês Seguinte.
```

#### Prompt 42: Strategic Upsell Proposal for Ongoing Service Upgrades
```text
Você é um consultor de expansão de contas (Customer Success & Upsell).
Temos um cliente satisfeito que atualmente contrata nosso plano básico de [Current Service].
Escreva uma proposta consultiva para apresentar a expansão da conta para o plano avançado [Advanced Service / Add-on].

A proposta deve destacar:
- Os ótimos resultados conquistados na fase inicial.
- As novas oportunidades de receita que o cliente está deixando na mesa sem a expansão.
- Condição de upgrade suave com transição sem interrupção de serviços.
```

#### Prompt 43: Quarterly Business Review (QBR) Agenda & Deck Script
```text
Atue como um vice-presidente de Customer Success.
Crie a pauta e o roteiro falado de slides para uma Reunião Trimestral de Alinhamento de Resultados (QBR - Quarterly Business Review) de 45 minutos com a diretoria do cliente [Client Name].

Apresente em 6 slides estratégicos:
1. Visão Geral do Trimestre: Onde Estávamos vs. Onde Chegamos.
2. Principais Conquistas e Marcos Batidos.
3. Aprendizados e Ajustes de Rota Necessários.
4. Análise de ROI Financeiro Gerado pela Parceria.
5. Visão de Futuro e Metas para os Próximos 90 Dias.
6. Alinhamento de Recursos e Renovação de Compromisso.
```

#### Prompt 44: 3-Question NPS Survey & High-Value Feedback Collector
```text
Você é um especialista em experiência do cliente (CX).
Crie uma mensagem amigável e descontraída para WhatsApp ou e-mail coletando feedback de satisfação de um cliente após 30 dias de projeto concluído.

A mensagem deve conter apenas 3 perguntas simples:
1. De 0 a 10, qual a probabilidade de você recomendar nosso trabalho para um amigo ou colega empresário?
2. Qual foi o maior benefício tangível que nossa parceria trouxe para a sua empresa até agora?
3. Se pudéssemos melhorar um único detalhe no nosso processo ou comunicação, o que seria?
```

#### Prompt 45: Frictionless Referral Request Script for Happy Clients
```text
Você é um diretor comercial sênior.
Um cliente acabou de enviar uma mensagem calorosa elogiando o resultado do nosso trabalho.
Escreva um script de resposta imediata para aproveitar esse momento de máxima satisfação e pedir indicações de outros clientes qualificados:

Regras do Script:
- Agradeça sinceramente pelo elogio.
- Explique que nosso modelo de negócio cresce quase 100% por indicação de parceiros de alto nível como ele.
- Faça um pedido específico e sem fricção: "Você conhece 1 ou 2 empresários do seu círculo que também estejam enfrentando o desafio de [Desafio] e se beneficiariam de uma ajuda nossa?".
- Ofereça uma bonificação ou crédito de desconto na próxima fatura dele como agradecimento pela indicação fechada.
```

#### Prompt 46: Annual Rate Increase Announcement Letter (Inflation/Value)
```text
Atue como o fundador e CEO de uma agência de consultoria premium.
Escreva uma carta de comunicação de reajuste anual de honorários para clientes de retainer recorrente de longa data.

Diretrizes da Mensagem:
- Aumento planejado: [Percentage, ex: 10% a 15%].
- Data de início: A partir de 60 dias da data de envio (aviso prévio generoso).
- Justificativa elegante: Investimento contínuo em novas ferramentas, expansão da equipe sênior e aumento comprovado no valor gerado para os clientes no último ano.
- Tom de respeito, parceria de longo prazo e segurança profissional.
```

#### Prompt 47: Ongoing Maintenance & Security SLA Proposal
```text
Você é um diretor de operações e infraestrutura de agência.
Crie uma proposta comercial concisa para um Plano de Manutenção Preventiva, Suporte e SLA Contínuo para ser oferecido no encerramento de um projeto de desenvolvimento/site.

O plano deve cobrir:
- Atualizações de segurança e backups diários em nuvem.
- Tempo de resposta garantido (SLA de até 4 horas úteis para emergências).
- Pacote de horas mensais inclusas para pequenos ajustes e melhorias contínuas.
- Valor mensal sugerido e cláusula de cancelamento simples com 30 dias de aviso prévio.
```

#### Prompt 48: Transparent Work & Impact Summary for Retainer Hours
```text
Você é um gerente de operações focado em transparência e confiança.
Escreva o modelo de resumo quinzenal de horas e impacto entregue para ser enviado ao cliente de retainer mensal [Client Name].

O modelo deve mostrar claramente:
- Total de Horas Contratadas vs. Horas Utilizadas no Ciclo.
- Tabela de Tarefas Entregues com o Impacto Real de Negócio gerado por cada uma.
- Horas restantes disponíveis e sugestão proativa da equipe sobre onde alocá-las no próximo ciclo para gerar mais resultado.
```

#### Prompt 49: Celebratory Project Completion & Offboarding Letter
```text
Atue como o líder da agência celebrando o sucesso da parceria.
Escreva uma carta comemorativa de encerramento oficial de projeto para o cliente [Client Name].

O texto deve:
- Celebrar o marco alcançado e agradecer a todos os membros envolvidos da equipe do cliente.
- Recapitular a grande transformação do ponto inicial até a entrega final.
- Disponibilizar os canais de suporte caso surja qualquer dúvida pontual nas próximas semanas.
- Deixar a porta aberta para projetos futuros com votos de sucesso contínuo para o negócio.
```

#### Prompt 50: Annual Retainer Renewal & Strategy Expansion Agreement
```text
Você é um estrategista sênior de negócios e retenção de contas.
Escreva um documento executivo de Renovação Anual de Contrato para o cliente [Client Name], cujo contrato de 12 meses está chegando ao fim.

O documento deve estruturar:
1. Retrospectiva dos 12 Meses: As vitórias históricas e números conquistados juntos.
2. A Nova Fase de Maturidade do Negócio do Cliente e os Desafios do Próximo Ano.
3. Plano Estratégico Proposto para os Próximos 12 Meses (visão de expansão).
4. Termos Financeiros de Renovação e Bônus Exclusivo de Continuidade.
5. Assinatura de Renovação Simples e Direta.
```
