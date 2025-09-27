# Análise de Documentos

## **Introdução**

A Análise de Documentos é uma técnica amplamente utilizada na elicitação de requisitos, que consiste em examinar materiais já existentes, como legislações, relatórios, manuais oficiais e documentos técnicos relacionados ao domínio do sistema. Essa prática permite identificar informações relevantes de forma estruturada, servindo como base sólida para complementar outras técnicas de elicitação. Reconhecida pela sua objetividade e riqueza de dados, a análise documental possibilita compreender o contexto do software, reduzir ambiguidades e alinhar o desenvolvimento às normas e necessidades previamente estabelecidas, sendo especialmente útil em projetos como o ID Jovem (VAZQUEZ; SIMÕES, 2016).

---

## **Técnica de Análise de Documentos**

### 1) Objetivo

* Levantar informações já disponíveis sobre o ID Jovem.
* Compreender melhor o domínio do sistema a partir de legislações, relatórios, notícias e feedbacks de usuários.

### 2) Fontes Analisadas

* Legislação e normas que regulamentam o programa ID Jovem.
* Site oficial e materiais de divulgação.
* Notícias e reportagens sobre o uso do benefício.
* Feedbacks de usuários em redes sociais e plataformas de reclamação.

### 3) Justificativa do Uso

* Técnica simples e eficaz, pois **“aproveita documentos já produzidos, permitindo identificar informações relevantes de forma objetiva e direta”** (SERRANO Milene; SERRANO Mauricio) *Requisitos – Aula 07*. Universidade de Brasília .

### 4) Benefícios Esperados

* Reduz ambiguidades e inconsistências.
* Alinha o desenvolvimento do sistema às normas já estabelecidas.
* Fornece uma base sólida para complementar outras técnicas de elicitação.
* Possibilita identificar requisitos reais a partir de documentos confiáveis.

---

## **Metodologia**

### 1) Documentos analisados

#### 1.1) Documento 1 – Site Oficial do ID Jovem

* **Fonte:** [idjovem.juventude.gov.br](https://idjovem.juventude.gov.br/)
* **Resumo:** O site oficial do ID Jovem apresenta informações completas sobre o programa, que é uma iniciativa do governo voltada para facilitar o acesso de jovens a direitos e benefícios sociais e culturais. Nele, é possível entender o que é o ID Jovem, como funciona, quais benefícios oferece e quem pode ter acesso. O portal também fornece formas de acesso, incluindo instruções passo a passo para emissão do documento digital, além de orientações de uso, garantindo que os jovens possam usufruir plenamente dos direitos oferecidos pelo programa. Dessa forma, o site funciona como um guia completo, esclarecendo dúvidas e facilitando a utilização do benefício de forma segura e prática.

<p align="center">
  <img src="assets/Elicitações/SiteIdJovem.png" alt="Descrição sobre o aplicativo Id Jovem no Site Id Jovem" width="500"/>
</p>

<p align="center">
  Fonte: Id Jovem Mobile (2025).
</p>

---

#### 1.2) Documento 2 – Aplicativo (App Store / Google Play)

* **Fonte:** Página do aplicativo nas lojas digitais ([Google Play e App Store](https://play.google.com/store/apps/details?id=com.idjovem2&hl=pt-BR)).
* **Resumo:** A descrição oficial do aplicativo na App Store, o ID Jovem permite que jovens de baixa renda emitam sua carteira digital e acessem benefícios do programa. Com o app, é possível emitir mais de uma carteira, receber alertas, consultar perguntas frequentes, acessar atendimento e permitir que estabelecimentos validem a carteira para concessão de descontos em eventos culturais, esportivos e transporte interestadual.

<p align="center">
  <img src="assets/Elicitações/AppStorePrint.png" alt="Descrição sobre o aplicativo Id Jovem na App Store" width="500"/>
</p>

<p align="center">
  Fonte: App Store (2025).
</p>

---

## **Resultados / Discussão**

A análise documental realizada no contexto do programa ID Jovem possibilitou levantar informações relevantes de forma clara e objetiva. Segundo o Guia de Técnicas de Elicitação de Requisitos da UFSC (2023), essa técnica aproveita informações previamente registradas, garantindo consistência e economia de tempo. No caso estudado, as legislações, sites oficiais e materiais digitais forneceram dados confiáveis sobre o funcionamento do sistema e seus requisitos.

Foram identificados requisitos funcionais diretamente relacionados ao uso do sistema, como a geração da carteira digital e a autenticação de usuários. Também emergiram requisitos não funcionais, ligados à segurança, acessibilidade e usabilidade, essenciais para garantir que jovens de baixa renda consigam usufruir do benefício sem barreiras técnicas.

Além disso, a técnica contribuiu para verificar a coerência entre normas legais e implementação prática, evidenciando pontos críticos como a integração entre sistemas governamentais e a necessidade de informações atualizadas. O cruzamento dessas informações reforça a importância da análise de documentos como técnica inicial e de suporte para entrevistas e observações futuras.

---

### Requisitos Identificados

| Tipo              | Requisito                                                                   |
| ----------------- | --------------------------------------------------------------------------- |
| **Funcional**     | Cadastro do usuário por meio do CPF                                         |
| **Funcional**     | Geração e emissão da carteira digital ID Jovem                              |
| **Funcional**     | Integração com bancos de dados governamentais                               |
| **Funcional**     | Autenticação e login do usuário no aplicativo                               |
| **Funcional**     | Possibilidade de emissão de mais de uma carteira digital                    |
| **Funcional**     | Exibição clara das regras de acesso e direitos garantidos                   |
| **Funcional**     | Disponibilização de perguntas frequentes e atendimento                      |
| **Funcional**     | Validação da carteira em estabelecimentos conveniados                       |
| **Não Funcional** | Usabilidade: Interface simples e acessível                                  |
| **Não Funcional** | Portabilidade: Disponibilidade em múltiplas plataformas (web, Android, iOS) |
| **Não Funcional** | Segurança: Proteção de dados pessoais (especialmente CPF)                   |
| **Não Funcional** | Confiabilidade: Informações oficiais e atualizadas                          |
| **Não Funcional** | Performance: Emissão rápida e estável da carteira digital                   |
| **Não Funcional** | Acessibilidade: Informações claras e de fácil entendimento                  |

---

## **Conclusão**

A análise documental aplicada ao programa ID Jovem demonstrou ser uma técnica eficaz para a elicitação de requisitos, permitindo levantar aspectos funcionais e não funcionais sem necessidade inicial de interação direta com usuários. Os documentos oficiais, legislações, sites e aplicativos forneceram informações consistentes que contribuem para reduzir ambiguidades e alinhar o desenvolvimento do sistema às normas previamente estabelecidas.

Assim, a técnica se mostra fundamental para fornecer uma base sólida ao processo de elicitação, podendo ser complementada por entrevistas, questionários e observações. No caso do ID Jovem, a análise de documentos revelou-se particularmente útil para identificar exigências legais e necessidades de usabilidade, garantindo que o desenvolvimento do sistema atenda tanto às diretrizes governamentais quanto às expectativas dos beneficiários.

---

## **Referências Bibliográficas**

SERRANO, Milene; SERRANO, Mauricio. Requisitos – Aula 07. Universidade de Brasília, 2016.

UNIVERSIDADE FEDERAL DE SANTA CATARINA. Técnicas de elicitação de requisitos: Análise de Documentos. Disponível em: [https://retraining.inf.ufsc.br/guia/app/classificacoes/tecnicas-de-elicitacao-de-requisitos/entidades/tecnicas-de-elicitacao-de-requisitos-analise-de-documentos](https://retraining.inf.ufsc.br/guia/app/classificacoes/tecnicas-de-elicitacao-de-requisitos/entidades/tecnicas-de-elicitacao-de-requisitos-analise-de-documentos). Acesso em: 26 set. 2025.

VAZQUEZ, Flávio; SIMÕES, Giovani. Elicitação de Requisitos no Projeto ID Jovem. 2016.

BRASIL. ID Jovem. Disponível em: [https://idjovem.juventude.gov.br](https://idjovem.juventude.gov.br). Acesso em: 26 set. 2025.

APP STORE; GOOGLE PLAY. Aplicativo ID Jovem. Disponível em: [https://apps.apple.com](https://apps.apple.com) e [https://play.google.com](https://play.google.com). Acesso em: 26 set. 2025.

---

| Versão |    Data    |       Descrição      |                                          Autor(es)                                         |                  Revisor(es)                  |
| :----: | :--------: | :------------------: | :----------------------------------------------------------------------------------------: | :-------------------------------------------: |
|  `1.0` | 25/09/2025 | Criação do documento | [Dylan](https://github.com/dylancavalcante) e [Giovana](https://github.com/GiovanaFontesS) | [Arthur](https://github.com/arthurfernandesj) |
