<h3 align="center" style="border-bottom: none; padding-bottom: 0;">Projetos em Destaque</h3>
<hr>

### AutoLog

![Flutter](https://img.shields.io/badge/flutter-555555?style=for-the-badge&logo=flutter&logoColor=26BEFD) ![Firebase](https://img.shields.io/badge/firebase-555555?style=for-the-badge&logo=firebase&logoColor=FFCA28) ![Em teste](https://img.shields.io/badge/em_teste-yellow?style=for-the-badge)

Aplicativo mobile para controle de manutenções veiculares — histórico de serviços, troca de óleo/bateria e gastos por veículo. O objetivo foi ir além de "só fazer funcionar": aplicar Clean Arch com boas práticas, e percorrer o fluxo real de publicação em loja — identidade visual, assinatura de release, política de privacidade, monitoramento de erros em produção e teste fechado com usuários reais.

- **Stack:** Flutter/Dart · Firebase (Auth, Firestore, Crashlytics) · flutter_bloc (Cubit) · get_it · dartz
- **Arquitetura:** Clean Architecture em 4 camadas, Repository Pattern, isolamento de dados por usuário via regras de segurança do Firestore
- **Testes:** unitários, widget e de repositório contra Firestore simulado (mocktail · bloc_test · fake_cloud_firestore)
- **Status:** Desenvolvimento concluído — em teste fechado na Play Store ⏳

Mais informações no readme do projeto: **[→ repositório](https://github.com/paulohm0/autolog_app)**

<p>
  <img src="https://github.com/user-attachments/assets/52613776-cdcf-428a-9e12-9fca6d897692" width="100" />
  <img src="https://github.com/user-attachments/assets/15c33df3-dbdd-473a-a75b-e85a0dbe6749" width="100" />
  <img src="https://github.com/user-attachments/assets/ab639023-1e84-4b71-8c9a-598ab2f3160e" width="100" />
  <img src="https://github.com/user-attachments/assets/62435743-8b0c-409e-9ee5-bb8e0dc98688" width="100" />
</p>

---

### Sentinel API

![Spring Boot](https://img.shields.io/badge/spring_boot-555555?style=for-the-badge&logo=springboot&logoColor=6DB33F) ![PostgreSQL](https://img.shields.io/badge/postgresql-555555?style=for-the-badge&logo=postgresql&logoColor=4169E1) ![Docker](https://img.shields.io/badge/docker-555555?style=for-the-badge&logo=docker&logoColor=2496ED) ![Em desenvolvimento](https://img.shields.io/badge/em_desenvolvimento-yellow?style=for-the-badge)

API REST para gestão de imóveis alugados — condomínios, apartamentos, inquilinos e contratos, pensada pra substituir o controle manual em planilha. O objetivo foi ir além de "só fazer funcionar": aplicar arquitetura em camadas por domínio, autenticação stateless com JWT, escopo de dado por dono do recurso e cobertura de testes automatizados.

- **Stack:** Java 21 · Spring Boot · Spring Security (JWT) · Spring Data JPA/Hibernate · PostgreSQL · Docker
- **Arquitetura:** módulos por domínio em camadas (entity/repository/service/controller/dto), soft delete como padrão em toda a API, escopo de dado por dono do recurso e tratamento de erros centralizado
- **Testes:** unitários de service e controller (JUnit 5 · Mockito)
- **Status:** Em desenvolvimento ativo 🚧

Mais informações no readme do projeto: **[→ repositório](https://github.com/paulohm0/sentinel_api)**

---

### 🗂️ Outros Projetos

**Mobile:** [kinvo-mobile-test](https://github.com/paulohm0/kinvo-mobile-test) · [techtaste-app](https://github.com/paulohm0/techtaste-app) · [gok-mobile-test](https://github.com/paulohm0/gok-mobile-test) · [wemovies-mobile-test](https://github.com/paulohm0/wemovies-mobile-test) · [telemedicina-mobile-test](https://github.com/paulohm0/telemedicina-mobile-test)

**Backend:** [orderflow](https://github.com/paulohm0/orderflow) · [investments-aggregator](https://github.com/paulohm0/investments-aggregator) · [latency-tracker_api](https://github.com/paulohm0/latency-tracker_api)
