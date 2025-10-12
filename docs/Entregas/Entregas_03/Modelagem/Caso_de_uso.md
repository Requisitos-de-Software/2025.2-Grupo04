# Casos de Uso 

## **Introdução**

Casos de uso são ferramentas essenciais na especificação de requisitos funcionais de um sistema, pois permitem descrever de forma clara e estruturada as interações entre os usuários (atores) e o software.   Cada caso de uso detalha um conjunto de passos que representam o cenário principal, bem como possíveis cenários alternativos, com o objetivo de alcançar determinada meta do ator dentro do sistema. Diferentemente de uma abordagem de implementação, os casos de uso focam no “o quê” o sistema deve fazer, e não no “como” será feito, deixando de lado detalhes sobre arquitetura, componentes de hardware ou linguagens de programação. A especificação baseada em casos de uso inclui o **diagrama de casos de uso**, a **descrição dos atores** e a própria **especificação detalhada de cada caso**, fornecendo uma visão completa das funcionalidades esperadas do sistema. <a id="TEC1" href="#RP2">(GUIA FACETADO..., 2017).</a>


## Casos de Uso

## 1) *Objetivo*

Descrever de maneira estruturada e clara as interações entre os atores e o sistema ID Jovem, contemplando tanto o fluxo principal quanto cenários alternativos. Garantir que cada ator possa alcançar seus objetivos dentro do sistema, fornecendo uma visão completa das funcionalidades esperadas e das condições associadas a cada caso de uso.

## 2) *Justificativa do Uso*

A utilização de casos de uso é eficaz por permitir especificar o que o sistema deve fazer, sem entrar em detalhes de design ou implementação, promovendo uma comunicação clara entre a equipe técnica e os stakeholders. Além disso, facilita a identificação de requisitos funcionais, fluxos alternativos, pré e pós-condições, e regras de negócio, garantindo maior consistência e alinhamento com as necessidades reais do sistema.

## **Metodologia**

Para a especificação dos casos de uso do sistema ID Jovem, adotou-se uma abordagem que busca descrever de forma completa o comportamento esperado de cada funcionalidade. Cada caso de uso é detalhado em termos de nome, breve descrição do comportamento lógico, atores que interagem com o sistema, pré-condições necessárias ao início e pós-condições esperadas ao término. Além disso, são apresentados os passos do fluxo principal, incluindo o intercâmbio de informações entre o usuário e o software e os requisitos de armazenamento associados, bem como diferentes cenários alternativos e de exceção. <a id="TEC1" href="#RP2">(VAZQUEZ; SIMÕES, 2016).</a> Sempre que aplicável, são indicadas as regras de negócio pertinentes, podendo-se fazer referência a um espaço específico destinado a elas, considerando que tais regras podem se aplicar a múltiplos casos de uso. Essa abordagem permite um registro estruturado e consistente das funcionalidades, assegurando clareza para análise, desenvolvimento e posterior validação do sistema.




# Diagrama de Casos de Uso 

## Introdução 

O diagrama de casos de uso é uma ferramenta gráfica que permite representar de forma clara quais funcionalidades de um software atendem a quais usuários ou sistemas específicos. Ele facilita a identificação de cada caso de uso como uma unidade de função dentro do software em análise, mostrando não apenas as funcionalidades, mas também os papéis que os usuários desempenham, chamados de atores, e como esses elementos se inter-relacionam <a id="TEC1" href="#RP2">(VAZQUEZ; SIMÕES, 2016)</a> . Os atores podem ser pessoas, grupos, outros sistemas ou dispositivos que interagem com o software para alcançar determinados objetivos. Cada caso de uso representa uma funcionalidade específica, normalmente nomeada com um verbo no infinitivo, e pode ser visualizado como uma elipse dentro dos limites do sistema. Conforme definem Vazquez e Simões (2016), o objetivo central deste diagrama é "descrever quem faz o quê no sistema", representando visualmente os eventos para os quais o sistema deve prover uma resposta e as entidades externas com as quais ele interage. Já os relacionamentos mostram como os atores interagem com os casos de uso ou como os próprios casos de uso se conectam entre si, por meio de linhas ou setas. Essa representação visual proporciona uma compreensão rápida e intuitiva das funcionalidades do sistema e de seus usuários, servindo como base para análise, documentação e comunicação entre a equipe de desenvolvimento e os stakeholders.

## 1) Objetivo

O objetivo do diagrama de casos de uso no contexto do aplicativo ID Jovem é representar de forma visual e estruturada todas as funcionalidades do sistema, identificando claramente os atores que interagem com ele e os objetivos que cada usuário deseja alcançar. Isso permite mapear os fluxos principais e alternativos das ações dentro do aplicativo, oferecendo uma visão abrangente das operações que o sistema deve suportar, como emissão de carteirinhas, consulta de benefícios e notificações aos usuários.

## 2) Justificativa do Uso

A utilização do diagrama de casos de uso é justificada por sua capacidade de demonstrar de maneira intuitiva e organizada as interações entre usuários e funcionalidades, sem entrar em detalhes de implementação. No caso do ID Jovem, isso facilita a comunicação entre desenvolvedores, analistas e stakeholders, assegurando que todos compreendam claramente como o sistema deve se comportar e quais serviços precisam ser disponibilizados, além de servir como base para levantamento de requisitos, planejamento de testes e documentação do software.

## Diagrama de Casos de Uso ID Jovem 


<p style="text-align: center; font-size: 10pt;">Fonte: <a href="https://github.com/GiovanaFontesS">Giovana Fontes</a></p>

---
## Legenda do Diagrama 


<p style="text-align: center; font-size: 10pt;">Fonte: <a href="https://github.com/GiovanaFontesS">Giovana Fontes</a></p>

---

### UC1 - Cadastrar Jovem Beneficiário

<p align="center"><font><strong>Tabela 1:</strong> Cadastrar Jovem Beneficiário</font><br></p>

| **UC01** | **Cadastrar Jovem Beneficiário** |
|:--|:--|
| **Descrição** | Este caso de uso descreve o processo pelo qual um jovem realiza seu cadastro no sistema ID Jovem por meio do CPF. |
| **Ator** | Jovem Beneficiário |
| **Fluxo básico** | 1. O jovem acessa o aplicativo ID Jovem.<br>2. Seleciona a opção "Fazer Cadastro".<br>3. Insere seu CPF para verificação.<br>4. O sistema valida o CPF e elegibilidade.<br>5. O jovem preenche informações pessoais necessárias.<br>6. O sistema confirma o cadastro e gera a carteira digital. |
| **Fluxos alternativos** | 1. Caso de uso "Validar Elegibilidade": O sistema verifica automaticamente se o jovem atende aos critérios do programa.<br>2. Caso de uso "Integração Gov.br": O sistema pode utilizar dados pré-existentes do Gov.br para agilizar o cadastro. |
| **Fluxo de exceção** | 1. Se o CPF for inválido ou o jovem não for elegível, o sistema informa a impossibilidade de cadastro. |
| **Pré-condições** | O jovem deve possuir CPF válido e atender aos critérios de idade (15-29 anos). |
| **Pós-condições** | O jovem é cadastrado como beneficiário e tem acesso à carteira digital ID Jovem. |
| **Data da criação** | 12/10/2025 |
| **Rastreabilidade** | [RF01](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf01), [RF15](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf15) |

<font size="3"><p style="text-align: center">Fonte: [Eduarda Domingos](https://github.com/eduardar0), 2025</p></font>

### UC2 - Consultar Benefícios Disponíveis

<p align="center"><font><strong>Tabela 2:</strong> Consultar Benefícios Disponíveis</font><br></p>

| **UC02** | **Consultar Benefícios Disponíveis** |
|:--|:--|
| **Descrição** | Este caso de uso descreve o processo pelo qual o jovem beneficiário consulta os benefícios disponíveis, como transporte gratuito e meia-entrada em eventos. |
| **Ator** | Jovem Beneficiário |
| **Fluxo básico** | 1. O jovem beneficiário acessa o aplicativo ID Jovem.<br>2. Seleciona a opção "Benefícios Disponíveis".<br>3. O sistema exibe a lista de benefícios (transporte e cultura).<br>4. O jovem seleciona um benefício para ver detalhes.<br>5. O sistema mostra informações completas sobre condições de uso. |
| **Fluxos alternativos** | 1. Caso de uso "Filtrar Benefícios": O jovem pode filtrar por tipo de benefício ou localização.<br>2. Caso de uso "Localizar Parceiros": O sistema mostra estabelecimentos que aceitam cada benefício. |
| **Fluxo de exceção** | 1. Se não houver benefícios disponíveis na região, o sistema informa sobre a indisponibilidade temporária. |
| **Pré-condições** | O jovem deve estar cadastrado e com a carteira digital ativa. |
| **Pós-condições** | O jovem beneficiário tem conhecimento dos benefícios disponíveis e como utilizá-los. |
| **Data da criação** | 12/10/2025 |
| **Rastreabilidade** | [RF04](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf04), [RF10](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf10) |

<font size="3"><p style="text-align: center">Fonte: [Eduarda Domingos](https://github.com/eduardar0), 2025</p></font>

## Referências Bibliográficas




> <a id="TEC1" href="#anchor_2">1.</a> </a> GUIA FACETADO DE TÉCNICAS DE ELICITAÇÃO DE REQUISITOS. Florianópolis: UFSC, 2017. Disponível em: <a href="https://retraining.inf.ufsc.br/guia/app/classificacoes/tecnicas-de-elicitacao-de-requisitos/entidades">https://retraining.inf.ufsc.br/guia/app/classificacoes/tecnicas-de-elicitacao-de-requisitos/entidades</a>. Acesso em: 22 set. 2025.

> <a id="TEC2" href="#anchor_2">2.</a> </a> VAZQUEZ, Carlos; SIMÕES, Guilherme. Engenharia de Requisitos: software orientado ao negócio. Rio de Janeiro: Brasport, 2016.</a>. Acesso em: 22 set. 2025.

## Bibliografia

> VAZQUEZ, Carlos; SIMÕES, Guilherme. Engenharia de Requisitos: software orientado ao negócio. Rio de Janeiro: Brasport, 2016.</a>. Acesso em: 22 set. 2025.

>
## Histórico de Versão

| Versão |    Data    |       Descrição      |                                          Autor(es)                                         |                  Revisor(es)                  |
| :----: | :--------: | :------------------: | :----------------------------------------------------------------------------------------: | :-------------------------------------------: |
|  `1.0` | 09/10/2025 | Criação do documento | [Dylan](https://github.com/dylancavalcante) | [Arthur](https://github.com/arthurfernandesj) |
|  `1.1` | 10/10/2025 | Conteúdo introdutório | [Giovana](https://github.com/GiovanaFontesS) |  [Dylan](https://github.com/dylancavalcante) |
|  `1.2` | 10/10/2025 | Mudança bibliografia | [Eduarda](https://github.com/eduardar0) |  [Dylan](https://github.com/dylancavalcante) |
|  `1.3` | 10/10/2025 | ADD US 01 e 02 | [Eduarda](https://github.com/eduardar0) |  [Dylan](https://github.com/dylancavalcante) |