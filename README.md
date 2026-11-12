# Olá, eu sou o Michael Costa 👋

**Desenvolvedor Back-end Java** · Estudante de Engenharia de Software (UniFatecie) · Salvador, BA

Construo APIs REST com **Java e Spring Boot**, da modelagem do banco ao deploy em containers, com testes e CI. Também crio sites e landing pages para pequenos negócios.

🎯 Busco minha primeira oportunidade como **Desenvolvedor Java Júnior ou Estagiário back-end** (presencial em Salvador, híbrido ou remoto).

[![LinkedIn](https://img.shields.io/badge/LinkedIn-michaelcostadevv-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/michaelcostadevv/)

---

## 🛠️ Stack

- **Back-end:** Java 17/21 · Spring Boot · Spring Security · JWT · Spring Data JPA / Hibernate · Bean Validation
- **Banco de dados:** MySQL · PostgreSQL · H2 · SQL · JDBC
- **Testes e qualidade:** JUnit 5 · Mockito · AssertJ · MockMvc · GitHub Actions (CI)
- **Infra e ferramentas:** Docker · Docker Compose · Maven · Git · Postman · Swagger/OpenAPI
- **Front-end:** React · TypeScript · HTML · CSS · JavaScript · Vercel

---

## 🚀 Projetos em destaque

### 🛒 [MarketCore API](https://github.com/michaelcostadevv/MarketCore-Spring) — Java 21 · Spring Boot · MySQL · Docker

API REST de e-commerce que simula um ambiente real de vendas.

- Autenticação **JWT** stateless com **Spring Security** e papéis USER/ADMIN
- Autorização por objeto: cada cliente só acessa os próprios pedidos (proteção contra IDOR/BOLA)
- Baixa de estoque na mesma transação do pedido + **lock otimista** contra venda acima do estoque
- Ciclo de vida do pedido com devolução ao estoque no cancelamento
- Testes com JUnit 5, Mockito e MockMvc, **CI no GitHub Actions**, Docker Compose e Swagger

Front-end em React + TypeScript: [MarketCore-Web](https://github.com/michaelcostadevv/MarketCore-Web)

### 🏢 [Sistema Gerencial (ERP)](https://github.com/michaelcostadevv/Sistema-Gerencial) — Spring Boot · PostgreSQL

API REST de ERP para clientes, produtos e pedidos, com cálculo de total no servidor, preço congelado no item, `@Transactional`, lock otimista, `@EntityGraph` contra N+1 e testes com JUnit e Mockito.

### 💬 [Assistente de Compromissos](https://github.com/michaelcostadevv/assistente-wpp-pessoal) — Spring Boot · JWT · PostgreSQL

API com cadastro e login via JWT para registrar compromissos e um agendador (`@Scheduled`) que envia lembretes por uma integração de WhatsApp.

### 💅 [Landing page Alanda Melo Studio](https://github.com/michaelcostadevv/alanda-melo-studio) — HTML · CSS · JavaScript

Site real de um estúdio de manicure em Salvador, publicado na Vercel: **[alanda-melo-studio.vercel.app](https://alanda-melo-studio.vercel.app)**

---

## 📈 Evolução

`Java + POO` → `JDBC + MySQL` ([MarketCore v1](https://github.com/michaelcostadevv/MarketCore)) → `Spring Boot + JPA` → `API REST` → `Spring Security + JWT` → `Testes + CI` → `Docker` → `React`
---

📫 Me chame no [LinkedIn](https://www.linkedin.com/in/michaelcostadevv/). Estou aberto a vagas, conversas e feedback sobre os projetos.
