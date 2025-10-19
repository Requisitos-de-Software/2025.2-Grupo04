# Introdução 

As histórias de usuário são uma forma simples e ágil de representar requisitos funcionais de um sistema, descrevendo de maneira breve o que o usuário precisa que o software faça. Segundo **Vazquez e Simões (Engenharia de Requisitos)**, elas surgiram no contexto da Extreme Programming (XP) como uma unidade de funcionalidade que demonstra o progresso do projeto por meio da entrega de código testado e integrado. Cada história de usuário deve ser compreensível para o cliente, testável pelos desenvolvedores e pequena o suficiente para ser implementada dentro de uma iteração. Atualmente, essa técnica é amplamente utilizada em métodos ágeis, como o Scrum, em que o Product Owner é responsável por elaborá-las com base nas necessidades dos usuários. O uso de histórias de usuário promove a colaboração da equipe, facilita a priorização e garante que o valor entregue seja claro, embora não seja indicado para ambientes que exigem documentação extensa e formal.


## Objetivo

O principal objetivo das histórias de usuário no contexto do ID Jovem é traduzir as necessidades dos jovens beneficiários em funcionalidades claras e testáveis, garantindo que o aplicativo seja acessível, funcional e atenda aos requisitos de inclusão digital. Através delas, o time de desenvolvimento consegue priorizar entregas que realmente impactam a experiência do usuário, assegurando que cada iteração do projeto contribua para um produto final mais eficiente e alinhado às expectativas do público.

## Justificativa de Uso

O uso de histórias de usuário no desenvolvimento do aplicativo ID Jovem se justifica por se tratar de uma abordagem ágil, que permite compreender e documentar de forma simples as necessidades reais dos usuários do sistema — jovens que buscam acesso facilitado a benefícios culturais, esportivos e de transporte. Esse formato favorece a comunicação entre a equipe de desenvolvimento e o Product Owner, garantindo que cada funcionalidade desenvolvida tenha valor prático e direto para o público-alvo. Além disso, as histórias de usuário tornam o processo mais dinâmico e colaborativo, possibilitando ajustes contínuos conforme o feedback dos usuários e a evolução do projeto.

## Metodologia 

As Histórias de Usuário foram elaboradas a partir dos requisitos funcionais, reinterpretados do ponto de vista do usuário do ID Jovem. Cada narrativa descreve de forma clara o que o aplicativo deve fazer e como contribui para o aprendizado, garantindo uma abordagem centrada no usuário e alinhada às práticas ágeis.
A elaboração de uma história de usuário segue um processo simples e objetivo, que busca transformar as necessidades dos usuários em funcionalidades claras e de valor para o sistema. Segundo **Vazquez e Simões (Engenharia de Requisitos)**, uma boa história de usuário deve responder a três perguntas essenciais: quem se beneficia, o que se quer e qual é o benefício.

- *Passo 1* – Identificar o ator **(Quem se beneficia?)**
Define-se quem é o usuário ou parte interessada que se beneficiará da funcionalidade. No caso do aplicativo ID Jovem, esse ator pode ser o jovem beneficiário, o administrador do sistema ou o atendente de suporte.

- *Passo 2* – Definir a funcionalidade **(O que se quer?)**
Descreve-se de forma simples o que o usuário deseja fazer no sistema, sem entrar em detalhes técnicos.

- *Passo 3* – Determinar o valor ou benefício **(Por quê?)**
Explica-se o motivo e o valor que essa funcionalidade traz ao usuário ou ao negócio.

- *Passo 4* – Escrever a história de usuário
Com as informações anteriores, a história é escrita de forma padronizada:
Como (papel), eu quero (ação) para (benefício).

- Passo 5 – Validar e detalhar
A história é validada com o Product Owner e a equipe, podendo ser ajustada ou subdividida se estiver muito ampla. Também são definidos os critérios de aceitação, que servem para testar se a história foi corretamente implementada.


## Tabela Padrão 

<font size="3"><p style="text-align: center">Tabela 1: Tabela de Padronização das Historia de usuário</p></font>

| **ID** | USN° |
|--------|------|
| **Rastreabilidade** | Relacionamento com o(s) requisito(s) funcional(is) correspondente(s) à história |
| **Tema** | Funcionalidade principal que a história aborda |
| **Descrição** | Breve explicação do que o usuário deseja fazer e o valor que isso traz  |
| **Critérios de Aceitação** | - Usuário consegue acessar a funcionalidade.<br>- Sistema retorna informações corretas.<br>- Funcionalidade funciona em dispositivos móveis. |
| **Prioridade Usuário** | Alta, média ou baixa |
| **Status** | Validada ou não pelo usuário |
| **Autor** | [Giovana Fontes](https://github.com/GiovanaFontesS) |

<font size="2"><p style="text-align: center">Fonte: [Giovana Fontes ](https://github.com/GiovanaFontesS)</p></font>


# **Histórias de Usuário**

## [US01](#) – Cadastro do Jovem Beneficiário

<font size="3"><p style="text-align: center">Tabela 1: US01</p></font>

| **ID** | [US01](#) |
|--------|-------|
| **Rastreabilidade** | [RF01](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf01) |
| **Tema** | Cadastro de Jovem Beneficiário |
| **Descrição** | Permitir que o sistema cadastre o Jovem Beneficiário utilizando o CPF como identificação única. |
| **Critérios de Aceitação** | - O usuário consegue inserir o CPF no sistema.<br>- O sistema valida se o CPF já está cadastrado.<br>- Cadastro é confirmado com sucesso após validação. |
| **Prioridade Usuário** | Alta |
| **Status** | Validada pelo usuário |
| **Autor** | [Giovana Fontes](https://github.com/GiovanaFontesS) |

<font size="2"><p style="text-align: center">Fonte: [Giovana Fontes ](https://github.com/GiovanaFontesS)</p></font>

## [US02](#) – Autenticação e Login via Gov.br

<font size="3"><p style="text-align: center">Tabela 2: US02</p></font>

| **ID** | [US02](#) |
|--------|------|
| **Rastreabilidade** |  [RF02](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf02) |
| **Tema** | Autenticação e Login |
| **Descrição** | Permitir que o usuário faça login no sistema utilizando sua conta Gov.br de forma segura. |
| **Critérios de Aceitação** | - Usuário consegue acessar a tela de login.<br>- Sistema autentica corretamente com a conta Gov.br.<br>- Mensagens de erro são exibidas em caso de login inválido.<br>- Usuário é redirecionado para a tela inicial após login bem-sucedido. |
| **Prioridade Usuário** | Alta |
| **Status** | Validada pelo usuário |
| **Autor** | [Giovana Fontes](https://github.com/GiovanaFontesS) |

<font size="2"><p style="text-align: center">Fonte: [Giovana Fontes ](https://github.com/GiovanaFontesS)</p></font>

## [US03](#) – Geração e Emissão da Carteira Digital ID Jovem

<font size="3"><p style="text-align: center">Tabela 3: US03</p></font>

| **ID** | [US03](#) |
|--------|------|
| **Rastreabilidade** | [RF03](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf03) |
| **Tema** | Emissão da Carteira Digital |
| **Descrição** | Permitir que o usuário gere e emita sua carteira digital ID Jovem diretamente pelo sistema. |
| **Critérios de Aceitação** | - Usuário consegue iniciar o processo de geração da carteira.<br>- Sistema valida os dados do usuário antes de emitir.<br>- Carteira digital é emitida corretamente.<br>- Usuário recebe confirmação de emissão bem-sucedida. |
| **Prioridade Usuário** | Alta |
| **Status** | Validada pelo usuário |
| **Autor** | [Giovana Fontes](https://github.com/GiovanaFontesS) |

<font size="2"><p style="text-align: center">Fonte: [Giovana Fontes ](https://github.com/GiovanaFontesS)</p></font>

## [US04](#) – Consulta de Benefícios do ID Jovem

<font size="3"><p style="text-align: center">Tabela 4: US04</p></font>

| **ID** | [US04](#) |
|--------|------|
| **Rastreabilidade** | [RF04](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf04) |
| **Tema** | Consulta de Benefícios |
| **Descrição** | Permitir que o usuário consulte seus benefícios, como transporte gratuito e meia-entrada em eventos, diretamente pelo sistema. |
| **Critérios de Aceitação** | - Usuário consegue acessar a tela de consulta de benefícios.<br>- Sistema exibe corretamente os benefícios disponíveis para o usuário.<br>- Informações são atualizadas em tempo real.<br>- Benefícios são apresentados de forma clara e organizada. |
| **Prioridade Usuário** | Alta |
| **Status** | Validada pelo usuário |
| **Autor** | [Giovana Fontes](https://github.com/GiovanaFontesS) |

<font size="2"><p style="text-align: center">Fonte: [Giovana Fontes ](https://github.com/GiovanaFontesS)</p></font>

## [US05](#) – Validação da Carteira Digital em Estabelecimentos
<font size="3"><p style="text-align: center">Tabela 5: US05</p></font>

| **ID** | [US05](#) |
|--------|------|
| **Rastreabilidade** | [RF05](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf05) |
| **Tema** | Validação da Carteira Digital |
| **Descrição** | Permitir que o sistema valide a carteira digital do usuário em estabelecimentos conveniados de forma rápida e segura. |
| **Critérios de Aceitação** | - Usuário apresenta a carteira digital para validação.<br>- Sistema confirma a autenticidade da carteira.<br>- Estabelecimento recebe confirmação de validação.<br>- Mensagens de erro são exibidas em caso de falha na validação. |
| **Prioridade Usuário** | Alta |
| **Status** | Validada pelo usuário |
| **Autor** | [Giovana Fontes](https://github.com/GiovanaFontesS) |

<font size="2"><p style="text-align: center">Fonte: [Giovana Fontes ](https://github.com/GiovanaFontesS)</p></font>


##  Referências Bibliográficas

> <a id="RP3" href="#TEC3">3.</a> VAZQUEZ, Carlos Eduardo; SIMÕES, Guilherme Siqueira; SIMÕES. *Engenharia de Requisitos: Software Orientado ao Negócio.* São Paulo , 2016. Acesso em: 19 de outubro de 2025.



##  Histórico de Versão

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
|--------|------|-----------|-----------|-------------|
| 1.0 | 19/10/2025 | Criação do Documento: Introdução, Metodologia, justificativa de uso e objetivo  | [Giovana Fontes](https://github.com/GiovanaFontesS) | [ Leticia ](https://github.com/leticialopes20) |
| 1.1 | 19/10/2025 | Historia de usuario [US01](#), [US02](#), [US03](#), [US04](#), [US05](#) | [Giovana Fontes](https://github.com/GiovanaFontesS) | [ Leticia ](https://github.com/leticialopes20) |