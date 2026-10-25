<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=200&color=0:C8102E,50:7A0A1C,100:000000&text=Raone%20Alencar&fontColor=ffffff&fontSize=52&fontAlignY=38&animation=fadeIn&desc=Back-end%20Java%20%C2%B7%20Spring%20Boot%20%C2%B7%20PostgreSQL%20%C2%B7%20Next.js&descSize=18&descAlignY=60" alt="Raone Alencar" width="100%" />

<a href="https://github.com/raonesi">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=1000&color=C8102E&center=true&vCenter=true&width=700&lines=Estagi%C3%A1rio+na+Gala+%C2%B7+Aparecida+do+Taboado+(MS);Construo+APIs+REST+com+Spring+Boot+e+JWT;Do+modelo+de+dados+%C3%A0+interface+com+Next.js;Banco+versionado+com+Flyway+e+deploy+com+Docker;Sempre+aprendendo+e+construindo+algo+novo" alt="Animação de apresentação" />
</a>

**Construo sistemas web completos, do modelo de dados à interface, com segurança e regras de negócio no centro.**

<a href="https://github.com/raonesi/reconstroi"><img src="https://img.shields.io/badge/Projeto_em_destaque-ReConstr%C3%B3i-C8102E?style=for-the-badge&logo=github&logoColor=white" alt="ReConstrói" /></a>

</div>

---

## 👋 Sobre mim

Sou desenvolvedor back-end em início de carreira e **estagiário na Gala, em Aparecida do Taboado (MS)**. Sou Técnico em Desenvolvimento de Sistemas pela Unifunec e estudo **Análise e Desenvolvimento de Sistemas (ADS)** na Unifunec de Santa Fé.

Gosto de problemas reais de negócio: pegar um fluxo bagunçado e entregar um sistema organizado, rastreável e que roda de ponta a ponta. Meus projetos seguem o mesmo desenho: **API REST em camadas, banco versionado com migrations, autenticação JWT e deploy com Docker**.

- 🔐 **Segurança:** autenticação JWT, controle de permissões por perfil e regras de negócio garantidas também no banco
- 🗄️ **Dados:** modelagem em PostgreSQL com migrations versionadas (Flyway)
- 🧩 **Arquitetura:** camadas bem separadas (controller, service, repository) e um mesmo backend servindo web e desktop
- 📦 **Entrega:** Docker Compose, health checks e configuração por variáveis de ambiente

🎯 **Hoje estou aprofundando:** arquitetura em camadas, segurança de APIs e containers.

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

<img src="https://capsule-render.vercel.app/api?type=waving&height=120&color=0:000000,50:7A0A1C,100:C8102E&section=footer" alt="" width="100%" />

</div>
