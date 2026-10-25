<div align="center">

# Raone Alencar

### 💻 Desenvolvedor Back-end Java · Spring Boot, PostgreSQL e Next.js

**Construo sistemas web completos, do modelo de dados à interface, com segurança e regras de negócio no centro.**

<a href="https://github.com/raonesi/reconstroi"><img src="https://img.shields.io/badge/Projeto_em_destaque-ReConstr%C3%B3i-2E7D32?style=for-the-badge&logo=github&logoColor=white" alt="ReConstrói" /></a>

</div>

---

## 👋 Sobre mim

Sou **estagiário na Gala, em Aparecida do Taboado (MS)**, Técnico em Desenvolvimento de Sistemas pela Unifunec e estudante de **Análise e Desenvolvimento de Sistemas (ADS)** na Unifunec de Santa Fé.

Gosto de problemas reais de negócio: pegar um fluxo bagunçado e entregar um sistema organizado, rastreável e que roda de ponta a ponta. Meus projetos seguem o mesmo desenho: **API REST em camadas, banco versionado com migrations, autenticação JWT e deploy com Docker**.

Hoje estou aprofundando **arquitetura em camadas, segurança de APIs e containers**.

---

## 📊 Atividade

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=raonesi&show_icons=true&theme=radical&hide_border=true" alt="Estatísticas do GitHub" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=raonesi&layout=compact&theme=radical&hide_border=true" alt="Linguagens mais usadas" />

</div>

---

## 🛠️ Stack

**Back-end**

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)

**Front-end**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Thymeleaf](https://img.shields.io/badge/Thymeleaf-005F0F?style=for-the-badge&logo=thymeleaf&logoColor=white)

**Dados**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=for-the-badge&logo=flyway&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white)

**Infra e ferramentas**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

**Outras linguagens**

![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![Java Swing](https://img.shields.io/badge/Java_Swing-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)

---

## 🚀 Projetos em destaque

**♻️ [ReConstrói](https://github.com/raonesi/reconstroi): reaproveitamento de materiais de construção**<br>
Plataforma que conecta doadores, construtoras, ONGs e famílias e acompanha o ciclo do anúncio até a doação finalizada. Três perfis (doador, beneficiário e administrador) com autoridades granulares recalculadas a partir do banco a cada requisição JWT, de modo que bloquear uma conta invalida na hora os tokens já emitidos. O fluxo de reserva é transacional (`DISPONÍVEL → SOLICITADA → APROVADA → RETIRADA → FINALIZADA`), com garantia no serviço e no PostgreSQL contra duas reservas ativas para o mesmo material, reservas parciais e histórico de ações com usuário, data/hora e IP. O mesmo backend atende a **web em Next.js** e um **cliente desktop em Java Swing** (padrão VIEW → DTO → DAO).<br>
<br>Operação: schema versionado com Flyway, Docker Compose com imagens multi-stage, health checks e volumes persistentes, e a API só inicia com `JWT_SECRET` e senha de banco definidos, sem segredo padrão no código.<br>
`Spring Boot` · `Spring Security` · `JWT` · `PostgreSQL` · `Flyway` · `Next.js` · `TypeScript` · `Tailwind` · `Java Swing` · `Docker`

**🍳 [Cadastro de Receitas](https://github.com/raonesi/cadastro-receitas-spring-boot)**<br>
CRUD web de receitas com validação de formulário (Bean Validation) e persistência em PostgreSQL, organizado em `controller`, `service`, `repository` e `model`.<br>
`Spring Boot` · `Spring MVC` · `Thymeleaf` · `JPA/Hibernate` · `PostgreSQL`

**📚 [Projeto Biblioteca](https://github.com/raonesi/Projeto_biblioteca)**<br>
Sistema web de biblioteca com login, cadastro de usuários, cadastro de livros com controle de estoque e faixa etária, empréstimos, devoluções e multa por atraso, no padrão MVC com DAO.<br>
`Java` · `Servlets` · `JSP` · `PostgreSQL`

---

<div align="center">

**[GitHub](https://github.com/raonesi)** · **Aparecida do Taboado, MS**

</div>
