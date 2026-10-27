<div align="center">

# ⚡ Isaque Santos
### **Software Engineer | .NET Backend, Clean Architecture, IoT & AI Systems**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/isaque-santos-348109376)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:isaquesantos001100@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Darwin00110-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Darwin00110)

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&duration=3000&pause=1000&color=512BD4&center=true&vCenter=true&width=620&lines=Desenvolvedor+Backend+.NET+%2F+C%23;Foco+em+Clean+Architecture%2C+DDD+e+Sistemas+Reais;Construindo+pontes+entre+Software%2C+IA+e+Hardware+IoT" alt="Typing SVG" />
</p>

---
</div>

## 👨‍💻 Sobre Mim

Desenvolvedor de software autodidata e apaixonado por **engenharia de backend, arquiteturas resilientes e integração de software com hardware**. Minha base é sólida no ecossistema **C# / .NET**, aplicando com rigor padrões de engenharia como **Clean Architecture, Domain-Driven Design (DDD), SOLID e Design Patterns**.

Tenho foco prático na construção de soluções completas: desde **ferramentas de produtividade para desenvolvedores (CLI Scaffolding)** até **sistemas de acesso remoto seguro, APIs financeiras transacionais e agentes autônomos de Inteligência Artificial** com integração a microcontroladores (ESP32).

- 🎯 **Foco Técnico:** Arquitetura de software de alta manutenibilidade, segurança ponta a ponta (criptografia/tokens), APIs escaláveis e automação.
- 💡 **Diferenciais:** Capacidade de conceber ferramentas do zero com alta cobertura de testes automatizados, rigor na separação de responsabilidades e mentalidade orientada a produtos de alto impacto.

---

## 🚀 Projetos em Destaque (Showcase)

> Seleção dos projetos mais representativos da minha evolução técnica, maturidade arquitetural e visão de engenharia.

### 🏗️ 01. ArchGen — Gerador de Clean Architecture em C#
> **Ferramenta CLI profissional para geração automatizada de soluções .NET em Clean Architecture — desenvolvida 100% em C# e ela mesma estruturada rigorosamente em Clean Architecture.**

[![Repo](https://img.shields.io/badge/Repositório-ArchGen-512BD4?style=flat&logo=github)](https://github.com/Darwin00110/ArchGen)
![.NET 8](https://img.shields.io/badge/.NET-8.0-512BD4?style=flat&logo=dotnet)
![C#](https://img.shields.io/badge/C%23-Clean_Architecture-239120?style=flat&logo=csharp)
![EF Core](https://img.shields.io/badge/EF_Core-SQLite-49A942?style=flat&logo=sqlite)
![Tests](https://img.shields.io/badge/Tests-86_Passed-brightgreen?style=flat&logo=xunit)

- **O que resolve:** Elimina o esforço manual repetitivo e propenso a inconsistências na criação de novas soluções C#, entregando projetos prontos para produção (modos `API` e `CONSOLE`) totalmente estruturados, com referências conectadas e compilando de primeira.
- **Engenharia & Arquitetura:**
  - **Clean Architecture Pura:** Camadas rigorosamente desacopladas (`Domain`, `Application`, `InfraStructure`, `CLI/Presentation` e `Tests`).
  - **Sistema de Templates Dinâmicos:** Clona templates padrão, manipula arquivos em tempo de execução e persiste novas definições customizadas via **EF Core com SQLite**.
  - **Auditoria & Histórico Automático:** Cada projeto gerado registra seus metadados (nome, caminho, tipo, template e status) no banco local.
  - **CLI Interativa:** Parser de argumentos robusto com tabela de ajuda rica formatada no terminal (`ArchGen --help`).
  - **Qualidade & Confiabilidade:** **86+ testes unitários** cobrindo todas as camadas utilizando `xUnit`, `Moq` e `FluentAssertions`.

---

### 🛡️ 02. Aquiles — Gestão, Acesso Remoto & Segurança de Dispositivos (PC, Mobile & IoT)
> **Plataforma de acesso remoto e gerenciamento seguro de computadores, smartphones e dispositivos IoT, garantindo soberania e controle total para o usuário.**

![Status](https://img.shields.io/badge/Status-Em_Desenvolvimento_Ativo-orange?style=flat)
![C#](https://img.shields.io/badge/C%23-.NET-512BD4?style=flat&logo=csharp)
![Security](https://img.shields.io/badge/Segurança-Criptografia_de_Ponta_a_Ponta-red?style=flat)
![Auth](https://img.shields.io/badge/Auth-Tokens_Seguros-black?style=flat&logo=jsonwebtokens)
![Real-Time](https://img.shields.io/badge/Comunicação-SignalR_%2F_MQTT-blue?style=flat)

- **O que resolve:** Centraliza o acesso e a execução de comandos remotos entre ecossistemas heterogêneos de dispositivos, sem depender de plataformas fechadas de terceiros e sem abrir mão de privacidade.
- **Engenharia & Arquitetura:**
  - **Segurança Reforçada:** Comunicação protegida por **criptografia de ponta a ponta** e autenticação rigorosa baseada em **tokens de sessão validados**, prevenindo acessos não autorizados e ataques de interceptação.
  - **Comunicação em Tempo Real:** Arquitetura bidirecional utilizando SignalR e protocolos de baixa latência para sincronização ágil de comandos e eventos.
  - **Conexão Física Hardware-Software:** Integração em desenvolvimento com microcontroladores (ESP32/Arduino) através de MQTT e comunicação serial para telemetria e acionamento de hardware.
  - **Arquitetura Modular:** Construído em C# seguindo Clean Architecture, facilitando a expansão de clientes (Desktop/Mobile) e serviços de mensageria.

---

### ⚡ 03. Hercules — Agente Autônomo de IA & Automação do Mundo Real
> **Agente de Inteligência Artificial para automação inteligente de tarefas, controle do sistema operacional, assistência de programação e orquestração de hardware robótico/assistivo.**

![Status](https://img.shields.io/badge/Status-Em_Evolução-blueviolet?style=flat)
![AI](https://img.shields.io/badge/IA-Autonomous_Agent-8A2BE2?style=flat&logo=openai)
![OS Automation](https://img.shields.io/badge/SO-File_Management_%26_Automation-2496ED?style=flat)
![IoT Bridge](https://img.shields.io/badge/Hardware-ESP32--C3_Bridge-E7352C?style=flat&logo=espressif)
![Business](https://img.shields.io/badge/Roadmap-Freemium_%2F_SaaS-success?style=flat)

- **Capacidades do Agente:**
  - **Automação Completa de SO:** Operações autônomas no sistema de arquivos (criar, ler, editar e deletar arquivos e pastas), agendamento de alarmes/rotinas e disparo de fluxos automatizados.
  - **Assistente Avançado de Desenvolvimento:** Auxílio direto em rotinas de programação, análise de código, automação de scripts e suporte a projetos de engenharia.
  - **Operação sem Limite de Tokens na Base:** Arquitetura pensada para eliminar gargalos e limites artificiais de tokens no uso cotidiano das versões iniciais.
- **Ponte com Hardware ("O Braço de Aquiles"):**
  - O Hercules atua como o núcleo inteligente que fará interface direta com o **"Braço de Aquiles"**: projeto futuro de uma **prótese biomecânica recarregável**, equipada com microcontrolador **ESP32-C3** e baterias de Lítio, demonstrando a convergência real entre software de IA e robótica assistiva.
- **Visão de Produto & Negócios:**
  - Modelo com roadmap estratégico desenhado para evolução SaaS comercial: planos mensais e anuais nas versões avançadas para gestão corporativa de dispositivos e automações em larga escala.

---

### 🏦 04. MidasAPI — API Financeira Bancária Transacional
> **Simulação realista das operações de um core banking moderno com alta consistência de dados.**

[![Repo](https://img.shields.io/badge/Repositório-MidasAPI-512BD4?style=flat&logo=github)](https://github.com/Darwin00110/MidasAPI)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat&logo=dotnet)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker)

- **Destaques de Engenharia:**
  - Clean Architecture aliada ao Domain-Driven Design (DDD).
  - Gestão de transferências bancárias (PIX, TED, DOC) com transações atômicas de banco de dados e **rollback automático** em caso de inconsistências.
  - Controle de acesso granular via JWT com separação de perfis (Admin / User).
  - Regras de negócio sofisticadas inspiradas em arquiteturas bancárias reais (cálculo de limites e simulação de crédito).
  - Testes unitários com `xUnit` e `Moq`, containerizado com `Docker`.

---

### 🔐 05. API Access Manager — Identity & Access Management (IAM)
> **Solução de autenticação, autorização granular e gestão de acessos corporativos.**

[![Repo](https://img.shields.io/badge/Repositório-API_AccessManager-512BD4?style=flat&logo=github)](https://github.com/Darwin00110/API-AccessManager)
[![Deploy](https://img.shields.io/badge/Deploy-Render-46E3B7?style=flat&logo=render)](https://github.com/Darwin00110/API-AccessManager)

- **Destaques de Engenharia:**
  - Arquitetura limpa com ASP.NET Core, EF Core e SQLite.
  - Autenticação e autorização via JWT com gestão de Roles e políticas de segurança.
  - Tratamento centralizado de exceções (`Custom Exception Middleware`) e uso extensivo de DTOs para validação.
  - Projeto colocado em produção com deploy no Render.

---

## 🛠️ Stack Tecnológica & Competências

| Área | Tecnologias & Conceitos |
| :--- | :--- |
| **Linguagens & Core** | C# (.NET 8 / Modern .NET), SQL, Python, C/C++ básico |
| **Backend & APIs** | ASP.NET Core, Web APIs RESTful, Entity Framework Core, SignalR |
| **Padrões & Arquitetura** | Clean Architecture, Domain-Driven Design (DDD), SOLID, Repository Pattern, Injeção de Dependência |
| **Segurança & Resiliência** | Criptografia, Autenticação JWT, Gestão de Tokens, Middleware de Exceção, Transações com Rollback |
| **Bancos de Dados** | MySQL, SQLite, InMemory |
| **Testes de Software** | Testes Unitários e de Integração, xUnit, Moq, FluentAssertions |
| **Hardware, IoT & IA** | ESP32-C3, Arduino, Protocolos MQTT / Serial, Agentes de IA Autônomos |
| **DevOps & Ferramentas** | Docker, Git, GitHub Actions, Terminal / CLI Scaffolding, Visual Studio, VS Code |

---

## 📊 Estatísticas & Atividade no GitHub

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Darwin00110&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="165" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Darwin00110&layout=compact&theme=tokyonight&hide_border=true" height="165" alt="Top Languages" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Darwin00110&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</div>

---

## 📬 Contato & Conexões

Estou disponível para oportunidades como **Desenvolvedor Backend .NET / C#**, projetos desafiadores e parcerias em tecnologia. Vamos conversar!

<p align="center">
  <a href="https://linkedin.com/in/isaque-santos-348109376" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Conectar-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  &nbsp;&nbsp;
  <a href="mailto:isaquesantos001100@gmail.com">
    <img src="https://img.shields.io/badge/Email-Enviar_Mensagem-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>
