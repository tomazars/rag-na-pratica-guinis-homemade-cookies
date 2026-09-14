
# 🍪 RAG na Prática: Guini's Homemade Cookies

**Fundamentos de RAG e construção de assistentes baseados em conhecimento, utilizando o Guini's Homemade Cookies como caso prático.**

## 📌 Introdução

Este repositório explora os fundamentos de **Retrieval-Augmented Generation (RAG)** e sua aplicação prática na construção de soluções baseadas em conhecimento.

O projeto aborda conceitos relacionados a **Inteligência Artificial, busca semântica, embeddings, bancos de dados vetoriais, Large Language Models (LLMs) e Cloud Computing**, utilizando o **OCI — Oracle Cloud Infrastructure** como parte do contexto tecnológico.

Para tornar o aprendizado mais concreto, foi estruturado um **Caderno Temático no Google NotebookLM**, utilizando o **Guini's Homemade Cookies** como caso prático para explorar a aplicação de RAG em um cenário de atendimento ao cliente e organização de informações.

A partir desse cenário, o projeto conecta **fundamentação teórica, experimentação prática e análise crítica**, demonstrando como uma arquitetura baseada em RAG pode utilizar uma base de conhecimento para recuperar informações relevantes e fornecer respostas contextualizadas.

Este trabalho também faz parte da minha jornada de desenvolvimento profissional em tecnologia, com foco na integração entre **Inteligência Artificial, dados, processos e soluções em Cloud Computing**.

---

## 🎯 1. Contexto e Objetivos

### Contexto

Em pequenos e médios negócios do segmento alimentício, a organização das informações, a padronização de receitas, o controle de ingredientes e a agilidade no atendimento são fatores importantes para a operação.

O **Guini's Homemade Cookies** é utilizado neste projeto como um **caso prático fictício**, permitindo explorar como um assistente baseado em conhecimento pode recuperar informações relevantes a partir de documentos e utilizá-las na geração de respostas contextualizadas.

### Objetivos de Estudo

* **Compreender a arquitetura RAG:** entender como a recuperação de informações a partir de fontes de conhecimento pode ser combinada à geração de texto por modelos de linguagem (LLMs).

* **Explorar o NotebookLM:** utilizar uma ferramenta de organização, análise e consulta de fontes para estruturar um Caderno Temático sobre RAG.

* **Aplicar os conceitos na prática:** utilizar o Guini's Homemade Cookies como cenário para relacionar os conceitos estudados a uma aplicação baseada em conhecimento.

* **Experimentar engenharia de prompts:** criar, testar e refinar prompts para obter respostas mais claras, contextualizadas e adequadas ao objetivo do projeto.

* **Documentar o aprendizado:** registrar conceitos, experimentos, testes, dificuldades e refinamentos realizados durante o desenvolvimento do Caderno Temático.

---

## 📂 2. Curadoria de Fontes — NotebookLM

O Caderno Temático foi estruturado a partir de diferentes fontes de conhecimento relacionadas aos conceitos estudados.

Entre os principais conteúdos utilizados estão:

1. **Documentação sobre OCI Generative AI**
   Conteúdos relacionados a serviços de Inteligência Artificial Generativa e possibilidades de aplicação em ambientes de Cloud Computing.

2. **Materiais técnicos sobre RAG**
   Conteúdos relacionados a recuperação de informações, embeddings, busca semântica e utilização de bases de conhecimento para fornecer contexto aos modelos de linguagem.

3. **Materiais do caso prático Guini's Homemade Cookies**
   Documentos fictícios utilizados para representar informações operacionais, como produtos, ingredientes, atendimento e regras de negócio.

A curadoria das fontes permite relacionar os conceitos teóricos com um cenário prático, facilitando a compreensão do funcionamento de uma solução baseada em conhecimento.

---

## 🔬 3. Engenharia de Prompts e "Cicatrizes" — Troubleshooting

Durante a construção do Caderno Temático, foram realizados testes com diferentes abordagens de prompt, observando a qualidade e a adequação das respostas geradas.

### Teste 1 — Simplificação dos conceitos de RAG

**Objetivo:** obter uma explicação simples e diretamente relacionada ao cenário de atendimento do Guini's Homemade Cookies.

**Prompt utilizado:**

> "Explain simply/directly how RAG works in a customer service assistant for a microbusiness of artisanal cookies."

### Dificuldade encontrada

A primeira resposta apresentou uma abordagem mais técnica, utilizando conceitos relacionados à representação vetorial e ao funcionamento matemático dos embeddings.

Embora tecnicamente válida, essa abordagem não estava totalmente alinhada ao objetivo didático do Caderno Temático.

### Refinamento

O prompt foi ajustado para utilizar uma linguagem mais simples e uma analogia próxima ao contexto do negócio.

Uma das abordagens utilizadas foi comparar o funcionamento do RAG ao trabalho de um **"bibliotecário muito rápido"**, capaz de localizar a informação correta em uma base de conhecimento antes que o atendente responda ao cliente.

### Resultado

O refinamento proporcionou uma explicação mais clara e didática, facilitando a compreensão do conceito de RAG e sua relação com um cenário de atendimento baseado em conhecimento.

---

## 📖 4. Miniguia de Estudo — Entrega Final

Como resultado do projeto, foi estruturado um **miniguia de estudo sobre RAG**, reunindo os principais conceitos trabalhados durante a construção do Caderno Temático.

### Principais conceitos

* **RAG (Retrieval-Augmented Generation):** abordagem que combina a recuperação de informações relevantes a partir de uma base de conhecimento com a geração de respostas por um modelo de linguagem.

* **Embeddings:** representações numéricas utilizadas para capturar relações semânticas entre conteúdos e possibilitar operações de busca por similaridade.

* **Busca semântica:** mecanismo que permite localizar informações considerando o significado e o contexto dos conteúdos, e não apenas a correspondência exata de palavras.

* **LLMs:** modelos de linguagem utilizados para interpretar informações e gerar respostas em linguagem natural.

* **OCI:** Oracle Cloud Infrastructure, utilizada como contexto para explorar serviços de Cloud Computing relacionados à Inteligência Artificial.

### Aplicações práticas

Os conceitos estudados podem ser aplicados em diferentes cenários, como:

* Atendimento e suporte;
* Consulta rápida a documentos e manuais;
* Organização e recuperação de conhecimento;
* Apoio a processos operacionais;
* Assistentes baseados em conhecimento;
* Automação de consultas internas.

### Glossário

| Conceito               | Definição                                                                                                                                      |
| ---------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| **RAG**                | Retrieval-Augmented Generation — técnica que combina recuperação de informações relevantes com geração de texto contextualizado.               |
| **Embeddings**         | Representações numéricas que capturam relações semânticas entre textos, permitindo buscas por similaridade.                                    |
| **Busca Semântica**    | Mecanismo que localiza informações considerando seu significado e contexto, e não apenas palavras exatas.                                      |
| **LLM**                | Large Language Model — modelo de linguagem treinado em grandes volumes de dados para interpretar e gerar texto em linguagem natural.           |
| **Vector Store**       | Banco ou estrutura especializada no armazenamento de embeddings e na realização de buscas por similaridade.                                    |
| **Prompt Engineering** | Processo de criar, testar e refinar instruções (prompts) para orientar a IA na geração de respostas mais adequadas ao objetivo.                |
| **OCI**                | Oracle Cloud Infrastructure — plataforma de computação em nuvem utilizada como contexto tecnológico neste projeto.                             |
| **NotebookLM**         | Ferramenta do Google para organização, análise e consulta de fontes, utilizada para estruturar o Caderno Temático.                             |
| **Cicatrizes**         | Registro das dificuldades, erros, testes e ajustes realizados durante o desenvolvimento, evidenciando o processo de aprendizado e refinamento. |
