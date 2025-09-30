### **Guia de Aplicação das Técnicas de Priorização (MoSCoW + $100)**

#### **1. Introdução**

Este guia descreve o processo passo a passo para priorizar o backlog de requisitos do projeto ID Jovem. O objetivo é utilizar uma abordagem combinada que aproveita a simplicidade do **MoSCoW** para uma classificação de alto nível e a granularidade da técnica dos **100 Dólares** para um refinamento orientado a valor.

Seguir este processo garantirá que o esforço de desenvolvimento esteja sempre focado nas funcionalidades mais críticas e valiosas para os usuários e para os objetivos do projeto.

#### **2. Pré-requisitos**

Antes de iniciar a sessão de priorização, os seguintes artefatos devem estar concluídos e disponíveis para todos os participantes:

-   Backlog inicial de requisitos (fruto das etapas de elicitação).
-   Documento de Visão e Escopo do projeto.
-   Personas definidas para o público-alvo do ID Jovem.

#### **3. Participantes**

A sessão de priorização deve incluir os seguintes papéis:

-   **Product Owner (PO):** Representante do negócio, com poder de decisão final sobre a prioridade.
-   **Stakeholders:** Representantes do governo e especialistas no domínio do ID Jovem para fornecer a perspectiva de negócio e do usuário.
-   **Equipe de Desenvolvimento:** Para oferecer insights sobre a complexidade técnica, esforço e possíveis dependências entre os requisitos.
-   **Facilitador (Scrum Master/Gerente de Projeto):** Para conduzir a sessão, garantir que o processo seja seguido e gerenciar o tempo.

#### **4. Processo de Priorização em Duas Fases**

O processo será conduzido em duas fases sequenciais:

##### **Fase 1: Classificação de Alto Nível com MoSCoW**

**Objetivo:** Separar rapidamente os requisitos em quatro categorias claras de prioridade.

-   **Passo 1.1:** O Facilitador apresenta cada requisito do backlog, um por um.
-   **Passo 1.2:** Para cada requisito, o grupo discute sua importância e alinhamento com os objetivos do projeto. A equipe de desenvolvimento pode esclarecer dúvidas técnicas.
-   **Passo 1.3:** O PO, com o apoio dos stakeholders, classifica o requisito em uma das quatro categorias:
    -   **Must have:** Essencial, inegociável para a entrega.
    -   **Should have:** Importante, mas não vital.
    -   **Could have:** Desejável, um "algo a mais".
    -   **Won't have:** Fora do escopo para esta entrega.
-   **Resultado da Fase 1:** Um backlog categorizado. Os itens **"Must have"** formam o escopo mínimo viável e devem ser feitos.

##### **Fase 2: Refinamento e Ranqueamento com 100 Dólares ($100)**

**Objetivo:** Priorizar os itens _dentro_ das categorias **"Should have"** e **"Could have"** para definir a ordem de implementação.

-   **Passo 2.1:** O Facilitador isola a lista de todos os requisitos classificados como **"Should have"**.
-   **Passo 2.2:** Cada participante (PO e Stakeholders) recebe 100 dólares imaginários.
-   **Passo 2.3:** Individualmente, cada participante distribui seus 100 dólares entre os requisitos da lista, alocando mais "dinheiro" para os itens que considera mais valiosos.
-   **Passo 2.4:** O Facilitador recolhe as alocações e soma o total de dólares que cada requisito recebeu.
-   **Passo 2.5:** A lista de requisitos **"Should have"** é reordenada com base na pontuação total, do maior para o menor valor.
-   **Passo 2.6 (Opcional):** O mesmo processo (passos 2.1 a 2.5) pode ser repetido para a lista de requisitos **"Could have"**, caso seja necessário um refinamento adicional.

#### **5. Resultado Final**

Ao final do processo, a equipe terá um backlog de requisitos priorizado em quatro níveis claros, pronto para ser usado no planejamento das próximas Sprints:

1.  **Must Have:** Itens essenciais (não ordenados, pois todos devem ser feitos).
2.  **Should Have:** Itens importantes, **ordenados por valor** (do maior para o menor).
3.  **Could Have:** Itens desejáveis, **ordenados por valor**.
4.  **Won't Have:** Itens que não serão desenvolvidos na entrega atual.

---

## Referências Bibliográficas

> SERRANO, Milene; SERRANO, Maurício. **Requisitos – Aula 07**. Gama, DF: Universidade de Brasília, [s.d.]. Material de aula.

> WIEGERS, Karl E. **Software Requirements**. 2. ed. Redmond, WA: Microsoft Press, 2003.

## Histórico de Versões

| Versão |    Data    |      Descrição       |                        Autor(es)                        |                       Revisor(es)                       |
| :----: | :--------: | :------------------: | :-----------------------------------------------------: | :-----------------------------------------------------: |
| `1.0`  | 28/09/2025 | Criação do guia de aplicação para o processo de priorização combinado  | [Danilo Melo](https://github.com/EngDann) |  [ Arthur Fernandes](https://github.com/arthurfernandesj)|
| `1.1`  | 29/09/2025 | Atualização do histórico de versão | [Arthur Fernandes](https://github.com/arthurfernandesj) |  [Leticia Lopes](https://github.com/leticialopes20)|
