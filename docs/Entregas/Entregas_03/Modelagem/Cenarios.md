## Introdução
Cenários de uso são histórias detalhadas que mostram como os usuários interagem com um sistema em situações reais ou possíveis. Eles ajudam a entender *o que o usuário faz, por que faz e quais recursos precisa* para atingir seus objetivos (Barbosa et al., 2021).

No caso do **ID Jovem**, esses cenários foram elaborados com base em **requisitos funcionais não implementados**, identificados durante a análise das necessidades dos usuários, especialmente no que diz respeito à clareza das informações e à confiabilidade da comunicação.

Cada cenário é estruturado com os elementos indicados: **título**, **metas/objetivo**, **contexto**, **atores**, **recursos**, **exceções** e **episódios** (Serrano; Serrano, 2025).

O objetivo é garantir que cada cenário seja *claro, detalhado e útil*, permitindo analisar o comportamento dos usuários, suas decisões, os obstáculos que enfrentam e como o aplicativo pode apoiar melhor suas atividades.

## Metodologia

Para elaborar os cenários do app **ID Jovem**, adotamos uma **abordagem centrada no usuário**, inspirada nas técnicas de **Interação Humano-Computador (IHC)** (Barbosa et al., 2021).

A ideia foi criar **narrativas realistas e detalhadas**, capazes de mostrar como os usuários interagem com o aplicativo em diferentes situações.

### *1) Construção de cenários narrativos*

Seguimos os elementos indicados pela professora **Milene Serrano** — *título, metas/objetivo, contexto, atores, recursos, exceções e episódios* — para criar narrativas realistas e detalhadas dos usuários do aplicativo.

### *2) Planejamento e avaliação do usuário*

Registramos como os usuários **tomam decisões**, **verificam resultados** e **lidam com eventos raros ou imprevistos** (Barbosa et al., 2021).

### *3) Questionamento sistemático*

Aplicamos perguntas do tipo **“o que?”**, **“como?”** e **“por que?”** para cada elemento do cenário, seguindo a *Tabela 8.2: Perguntas para refinar cenários* do livro *Interação Humano-Computador (IHC)*, garantindo que lacunas fossem identificadas e informações importantes não fossem omitidas (Carroll et al., 1994; Barbosa et al., 2021).

Conforme solicitado pelo docente da disciplina de Requisitos de Software, cada membro da equipe ficou responsável por **desenvolver e apresentar dois cenários completos**.

Essa divisão garantiu a *participação equilibrada* e permitiu uma análise mais aprofundada de cada situação, favorecendo a compreensão coletiva dos requisitos e o desenvolvimento colaborativo da documentação.

A **Tabela 1** apresenta os membros responsáveis pelo desenvolvimento dos cenários, assim como as **datas e horários de submissão** de seus respectivos cenários no documento correspondente.

<font size="3"><p style="text-align: center">Tabela 1: Participantes</p></font>
<div align="center">
<table>
<thead>
<tr>
<th>Nome</th>
<th>Data</th>
<th>Hora</th>
</tr>
</thead>
<tbody>
<tr>
<td><a href="https://github.com/arthurfernandesj">Arthur Fernandes</a></td>
<td>00/10/2025</td>
<td>00:00</td>
</tr>
<tr>
<td><a href="https://github.com/BrenoLTeixeira">Breno Lourenço</a></td>
<td>00/10/2025</td>
<td>00:00</td>
</tr>
<tr>
<td><a href="https://github.com/dylancavalcante">Dylan Cavalcante</a></td>
<td>00/10/2025</td>
<td>00:00</td>
</tr>
<tr>
<td><a href="https://github.com/eduardar0">Eduarda Domingos</a></td>
<td>11/10/2025</td>
<td>22:00</td>
</tr>
<tr>
<td><a href="https://github.com/GiovanaFontesS">Giovana Fontes</a></td>
<td>00/10/2025</td>
<td>00:00</td>
</tr>
<tr>
<td><a href="https://github.com/leticialopes20">Letícia Lopes</a></td>
<td>11/10/2025</td>
<td>21:00</td>
</tr>
</tbody>
</table>
</div>
<font size="2"><p style="text-align: center">Fonte: <i>[Leticia Lopes](https://github.com/leticialopes20)</i> </p></font>


###  **Cenário 1: Integração com o CadÚnico para Atualização Automática de Dados**

<font size="3"><p style="text-align: center">Tabela 1: Cenário de Integração com o CadÚnico para Atualização Automática de Dados</p></font>

| **ID**         | [RF07](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf07)                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objetivo**   | Permitir que o sistema do ID Jovem atualize automaticamente as informações do usuário a partir da base de dados do CadÚnico, evitando divergências e a necessidade de atualizações manuais.                                                                                                                                                                                                                                             |
| **Contexto**   | O usuário deseja acessar o aplicativo ID Jovem, mas seus dados pessoais (como renda, endereço ou composição familiar) estão desatualizados no sistema. O aplicativo precisa buscar e sincronizar automaticamente as informações mais recentes do CadÚnico.                                                                                                                                                                              |
| **Atores**     | Usuário do aplicativo ID Jovem, Sistema ID Jovem, Base de Dados CadÚnico.                                                                                                                                                                                                                                                                                                                                                               |
| **Recursos**   | Aplicativo ID Jovem, conexão à internet, API de integração com o CadÚnico, banco de dados local do sistema.                                                                                                                                                                                                                                                                                                                             |
| **Episódios**  | 1. O usuário acessa o aplicativo ID Jovem e faz login.<br>2. O sistema verifica a data da última sincronização com o CadÚnico.<br>3. Caso a atualização esteja pendente, o sistema realiza uma consulta automática na base do CadÚnico.<br>4. As informações do usuário (como nome, CPF, NIS, endereço e renda) são atualizadas automaticamente.<br>5. O aplicativo notifica o usuário de que seus dados foram atualizados com sucesso. |
| **Restrições** | A integração depende da disponibilidade da API do CadÚnico e de autorização prévia do usuário para compartilhamento de dados.                                                                                                                                                                                                                                                                                                           |
| **Exceções**   | - Falha na conexão com o CadÚnico.<br>- Dados divergentes entre sistemas.<br>- Usuário não encontrado na base do CadÚnico.                                                                                                                                                                                                                                                                                                              |
| **Autor**      | [Letícia Lopes](https://github.com/leticialopes20)                                                                                                                                                                                                                                                                                                                                                                                                                         |


<font size="2"><p style="text-align: center">Fonte: [Letícia Lopes](https://github.com/leticialopes20)</p></font>


###  **Cenário 2: Notificações sobre Vencimento e Renovação do Benefício**

<font size="3"><p style="text-align: center">Tabela 2: Cenário de Notificações sobre Vencimento e Renovação do Benefício</p></font>

| **ID**         | [RF08](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf08)                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| -------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Objetivo**   | Garantir que o usuário receba notificações automáticas sobre o vencimento do seu benefício ID Jovem e seja orientado sobre o processo de renovação.                                                                                                                                                                                                                                                                                                                      |
| **Contexto**   | O usuário possui um benefício ativo do ID Jovem e precisa ser informado quando a validade estiver próxima do vencimento para realizar a renovação em tempo hábil.                                                                                                                                                                                                                                                                                                        |
| **Atores**     | Usuário, Sistema do ID Jovem, Servidor de Notificações.                                                                                                                                                                                                                                                                                                                                                                                                                  |
| **Recursos**   | Aplicativo ID Jovem, módulo de notificações push, conexão à internet, base de dados de validade dos benefícios.                                                                                                                                                                                                                                                                                                                                                          |
| **Episódios**  | 1. O sistema verifica diariamente os benefícios com vencimento próximo (até 30 dias).<br>2. O sistema identifica que o benefício do usuário está prestes a vencer.<br>3. O usuário recebe uma notificação push informando o prazo de validade e instruções para renovação.<br>4. O usuário acessa o app e é redirecionado à seção “Renovar Benefício”.<br>5. Após a renovação, o sistema confirma a atualização da validade e emite uma nova notificação de confirmação. |
| **Restrições** | As notificações devem ser enviadas com antecedência mínima de 15 dias antes do vencimento. O sistema deve garantir que o envio ocorra apenas para usuários com o benefício ativo.                                                                                                                                                                                                                                                                                        |
| **Exceções**   | - Falha no envio da notificação.<br>- Usuário sem conexão com a internet.<br>- Erro ao atualizar o status da renovação no sistema.                                                                                                                                                                                                                                                                                                                                       |
| **Autor**      | [Letícia Lopes](https://github.com/leticialopes20)                                                                                                                                                                                                                                                                                                                                                                                                                               |


<font size="2"><p style="text-align: center">Fonte: [Letícia Lopes](https://github.com/leticialopes20)</p></font>


### **Cenário 3: Consulta de Locais e Parceiros que Aceitam o Benefício**

<font size="3"><p style="text-align: center">Tabela 3: Cenário de Consulta de Locais e Parceiros que Aceitam o Benefício</p></font>

| **ID**         | [RF10](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf10) |
| -------------- | ------------------------------------------------------------------------------------------------------------------------- |
| **Objetivo**   | Permitir que o Jovem Beneficiário localize estabelecimentos e parceiros que aceitam os benefícios do ID Jovem.          |
| **Contexto**   | O usuário deseja utilizar seus benefícios (transporte ou meia-entrada) e precisa encontrar locais conveniados próximos a sua localização. |
| **Atores**     | Jovem Beneficiário, Sistema do ID Jovem, Base de dados de parceiros.                                                      |
| **Recursos**   | Aplicativo ID Jovem, GPS do dispositivo, conexão à internet, banco de dados atualizado de estabelecimentos parceiros.      |
| **Episódios**  | 1. O usuário acessa a seção "Locais Parceiros" no aplicativo ID Jovem.<br>2. O sistema solicita permissão de localização do usuário.<br>3. O aplicativo exibe os estabelecimentos conveniados mais próximos da localização atual.<br>4. O usuário pode filtrar os resultados por tipo de benefício (transporte ou cultura).<br>5. O sistema mostra informações detalhadas de cada parceiro: endereço, horário de funcionamento e benefícios aceitos.<br>6. O usuário seleciona um estabelecimento e obtém rotas de acesso. |
| **Restrições** | A lista de parceiros deve ser atualizada regularmente. O sistema deve funcionar offline com os dados previamente carregados. |
| **Exceções**   | - GPS desativado ou indisponível.<br>- Sem estabelecimentos parceiros na região do usuário.<br>- Base de dados desatualizada.<br>- Falta de conexão com a internet. |
| **Autor**      | [Eduarda Domingos](https://github.com/eduardar0)                                                                               |




<font size="2"><p style="text-align: center">Fonte: [Eduarda Domingos](https://github.com/eduardar0)</p></font>

### **Cenário 4: Canal de Suporte via Chat, E-mail ou Formulário de Contato**

<font size="3"><p style="text-align: center">Tabela 4: Cenário de Canal de Suporte via Chat, E-mail ou Formulário de Contato</p></font>

| **ID**         | [RF11](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf11) |
| -------------- | ------------------------------------------------------------------------------------------------------------------------- |
| **Objetivo**   | Oferecer múltiplos canais de suporte para que o Jovem Beneficiário resolva dúvidas e problemas relacionados ao ID Jovem. |
| **Contexto**   | O usuário enfrenta dificuldades no uso do aplicativo ou tem questões sobre seus benefícios e precisa de assistência. |
| **Atores**     | Jovem Beneficiário, Sistema de Suporte do ID Jovem, Atendente (humano ou virtual). |
| **Recursos**   | Aplicativo ID Jovem, módulo de chat integrado, sistema de e-mails, formulário de contato, base de conhecimento. |
| **Episódios**  | 1. O usuário acessa a seção "Ajuda" ou "Suporte" no aplicativo.<br>2. O sistema apresenta as opções de contato: chat, e-mail e formulário.<br>3. O usuário seleciona o canal preferido para suporte.<br>4. No chat: inicia conversa com atendente virtual/humano em tempo real.<br>5. Por e-mail: preenche dados e descreve o problema para envio.<br>6. Via formulário: preenche campos obrigatórios e detalha a solicitação.<br>7. O sistema registra o ticket e fornece número de protocolo para acompanhamento.<br>8. O usuário recebe resposta pelo canal escolhido dentro do prazo estabelecido. |
| **Restrições** | Resposta via chat deve ser em até 5 minutos durante horário comercial. E-mails e formulários respondidos em até 48 horas. |
| **Exceções**   | - Canal de chat indisponível fora do horário comercial.<br>- Falha no envio de e-mail/formulário.<br>- Problema técnico no sistema de suporte.<br>- Dúvida não resolvida pelo atendimento inicial. |
| **Autor**      | [Eduarda Domingos](https://github.com/eduardar0)                                                                                |









<font size="2"><p style="text-align: center">Fonte: [Eduarda Domingos](https://github.com/eduardar0)</p></font>


## Referências Bibliográficas

1. BARBOSA, Simone Diniz Junqueira et al. *Interação humano-computador e experiência do usuário.* Auto publicação, 2021.  

2. SERRANO, Milene; SERRANO, Maurício. *Requisitos – Aula 10.* UnB, 2025, p. 8. Disponível em: [https://aprender3.unb.br/pluginfile.php/3210627/mod_resource/content/1/Aula%2010.pdf](https://aprender3.unb.br/pluginfile.php/3210627/mod_resource/content/1/Aula%2010.pdf). Acesso em: 10 de outubro de 2025.



## Histórico de Versão
| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :----: | :--------: | :------------------: | :----------------------------------------------------------------------------------------: | :-------------------------------------------: |
| `1.0` | 09/10/2025 | Criação do documento | [Arthur Fernandes](https://github.com/arthurfernandesj) | [Letícia Lopes ](https://github.com/leticialopes20) |
| `1.1` | 11/10/2025 | Adição do texto da Introdução,Metodologia e Bibliografia | [Letícia Lopes](https://github.com/leticialopes20) | [Arthur Fernandes](https://github.com/arthurfernandesj) |
| `1.2` | 11/10/2025 | Adição dos cenários 1 e 2 | [Letícia Lopes](https://github.com/leticialopes20) | [Eduarda Domingos](https://github.com/eduardar0) |
| `1.3` | 11/10/2025 | Adição dos cenários 3 e 4   | [Eduarda Domingos](https://github.com/eduardar0) |[Letícia Lopes](https://github.com/leticialopes20)