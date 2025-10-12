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
### Caso de Uso 1 ([RF07](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf07))
<font size="3"><p style="text-align: center">Tabela 1: Atualizar Dados via CadÚnico</p></font>

| [RF07](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf07) | **Descrição** |
| ------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Nome do Caso de Uso** | Atualizar Dados do Beneficiário via CadÚnico |
| **Rastreabilidade** | [BS09](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/), [IDJ08](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspec%C3%A7%C3%A3o/) |
| **Ator Principal** | Beneficiário do ID Jovem |
| **Atores Secundários** | Sistema CadÚnico, Sistema ID Jovem |
| **Objetivo** | Permitir que o sistema ID Jovem integre-se automaticamente com o CadÚnico para atualizar os dados do perfil do jovem. |
| **Pré-condições** | - O participante do programa deve estar autenticado no aplicativo ID Jovem.<br>- O jovem deve estar cadastrado no CadÚnico. |
| **Fluxo Principal de Eventos** | 1. O **beneficiário do ID Jovem** acessa o aplicativo.<br>2. Seleciona a opção "Atualizar meus dados".<br>3. O sistema solicita autenticação e validação no CadÚnico.<br>4. O sistema recebe os dados atualizados do CadÚnico.<br>5. As informações do **perfil do jovem** são atualizadas automaticamente no ID Jovem.<br>6. O **beneficiário** recebe confirmação da atualização. |
| **Fluxos Alternativos** | - O jovem opta por atualizar apenas dados específicos.<br>- O sistema exibe histórico de alterações feitas anteriormente via CadÚnico. |
| **Exceções** | - Falha na conexão com CadÚnico: o sistema exibe mensagem de erro e oferece opção de tentar novamente.<br>- Dados divergentes: o sistema notifica o participante e solicita validação manual.<br>- Jovem não cadastrado no CadÚnico: sistema informa a necessidade de cadastro prévio. |
| **Pós-condições** | - Os dados do perfil do jovem no ID Jovem foram atualizados com sucesso ou permanecem pendentes até a resolução de erro. |
| **Autor** | [Leticia Lopes](https://github.com/leticialopes20) |

<font size="2"><p style="text-align: center"><b>Fonte: <i> [Letícia Lopes](https://github.com/leticialopes20) </i></b></p></font>

### Caso de Uso 2 ([RF08](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf08))
<font size="3"><p style="text-align: center">Tabela 2: Notificações de Vencimento e Renovação de Benefício</p></font>

| [RF08](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf08) | **Descrição** |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Nome do Caso de Uso** | Receber Notificações de Vencimento e Renovação de Benefício |
| **Rastreabilidade** | [BS11](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/), [ST04](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Storytelling/), [IDJ11](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspecção/) |
| **Ator Principal** | Beneficiário do ID Jovem |
| **Atores Secundários** | Sistema de Notificações, Sistema ID Jovem |
| **Objetivo** | Permitir que o **participante do programa** receba notificações sobre o vencimento e a renovação do benefício ID Jovem. |
| **Pré-condições** | - O jovem deve estar autenticado no aplicativo.<br>- O benefício do participante deve ter data de vencimento registrada no sistema. |
| **Fluxo Principal de Eventos** | 1. O **beneficiário do ID Jovem** acessa o aplicativo.<br>2. O sistema verifica datas de vencimento dos benefícios cadastrados.<br>3. O sistema envia notificações ao **participante** sobre o vencimento próximo.<br>4. O sistema envia notificações quando a renovação estiver disponível.<br>5. O **beneficiário** visualiza a notificação e realiza a renovação se desejar. |
| **Fluxos Alternativos** | - O jovem escolhe receber notificações via e-mail ou SMS.<br>- O participante adia a renovação e recebe lembrete posterior. |
| **Exceções** | - Falha no envio da notificação: sistema registra tentativa e exibe alerta no aplicativo.<br>- Dados de vencimento ausentes ou incorretos: sistema solicita atualização junto ao jovem. |
| **Pós-condições** | - O **beneficiário** foi notificado sobre vencimento ou renovação do benefício. |
| **Autor** | [Leticia Lopes](https://github.com/leticialopes20) |

<font size="2"><p style="text-align: center"><b>Fonte: <i> [Letícia Lopes](https://github.com/leticialopes20) </i></b></p></font>

### Caso de Uso 3 ([RF10](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf10))
<font size="3"><p style="text-align: center">Tabela 3: Consultar Locais e Parceiros</p></font>

| [RF10](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf10) | **Descrição** |
| ------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Nome do Caso de Uso** | Consultar Locais e Parceiros |
| **Rastreabilidade** | [BS10](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/), [ST06](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Storytelling/) |
| **Ator Principal** | Jovem Beneficiário |
| **Atores Secundários** | Sistema de Localização, Sistema ID Jovem |
| **Objetivo** | Permitir que o jovem beneficiário consulte estabelecimentos e parceiros que aceitam os benefícios do ID Jovem. |
| **Pré-condições** | - O jovem deve estar cadastrado e com a carteira digital ativa.<br>- O aplicativo deve ter acesso à localização do dispositivo. |
| **Fluxo Principal de Eventos** | 1. O **jovem beneficiário** acessa o aplicativo ID Jovem.<br>2. Seleciona a opção "Locais Parceiros".<br>3. O sistema solicita permissão de localização.<br>4. O aplicativo exibe estabelecimentos conveniados próximos.<br>5. O **jovem** visualiza informações detalhadas de cada parceiro.<br>6. O sistema mostra rotas de acesso aos estabelecimentos selecionados. |
| **Fluxos Alternativos** | - O jovem pode filtrar por benefício específico (transporte ou cultura).<br>- O jovem pode buscar estabelecimentos em localização específica. |
| **Exceções** | - Se não houver parceiros na região, o sistema sugere expandir a área de busca.<br>- Se o GPS estiver desativado, o sistema funciona com busca manual por endereço. |
| **Pós-condições** | - O **jovem beneficiário** localizou estabelecimentos parceiros para utilização dos benefícios. |
| **Autor** | [Eduarda Domingos](https://github.com/eduardar0) |

<font size="2"><p style="text-align: center"><b>Fonte: <i> [Eduarda Domingos](https://github.com/eduardar0) </i></b></p></font>

### Caso de Uso 4 ([RF11](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf11))
<font size="3"><p style="text-align: center">Tabela 4: Solicitar Suporte ao Beneficiário</p></font>

| [RF11](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf11) | **Descrição** |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Nome do Caso de Uso** | Solicitar Suporte ao Beneficiário |
| **Rastreabilidade** | [ENT05](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/), [BS08](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/), [IDJ05](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspecção/) |
| **Ator Principal** | Jovem Beneficiário |
| **Atores Secundários** | Sistema de Atendimento, Sistema ID Jovem |
| **Objetivo** | Permitir que o jovem beneficiário solicite suporte através de chat, e-mail ou formulário de contato. |
| **Pré-condições** | - O jovem deve estar autenticado no aplicativo. |
| **Fluxo Principal de Eventos** | 1. O **jovem beneficiário** acessa o aplicativo ID Jovem.<br>2. Seleciona a opção "Ajuda" ou "Suporte".<br>3. O sistema apresenta opções de contato (chat, e-mail, formulário).<br>4. O **jovem** escolhe o canal preferido e descreve o problema.<br>5. O sistema registra a solicitação e gera número de protocolo.<br>6. O **jovem beneficiário** recebe confirmação e acompanha o atendimento. |
| **Fluxos Alternativos** | - Para dúvidas urgentes, o jovem é atendido imediatamente por chat.<br>- O sistema sugere soluções na base de conhecimento antes do contato. |
| **Exceções** | - Se o canal escolhido estiver indisponível, o sistema oferece alternativas.<br>- Se houver falha no envio, o sistema salva rascunho para tentativa posterior. |
| **Pós-condições** | - A solicitação de suporte foi registrada e o **jovem beneficiário** receberá resposta pelo canal escolhido. |
| **Autor** | [Eduarda Domingos](https://github.com/eduardar0) |

<font size="2"><p style="text-align: center"><b>Fonte: <i> [Eduarda Domingos](https://github.com/eduardar0) </i></b></p></font>

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
|  `1.2` | 12/10/2025 | Mudança bibliografia | [Eduarda](https://github.com/eduardar0) |  [Dylan](https://github.com/dylancavalcante) |
|  `1.3` | 12/10/2025 | Adição de uso de caso 01 e 02 | [Leticia](https://github.com/leticialopes20) | [Arthur](https://github.com/arthurfernandesj) |
|  `1.4` | 12/10/2025 | Adição de uso de caso 03 e 04 | [Leticia](https://github.com/leticialopes20) | [Arthur](https://github.com/arthurfernandesj) |
