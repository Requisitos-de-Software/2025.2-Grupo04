## Introdução

A técnica de observação de requisitos é uma abordagem importante para coletar informações sobre o uso e as limitações de um sistema. Essa técnica consiste em acompanhar usuários durante a interação com o software, analisando suas ações, dificuldades e reações, a fim de identificar necessidades e oportunidades de melhoria.

No contexto do projeto ID Jovem, buscou-se compreender como o público-alvo lida com o aplicativo oficial do programa. Entretanto, não foi possível contar com usuários externos reais no momento da atividade. Dessa forma, o desenvolvedor [Arthur Fernandes](https:github.com/arthurfernandesj) assumiu o papel da persona [nome]() ,jovem beneficiário do programa, para simular a experiência prática de utilização do aplicativo.


## Metodologia

A atividade foi desenvolvida no dia xx/xx/2025 das 00:00 - 00:00, em reunião online pelo **Microsoft Teams** com os participantes descritos na **tabela 1**. O objetivo da sessão foi conduzir uma **Observação Participativa**, na qual o Engenheiro de Software instruiu o usuário simulado sobre as ações a serem realizadas dentro do aplicativo do ID Jovem.

Durante a análise, o participante responsável por representar o usuário compartilhou a tela do dispositivo móvel enquanto executava tarefas previamente definidas, como:

* Efetuar login no sistema.

* Emitir a carteirinha digital do ID Jovem.

* Consultar informações sobre a validade do documento.

* Explorar opções de uso do benefício (ex.: emissão de passagens, acesso a eventos, entre outras).


---

| Nome | Funnção |
|-------|------------|
| Nome | Nome |
| Nome | Nome |

---

<font size="3"><p style="text-align: center">Tabela 2: Detalhes da Observação</p></font>

<div align="center">

<table>
  <thead>
    <tr>
      <th>Nome do Usuário Observado</th>
      <th>Data</th>
      <th>Hora</th>
      <th>Local</th>
      <th>Observador</th>
      <th>Anotador de Requisitos</th>
      <th>Meio de Observação</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Nome</td>
      <td>xx/xx/2025</td>
      <td>xx:xx</td>
      <td>LOCAL</td>
      <td>NOME DO OBSERVADOR</td>
      <td>NOME DO ANOTADOR</td>
      <td>Gravação de Interação ou TEAMS</td>
    </tr>
    <tr>
 <td>Nome</td>
      <td>xx/xx/2025</td>
      <td>xx:xx</td>
      <td>LOCAL</td>
      <td>NOME DO OBSERVADOR</td>
      <td>NOME DO ANOTADOR</td>
      <td>Gravação de Interação ou TEAMS</td>
    </tr>
  </tbody>

</table>
</div>

<p style="text-align: center; font-size: 16px;">Fonte: Autores</p>

---

## Requisitos Elicitados

As funcionalidades observadas foram organizadas a seguir como possíveis **Requisitos Funcionais (RF)** ou **Não Funcionais (RNF)**. O código **EOx** indica que a origem é observação.

<font size="3"><p style="text-align: center">Tabela 2: Legenda</p></font>

<div align="center">

<table>
  <thead>
    <tr>
      <th>Código</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>RFx</td>
      <td>Requisito Funcional nº x</td>
    </tr>
    <tr>
      <td>RNFx</td>
      <td>Requisito Não-Funcional nº x</td>
    </tr>
    <tr>
      <td>EOx</td>
      <td>Requisito nº x elicitado por observação</td>
    </tr>
  </tbody>
</table>

</div>


<p style="text-align: center; font-size: 16px;">Fonte: <i>Arthur Fernandes</i></p>

---

### Requisitos Funcionais

<font size="3"><p style="text-align: center">Tabela 3: Requisitos Funcionais</p></font>

<a name="OB_RF"></a>

| Código | Requisito Funcional / Descrição                                                                                     | ID   | Implementado |
| ------ | ------------------------------------------------------------------------------------------------------------------- | ---- | :----------: |
| RF05   | Login seguro, garantindo que apenas o jovem autorizado acesse o aplicativo                                         | OB01 |      Sim     |
| RF06   | Apresentar resumo dos benefícios disponíveis para o jovem, como transporte gratuito e eventos culturais           | OB02 |      Sim     |
| RF07   | Permitir solicitação de benefícios com justificativa adequada                                                     | OB03 |      Sim     |
| RF08   | Exibir histórico de benefícios já utilizados pelo jovem                                                           | OB04 |      Sim     |
| RF09   | Mostrar nome completo do titular do ID Jovem                                                                       | OB05 |      Sim     |
| RF10   | Disponibilizar histórico de solicitações realizadas                                                              | OB06 |      Sim     |
| RF11   | Aba dedicada à solicitação e acompanhamento dos benefícios                                                       | OB07 |      Sim     |
| RF12   | Possibilitar atualização de dados pessoais e informações de contato                                              | OB08 |      Sim     |
| RF13   | Incluir aba para itens diversos como dúvidas, ajuda, convocações e regulamentos do programa                        | OB09 |      Sim     |

### Requisitos Não Funcionais

<font size="3"><p style="text-align: center">Tabela 4: Requisitos Não Funcionais</p></font>

<a name="OB_RNF"></a>

| Código | Requisito Não-Funcional                                                                               | ID   | Implementado |
| ------ | ----------------------------------------------------------------------------------------------------- | ---- | :----------: |
| RNF06  | O sistema deve garantir segurança firme com verificação de dados pelo usuário                         | OB10 |      Sim     |
| RNF07  | A interface deve ser dividida em abas específicas com funções bem segmentadas                         | OB11 |      Sim     |
| RNF08  | A aplicação deve exibir notificações ou notícias úteis de forma acessível                             | OB12 |      Sim     |
| RNF09  | As informações devem estar organizadas de forma clara e com terminologia compreensível para o usuário | OB13 |      Sim     |


## Registro Visual da Observação

<p style="text-align: center">Figura 1 – Print da anotação feita durante a observação</p> <div align="center"> <img src="" width="500px"/> </div> <p style="text-align: center; font-size: 16px;">Fonte: <i>XXXX</i></p>

## Gravação

<p style="text-align: center">
<iframe width="560" height="315" src="" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>

<p style="text-align: center">
<iframe width="560" height="315" src="" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>


## Bibliografia


## 📝 Histórico de Versões

| Versão | Data       | Descrição                                        | Autor(es)    | Revisor(es) |
|--------|-----------|-------------------------------------------------|-------------|-------------|
| 1.0    | 17/09/2025 | Criação da página | [Arthur Fernandes](https://github.com/arthurfernandesj) | [Nome](https://github.com/)|


