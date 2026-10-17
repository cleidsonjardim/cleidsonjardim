<h1 align="center">Cleidson Jardim 🚀</h1>
<h3 align="center">Consultor em Arquitetura de Dados & Infraestrutura Big Data | Especialista Bare-Metal</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/cleidson-jardim-de-lima-11629782/" target="_blank">
    <img src="./linkedin.svg" alt="LinkedIn">
  </a>
  <a href="mailto:cleidson.jardim@outlook.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
</p>

---

## 👨‍💻 Visão Executiva

Especialista e Arquiteto de Dados com **mais de 18 anos de trajetória** na área de Tecnologia da Informação. Meu foco principal é o desenho, implementação e otimização de infraestruturas de dados de alta complexidade e performance. Minha atuação é o ponto de intersecção entre a **Engenharia de Dados Moderna**, o rigor do **FinOps** e a execução estratégica de **Cloud Repatriation** (Repatriamento de Nuvem).

* 🏗️ **Foco Atual:** Liderança na migração estratégica de stacks de Engenharia de Dados do Azure para infraestrutura On-Premises de alta disponibilidade, totalmente baseada em **Kubernetes (K8s) Bare-Metal** e ecossistema Open Source.
* 🎓 **Formação Acadêmica:** Graduação em Banco de Dados e Pós-Graduação em Big Data Analytics.
* 🎯 **Missão:** Gerar eficiências financeiras milionárias para o negócio sem comprometer escalabilidade, resiliência ou segurança.

---

## 🏆 Destaques de Impacto & FinOps (+R$ 4.4M de Economia)

Minha abordagem de arquitetura é orientada a valor (Value-Driven). Ao longo da minha carreira, acumulei **+R$ 4,4 Milhões em economia total** gerada diretamente por otimização de recursos e substituição de ferramentas proprietárias por soluções Open Source Enterprise-Grade.

* 📉 **Redução de R$ 2,4 Milhões (Cloud Costs):** Arquitetura e migração de pipelines legados em Azure Data Factory (ADF) e Databricks para um ambiente Open Source robusto (Apache Spark, Airflow e NiFi) rodando sobre Kubernetes Bare-Metal.
* 💰 **Economia de R$ 2,0 Milhões (Licenciamento):** Condução de projetos de migração de clusters SQL Server para PostgreSQL, eliminando o *vendor lock-in* e custos recorrentes de licenças de SGBD e Sistemas Operacionais.

---

## 🏛️ Arquitetura: Cloud Repatriation & Modernização

O diagrama abaixo ilustra o meu case principal de transformação arquitetural, movendo workloads caros de nuvem pública para uma infraestrutura Bare-Metal ultra-otimizada:

```mermaid
graph TD
    subgraph "Legacy Architecture (Cloud / Proprietary)"
        A[Azure Data Factory] --> B(Databricks / Spark)
        B --> C[(SQL Server Enterprise)]
        style A fill:#0072C6,stroke:#fff,stroke-width:2px,color:#fff
        style B fill:#FF3621,stroke:#fff,stroke-width:2px,color:#fff
        style C fill:#CC292B,stroke:#fff,stroke-width:2px,color:#fff
    end

    subgraph "Modern Architecture (On-Premises / Open Source)"
        D[Apache NiFi <br> Data Ingestion] --> E(Apache Spark on K8s <br> Processing)
        F[Apache Airflow <br> Orchestration] -.->|Triggers| D
        F -.->|Triggers| E
        E --> G[(PostgreSQL <br> Data Warehouse/Lakehouse)]
        style D fill:#729FCF,stroke:#fff,stroke-width:2px,color:#fff
        style E fill:#E25A1C,stroke:#fff,stroke-width:2px,color:#fff
        style F fill:#017CEE,stroke:#fff,stroke-width:2px,color:#fff
        style G fill:#336791,stroke:#fff,stroke-width:2px,color:#fff
    end

    C -.->|Migração de Dados <br> & Refatoração| G
    A -.->|Repatriamento <br> FinOps| D
    B -.->|K8s Bare-Metal| E

```

---

## 🛠️ Stack Tecnológica & Especialidades Detalhadas

Minhas decisões tecnológicas são pautadas na tríade: **Performance, Escalabilidade e TCO (Total Cost of Ownership)**.

### ☸️ Infraestrutura & Orquestração de Containers
* ![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white) **Kubernetes (K8s) Bare-Metal:** Desenho de clusters K8s altamente disponíveis diretamente no hardware físico (On-Premises). Eliminação de hypervisors para extrair a performance máxima de I/O e CPU necessária para workloads de Big Data.
* ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) **Containerização:** Padronização de ambientes de execução para garantir que o código funcione de forma idêntica do desenvolvimento à produção.

### ⚙️ Engenharia & Processamento de Dados
* ![Apache Spark](https://img.shields.io/badge/apache%20spark-%23E25A1C.svg?style=for-the-badge&logo=apachespark&logoColor=white) **Apache Spark:** Motor de processamento distribuído utilizado para rotinas pesadas de ETL/ELT. Experiência na configuração do Spark rodando nativamente sobre Kubernetes, otimizando alocação de executores e memória.
* ![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=Apache%20Airflow&logoColor=white) **Apache Airflow:** Orquestração centralizada de pipelines de dados. Criação de DAGs complexas, controle de dependências, SLAs e alertas corporativos. Substituição direta do Azure Data Factory.
* ![Apache NiFi](https://img.shields.io/badge/Apache%20NiFi-729FCF?style=for-the-badge&logo=Apache&logoColor=white) **Apache NiFi:** Roteamento dinâmico e ingestão de dados em tempo real. Essencial para desacoplar sistemas de origem e gerenciar backpressure em arquiteturas de alta volumetria.
* ![Databricks](https://img.shields.io/badge/databricks-%23FF3621.svg?style=for-the-badge&logo=databricks&logoColor=white) / ![Azure](https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white) **Legacy Cloud/PaaS:** Profundo conhecimento em Azure Cloud (ADF, Databricks, Synapse) para arquitetar a desconstrução e migração reversa segura (Repatriamento).

### 🗄️ Bancos de Dados, Migrações & Modelagem
* ![PostgreSQL](https://img.shields.io/badge/postgresql-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) **PostgreSQL:** Escolha primária para consolidação de dados relacionais e Data Warehouses operacionais. Especialista em Tuning avançado de queries, configuração de buffers, replicação lógica/física e otimização de I/O.
* ![MicrosoftSQLServer](https://img.shields.io/badge/Microsoft%20SQL%20Server-CC292B?style=for-the-badge&logo=microsoft%20sql%20server&logoColor=white) **SQL Server:** Administração avançada, modelagem e liderança de projetos de descontinuação (migração homogênea e heterogênea) visando economia de licenciamento.
* 📐 **Modelagem & Tuning:** Desenho de esquemas (Star/Snowflake), normalização/desnormalização estratégica e troubleshooting de performance em alto volume transacional e analítico.

---

## 📈 Atividade no GitHub

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=cleidsonjardim&show_icons=true&theme=transparent&hide_border=true&title_color=017CEE&text_color=777777" alt="Estatísticas do Cleidson" width="48%" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=cleidsonjardim&theme=transparent&hide_border=true&title_color=017CEE&text_color=777777" alt="Streak do Cleidson" width="48%" />
</p>

---
<p align="center">
  <i>"A verdadeira arquitetura não resolve apenas problemas técnicos, mas otimiza a sustentabilidade financeira do negócio."</i>
</p>
