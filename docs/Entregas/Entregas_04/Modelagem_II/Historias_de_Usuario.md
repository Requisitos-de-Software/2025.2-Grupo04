# Introdução 


As histórias de usuário são uma forma simples e ágil de representar requisitos funcionais de um sistema, descrevendo de maneira breve o que o usuário precisa que o software faça. Segundo **Vazquez e Simões (Engenharia de Requisitos)**, elas surgiram no contexto da Extreme Programming (XP) como uma unidade de funcionalidade que demonstra o progresso do projeto por meio da entrega de código testado e integrado. Cada história de usuário deve ser compreensível para o cliente, testável pelos desenvolvedores e pequena o suficiente para ser implementada dentro de uma iteração. Atualmente, essa técnica é amplamente utilizada em métodos ágeis, como o Scrum, em que o Product Owner é responsável por elaborá-las com base nas necessidades dos usuários. O uso de histórias de usuário promove a colaboração da equipe, facilita a priorização e garante que o valor entregue seja claro, embora não seja indicado para ambientes que exigem documentação extensa e formal.

<small><em>Revisado por [Chat GPT](https://chatgpt.com/share/68fa1aea-f1e0-8000-92d0-4f83227ea1d0), em 20 de outubro de 2025</em></small>


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

<small><em>Revisado por [Chat GPT](https://chatgpt.com/share/68fa1aea-f1e0-8000-92d0-4f83227ea1d0), em 20 de outubro de 2025</em></small>

### Participantes e histórias feitas

<font size="3"><p style="text-align: center">Tabela 1: Participantes</p></font>

<div align="center">

<table>
  <thead>
    <tr>
      <th align="center">Nome</th>
      <th align="left">Histórias</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center"><a href="https://github.com/arthurfernandesj">Arthur Fernandes</a></td>
      <td align="left">
        <a href="#h10">US10</a> – Fornecer alertas sobre possíveis irregularidades no uso dos benefícios<br>
        <a href="#h11">US11</a> – Possuir um mapa interativo para visualizar geograficamente parceiros e eventos<br>
        <a href="#h33">US33</a> – Registro de Logs de Acesso e Ações do Usuário<br>
        <a href="#h34">US34</a> – Alertas sobre Atualizações Importantes do Programa<br>
        <a href="#h35">US35</a> – Alteração de Senha de Acesso pelo Aplicativo<br>
        <a href="#h36">US36</a> – Integração com GPS para Localizar Estabelecimentos Próximos
      </td>
    </tr>
    <tr>
      <td align="center"><a href="https://github.com/BrenoLTeixeira">Breno Teixeira</a></td>
      <td align="left">
        <a href="#h09">US09</a> – Permitir que o jovem beneficiário atualize seu cadastro e defina preferências pessoais<br>
        <a href="#h13">US13</a> – Fornecer um canal para denúncia ou feedback sobre estabelecimentos que recusam o benefício<br>
        <a href="#h29">US29</a> – Exportação de Histórico de Uso em PDF<br>
        <a href="#h30">US30</a> – Configuração de Preferências de Notificação<br>
        <a href="#h31">US31</a> – Exibir Versão do Aplicativo e Informações de Atualização<br>
        <a href="#h32">US32</a> – Acesso aos Termos de Uso e Política de Privacidade
      </td>
    </tr>
    <tr>
      <td align="center"><a href="https://github.com/dylancavalcante">Dylan Cavalcante</a></td>
      <td align="left">
        <a href="#h05">US05</a> – Permitir que o Jovem Beneficiário visualize o histórico de utilização dos benefícios<br>
        <a href="#h06">US06</a> – Seção de "Vantagens e Parcerias" com novidades, divulgação sobre o programa e ofertas exclusivas<br>
        <a href="#h14">US14</a> – Permitir que o jovem beneficiário favorite eventos e estabelecimentos para consulta rápida<br>
        <a href="#h26">US26</a> – Integração com Outros Serviços Governamentais<br>
        <a href="#h27">US27</a> – Avaliação de Parceiros e Estabelecimentos<br>
        <a href="#h28">US28</a> – Modo Acessível (Contraste e Leitura por Voz)
      </td>
    </tr>
    <tr>
      <td align="center"><a href="https://github.com/eduardar0">Eduarda Domingos</a></td>
      <td align="left">
        <a href="#h03">US03</a> – Disponibilizar informações sobre locais e parceiros que aceitam o benefício<br>
        <a href="#h04">US04</a> – Fornecer canal de suporte via chat, e-mail ou formulário de contato<br>
        <a href="#h22">US22</a> – Exibir Seção de Perguntas Frequentes (FAQ)<br>
        <a href="#h23">US23</a> – Download da Carteirinha para Uso Offline<br>
        <a href="#h24">US24</a> – Reserva e Emissão de Comprovantes de Uso<br>
        <a href="#h25">US25</a> – Validação Automática de Elegibilidade
      </td>
    </tr>
    <tr>
      <td align="center"><a href="https://github.com/GiovanaFontesS">Giovana Fontes</a></td>
      <td align="left">
        <a href="#h07">US07</a> – Permitir compartilhar a carteirinha em PDF ou imagem<br>
        <a href="#h08">US08</a> – Fornecer informações sobre pendências ou erros relacionados aos benefícios do jovem beneficiário<br>
        <a href="#h01">US15</a> – Cadastro do Jovem Beneficiário via CPF<br>
        <a href="#h02">US16</a> – Autenticação e Login via Gov.br<br>
        <a href="#h17">US17</a> – Recuperação de Conta via Gov.br, E-mail ou SMS<br>
        <a href="#h18">US18</a> – Tutorial Interativo do ID Jovem
      </td>
    </tr>
    <tr>
      <td align="center"><a href="https://github.com/leticialopes20">Letícia Lopes</a></td>
      <td align="left">
        <a href="#h01">US01</a> – Integração com o CadÚnico para atualização automática de dados<br>
        <a href="#h02">US02</a> – Emitir notificações sobre vencimento e renovação do benefício<br>
        <a href="#h12">US12</a> – Apresentar uma agenda integrada de eventos com filtros de busca<br>
        <a href="#h19">US19</a> – Geração e Emissão da Carteira Digital ID Jovem<br>
        <a href="#h20">US20</a> – Consulta de Benefícios (Transporte Gratuito e Meia-Entrada)<br>
        <a href="#h21">US21</a> – Validação da Carteira Digital em Estabelecimentos
      </td>
    </tr>
  </tbody>
</table>
</div>

<font size="2"><p style="text-align: center">Fontes: <i>[Letícia Lopes](https://github.com/leticialopes20) e [Dylan Cavalcante](https://github.com/dylancavalcante), 2025</i> </p></font>

<small><em>Revisado por [Chat GPT](https://chatgpt.com/share/68fa1aea-f1e0-8000-92d0-4f83227ea1d0), em 20 de outubro de 2025</em></small>

---

## Tabela Padrão 

A tabela abaixo será utilizada como modelo para a elaboração das histórias de usuário do projeto. Ela padroniza os principais elementos necessários, como a descrição da necessidade, critérios de aceitação, prioridade, status de validação, entre outros. O objetivo é garantir consistência, rastreabilidade e clareza em todas as histórias documentadas.

<font size="3"><p style="text-align: center">Tabela 2: Tabela de Padronização das Historia de usuário</p></font>

| **ID** | USN° |
|--------|------|
| **Rastreabilidade** | Relacionamento com o(s) requisito(s) funcional(is) correspondente(s) à história |
| **Tema** | Funcionalidade principal que a história aborda |
| **Descrição** | Breve explicação do que o usuário deseja fazer e o valor que isso traz  |
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
| **Status** | Validado |
| **Autor** | [Letícia Lopes](https://github.com/leticialopes20) |

<font size="2"><p style="text-align: center">Fonte: [Letícia Lopes](https://github.com/leticialopes20)</p></font>

### <a name="h02"></a> **História 02: Emitir notificações sobre vencimento e renovação do benefício** <font size="3"><p style="text-align: center">Tabela 4: História de Emissão de notificações sobre vencimento e renovação de benefícios</p></font>

| **ID** | US02 |
|--------|-------|
| **Rastreabilidade** | [RF08](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf08) ([BS11](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/), [ST04](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Storytelling/), [IDJ11](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspecção/), [ENT13](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/))|
| **Tema** | Emissão de notificações automáticas de renovação do benefício |
| **Descrição** | Eu, como Jovem Beneficiário, desejo receber notificações sobre o vencimento e o prazo de renovação do meu benefício, para que eu possa manter o cadastro ativo e não perca o acesso aos direitos oferecidos pelo programa. |
| **Critérios de Aceitação** | - O sistema deve emitir notificações automáticas 30, 15 e 5 dias antes do vencimento do benefício. <br>- As notificações devem estar disponíveis no aplicativo e opcionalmente por e-mail ou push notification. <br>- A mensagem deve conter o link ou instrução para realizar a renovação. <br>- O sistema deve confirmar quando a renovação for concluída com sucesso. |
| **Prioridade Usuário** |Alta|
| **Status** | Validado |
| **Autor** | [Letícia Lopes](https://github.com/leticialopes20) |

<font size="2"><p style="text-align: center">Fonte: [Letícia Lopes](https://github.com/leticialopes20)</p></font>

### <a name="h03"></a> **História 03: Disponibilizar informações sobre locais e parceiros que aceitam o benefício**

<font size="3"><p style="text-align: center">Tabela 5: História de disponibilização de informações sobre locais e parceiros que aceitam o benefício </p></font>

| **ID** | US03 |
|--------|-------|
| **Rastreabilidade** | [RF10](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf10) ([ENT05](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/), [BS08](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/)) |
| **Tema** | Consulta de Parceiros |
| **Descrição** | Como jovem beneficiário, eu quero consultar os locais e parceiros que aceitam o ID Jovem, para saber onde posso utilizar meus benefícios de forma prática e planejada.  |
| **Critérios de Aceitação** | -Usuário consegue acessar a lista de parceiros <br>- Sistema exibe informações completas dos estabelecimentos (nome, endereço, horário)<br> - Funcionalidade funciona em dispositivos móveis<br>- Busca por localização ou categoria disponível<br>- Informações atualizadas e precisas|
| **Prioridade Usuário** |Média  |
| **Status** | Validado |
| **Autor** | [Eduarda](https://github.com/eduardar0) |

<font size="2"><p style="text-align: center">Fonte:[Eduarda](https://github.com/eduardar0)</p></font>

### <a name="h04"></a> **História 04: Fornecer canal de suporte via chat, e-mail ou formulário de contato**

<font size="3"><p style="text-align: center">Tabela 6: História de fornecimento de canal de suporte via chat, e-mail ou formulário de contato</p></font>

| **ID** | US04 |
|--------|-------|
| **Rastreabilidade** | [RF11](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf11) |
| **Tema** |  Canal de Suporte |
| **Descrição** | Como usuário do ID Jovem, eu quero ter acesso a um canal de suporte eficiente, para resolver minhas dúvidas e problemas de forma rápida e satisfatória.  |
| **Critérios de Aceitação** |- Usuário consegue acessar o canal de suporte <br>- Múltiplas opções disponíveis (chat, e-mail, formulário)<br>- Sistema fornece confirmação de recebimento<br>- Tempo de resposta dentro do esperado<br>- Funcionalidade funciona em dispositivos móveis<br>- Histórico de atendimento disponível  |
| **Prioridade Usuário** | Alta  |
| **Status** | Validado |
| **Autor** | [Eduarda](https://github.com/eduardar0) |

<font size="2"><p style="text-align: center">Fonte: [Eduarda](https://github.com/eduardar0)</p></font>

### <a name="h05"></a> **História 05: Permitir que o Jovem Beneficiário visualize o histórico de utilização dos benefícios** <font size="3"><p style="text-align: center">Tabela 7: História de permissão de que o Jovem Beneficiário visualize o histórico de utilização dos benefícios</p></font>

| **ID** | US05|
|--------|-------|
| **Rastreabilidade** | [RF12](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf12) |
| **Tema** | Permitir que o Jovem Beneficiário visualize o histórico de utilização dos benefícios  |
| **Descrição** | Eu, como Jovem Beneficiário, desejo visualizar um histórico de onde e quando utilizei meus benefícios (como viagens interestaduais e meia-entrada), para poder acompanhar meu uso e ter um registro das minhas atividades. |
| **Critérios de Aceitação** | - O histórico deve exibir uma lista cronológica das utilizações.<br>- Cada item da lista deve detalhar o tipo de benefício usado (ex: Meia-entrada, Vaga gratuita em transporte). <br>- Cada item deve registrar a data e, se possível, a empresa ou evento onde foi utilizado. <br>- O histórico deve ser de fácil acesso a partir do menu principal ou do perfil do jovem beneficiário. |
| **Prioridade Usuário** | média |
| **Status** | Validado |
| **Autor** | [Dylan Cavalcante](https://github.com/dylancavalcante) |

<font size="2"><p style="text-align: center">Fonte: [Dylan Cavalcante](https://github.com/dylancavalcante)</p></font>

### <a name="h06"></a> **História 06: Seção de "Vantagens e Parcerias" com novidades, divulgação sobre o programa e ofertas exclusivas** <font size="3"><p style="text-align: center">Tabela 8: História de visualização da seção de "Vantagens e Parcerias" com novidades, divulgação sobre o programa e ofertas exclusivas</p></font>

| **ID** | US06 |
|--------|-------|
| **Rastreabilidade** | [RF13](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf13) |
| **Tema** | Seção de "Vantagens e Parcerias" com novidades, divulgação sobre o programa e ofertas exclusivas |
| **Descrição** | Eu, como Jovem Beneficiário, desejo acessar uma seção de "Vantagens e Parcerias" para descobrir novidades sobre o programa, cursos profissionalizantes, e ofertas exclusivas de parceiros. |
| **Critérios de Aceitação** | - A seção deve ser claramente visível no menu principal do aplicativo. <br>- O conteúdo deve ser dividido em categorias (ex: 'Novidades do Programa', 'Cursos e Capacitação', 'Ofertas de Parceiros'). <br>- O conteúdo deve ser atualizado regularmente. <br>- As ofertas e notícias devem ser relevantes para o público do ID Jovem. |
| **Prioridade Usuário** | média|
| **Status** | Validado |
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
| **Status** | Validado |
| **Autor** | [Giovana Fontes](https://github.com/GiovanaFontesS) |

<font size="2"><p style="text-align: center">Fonte: [Giovana Fontes](https://github.com/GiovanaFontesS)</p></font>


### <a name="h08"></a> **História 08: Fornecer informações sobre pendências ou erros relacionados aos benefícios do jovem beneficiário**

<font size="3"><p style="text-align: center">Tabela 10: História de fornecimento de informações sobre pendências ou erros relacionados aos benefícios do jovem beneficiário</p></font>

| **ID** | US08 |
|--------|------------|
| **Rastreabilidade** | [RF18](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf18)  |
| **Tema** | Exibição de pendências e erros nos benefícios |
| **Descrição** | Eu, como Jovem Beneficiário, desejo visualizar informações sobre pendências ou erros relacionados aos meus benefícios, para compreender o motivo de possíveis bloqueios ou falhas na emissão da carteirinha. |
| **Critérios de Aceitação** | - O aplicativo deve exibir mensagens claras quando houver pendências ou erros nos dados do beneficiário. <br> - As mensagens devem conter instruções sobre como resolver o problema (ex: atualizar cadastro, verificar documentação). <br> - O sistema deve diferenciar visualmente os tipos de erro (pendência documental, erro no sistema, dados inválidos etc.). <br> - As notificações devem ser acessíveis na tela principal do usuário. |
| **Prioridade Usuário** | Alta |
| **Status** | Validado |
| **Autor** | [Giovana Fontes](https://github.com/GiovanaFontesS) |

<font size="2"><p style="text-align: center">Fonte: [Giovana Fontes](https://github.com/GiovanaFontesS)</p></font>


### <a name="h09"></a> **História 09: Permitir que o jovem beneficiário atualize seu cadastro e defina preferências pessoais** <font size="3"><p style="text-align: center">Tabela 11:História de permissão de que o jovem beneficiário atualize seu cadastro e defina preferências pessoais</p></font>

| **ID** | US09 |
|--------|-------|
| **Rastreabilidade** | [RF19](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf19) |
| **Tema** | Gerenciamento de Perfil e Preferências |
| **Descrição** | Eu, como Jovem Beneficiário, desejo poder atualizar minhas informações de cadastro e definir preferências pessoais, para manter meus dados corretos e receber conteúdo alinhado aos meus interesses. |
| **Critérios de Aceitação** | - O usuário deve conseguir acessar uma seção "Meu Perfil" ou "Configurações".<br>- O usuário deve conseguir editar campos cadastrais (ex: e-mail, telefone).<br>- O usuário deve conseguir salvar as alterações no perfil.<br>- O usuário deve poder selecionar categorias de interesse (ex: shows, esportes, teatro) para personalizar notificações. |
| **Prioridade Usuário** | Média |
| **Status** | Validado |
| **Autor** | [Breno Teixeira](https://github.com/BrenoLTeixeira) |

### <a name="h10"></a> **História 10: Fornecer alertas sobre possíveis irregularidades no uso dos benefícios**  
<font size="3"><p style="text-align: center">Tabela 12: História de fornecimento de alertas sobre possíveis irregularidades no uso dos benefícios</p></font>

| **ID** | US10 |
|--------|-------|
| **Rastreabilidade** | [RF20](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf20) |
| **Tema** | Segurança e Conformidade no uso de benefícios |
| **Descrição** | Eu, como Jovem Beneficiário, desejo receber alertas sobre possíveis irregularidades no uso dos meus benefícios, para que eu possa evitar problemas legais e garantir que estou utilizando corretamente meus direitos. |
| **Critérios de Aceitação** | - O sistema deve identificar padrões de uso incorreto ou suspeito.<br>- Alertas devem ser enviados via aplicativo ou e-mail em tempo real.<br>- Cada alerta deve conter instruções claras sobre como regularizar a situação.<br>- O sistema deve evitar falsos positivos em mais de 5% dos casos. |
| **Prioridade Usuário** | Alta |
| **Status** | Validado |
| **Autor** | [Arthur Fernandes](https://github.com/arthurfernandesj) |

<font size="2"><p style="text-align: center">Fonte: [Arthur Fernandes](https://github.com/arthurfernandesj)</p></font>

---

### <a name="h11"></a> **História 11: Possuir um mapa interativo para visualizar geograficamente parceiros e eventos**  
<font size="3"><p style="text-align: center">Tabela 13: História de visualização de parceiros e eventos geograficamente por mapa interativo</p></font>

| **ID** | US11 |
|--------|-------|
| **Rastreabilidade** | [RF21](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf21) |
| **Tema** | Usabilidade e Visualização de Benefícios |
| **Descrição** | Eu, como Jovem Beneficiário, desejo visualizar parceiros e eventos em um mapa interativo, para localizar facilmente onde posso utilizar meus benefícios e participar de atividades do programa. |
| **Critérios de Aceitação** | - O mapa deve exibir todos os parceiros e eventos cadastrados.<br>- Deve ser possível filtrar por tipo de benefício, data ou localidade.<br>- Clicar em um ponto do mapa deve exibir informações detalhadas sobre o parceiro ou evento.<br>- O mapa deve ser responsivo e funcionar corretamente em dispositivos móveis. |
| **Prioridade Usuário** | Média |
| **Status** | Validado |
| **Autor** | [Arthur Fernandes](https://github.com/arthurfernandesj) |

<font size="2"><p style="text-align: center">Fonte: [Arthur](https://github.com/arthurfernandesj)</p></font>



### <a name="h12"></a> **História 12: Apresentar uma agenda integrada de eventos com filtros de busca** <font size="3"><p style="text-align: center">Tabela 14: História de apresentação de uma agenda integrada de eventos com filtros de busca</p></font>

| **ID** | US12|
|--------|-------|
| **Rastreabilidade** | [RF22](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf22) |
| **Tema** | Agenda integrada de eventos culturais e sociais|
| **Descrição** | Eu, como Jovem Beneficiário, desejo acessar uma agenda de eventos integrados ao aplicativo, com possibilidade de filtrar por data, local e tipo de evento, para planejar melhor minha participação em atividades culturais, esportivas e educacionais.|
| **Critérios de Aceitação** | - A agenda deve listar eventos culturais, esportivos e educacionais disponíveis aos beneficiários do programa.<br>- O usuário deve conseguir filtrar eventos por data, cidade e categoria. <br>- Cada evento deve exibir informações detalhadas (nome, local, horário, parceiro envolvido e se há meia-entrada ou gratuidade). <br>- Deve haver opção para adicionar eventos à agenda pessoal ou marcar como favorito. |
| **Prioridade Usuário** | Média |
| **Status** | Validado |
| **Autor** | [Letícia Lopes](https://github.com/leticialopes20) |

<font size="2"><p style="text-align: center">Fonte: [Letícia Lopes](https://github.com/leticialopes20)</p></font>

### <a name="h13"></a> **História 13: Fornecer um canal para denúncia ou feedback sobre estabelecimentos que recusam o benefício**

<font size="3"><p style="text-align: center">Tabela 15: História de fornecimento de canal para denúncia ou feedback sobre estabelecimentos que recusam o benefício</p></font>

| **ID** | US13 |
|--------|-------|
| **Rastreabilidade** | [RF23](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf23) |
| **Tema** | Canal de Denúncia e Feedback |
| **Descrição** | Eu, como Jovem Beneficiário, desejo ter um canal para enviar denúncias ou feedbacks sobre estabelecimentos que recusaram a ID Jovem, para que os administradores do programa possam tomar providências e garantir meu direito. |
| **Critérios de Aceitação** | - Deve existir uma seção "Denúncia" ou "Reportar Problema" no aplicativo.<br>- O formulário deve permitir inserir o nome do estabelecimento, data, local e uma descrição do ocorrido.<br>- O sistema deve permitir (opcionalmente) anexar uma foto do local ou comprovante.<br>- O sistema deve enviar uma confirmação de recebimento da denúncia/feedback. |
| **Prioridade Usuário** | Alta |
| **Status** | Validado |
| **Autor** | [Breno Teixeira](https://github.com/BrenoLTeixeira) |

<font size="2"><p style="text-align: center">Fonte: [Breno Teixeira](https://github.com/BrenoLTeixeira)</p></font>

### <a name="h14"></a> **História 14: Permitir que o jovem beneficiário favorite eventos e estabelecimentos para consulta rápida** <font size="3"><p style="text-align: center">Tabela 16: História de permissão de que o jovem beneficiário favorite eventos e estabelecimentos para consulta rápida </p></font>

| **ID** | US14 |
|--------|-------|
| **Rastreabilidade** | [RF24](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf24) |
| **Tema** | Permitir que o jovem beneficiário favorite eventos e estabelecimentos para consulta rápida  |
| **Descrição** | Eu, como Jovem Beneficiário, desejo salvar (favoritar) eventos e estabelecimentos parceiros do meu interesse para poder consultá-los rapidamente no futuro em uma lista dedicada. |
| **Critérios de Aceitação** | - Deve haver um botão ou ícone (ex: estrela, coração) visível na página de detalhes de cada evento/estabelecimento para favoritá-lo. <br>- Deve existir uma seção "Meus Favoritos" no aplicativo, acessível pelo menu ou perfil do jovem beneficiário. <br>- Ao clicar no botão de favoritar, o item deve ser adicionado à lista "Meus Favoritos". <br>- O jovem beneficiário deve poder remover um item da lista de favoritos a qualquer momento. |
| **Prioridade Usuário** | baixa |
| **Status** | Validado |
| **Autor** | [Dylan Cavalcante](https://github.com/dylancavalcante) |

<font size="2"><p style="text-align: center">Fonte: [Dylan Cavalcante](https://github.com/dylancavalcante)</p></font>

### <a name="h01"></a> **História 15: Cadastro do Jovem Beneficiário via CPF**

<font size="3"><p style="text-align: center">Tabela 1: História de cadastro do Jovem Beneficiário via CPF</p></font>

| **ID** | US15 |
|--------|------------|
| **Rastreabilidade** | [RF01](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf01) |
| **Tema** | Cadastro do Jovem Beneficiário |
| **Descrição** | Eu, como Jovem Beneficiário, desejo me cadastrar no sistema utilizando meu CPF para ter acesso às funcionalidades do aplicativo de forma segura e personalizada. |
| **Critérios de Aceitação** | - O sistema deve permitir o cadastro utilizando CPF válido. <br> - O cadastro deve validar se o CPF não está duplicado. <br> - O cadastro deve gerar um perfil inicial do beneficiário após validação do CPF. |
| **Prioridade Usuário** | Alta |
| **Status** | Validado |
| **Autor** | [Giovana Fontes](https://github.com/GiovanaFontesS) |

<font size="2"><p style="text-align: center">Fonte: [Giovana Fontes](https://github.com/GiovanaFontesS)</p></font>

---
### <a name="h02"></a> **História 16: Autenticação e Login via Gov.br**

<font size="3"><p style="text-align: center">Tabela 2: História de autenticação e login via Gov.br</p></font>

| **ID** | US16 |
|--------|------------|
| **Rastreabilidade** | [RF02](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf02),  |
| **Tema** | Autenticação e Login |
| **Descrição** | Eu, como Jovem Beneficiário, desejo me autenticar e fazer login no aplicativo via Gov.br para garantir a segurança e confiabilidade do acesso às minhas informações. |
| **Critérios de Aceitação** | - O sistema deve permitir login via Gov.br. <br> - O processo de autenticação deve validar as credenciais do usuário em tempo real. <br> - O sistema deve redirecionar o usuário para a tela inicial após login bem-sucedido. <br> - Mensagens de erro devem ser exibidas em caso de falha na autenticação. |
| **Prioridade Usuário** | Alta |
| **Status** | Validado |
| **Autor** | [Giovana Fontes](https://github.com/GiovanaFontesS) |

<font size="2"><p style="text-align: center">Fonte: [Giovana Fontes](https://github.com/GiovanaFontesS)</p></font>


### <a name="h17"></a> **História 17: Recuperação de Conta via Gov.br, E-mail ou SMS**

<font size="3"><p style="text-align: center">Tabela 3: História de recuperação de conta</p></font>

| **ID** | US17 |
|--------|------------|
| **Rastreabilidade** | [RF25](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf25) |
| **Tema** | Recuperação de Conta |
| **Descrição** | Eu, como Jovem Beneficiário, desejo recuperar o acesso à minha conta por meio de verificação via e-mail, SMS ou Gov.br, para garantir que possa acessar meus dados mesmo em caso de perda de credenciais. |
| **Critérios de Aceitação** | - O sistema deve permitir recuperação de conta via e-mail, SMS ou Gov.br. <br> - O usuário deve receber instruções claras para concluir a recuperação. <br> - Mensagens de erro devem ser exibidas em caso de falha no processo de verificação. <br> - A conta só deve ser recuperada após validação segura das informações fornecidas. |
| **Prioridade Usuário** | Alta |
| **Status** | Validado |
| **Autor** | <a href="https://github.com/GiovanaFontesS">Giovana Fontes</a> |

<font size="2"><p style="text-align: center">Fonte: <a href="https://github.com/GiovanaFontesS">Giovana Fontes</a></p></font>

### <a name="h18"></a> **História 18: Tutorial Interativo do ID Jovem**

<font size="3"><p style="text-align: center">Tabela 4: História do tutorial interativo</p></font>

| **ID** | US18 |
|--------|------------|
| **Rastreabilidade** | [RF26](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf26) |
| **Tema** | Tutorial Interativo |
| **Descrição** | Eu, como Jovem Beneficiário, desejo acessar um tutorial interativo no aplicativo para ser orientado sobre como utilizar o ID Jovem e aproveitar seus benefícios. |
| **Critérios de Aceitação** | - O aplicativo deve disponibilizar um tutorial interativo ao novo usuário. <br> - O tutorial deve explicar passo a passo como acessar e usar o ID Jovem. <br> - O usuário deve poder acessar o tutorial a qualquer momento pelo menu de ajuda. <br> - Feedbacks e instruções devem ser claros e de fácil compreensão. |
| **Prioridade Usuário** | Média |
| **Status** | Validado |
| **Autor** | <a href="https://github.com/GiovanaFontesS">Giovana Fontes</a> |

<font size="2"><p style="text-align: center">Fonte: <a href="https://github.com/GiovanaFontesS">Giovana Fontes</a></p></font>

### <a name="h19"></a> **História 19: Geração e Emissão da Carteira Digital ID Jovem**
<font size="3"><p style="text-align: center">Tabela 17: História de Geração e Emissão da Carteira Digital ID Jovem</p></font>

| **ID** | US19 |
|--------|-------|
| **Rastreabilidade** | [RF03](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf03) |
| **Tema** | Emissão da Carteira Digital |
| **Descrição** | Eu, como Jovem Beneficiário, desejo gerar e emitir minha carteira digital ID Jovem através do aplicativo, para poder apresentá-la e acessar meus benefícios. |
| **Critérios de Aceitação** | - Após o login e validação da elegibilidade, o sistema deve exibir a opção "Gerar Carteira".<br>- A carteira digital gerada deve conter meu nome, data de nascimento, NIS, data de validade e um QR Code de validação.<br>- O processo de geração deve ser concluído em menos de 10 segundos.<br>- A carteira deve ficar acessível na tela principal do aplicativo após ser gerada. |
| **Prioridade Usuário** | Alta |
| **Status** | Validado |
| **Autor** | [Letícia Lopes](https://github.com/leticialopes20) |

<font size="2"><p style="text-align: center">Fonte: [Letícia Lopes](https://github.com/leticialopes20)</p></font>

### <a name="h20"></a> **História 20: Consulta de Benefícios (Transporte Gratuito e Meia-Entrada)**
<font size="3"><p style="text-align: center">Tabela 18: História de Consulta de Benefícios</p></font>

| **ID** | US20 |
|--------|-------|
| **Rastreabilidade** | [RF04](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf04) |
| **Tema** | Informações sobre Benefícios |
| **Descrição** | Eu, como Jovem Beneficiário, desejo consultar informações claras sobre meus direitos, como transporte gratuito e meia-entrada em eventos, para entender o que o programa me oferece. |
| **Critérios de Aceitação** | - O aplicativo deve ter uma seção "Meus Benefícios".<br>- A seção deve detalhar as regras de uso do transporte interestadual gratuito (duas vagas) e com desconto (duas vagas).<br>- A seção deve explicar o direito à meia-entrada em eventos artístico-culturais e esportivos.<br>- As informações devem estar em linguagem simples e de fácil compreensão. |
| **Prioridade Usuário** | Alta |
| **Status** | Validado |
| **Autor** | [Letícia Lopes](https://github.com/leticialopes20) |

<font size="2"><p style="text-align: center">Fonte: [Letícia Lopes](https://github.com/leticialopes20)</p></font>

### <a name="h21"></a> **História 21: Validação da Carteira Digital em Estabelecimentos**
<font size="3"><p style="text-align: center">Tabela 19: História de Validação da Carteira Digital</p></font>

| **ID** | US21 |
|--------|-------|
| **Rastreabilidade** | [RF05](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf05) |
| **Tema** | Validação da Carteira |
| **Descrição** | Eu, como Jovem Beneficiário, desejo que minha carteira digital possa ser facilmente validada por estabelecimentos conveniados (como cinemas e empresas de transporte), para comprovar minha identidade e direito ao benefício. |
| **Critérios de Aceitação** | - A carteira digital deve exibir um QR Code único e dinâmico (ou estático, mas seguro).<br>- O estabelecimento deve conseguir ler o QR Code com um aplicativo validador ou câmera.<br>- A validação deve confirmar a autenticidade e a data de validade da carteira.<br>- O sistema deve funcionar mesmo se o estabelecimento estiver offline (se o QR Code contiver os dados assinados). |
| **Prioridade Usuário** | Alta |
| **Status** | Validado |
| **Autor** | [Letícia Lopes](https://github.com/leticialopes20) |

<font size="2"><p style="text-align: center">Fonte: [Letícia Lopes](https://github.com/leticialopes20)</p></font>

### <a name="h22"></a> **História 22: Exibir Seção de Perguntas Frequentes (FAQ)**
<font size="3"><p style="text-align: center">Tabela 20: História de Exibição de Seção de Perguntas Frequentes (FAQ)</p></font>

| **ID** | US22 |
|--------|-------|
| **Rastreabilidade** | [RF06](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf06) |
| **Tema** | Suporte ao Usuário (FAQ) |
| **Descrição** | Eu, como Jovem Beneficiário, desejo acessar uma seção de Perguntas Frequentes (FAQ) para tirar dúvidas comuns sobre o programa ID Jovem, elegibilidade e uso dos benefícios. |
| **Critérios de Aceitação** | - O aplicativo deve ter um item de menu "FAQ" ou "Dúvidas Frequentes".<br>- As perguntas devem ser organizadas por categorias (ex: Cadastro, Uso, Renovação).<br>- Deve haver uma barra de busca para filtrar as perguntas.<br>- As respostas devem ser claras e objetivas. |
| **Prioridade Usuário** | Média |
| **Status** | Validado |
| **Autor** | [Eduarda](https://github.com/eduardar0) |

<font size="2"><p style="text-align: center">Fonte: [Eduarda](https://github.com/eduardar0)</p></font>

### <a name="h23"></a> **História 23: Download da Carteirinha para Uso Offline**
<font size="3"><p style="text-align: center">Tabela 21: História de Download da Carteirinha para Uso Offline</p></font>

| **ID** | US23 |
|--------|-------|
| **Rastreabilidade** | [RF09](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf09) |
| **Tema** | Acesso Offline |
| **Descrição** | Eu, como Jovem Beneficiário, desejo poder fazer o download da minha carteirinha para que eu possa acessá-la e apresentá-la mesmo quando estiver sem conexão com a internet. |
| **Critérios de Aceitação** | - Deve haver um botão "Salvar Offline" ou "Baixar" na tela da carteirinha.<br>- A carteirinha (imagem ou dados) deve ser armazenada localmente no dispositivo.<br>- O aplicativo deve ser capaz de exibir a carteirinha salva sem acesso à rede.<br>- A carteirinha offline deve exibir a data em que foi salva para controle de validade. |
| **Prioridade Usuário** | Alta |
| **Status** | Validado |
| **Autor** | [Eduarda](https://github.com/eduardar0) |

<font size="2"><p style="text-align: center">Fonte: [Eduarda](https://github.com/eduardar0)</p></font>

### <a name="h24"></a> **História 24: Reserva e Emissão de Comprovantes de Uso**
<font size="3"><p style="text-align: center">Tabela 22: História de Reserva e Emissão de Comprovantes de Uso</p></font>

| **ID** | US24 |
|--------|-------|
| **Rastreabilidade** | [RF14](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf14) |
| **Tema** | Reserva de Benefícios |
| **Descrição** | Eu, como Jovem Beneficiário, desejo poder reservar (quando aplicável, como em transporte) e emitir comprovantes de uso do benefício diretamente pelo aplicativo, para facilitar o controle e a organização. |
| **Critérios de Aceitação** | - O sistema deve permitir a reserva de passagens interestaduais (se integrado às viações).<br>- Após a utilização de um benefício (ex: viagem), o sistema deve gerar um comprovante digital.<br>- O comprovante deve ser armazenado no histórico de utilização (referente à US05).<br>- O usuário deve poder visualizar ou baixar este comprovante. |
| **Prioridade Usuário** | Média |
| **Status** | Validado |
| **Autor** | [Eduarda](https://github.com/eduardar0) |

<font size="2"><p style="text-align: center">Fonte: [Eduarda](https://github.com/eduardar0)</p></font>

### <a name="h25"></a> **História 25: Validação Automática de Elegibilidade**
<font size="3"><p style="text-align: center">Tabela 23: História de Validação Automática de Elegibilidade</p></font>

| **ID** | US25 |
|--------|-------|
| **Rastreabilidade** | [RF15](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf15) |
| **Tema** | Validação de Cadastro |
| **Descrição** | Eu, como Jovem, ao tentar me cadastrar, desejo que o sistema valide automaticamente minha elegibilidade (idade, renda familiar, inscrição no CadÚnico), para saber imediatamente se tenho direito ao benefício. |
| **Critérios de Aceitação** | - Ao inserir o CPF (US15), o sistema deve consultar as bases do CadÚnico e outras bases governamentais.<br>- O sistema deve verificar a faixa etária (15-29 anos) e a renda familiar (até dois salários mínimos).<br>- Se elegível, o sistema permite prosseguir com o cadastro/login.<br>- Se inelegível, o sistema deve informar o motivo (ex: "Renda acima do limite", "Fora da faixa etária"). |
| **Prioridade Usuário** | Alta |
| **Status** | Validado |
| **Autor** | [Eduarda](https://github.com/eduardar0) |

<font size="2"><p style="text-align: center">Fonte: [Eduarda](https://github.com/eduardar0)</p></font>

### <a name="h26"></a> **História 26: Integração com Outros Serviços Governamentais**
<font size="3"><p style="text-align: center">Tabela 24: História de Integração com Outros Serviços Governamentais</p></font>

| **ID** | US26 |
|--------|-------|
| **Rastreabilidade** | [RF16](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf16) |
| **Tema** | Integração de Serviços |
| **Descrição** | Eu, como Jovem Beneficiário, desejo que o aplicativo ID Jovem se integre com outros serviços governamentais (além do Gov.br e CadÚnico), para centralizar o acesso a outros programas de interesse juvenil. |
| **Critérios de Aceitação** | - O aplicativo deve prover links ou integrações diretas (APIs) com outros serviços (ex: SINE, programas de capacitação do MEC).<br>- A integração deve aproveitar η autenticação Gov.br (Single Sign-On).<br>- O usuário deve ser informado sobre quais dados estão sendo compartilhados entre os serviços. |
| **Prioridade Usuário** | Baixa |
| **Status** | Validado |
| **Autor** | [Dylan Cavalcante](https://github.com/dylancavalcante) |

<font size="2"><p style="text-align: center">Fonte: [Dylan Cavalcante](https://github.com/dylancavalcante)</p></font>

### <a name="h27"></a> **História 27: Avaliação de Parceiros e Estabelecimentos**
<font size="3"><p style="text-align: center">Tabela 25: História de Avaliação de Parceiros e Estabelecimentos</p></font>

| **ID** | US27 |
|--------|-------|
| **Rastreabilidade** | [RF27](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf27) |
| **Tema** | Feedback de Parceiros |
| **Descrição** | Eu, como Jovem Beneficiário, desejo poder avaliar (com notas e comentários) os parceiros e estabelecimentos conveniados onde utilizei meu benefício, para compartilhar minha experiência com outros jovens e ajudar o programa a monitorar a qualidade do serviço. |
| **Critérios de Aceitação** | - Na página de detalhes de um parceiro (US03/US11), deve haver uma opção "Avaliar".<br>- O usuário deve poder dar uma nota (ex: 1 a 5 estrelas).<br>- O usuário deve poder deixar um comentário (opcional).<br>- A média das avaliações deve ser visível para outros usuários.<br>- Comentários inadequados devem ser moderados. |
| **Prioridade Usuário** | Média |
| **Status** | Validado |
| **Autor** | [Dylan Cavalcante](https://github.com/dylancavalcante) |

<font size="2"><p style="text-align: center">Fonte: [Dylan Cavalcante](https://github.com/dylancavalcante)</p></font>

### <a name="h28"></a> **História 28: Modo Acessível (Contraste e Leitura por Voz)**
<font size="3"><p style="text-align: center">Tabela 26: História de Modo Acessível</p></font>

| **ID** | US28 |
|--------|-------|
| **Rastreabilidade** | [RF28](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf28) |
| **Tema** | Acessibilidade |
| **Descrição** | Eu, como usuário com deficiência visual, desejo que o aplicativo ofereça um modo acessível, com contraste ajustável e leitura por voz, para que eu possa navegar e utilizar o ID Jovem sem dificuldades. |
| **Critérios de Aceitação** | - O aplicativo deve ter uma opção "Acessibilidade" nas configurações.<br>- Deve haver uma opção para "Alto Contraste".<br>- O aplicativo deve ser compatível com os leitores de tela nativos do sistema operacional (TalkBack/VoiceOver).<br>- Fontes devem ser redimensionáveis de acordo com a preferência do sistema. |
| **Prioridade Usuário** | Média |
| **Status** | Validado |
| **Autor** | [Dylan Cavalcante](https://github.com/dylancavalcante) |

<font size="2"><p style="text-align: center">Fonte: [Dylan Cavalcante](https://github.com/dylancavalcante)</p></font>

### <a name="h29"></a> **História 29: Exportação de Histórico de Uso em PDF**
<font size="3"><p style="text-align: center">Tabela 27: História de Exportação de Histórico de Uso em PDF</p></font>

| **ID** | US29 |
|--------|-------|
| **Rastreabilidade** | [RF29](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf29) |
| **Tema** | Exportação de Dados |
| **Descrição** | Eu, como Jovem Beneficiário, desejo poder exportar meu histórico de utilização dos benefícios (US05) e meus comprovantes (US24) em formato PDF, para ter um registro formal ou para prestação de contas. |
| **Critérios de Aceitação** | - Na tela de "Histórico de Utilização", deve haver um botão "Exportar PDF".<br>- O usuário deve poder selecionar um período (ex: "Últimos 6 meses", "Ano de 2025").<br>- O PDF gerado deve ser formatado de maneira clara, listando data, benefício e local.<br>- O arquivo deve poder ser salvo localmente ou compartilhado. |
| **Prioridade Usuário** | Baixa |
| **Status** | Validado |
| **Autor** | [Breno Teixeira](https://github.com/BrenoLTeixeira) |

<font size="2"><p style="text-align: center">Fonte: [Breno Teixeira](https://github.com/BrenoLTeixeira)</p></font>

### <a name="h30"></a> **História 30: Configuração de Preferências de Notificação**
<font size="3"><p style="text-align: center">Tabela 28: História de Configuração de Preferências de Notificação</p></font>

| **ID** | US30 |
|--------|-------|
| **Rastreabilidade** | [RF30](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf30) |
| **Tema** | Configuração de Notificações |
| **Descrição** | Eu, como Jovem Beneficiário, desejo configurar minhas preferências de notificação (RF08, RF34), para escolher quais tipos de alertas quero receber (ex: vencimento, novos parceiros) e com qual frequência. |
| **Critérios de Aceitação** | - Nas "Configurações" do aplicativo, deve haver uma seção "Notificações".<br>- O usuário deve poder habilitar ou desabilitar categorias de notificação (ex: "Vencimento da ID", "Novos Eventos", "Promoções de Parceiros").<br>- O usuário deve poder escolher o canal (Push, E-mail).<br>- As preferências devem ser salvas e respeitadas pelo sistema. |
| **Prioridade Usuário** | Média |
| **Status** | Validado |
| **Autor** | [Breno Teixeira](https://github.com/BrenoLTeixeira) |

<font size="2"><p style="text-align: center">Fonte: [Breno Teixeira](https://github.com/BrenoLTeixeira)</p></font>

### <a name="h31"></a> **História 31: Exibir Versão do Aplicativo e Informações de Atualização**
<font size="3"><p style="text-align: center">Tabela 29: História de Exibição de Versão do Aplicativo</p></font>

| **ID** | US31 |
|--------|-------|
| **Rastreabilidade** | [RF31](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf31) |
| **Tema** | Informações do Sistema |
| **Descrição** | Eu, como usuário, desejo ver a versão atual do aplicativo em uma seção "Sobre", para saber se estou com a versão mais recente ou para reportar problemas ao suporte. |
| **Critérios de Aceitação** | - O aplicativo deve ter uma seção "Sobre" ou "Informações".<br>- Esta seção deve exibir o número da versão atual (ex: "Versão 2.1.3").<br>- O sistema pode, opcionalmente, exibir um link para as notas da versão (o que há de novo) ou verificar se há atualizações. |
| **Prioridade Usuário** | Baixa |
| **Status** | Validado |
| **Autor** | [Breno Teixeira](https://github.com/BrenoLTeixeira) |

<font size="2"><p style="text-align: center">Fonte: [Breno Teixeira](https://github.com/BrenoLTeixeira)</p></font>

### <a name="h32"></a> **História 32: Acesso aos Termos de Uso e Política de Privacidade**
<font size="3"><p style="text-align: center">Tabela 30: História de Acesso aos Termos de Uso e Política de Privacidade</p></font>

| **ID** | US32 |
|--------|-------|
| **Rastreabilidade** | [RF32](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf32) |
| **Tema** | Informações Legais |
| **Descrição** | Eu, como usuário, desejo acessar facilmente os Termos de Uso e a Política de Privacidade do aplicativo, para entender como meus dados são usados e quais são as regras do serviço. |
| **Critérios de Aceitação** | - O menu de "Configurações" ou "Sobre" deve conter links para "Termos de Uso" e "Política de Privacidade".<br>- Os documentos devem ser exibidos dentro do aplicativo ou em um navegador web.<br>- Os textos devem estar atualizados conforme a legislação vigente (LGPD). |
| **Prioridade Usuário** | Média |
| **Status** | Validado |
| **Autor** | [Breno Teixeira](https://github.com/BrenoLTeixeira) |

<font size="2"><p style="text-align: center">Fonte: [Breno Teixeira](https://github.com/BrenoLTeixeira)</p></font>

### <a name="h33"></a> **História 33: Registro de Logs de Acesso e Ações do Usuário**
<font size="3"><p style="text-align: center">Tabela 31: História de Registro de Logs para Auditoria</p></font>

| **ID** | US33 |
|--------|-------|
| **Rastreabilidade** | [RF33](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf33) |
| **Tema** | Segurança e Auditoria (Não-Funcional/Backend) |
| **Descrição** | Eu, como Administrador do Sistema, desejo que o sistema registre logs de acesso e ações críticas do usuário (como geração de carteira, alteração de dados), para fins de auditoria, segurança e depuração de erros. |
| **Critérios de Aceitação** | - O sistema (backend) deve registrar logs para eventos de login (sucesso e falha).<br>- O sistema deve registrar logs para emissão de carteira (US19) e alteração de senha (US35).<br>- Os logs devem conter data/hora, ID do usuário (anonimizado se necessário) e a ação realizada.<br>- Os logs devem ser armazenados de forma segura e acessíveis apenas por administradores autorizados. |
| **Prioridade Usuário** | Alta |
| **Status** | Validado |
| **Autor** | [Arthur Fernandes](https://github.com/arthurfernandesj) |

<font size="2"><p style="text-align: center">Fonte: [Arthur Fernandes](https://github.com/arthurfernandesj)</p></font>

### <a name="h34"></a> **História 34: Alertas sobre Atualizações Importantes do Programa**
<font size="3"><p style="text-align: center">Tabela 32: História de Alertas sobre Atualizações do Programa</p></font>

| **ID** | US34 |
|--------|-------|
| **Rastreabilidade** | [RF34](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf34) |
| **Tema** | Notificações do Programa |
| **Descrição** | Eu, como Jovem Beneficiário, desejo receber alertas (notificações) sobre atualizações importantes nas regras ou no funcionamento do programa ID Jovem, para me manter informado sobre meus direitos. |
| **Critérios de Aceitação** | - O sistema deve enviar notificações push ou e-mail quando houver mudanças legais ou administrativas no programa (ex: mudança nas regras de renda).<br>- Os alertas devem ser claros e direcionar para uma fonte oficial (ex: site do governo) com mais detalhes.<br>- O usuário pode configurar o recebimento desses alertas (relacionado à US30). |
| **Prioridade Usuário** | Média |
| **Status** | Validado |
| **Autor** | [Arthur Fernandes](https://github.com/arthurfernandesj) |

<font size="2"><p style="text-align: center">Fonte: [Arthur Fernandes](https://github.com/arthurfernandesj)</p></font>

### <a name="h35"></a> **História 35: Alteração de Senha de Acesso pelo Aplicativo**
<font size="3"><p style="text-align: center">Tabela 33: História de Alteração de Senha</p></font>

| **ID** | US35 |
|--------|-------|
| **Rastreabilidade** | [RF35](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf35) |
| **Tema** | Segurança da Conta |
| **Descrição** | Eu, como Jovem Beneficiário, desejo poder alterar minha senha de acesso (caso não esteja usando exclusivamente o Gov.br) pelo próprio aplicativo, para manter minha conta segura. |
| **Critérios de Aceitação** | - Na seção "Segurança" ou "Perfil", deve haver a opção "Alterar Senha".<br>- O sistema deve solicitar a senha atual e a nova senha (duas vezes).<br>- O sistema deve validar a força da nova senha (ex: mínimo de 8 caracteres, letras e números).<br>- Se o login for exclusivo via Gov.br (US16), esta opção deve redirecionar o usuário para alterar a senha no Gov.br. |
| **Prioridade Usuário** | Média |
| **Status** | Validado |
| **Autor** | [Arthur Fernandes](https://github.com/arthurfernandesj) |

<font size="2"><p style="text-align: center">Fonte: [Arthur Fernandes](https://github.com/arthurfernandesj)</p></font>

### <a name="h36"></a> **História 36: Integração com GPS para Localizar Estabelecimentos Próximos**
<font size="3"><p style="text-align: center">Tabela 34: História de Integração com GPS para Localização</p></font>

| **ID** | US36 |
|--------|-------|
| **Rastreabilidade** | [RF36](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf36) |
| **Tema** | Localização de Parceiros |
| **Descrição** | Eu, como Jovem Beneficiário, desejo que o aplicativo use o GPS do meu celular para localizar e mostrar no mapa (US11) os estabelecimentos e parceiros próximos da minha localização atual. |
| **Critérios de Aceitação** | - O aplicativo deve solicitar permissão para usar o GPS.<br>- O mapa interativo (US11) deve ter um botão "Usar minha localização" ou "Perto de mim".<br>- Ao ativar, o mapa deve centralizar na localização do usuário.<br>- O sistema deve exibir os parceiros em um raio definido (ex: 5km) ou os mais próximos. |
| **Prioridade Usuário** | Média |
| **Status** | Validado |
| **Autor** | [Arthur Fernandes](https://github.com/arthurfernandesj) |

<font size="2"><p style="text-align: center">Fonte: [Arthur Fernandes](https://github.com/arthurfernandesj)</p></font>

## Validação  

### Gravação 1 - Validação Dylan e Arthur 

<p style="text-align: center">
  <iframe width="560" height="315" 
    src="https://www.youtube.com/embed/ej2ZI_-7yVc" 
    title="YouTube video player" 
    frameborder="0" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
    referrerpolicy="strict-origin-when-cross-origin" 
    allowfullscreen>
  </iframe>
</p>

 <font size="3">
    <p style="text-align: center">
      <b>Fonte:</b> <a href="https://github.com/GiovanaFontesS">Giovana Fontes</a>, 2025
    </p>
  </font>
  
### Gravação 2 - Validação Eduarda e Leticia  

<p style="text-align: center">
  <iframe width="560" height="315" 
    src="https://www.youtube.com/embed/FzFgf3r_DWU" 
    title="YouTube video player" 
    frameborder="0" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
    referrerpolicy="strict-origin-when-cross-origin" 
    allowfullscreen>
  </iframe>
</p>

 <font size="3">
    <p style="text-align: center">
      <b>Fonte:</b> <a href="https://github.com/GiovanaFontesS">Giovana Fontes</a>, 2025
    </p>
  </font>
  
---

### Gravação 3 - Validação Breno e Giovana

<p style="text-align: center">
  <iframe width="560" height="315" 
    src="https://www.youtube.com/embed/I0Id9MMhdqA" 
    title="YouTube video player" 
    frameborder="0" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
    referrerpolicy="strict-origin-when-cross-origin" 
    allowfullscreen>
  </iframe>
</p>

 <font size="3">
    <p style="text-align: center">
      <b>Fonte:</b> <a href="https://github.com/GiovanaFontesS">Giovana Fontes</a>, 2025
    </p>
  </font>
  
---

##  Referências Bibliográficas

> <a id="RP3" href="#TEC3">1.</a> VAZQUEZ, Carlos Eduardo; SIMÕES, Guilherme Siqueira; SIMÕES. *Engenharia de Requisitos: Software Orientado ao Negócio.* São Paulo , 2016. Acesso em: 19 de outubro de 2025.



##  Histórico de Versão

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
|--------|------|-----------|-----------|-------------|
| 1.0 | 19/10/2025 | Criação do Documento: Introdução, Metodologia, justificativa de uso e objetivo  | [Giovana Fontes](https://github.com/GiovanaFontesS) | [ Letícia Lopes ](https://github.com/leticialopes20) |
| 1.1 | 19/10/2025 | Adição das Historias de usuario [US05](#h05), [US06](#h06), [US14](#h14) | [Dylan Cavalcante](https://github.com/dylancavalcante) | [ Letícia Lopes](https://github.com/leticialopes20) |
| 1.2 | 20/10/2025 | Adição das Historias de usuario [US07](#h07) e [US08](#h08) | [Giovana Fontes](https://github.com/GiovanaFontesS) | [ Letícia Lopes](https://github.com/leticialopes20) |  
| 1.3 | 20/10/2025 |Adição das Historias de usuario [US01](#h01), [US02](#h02), [US12](#h12), refatoração do documento/edição de  hiperlinks| [ Letícia Lopes](https://github.com/leticialopes20)| [Dylan Cavalcante](https://github.com/dylancavalcante) |  
| 1.4 | 20/10/2025 |Adição das Historias de usuario [US03](#h03), [US04](#h04)|[Eduarda Rodrigues](https://github.com/eduardar0)| [Dylan Cavalcante](https://github.com/dylancavalcante) |
| 1.5 | 20/10/2025 | Adição das Histórias de Usuário [US09](#h09) e [US13](#h13) | [Breno Teixeira](https://github.com/BrenoLTeixeira) | [Eduarda Rodrigues](https://github.com/eduardar0) |
| 1.6 | 20/10/2025 | Adição das Histórias de Usuário [US10](#h09) e [US11](#h13) | [Arthur Fernandes](https://github.com/arthurfernandesj) | [ Letícia Lopes](https://github.com/leticialopes20) |
| 1.7 | 21/10/2025 | Adição de gravações de validação |  [Giovana Fontes](https://github.com/GiovanaFontesS) | [Arthur Fernandes](https://github.com/arthurfernandesj) | 
| 1.8 | 21/10/2025 |  Adição de Contribuições | [Giovana Fontes](https://github.com/GiovanaFontesS) |  [Arthur Fernandes](https://github.com/arthurfernandesj) |
| 1.9 | 21/10/2025 |  Fix tabela e adição de novas história | [Dylan Cavalcante](https://github.com/dylancavalcante) |  [Arthur Fernandes](https://github.com/arthurfernandesj) |

## Agrecimentos

Queremos agradecer ao [Chat GPT](https://chatgpt.com/share/68fa1aea-f1e0-8000-92d0-4f83227ea1d0), ferramenta de Inteligência Artificial Generativa, pelo apoio durante o desenvolvimento deste projeto ID Jovem. Sua ajuda foi essencial na revisão de textos, na organização das ideias e na pesquisa de conteúdos complementares que contribuíram para deixar nossa documentação mais clara e completa.

De acordo com o Código de Conduta da Sociedade Brasileira de Computação (SBC), destacamos que a ferramenta foi utilizada apenas como apoio técnico e linguístico.
Todo o conteúdo apresentado é de autoria do Grupo 04, que assume total responsabilidade por sua originalidade e precisão.
