# **Elos**

## **Introdução**

Os **elos de rastreabilidade** representam as conexões que estabelecem vínculos entre diferentes artefatos e atividades ao longo do ciclo de vida de um projeto ou sistema. No contexto do **ID Jovem**, esses elos permitem compreender a relação entre os requisitos definidos, as funcionalidades desenvolvidas e os testes realizados, assegurando que cada parte do sistema esteja alinhada aos objetivos do programa.

Por meio da rastreabilidade, é possível acompanhar a origem e a evolução de cada funcionalidade, verificar se os requisitos foram devidamente implementados e testados, registrar decisões importantes e identificar impactos de eventuais mudanças. Dessa forma, a criação e manutenção dos elos de rastreabilidade contribuem para uma **gestão mais eficiente, transparente e integrada** do desenvolvimento e manutenção do sistema <a id="TEC1" href="#RP1">[1]</a>.

<small><em>Revisado por [Chat GPT](https://chatgpt.com/share/6900b5f9-b0f4-8000-9e22-1c8d3e432359), em 28 de outubro de 2025</em></small>

### **Backward-from**

A **rastreabilidade backward-from** é um processo fundamental na engenharia de requisitos, responsável por estabelecer a ligação dos requisitos às suas fontes originais. Esse tipo de rastreabilidade é essencial para garantir que todos os requisitos identificados possuam uma origem bem definida, facilitando as etapas de validação e verificação ao longo do ciclo de vida do desenvolvimento do software.  

Além disso, a rastreabilidade backward-from contribui para o gerenciamento de mudanças, permitindo rastrear cada requisito de volta às suas bases. Dessa forma, qualquer modificação no sistema pode ser rapidamente associada à sua origem, assegurando uma resposta eficaz às alterações e mantendo a conformidade com os requisitos iniciais do projeto <a id="TEC1" href="#RP1">[1]</a>.  

---
<small><em>Revisado por [Chat GPT](https://chatgpt.com/share/6900b5f9-b0f4-8000-9e22-1c8d3e432359), em 28 de outubro de 2025</em></small>

### **Forward-from**

A **rastreabilidade forward-from** é um componente essencial na engenharia de requisitos, que permite a ligação dos requisitos aos artefatos subsequentes, como design, código, testes e documentação. Esse tipo de rastreabilidade é crucial para garantir que todos os requisitos sejam devidamente implementados, testados e validados ao longo do ciclo de vida do desenvolvimento do software.  

Além disso, a rastreabilidade forward-from facilita a gestão de mudanças, assegurando que qualquer modificação nos requisitos seja refletida de maneira consistente em todos os artefatos impactados. Isso garante que as atualizações sejam corretamente incorporadas e verificadas, mantendo a integridade e a conformidade do sistema em relação aos requisitos definidos inicialmente <a id="TEC2" href="#RP2">[2]</a>.  

## Metodologia

Baseamos a construção dos nossos cartões no modelo apresentado pelos professores **Milene Serrano** e **Maurício Serrano**, entre as páginas 22 e 27 dos slides <a id="RP3" href="#TEC3">[3]</a>. As **categorias** e **tipos de elos** adotados seguem o **Meta-modelo de Toranzo**. Embora o formato visual dos cartões seja semelhante ao dos exemplos apresentados, elaboramos cada um deles a partir dos **requisitos do projeto**, de modo que **cada cartão representa todos os tipos de elos associados ao requisito correspondente**.



### Cartões de Relacionamento dos Elos

<div align="center">
  <strong>Tabela 1 -</strong> Exemplo de cartão
</div>

<div align="center">
  <table>
    <tr>
      <td><strong>Categoria:</strong></td>
      <td>Implementação</td>
    </tr>
    <tr>
      <td><strong>Elementos Relacionados:</strong></td>
      <td>RE01, UC01, CE01, ENT01</td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from:</strong></td>
      <td>Agregação: RE01 ← ENT01 — O requisito foi identificado a partir da entrevista realizada.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from:</strong></td>
      <td>
        Satisfação: RE01 → CS01 — O requisito originou o caso de uso.<br>
        Satisfação: RE01 → CE01 — O requisito também deu origem ao cenário correspondente.
      </td>
    </tr>
  </table>
</div>


<font size="3"><p style="text-align: center">Autor: [Eduarda Domingos](https://github.com/eduardar0).</p></font>

### Legenda

- **Categoria**: Os cartões são divididos em quatro categorias principais:
  - **Ambiental**: Inclui informações provenientes do ambiente externo da organização que podem influenciar o desenvolvimento do sistema.
  - **Organizacional**: Agrupa elementos relacionados à própria instituição — como missão, metas e padrões — que impactam diretamente os requisitos.
  - **Gerencial**: Reúne dados que associam atividades e tarefas aos requisitos, apoiando o controle e acompanhamento do projeto.
  - **Desenvolvimento**: Abrange artefatos produzidos ao longo do processo de construção do sistema, como documentos de requisitos, diagramas, códigos e casos de teste.

- **Elementos**: Conjunto de identificadores que fazem referência a diferentes artefatos do projeto, como [requisitos](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/) (RE01), [casos de uso](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_03/Modelagem/Caso_de_uso.md/) (US01), [cenários](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_03/Modelagem/Cenarios/) (CEN01) e [técnicas de elicitação](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/) (ENT01).

- **Elos Backward-from**: Indicam a origem de um requisito, mostrando o tipo de elo e de onde ele se derivou.  
  Exemplo: o requisito **RE01** foi obtido a partir da técnica **ENT01** (entrevista).

- **Elos Forward-from**: Representam a ligação de um requisito com artefatos gerados posteriormente, destacando como ele se relaciona ou é satisfeito por outros elementos.  
  Exemplo: o requisito **RE01** resultou na criação do caso de uso **CS01** e do cenário **CE01**.

- **Tipos de Elos**:
  - **Satisfação**: Indica dependência de atendimento entre os elementos de origem e destino.
  - **Recurso**: Mostra quando um elemento depende de outro para fornecer informações, dados ou funcionalidades.
  - **Responsabilidade**: Associa pessoas, papéis ou equipes a artefatos, registrando quem executa ou valida determinada ação.
  - **Representação**: Relaciona o requisito à sua forma representada em outro modelo ou linguagem.
  - **Alocado**: Demonstra a vinculação entre um elemento e o subsistema responsável por sua implementação.
  - **Agregação**: Mostra uma relação de composição, em que o elemento de origem é formado por outros componentes.

### Participantes

<font size="3"><p style="text-align: center">Tabela 2: Participantes</p></font>

<div align="center">

<table>
  <thead>
    <tr>
      <th align="center">Nome</th>
      <th align="left">ELOS</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center"><a href="https://github.com/arthurfernandesj">Arthur Fernandes</a></td>
      <td align="left">RF20, RF21, RF33, RF34, RF35, RF36</td>
    </tr>
    <tr>
      <td align="center"><a href="https://github.com/BrenoLTeixeira">Breno Teixeira</a></td>
      <td align="left">RF19, RF23, RF29, RF30, RF31, RF32</td>
    </tr>
    <tr>
      <td align="center"><a href="https://github.com/dylancavalcante">Dylan Cavalcante</a></td>
      <td align="left">RF12, RF13, RF16, RF24, RF27, RF28</td>
    </tr>
    <tr>
      <td align="center"><a href="https://github.com/eduardar0">Eduarda Domingos</a></td>
      <td align="left">RF06, RF09, RF10, RF11, RF14, RF15</td>
    </tr>
    <tr>
      <td align="center"><a href="https://github.com/GiovanaFontesS">Giovana Fontes</a></td>
      <td align="left">RF01, RF02, RF17, RF18, RF25, RF26</td>
    </tr>
    <tr>
      <td align="center"><a href="https://github.com/leticialopes20">Letícia Lopes</a></td>
      <td align="left">RF03, RF04, RF05, RF07, RF08, RF22</td>
    </tr>
  </tbody>
</table>
</div>

### RF01

<div align="center">
  <strong>Tabela 1 -</strong> Cartão do Requisito 01 - C01
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF01](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf01), [ADD01](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Analise_de_Documentos/), [UC01](), [CEN01]() |
| **Descrição do Requisito** | O sistema deve permitir o cadastro do Jovem Beneficiário por meio do CPF. |
| **Elos Backward-from:** | Agregação: RF01 ← ADD01 - O requisito foi identificado através da análise de documentos. |
| **Elos Forward-from:** | Satisfação: RF01 → UC01 - O requisito deu origem ao caso de uso "Cadastrar Jovem Beneficiário".<br>Satisfação: RF01 → CEN01 - O requisito deu origem ao cenário "Cadastro de Jovem Beneficiário via CPF". |

<p align="center">Fonte: <a href="https://github.com/GiovanaFontesS">Giovana Fontes</a></p>

### RF02

<div align="center">
  <strong>Tabela 2 -</strong> Cartão do Requisito 02 - C02
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF02](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf02), [ADD02](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Analise_de_Documentos/), [BS01](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/), [ST01](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Storytelling/), [UC02](), [CEN02]() |
| **Descrição do Requisito** | O sistema deve fornecer mecanismos de autenticação e login via Gov.br. |
| **Elos Backward-from:** | Agregação: RF02 ← ADD02 - Identificado pela análise de documentos.<br>Agregação: RF02 ← BS01 - Identificado em sessão de brainstorming.<br>Agregação: RF02 ← ST01 - Identificado por meio de storytelling. |
| **Elos Forward-from:** | Satisfação: RF02 → UC02 - O requisito deu origem ao caso de uso "Autenticação via Gov.br".<br>Satisfação: RF02 → CEN02 - O requisito deu origem ao cenário "Login seguro via Gov.br". |

<p align="center">Fonte: <a href="https://github.com/GiovanaFontesS">Giovana Fontes</a></p>

### RF03

<div align="center">
  <strong>Tabela 5 -</strong> Cartão do Requisito 03 - C03
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** |  [RF03](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf03), [ADD03](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Analise_de_Documentos/), [IDJ01](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspec%C3%A7%C3%A3o/), [BS04](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/), [UC03](), [CEN03]()           |
| **Descrição do Requisito** | O sistema deve permitir a geração e emissão da carteira digital ID Jovem. |
| **Elos Backward-from:** | Agregação: RF03 ← ADD03 - O requisito foi identificado através da análise de documentos.<br>Agregação: RF03 ← IDJ01 - O requisito foi identificado através da introspecção.<br>Agregação: RF03 ← BS04 - O requisito foi identificado através de brainstorming. |
| **Elos Forward-from:** | Satisfação: RF03 → UC03 - O requisito deu origem ao caso de uso "Gerar Carteira Digital".<br>Satisfação: RF03 → CEN03 - O requisito deu origem ao cenário "Emissão da Carteira Digital ID Jovem". |

<p align="center">Fonte: <a href="https://github.com/leticialopes20">Leticia Lopes</a></p>

### RF04

<div align="center">
  <strong>Tabela 6 -</strong> Cartão do Requisito 04 - C04
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF04](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf04), [ENT02](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/), [IDJ03](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspec%C3%A7%C3%A3o/), [BS05](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/), [UC04](), [CEN04]()               |
| **Descrição do Requisito** | O sistema deve permitir a consulta de benefícios como transporte gratuito e meia-entrada em eventos. |
| **Elos Backward-from:** | Agregação: RF04 ← ENT02 - O requisito foi identificado através de entrevista.<br>Agregação: RF04 ← IDJ03 - O requisito foi identificado através da introspecção.<br>Agregação: RF04 ← BS05 - O requisito foi identificado através de brainstorming. |
| **Elos Forward-from:** | Satisfação: RF04 → UC04 - O requisito deu origem ao caso de uso "Consultar Benefícios".<br>Satisfação: RF04 → CEN04 - O requisito deu origem ao cenário "Consulta de Benefícios Disponíveis". |

<p align="center">Fonte: <a href="https://github.com/leticialopes20">Leticia Lopes</a></p>

### RF05

<div align="center">
  <strong>Tabela 7 -</strong> Cartão do Requisito 05 - C05
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF05](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf05), [ADD04](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Analise_de_Documentos/), [IDJ02](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspec%C3%A7%C3%A3o/), [UC05](), [CEN05]()               |
| **Descrição do Requisito** | O sistema deve validar a carteira digital em estabelecimentos conveniados. |
| **Elos Backward-from:** | Agregação: RF05 ← ADD04 - O requisito foi identificado através da análise de documentos.<br>Agregação: RF05 ← IDJ02 - O requisito foi identificado através da introspecção. |
| **Elos Forward-from:** | Satisfação: RF05 → UC05 - O requisito deu origem ao caso de uso "Validar Carteira Digital".<br>Satisfação: RF05 → CEN05 - O requisito deu origem ao cenário "Validação da Carteira em Estabelecimento". |

<p align="center">Fonte: <a href="https://github.com/leticialopes20">Leticia Lopes</a></p>

### RF06

<div align="center">
  <strong>Tabela 8 -</strong> Cartão do Requisito 06 - C06
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF06](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf06), [ADD05](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Analise_de_Documentos/), [BS08](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/), [IDJ04](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspec%C3%A7%C3%A3o/), [UC06](), [CEN06](), [US01]() |
| **Descrição do Requisito** | O sistema deve exibir uma seção de perguntas frequentes (FAQ) e suporte ao Jovem Beneficiário. |
| **Elos Backward-from:** | Agregação: RF06 ← ADD05 - O requisito foi identificado através da análise de documentos.<br>Agregação: RF06 ← BS08 - O requisito foi identificado através de brainstorming.<br>Agregação: RF06 ← IDJ04 - O requisito foi identificado através de introspecção. |
| **Elos Forward-from:** | Satisfação: RF06 → UC06 - O requisito deu origem ao caso de uso "Consultar FAQ e Suporte".<br>Satisfação: RF06 → CEN06 - O requisito deu origem ao cenário "Consulta de Perguntas Frequentes (FAQ)".<br>Satisfação: RF06 → US01 - O requisito deu origem à história de usuário "Exibir seção de perguntas frequentes (FAQ)". |

<p align="center">Fonte: <a href="https://github.com/eduardar0">Eduarda Domingos</a></p>

### RF07

<div align="center">
  <strong>Tabela 9 -</strong> Cartão do Requisito 07 - C07
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF07](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf07), [BS09](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/), [IDJ08](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspec%C3%A7%C3%A3o/), [UC07](), [CEN07]()       |
| **Descrição do Requisito** | O sistema deve permitir integração com o CadÚnico para atualização automática de dados. |
| **Elos Backward-from:** | Agregação: RF07 ← BS09 - O requisito foi identificado através de brainstorming.<br>Agregação: RF07 ← IDJ08 - O requisito foi identificado através da introspecção. |
| **Elos Forward-from:** | Satisfação: RF07 → UC07 - O requisito deu origem ao caso de uso "Integrar com CadÚnico".<br>Satisfação: RF07 → CEN07 - O requisito deu origem ao cenário "Atualização Automática de Dados via CadÚnico". |

<p align="center">Fonte: <a href="https://github.com/leticialopes20">Leticia Lopes</a></p>

### RF08

<div align="center">
  <strong>Tabela 10 -</strong> Cartão do Requisito 08 - C08
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF08](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf08), [BS11](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/), [ST04](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Storytelling/), [IDJ11](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspec%C3%A7%C3%A3o/), [ENT13](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/), [UC08](), [CEN08]()                 |
| **Descrição do Requisito** | O sistema deve emitir notificações sobre vencimento, renovação do benefício, novos parceiros e eventos de interesse. |
| **Elos Backward-from:** | Agregação: RF08 ← BS11 - O requisito foi identificado através de brainstorming.<br>Agregação: RF08 ← ST04 - O requisito foi identificado através de storytelling.<br>Agregação: RF08 ← IDJ11 - O requisito foi identificado através da introspecção.<br>Agregação: RF08 ← ENT13 - O requisito foi identificado através de entrevista. |
| **Elos Forward-from:** | Satisfação: RF08 → UC08 - O requisito deu origem ao caso de uso "Enviar Notificações".<br>Satisfação: RF08 → CEN08 - O requisito deu origem ao cenário "Recebimento de Notificação de Vencimento". |

<p align="center">Fonte: <a href="https://github.com/leticialopes20">Leticia Lopes</a></p>

### RF09

<div align="center">
  <strong>Tabela 11 -</strong> Cartão do Requisito 09 - C09
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF09](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf09), [ST03](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Storytelling/), [BS19](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/), [UC09](), [CEN09](), [US02]()               |
| **Descrição do Requisito** | O sistema deve permitir o download da carteirinha para uso offline. |
| **Elos Backward-from:** | Agregação: RF09 ← ST03 - O requisito foi identificado através de storytelling.<br>Agregação: RF09 ← BS19 - O requisito foi identificado através de brainstorming. |
| **Elos Forward-from:** | Satisfação: RF09 → UC09 - O requisito deu origem ao caso de uso "Download da Carteirinha Offline".<br>Satisfação: RF09 → CEN09 - O requisito deu origem ao cenário "Download da Carteirinha para Uso Offline".<br>Satisfação: RF09 → US02 - O requisito deu origem à história de usuário "Permitir download da carteirinha para uso offline". |

<p align="center">Fonte: <a href="https://github.com/eduardar0">Eduarda Domingos</a></p>

### RF10

<div align="center">
  <strong>Tabela 12 -</strong> Cartão do Requisito 10 - C10
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF10](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf10) , [BS10](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming), [ST06](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Storytelling), [UC10](), [CEN10](), [US03]()                |
| **Descrição do Requisito** | O aplicativo deve disponibilizar informações sobre locais e parceiros que aceitam o benefício.|
| **Elos Backward-from:** | Agregação: RF10 ← BS10 - O requisito foi identificado através de brainstorming.<br>Agregação: RF10 ← ST06 - O requisito foi identificado através de storytelling.  |
| **Elos Forward-from:** | Satisfação: RF10 → UC10 - O requisito deu origem ao caso de uso "Consultar Locais e Parceiros".<br>Satisfação: RF10 → CEN10 - O requisito deu origem ao cenário "Consulta de Locais e Parceiros que Aceitam o Benefício".<br>Satisfação: RF10 → US03 - O requisito deu origem à história de usuário "Disponibilizar informações sobre locais e parceiros que aceitam o benefício". |

<p align="center">Fonte: <a href="https://github.com/eduardar0">Eduarda Domingos</a></p>

### RF11

<div align="center">
  <strong>Tabela 13 -</strong> Cartão do Requisito 11 - C11
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF11](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf11), [ENT05](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/), [BS08](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming), [IDJ05](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspecção/), [UC11](), [CEN11](), [US04]()                 |
| **Descrição do Requisito** | O sistema deve fornecer canal de suporte via chat, e-mail ou formulário de contato. |
| **Elos Backward-from:** |Agregação: RF11 ← ENT05 - O requisito foi identificado através de entrevista.<br>Agregação: RF11 ← BS08 - O requisito foi identificado através de brainstorming.<br>Agregação: RF11 ← IDJ05 - O requisito foi identificado através de introspecção. |
| **Elos Forward-from:** | Satisfação: RF11 → UC11 - O requisito deu origem ao caso de uso "Solicitar Suporte ao Beneficiário".<br>Satisfação: RF11 → CEN11 - O requisito deu origem ao cenário "Canal de Suporte via Chat, E-mail ou Formulário de Contato".<br>Satisfação: RF11 → US04 - O requisito deu origem à história de usuário "Fornecer canal de suporte via chat, e-mail ou formulário de contato".|

<p align="center">Fonte: <a href="https://github.com/eduardar0">Eduarda Domingos</a></p>

### RF12

<div align="center">
  <strong>Tabela 14 -</strong> Cartão do Requisito 12 - C12
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF12](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf12), [ST08](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Storytelling/), [ENT12](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/), [UC12](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_03/Modelagem/Caso_de_uso), [CEN12](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_03/Modelagem/Cenarios), [US12]() |
| **Descrição do Requisito** | O aplicativo deve permitir que o Jovem Beneficiário visualize o histórico de utilização dos benefícios. |
| **Elos Backward-from:** | Agregação: RF12 ← ST08 - O requisito foi identificado através de storytelling.<br>Agregação: RF12 ← ENT12 - O requisito foi identificado através de entrevista. |
| **Elos Forward-from:** | Satisfação: RF12 → UC12 - O requisito deu origem ao caso de uso "Visualizar Histórico de Utilização".<br>Satisfação: RF12 → CEN12 - O requisito deu origem ao cenário "Consulta ao Histórico de Benefícios Utilizados".<br>Satisfação: RF12 → US12 - O requisito deu origem à história de usuário "Como jovem beneficiário, quero visualizar meu histórico de utilização para acompanhar meus gastos e usos." |

<p align="center">Fonte: <a href="https://github.com/dylancavalcante">Dylan Cavalcante</a></p>

### RF13

<div align="center">
  <strong>Tabela 15 -</strong> Cartão do Requisito 13 - C13
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF13](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf13), [ADD07](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Analise_de_Documentos/), [BS07](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/), [ENT16](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/), [UC13](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_03/Modelagem/Caso_de_uso), [CEN13](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_03/Modelagem/Cenarios), [US13]() |
| **Descrição do Requisito** | O sistema deve apresentar uma seção de "Vantagens e Parcerias" com novidades, divulgação sobre o programa e ofertas exclusivas. |
| **Elos Backward-from:** | Agregação: RF13 ← ADD07 - O requisito foi identificado através da análise de documentos.<br>Agregação: RF13 ← BS07 - O requisito foi identificado através de brainstorming.<br>Agregação: RF13 ← ENT16 - O requisito foi identificado através de entrevista. |
| **Elos Forward-from:** | Satisfação: RF13 → UC13 - O requisito deu origem ao caso de uso "Consultar Vantagens e Parcerias".<br>Satisfação: RF13 → CEN13 - O requisito deu origem ao cenário "Visualização de Novidades e Ofertas Exclusivas".<br>Satisfação: RF13 → US13 - O requisito deu origem à história de usuário "Como jovem beneficiário, quero acessar uma seção de vantagens para descobrir novas parcerias e ofertas." |

<p align="center">Fonte: <a href="https://github.com/dylancavalcante">Dylan Cavalcante</a></p>

### RF14

<div align="center">
  <strong>Tabela 16 -</strong> Cartão do Requisito 14 - C14
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF14](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf14), [ENT03](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/), [UC14](), [CEN14](), [US05]()       |
| **Descrição do Requisito** | O aplicativo deve permitir reserva e emissão de comprovantes de uso do benefício. |
| **Elos Backward-from:** | Agregação: RF14 ← ENT03 - O requisito foi identificado através de entrevista. |
| **Elos Forward-from:** | Satisfação: RF14 → UC14 - O requisito deu origem ao caso de uso "Reservar e Emitir Comprovante de Uso".<br>Satisfação: RF14 → CEN14 - O requisito deu origem ao cenário "Emissão de Comprovante de Uso do Benefício".<br>Satisfação: RF14 → US05 - O requisito deu origem à história de usuário "Permitir reserva e emissão de comprovantes de uso". |

<p align="center">Fonte: <a href="https://github.com/eduardar0">Eduarda Domingos</a></p>

### RF15

<div align="center">
  <strong>Tabela 17 -</strong> Cartão do Requisito 15 - C15
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF15](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf15), [ST02](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Storytelling/), [UC15](), [CEN15](), [US06]()       |
| **Descrição do Requisito** | O sistema deve validar automaticamente a elegibilidade do Jovem Beneficiário ao benefício. |
| **Elos Backward-from:** | Agregação: RF15 ← ST02 - O requisito foi identificado através de storytelling. |
| **Elos Forward-from:** | Satisfação: RF15 → UC15 - O requisito deu origem ao caso de uso "Validar Elegibilidade do Beneficiário".<br>Satisfação: RF15 → CEN15 - O requisito deu origem ao cenário "Validação Automática de Elegibilidade".<br>Satisfação: RF15 → US06 - O requisito deu origem à história de usuário "Validar automaticamente a elegibilidade do jovem". |

<p align="center">Fonte: <a href="https://github.com/eduardar0">Eduarda Domingos</a></p>

### RF16

<div align="center">
  <strong>Tabela 18 -</strong> Cartão do Requisito 16 - C16
</div>

| **Categoria:** | Desenvolvimento / Integração |
|:---------------|:----------------|
| **Elementos:** | [RF16](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf16), [BS21](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/), [ST10](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Storytelling/), [UC16](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_03/Modelagem/Caso_de_uso), [CEN16](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_03/Modelagem/Cenarios), [US16]() |
| **Descrição do Requisito** | O sistema deve permitir integração com o Gov.br e outros serviços governamentais. |
| **Elos Backward-from:** | Agregação: RF16 ← BS21 - O requisito foi identificado através de brainstorming.<br>Agregação: RF16 ← ST10 - O requisito foi identificado através de storytelling. |
| **Elos Forward-from:** | Satisfação: RF16 → UC16 - O requisito deu origem ao caso de uso "Integrar Sistema com Gov.br".<br>Satisfação: RF16 → CEN16 - O requisito deu origem ao cenário "Validação de Dados via Serviços Governamentais".<br>Satisfação: RF16 → US16 - O requisito deu origem à história de usuário "Como sistema, devo integrar com o Gov.br para assegurar a autenticidade e atualização dos dados do usuário." |

<p align="center">Fonte: <a href="https://github.com/dylancavalcante">Dylan Cavalcante</a></p>

### RF17

<div align="center">
  <strong>Tabela 19 -</strong> Cartão do Requisito 17 - C17
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF17](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf17), [BS12](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming), [IDJ17](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspecção/), [UC17](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_03/Modelagem/Caso_de_uso), [CEN17](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_03/Modelagem/Cenarios), [US17]() |
| **Descrição do Requisito** | O aplicativo deve permitir compartilhar a carteirinha digital em formato PDF ou imagem. |
| **Elos Backward-from:** | Agregação: RF17 ← BS12 - O requisito foi identificado através de brainstorming, quando foi sugerido que o usuário pudesse compartilhar sua carteirinha digital em PDF ou imagem para uso em estabelecimentos. |
| **Elos Forward-from:** | Satisfação: RF17 → UC17 - O requisito deu origem ao caso de uso "Compartilhar Carteirinha Digital".<br>Satisfação: RF17 → CEN17 - O requisito deu origem ao cenário "Compartilhar Carteirinha Digital em PDF ou Imagem".<br>Satisfação: RF17 → US17 - O requisito deu origem à história de usuário "Como jovem beneficiário, quero compartilhar minha carteirinha digital em PDF ou imagem para comprovar meus benefícios easily." | 

<p align="center">Fonte: <a href="https://github.com/GiovanaFontesS">Giovana Fontes</a></p>

### RF18

<div align="center">
  <strong>Tabela 20 -</strong> Cartão do Requisito 18 - C18
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF18](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf18), [ENT04](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/), [IDJ18](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspecção/), [UC18](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_03/Modelagem/Caso_de_uso), [CEN18](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_03/Modelagem/Cenarios), [US18]() |
| **Descrição do Requisito** | O sistema deve fornecer informações sobre pendências ou erros relacionados aos benefícios do usuário. |
| **Elos Backward-from:** | Agregação: RF18 ← ENT04 - O requisito foi identificado através de entrevista, onde os usuários expressaram a necessidade de serem informados sobre irregularidades ou falhas nos benefícios. |
| **Elos Forward-from:** | Satisfação: RF18 → UC18 - O requisito deu origem ao caso de uso "Exibir Pendências e Erros dos Benefícios".<br>Satisfação: RF18 → CEN18 - O requisito deu origem ao cenário "Informar Pendências e Inconsistências de Benefícios".<br>Satisfação: RF18 → US18 - O requisito deu origem à história de usuário "Como jovem beneficiário, quero visualizar pendências ou erros nos meus benefícios para poder corrigi-los rapidamente." |

<p align="center">Fonte: <a href="https://github.com/GiovanaFontesS">Giovana Fontes</a></p>

### RF19

<div align="center">
  <strong>Tabela 21 -</strong> Cartão do Requisito 19 - C19
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF19](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf19), [ENT06](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/), [UC19](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_03/Modelagem/Caso_de_uso), [CEN19](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_03/Modelagem/Cenarios), [US19]() |
| **Descrição do Requisito** | O sistema deve permitir que os usuários atualizem seu cadastro e definam preferências pessoais. |
| **Elos Backward-from:** | Agregação: RF19 ← ENT06 - O requisito foi identificado através de entrevista. |
| **Elos Forward-from:** | Satisfação: RF19 → UC19 - O requisito deu origem ao caso de uso "Atualizar Cadastro e Preferências".<br>Satisfação: RF19 → CEN19 - O requisito deu origem ao cenário "Usuário Altera Dados Cadastrais".<br>Satisfação: RF19 → US19 - O requisito deu origem à história de usuário "Como usuário, quero atualizar meus dados cadastrais e definir minhas preferências." |

<p align="center">Fonte: <a href="https://github.com/brenolteixeira">Breno Teixeira</a></p>

### RF20

<div align="center">
  <strong>Tabela 22 -</strong> Cartão do Requisito 20 - C20
</div>

| **Categoria:** | Desenvolvimento / Segurança |
|:---------------|:------------------------------|
| **Elementos:** | [RF20](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf20), [ENT09](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/), [IDJ18](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspecção/#idj18) , [UC20](), [CEN20](), [US20]() |
| **Descrição do Requisito:** | O sistema deve fornecer alertas sobre possíveis irregularidades no uso dos benefícios, identificando padrões suspeitos |
| **Elos Backward-from:** | Agregação: RF20 ← ENT09 - O requisito foi identificado a partir de entrevistas com stakeholders (usuários/gestores) que relataram a necessidade de monitoramento e prevenção de uso indevido do benefício. |
| **Elos Forward-from:** | Satisfação: RF20 → UC20 - O requisito deu origem ao caso de uso “Monitorar e Notificar Irregularidades de Uso”.<br>Satisfação: RF20 → CEN20 - O requisito deu origem ao cenário “Detecção de Padrão Suspeito e Emissão de Alerta”.<br>Satisfação: RF20 → US20 - O requisito deu origem à história de usuário “Como gestor do programa, desejo receber alertas sobre possíveis irregularidades para investigar fraudes e proteger os benefícios.” |
<p align="center">Fonte: <a href="https://github.com/arthurfernandesj">Arthur Fernandes</a></p>


### RF21

<div align="center">
  <strong>Tabela 23 -</strong> Cartão do Requisito 21 - C21
</div>

| **Categoria:** | Desenvolvimento / Experiência do Usuário |
|:---------------|:----------------|
| **Elementos:** | [RF21](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf21), [ENT10](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/), [ST06](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Storytelling/), [IDJ06](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspecção/#idj06), [UC21](), [CEN21](), [US21]() |
| **Descrição do Requisito:** | O sistema deve possuir um mapa interativo que permita visualizar geograficamente os parceiros e eventos culturais vinculados ao programa ID Jovem. |
| **Elos Backward-from:** | Agregação: RF21 ← ENT10 - O requisito foi identificado a partir das entrevistas, nas quais os usuários destacaram a importância de localizar visualmente os parceiros e eventos culturais próximos.<br>Agregação: RF21 ← ST06 - O requisito foi reforçado pelo storytelling, onde o jovem desejava encontrar facilmente locais parceiros e eventos acessíveis. |
| **Elos Forward-from:** | Satisfação: RF21 → UC21 - O requisito deu origem ao caso de uso “Visualizar Parceiros e Eventos em Mapa Interativo”.<br>Satisfação: RF21 → CEN21 - O requisito deu origem ao cenário “Consulta e Interação com o Mapa de Parceiros e Eventos”.<br>Satisfação: RF21 → US21 - O requisito deu origem à história de usuário “Como jovem beneficiário, desejo visualizar no mapa os parceiros e eventos próximos para facilitar meu acesso aos benefícios culturais.” |


<p align="center">Fonte: <a href="https://github.com/arthurfernandesj">Arthur Fernandes</a></p>

### RF22

<div align="center">
  <strong>Tabela 24 -</strong> Cartão do Requisito 22 - C22
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF22](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf22), [ENT11](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/), [UC22](), [CEN22]() |
| **Descrição do Requisito:** | O sistema deve apresentar uma agenda integrada de eventos com filtros de busca. |
| **Elos Backward-from:** | Agregação: RF22 ← ENT11 - O requisito foi identificado através de entrevista. |
| **Elos Forward-from:** | Satisfação: RF22 → UC22 - O requisito deu origem ao caso de uso “Consultar Agenda de Eventos”.<br>Satisfação: RF22 → CEN22 - O requisito deu origem ao cenário “Busca de Eventos com Filtros”. |


<p align="center">Fonte: <a href="https://github.com/leticialopes20">Leticia Lopes</a></p>

### RF23

<div align="center">
  <strong>Tabela 25 -</strong> Cartão do Requisito 23 - C23
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF23](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf23), [ENT14](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/), [UC23](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_03/Modelagem/Caso_de_uso), [CEN23](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_03/Modelagem/Cenarios), [US23]() |
| **Descrição do Requisito** | O sistema deve fornecer um canal para denúncia ou feedback sobre estabelecimentos que recusam o benefício. |
| **Elos Backward-from:** | Agregação: RF23 ← ENT14 - O requisito foi identificado através de entrevista. |
| **Elos Forward-from:** | Satisfação: RF23 → UC23 - O requisito deu origem ao caso de uso "Registrar Denúncia ou Feedback".<br>Satisfação: RF23 → CEN23 - O requisito deu origem ao cenário "Usuário Envia Denúncia de Recusa de Benefício".<br>Satisfação: RF23 → US23 - O requisito deu origem à história de usuário "Como usuário, quero denunciar locais que não aceitaram meu benefício." |

<p align="center">Fonte: <a href="https://github.com/brenolteixeira">Breno Teixeira</a></p>

### RF24

<div align="center">
  <strong>Tabela 26 -</strong> Cartão do Requisito 24 - C24
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF24](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf24), [ENT15](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/), [UC24](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_03/Modelagem/Caso_de_uso), [CEN24](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_03/Modelagem/Cenarios), [US24]() |
| **Descrição do Requisito** | O sistema deve permitir que o usuário favorite eventos e estabelecimentos para consulta rápida. |
| **Elos Backward-from:** | Agregação: RF24 ← ENT15 - O requisito foi identificado através de entrevista. |
| **Elos Forward-from:** | Satisfação: RF24 → UC24 - O requisito deu origem ao caso de uso "Favoritar Eventos e Estabelecimentos".<br>Satisfação: RF24 → CEN24 - O requisito deu origem ao cenário "Usuário Adiciona Evento aos Favoritos".<br>Satisfação: RF24 → US24 - O requisito deu origem à história de usuário "Como jovem beneficiário, quero poder favoritar eventos e locais de meu interesse para encontrá-los facilmente." |

<p align="center">Fonte: <a href="https://github.com/dylancavalcante">Dylan Cavalcante</a></p>

### RF25

<div align="center">
  <strong>Tabela 27 -</strong> Cartão do Requisito 25 - C25
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF25](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf25), [ADD07](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Analise_de_Documentos/), [ENT16](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/), [UC25](), [CEN25]() |
| **Descrição do Requisito** | O sistema deve permitir que o usuário recupere o acesso à conta por meio de verificação via e-mail, SMS ou Gov.br. |
| **Elos Backward-from:** | Agregação: RF25 ← ADD07 - Identificado pela análise de documentos.<br>Agregação: RF25 ← ENT16 - Identificado através de entrevista. |
| **Elos Forward-from:** | Satisfação: RF25 → UC25 - O requisito deu origem ao caso de uso "Recuperar Acesso à Conta".<br>Satisfação: RF25 → CEN25 - O requisito deu origem ao cenário "Recuperação de Conta via E-mail, SMS ou Gov.br". |


<p align="center">Fonte: <a href="https://github.com/GiovanaFontesS">Giovana Fontes</a></p>

### RF26

<div align="center">
  <strong>Tabela 28 -</strong> Cartão do Requisito 26 - C26
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF26](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf26), [BS09](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/), [IDJ09](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspecção/), [UC26](), [CEN26]() |
| **Descrição do Requisito** | O aplicativo deve disponibilizar um tutorial interativo para orientar novos usuários sobre como utilizar o ID Jovem e seus benefícios. |
| **Elos Backward-from:** | Agregação: RF26 ← BS09 - O requisito foi identificado através de brainstorming.<br>Agregação: RF26 ← IDJ09 - O requisito foi identificado através de introspecção. |
| **Elos Forward-from:** | Satisfação: RF26 → UC26 - O requisito deu origem ao caso de uso "Acessar Tutorial Interativo".<br>Satisfação: RF26 → CEN26 - O requisito deu origem ao cenário "Orientação para novos usuários". |


<p align="center">Fonte: <a href="https://github.com/GiovanaFontesS">Giovana Fontes</a></p>

### RF27

<div align="center">
  <strong>Tabela 29 -</strong> Cartão do Requisito 27 - C27
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF27](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf27), [BS10](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/), [ENT18](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/), [UC27](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_03/Modelagem/Caso_de_uso), [CEN27](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_03/Modelagem/Cenarios), [US27]() |
| **Descrição do Requisito** | O sistema deve permitir que o usuário avalie parceiros e estabelecimentos conveniados com notas e comentários. |
| **Elos Backward-from:** | Agregação: RF27 ← BS10 - O requisito foi identificado através de brainstorming.<br>Agregação: RF27 ← ENT18 - O requisito foi identificado através de entrevista. |
| **Elos Forward-from:** | Satisfação: RF27 → UC27 - O requisito deu origem ao caso de uso "Avaliar Parceiros e Estabelecimentos".<br>Satisfação: RF27 → CEN27 - O requisito deu origem ao cenário "Envio de Avaliação (Nota e Comentário) de um Estabelecimento".<br>Satisfação: RF27 → US27 - O requisito deu origem à história de usuário "Como jovem beneficiário, quero avaliar os locais que utilizei para compartilhar minha experiência." |

<p align="center">Fonte: <a href="https://github.com/dylancavalcante">Dylan Cavalcante</a></p>

### RF28

<div align="center">
  <strong>Tabela 30 -</strong> Cartão do Requisito 28 - C28
</div>

| **Categoria:** | Desenvolvimento / Acessibilidade |
|:---------------|:----------------|
| **Elementos:** | [RF28](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf28), [ADD08](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Analise_de_Documentos/), [ENT19](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/), [UC28](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_03/Modelagem/Caso_de_uso), [CEN28](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_03/Modelagem/Cenarios), [US28]() |
| **Descrição do Requisito** | O aplicativo deve oferecer um modo acessível, com contraste ajustável e leitura por voz para pessoas com deficiência visual. |
| **Elos Backward-from:** | Agregação: RF28 ← ADD08 - O requisito foi identificado através da análise de documentos.<br>Agregação: RF28 ← ENT19 - O requisito foi identificado através de entrevista. |
| **Elos Forward-from:** | Satisfação: RF28 → UC28 - O requisito deu origem ao caso de uso "Ajustar Opções de Acessibilidade".<br>Satisfação: RF28 → CEN28 - O requisito deu origem ao cenário "Ativação de Modo de Alto Contraste e Leitor de Tela".<br>Satisfação: RF28 → US28 - O requisito deu origem à história de usuário "Como usuário com baixa visão, quero ajustar o contraste e usar leitura por voz para conseguir navegar no aplicativo." |

<p align="center">Fonte: <a href="https://github.com/dylancavalcante">Dylan Cavalcante</a></p>

### RF29

<div align="center">
  <strong>Tabela 31 -</strong> Cartão do Requisito 29 - C29
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF29](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf29), [ADD09](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Analise_de_Documentos/), [BS11](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/), [UC29](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_03/Modelagem/Caso_de_uso), [CEN29](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_03/Modelagem/Cenarios), [US29]() |
| **Descrição do Requisito** | O sistema deve possibilitar a exportação dos comprovantes e histórico de uso em formato PDF. |
| **Elos Backward-from:** | Agregação: RF29 ← ADD09 - O requisito foi identificado através da análise de documentos.<br>Agregação: RF29 ← BS11 - O requisito foi identificado através de brainstorming. |
| **Elos Forward-from:** | Satisfação: RF29 → UC29 - O requisito deu origem ao caso de uso "Exportar Histórico e Comprovantes".<br>Satisfação: RF29 → CEN29 - O requisito deu origem ao cenário "Exportação de Histórico de Uso para PDF".<br>Satisfação: RF29 → US29 - O requisito deu origem à história de usuário "Como usuário, quero exportar meu histórico e comprovantes em PDF." |

<p align="center">Fonte: <a href="https://github.com/brenolteixeira">Breno Teixeira</a></p>

### RF30

<div align="center">
  <strong>Tabela 32 -</strong> Cartão do Requisito 30 - C30
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF30](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf30), [ENT20](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/), [IDJ10](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspec%C3%A7%C3%A3o/), [UC30](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_03/Modelagem/Caso_de_uso), [CEN30](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_03/Modelagem/Cenarios), [US30]() |
| **Descrição do Requisito** | O aplicativo deve permitir que o usuário configure preferências de notificação, como tipo de alerta e frequência. |
| **Elos Backward-from:** | Agregação: RF30 ← ENT20 - O requisito foi identificado através de entrevista.<br>Agregação: RF30 ← IDJ10 - O requisito foi identificado através de introspecção. |
| **Elos Forward-from:** | Satisfação: RF30 → UC30 - O requisito deu origem ao caso de uso "Configurar Preferências de Notificação".<br>Satisfação: RF30 → CEN30 - O requisito deu origem ao cenário "Usuário Ajusta Frequência de Notificações".<br>Satisfação: RF30 → US30 - O requisito deu origem à história de usuário "Como usuário, quero configurar quais notificações desejo receber e com que frequência." |

<p align="center">Fonte: <a href="https://github.com/brenolteixeira">Breno Teixeira</a></p>

### RF31

<div align="center">
  <strong>Tabela 33 -</strong> Cartão do Requisito 31 - C31
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF31](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf31), [ADD10](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Analise_de_Documentos/), [UC31](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_03/Modelagem/Caso_de_uso), [CEN31](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_03/Modelagem/Cenarios), [US31]() |
| **Descrição do Requisito** | O sistema deve exibir a versão do aplicativo e informações sobre atualizações. |
| **Elos Backward-from:** | Agregação: RF31 ← ADD10 - O requisito foi identificado através da análise de documentos. |
| **Elos Forward-from:** | Satisfação: RF31 → UC31 - O requisito deu origem ao caso de uso "Verificar Versão e Atualizações".<br>Satisfação: RF31 → CEN31 - O requisito deu origem ao cenário "Consulta de Versão do Aplicativo".<br>Satisfação: RF31 → US31 - O requisito deu origem à história de usuário "Como usuário, quero ver a versão do app e se há atualizações." |

<p align="center">Fonte: <a href="https://github.com/brenolteixeira">Breno Teixeira</a></p>

### RF32

<div align="center">
  <strong>Tabela 34 -</strong> Cartão do Requisito 32 - C32
</div>

| **Categoria:** | Desenvolvimento / Legal |
|:---------------|:----------------|
| **Elementos:** | [RF32](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf32), [ADD11](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Analise_de_Documentos/), [ENT21](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/), [UC32](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_03/Modelagem/Caso_de_uso), [CEN32](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_03/Modelagem/Cenarios), [US32]() |
| **Descrição do Requisito** | O aplicativo deve fornecer acesso rápido a termos de uso e política de privacidade. |
| **Elos Backward-from:** | Agregação: RF32 ← ADD11 - O requisito foi identificado através da análise de documentos.<br>Agregação: RF32 ← ENT21 - O requisito foi identificado através de entrevista. |
| **Elos Forward-from:** | Satisfação: RF32 → UC32 - O requisito deu origem ao caso de uso "Acessar Termos de Uso e Política de Privacidade".<br>Satisfação: RF32 → CEN32 - O requisito deu origem ao cenário "Consulta à Política de Privacidade".<br>Satisfação: RF32 → US32 - O requisito deu origem à história de usuário "Como usuário, quero acessar facilmente os termos de uso e a política de privacidade." |

<p align="center">Fonte: <a href="https://github.com/brenolteixeira">Breno Teixeira</a></p>

### RF33

<div align="center">
  <strong>Tabela 35 -</strong> Cartão do Requisito 33 - C33
</div>

| **Categoria:** | Desenvolvimento / Segurança |
|:---------------|:----------------|
| **Elementos:** | [RF33](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf33), [ADD12](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Analise_de_Documentos/), [UC33](), [CEN33](), [US33]() |
| **Descrição do Requisito** | O sistema deve registrar logs de acesso e ações do usuário para auditoria e segurança. |
| **Elos Backward-from:** | Agregação: RF33 ← ADD12 - O requisito foi identificado através da análise de documentos (legislação de segurança). |
| **Elos Forward-from:** | Satisfação: RF33 → UC33 - O requisito deu origem ao caso de uso "Registrar Logs de Auditoria".<br>Satisfação: RF33 → CEN33 - O requisito deu origem ao cenário "Registro de Ação de Usuário no Log".<br>Satisfação: RF33 → US33 - O requisito deu origem à história de usuário "Como administrador do sistema, quero que logs de acesso e ações sejam registrados para fins de auditoria." |

<p align="center">Fonte: <a href="https://github.com/arthurfernandesj">Arthur Fernandes</a></p>

### RF34

<div align="center">
  <strong>Tabela 36 -</strong> Cartão do Requisito 34 - C34
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF34](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf34), [BS12](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/), [IDJ11](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspec%C3%A7%C3%A3o/), [UC34](), [CEN34](), [US34]() |
| **Descrição do Requisito** | O aplicativo deve enviar alertas sobre atualizações importantes do programa ID Jovem. |
| **Elos Backward-from:** | Agregação: RF34 ← BS12 - O requisito foi identificado através de brainstorming.<br>Agregação: RF34 ← IDJ11 - O requisito foi identificado através de introspecção. |
| **Elos Forward-from:** | Satisfação: RF34 → UC34 - O requisito deu origem ao caso de uso "Enviar Alertas do Programa".<br>Satisfação: RF34 → CEN34 - O requisito deu origem ao cenário "Recebimento de Alerta sobre Mudança no Programa".<br>Satisfação: RF34 → US34 - O requisito deu origem à história de usuário "Como jovem beneficiário, quero receber alertas sobre atualizações importantes do programa." |

<p align="center">Fonte: <a href="https://github.com/arthurfernandesj">Arthur Fernandes</a></p>

### RF35

<div align="center">
  <strong>Tabela 37 -</strong> Cartão do Requisito 35 - C35
</div>

| **Categoria:** | Desenvolvimento / Segurança |
|:---------------|:----------------|
| **Elementos:** | [RF35](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf35), [ADD13](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Analise_de_Documentos/), [ENT22](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/), [UC35](), [CEN35](), [US35]() |
| **Descrição do Requisito** | O sistema deve permitir que o usuário altere sua senha de acesso pelo próprio aplicativo. |
| **Elos Backward-from:** | Agregação: RF35 ← ADD13 - O requisito foi identificado através da análise de documentos (padrões de segurança).<br>Agregação: RF35 ← ENT22 - O requisito foi identificado através de entrevista. |
| **Elos Forward-from:** | Satisfação: RF35 → UC35 - O requisito deu origem ao caso de uso "Alterar Senha de Acesso".<br>Satisfação: RF35 → CEN35 - O requisito deu origem ao cenário "Usuário Altera Senha com Sucesso".<br>Satisfação: RF35 → US35 - O requisito deu origem à história de usuário "Como usuário, quero poder alterar minha senha de acesso pelo aplicativo." |

<p align="center">Fonte: <a href="https://github.com/arthurfernandesj">Arthur Fernandes</a></p>

### RF36

<div align="center">
  <strong>Tabela 38 -</strong> Cartão do Requisito 36 - C36
</div>

| **Categoria:** | Desenvolvimento / Experiência do Usuário |
|:---------------|:----------------|
| **Elementos:** | [RF36](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf36), [BS13](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/), [IDJ12](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspec%C3%A7%C3%A3o/), [UC36](), [CEN36](), [US36]() |
| **Descrição do Requisito** | O aplicativo deve fornecer integração com GPS para localizar estabelecimentos próximos em tempo real. |
| **Elos Backward-from:** | Agregação: RF36 ← BS13 - O requisito foi identificado através de brainstorming.<br>Agregação: RF36 ← IDJ12 - O requisito foi identificado através de introspecção. |
| **Elos Forward-from:** | Satisfação: RF36 → UC36 - O requisito deu origem ao caso de uso "Localizar Estabelecimentos Próximos (GPS)".<br>Satisfação: RF36 → CEN36 - O requisito deu origem ao cenário "Busca de Parceiros Próximos via GPS".<br>Satisfação: RF36 → US36 - O requisito deu origem à história de usuário "Como jovem beneficiário, quero usar o GPS para encontrar locais parceiros perto de mim." |

<p align="center">Fonte: <a href="https://github.com/arthurfernandesj">Arthur Fernandes</a></p>




---

## **Referências Bibliográficas**

> <a id="RP1" href="#TEC1">[1]</a> SAYÃO, Miriam; LEITE, Julio. *Rastreabilidade de Requisitos*. Rio de Janeiro: Departamento de Informática – PUC-Rio, 2005. Disponível em: [https://www-di.inf.puc-rio.br/~julio/rastre.pdf](https://www-di.inf.puc-rio.br/~julio/rastre.pdf). Acesso em: 27 Out. 2025.  

> <a id="RP2" href="#TEC2">[2]</a> KOTONYA, Gerald; SOMMERVILLE, Ian. *Requirements Engineering: Processes and Techniques*. John Wiley & Sons, 1998. Disponível em: [https://www.acqnotes.com/Attachments/The%20Requirements%20Engineering%20Handbook%20by%20Ralph%20R.%20Young.pdf](https://www.acqnotes.com/Attachments/The%20Requirements%20Engineering%20Handbook%20by%20Ralph%20R.%20Young.pdf). Acesso em: 27 Out. 2025.  

> <a id="RP3" href="#TEC3">[3]</a> SERRANO, Milene; SERRANO, Maurício. *Requisitos (Aula 26): Elicitação, Modelagem e Análise*. Universidade de Brasília – FGA, Brasília, 2023. Disponível em: [https://aprender3.unb.br/pluginfile.php/3210695/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf](https://aprender3.unb.br/pluginfile.php/3210695/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf). Acesso em: 27 Out. 2025.



## Histórico de Versão

| Versão |    Data    |       Descrição      |                                          Autor(es)                                         |                  Revisor(es)                  |
| :----: | :--------: | :------------------: | :----------------------------------------------------------------------------------------: | :-------------------------------------------: |
|  `1.0` | 09/10/2025 | Criação do documento |[Eduarda Domingos](https://github.com/eduardar0) | [Arthur](https://github.com/arthurfernandesj) |
|  `1.1` | 09/10/2025 | Introdução e metodologia | [Eduarda Domingos](https://github.com/eduardar0) | [Arthur](https://github.com/arthurfernandesj) |
|  `1.2` | 09/10/2025 | Adicionando C09 e C10| [Arthur Fernandes](https://github.com/arthurfernandesj) | [Eduarda Domingos](https://github.com/eduardar0) |
|  `1.3` | 28/10/2025 | Preenchimento dos cartões de Dylan (RF12, RF13, RF16, RF24, RF27, RF28) | [Dylan Cavalcante](https://github.com/dylancavalcante) | [Breno Teixeira](https://github.com/BrenoLTeixeira) |

## Agrecimentos

Queremos agradecer ao [Chat GPT](https://chatgpt.com/share/6900b5f9-b0f4-8000-9e22-1c8d3e432359), ferramenta de Inteligência Artificial Generativa, pelo apoio durante o desenvolvimento deste projeto ID Jovem. Sua ajuda foi essencial na revisão de textos, na organização das ideias e na pesquisa de conteúdos complementares que contribuíram para deixar nossa documentação mais clara e completa.

De acordo com o Código de Conduta da Sociedade Brasileira de Computação (SBC), destacamos que a ferramenta foi utilizada apenas como apoio técnico e linguístico.
Todo o conteúdo apresentado é de autoria do Grupo 04, que assume total responsabilidade por sua originalidade e precisão.