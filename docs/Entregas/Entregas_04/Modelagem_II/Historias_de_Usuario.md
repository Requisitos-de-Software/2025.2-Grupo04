## Introdução 

As histórias de usuário são uma forma simples e ágil de representar requisitos funcionais de um sistema, descrevendo de maneira breve o que o usuário precisa que o software faça. Segundo **Vazquez e Simões (Engenharia de Requisitos)**, elas surgiram no contexto da Extreme Programming (XP) como uma unidade de funcionalidade que demonstra o progresso do projeto por meio da entrega de código testado e integrado. Cada história de usuário deve ser compreensível para o cliente, testável pelos desenvolvedores e pequena o suficiente para ser implementada dentro de uma iteração. Atualmente, essa técnica é amplamente utilizada em métodos ágeis, como o Scrum, em que o Product Owner é responsável por elaborá-las com base nas necessidades dos usuários. O uso de histórias de usuário promove a colaboração da equipe, facilita a priorização e garante que o valor entregue seja claro, embora não seja indicado para ambientes que exigem documentação extensa e formal.


### Objetivo

O principal objetivo das histórias de usuário no contexto do ID Jovem é traduzir as necessidades dos jovens beneficiários em funcionalidades claras e testáveis, garantindo que o aplicativo seja acessível, funcional e atenda aos requisitos de inclusão digital. Através delas, o time de desenvolvimento consegue priorizar entregas que realmente impactam a experiência do usuário, assegurando que cada iteração do projeto contribua para um produto final mais eficiente e alinhado às expectativas do público.

### Justificativa de Uso

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

### Participantes


<font size="3"><p style="text-align: center">Tabela 1: Participantes</p></font>

<div align="center">

<table>
  <thead>
    <tr>
      <th align="center">Nome</th>
      <th align="center">Histórias</th>
      <th align="center">Data</th>
      <th align="center">Hora</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center"><a href="https://github.com/arthurfernandesj">Arthur Fernandes</a></td>
      <td align="center"><a href="#h10">US10</a>, <a href="#h11">US11</a></td>
      <td align="center">00/10/2025</td>
      <td align="center">00:00</td>
    </tr>
    <tr>
      <td align="center"><a href="https://github.com/BrenoLTeixeira">Breno Lourenço</a></td>
      <td align="center"><a href="#h09">US09</a>, <a href="#h13">US13</a></td>
      <td align="center">00/10/2025</td>
      <td align="center">00:00</td>
    </tr>
    <tr>
      <td align="center"><a href="https://github.com/dylancavalcante">Dylan Cavalcante</a></td>
      <td align="center"><a href="#h05">US05</a>, <a href="#h06">US06</a>, <a href="#h14">US14</a></td>
      <td align="center">19/10/2025</td>
      <td align="center">19:08</td>
    </tr>
    <tr>
      <td align="center"><a href="https://github.com/eduardar0">Eduarda Domingos</a></td>
      <td align="center"><a href="#h03">US03</a>, <a href="#h04">US04</a></td>
      <td align="center">20/10/2025</td>
      <td align="center">16:30</td>
    </tr>
    <tr>
      <td align="center"><a href="https://github.com/GiovanaFontesS">Giovana Fontes</a></td>
      <td align="center"><a href="#h07">US07</a>, <a href="#h08">US08</a></td>
      <td align="center">20/10/2025</td>
      <td align="center">07:23</td>
    </tr>
    <tr>
      <td align="center"><a href="https://github.com/leticialopes20">Letícia Lopes</a></td>
      <td align="center"><a href="#h01">US01</a>, <a href="#h02">US02</a>, <a href="#h12">US12</a></td>
      <td align="center">20/10/2025</td>
      <td align="center">00:30</td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fontes: <i>[Letícia Lopes](https://github.com/leticialopes20)e [Dylan Cavalcante](https://github.com/dylancavalcante), 2025</i> </p></font>



## Sumário

- [H01 – Integração com o CadÚnico  (RF07)](#h01)
- [H02 – Emitir notificações sobre vencimento, renovação do benefício (RF08)](#h02)
- [H03 – Disponibilizar informações sobre locais e parceiros que aceitam o benefício (RF10)](#h03)
- [H04 – Fornecer canal de suporte via chat, e-mail ou formulário de contato (RF11)](#h04)
- [H05 – Permitir que o Jovem Beneficiário visualize o histórico de utilização dos benefícios (RF12)](#h05)
- [H06 – Seção de "Vantagens e Parcerias" com novidades, divulgação sobre o programa e ofertas exclusivas (RF13)](#h06)
- [H07 – Permitir compartilhar a carteirinha em PDF ou imagem (RF17)](#h07)
- [H08 – Fornecer informações sobre pendências ou erros relacionados aos benefícios do usuário (RF18)](#h08)
- [H09 – Permitir que os usuários atualizem seu cadastro e definam preferências pessoais (RF19)](#h09)
- [H10 – Fornecer alertas sobre possíveis irregularidades no uso dos benefícios (RF20)](#h10)
- [H11 – Possuir um mapa interativo para visualizar geograficamente parceiros e eventos (RF21)](#h11)
- [H12 – Apresentar uma agenda integrada de eventos com filtros de busca (RF22)](#h12)
- [H13 – Fornecer um canal para denúncia ou feedback sobre estabelecimentos que recusam o benefício (RF23)](#h13)
- [H14 –  Permitir que o usuário favorite eventos e estabelecimentos para consulta rápida (RF24)](#h14)

---

## Tabela Padrão 

A tabela abaixo será utilizada como modelo para a elaboração das histórias de usuário do projeto. Ela padroniza os principais elementos necessários, como a descrição da necessidade, critérios de aceitação, prioridade, status de validação, entre outros. O objetivo é garantir consistência, rastreabilidade e clareza em todas as histórias documentadas.

<font size="3"><p style="text-align: center">Tabela 2: Tabela de Padronização das Historia de usuário</p></font>

| **ID** | USN° |
|--------|------|
| **Rastreabilidade** | Relacionamento com o(s) requisito(s) funcional(is) correspondente(s) à história |
| **Tema** | Funcionalidade principal que a história aborda |
| **Descrição** | Breve explicação do que o usuário deseja fazer e o valor que isso traz  |
| **Critérios de Aceitação** | - Usuário consegue acessar a funcionalidade.<br>- Sistema retorna informações corretas.<br>- Funcionalidade funciona em dispositivos móveis. |
| **Prioridade Usuário** | Alta, média ou baixa |
| **Status** | Validada ou não pelo usuário |
| **Autor** | Autorx |

<font size="2"><p style="text-align: center">Fonte: [Giovana Fontes ](https://github.com/GiovanaFontesS)</p></font>


## **Histórias de Usuário**

### <a name="h01"></a> **História 01: Integração com o CadÚnico para Atualização automática de Dados**

<font size="3"><p style="text-align: center">Tabela 3: História de Integração com o CadÚnico para Atualização Automática de Dados</p></font>

| **ID** | US01 |
|--------|-------|
| **Rastreabilidade** | [RF07](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf07) ([BS09](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs09), [IDJ08](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspecção/)) |
| **Tema** | Integração do aplicativo com o CadÚnico |
| **Descrição** | Eu, como Jovem Beneficiário, desejo que meus dados pessoais e cadastrais sejam atualizados automaticamente por meio da integração do aplicativo com o CadÚnico, para garantir que minhas informações estejam sempre corretas e evitar bloqueios ou inconsistências no benefício. |
| **Critérios de Aceitação** | - O sistema deve se conectar automaticamente à base de dados do CadÚnico. <br>- As atualizações devem ocorrer periodicamente, sem necessidade de ação manual do usuário.<br>- O usuário deve ser notificado quando seus dados forem atualizados. <br>- Em caso de falha na atualização, o sistema deve informar o motivo e sugerir solução. |
| **Prioridade Usuário** | Alta|
| **Status** | Aguardando validação |
| **Autor** | [Letícia Lopes](https://github.com/leticialopes20) |

<font size="2"><p style="text-align: center">Fonte: [Letícia Lopes](https://github.com/leticialopes20)</p></font>

### <a name="h02"></a> **História 02: Emitir notificações sobre vencimento e renovação do benefício** 

<font size="3"><p style="text-align: center">Tabela 4: História de Emissão de notificações sobre vencimento e renovação de benefícios</p></font>

| **ID** | US02 |
|--------|-------|
| **Rastreabilidade** | [RF08](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf08) ([BS11](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/), [ST04](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Storytelling/), [IDJ11](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspecção/), [ENT13](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/))|
| **Tema** | Emissão de notificações automáticas de renovação do benefício |
| **Descrição** | Eu, como Jovem Beneficiário, desejo receber notificações sobre o vencimento e o prazo de renovação do meu benefício, para que eu possa manter o cadastro ativo e não perca o acesso aos direitos oferecidos pelo programa. |
| **Critérios de Aceitação** | - O sistema deve emitir notificações automáticas 30, 15 e 5 dias antes do vencimento do benefício. <br>- As notificações devem estar disponíveis no aplicativo e opcionalmente por e-mail ou push notification. <br>- A mensagem deve conter o link ou instrução para realizar a renovação. <br>- O sistema deve confirmar quando a renovação for concluída com sucesso. |
| **Prioridade Usuário** |Alta|
| **Status** | Aguardando validação |
| **Autor** | [Letícia Lopes](https://github.com/leticialopes20) |

<font size="2"><p style="text-align: center">Fonte: [Letícia Lopes](https://github.com/leticialopes20)</p></font>

### <a name="h03"></a> **História 03: Disponibilizar informações sobre locais e parceiros que aceitam o benefício**

<font size="3"><p style="text-align: center">Tabela 5: História de disponibilização de informações sobre locais e parceiros que aceitam o benefício </p></font>

| **ID** | US03 |
|--------|-------|
| **Rastreabilidade** | [RF10](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf10) ([ENT05](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/), [BS08](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/)) |
| **Tema** | Consulta de Parceiros |
| **Descrição** | Como jovem beneficiário, eu quero consultar os locais e parceiros que aceitam o ID Jovem, para saber onde posso utilizar meus benefícios de forma prática e planejada.  |
| **Critérios de Aceitação** | -Usuário consegue acessar a lista de parceiros <br>- Sistema exibe informações completas dos estabelecimentos (nome, endereço, horário)<br> - Funcionalidade funciona em dispositivos móveis<br>- Busca por localização ou categoria disponível<br>- Informações atualizadas e precisas|
| **Prioridade Usuário** |Média  |
| **Status** | Aguardadando validação |
| **Autor** | [Eduarda](https://github.com/eduardar0) |

<font size="2"><p style="text-align: center">Fonte:[Eduarda](https://github.com/eduardar0)</p></font>

### <a name="h04"></a> **História 04: Fornecer canal de suporte via chat, e-mail ou formulário de contato**

<font size="3"><p style="text-align: center">Tabela 6: História de fornecimento de canal de suporte via chat, e-mail ou formulário de contato</p></font>

| **ID** | US04 |
|--------|-------|
| **Rastreabilidade** | [RF11](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf11) |
| **Tema** | 	Canal de Suporte |
| **Descrição** | Como usuário do ID Jovem, eu quero ter acesso a um canal de suporte eficiente, para resolver minhas dúvidas e problemas de forma rápida e satisfatória.  |
| **Critérios de Aceitação** |- Usuário consegue acessar o canal de suporte <br>- Múltiplas opções disponíveis (chat, e-mail, formulário)<br>- Sistema fornece confirmação de recebimento<br>- Tempo de resposta dentro do esperado<br>- Funcionalidade funciona em dispositivos móveis<br>- Histórico de atendimento disponível  |
| **Prioridade Usuário** | Alta  |
| **Status** | Aguardando Validação |
| **Autor** | [Eduarda](https://github.com/eduardar0) |

<font size="2"><p style="text-align: center">Fonte: [Eduarda](https://github.com/eduardar0)</p></font>

### <a name="h05"></a> **História 05: Permitir que o Jovem Beneficiário visualize o histórico de utilização dos benefícios** 

<font size="3"><p style="text-align: center">Tabela 7: História de permissão de que o Jovem Beneficiário visualize o histórico de utilização dos benefícios</p></font>

| **ID** | US05|
|--------|-------|
| **Rastreabilidade** | [RF12](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf12) |
| **Tema** | Permitir que o Jovem Beneficiário visualize o histórico de utilização dos benefícios  |
| **Descrição** | Eu, como Jovem Beneficiário, desejo visualizar um histórico de onde e quando utilizei meus benefícios (como viagens interestaduais e meia-entrada), para poder acompanhar meu uso e ter um registro das minhas atividades. |
| **Critérios de Aceitação** | - O histórico deve exibir uma lista cronológica das utilizações.<br>- Cada item da lista deve detalhar o tipo de benefício usado (ex: Meia-entrada, Vaga gratuita em transporte). <br>- Cada item deve registrar a data e, se possível, a empresa ou evento onde foi utilizado. <br>- O histórico deve ser de fácil acesso a partir do menu principal ou do perfil do jovem beneficiário. |
| **Prioridade Usuário** | média |
| **Status** | Aguardando validação |
| **Autor** | [Dylan Cavalcante](https://github.com/dylancavalcante) |

<font size="2"><p style="text-align: center">Fonte: [Dylan Cavalcante](https://github.com/dylancavalcante)</p></font>

### <a name="h06"></a> **História 06: Seção de "Vantagens e Parcerias" com novidades, divulgação sobre o programa e ofertas exclusivas** 

<font size="3"><p style="text-align: center">Tabela 8: História de visualização da seção de "Vantagens e Parcerias" com novidades, divulgação sobre o programa e ofertas exclusivas</p></font>

| **ID** | US06 |
|--------|-------|
| **Rastreabilidade** | [RF13](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf13) |
| **Tema** | Seção de "Vantagens e Parcerias" com novidades, divulgação sobre o programa e ofertas exclusivas |
| **Descrição** | Eu, como Jovem Beneficiário, desejo acessar uma seção de "Vantagens e Parcerias" para descobrir novidades sobre o programa, cursos profissionalizantes, e ofertas exclusivas de parceiros. |
| **Critérios de Aceitação** | - A seção deve ser claramente visível no menu principal do aplicativo. <br>- O conteúdo deve ser dividido em categorias (ex: 'Novidades do Programa', 'Cursos e Capacitação', 'Ofertas de Parceiros'). <br>- O conteúdo deve ser atualizado regularmente. <br>- As ofertas e notícias devem ser relevantes para o público do ID Jovem. |
| **Prioridade Usuário** | média|
| **Status** | Aguardando validação |
| **Autor** | [Dylan Cavalcante](https://github.com/dylancavalcante) |

<font size="2"><p style="text-align: center">Fonte: [Dylan Cavalcante](https://github.com/dylancavalcante)</p></font>

### <a name="h07"></a> **História 07: Permitir compartilhar a carteirinha em PDF ou imagem**

<font size="3"><p style="text-align: center">Tabela 9: História de permissão de compartilhamento de carteirinha em PDF ou imagem</p></font>

| **ID** | US07 |
|--------|------------|
| **Rastreabilidade** | [RF17](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf17) |
| **Tema** | Compartilhamento da carteirinha digital |
| **Descrição** | Eu, como Jovem Beneficiário, desejo compartilhar minha carteirinha digital em formato PDF ou imagem para apresentá-la facilmente em locais que exigem comprovação do benefício. |
| **Critérios de Aceitação** | - O aplicativo deve permitir o download da carteirinha em formato PDF e imagem (JPEG ou PNG). <br> - O arquivo gerado deve conter todas as informações válidas do beneficiário. <br> - O compartilhamento deve ser possível por aplicativos de mensagem e e-mail. <br> - O processo de compartilhamento deve ocorrer em até 5 segundos após a solicitação. |
| **Prioridade Usuário** | Alta |
| **Status** | Aguardando validação |
| **Autor** | [Giovana Fontes](https://github.com/GiovanaFontesS) |

<font size="2"><p style="text-align: center">Fonte: [Giovana Fontes](https://github.com/GiovanaFontesS)</p></font>


### <a name="h08"></a> **História 08: Fornecer informações sobre pendências ou erros relacionados aos benefícios do jovem beneficiário**

<font size="3"><p style="text-align: center">Tabela 10: História de fornecimento de informações sobre pendências ou erros relacionados aos benefícios do jovem beneficiário</p></font>

| **ID** | US08 |
|--------|------------|
| **Rastreabilidade** | [RF18](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf18)  |
| **Tema** | Exibição de pendências e erros nos benefícios |
| **Descrição** | Eu, como Jovem Beneficiário, desejo visualizar informações sobre pendências ou erros relacionados aos meus benefícios, para compreender o motivo de possíveis bloqueios ou falhas na emissão da carteirinha. |
| **Critérios de Aceitação** | - O aplicativo deve exibir mensagens claras quando houver pendências ou erros nos dados do beneficiário. <br> - As mensagens devem conter instruções sobre como resolver o problema (ex: atualizar cadastro, verificar documentação). <br> - O sistema deve diferenciar visualmente os tipos de erro (pendência documental, erro no sistema, dados inválidos etc.). <br> - As notificações devem ser acessíveis na tela principal do usuário. |
| **Prioridade Usuário** | Alta |
| **Status** | Aguardando validação |
| **Autor** | [Giovana Fontes](https://github.com/GiovanaFontesS) |

<font size="2"><p style="text-align: center">Fonte: [Giovana Fontes](https://github.com/GiovanaFontesS)</p></font>


### <a name="h09"></a> **História 09: Permitir que o jovem beneficiário atualize seu cadastro e defina preferências pessoais** 

<font size="3"><p style="text-align: center">Tabela 11:História de permissão de que o jovem beneficiário atualize seu cadastro e defina preferências pessoais</p></font>

| **ID** | US09 |
|--------|-------|
| **Rastreabilidade** | [RF19](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf19) |
| **Tema** |  |
| **Descrição** |  |
| **Critérios de Aceitação** |  |
| **Prioridade Usuário** |  |
| **Status** |  |
| **Autor** | [Seu nome](https://github.com/seu-usuario) |

<font size="2"><p style="text-align: center">Fonte: [Seu nome ](https://github.com/seu-usuario)</p></font>

### <a name="h10"></a> **História 10: Fornecer alertas sobre possíveis irregularidades no uso dos benefícios** 

<font size="3"><p style="text-align: center">Tabela 12: História de fornecimento de alertas sobre possíveis irregularidades no uso dos benefícios</p></font>

| **ID** | US10 |
|--------|-------|
| **Rastreabilidade** | [RF20](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf20) |
| **Tema** |  |
| **Descrição** |  |
| **Critérios de Aceitação** |  |
| **Prioridade Usuário** |  |
| **Status** |  |
| **Autor** | [Seu nome](https://github.com/seu-usuario) |

<font size="2"><p style="text-align: center">Fonte: [Seu nome ](https://github.com/seu-usuario)</p></font>

### <a name="h11"></a> **História 11: Possuir um mapa interativo para visualizar geograficamente parceiros e eventos**

<font size="3"><p style="text-align: center">Tabela 13: História de visualização de parceiros e eventos geograficamente por mapa interativo</p></font>

| **ID** | US11 |
|--------|-------|
| **Rastreabilidade** | [RF21](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf21) |
| **Tema** |  |
| **Descrição** |  |
| **Critérios de Aceitação** |  |
| **Prioridade Usuário** |  |
| **Status** |  |
| **Autor** | [Seu nome](https://github.com/seu-usuario) |

<font size="2"><p style="text-align: center">Fonte: [Seu nome ](https://github.com/seu-usuario)</p></font>

### <a name="h12"></a> **História 12: Apresentar uma agenda integrada de eventos com filtros de busca** 

<font size="3"><p style="text-align: center">Tabela 14: História de apresentação de uma agenda integrada de eventos com filtros de busca</p></font>

| **ID** | US12|
|--------|-------|
| **Rastreabilidade** | [RF22](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf22) |
| **Tema** | Agenda integrada de eventos culturais e sociais|
| **Descrição** | Eu, como Jovem Beneficiário, desejo acessar uma agenda de eventos integrados ao aplicativo, com possibilidade de filtrar por data, local e tipo de evento, para planejar melhor minha participação em atividades culturais, esportivas e educacionais.|
| **Critérios de Aceitação** | - A agenda deve listar eventos culturais, esportivos e educacionais disponíveis aos beneficiários do programa.<br>- O usuário deve conseguir filtrar eventos por data, cidade e categoria. <br>- Cada evento deve exibir informações detalhadas (nome, local, horário, parceiro envolvido e se há meia-entrada ou gratuidade). <br>- Deve haver opção para adicionar eventos à agenda pessoal ou marcar como favorito. |
| **Prioridade Usuário** | Média |
| **Status** | Aguardando validação |
| **Autor** | [Letícia Lopes](https://github.com/leticialopes20) |

<font size="2"><p style="text-align: center">Fonte: [Letícia Lopes](https://github.com/leticialopes20)</p></font>

### <a name="h13"></a> **História 13: Fornecer um canal para denúncia ou feedback sobre estabelecimentos que recusam o benefício**

<font size="3"><p style="text-align: center">Tabela 15: História de fornecimento de canal para denúncia ou feedback sobre estabelecimentos que recusam o benefício</p></font>

| **ID** | US13 |
|--------|-------|
| **Rastreabilidade** | [RF23](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf23) |
| **Tema** |  |
| **Descrição** |  |
| **Critérios de Aceitação** |  |
| **Prioridade Usuário** |  |
| **Status** |  |
| **Autor** | [Seu nome](https://github.com/seu-usuario) |

<font size="2"><p style="text-align: center">Fonte: [Seu nome ](https://github.com/seu-usuario)</p></font>

### <a name="h14"></a> **História 14: Permitir que o jovem beneficiário favorite eventos e estabelecimentos para consulta rápida** 

<font size="3"><p style="text-align: center">Tabela 16: História de permissão de que o jovem beneficiário favorite eventos e estabelecimentos para consulta rápida </p></font>

| **ID** | US14 |
|--------|-------|
| **Rastreabilidade** | [RF24](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf24) |
| **Tema** | Permitir que o jovem beneficiário favorite eventos e estabelecimentos para consulta rápida  |
| **Descrição** | Eu, como Jovem Beneficiário, desejo salvar (favoritar) eventos e estabelecimentos parceiros do meu interesse para poder consultá-los rapidamente no futuro em uma lista dedicada. |
| **Critérios de Aceitação** | - Deve haver um botão ou ícone (ex: estrela, coração) visível na página de detalhes de cada evento/estabelecimento para favoritá-lo. <br>- Deve existir uma seção "Meus Favoritos" no aplicativo, acessível pelo menu ou perfil do jovem beneficiário. <br>- Ao clicar no botão de favoritar, o item deve ser adicionado à lista "Meus Favoritos". <br>- O jovem beneficiário deve poder remover um item da lista de favoritos a qualquer momento. |
| **Prioridade Usuário** | baixa |
| **Status** | Aguardando validação |
| **Autor** | [Dylan Cavalcante](https://github.com/dylancavalcante) |

<font size="2"><p style="text-align: center">Fonte: [Dylan Cavalcante](https://github.com/dylancavalcante)</p></font>

##  Referências Bibliográficas

> <a id="RP3" href="#TEC3">1.</a> VAZQUEZ, Carlos Eduardo; SIMÕES, Guilherme Siqueira; SIMÕES. *Engenharia de Requisitos: Software Orientado ao Negócio.* São Paulo , 2016. Acesso em: 19 de outubro de 2025.



##  Histórico de Versão

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
|--------|------|-----------|-----------|-------------|
| 1.0 | 19/10/2025 | Criação do Documento: Introdução, Metodologia, justificativa de uso e objetivo  | [Giovana Fontes](https://github.com/GiovanaFontesS) | [ Letícia Lopes ](https://github.com/leticialopes20) |
| 1.1 | 19/10/2025 | Adição das Historias de usuario [US05](#h05), [US06](#h06), [US14](#h14) | [Dylan Cavalcante](https://github.com/dylancavalcante) | [ Letícia Lopes](https://github.com/leticialopes20) |
| 1.2 | 20/10/2025 | Adição das Historias de usuario [US07](#h07) e [US08](#h08) | [Giovana Fontes](https://github.com/GiovanaFontesS) | [ Letícia Lopes](https://github.com/leticialopes20) |  
| 1.3 | 20/10/2025 |Adição das Historias de usuario [US01](#h01), [US02](#h02), [US12](#h12), refatoração do documento/edição de  hiperlinks| [ Letícia Lopes](https://github.com/leticialopes20)| [Dylan Cavalcante](https://github.com/dylancavalcante) |  
| 1.4 | 20/10/2025 |Adição das Historias de usuario [US03](#h03), [US04](#h04)|[Eduarda Rodrigues](https://github.com/eduardar0)| [Dylan Cavalcante](https://github.com/dylancavalcante) |  