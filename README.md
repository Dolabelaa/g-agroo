# 🌱 G-Agro 👨‍🌾

> [!NOTE]
> **G-Agro** é uma plataforma completa de **gestão agrícola inteligente** que centraliza o controle de fazendas, talhões, safras, insumos e monitoramento climático em um único sistema. Leve mais produtividade e rastreabilidade para o campo.

<table>
  <tr>
    <td width="800px">
      <div align="justify">
        O <b>G-Agro</b> é uma plataforma digital de <b>gestão agrícola inteligente</b> desenvolvida para atender produtores rurais e técnicos agrônomos que buscam digitalizar e otimizar o gerenciamento de suas propriedades. O sistema permite o controle completo de <i>fazendas, talhões, safras, estoque de insumos e monitoramento climático</i>, integrando dados em tempo real de APIs meteorológicas e geográficas para auxiliar na <b>tomada de decisões assertivas no campo</b>. Com uma arquitetura moderna (React + Spring Boot + PostgreSQL), o G-Agro entrega uma experiência responsiva tanto na web quanto no mobile, promovendo <i>rastreabilidade, produtividade e sustentabilidade</i> na agricultura brasileira.
      </div>
    </td>
    <td align="center">
      <img src="https://img.shields.io/badge/🌱_G--Agro-v1.0.0-2E7D32?style=for-the-badge" alt="G-Agro" width="180px"/>
    </td>
  </tr>
</table>

---

## 🚧 Status do Projeto

[![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/Dolabelaa/g-agro/main.yml?branch=main&style=flat-square)](https://github.com/Dolabelaa/g-agro/actions)
[![Versão](https://img.shields.io/badge/Versão-v1.0.0-2E7D32)](https://github.com/Dolabelaa/g-agro/releases)
[![Licença](https://img.shields.io/badge/Licença-MIT-2E7D32)](#-licença)

[![Versão](https://img.shields.io/badge/Versão-v1.0.0-2E7D32?style=for-the-badge)](https://github.com/Dolabelaa/g-agro/releases)
![React](https://img.shields.io/badge/React-18.3.1-2E7D32?style=for-the-badge&logo=react&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-5.2.0-2E7D32?style=for-the-badge&logo=vite&logoColor=white)
![Java](https://img.shields.io/badge/Java-17-2E7D32?style=for-the-badge&logo=openjdk&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-3.9.6-2E7D32?style=for-the-badge&logo=apachemaven&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.2.5-2E7D32?style=for-the-badge&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16-2E7D32?style=for-the-badge&logo=postgresql&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-0.74-2E7D32?style=for-the-badge&logo=react&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-7.2-2E7D32?style=for-the-badge&logo=redis&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-EC2%2FRDS%2FS3-2E7D32?style=for-the-badge&logo=amazonaws&logoColor=white)

---

## 📚 Índice

- [🔗 Links Úteis](#-links-úteis)
- [📝 Sobre o Projeto](#-sobre-o-projeto)
- [✨ Funcionalidades Principais](#-funcionalidades-principais)
- [🛠 Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [🏗 Arquitetura](#-arquitetura)
- [🔧 Instalação e Execução](#-instalação-e-execução)
- [🚀 Deploy](#-deploy)
- [📂 Estrutura de Pastas](#-estrutura-de-pastas)
- [🎥 Demonstração](#-demonstração)
- [🧪 Testes](#-testes)
- [🔗 Documentações Utilizadas](#-documentações-utilizadas)
- [👥 Autores](#-autores)
- [🤝 Contribuição](#-contribuição)
- [🙏 Agradecimentos](#-agradecimentos)
- [📄 Licença](#-licença)

---

## 🔗 Links Úteis

* 🌐 **Demo Online:** [Acesse a Aplicação Web](https://g-agro.vercel.app)
  > 💻 Aplicação hospedada na Vercel (front-end) com back-end na AWS EC2. Credenciais de demo: `demo@gagro.com.br` / `Demo@2025`.

* 📱 **Download Mobile:** [Google Play](https://play.google.com/store/apps/g-agro) | [APK Direto](https://github.com/Dolabelaa/g-agro/releases/download/v1.0.0/g-agro.apk)
  > 📱 App Android disponível via Google Play ou APK direto.

* 📖 **Documentação da API:** [Swagger / OpenAPI](https://api.g-agro.com.br/swagger-ui.html)
  > 📚 Documentação interativa completa da API REST gerada pelo SpringDoc OpenAPI 3.

---

## 📝 Sobre o Projeto

O **G-Agro** nasceu da necessidade real de produtores rurais brasileiros de **centralizar e digitalizar** a gestão de suas propriedades agrícolas. Atualmente, grande parte dos pequenos e médios produtores ainda gerencia suas fazendas em planilhas ou cadernos, perdendo rastreabilidade, produtividade e acesso a crédito rural por falta de documentação estruturada.

**Por que existe:** O agronegócio representa mais de 25% do PIB brasileiro, mas a digitalização do campo ainda é baixa. O G-Agro surge para preencher essa lacuna com uma solução acessível, intuitiva e completa.

**Problema resolvido:** Falta de controle sobre safras e produtividade, dificuldade no gerenciamento de estoque de insumos, ausência de alertas climáticos automatizados e impossibilidade de gerar relatórios para financiamentos bancários.

**Contexto:** Projeto acadêmico da disciplina de Laboratório de Desenvolvimento de Software — PUC Minas, simulando um produto real de mercado com arquitetura profissional.

**Onde pode ser utilizado:** Fazendas de pequeno, médio e grande porte que cultivam grãos (soja, milho, trigo), horticultura, fruticultura ou pecuária integrada.

> [!NOTE]
> Este projeto foi desenvolvido como trabalho acadêmico seguindo boas práticas de engenharia de software, arquitetura em camadas, diagramação com PlantUML e documentação profissional.

---

## ✨ Funcionalidades Principais

- 🔐 **Autenticação Segura:** Login com JWT, Cadastro e Recuperação de Senha via e-mail (SendGrid).
- 🗺️ **Gestão de Fazendas e Talhões:** Cadastro completo com geolocalização, área em hectares e mapeamento por cultura.
- 🌾 **Controle de Safras:** Registro de plantio, acompanhamento do ciclo de desenvolvimento e colheita com cálculo de produtividade (kg/ha).
- 🧪 **Monitoramento de Solo:** Registro de laudos de análise (pH, NPK, matéria orgânica) com recomendações automáticas de corretivos.
- 🌦️ **Alertas Climáticos:** Integração com a API do INMET para previsão do tempo e alertas automáticos de geada, seca e excesso de chuva.
- 📦 **Gestão de Insumos:** Controle de estoque de fertilizantes, defensivos e sementes com alertas de reposição e rastreamento de aplicações.
- 📊 **Dashboard de Produtividade:** Painel visual com gráficos de produção por safra, consumo de insumos e comparativo entre talhões.
- 📋 **Relatórios Exportáveis:** Geração de relatórios em PDF e CSV para laudos técnicos e prestação de contas.
- 📱 **Aplicativo Mobile:** App React Native para registros em campo com modo offline e sincronização posterior.
- 🔔 **Sistema de Notificações:** Alertas por e-mail e push para datas de aplicação, colheita e eventos climáticos críticos.

---

## 🛠 Tecnologias Utilizadas

### 💻 Front-end

* **Framework/Biblioteca:** React 18.3.1
* **Linguagem/Superset:** TypeScript 5.4.5
* **Estilização:** Tailwind CSS 3.4.3
* **Gerenciamento de Estado:** Zustand 4.5.2 + React Query 5.35
* **Build Tool:** Vite 5.2.0
* **Mapas:** React Leaflet 4.2.1
* **Gráficos:** Recharts 2.12
* **HTTP Client:** Axios 1.7.2

### 🖥️ Back-end

* **Linguagem/Runtime:** Java 17 (JDK LTS)
* **Framework:** Spring Boot 3.2.5
* **Banco de Dados:** PostgreSQL 16 + Redis 7.2 (cache)
* **ORM:** Hibernate / Spring Data JPA 3.2.5
* **Autenticação:** JWT (jjwt 0.12.5) + Spring Security 6.2.4
* **Migrações:** Flyway 10.12
* **Documentação API:** SpringDoc OpenAPI 3 (Swagger UI)

### 📱 Mobile

* **Framework:** React Native 0.74.1 + Expo 51.0
* **Ferramentas:** React Navigation 6.x, AsyncStorage 1.23 (modo offline)

### ⚙️ Infraestrutura & DevOps

* **Containerização:** Docker 26.1
* **Cloud:** AWS (EC2, RDS PostgreSQL 16, S3)
* **Deploy Front-end:** Vercel
* **CI/CD:** GitHub Actions

---

## 🏗 Arquitetura

O G-Agro adota uma **arquitetura em camadas (Layered Architecture)** no back-end, com separação clara entre **Controller → Service → Repository → Model**, seguindo os princípios do **Domain-Driven Design (DDD)**. O front-end é uma **SPA (Single Page Application)** em React comunicando-se exclusivamente via **API REST JSON**.

**Padrões adotados:** Repository Pattern, Service Layer, DTO Pattern, Observer (alertas via eventos Spring), Factory (relatórios PDF/CSV).

**Decisões arquiteturais importantes:**
- JWT stateless com refresh token para escalabilidade horizontal
- Flyway para versionamento do schema, garantindo reprodutibilidade
- Modo offline no mobile com fila de sincronização via AsyncStorage

---

### 📐 Diagramas PlantUML

> Todos os diagramas foram criados com **[PlantUML](https://plantuml.com)**. Os arquivos `.puml` estão em [`/docs/plantuml/`](./docs/plantuml/) e as imagens em [`/docs/images/`](./docs/images/).

---

#### Diagrama 1 — Arquitetura de Componentes (Camadas)

Organização interna do sistema em camadas: Front-end SPA, Back-end Spring Boot (Configuração, Apresentação, Aplicação, Persistência) e integrações externas.

<div align="center">
  <img src="./docs/images/01_arquitetura_componentes.png" alt="Arquitetura de Componentes G-Agro" width="850px"/>
</div>

---

#### Diagrama 2 — Diagrama de Classes (Domínio)

Estrutura completa das entidades de domínio, seus atributos, métodos e relacionamentos entre Usuario, Fazenda, Talhao, PlantioSafra, Cultura, Insumo e demais classes.

<div align="center">
  <img src="./docs/images/02_diagrama_classes.png" alt="Diagrama de Classes G-Agro" width="850px"/>
</div>

---

#### Diagrama 3 — Modelo de Dados (PostgreSQL)

Modelo físico do banco de dados PostgreSQL com todas as tabelas, colunas, tipos de dados e relacionamentos por chaves estrangeiras.

<div align="center">
  <img src="./docs/images/03_modelo_dados_der.png" alt="Modelo de Dados G-Agro" width="850px"/>
</div>

---

#### Diagrama 4 — Sequência: Fluxo de Autenticação (Login JWT)

Fluxo completo de login — do preenchimento do formulário até a geração do JWT — com tratamento de erros para usuário não encontrado e senha incorreta.

<div align="center">
  <img src="./docs/images/04_sequencia_login.png" alt="Sequência Login JWT G-Agro" width="850px"/>
</div>

---

#### Diagrama 5 — Sequência: Registro de Safra e Alerta Climático

Fluxo de registro de plantio com validação de estoque de insumos, persistência da safra, notificação ao produtor e disparo automático de alertas climáticos via integração com a API do INMET.

<div align="center">
  <img src="./docs/images/05_sequencia_safra.png" alt="Sequência Safra e Alerta G-Agro" width="850px"/>
</div>

---

#### Diagrama 6 — Casos de Uso

Todos os casos de uso organizados por ator: Produtor Rural, Técnico Agrônomo, Administrador e sistemas externos (API INMET e SendGrid).

<div align="center">
  <img src="./docs/images/06_casos_de_uso.png" alt="Casos de Uso G-Agro" width="850px"/>
</div>

---

#### Diagrama 7 — Diagrama de Implantação (Deploy em Produção)

Visão completa da infraestrutura de produção: dispositivos do usuário, pipeline CI/CD (GitHub Actions), Vercel (CDN), AWS (ECS/EC2, RDS, S3) e serviços de terceiros.

<div align="center">
  <img src="./docs/images/07_deployment.png" alt="Deployment G-Agro" width="850px"/>
</div>

---

#### Diagrama 8 — Comunicação: Alerta Climático (UC-12)

Colaboração entre objetos no disparo automático de alertas climáticos via integração com a API do INMET.

<div align="center">
  <img src="./docs/images/08_comunicacao_alerta.png" alt="Comunicação Alerta Climático" width="850px"/>
</div>

---

#### Diagrama 9 — Comunicação: Registro de Safra (UC-07)

Colaboração entre objetos no fluxo de registro de plantio, validação de estoque e notificação ao produtor.

<div align="center">
  <img src="./docs/images/09_comunicacao_safra.png" alt="Comunicação Registro de Safra" width="850px"/>
</div>

---

#### Diagrama 10 — Estados: AlertaClima

Ciclo de vida de um alerta climático desde sua criação até ser marcado como lido pelo produtor.

<div align="center">
  <img src="./docs/images/10_estado_alerta.png" alt="Estados AlertaClima" width="600px"/>
</div>

---

#### Diagrama 11 — Estados: Insumo

Ciclo de vida do estoque de um insumo, com transições entre disponível, estoque baixo e esgotado.

<div align="center">
  <img src="./docs/images/11_estado_insumo.png" alt="Estados Insumo" width="600px"/>
</div>

---

#### Diagrama 12 — Estados: PlantioSafra

Ciclo de vida de uma safra desde o planejamento até a colheita ou cancelamento.

<div align="center">
  <img src="./docs/images/12_estado_safra.png" alt="Estados PlantioSafra" width="600px"/>
</div>

---

| # | Diagrama | Tipo | Arquivo `.puml` |
|:---:|:---|:---:|:---:|
| 1 | Arquitetura de Componentes | Component | [`01_arquitetura_componentes.puml`](./docs/plantuml/01_arquitetura_componentes.puml) |
| 2 | Diagrama de Classes | UML Class | [`02_diagrama_classes.puml`](./docs/plantuml/02_diagrama_classes.puml) |
| 3 | Modelo de Dados (DER) | Entity-Relationship | [`03_modelo_dados_der.puml`](./docs/plantuml/03_modelo_dados_der.puml) |
| 4 | Sequência — Login JWT | UML Sequence | [`04_sequencia_login.puml`](./docs/plantuml/04_sequencia_login.puml) |
| 5 | Sequência — Safra e Alerta | UML Sequence | [`05_sequencia_safra.puml`](./docs/plantuml/05_sequencia_safra.puml) |
| 6 | Casos de Uso | UML Use Case | [`06_casos_de_uso.puml`](./docs/plantuml/06_casos_de_uso.puml) |
| 7 | Implantação (Deploy) | UML Deployment | [`07_deployment.puml`](./docs/plantuml/07_deployment.puml) |
| 8 | Comunicação — Alerta Climático | UML Communication | [`08_comunicacao_alerta.puml`](./docs/plantuml/08_comunicacao_alerta.puml) |
| 9 | Comunicação — Registro de Safra | UML Communication | [`09_comunicacao_safra.puml`](./docs/plantuml/09_comunicacao_safra.puml) |
| 10 | Estados — AlertaClima | UML State | [`10_estado_alerta.puml`](./docs/plantuml/10_estado_alerta.puml) |
| 11 | Estados — Insumo | UML State | [`11_estado_insumo.puml`](./docs/plantuml/11_estado_insumo.puml) |
| 12 | Estados — PlantioSafra | UML State | [`12_estado_safra.puml`](./docs/plantuml/12_estado_safra.puml) |

---

## 🔧 Instalação e Execução

### Pré-requisitos

* **Java JDK 17** ou superior — [Download Adoptium](https://adoptium.net/)
* **Node.js v20.x LTS** ou superior — [Download Node.js](https://nodejs.org/)
* **npm v10+** ou **yarn v1.22+**
* **Docker 26+** — [Download Docker Desktop](https://www.docker.com/products/docker-desktop/)
* **Git** — [Download Git](https://git-scm.com/)

---

### 🔑 Variáveis de Ambiente

#### 1. Back-end (Spring Boot)

Crie `backend/src/main/resources/application-local.yml` ou configure as variáveis de ambiente:

| Variável | Descrição | Exemplo |
|:---|:---|:---|
| `SERVER_PORT` | Porta do back-end | `8080` |
| `SPRING_DATASOURCE_URL` | URL JDBC do PostgreSQL | `jdbc:postgresql://localhost:5432/gagro_db` |
| `SPRING_DATASOURCE_USERNAME` | Usuário do banco | `gagro_user` |
| `SPRING_DATASOURCE_PASSWORD` | Senha do banco | `GAgro@2025` |
| `JWT_SECRET` | Chave secreta JWT (Base64) | `c2Vj...` |
| `JWT_EXPIRATION_MS` | Expiração do access token | `3600000` (1h) |
| `REDIS_HOST` | Host do Redis | `localhost` |
| `AWS_S3_BUCKET` | Nome do bucket S3 | `gagro-arquivos-prod` |
| `SENDGRID_API_KEY` | Chave API do SendGrid | `SG.xxx...` |
| `INMET_API_KEY` | Chave API do INMET | `inmet-key-xxx` |

#### 2. Front-end (React + Vite)

Crie o arquivo `frontend/.env.local`:

| Variável | Descrição | Exemplo |
|:---|:---|:---|
| `VITE_API_URL` | URL base da API back-end | `http://localhost:8080/api/v1` |
| `VITE_GOOGLE_MAPS_KEY` | Chave Google Maps | `AIzaSy...` |
| `VITE_APP_NAME` | Nome da aplicação | `G-Agro` |

---

#### 3. Exemplos de Variáveis na Vercel (Produção)

**Front-end React + Vite:**
```
VITE_API_URL=https://api.g-agro.com.br/api/v1
VITE_GOOGLE_MAPS_KEY=AIzaSyXXX
VITE_APP_NAME=G-Agro
```

**Back-end Spring Boot (AWS EC2 — `.env`):**
```
SPRING_DATASOURCE_URL=jdbc:postgresql://gagro-db.rds.amazonaws.com:5432/gagro_db
SPRING_DATASOURCE_USERNAME=gagro_admin
SPRING_DATASOURCE_PASSWORD=Senha_Prod_Segura!
JWT_SECRET=chave-jwt-producao-super-segura-base64
AWS_S3_BUCKET=gagro-arquivos-prod
SENDGRID_API_KEY=SG.chave-producao
```

> **Obs.:** Nunca versione arquivos `.env` com senhas reais. Use `.env.example` no repositório e configure as variáveis reais no painel do provedor.

---

### 📦 Instalação de Dependências

**1. Clone o repositório:**
```bash
git clone https://github.com/Dolabelaa/g-agro.git
cd g-agro
```

**2. Front-end:**
```bash
cd frontend
npm install
cd ..
```

**3. Back-end (Maven Wrapper):**
```bash
cd backend
./mvnw clean install -DskipTests
cd ..
```

---

### 💾 Inicialização do Banco de Dados (PostgreSQL)

```bash
# Sobe PostgreSQL e Redis via Docker
docker run --name gagro-db \
  -e POSTGRES_DB=gagro_db \
  -e POSTGRES_USER=gagro_user \
  -e POSTGRES_PASSWORD=GAgro@2025 \
  -p 5432:5432 -d postgres:16

docker run --name gagro-redis -p 6379:6379 -d redis:7-alpine
```

O Flyway aplicará as migrações automaticamente no primeiro startup do back-end.

---

### ⚡ Como Executar a Aplicação

Execute em **dois terminais separados**:

#### Terminal 1 — Back-end (Spring Boot)

```bash
cd backend
./mvnw spring-boot:run -Dspring-boot.run.profiles=local
```

🚀 **API em:** `http://localhost:8080` | 📖 **Swagger:** `http://localhost:8080/swagger-ui.html`

---

#### Terminal 2 — Front-end (React + Vite)

```bash
cd frontend
npm run dev
```

🎨 **App Web em:** `http://localhost:5173`

---

### 🐳 Execução Local Completa com Docker Compose

```bash
# Linux — inicia o serviço Docker
sudo systemctl start docker

# Sobe PostgreSQL + Redis + Back-end + Front-end
docker-compose up --build -d

# Verifica containers
docker ps

# Logs do back-end (migrações Flyway)
docker logs g-agro-backend -f

# Para e remove containers
docker-compose down
```

> [!NOTE]
> O parâmetro `--build` reconstrói as imagens com o código mais recente. Use `-d` para executar em segundo plano.

---

## 🚀 Deploy

```bash
# 1. Build do Front-end (gera /frontend/dist)
cd frontend && npm run build

# 2. Build do Back-end (gera /backend/target/g-agro-1.0.0.jar)
cd ../backend && ./mvnw clean package -DskipTests

# 3. Execução em produção
java -jar -Dspring.profiles.active=prod backend/target/g-agro-1.0.0.jar

# 4. Servir front-end estático
npm install -g serve
serve -s frontend/dist -l 3000
```

> 🔑 Configure `SPRING_DATASOURCE_URL`, `JWT_SECRET`, `AWS_ACCESS_KEY` e `SENDGRID_API_KEY` no painel da AWS (Parameter Store ou Secrets Manager).

---

## 📂 Estrutura de Pastas

```
g-agro/
├── .env.example                         # 🧩 Variáveis de exemplo (sem valores sensíveis)
├── .gitignore                           # 🧹 node_modules, .env, /target ignorados
├── .github/
│   └── workflows/
│       └── ci-cd.yml                    # 🤖 Pipeline GitHub Actions
├── README.md                            # 📘 Documentação principal
├── CONTRIBUTING.md                      # 🤝 Guia de contribuição
├── LICENSE                              # ⚖️ Licença MIT
│
├── docs/                                # 📚 Documentação técnica
│   ├── plantuml/                        # 📐 Códigos-fonte PlantUML (.puml)
│   │   ├── 01_arquitetura_componentes.puml
│   │   ├── 02_diagrama_classes.puml
│   │   ├── 03_modelo_dados_der.puml
│   │   ├── 04_sequencia_login.puml
│   │   ├── 05_sequencia_safra.puml
│   │   ├── 06_casos_de_uso.puml
│   │   └── 07_deployment.puml
│   └── images/                          # 🖼️ Imagens PNG geradas pelo PlantUML
│       ├── 01_arquitetura_componentes.png
│       ├── 02_diagrama_classes.png
│       ├── 03_modelo_dados_der.png
│       ├── 04_sequencia_login.png
│       ├── 05_sequencia_safra.png
│       ├── 06_casos_de_uso.png
│       └── 07_deployment.png
│
├── frontend/                            # 📁 Aplicação React + Vite
│   ├── .env.example
│   ├── vite.config.ts
│   ├── tailwind.config.ts
│   ├── public/
│   └── src/
│       ├── components/                  # 🧱 Componentes reutilizáveis (UI, charts, maps)
│       ├── pages/                       # 📄 Dashboard, Fazendas, Safras, Insumos, Auth
│       ├── services/                    # 🔌 Chamadas HTTP (Axios + React Query)
│       ├── stores/                      # 🏪 Estado global (Zustand)
│       ├── hooks/                       # 🎣 Custom hooks
│       ├── types/                       # 📝 Tipagens TypeScript
│       └── utils/                       # 🛠️ Funções utilitárias
│
├── backend/                             # 📁 Aplicação Spring Boot
│   ├── pom.xml                          # 🛠️ Dependências Maven
│   └── src/
│       ├── main/
│       │   ├── java/br/com/gagro/
│       │   │   ├── controller/          # 🎮 Endpoints REST
│       │   │   ├── service/             # ⚙️ Regras de negócio
│       │   │   ├── repository/          # 🗄️ Repositórios JPA
│       │   │   ├── model/               # 🧬 Entidades JPA
│       │   │   ├── dto/                 # ✉️ DTOs Request/Response
│       │   │   ├── config/              # 🔧 Security, Redis, S3, Swagger
│       │   │   ├── exception/           # 💥 Exceptions customizadas
│       │   │   └── security/            # 🛡️ JWT Filter, UserDetails
│       │   └── resources/
│       │       ├── application.yml
│       │       ├── application-local.yml
│       │       ├── application-prod.yml
│       │       └── db/migration/        # 📜 Scripts Flyway (V1__init.sql...)
│       └── test/                        # 🧪 Testes unitários e integração
│
└── mobile/                              # 📱 App React Native (Expo)
    ├── app.json
    └── src/
        ├── screens/
        ├── navigation/
        └── services/                    # offline queue + AsyncStorage
```

---

## 🎥 Demonstração

> Os wireframes abaixo foram gerados com **PlantUML (Salt)** e representam as telas principais do G-Agro. Em produção, substituir pelos screenshots reais hospedados no GitHub Pages.

### 🌐 Aplicação Web

| Tela | Captura de Tela |
|:---:|:---:|
| **Dashboard Principal** | **Registro de Safra** |
| <img src="./docs/images/screenshot_dashboard.png" alt="Dashboard G-Agro" width="400px"> | <img src="./docs/images/screenshot_safra.png" alt="Registro de Safra" width="400px"> |
| **Controle de Insumos** | **Central de Alertas** |
| <img src="./docs/images/screenshot_insumos.png" alt="Controle de Insumos" width="400px"> | <img src="./docs/images/screenshot_alertas.png" alt="Central de Alertas" width="400px"> |

### 📱 Aplicativo Mobile

| Home | Alerta Climático |
|:---:|:---:|
| <img src="./docs/images/screenshot_mobile_home.png" alt="Home Mobile" width="280px"> | <img src="./docs/images/screenshot_mobile_alerta.png" alt="Alerta Mobile" width="280px"> |

### 💻 Exemplo de Saída no Terminal (API)

#### 1. Listagem de Fazendas

```bash
curl -X GET 'http://localhost:8080/api/v1/fazendas' \
     -H 'Authorization: Bearer eyJhbGciOiJIUzI1NiJ9...'
```

**Saída Esperada:**
```json
{
  "total": 2,
  "pagina": 1,
  "fazendas": [
    {
      "id": 1,
      "nome": "Fazenda São João",
      "localizacao": "Unaí, MG",
      "areaTotalHa": 850.5,
      "talhoesAtivos": 6,
      "safraAtual": "Soja 2024/2025",
      "statusGeral": "EM_ANDAMENTO"
    }
  ]
}
```

#### 2. Consulta de Alertas Climáticos

```bash
curl -X GET 'http://localhost:8080/api/v1/alertas?fazendaId=1&grauRisco=ALTO' \
     -H 'Authorization: Bearer eyJhbGciOiJIUzI1NiJ9...'
```

**Saída Esperada:**
```json
{
  "alertas": [
    {
      "id": 15,
      "tipo": "GEADA",
      "descricao": "Previsão de geada nos próximos 2 dias. Temperatura mínima: -2°C.",
      "dataHora": "2025-06-15T03:00:00",
      "grauRisco": "ALTO",
      "notificado": true
    }
  ]
}
```

---

## 🧪 Testes

### Testes Unitários e de Integração (Back-end)

```bash
cd backend
./mvnw test
```

*Ferramentas: JUnit 5, Mockito, Spring Boot Test, Testcontainers (PostgreSQL)*

### Testes Front-end

```bash
cd frontend
npm run test
npm run test:coverage
```

*Ferramentas: Vitest, React Testing Library, MSW (Mock Service Worker)*

### Testes End-to-End (E2E)

```bash
cd frontend
npm run test:e2e
```

*Ferramenta: Playwright — fluxos completos: login → cadastro de safra → geração de relatório*

---

## 🔗 Documentações Utilizadas

* 📖 **React 18:** [Documentação Oficial](https://react.dev/reference/react)
* 📖 **Vite 5:** [Guia de Configuração](https://vitejs.dev/config/)
* 📖 **Spring Boot 3.x:** [Documentação Oficial](https://docs.spring.io/spring-boot/docs/3.2.5/reference/html/)
* 📖 **Spring Security 6:** [Referência de Segurança](https://docs.spring.io/spring-security/reference/)
* 📖 **Spring Data JPA:** [Documentação JPA](https://docs.spring.io/spring-data/jpa/docs/current/reference/html/)
* 📖 **Flyway:** [Migrações de Banco](https://flywaydb.org/documentation/)
* 📖 **PlantUML:** [Guia de Diagramas](https://plantuml.com/guide)
* 📖 **React Native + Expo:** [Documentação Expo](https://docs.expo.dev/)
* 📖 **Tailwind CSS:** [Utilitários](https://tailwindcss.com/docs)
* 📖 **Conventional Commits:** [Padrão de Mensagens](https://www.conventionalcommits.org/en/v1.0.0/)

---

## 👥 Autores

| 👤 Nome | 🖼️ Foto | :octocat: GitHub | 💼 LinkedIn |
|:---:|:---:|:---:|:---:|
| **Lucas Dolabela** | <div align="center"><img src="https://github.com/Dolabelaa.png" width="70px" height="70px" style="border-radius:50%"/></div> | <div align="center"><a href="https://github.com/Dolabelaa"><img src="https://img.shields.io/badge/Dolabelaa-181717?style=for-the-badge&logo=github&logoColor=white"/></a></div> | <div align="center"><a href="https://www.linkedin.com/in/lucas-dolabela/"><img src="https://img.shields.io/badge/Lucas_Dolabela-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a></div> |

---

## 🤝 Contribuição

1. Faça um `fork` do projeto.
2. Crie uma branch: `git checkout -b feature/nova-funcionalidade`
3. Commit: `git commit -m 'feat: adiciona monitoramento de pH do solo'` *(use [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/))*
4. Push: `git push origin feature/nova-funcionalidade`
5. Abra um **Pull Request**.

> [!IMPORTANT]
> Leia o arquivo [`CONTRIBUTING.md`](./CONTRIBUTING.md) para detalhes sobre o guia de estilo e processo de code review.

---

## 🙏 Agradecimentos

* [**Engenharia de Software PUC Minas**](https://www.instagram.com/engsoftwarepucminas/) — Pelo ambiente acadêmico de excelência e incentivo à inovação tecnológica.
* [**Prof. Dr. João Paulo Aramuni**](https://github.com/joaopauloaramuni) — Pelos ensinamentos fundamentais de **Arquitetura de Software**, **Padrões de Projeto** e **Boas Práticas de Documentação**.
* [**PlantUML**](https://plantuml.com/) — Pela ferramenta gratuita e poderosa de diagramação textual.
* [**Baeldung**](https://www.baeldung.com/) — Pelos tutoriais detalhados sobre Spring Boot, Spring Security e JWT.
* [**Rocketseat**](https://rocketseat.com.br/) — Pelos conteúdos de qualidade em React e React Native.

---

## 📄 Licença

Este projeto está distribuído sob a **Licença MIT**. Consulte o arquivo [LICENSE](./LICENSE) para mais detalhes.

```
MIT License — Copyright (c) 2025 Lucas Dolabela
```

---

<div align="center">
  <sub>Desenvolvido com 🌱 por <a href="https://github.com/Dolabelaa">Lucas Dolabela</a> — PUC Minas, 2025</sub>
</div>
