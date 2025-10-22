# Backlog

## Introdução

O Product Backlog do ID Jovem representa o registro contínuo e priorizado de todos os requisitos, funcionalidades e melhorias planejadas para o aplicativo, com o objetivo de oferecer valor direto aos jovens beneficiários e à gestão dos serviços disponibilizados pelo governo <a id="TEC1" href="#RP1">[1] </a>. Este artefato é dinâmico, permitindo a inclusão de novos itens a qualquer momento, o que facilita a adaptação a mudanças nas demandas dos jovens ou nas políticas públicas relacionadas ao programa. A gestão e redefinição das prioridades no backlog são responsabilidade do gerente de produto _(Product Owner)_, que realiza avaliações periódicas para otimizar o fluxo de desenvolvimento e garantir que as funcionalidades de maior impacto sejam implementadas primeiro <a id="TEC2" href="#RP2">[2] </a>.

## Metodologia

A construção do *Product Backlog do ID Jovem teve início com reuniões e entrevistas realizadas junto aos jovens beneficiários do aplicativo, bem como aos gestores do programa, com o objetivo de identificar funcionalidades essenciais e validar requisitos já levantados. A partir dessas interações, as funcionalidades foram formalizadas em Histórias de Jovem, utilizando a estrutura: "Como um [tipo de jovem], eu desejo [ação] para [benefício]".

Cada história conta com critérios de aceitação claros, que servem como referência para o desenvolvimento e a validação das entregas, garantindo que o aplicativo atenda às necessidades reais dos jovens beneficiários, como acesso à carterinha digital, emissão de comprovantes e visualização de eventos culturais e esportivos.  

O Product Owner realizou a priorização das histórias seguindo a abordagem Three Level Scale, classificando-as em Alta, Média ou Baixa prioridade conforme o impacto esperado para os jovens beneficiários e para a eficiência do serviço. Em seguida, as histórias foram organizadas hierarquicamente em temas e épicos, adotando a estrutura recomendada em frameworks ágeis como Scrum e SAFe. Neste documento, o padrão utilizado é Tema → Épico → Histórias de Jovem, conforme descrito por Milene Serrano e Maurício Serrano <a id="TEC2" href="#RP2">[2] </a>.

O detalhamento completo de cada história do ID Jovem pode ser consultado nos artefatos vinculados, permitindo transparência no processo de desenvolvimento e acompanhamento das funcionalidades implementadas.


<div align="center">
<table>
  <thead>
    <tr>
      <th>Participante</th>
      <th>Função</th>
      <th>Épicos</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://github.com/arthurfernandesj">Arthur Fernandes</a></td>
      <td>Produtor do Backlog</td>
      <td><a href="#e10">E10</a>, <a href="#e11">E11</a>, <a href="#e33">E33</a>, <a href="#e34">E34</a>, <a href="#e35">E35</a>, <a href="#e36">E36</a></td>
    </tr>
    <tr>
      <td><a href="https://github.com/BrenoLTeixeira">Breno Lourenço</a></td>
      <td>Produtor do Backlog</td>
      <td><a href="#e09">E09</a>, <a href="#e13">E13</a>, <a href="#e29">E29</a>, <a href="#e30">E30</a>, <a href="#e31">E31</a>, <a href="#e32">E32</a></td>
    </tr>
    <tr>
      <td><a href="https://github.com/dylancavalcante">Dylan Cavalcante</a></td>
      <td>Produtor do Backlog</td>
      <td><a href="#e05">E05</a>, <a href="#e06">E06</a>, <a href="#e14">E14</a>, <a href="#e26">E26</a>, <a href="#e27">E27</a>, <a href="#e28">E28</a></td>
    </tr>
    <tr>
      <td><a href="https://github.com/eduardar0">Eduarda Domingos</a></td>
      <td>Produtor do Backlog</td>
      <td><a href="#e03">E03</a>, <a href="#e04">E04</a>, <a href="#e22">E22</a>, <a href="#e23">E23</a>, <a href="#e24">E24</a>, <a href="#e25">E25</a></td>
    </tr>
    <tr>
      <td><a href="https://github.com/GiovanaFontesS">Giovana Fontes</a></td>
      <td>Produtor do Backlog</td>
      <td><a href="#e07">E07</a>, <a href="#e08">E08</a>, <a href="#e15">E15</a>, <a href="#e16">E16</a>, <a href="#e17">E17</a>, <a href="#e18">E18</a></td>
    </tr>
    <tr>
      <td><a href="https://github.com/leticialopes20">Leticia Lopes</a></td>
      <td>Produtor do Backlog</td>
      <td><a href="#e01">E01</a>, <a href="#e02">E02</a>, <a href="#e12">E12</a>, <a href="#e19">E19</a>, <a href="#e20">E20</a>, <a href="#e21">E21</a></td>
    </tr>
  </tbody>
</table>
</div>

<p style="text-align: center; font-size: 10pt;">Fonte: <a href="https://github.com/arthurfernandesj">Arthur Fernandes</a></p>


## Temas e Épicos

Após a análise e organização das demandas coletadas para o aplicativo ID Jovem, foi possível agrupá-las em cinco grandes temas. Esses temas representam o nível mais alto de abstração e refletem as áreas principais de funcionalidades do aplicativo, facilitando a visualização geral das necessidades dos jovens beneficiários.  

Para detalhar os temas, as demandas foram desmembradas em épicos — agrupamentos de funcionalidades que representam grandes blocos de trabalho, com um nível intermediário de especificação. Cada épico contempla um conjunto de histórias de jovem que descrevem ações e benefícios esperados.  

Abaixo estão todos os temas e épicos identificados para o ID Jovem.

<a name="tema1"></a>


### Tema 1: Consulta e Informações Pessoais

- **E01 - Consulta de carterinha digital**  
  *Eu, como jovem beneficiário, desejo consultar minha carterinha digital e verificar informações detalhadas para acompanhar meus benefícios.*

- **E02 - Consulta de dados pessoais**  
  *Eu, como jovem beneficiário, desejo visualizar e atualizar meus dados pessoais para manter minhas informações corretas.*

- **E03 - Histórico de acessos e benefícios**  
  *Eu, como jovem beneficiário, desejo acessar o histórico de utilização de benefícios para controle e transparência.*

- **E20 - Exportação de comprovantes e histórico em PDF**  
  *Eu, como jovem beneficiário, desejo exportar meus comprovantes e histórico de uso em formato PDF para armazenar e compartilhar informações.*

- **E23 - Tutorial interativo do ID Jovem**  
  *Eu, como jovem beneficiário, desejo acessar um tutorial interativo no aplicativo para ser orientado sobre como utilizar o ID Jovem e aproveitar seus benefícios.*

---

<a name="tema2"></a>

### Tema 2: Emissão e Solicitação de Benefícios

- **E04 - Solicitação e acompanhamento de benefícios**  
  *Eu, como jovem beneficiário, desejo solicitar benefícios e acompanhar o status para gerenciar minhas solicitações.*

- **E05 - Cancelamento e filtro de solicitações**  
  *Eu, como jovem beneficiário, desejo cancelar solicitações e filtrar por tipo e data para facilitar o controle.*

- **E06 - Informação sobre bloqueios e motivos**  
  *Eu, como jovem beneficiário, desejo ser informado sobre bloqueios de benefícios e seus motivos para entender impedimentos.*

- **E07 - Guias e ajuda para solicitações**  
  *Eu, como jovem beneficiário, desejo contar com guias interativos e seções de ajuda para facilitar o uso dos benefícios.*

<a name="tema3"></a>

### Tema 3: Parceiros e Eventos

- **E08 - Visualização e cadastro de parceiros e eventos**  
  *Eu, como jovem beneficiário, desejo consultar parceiros e eventos próximos para planejar minha participação e utilizar benefícios.*

- **E14 - Avaliação de parceiros e estabelecimentos**  
  *Eu, como jovem beneficiário, desejo avaliar parceiros e estabelecimentos conveniados com notas e comentários.*

- **E24 - Integração com GPS para localização de estabelecimentos**  
  *Eu, como jovem beneficiário, desejo localizar estabelecimentos próximos em tempo real via GPS.*


<a name="tema4"></a>

### Tema 4: Comunicação e Suporte

- **E09 - Suporte via chat e canal de atendimento**  
  *Eu, como jovem beneficiário, desejo ter acesso a suporte via chatbot ou assistente para esclarecer dúvidas rapidamente.*

- **E10 - Notificações e avisos**  
  *Eu, como jovem beneficiário, desejo receber notificações sobre eventos, benefícios e atualizações importantes.*

-  **E15 - Configuração de preferências de notificação**  
  *Eu, como jovem beneficiário, desejo configurar preferências de notificação, como tipo de alerta e frequência.*

- **E21 - Exibir versão do app e informações de atualização**  
  *Eu, como jovem beneficiário, desejo visualizar a versão do aplicativo e informações sobre atualizações.*

- **E22 - Alertas sobre atualizações importantes**  
  *Eu, como jovem beneficiário, desejo receber alertas sobre atualizações importantes do programa ID Jovem.*

- **E25 - Acesso rápido a termos de uso e política de privacidade**  
  *Eu, como jovem beneficiário, desejo acessar rapidamente os termos de uso e política de privacidade.*

---

<a name="tema5"></a>

### Tema 5: Usabilidade e Acessibilidade

- **E11 - Personalização da interface**  
  *Eu, como jovem beneficiário, desejo ajustar o tamanho das fontes e utilizar uma interface simples para melhorar a experiência.*

- **E12 - Busca e navegação**  
  *Eu, como jovem beneficiário, desejo dispor de um campo de busca e navegação clara para encontrar funcionalidades facilmente.*

- **E16 - Modo acessível e leitura por voz**  
  *Eu, como jovem beneficiário, desejo utilizar um modo acessível com contraste ajustável e leitura por voz para pessoas com deficiência visual.*

---

<a name="tema6"></a>

### Tema 6: Segurança

- **E13 - Acesso seguro e autenticação**  
  *Eu, como jovem beneficiário, desejo acessar o aplicativo de forma segura para garantir a proteção dos meus dados e o uso adequado das funcionalidades.*

- **E17 - Recuperação de conta**  
  *Eu, como jovem beneficiário, desejo recuperar o acesso à minha conta via e-mail, SMS ou Gov.br para não perder meus dados.*

- **E18 - Alteração de senha**  
  *Eu, como jovem beneficiário, desejo alterar minha senha pelo aplicativo para manter minha conta segura.*

- **E19 - Registro de logs e auditoria**  
  *Eu, como jovem beneficiário, desejo que o sistema registre logs de acesso e ações para fins de auditoria e segurança.*

## Backlog

| Tema | Épico | Histórias de Usuário | ID US | Prioridade | Rastreabilidade |
|:--|:--|:--|:--|:--|:--|
| Consulta e Informações Pessoais | E01 | Consulta de carteirinha digital | US01 | Alta | [US01](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entrega_04/#us01) |
| Consulta e Informações Pessoais | E02 | Consulta de dados pessoais | US02 | Média | [US02](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entrega_04/#us02)  |
| Consulta e Informações Pessoais | E03 | Histórico de acessos e benefícios | US03 | Alta | [US03](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entrega_04/#us03) |
| Emissão e Solicitação de Benefícios | E04 | Solicitação e acompanhamento de benefícios | US04 | Média | [US04](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entrega_04/#us04) |
| Emissão e Solicitação de Benefícios | E05 | Cancelamento e filtro de solicitações | US05 | Média | [US05](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entrega_04/#us05) |
| Emissão e Solicitação de Benefícios | E06 | Informação sobre bloqueios e motivos | US06 | Alta | [US06](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entrega_04/#us06) |
| Emissão e Solicitação de Benefícios | E07 | Guias e ajuda para solicitações | US07 | Alta | [US07](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entrega_04/#us07)  |
| Parceiros e Eventos | E08 | Visualização e cadastro de parceiros e eventos | US08 | Média | [US08](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entrega_04/#us08) |
| Comunicação e Suporte | E09 | Suporte via chat e canal de atendimento | US09 | Média | [US09](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entrega_04/#us09) |
| Comunicação e Suporte | E10 | Notificações e avisos | US10 | Alta | [US10](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entrega_04/#us10) |
| Usabilidade e Acessibilidade | E11 | Personalização da interface | US11 | Alta | [US11](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entrega_04/#us11) |
| Usabilidade e Acessibilidade | E12 | Busca e navegação | US12 |  Alta | [US12](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entrega_04/#us12) |
| Segurança | E13 | Acesso seguro e autenticação | US13 | Alta | [US13](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entrega_04/#us13) |
| Parceiros e Eventos | E08 | Visualização e cadastro de parceiros e eventos | US08 | Média | [US08](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entrega_04/#us08) |
| Parceiros e Eventos | E14 | Avaliação de parceiros e estabelecimentos | US14 | Alta | [US14](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entrega_04/#us14) |
| Comunicação e Suporte | E09 | Suporte via chat e canal de atendimento | US09 | Alta | [US09](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entrega_04/#us09) |
| Comunicação e Suporte | E10 | Notificações e avisos | US10 | Alta | [US10](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entrega_04/#us10) |
| Comunicação e Suporte | E15 | Configuração de preferências de notificação | US15 | Média | [US15](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entrega_04/#us15) |
| Usabilidade e Acessibilidade | E11 | Personalização da interface | US11 |  Média | [US11](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entrega_04/#us11) |
| Usabilidade e Acessibilidade | E12 | Busca e navegação | US12 | Média | [US12](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entrega_04/#us12) |
| Usabilidade e Acessibilidade | E16 | Modo acessível e leitura por voz | US16 | Alta | [US16](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entrega_04/#us16) |
| Segurança | E13 | Acesso seguro e autenticação | US13 | Alta | [US13](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entrega_04/#us13) |
| Segurança | E17 | Recuperação de conta | US17 | Alta | [US17](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entrega_04/#us17) |
| Segurança | E18 | Alteração de senha | US18 | Alta | [US18](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entrega_04/#us18)|
| Segurança | E19 | Registro de logs e auditoria | US19 | Alta | [US19](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entrega_04/#us19) |
| Consulta e Informações Pessoais | E20 | Exportação de comprovantes e histórico em PDF | US20 | Alta | [US20](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entrega_04/#us20) |
| Comunicação e Suporte | E21 | Exibir versão do app e informações de atualização | US21 | Média | [US21](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entrega_04/#us21) |
| Comunicação e Suporte | E22 | Alertas sobre atualizações importantes | US22 | Alta |[US22](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entrega_04/#us22)|
| Consulta e Informações Pessoais | E23 | Tutorial interativo do ID Jovem | US23 | Alta | [US23](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entrega_04/#us23) |
| Parceiros e Eventos | E24 | Integração com GPS para localização de estabelecimentos | US24 | Média | [US24](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entrega_04/#us24)|
| Comunicação e Suporte | E25 | Acesso rápido a termos de uso e política de privacidade | US25 | Alta | [US25](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entrega_04/#us25) |


<font size="2"><p style="text-align: center">Fonte: [Arthur Fernandes](https://github.com/arthurfernandesj)</p></font>

## Validação

### Gravação 1 - Validação Dylan e Arthur 

<p style="text-align: center">
  <iframe width="560" height="315" 
    src="https://www.youtube.com/embed/XqMZYMSVyak" 
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
    src="https://www.youtube.com/embed/4IY3tEKq5II" 
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
    src="https://www.youtube.com/embed/CPbK4F7Y9uA" 
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

##  Referências Bibliográficas


> SERRANO, Milene. Requisitos - Aula 15. Local: UnB-FGA, Gama, DF. Apresentação de Power Point. 35, color. Disponível em: [Requisitos - Aula 15](). Acesso em: 20 de Out de 2025.
>

> </a> Requisitos de Software. Lichess (2022.2). Disponível em: [https://requisitos-de-software.github.io/2022.2-Lichess/modelagem/agil/backlog/](https://requisitos-de-software.github.io/2022.2-Lichess/modelagem/agil/backlog/). Acesso em: 20 Out. 2025.



##  Histórico de Versão

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
|--------|------|-----------|-----------|-------------|
| 1.0 | 18/10/2025 | Criação do Documento: Introdução, Metodologia e Backlog  | [Arthur](https://github.com/arthurfernandesj) | [ Leticia ](https://github.com/leticialopes20) |
| 1.1 | 20/10/2025 | Atualização na tabela de Backlog  | [Arthur](https://github.com/arthurfernandesj) | [ Dylan ](https://github.com/dylancavalcante) |
| 1.2 | 21/10/2025 | Adição de gravações de validação |  [Giovana Fontes](https://github.com/GiovanaFontesS) | [Arthur Fernandes](https://github.com/arthurfernandesj) | 







