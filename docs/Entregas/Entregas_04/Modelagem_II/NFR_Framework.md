# NFR Framework

## Introdução

No contexto do desenvolvimento do aplicativo ID Jovem, os [Requisitos Não-Funcionais (RNFs)]() desempenham um papel essencial ao definir qualidades e restrições que afetam diretamente a experiência do jovem beneficiário, a segurança dos dados, o desempenho e a conformidade com as legislações vigentes. Dentre esses requisitos, destaca-se a importância de garantir a proteção das informações pessoais e a confiabilidade na emissão e validação da Identidade Jovem.

Com o objetivo de representar e analisar esses requisitos de maneira estruturada, este trabalho adota o NFR Framework, uma abordagem proposta por [Chung et al. (2000)](). Esse framework possibilita a modelagem dos RNFs por meio de *softgoals*, que representam objetivos qualitativos sem critérios de satisfação exatos, mas fundamentais para a qualidade do produto. 

A representação gráfica desses *softgoals* é feita através de um grafo SIG (Softgoal Interdependency Graph), que evidencia suas interdependências, influências e possíveis conflitos. Assim, o NFR Framework aplicado ao ID Jovem contribui para o fortalecimento da usabilidade, segurança, confiabilidade e acessibilidade do aplicativo, assegurando que os jovens beneficiários utilizem a plataforma de forma prática e segura.

## SIG - Softgoal Interdependency Graph

O NFR Framework funciona por meio da construção e análise de um grafo chamado Softgoal Interdependency Graph (SIG), que representa graficamente os Requisitos Não-Funcionais (softgoals), suas interdependências, alternativas e justificativas. Esse grafo permite avaliar se os requisitos de alto nível foram atendidos e apoia decisões de projeto voltadas à melhoria do aplicativo ID Jovem.

### Tipos de SIG

O SIG é dividido em três tipos principais:

- Softgoals NFR: representam alternativas técnicas e soluções práticas (como processos, restrições ou estruturas) para atender aos softgoals do aplicativo ID Jovem — por exemplo, garantir desempenho adequado ao emitir o cartão digital.

- Softgoals de Operacionalização: representam os softgoals e suas interdependências, permitindo identificar conflitos e sinergias, como a relação entre acessibilidade e desempenho no uso do app.

- Softgoals de Afirmação: trazem justificativas baseadas em características do domínio do ID Jovem (como requisitos de segurança e prioridade de acesso), apoiando decisões e rastreabilidade do sistema.

<font size="3"><p style="text-align: center">Figura 1: Tipos de Softgoal</p></font>

![Figura 1](../../../assets/NFR/imagem1.png)

<font size="2"><p style="text-align: center">Fonte: [SILVA, 2019]()</p></font>

### Tipos e Interdependências de Softgoals no NFR Framework

- O NFR Framework utiliza três tipos de *softgoals*, representados por diferentes estilos de nuvens:
  - Softgoals NFR: nuvens claras  
  - Softgoals de Operacionalização: nuvens com linhas grossas  
  - Softgoals de Afirmação: nuvens com linhas tracejadas  

- Cada *softgoal NFR* possui um tipo (ex: Usabilidade) e um tópico (ex: Interface do Usuário), que indicam a parte específica do aplicativo ID Jovem à qual se referem.

- As interdependências entre os *softgoals* são classificadas em:
  - Refinamentos (top-down), onde um *softgoal* pai gera filhos mais específicos, podendo ser:
    - Decomposição de Softgoal NFR: divide um requisito não-funcional em outros mais detalhados, como dividir “Confiabilidade” em “Disponibilidade” e “Segurança”.
    - Decomposição de Operacionalização: refina soluções implementáveis, como criptografia de dados ou autenticação do beneficiário.
    - Decomposição de Afirmação: detalha justificativas de projeto, como priorizar o acesso rápido mesmo em conexões móveis limitadas.
    - Priorização: refina um *softgoal* destacando sua importância dentro do aplicativo, como dar prioridade à acessibilidade sobre o desempenho visual.

Essa estrutura permite representar, refinar e justificar de forma clara os requisitos não-funcionais que impactam diretamente a qualidade e a confiabilidade do aplicativo ID Jovem, garantindo que o sistema cumpra seu propósito social com eficiência e segurança.

<font size="3"><p style="text-align: center">Figura 2: Tipos e Interdependências de Softgoals no NFR Framework</p></font>

![Figura 2](../../../assets/NFR/imagem2.png) 

<font size="2"><p style="text-align: center">Fonte: [SILVA, 2019]()</p></font>


### Contribuições e Tipos no NFR Framework

- Durante o refinamento dos *softgoals*, um *softgoal* descendente pode contribuir positiva ou negativamente, de forma total ou parcial, para a satisfação do *softgoal* ascendente.
- A satisfação de softgoal indica que o requisito não-funcional deve ser atendido dentro de limites aceitáveis, o que é essencial no ID Jovem, pois certos aspectos (como desempenho e segurança) podem influenciar-se mutuamente.

- AND: todos os descendentes precisam ser satisfeitos para o ascendente ser satisfeito (ex: para alcançar “Segurança”, é necessário satisfazer “Criptografia” e “Validação de Identidade”).  
- OR: basta um descendente satisfeito para o ascendente ser satisfeito (ex: “Autenticação” pode ser feita via CPF ou QR Code).  
- MAKE (++): contribuição altamente positiva; a satisfação do descendente garante a satisfação do ascendente.  
- BREAK (--): contribuição altamente negativa; a satisfação do descendente prejudica o ascendente.  
- HELP (+): contribuição parcialmente positiva; satisfação parcial do descendente contribui parcialmente para o ascendente.  
- HURT (-): contribuição parcialmente negativa; satisfação do descendente prejudica parcialmente o ascendente.  
- UNKNOWN (?): contribuição desconhecida, pode ser positiva ou negativa.  
- EQUALS: o descendente só é satisfeito se o ascendente for satisfeito.  
- SOME: há um sinal conhecido (positivo ou negativo), mas o grau da contribuição é incerto.

Essas contribuições permitem entender como decisões técnicas no ID Jovem (como escolha de layout, autenticação e performance) afetam a satisfação global dos requisitos de qualidade do sistema.

---

### Procedimento de Avaliação no NFR Framework

- O procedimento de avaliação determina o grau em que os requisitos não-funcionais (*softgoals*) são satisfeitos por um conjunto de decisões de projeto.  
- Cada *softgoal* ou interdependência do Softgoal Interdependency Graph (SIG) recebe um rótulo que indica seu status de satisfação.  

#### Tipos de rótulos usados:

- ✓ (satisfeito): O requisito é plenamente atendido.  
- 𝒲+ (fracamente satisfeito): Atendido parcialmente; impacto positivo moderado.  
- X (negado): O requisito não é atendido.  
- 𝒲- (fracamente negado): Negação parcial; impacto negativo brando.  
- 🗲 (conflitante): Há conflito entre requisitos, coexistindo aspectos positivos e negativos.  
- u (indeterminado): Não há dados suficientes para determinar o impacto.

No contexto do ID Jovem, essa avaliação permite verificar, por exemplo, se as melhorias na usabilidade não comprometem a segurança dos dados, garantindo um equilíbrio entre experiência do usuário e conformidade com os requisitos legais e técnicos.

A avaliação é feita de forma hierárquica:
- Inicia-se pelos *softgoals* de nível mais baixo, relacionados a decisões específicas (como design de tela ou criptografia).
- Em seguida, os rótulos são propagados para os níveis superiores, avaliando o impacto cumulativo até os *softgoals* de alto nível (como “Confiabilidade” e “Segurança da Informação”).

<font size="3"><p style="text-align: center">Figura 3: Procedimento de Avaliação no NFR Framework</p></font>

![Figura 3](../../../assets/NFR/procedimento.png)


<font size="2"><p style="text-align: center">Fonte: [SILVA, 2019]()</p></font>



## Metodologia

Para aplicar o NFR Framework ao desenvolvimento do aplicativo, adotamos uma abordagem em etapas estruturadas, com o objetivo de identificar, modelar, analisar e tomar decisões relacionadas aos requisitos não funcionais (softgoals) do sistema. A metodologia compreende as seguintes fases:

### 1. Identificação dos Requisitos Não Funcionais (Softgoals)

Nesta etapa, foram identificados os principais requisitos não funcionais relevantes ao contexto do aplicativo, como:

- Usabilidade  
- Desempenho  
- Segurança  
- Acessibilidade  
- Confiabilidade  
- Portabilidade

Essa identificação foi baseada em entrevistas com stakeholders, análise de mercado e levantamento de requisitos funcionais relacionados. Os requisitos não funcionais são representados como softgoals, que expressam intenções qualitativas sem critérios rígidos de satisfação.

### 2. Modelagem com o NFR Framework

A modelagem foi realizada utilizando a notação proposta por [*Chung et al. (2000)*](), representando os softgoals em uma estrutura hierárquica com relacionamentos de contribuição entre eles. Foram utilizados os seguintes tipos de contribuição:

- MAKE (++)
- HELP (+)
- HURT (-)
- BREAK (--)
- OR
- AND
- EQUALS
- UNKNOWN (?)
- SOME


Também foram especificadas as operacionalizações, ou seja, decisões de projeto que implementam cada softgoal.

#### Uso do Cartão de Especificação

Durante essa fase de modelagem, utilizou-se o Cartão de Especificação como instrumento de apoio à documentação e análise. Cada cartão foi preenchido com os seguintes elementos:

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
  <tr><td><strong>Classificação</strong></td><td>	Classificação do RNF conforme a hierarquia do catálogo.</td></tr>
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


O cartão facilitou a rastreabilidade, clareza e consistência das informações, além de permitir uma análise comparativa entre alternativas e apoiar a comunicação com os stakeholders durante a modelagem dos requisitos.

### 3. Avaliação dos Softgoals

Após modelar os softgoals e suas contribuições, foi realizado o procedimento de avaliação, no qual cada softgoal recebeu um rótulo indicando o grau de satisfação:

- `✓` Satisfeito: Requisito não funcional plenamente atendido.  
- `𝒲+` Fracamente satisfeito: Satisfação parcial.  
- `X` Negado: Requisito contradiz outro.  
- `𝒲-` Fracamente negado: Impacto negativo moderado.  
- `🗲` Conflitante: Conflito entre requisitos.  
- `u` Indeterminado: Impacto incerto ou desconhecido.

A avaliação começou pelos softgoals de nível mais baixo (operacionalizações), subindo até os níveis superiores da hierarquia para analisar o impacto global das decisões.


### 4. Tomada de Decisão

Com base nas análises e rótulos atribuídos, foram tomadas decisões de projeto priorizando as alternativas que maximizassem a satisfação dos softgoals mais críticos.  
Em casos de conflito (por exemplo, Desempenho vs. Segurança), foram realizadas ponderações junto aos stakeholders, buscando o melhor compromisso entre eficiência e proteção dos dados do usuário.

---

### 5. Validação

A etapa de validação da modelagem seguiu duas vertentes principais:

- Rastreabilidade com as histórias de usuário:  
  Verificou-se se os *softgoals* contemplavam os desejos e expectativas expressas por cada persona.  

- Análise de cobertura:  
  Avaliou-se se os principais atributos de qualidade esperados para um aplicativo público financeiro — como disponibilidade, desempenho e segurança — foram devidamente modelados.

Essa validação assegurou que os requisitos não funcionais fossem não apenas documentados, mas também rastreáveis, justificáveis e compatíveis com os requisitos funcionais do ID Jovem.

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
      <td><a href="https://github.com/BrenoLTeixeira">Breno Lourenço</a></td>
      <td>xx/10/2025</td>
      <td>00:00</td>
    </tr>
    <tr>
      <td><a href="https://github.com/dylancavalcante">Dylan Cavalcante</a></td>
      <td>xx/10/2025</td>
      <td>00:00</td>
    </tr>
    <tr>
      <td><a href="https://github.com/eduardar0">Eduarda Domingos</a></td>
      <td>xx/10/2025</td>
      <td>00:00</td>
    </tr>
    <tr>
      <td><a href="https://github.com/GiovanaFontesS">Giovana Fontes</a></td>
      <td>20/10/2025</td>
      <td>07:10</td>
    </tr>
    <tr>
      <td><a href="https://github.com/leticialopes20">Letícia Lopes</a></td>
      <td>xx/10/2025</td>
      <td>00:00</td>
    </tr>
  </tbody>
</table>
</div>

<p style="text-align: center; font-size: 10pt;">Fonte: <a href="https://github.com/arthurfernandesj">Arthur Fernandes</a></p>

### Requisitos Não-Funcionais

<font size="3"><p style="text-align: center">Tabela 3: Requisitos Não-Funcionais utilizados na criação do NFR Framework</p></font>

| Código | Versão | Descrição                                                                                          | Origem |
|------------|------------|--------------------------------------------------------------------------------------------------------|------------|
| <a name="rnf06"></a>[RNF06](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf06)  | 1.0 | O aplicativo deve funcionar com baixo consumo de internet e ser acessível em regiões carentes | [BS24](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming)|
|<a name="rnf07"></a> [RNF07](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf07)  | 1.0 |	O aplicativo deve possuir recursos de acessibilidade (alto contraste, leitura de tela, voz e Libras)| [BS20](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming), [IDJ09](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspecção/) |
|<a name="rnf08"></a>[RNF08](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf08) | 1.0 | 	O sistema deve garantir disponibilidade mínima de 99,5% | [RNF-CON-01](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf08)  |
|<a name="rnf10"></a>[RNF10](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf10) | 1.0 | O tempo de carregamento das páginas do site oficial não deve exceder 3 segundos em conexões de internet de baixa velocidade | [ADD - Desempenho](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Analise_de_Documentos/) |
|<a name="rnf11"></a>[RNF11](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf11) | 1.0 | O aplicativo deve garantir que as informações sobre os benefícios estejam 100% sincronizadas com a base de dados oficial|  [ADD - Confiabilidade](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Analise_de_Documentos/) |
|<a name="rnf12"></a>[RNF12](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf12) | 1.0 | O sistema deve ser compatível com as duas versões anteriores dos principais navegadores web e sistemas operacionais móveis|  [ADD - Suportabilidade](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Analise_de_Documentos/) |
|<a name="rnf13"></a>[RNF13](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf13) | 1.0 |A navegação entre as seções do aplicativo deve ser consistente e previsível para o jovem beneficiário |  [ADD - Usabilidade](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Analise_de_Documentos/) |
|<a name="rnf14"></a>[RNF14](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf14) | 1.0 |O aplicativo deve apresentar um feedback visual e sonoro claro para cada interação do jovem beneficiário | [BS26](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming) |
|<a name="rnf15"></a>[RNF15](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf15) | 1.0 |	O sistema deve ter um tempo máximo de inatividade de 2 horas por mês, fora das janelas de manutenção programada |  [BS27](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming)  |
|<a name="rnf16"></a>[RNF16](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf16) | 1.0 |	O tempo de resposta para validação da carteirinha (QR Code) não deve exceder 2 segundos |[BS28](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming) |
|<a name="rnf17"></a>[RNF17](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf17) | 1.0 |A equipe de desenvolvimento deve disponibilizar atualizações de segurança e correções de bugs em um ciclo de, no máximo, 3 meses | [BS29](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming) |
|<a name="rnf18"></a>[RNF18](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf18) | 1.0 | O aplicativo deve permitir que o jovem beneficiário personalize o tamanho da fonte e o esquema de cores para melhorar a legibilidade	 | [IDJ18](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspecção/) |
|<a name="rnf19"></a>[RNF19](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf19) | 1.0 |O sistema deve registrar todas as tentativas de validação da carteira, bem-sucedidas ou não, para fins de auditoria |  [IDJ19](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspecção/)  |
|<a name="rnf20"></a>[RNF20](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf20) | 1.0 | 	A consulta à elegibilidade do CadÚnico deve retornar o resultado em no máximo 3 segundos|  [IDJ20](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspecção/) |
|<a name="rnf21"></a>[RNF21](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf21) | 1.0 | 	O sistema deve ter capacidade de ser facilmente escalado para atender a um aumento de 50% no número de jovens beneficiários sem degradação do desempenho| [IDJ21](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspecção/) |
|<a name="rnf22"></a>[RNF22](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf22) | 1.0 | O sistema deve manter um log de auditoria de todas as emissões e validações de carteirinhas por 5 anos| [ST12](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Storytelling/) |
|<a name="rnf23"></a>[RNF23](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf23) | 1.0 | O aplicativo deve carregar as informações de eventos e parceiros em no máximo 3 segundos, mesmo com grande volume de dados | [ST13](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Storytelling/) |
|<a name="rnf"></a>[RNF24](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf24) | 1.0 | O aplicativo deve ser compatível com a API mais recente e as duas versões anteriores do sistema operacional móvel |  [ST14](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Storytelling/)|

<font size="2"><p style="text-align: center">Fontes: [Letícia Lopes](https://github.com/leticialopes20) e [Arthur Fernandes](https://github.com/arthurfernandesj), 2025</p></font>



## Cartão Especificação


<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 4:</b> Requisito Não Funcional – RNF06</p></font>



<center>
<table border="1" cellpadding="6" cellspacing="0">
  <tr><th colspan="2"><a name="RNF06"></a>Requisito Não Funcional – <a href="#rnf06">RNF06</a></th></tr>
  <tr><td><strong>Classificação</strong></td><td></td></tr>
  <tr><td><strong>Descrição</strong></td><td></td></tr>
  <tr><td><strong>Justificativa</strong></td><td></td></tr>
  <tr><td><strong>Origem do Requisito</strong></td><td></td></tr>
  <tr><td><strong>Critério de Aceitação</strong></td><td></td></tr>
  <tr><td><strong>Dependências</strong></td><td></td></tr>
  <tr><td><strong>Prioridade</strong></td><td></td></tr>
  <tr><td><strong>Conflitos</strong></td><td></td></tr>
  <tr><td><strong>História</strong></td><td></td></tr>
</table>
</center>
</div>

<font size="2"><p style="text-align: center">Fonte: [Arthur Fernandes](https://github.com/arthurfernandesj)</p></font>



<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 5:</b> Requisito Não Funcional – RNF07</p></font>


<center>
<table border="1" cellpadding="6" cellspacing="0">
  <tr><th colspan="2"><a name="RNF07"></a>Requisito Não Funcional – <a href="#rnf07">RNF07</a></th></tr>
  <tr><td><strong>Classificação</strong></td><td></td></tr>
  <tr><td><strong>Descrição</strong></td><td></td></tr>
  <tr><td><strong>Justificativa</strong></td><td></td></tr>
  <tr><td><strong>Origem do Requisito</strong></td><td></td></tr>
  <tr><td><strong>Critério de Aceitação</strong></td><td></td></tr>
  <tr><td><strong>Dependências</strong></td><td></td></tr>
  <tr><td><strong>Prioridade</strong></td><td></td></tr>
  <tr><td><strong>Conflitos</strong></td><td></td></tr>
  <tr><td><strong>História</strong></td><td></td></tr>
</table>
</center>

</div>

<font size="2"><p style="text-align: center">Fonte: [Arthur Fernandes](https://github.com/arthurfernandesj)</p></font>

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 6:</b> Requisito Não Funcional – RNF08</p></font>


<center>
<table border="1" cellpadding="6" cellspacing="0">
  <tr><th colspan="2"><a name="RNF08"></a>Requisito Não Funcional – <a href="#rnf08">RNF08</a></th></tr>
  <tr><td><strong>Classificação</strong></td><td></td></tr>
  <tr><td><strong>Descrição</strong></td><td></td></tr>
  <tr><td><strong>Justificativa</strong></td><td></td></tr>
  <tr><td><strong>Origem do Requisito</strong></td><td></td></tr>
  <tr><td><strong>Critério de Aceitação</strong></td><td></td></tr>
  <tr><td><strong>Dependências</strong></td><td></td></tr>
  <tr><td><strong>Prioridade</strong></td><td></td></tr>
  <tr><td><strong>Conflitos</strong></td><td></td></tr>
  <tr><td><strong>História</strong></td><td></td></tr>
</table>
</center>

</div>

<font size="2"><p style="text-align: center">Fonte: [Arthur Fernandes](https://github.com/arthurfernandesj)</p></font>
<div align="center">

<font size="3"><p style="text-align: center"><b>Tabela 7:</b> Requisito Não Funcional – RNF10</p></font>


<center>
<table border="1" cellpadding="6" cellspacing="0">
  <tr><th colspan="2"><a name="RNF10"></a>Requisito Não Funcional – <a href="#rnf10">RNF10</a></th></tr>
  <tr><td><strong>Classificação</strong></td><td></td></tr>
  <tr><td><strong>Descrição</strong></td><td></td></tr>
  <tr><td><strong>Justificativa</strong></td><td></td></tr>
  <tr><td><strong>Origem do Requisito</strong></td><td></td></tr>
  <tr><td><strong>Critério de Aceitação</strong></td><td></td></tr>
  <tr><td><strong>Dependências</strong></td><td></td></tr>
  <tr><td><strong>Prioridade</strong></td><td></td></tr>
  <tr><td><strong>Conflitos</strong></td><td></td></tr>
  <tr><td><strong>História</strong></td><td></td></tr>
</table>
</center>

</div>

<font size="2"><p style="text-align: center">Fonte: <a href="https://github.com/GiovanaFontesS">Giovana Fontes</a></p></font>

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 8:</b> Requisito Não Funcional – RNF11</p></font>

<center>
<table border="1" cellpadding="6" cellspacing="0">
  <tr><th colspan="2"><a name="RNF11"></a>Requisito Não Funcional – <a href="#rnf11">RNF11</a></th></tr>
  <tr><td><strong>Classificação</strong></td><td></td></tr>
  <tr><td><strong>Descrição</strong></td><td></td></tr>
  <tr><td><strong>Justificativa</strong></td><td></td></tr>
  <tr><td><strong>Origem do Requisito</strong></td><td></td></tr>
  <tr><td><strong>Critério de Aceitação</strong></td><td></td></tr>
  <tr><td><strong>Dependências</strong></td><td></td></tr>
  <tr><td><strong>Prioridade</strong></td><td></td></tr>
  <tr><td><strong>Conflitos</strong></td><td></td></tr>
  <tr><td><strong>História</strong></td><td></td></tr>
</table>
</center>

</div>

<font size="2"><p style="text-align: center">Fonte: <a href="https://github.com/GiovanaFontesS">Giovana Fontes</a></p></font>

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 9:</b> Requisito Não Funcional – RNF12</p></font>


<center>
<table border="1" cellpadding="6" cellspacing="0">
  <tr><th colspan="2"><a name="RNF12"></a>Requisito Não Funcional – <a href="#rnf12">RNF12</a></th></tr>
  <tr><td><strong>Classificação</strong></td><td></td></tr>
  <tr><td><strong>Descrição</strong></td><td></td></tr>
  <tr><td><strong>Justificativa</strong></td><td></td></tr>
  <tr><td><strong>Origem do Requisito</strong></td><td></td></tr>
  <tr><td><strong>Critério de Aceitação</strong></td><td></td></tr>
  <tr><td><strong>Dependências</strong></td><td></td></tr>
  <tr><td><strong>Prioridade</strong></td><td></td></tr>
  <tr><td><strong>Conflitos</strong></td><td></td></tr>
  <tr><td><strong>História</strong></td><td></td></tr>
</table>
</center>

</div>

<font size="2"><p style="text-align: center">Fonte: <a href="https://github.com/GiovanaFontesS">Giovana Fontes</a></p></font>

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 10:</b> Navegação entre seções do aplicativo consistente e previsível para o Jovem Beneficiário</p></font>


<center>
<table border="1" cellpadding="6" cellspacing="0">
  <tr><th colspan="2"><a name="RNF13"></a>Requisito Não Funcional – <a href="#rnf13">RNF13</a></th></tr>
  <tr><td><strong>Classificação</strong></td><td>Usabilidade</td></tr>
  <tr><td><strong>Descrição</strong></td><td>A navegação entre as seções do aplicativo deve ser consistente e previsível para o jovem beneficiário.</td></tr>
  <tr><td><strong>Justificativa</strong></td><td>Uma navegação previsível e uniforme melhora a experiência do usuário e reduz a curva de aprendizado no uso do aplicativo.</td></tr>
  <tr><td><strong>Origem do Requisito</strong></td><td><a href="https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Analise_de_Documentos/">ADD - Usabilidade</a></td></tr>
  <tr><td><strong>Critério de Aceitação</strong></td><td>O jovem beneficiário deve conseguir identificar facilmente onde está e retornar à página inicial sem dificuldade em até dois cliques.</td></tr>
  <tr><td><strong>Dependências</strong></td><td>Framework de UI consistente, padrões de design system, componentes de navegação unificados</td></tr>
  <tr><td><strong>Prioridade</strong></td><td>8</td></tr>
  <tr><td><strong>Conflitos</strong></td><td>Possível conflito com <a href="#rnf10">RNF10</a> se a navegação complexa impactar tempo de carregamento</td></tr>
  <tr><td><strong>História</strong></td><td>20/10/2025</td></tr>
</table>
</center>

</div>

<font size="2"><p style="text-align: center">Fonte: <a href="https://github.com/leticialopes20">Letícia Lopes </a></p></font>

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 11:</b> Apresentação de feedback visual e sonoro claros para cada interação do Jovem Beneficiário no aplicativo</p></font>


<center>
<table border="1" cellpadding="6" cellspacing="0">
  <tr><th colspan="2"><a name="RNF14"></a>Requisito Não Funcional – <a href="#rnf14">RNF14</a></th></tr>
  <tr><td><strong>Classificação</strong></td><td>Usabilidade / Acessibilidade</td></tr>
  <tr><td><strong>Descrição</strong></td><td>O aplicativo deve apresentar um feedback visual e sonoro claro para cada interação do jovem beneficiário.</td></tr>
  <tr><td><strong>Justificativa</strong></td><td>Feedback imediato e claro aumenta a confiança do usuário no sistema e confirma que as ações foram reconhecidas e processadas.</td></tr>
  <tr><td><strong>Origem do Requisito</strong></td><td><a href="https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming">BS26</a></td></tr>
  <tr><td><strong>Critério de Aceitação</strong></td><td>Todas as interações do usuário (cliques, toques, envios) devem gerar feedback visual ou sonoro dentro de 500ms.</td></tr>
  <tr><td><strong>Dependências</strong></td><td>Bibliotecas de animação, componentes de feedback visual, APIs de áudio nativas</td></tr>
  <tr><td><strong>Prioridade</strong></td><td>7</td></tr>
  <tr><td><strong>Conflitos</strong></td><td>Pode impactar <a href="#rnf06">RNF06</a> se os recursos de feedback consumirem muitos dados</td></tr>
  <tr><td><strong>História</strong></td><td>20/10/2025</td></tr>
</table>
</center>

</div>

<font size="2"><p style="text-align: center">Fonte: <a href="https://github.com/leticialopes20">Letícia Lopes </a></p></font>

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 12:</b> Tempo Máximo de inatividade de 2 horas por mês, fora das janelas de manutenção programada</p></font>


<center>
<table border="1" cellpadding="6" cellspacing="0">
  <tr><th colspan="2"><a name="RNF15"></a>Requisito Não Funcional – <a href="#rnf15">RNF15</a></th></tr>
  <tr><td><strong>Classificação</strong></td><td>Confiabilidade</td></tr>
  <tr><td><strong>Descrição</strong></td><td>O sistema deve ter um tempo máximo de inatividade de 2 horas por mês, fora das janelas de manutenção programada.</td></tr>
  <tr><td><strong>Justificativa</strong></td><td>Garantir que o aplicativo esteja disponível quando o jovem beneficiário precisar acessar seus benefícios e carteirinha digital.</td></tr>
  <tr><td><strong>Origem do Requisito</strong></td><td><a href="https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming">BS27</a></td></tr>
  <tr><td><strong>Critério de Aceitação</strong></td><td>Monitoramento mensal deve comprovar disponibilidade de 99,72% ou superior (máximo 2 horas de indisponibilidade mensal)</td></tr>
  <tr><td><strong>Dependências</strong></td><td> Infraestrutura de alta disponibilidade, sistemas de load balancing, monitoramento contínuo</td></tr>
  <tr><td><strong>Prioridade</strong></td><td>9</td></tr>
  <tr><td><strong>Conflitos</strong></td><td>Pode conflitar com <a href="#rnf17">RNF17</a> se as manutenções exigirem tempo de inatividade adicional</td></tr>
  <tr><td><strong>História</strong></td><td>20/10/2025</td></tr>
</table>
</center>

</div>

<font size="2"><p style="text-align: center">Fonte: <a href="https://github.com/leticialopes20">Letícia Lopes </a></p></font>


<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 13:</b> Requisito Não Funcional – RNF16</p></font>


<center>
<table border="1" cellpadding="6" cellspacing="0">
  <tr><th colspan="2"><a name="RNF16"></a>Requisito Não Funcional – <a href="#rnf16">RNF16</a></th></tr>
  <tr><td><strong>Classificação</strong></td><td></td></tr>
  <tr><td><strong>Descrição</strong></td><td></td></tr>
  <tr><td><strong>Justificativa</strong></td><td></td></tr>
  <tr><td><strong>Origem do Requisito</strong></td><td></td></tr>
  <tr><td><strong>Critério de Aceitação</strong></td><td></td></tr>
  <tr><td><strong>Dependências</strong></td><td></td></tr>
  <tr><td><strong>Prioridade</strong></td><td></td></tr>
  <tr><td><strong>Conflitos</strong></td><td></td></tr>
  <tr><td><strong>História</strong></td><td></td></tr>
</table>
</center>

</div>

<font size="2"><p style="text-align: center">Fonte: <a href="https://github.com/eduardar0">Eduarda Domingos </a></p></font>

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 14:</b> Requisito Não Funcional – RNF17</p></font>

<center>
<table border="1" cellpadding="6" cellspacing="0">
  <tr><th colspan="2"><a name="RNF17"></a>Requisito Não Funcional – <a href="#rnf17">RNF17</a></th></tr>
  <tr><td><strong>Classificação</strong></td><td></td></tr>
  <tr><td><strong>Descrição</strong></td><td></td></tr>
  <tr><td><strong>Justificativa</strong></td><td></td></tr>
  <tr><td><strong>Origem do Requisito</strong></td><td></td></tr>
  <tr><td><strong>Critério de Aceitação</strong></td><td></td></tr>
  <tr><td><strong>Dependências</strong></td><td></td></tr>
  <tr><td><strong>Prioridade</strong></td><td></td></tr>
  <tr><td><strong>Conflitos</strong></td><td></td></tr>
  <tr><td><strong>História</strong></td><td></td></tr>
</table>
</center>

</div>

<font size="2"><p style="text-align: center">Fonte: <a href="https://github.com/eduardar0">Eduarda Domingos </a></p></font>

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 15:</b> Requisito Não Funcional – RNF18</p></font>


<center>
<table border="1" cellpadding="6" cellspacing="0">
  <tr><th colspan="2"><a name="RNF18"></a>Requisito Não Funcional – <a href="#rnf18">RNF18</a></th></tr>
  <tr><td><strong>Classificação</strong></td><td></td></tr>
  <tr><td><strong>Descrição</strong></td><td></td></tr>
  <tr><td><strong>Justificativa</strong></td><td></td></tr>
  <tr><td><strong>Origem do Requisito</strong></td><td></td></tr>
  <tr><td><strong>Critério de Aceitação</strong></td><td></td></tr>
  <tr><td><strong>Dependências</strong></td><td></td></tr>
  <tr><td><strong>Prioridade</strong></td><td></td></tr>
  <tr><td><strong>Conflitos</strong></td><td></td></tr>
  <tr><td><strong>História</strong></td><td></td></tr>
</table>
</center>

</div>

<font size="2"><p style="text-align: center">Fonte: <a href="https://github.com/eduardar0">Eduarda Domingos </a></p></font>

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 16:</b> Requisito Não Funcional – RNF19</p></font>


<center>
<table border="1" cellpadding="6" cellspacing="0">
  <tr><th colspan="2"><a name="RNF19"></a>Requisito Não Funcional – <a href="#rnf19">RNF19</a></th></tr>
  <tr><td><strong>Classificação</strong></td><td></td></tr>
  <tr><td><strong>Descrição</strong></td><td></td></tr>
  <tr><td><strong>Justificativa</strong></td><td></td></tr>
  <tr><td><strong>Origem do Requisito</strong></td><td></td></tr>
  <tr><td><strong>Critério de Aceitação</strong></td><td></td></tr>
  <tr><td><strong>Dependências</strong></td><td></td></tr>
  <tr><td><strong>Prioridade</strong></td><td></td></tr>
  <tr><td><strong>Conflitos</strong></td><td></td></tr>
  <tr><td><strong>História</strong></td><td></td></tr>
</table>
</center>

</div>

<font size="2"><p style="text-align: center">Fonte: <a href="https://github.com/dylancavalcante">Dylan Cavalcante </a></p></font>

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 17:</b> Requisito Não Funcional – RNF20</p></font>


<center>
<table border="1" cellpadding="6" cellspacing="0">
  <tr><th colspan="2"><a name="RNF20"></a>Requisito Não Funcional – <a href="#rnf20">RNF20</a></th></tr>
  <tr><td><strong>Classificação</strong></td><td></td></tr>
  <tr><td><strong>Descrição</strong></td><td></td></tr>
  <tr><td><strong>Justificativa</strong></td><td></td></tr>
  <tr><td><strong>Origem do Requisito</strong></td><td></td></tr>
  <tr><td><strong>Critério de Aceitação</strong></td><td></td></tr>
  <tr><td><strong>Dependências</strong></td><td></td></tr>
  <tr><td><strong>Prioridade</strong></td><td></td></tr>
  <tr><td><strong>Conflitos</strong></td><td></td></tr>
  <tr><td><strong>História</strong></td><td></td></tr>
</table>
</center>

</div>

<font size="2"><p style="text-align: center">Fonte: <a href="https://github.com/dylancavalcante">Dylan Cavalcante </a></p></font>

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 18:</b> Requisito Não Funcional – RNF21</p></font>


<center>
<table border="1" cellpadding="6" cellspacing="0">
  <tr><th colspan="2"><a name="RNF21"></a>Requisito Não Funcional – <a href="#rnf21">RNF21</a></th></tr>
  <tr><td><strong>Classificação</strong></td><td></td></tr>
  <tr><td><strong>Descrição</strong></td><td></td></tr>
  <tr><td><strong>Justificativa</strong></td><td></td></tr>
  <tr><td><strong>Origem do Requisito</strong></td><td></td></tr>
  <tr><td><strong>Critério de Aceitação</strong></td><td></td></tr>
  <tr><td><strong>Dependências</strong></td><td></td></tr>
  <tr><td><strong>Prioridade</strong></td><td></td></tr>
  <tr><td><strong>Conflitos</strong></td><td></td></tr>
  <tr><td><strong>História</strong></td><td></td></tr>
</table>
</center>

</div>

<font size="2"><p style="text-align: center">Fonte: <a href="https://github.com/dylancavalcante">Dylan Cavalcante </a></p></font>


<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 19:</b> Requisito Não Funcional – RNF22</p></font>


<center>
<table border="1" cellpadding="6" cellspacing="0">
  <tr><th colspan="2"><a name="RNF22"></a>Requisito Não Funcional – <a href="#rnf22">RNF22</a></th></tr>
  <tr><td><strong>Classificação</strong></td><td></td></tr>
  <tr><td><strong>Descrição</strong></td><td></td></tr>
  <tr><td><strong>Justificativa</strong></td><td></td></tr>
  <tr><td><strong>Origem do Requisito</strong></td><td></td></tr>
  <tr><td><strong>Critério de Aceitação</strong></td><td></td></tr>
  <tr><td><strong>Dependências</strong></td><td></td></tr>
  <tr><td><strong>Prioridade</strong></td><td></td></tr>
  <tr><td><strong>Conflitos</strong></td><td></td></tr>
  <tr><td><strong>História</strong></td><td></td></tr>
</table>
</center>

</div>

<font size="2"><p style="text-align: center">Fonte: <a href="https://github.com/brenolteixeira">Breno Lourenço </a></p></font>

<div align="center">

 <a name="RNF23"></a><font size="3"><p style="text-align: center"><b>Tabela 20:</b> Requisito Não Funcional – RNF23</p></font>


<center>
<table border="1" cellpadding="6" cellspacing="0">
  <tr><th colspan="2"><a name="RNF23"></a>Requisito Não Funcional – <a href="#rnf23">RNF23</a></th></tr>
  <tr><td><strong>Classificação</strong></td><td></td></tr>
  <tr><td><strong>Descrição</strong></td><td></td></tr>
  <tr><td><strong>Justificativa</strong></td><td></td></tr>
  <tr><td><strong>Origem do Requisito</strong></td><td></td></tr>
  <tr><td><strong>Critério de Aceitação</strong></td><td></td></tr>
  <tr><td><strong>Dependências</strong></td><td></td></tr>
  <tr><td><strong>Prioridade</strong></td><td></td></tr>
  <tr><td><strong>Conflitos</strong></td><td></td></tr>
  <tr><td><strong>História</strong></td><td></td></tr>
</table>
</center>

</div>

<font size="2"><p style="text-align: center">Fonte: <a href="https://github.com/brenolteixeira">Breno Lourenço </a></p></font>

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 21:</b> Requisito Não Funcional – RNF24</p></font>


<center>
<table border="1" cellpadding="6" cellspacing="0">
  <tr><th colspan="2"><a name="RNF24"></a>Requisito Não Funcional –<a href="#rnf24">RNF24</a></th></tr>
  <tr><td><strong>Classificação</strong></td><td></td></tr>
  <tr><td><strong>Descrição</strong></td><td></td></tr>
  <tr><td><strong>Justificativa</strong></td><td></td></tr>
  <tr><td><strong>Origem do Requisito</strong></td><td></td></tr>
  <tr><td><strong>Critério de Aceitação</strong></td><td></td></tr>
  <tr><td><strong>Dependências</strong></td><td></td></tr>
  <tr><td><strong>Prioridade</strong></td><td></td></tr>
  <tr><td><strong>Conflitos</strong></td><td></td></tr>
  <tr><td><strong>História</strong></td><td></td></tr>
</table>
</center>

</div>

<font size="2"><p style="text-align: center">Fonte: <a href="https://github.com/brenolteixeira">Breno Lourenço </a></p></font>


## Referências Bibliográficas

> 1.</a> SILVA, Reinaldo Antônio da. NFR4ES: um catálogo de requisitos não-funcionais para sistemas embarcados. 2019. 154 f. Dissertação (Mestrado em Ciência da Computação) – Universidade Federal de Pernambuco, Recife, 2019.

> 2.</a> CHUNG, Lawrence; NIXON, Brian A.; YU, Eric; MYLLOPULOS, John. Non-functional requirements in software engineering. Springer Science & Business Media, 2000.


## Histórico de Versão
| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :----: | :--------: | :------------------: | :----------------------------------------------------------------------------------------: | :-------------------------------------------: |
| `1.0` | 19/10/2025 | Criação inicial do documento de NFR | [Arthur Fernandes](https://github.com/arthurfernandesj) | [Dylan Cavalvante ](https://github.com/dylancavalcante) |
| `1.1` | 19/10/2025 | Adição de Cartões de Especificação [RNF06](#RNF06), [RNF07](#RNF07), [RNF08](#RNF08)  | [Arthur Fernandes](https://github.com/arthurfernandesj) | [Dylan Cavalvante ](https://github.com/dylancavalcante) |
|`1.2` | 20/10/2025 |Adição de Cartões de Especificação [RNF10](#RNF10), [RNF11](#RNF11), [RNF12](#RNF12)  | [Giovana Fontes](https://github.com/GiovanaFontesS) |[Letícia Lopes](https://github.com/leticialopes20)
|`1.3` | 20/10/2025 | Adição de tabelas para todos os RNFS, adição de todos os RNFS na tabela 3, adição de hiperlinks na página | [Letícia Lopes](https://github.com/leticialopes20) | [Arthur Fernandes](https://github.com/arthurfernandesj)