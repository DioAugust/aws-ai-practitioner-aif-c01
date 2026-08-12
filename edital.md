# AWS Certified AI Practitioner (AIF-C01) — edital e plano de estudo

Fonte: exam guide oficial da AWS (docs.aws.amazon.com/aws-certification), consultado em 12/08/2026.

## Formato da prova

| Item | Valor |
|---|---|
| Questões | 65 (50 pontuadas + 15 não pontuadas) |
| Duração | 90 minutos |
| Nota de corte | 700 de 1000 (escala 100–1000) |
| Modelo de nota | compensatório — passa pelo total, não por domínio |
| Tipos | múltipla escolha, múltipla resposta, ordenação, correspondência |
| Custo | USD 100 |
| Nível | Foundational |
| Aplicação | Pearson VUE ou online proctored |

Perfil-alvo: até 6 meses de exposição a AI/ML na AWS; **usa**, não constrói, soluções de AI/ML.

**Fora de escopo:** desenvolver/codar modelos, data e feature engineering, hyperparameter tuning, construir pipelines/infra de AI/ML, análise matemática/estatística, implementar segurança/compliance, criar frameworks de governança.

## Domínios e pesos

| Domínio | Peso |
|---|---|
| D1 — Fundamentals of AI and ML | 20% |
| D2 — Fundamentals of Generative AI | 24% |
| D3 — Applications of Foundation Models | 28% |
| D4 — Guidelines for Responsible AI | 14% |
| D5 — Security, Compliance and Governance for AI Solutions | 14% |

## Task statements

**D1 — Fundamentals of AI and ML (20%)**

- **1.1 Conceitos e terminologias** — AI, ML, deep learning, neural networks, computer vision, NLP, model, algorithm, training/inferencing, bias, fairness, fit, LLM, GenAI, agentic AI; diferenças entre eles; tipos de inferencing (batch, real-time, asynchronous, serverless); tipos de dado (labeled/unlabeled, tabular, time-series, image, text, structured/unstructured); supervised, unsupervised e reinforcement learning.
- **1.2 Casos de uso práticos** — quando AI/ML agrega valor e quando não é apropriado; regression, classification, clustering; aplicações reais (computer vision, NLP, speech recognition, recommendation, fraud detection, forecasting, knowledge bases, agentic AI); serviços gerenciados (SageMaker AI, Transcribe, Translate, Comprehend, Lex, Polly); ML tradicional vs. foundation models.
- **1.3 Ciclo de vida AI/ML** — componentes do pipeline; fontes de FMs; modelo em produção (managed API vs. self-hosted); serviços por estágio (Bedrock, Amazon Q, Amazon Quick, Kiro, SageMaker AI); MLOps; métricas de modelo (accuracy, precision, recall, F1) e de negócio (custo por usuário, ROI).

**D2 — Fundamentals of Generative AI (24%)**

- **2.1 Conceitos básicos** — tokens, chunking, embeddings, vectors, prompt engineering, transformer LLMs, FMs, multi-modal, diffusion models; casos de uso; ciclo de vida do FM; pricing por token; **context engineering**; **agentic AI** (multi-agent patterns, **MCP**, memory management, tool usage, workflow orchestration).
- **2.2 Capacidades e limitações** — vantagens; hallucinations, interpretabilidade, imprecisão, não-determinismo; critérios de escolha de modelo; valor de negócio e métricas.
- **2.3 Infraestrutura AWS** — Bedrock, SageMaker AI, JumpStart, Amazon Quick, Kiro, **Strands Agents**, **Bedrock AgentCore**; vantagens dos serviços gerenciados; trade-offs de custo (token pricing, provisioned throughput, custom models).

**D3 — Applications of Foundation Models (28%) — maior peso da prova**

- **3.1 Design de aplicações com FMs** — critérios de seleção (custo, modality, latência, multi-lingual, tamanho, customização, input/output length, **prompt caching**); inference parameters (temperature, comprimento); **RAG** e Bedrock Knowledge Bases; vector stores (OpenSearch, Aurora, Neptune, RDS for PostgreSQL); trade-offs de customização (pre-training, fine-tuning, in-context learning, RAG, **model distillation**); AI agents.
- **3.2 Prompt engineering** — context, instruction, negative prompts; chain-of-thought, zero/single/few-shot, templates; boas práticas e guardrails; riscos (exposure, poisoning, hijacking, jailbreaking); **Bedrock Prompt Management**.
- **3.3 Training e fine-tuning** — pre-training, fine-tuning, continuous pre-training, distillation; instruction tuning, domain adaptation, transfer learning; preparação de dados, **RLHF**.
- **3.4 Avaliação de FMs** — human-in-the-loop, benchmark datasets, **Bedrock Model Evaluation**; **ROUGE, BLEU, BERTScore, LLM-as-a-judge**; avaliação de aplicações (RAG, agents, workflows); métricas de negócio (task completion rate, user satisfaction, cost per interaction).

**D4 — Guidelines for Responsible AI (14%)**

- **4.1 IA responsável** — bias, fairness, inclusivity, robustness, safety, veracity; **Bedrock Guardrails**; sustentabilidade; riscos legais de GenAI; características de datasets; bias e variance (overfitting/underfitting); **SageMaker Clarify**, **Model Monitor**, **Amazon A2I**.
- **4.2 Transparência e explicabilidade** — modelos transparentes vs. black box; **SageMaker Model Cards**, Clarify, Bedrock Model Evaluation, open source e licenciamento; trade-off interpretabilidade × performance; human-centered design.

**D5 — Security, Compliance and Governance (14%)**

- **5.1 Segurança** — IAM, encryption/KMS, **Macie**, **PrivateLink**, shared responsibility model, **AgentCore Identity**, **Bedrock Guardrails**; source citation, data lineage, cataloging, Model Cards; secure data engineering; **prompt injection**, data leakage prevention, output filtering, audit trail, toxicity; detecção de hallucination e grounding (RAG grounding, output validation, confidence scoring).
- **5.2 Governança e compliance** — **AWS Config, Inspector, Audit Manager, Artifact, CloudTrail, Trusted Advisor**; data lifecycle, logging, residency, retenção; **Generative AI Security Scoping Matrix**, cadência de revisão, treinamento de equipe.

## Serviços mais cobrados

Bedrock (+ Knowledge Bases, Guardrails, Agents, AgentCore, Model Evaluation, Prompt Management), SageMaker AI (+ JumpStart, Clarify, Model Monitor, Model Cards), Amazon Q, Amazon Nova, Kiro, Strands Agents, A2I, Comprehend, Kendra, Lex, Personalize, Polly, Rekognition, Textract, Transcribe, Translate, OpenSearch, Aurora, Neptune, RDS, IAM, KMS, Macie, Secrets Manager, Artifact, Audit Manager, Inspector, CloudTrail, Config, Trusted Advisor, CloudWatch.

## Material de apoio neste repositório

- [`index.html`](index.html) — simulado interativo com 100 questões inéditas em PT-BR (termos técnicos em inglês), distribuídas na proporção oficial 20/24/28/14/14. Modos: prova completa (65q, 90 min), prova rápida (30q), banco inteiro, treino por domínio e modo estudo com gabarito imediato. O painel final mostra acerto por domínio e por task statement, ordenado por **perda ponderada** (erro × peso do domínio), que é a fila de prioridade de estudo.