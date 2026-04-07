<div align="center">
<img src="banner_github.svg" alt="" width="100%">

### Full Stack Developer · Especialista em IA & LLMs 

*Construo aplicações que pensam — unindo arquitetura de software robusta com a inteligência dos modelos de linguagem modernos.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/cainã-barros-0aaa0a282/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:cainabnascimento@gmail.com)


</div>

---

## Sobre mim

Minha trajetória começou longe das telas: passei anos como **Soldador Sênior**, trabalhando em estruturas de alta responsabilidade onde erro não era opção. Essa escola me formou em algo que nenhum bootcamp ensina — **disciplina de execução, pensamento sistêmico e responsabilidade em ambientes críticos**.

Hoje aplico essa mesma mentalidade na engenharia de software. Construo desde aplicações Angular com arquitetura limpa até pipelines de IA com LangGraph, passando por APIs REST em FastAPI e sistemas de observabilidade de LLMs. Sou um desenvolvedor Full Stack que **escolheu se especializar profundamente em IA** — não alguém que só conhece prompts.

O que me diferencia: consigo pegar um problema de negócio real, modelar a solução em código limpo, escalável e testável, **e ainda integrar inteligência artificial onde ela genuinamente agrega valor** — sem hype, com engenharia.

---

## Stack Técnica

### 🤖 AI, LLMs & Dados

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=for-the-badge&logo=openai&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-000000?style=for-the-badge&logo=chainlink&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3A5E?style=for-the-badge&logo=graphql&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

**Conceitos:** RAG Pipelines · Prompt Engineering · Structured Output · Agentes de IA · Embeddings · Observabilidade de LLMs (tokens, latência, custo) · Multi-agent Orchestration

---

### ⚙️ Backend & Arquitetura

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)

**Conceitos:** Clean Architecture · SOLID · Strategy Pattern · Repository Pattern · Retry/Backoff (tenacity) · Background Tasks · Pydantic v2 · Structured Logging (structlog)

---

### 🖥️ Frontend

![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)

**Conceitos:** Standalone Components · Reactive Forms · DI · Lifecycle Hooks · Lazy Loading · Tipagem estrita

---

### 🛠️ Banco de Dados, DevOps & Ferramentas

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

---

## Projetos em Destaque

### 🤖 [AI Insight Engine](https://github.com/Cainan-bn/AI-Insight-Engine).
> Pipeline automatizado de análise de notícias sobre IA com LLMs, observabilidade completa e dashboard interativo.

Pipeline de ponta a ponta: scraping de notícias → processamento → análise com **GPT-4o-mini via OpenAI API** → API REST (FastAPI) → Dashboard (Streamlit). Inclui sistema de observabilidade próprio com rastreamento de tokens, latência e custo por requisição, além de avaliação automática de qualidade de prompts.

`Python` `FastAPI` `OpenAI API` `Pydantic v2` `Pandas` `Streamlit` `tenacity` `pytest`

---

### 🃏 [Assistente de Cartões IA](https://github.com/Cainan-bn/Assistente-de-cartao).
> Sistema multiagente conversacional para operações de cartão de crédito, orquestrado por grafo de estados.

Arquitetura de **agentes especializados** (fatura, limite, transações) com roteamento automático de intenção via classificador few-shot com structured output. Memória de sessão via Redis, retry resiliente com tenacity, containerização completa Docker multi-stage e logging estruturado em JSON.

`Python` `LangGraph` `LangChain` `GPT-4o` `FastAPI` `Redis` `Docker` `httpx` `pytest-asyncio`

---

### 📚 [Catálogo de Livros — Angular](https://github.com/Cainan-bn/angular-book-manager-solid).
> Sistema de gestão de acervo com arquitetura limpa, tipagem estrita e boas práticas SOLID.

Aplicação Full Stack acadêmica em **Angular 17+** com separação clara entre camadas `core` (lógica de negócio) e `features` (UI por domínio). Demonstra domínio de injeção de dependência, lifecycle hooks, two-way binding e otimizações de renderização com `trackBy`. Documentada com trade-offs explícitos entre abordagem didática e produção corporativa.

`Angular 17+` `TypeScript` `Bootstrap 5` `SOLID` `Clean Architecture`

---

## Vamos conversar?

Estou aberto a oportunidades em **Engenharia de IA, Full Stack, Backend e Dados**. Se você tem um problema complexo que precisa de software bem construído — com ou sem IA —, quero ouvir.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Me_encontre_no_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/cainã-barros-0aaa0a282/)
[![Email](https://img.shields.io/badge/Me_manda_um_email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:cainabnascimento@gmail.com)

</div>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=120&section=footer"/>
</div>
