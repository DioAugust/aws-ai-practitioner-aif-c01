# AWS Certified AI Practitioner (AIF-C01) — como eu me preparei

Este repositório é o registro do caminho que eu fiz para a **AWS Certified AI Practitioner**, com o material que produzi no meio do caminho já pronto para você usar.

### 👉 [Abrir o simulado agora](https://dioaugust.github.io/aws-ai-practitioner-aif-c01/)

100 questões inéditas em PT-BR, direto no navegador. Não precisa baixar nem instalar nada.

> **Até 30/09/2026:** o cupom `AIF2CLOUD` derruba o exame de USD 100 para USD 50 e, se você passar, a **Cloud Practitioner vem de graça**. [Detalhes e regras ↓](#promo)

---

Tem três coisas aqui:

| Arquivo | O que é |
|---|---|
| [`index.html`](index.html) | Simulado interativo com **100 questões inéditas em PT-BR**, na proporção oficial dos domínios. Roda no navegador, sem instalar nada. |
| [`edital.md`](edital.md) | O exam guide oficial destrinchado: formato, pesos, task statements e a lista dos serviços que mais aparecem. |
| Este README | A trilha de estudo, incluindo o que fazer se você só estuda em português. |

---

## A prova em 30 segundos

| Item | Valor |
|---|---|
| Questões | 65 (50 valem nota, 15 são de calibração) |
| Duração | 90 minutos |
| Nota de corte | 700 de 1000 (escala 100–1000) |
| Modelo de nota | compensatório — passa pelo total, não domínio a domínio |
| Custo | USD 100 — **USD 50 com o cupom abaixo** |
| Nível | Foundational |
| Aplicação | Pearson VUE ou online proctored |

Pesos dos domínios: **D1** Fundamentals of AI and ML 20% · **D2** Fundamentals of Generative AI 24% · **D3** Applications of Foundation Models 28% · **D4** Responsible AI 14% · **D5** Security, Compliance and Governance 14%.

O perfil da prova é de quem **usa** IA na AWS, não de quem constrói. Não cai código, feature engineering, hyperparameter tuning nem matemática. Cai saber qual serviço resolve qual problema.

---

<a id="promo"></a>

## 💸 Antes de qualquer coisa: 50% de desconto e uma segunda certificação de graça

A AWS está com a promoção **AI & Cloud Foundational Certifications**, e ela muda a conta inteira. Vale conferir antes de comprar o exame.

**Página oficial da promoção → https://www.pearsonvue.com/us/en/aws/aif2cloud.html**

Como funciona:

1. **Aplique o código `AIF2CLOUD`** no pagamento, na hora de registrar o AIF-C01. O exame cai de **USD 100 para USD 50**.
2. **Passe no AIF-C01 até 30 de setembro de 2026.** Registro e realização da prova precisam acontecer dentro da janela, que começou em 26 de maio de 2026.
3. **Você recebe automaticamente um voucher grátis** para a **AWS Certified Cloud Practitioner (CLF-C02)** — sem precisar de outro código.
4. **Faça a CLF-C02 até 30 de novembro de 2026** para usar o voucher.

Ou seja: **duas certificações AWS por USD 50**, em vez de USD 200 pelas duas no preço cheio.

Restrições que importam: uma por pessoa/conta, não acumula com outras promoções, exige 18 anos ou mais e há países excluídos. As regras completas estão na página da Pearson VUE.

> ⚠️ **Promoção com prazo.** Se você está lendo isto depois de **30 de setembro de 2026** (ou de 30 de novembro de 2026 para o voucher da CLF-C02), a janela fechou. Confira a página oficial acima e a [central de certificações da AWS](https://aws.amazon.com/pt/certification/) — a AWS costuma rodar promoções novas, e quem já é certificado normalmente ganha um voucher de 50% na conta de certificação para a prova seguinte.

### Onde agendar

O agendamento sai pela sua **AWS Certification Account**, acessível pela central oficial:

**https://aws.amazon.com/pt/certification/**

De lá você escolhe entre centro de testes Pearson VUE e prova online com proctoring, e aplica o cupom no pagamento. Um detalhe da prova online: ela exige uma mesa limpa, documento com foto e um ambiente sem interrupções — se sua casa não colabora, o centro de testes evita dor de cabeça.

---

## A trilha que eu segui

### 1. Curso base — ExamPro (inglês, tem plano grátis)

**https://app.exampro.co/student/journey/aif-c01**

Foi o material principal da minha preparação. O plano gratuito dá acesso ao conteúdo do curso e a **1 simulado**. Foi mais do que suficiente para montar a base.

O detalhe importante: **é tudo em inglês.** Se inglês técnico não te trava, comece por aqui.

### 2. Ler o edital com atenção

O [`edital.md`](edital.md) deste repositório é o exam guide oficial mastigado. Vale ler antes de estudar e reler na véspera. Dois motivos:

- **Peso importa.** D3 (Applications of Foundation Models) sozinho vale 28% da prova. Uma hora estudando D3 rende o dobro de uma hora estudando D4.
- **Saber o que NÃO cai economiza semanas.** A lista de fora de escopo está no edital.

### 3. Simulado — treinar em formato de prova

Depois de fechar o conteúdo, o que mais rendeu foi responder questão. Como o plano grátis do ExamPro só libera um simulado, montei o meu: o [`index.html`](index.html) deste repo, com 100 questões escritas a partir do exam guide oficial.

---

## Se você só estuda em português

O ExamPro é ótimo, mas é 100% em inglês. Se isso for barreira, a alternativa que eu recomendo é este curso:

**https://www.udemy.com/course/certificacao-amazon-aws-ai-practitioner/**

Curso completo em português, cobrindo o edital do AIF-C01. Dá para fazer a trilha inteira em PT-BR: curso na Udemy → `edital.md` daqui → simulado daqui.

> Uma ressalva honesta: **a prova em si você pode fazer em português**, mas boa parte da documentação da AWS e dos nomes de serviço vive em inglês. Vale se acostumar com os termos técnicos originais (`foundation model`, `fine-tuning`, `guardrails`, `inference`) mesmo estudando em PT-BR. Por isso o simulado deste repo mantém os termos técnicos em inglês dentro de enunciados em português — é assim que a prova traduzida se comporta.

---

## O simulado

A forma mais rápida é abrir direto: **https://dioaugust.github.io/aws-ai-practitioner-aif-c01/** — funciona no computador e no celular.

Se preferir ter o arquivo, baixe pelo botão **Code → Download ZIP** e abra o `index.html`. É um arquivo único, sem build, sem servidor, sem dependência: depois de baixado **funciona offline**, o que ajuda para estudar no transporte ou em qualquer lugar sem internet.

### Modos

| Modo | Para quê |
|---|---|
| **Simulado completo — 65q / 90 min** | Formato oficial, proporção 20/24/28/14/14 e cronômetro. É o mais parecido com o dia da prova. |
| **Prova rápida — 30q / 45 min** | Diagnóstico do dia, mesma proporção de domínios. |
| **Banco inteiro — 100q** | Maratona de revisão, sem cronômetro. |
| **Treino por domínio** | Ataca um domínio isolado depois de identificar o ponto fraco. |
| **Modo estudo** | Mostra o gabarito e a explicação assim que você responde. Bom no começo, ruim perto da prova. |

Ainda dá para embaralhar questões e alternativas, marcar questões para revisar e navegar pelo mapa de questões. Teclado: `1`–`5` marcam alternativa, `←` e `→` navegam.

### O painel de resultado é a parte que importa

No fim ele mostra acerto por domínio e por task statement — mas ordenado por **perda ponderada**, que é o seu erro multiplicado pelo peso do domínio na prova.

Essa é a diferença entre "errei 40% do D4" e "o D4 está me custando 5,6 pontos da nota final". Como o D3 pesa o dobro do D4, errar 30% do D3 dói mais do que errar 50% do D4. **Estude de cima para baixo nessa lista** e cada hora rende o máximo de nota possível.

O resultado também sai em `.json` para você comparar tentativas ao longo do tempo.

---

## O que eu faria diferente

- **Começar pelo D3.** É o maior peso e o que mais tem detalhe decoreba (critérios de escolha de modelo, RAG, vector stores, trade-offs de customização).
- **Decorar a tabela de serviços.** Boa parte da prova é "qual serviço faz X". A lista está no fim do [`edital.md`](edital.md).
- **Não subestimar D4 e D5.** São 28% da prova somados, com conteúdo curto e previsível. É a nota mais barata de comprar.
- **Sair do modo estudo cedo.** Ele vicia: você acerta lendo o gabarito, não raciocinando. Na última semana, só simulado cronometrado.
- **Emendar a Cloud Practitioner.** Se você pegar a promoção, o voucher da CLF-C02 já está pago. O conteúdo de D5 (segurança, IAM, compliance) tem sobreposição grande com a Cloud Practitioner — fazer as duas em sequência aproveita o estudo ainda fresco.

---

## Aviso

Este material é **não oficial**. As questões do simulado foram escritas do zero a partir do exam guide público do AIF-C01 e **não reproduzem questões reais do exame**. AWS e AWS Certified AI Practitioner são marcas da Amazon Web Services, Inc.

## Licença

[MIT](LICENSE) — use, adapte e compartilhe à vontade. Se ajudar alguém, me conta.

---

**@dioaugusto.dev**
