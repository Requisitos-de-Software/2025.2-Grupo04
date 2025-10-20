# NFR Framework

## Introdução

No contexto do desenvolvimento do **aplicativo ID Jovem**, os [Requisitos Não-Funcionais (RNFs)]() desempenham um papel essencial ao definir qualidades e restrições que afetam diretamente a experiência do jovem beneficiário, a segurança dos dados, o desempenho e a conformidade com as legislações vigentes. Dentre esses requisitos, destaca-se a importância de garantir a **proteção das informações pessoais** e a **confiabilidade** na emissão e validação da Identidade Jovem.

Com o objetivo de representar e analisar esses requisitos de maneira estruturada, este trabalho adota o **NFR Framework**, uma abordagem proposta por [Chung et al. (2000)](). Esse framework possibilita a modelagem dos RNFs por meio de *softgoals*, que representam objetivos qualitativos sem critérios de satisfação exatos, mas fundamentais para a qualidade do produto. 

A representação gráfica desses *softgoals* é feita através de um **grafo SIG (Softgoal Interdependency Graph)**, que evidencia suas interdependências, influências e possíveis conflitos. Assim, o **NFR Framework aplicado ao ID Jovem** contribui para o fortalecimento da **usabilidade**, **segurança**, **confiabilidade** e **acessibilidade** do aplicativo, assegurando que os jovens beneficiários utilizem a plataforma de forma prática e segura.

## SIG - Softgoal Interdependency Graph

O NFR Framework funciona por meio da construção e análise de um grafo chamado **Softgoal Interdependency Graph (SIG)**, que representa graficamente os Requisitos Não-Funcionais (softgoals), suas interdependências, alternativas e justificativas. Esse grafo permite avaliar se os requisitos de alto nível foram atendidos e apoia decisões de projeto voltadas à melhoria do aplicativo ID Jovem.

### Tipos de SIG

O SIG é dividido em três tipos principais:

- **Softgoals NFR**: representam alternativas técnicas e soluções práticas (como processos, restrições ou estruturas) para atender aos softgoals do aplicativo ID Jovem — por exemplo, garantir desempenho adequado ao emitir o cartão digital.

- **Softgoals de Operacionalização**: representam os softgoals e suas interdependências, permitindo identificar conflitos e sinergias, como a relação entre acessibilidade e desempenho no uso do app.

- **Softgoals de Afirmação**: trazem justificativas baseadas em características do domínio do ID Jovem (como requisitos de segurança e prioridade de acesso), apoiando decisões e rastreabilidade do sistema.

<font size="3"><p style="text-align: center">Figura 1: Tipos de Softgoal</p></font>

![Figura 1](../../../assets/NFR/imagem1.png)

<font size="2"><p style="text-align: center">Fonte: [SILVA, 2019]()</p></font>

### Tipos e Interdependências de Softgoals no NFR Framework

- O NFR Framework utiliza três tipos de *softgoals*, representados por diferentes estilos de nuvens:
  - **Softgoals NFR**: nuvens claras  
  - **Softgoals de Operacionalização**: nuvens com linhas grossas  
  - **Softgoals de Afirmação**: nuvens com linhas tracejadas  

- Cada *softgoal NFR* possui um **tipo** (ex: Usabilidade) e um **tópico** (ex: Interface do Usuário), que indicam a parte específica do aplicativo ID Jovem à qual se referem.

- As **interdependências** entre os *softgoals* são classificadas em:
  - **Refinamentos (top-down)**, onde um *softgoal* pai gera filhos mais específicos, podendo ser:
    - **Decomposição de Softgoal NFR**: divide um requisito não-funcional em outros mais detalhados, como dividir “Confiabilidade” em “Disponibilidade” e “Segurança”.
    - **Decomposição de Operacionalização**: refina soluções implementáveis, como criptografia de dados ou autenticação do beneficiário.
    - **Decomposição de Afirmação**: detalha justificativas de projeto, como priorizar o acesso rápido mesmo em conexões móveis limitadas.
    - **Priorização**: refina um *softgoal* destacando sua importância dentro do aplicativo, como dar prioridade à acessibilidade sobre o desempenho visual.

Essa estrutura permite representar, refinar e justificar de forma clara os requisitos não-funcionais que impactam diretamente a qualidade e a confiabilidade do aplicativo **ID Jovem**, garantindo que o sistema cumpra seu propósito social com eficiência e segurança.

<font size="3"><p style="text-align: center">Figura 2: Tipos e Interdependências de Softgoals no NFR Framework</p></font>

![Figura 2](../../../assets/NFR/imagem2.png) 

<font size="2"><p style="text-align: center">Fonte: [SILVA, 2019]()</p></font>


### Contribuições e Tipos no NFR Framework

- Durante o refinamento dos *softgoals*, um *softgoal* descendente pode contribuir positiva ou negativamente, de forma total ou parcial, para a satisfação do *softgoal* ascendente.
- A **satisfação de softgoal** indica que o requisito não-funcional deve ser atendido dentro de limites aceitáveis, o que é essencial no **ID Jovem**, pois certos aspectos (como desempenho e segurança) podem influenciar-se mutuamente.

- **AND**: todos os descendentes precisam ser satisfeitos para o ascendente ser satisfeito (ex: para alcançar “Segurança”, é necessário satisfazer “Criptografia” **e** “Validação de Identidade”).  
- **OR**: basta um descendente satisfeito para o ascendente ser satisfeito (ex: “Autenticação” pode ser feita via CPF **ou** QR Code).  
- **MAKE (++)**: contribuição highly positiva; a satisfação do descendente garante a satisfação do ascendente.  
- **BREAK (--)**: contribuição highly negativa; a satisfação do descendente prejudica o ascendente.  
- **HELP (+)**: contribuição parcialmente positiva; satisfação parcial do descendente contribui parcialmente para o ascendente.  
- **HURT (-)**: contribuição parcialmente negativa; satisfação do descendente prejudica parcialmente o ascendente.  
- **UNKNOWN (?)**: contribuição desconhecida, pode ser positiva ou negativa.  
- **EQUALS**: o descendente só é satisfeito se o ascendente for satisfeito.  
- **SOME**: há um sinal conhecido (positivo ou negativo), mas o grau da contribuição é incerto.

Essas contribuições permitem entender como decisões técnicas no ID Jovem (como escolha de layout, autenticação e performance) afetam a satisfação global dos requisitos de qualidade do sistema.

---

### Procedimento de Avaliação no NFR Framework

- O **procedimento de avaliação** determina o grau em que os requisitos não-funcionais (*softgoals*) são satisfeitos por um conjunto de decisões de projeto.  
- Cada *softgoal* ou interdependência do **Softgoal Interdependency Graph (SIG)** recebe um **rótulo** que indica seu status de satisfação.  

#### Tipos de rótulos usados:

- ✓ **(satisfeito)**: O requisito é plenamente atendido.  
- 𝒲+ **(fracamente satisfeito)**: Atendido parcialmente; impacto positivo moderado.  
- X **(negado)**: O requisito não é atendido.  
- 𝒲- **(fracamente negado)**: Negação parcial; impacto negativo brando.  
- 𝟲 **(conflitante)**: Há conflito entre requisitos, coexistindo aspectos positivos e negativos.  
- u **(indeterminado)**: Não há dados suficientes para determinar o impacto.

No contexto do **ID Jovem**, essa avaliação permite verificar, por exemplo, se as melhorias na **usabilidade** não comprometem a **segurança dos dados**, garantindo um equilíbrio entre experiência do usuário e conformidade com os requisitos legais e técnicos.

A avaliação é feita de forma hierárquica:
- Inicia-se pelos *softgoals* de **nível mais baixo**, relacionados a decisões específicas (como design de tela ou criptografia).
- Em seguida, os rótulos são **propagados para os níveis superiores**, avaliando o impacto cumulativo até os *softgoals* de alto nível (como “Confiabilidade” e “Segurança da Informação”).

<font size="3"><p style="text-align: center">Figura 3: Procedimento de Avaliação no NFR Framework</p></font>

![Figura 3](../../../assets/NFR/procedimento.png)


<font size="2"><p style="text-align: center">Fonte: [SILVA, 2019]()</p></font>



## Metodologia

Para aplicar o **NFR Framework** ao desenvolvimento do aplicativo, adotamos uma abordagem em etapas estruturadas, com o objetivo de identificar, modelar, analisar e tomar decisões relacionadas aos requisitos não funcionais (softgoals) do sistema. A metodologia compreende as seguintes fases:

### 1. Identificação dos Requisitos Não Funcionais (Softgoals)

Nesta etapa, foram identificados os principais requisitos não funcionais relevantes ao contexto do aplicativo, como:

- Usabilidade  
- Desempenho  
- Segurança  
- Acessibilidade  
- Confiabilidade  
- Portabilidade

Essa identificação foi baseada em entrevistas com stakeholders, análise de mercado e levantamento de requisitos funcionais relacionados. Os requisitos não funcionais são representados como **softgoals**, que expressam intenções qualitativas sem critérios rígidos de satisfação.

### 2. Modelagem com o NFR Framework

A modelagem foi realizada utilizando a notação proposta por [*Chung et al. (2000)*](), representando os softgoals em uma estrutura hierárquica com relacionamentos de contribuição entre eles. Foram utilizados os seguintes tipos de contribuição:

- **MAKE (++)**
- **HELP (+)**
- **HURT (-)**
- **BREAK (--)**
- **OR**
- **AND**
- **EQUALS**
- **UNKNOWN (?)**
- **SOME**


Também foram especificadas as **operacionalizações**, ou seja, decisões de projeto que implementam cada softgoal.

#### Uso do Cartão de Especificação

Durante essa fase de modelagem, utilizou-se o **Cartão de Especificação** como instrumento de apoio à documentação e análise. Cada cartão foi preenchido com os seguintes elementos:

- Nome do softgoal  
- Descrição do requisito não funcional  
- Alternativas de operacionalização  
- Contribuições com outros softgoals  
- Justificativa das decisões  
- Responsável e data da análise  

A Tabela 1 ilustra o modelo adotado para a elaboração dos cartões de especificação.

<font size="3"><p style="text-align: center">Tabela 1: Template de cartão de especificação </p></font>

<center>
<table border="1" cellpadding="6" cellspacing="0">
  <tr><th colspan="2">Requisito Não Funcional – RNFXX</th></tr>
  <tr><td><strong>Classificação</strong></td><td> Classificação do RNF conforme a hierarquia do catálogo.</td></tr>
  <tr><td><strong>Descrição</strong></td><td>Declaração única do significado do requisito.</td></tr>
  <tr><td><strong>Justificativa</strong></td><td>Justificativa sobre a criação do requisito</td></tr>
  <tr><td><strong>Origem do Requisito</strong></td><td>Origem do requisito (stakeholder, norma técnica e etc...)</td></tr>
  <tr><td><strong>Critério de Aceitação</strong></td><td>Métrica do requisito que possa ser testada e que deve ser satisfeita.</td></tr>
  <tr><td><strong>Dependências</strong></td><td>Requisitos relacionados a este.</td></tr>
  <tr><td><strong>Prioridade</strong></td><td>Um número usado para decidir a importância relativa deste requisito entre os outros RNFs (varia de 1 a 10). A prioridade mínima é 1 e a máxima é 10.</td></tr>
  <tr><td><strong>Conflitos</strong></td><td>Requisitos conflitantes com este.</td></tr>
  <tr><td><strong>História</strong></td><td>Data de criação e de modificações.</td></tr>
</table>
</center>

<font size="2"><p style="text-align: center">Autor: [Arthur Fernandes](https://github.com/arthurfernandesj) </p></font>


O cartão facilitou a **rastreabilidade, clareza e consistência** das informações, além de permitir uma análise comparativa entre alternativas e apoiar a comunicação com os stakeholders durante a modelagem dos requisitos.

### 3. Avaliação dos Softgoals

Após modelar os softgoals e suas contribuições, foi realizado o **procedimento de avaliação**, no qual cada softgoal recebeu um rótulo indicando o grau de satisfação:

- `✓` **Satisfeito**: Requisito não funcional plenamente atendido.  
- `𝒲+` **Fracamente satisfeito**: Satisfação parcial.  
- `X` **Negado**: Requisito contradiz outro.  
- `𝒲-` **Fracamente negado**: Impacto negativo moderado.  
- `𝟲` **Conflitante**: Conflito entre requisitos.  
- `u` **Indeterminado**: Impacto incerto ou desconhecido.

A avaliação começou pelos softgoals de nível mais baixo (operacionalizações), subindo até os níveis superiores da hierarquia para analisar o impacto global das decisões.


### 4. Tomada de Decisão

Com base nas análises e rótulos atribuídos, foram tomadas decisões de projeto priorizando as alternativas que **maximizassem a satisfação dos softgoals mais críticos**.  
Em casos de conflito (por exemplo, **Desempenho vs. Segurança**), foram realizadas **ponderações junto aos stakeholders**, buscando o melhor compromisso entre eficiência e proteção dos dados do usuário.

---

### 5. Validação

A etapa de validação da modelagem seguiu duas vertentes principais:

- **Rastreabilidade com as histórias de usuário:**  
  Verificou-se se os *softgoals* contemplavam os desejos e expectativas expressas por cada persona.  

- **Análise de cobertura:**  
  Avaliou-se se os principais atributos de qualidade esperados para um aplicativo público financeiro — como **disponibilidade**, **desempenho** e **segurança** — foram devidamente modelados.

Essa validação assegurou que os **requisitos não funcionais** fossem não apenas documentados, mas também **rastreáveis, justificáveis e compatíveis** com os requisitos funcionais do **ID Jovem**.

---

### Cronograma de Participantes

<p style="text-align: center; font-size: 12pt;"><strong>Tabela 2: Cronograma de Participantes</strong></p>

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
      <td>19/10/2025</td>
      <td>19:30</td>
    </tr>
    <tr>
      <td><a href="https://github.com/brenolteixeira">Breno Teixeira</a></td>
      <td>xx/10/2025</td>
      <td>04:16</td>
    </tr>
    <tr>
      <td><a href="https://github.com/"> </a></td>
      <td>xx/10/2025</td>
      <td>00:00</td>
    </tr>
    <tr>
      <td><a href="https://github.com/"></a></td>
      <td>xx/10/2025</td>
      <td>00:00</td>
    </tr>
    <tr>
      <td><a href="https://github.com/"></a></td>
      <td>xx/10/2025</td>
      <td>00:00</td>
    </tr>
    <tr>
      <td><a href="https://github.com/"></a></td>
      <td>xx/10/2025</td>
      <td>00:00</td>
    </tr>
  </tbody>
</table>
</div>

<p style="text-align: center; font-size: 10pt;">Autor: <a href="https://github.com/arthurfernandesj">Arthur Fernandes</a></p>

### **Requisitos Não-Funcionais**

<font size="3"><p style="text-align: center">Tabela 3: Requisitos Não-Funcionais utilizados na criação do NFR Framework</p></font>

| **Código** | **Versão** | **Descrição**                                                                                          | **Origem** |
|------------|------------|--------------------------------------------------------------------------------------------------------|------------|
| RNF01 | 1.0 | O aplicativo deve ser intuitivo e de fácil uso, mesmo para jovens com pouca experiência digital. | ENT17 |
| RNF-- | 1.0 | --------------------------|  |
| RNF-- | 1.0 | O aplicativo deve ser gratuito e compatível com Android e iOS.| IDJ06 |
| RNF-- | 1.0 | O aplicativo deve possuir recursos de acessibilidade|BS20,IDJ09 |
| RNF-- | 1.0 | --------------------------|  |
| RNF-- | 1.0 | -------------------------- |  |
| RNF-- | 1.0 |-------------------------- | |
| RNF-- | 1.0 |-------------------------- |  |
| RNF-- | 1.0 |-------------------------- |  |
| RNF-- | 1.0 |-------------------------- | |
| RNF-- | 1.0 |-------------------------- |  |
| RNF-- | 1.0 | -------------------------- |  |
| RNF-- | 1.0 | -------------------------- |  |
| RNF-- | 1.0 | -------------------------- | |

<font size="2"><p style="text-align: center">Autor: [Arthur Fernandes](https://github.com/arthurfernandesj)</p></font>



## Cartão Especificação


<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 9:</b> Requisito Não Funcional – ENT17</p></font>

<a name="ENT17"></a>

<center>
<table border="1" cellpadding="6" cellspacing="0">
  <tr><th colspan="2">Requisito Não Funcional – RNF01</th></tr>
  <tr><td><strong>Classificação</strong></td><td>Usabilidade</td></tr>
  <tr><td><strong>Descrição</strong></td><td>O aplicativo deve ser intuitivo e de fácil uso, mesmo para jovens com pouca experiência digital.</td></tr>
  <tr><td><strong>Justificativa</strong></td><td>Um design intuitivo garante que todos os jovens, independentemente de sua familiaridade com tecnologia, consigam utilizar o aplicativo de forma eficiente e sem frustração.</td></tr>
  <tr><td><strong>Origem do Requisito</strong></td><td>ENT17</td></tr>
  <tr><td><strong>Critério de Aceitação</strong></td><td>Usuários novatos devem conseguir completar tarefas básicas sem orientação adicional e sem erros críticos.</td></tr>
  <tr><td><strong>Dependências</strong></td><td>Interface gráfica do aplicativo, fluxos de navegação e testes de usabilidade.</td></tr>
  <tr><td><strong>Prioridade</strong></td><td>10</td></tr>
  <tr><td><strong>Conflitos</strong></td><td>Nenhum</td></tr>
  <tr><td><strong>História</strong></td><td>19/10/2025</td></tr>
</table>
</center>

</div>

<font size="2"><p style="text-align: center">Autor: [Arthur Fernandes](https://github.com/arthurfernandesj)</p></font>

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 10:</b> Requisito Não Funcional – RNF05</p></font>

<a name="RNF05"></a>

<center>
<table border="1" cellpadding="6" cellspacing="0">
  <tr><th colspan="2">Requisito Não Funcional – RNF05</th></tr>
  <tr><td><strong>Classificação</strong></td><td>Segurança</td></tr>
  <tr><td><strong>Descrição</strong></td><td>Os dados pessoais do Jovem Beneficiário devem ser protegidos com criptografia conforme a LGPD.</td></tr>
  <tr><td><strong>Justificativa</strong></td><td>A segurança dos dados é essencial para proteger as informações sensíveis do jovem, garantindo conformidade com a Lei Geral de Proteção de Dados (LGPD) e evitando o uso indevido de informações pessoais.</td></tr>
  <tr><td><strong>Origem do Requisito</strong></td><td>RNF-SEG-01, BS22, ENT19</td></tr>
  <tr><td><strong>Critério de Aceitação</strong></td><td>Todos os dados pessoais armazenados e transmitidos devem utilizar criptografia AES-256, com autenticação e controle de acesso baseados em tokens seguros.</td></tr>
  <tr><td><strong>Dependências</strong></td><td>Sistema de autenticação, banco de dados seguro e integração com o Gov.br.</td></tr>
  <tr><td><strong>Prioridade</strong></td><td>10</td></tr>
  <tr><td><strong>Conflitos</strong></td><td>Pode impactar o desempenho em dispositivos com hardware limitado.</td></tr>
  <tr><td><strong>História</strong></td><td>19/10/2025</td></tr>
</table>
</center>

</div>

<font size="2"><p style="text-align: center">Autor: [Arthur Fernandes](https://github.com/arthurfernandesj)</p></font>

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 11:</b> Requisito Não Funcional – RNF04</p></font>

<a name="RNF04"></a>

<center>
<table border="1" cellpadding="6" cellspacing="0">
  <tr><th colspan="2">Requisito Não Funcional – RNF04</th></tr>
  <tr><td><strong>Classificação</strong></td><td>Portabilidade</td></tr>
  <tr><td><strong>Descrição</strong></td><td>O aplicativo deve ser gratuito e compatível com Android e iOS.</td></tr>
  <tr><td><strong>Justificativa</strong></td><td>Para garantir o acesso universal ao benefício, o aplicativo deve funcionar nas principais plataformas móveis (Android e iOS) utilizadas pelo público-alvo, sem custo de aquisição.</td></tr>
  <tr><td><strong>Origem do Requisito</strong></td><td>IDJ06</td></tr>
  <tr><td><strong>Critério de Aceitação</strong></td><td>O aplicativo deve estar disponível para download gratuito na Google Play Store (Android) e na Apple App Store (iOS).<br>- Deve ser compatível com as versões N-2 (duas versões anteriores à mais recente) de ambos os sistemas operacionais.</td></tr>
  <tr><td><strong>Dependências</strong></td><td>Políticas de publicação da Google Play Store e Apple App Store.</td></tr>
  <tr><td><strong>Prioridade</strong></td><td>10</td></tr>
  <tr><td><strong>Conflitos</strong></td><td>Nenhum.</td></tr>
  <tr><td><strong>História</strong></td><td>20/10/2025</td></tr>
</table>
</center>

</div>

<font size="2"><p style="text-align: center">Autor: [Breno Teixeira](https://github.com/BrenoLTeixeira)</p></font>

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 12:</b> Requisito Não Funcional – RNF07</p></font>

<a name="RNF07"></a>

<center>
<table border="1" cellpadding="6" cellspacing="0">
  <tr><th colspan="2">Requisito Não Funcional – RNF07</th></tr>
  <tr><td><strong>Classificação</strong></td><td>Acessibilidade</td></tr>
  <tr><td><strong>Descrição</strong></td><td>O aplicativo deve possuir recursos de acessibilidade (alto contraste, leitura de tela, voz e Libras).</td></tr>
  <tr><td><strong>Justificativa</strong></td><td>Garantir que jovens com deficiência (visual, auditiva, etc.) possam acessar e utilizar o aplicativo plenamente, em conformidade com as leis de inclusão digital (como a LBI).</td></tr>
  <tr><td><strong>Origem do Requisito</strong></td><td>BS20, IDJ09</td></tr>
  <tr><td><strong>Critério de Aceitação</strong></td><td>O aplicativo deve ser 100% navegável e funcional utilizando leitores de tela (TalkBack, VoiceOver).<br>- Deve oferecer um modo de alto contraste.<br>- As principais funcionalidades devem ter suporte (vídeo ou ícone) para Libras.</td></tr>
s <tr><td><strong>Dependências</strong></td><td>APIs de acessibilidade nativas do Android e iOS.</td></tr>
  <tr><td><strong>Prioridade</strong></td><td>8</td></tr>
  <tr><td><strong>Conflitos</strong></td><td>Pode aumentar a complexidade do design da interface (UI) e o tempo de desenvolvimento.</td></tr>
  <tr><td><strong>História</strong></td><td>20/10/2025</td></tr>
</table>
</center>

</div>

<font size="2"><p style="text-align: center">Autor: [Breno Teixeira](https://github.com/BrenoLTeixeira)</p></font>


## Referências Bibliográficas

## Histórico de Versão
| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :----: | :--------: | :------------------: | :----------------------------------------------------------------------------------------: | :-------------------------------------------: |
| `1.0` | 19/10/2025 | Criação inicial do documento de NFR | [Arthur Fernandes](https://github.com/arthurfernandesj) | [Dylan Cavalvante ](https://github.com/dylancavalcante) |
| `1.1` | 19/10/2025 |  | [Arthur Fernandes](https://github.com/arthurfernandesj) | [Dylan Cavalvante ](https://github.com/dylancavalcante) |
| `1.2` | 20/10/2025 | Adição dos cartões RNF04 e RNF07. | [Breno Teixeira](https://github.com/BrenoLTeixeira) | [ Arthur Fernandes ](https://github.com/arthurfernandesj) |