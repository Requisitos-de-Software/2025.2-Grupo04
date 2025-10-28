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
      <td align="left"></td>
    </tr>
    <tr>
      <td align="center"><a href="https://github.com/BrenoLTeixeira">Breno Teixeira</a></td>
      <td align="left"></td>
    </tr>
    <tr>
      <td align="center"><a href="https://github.com/dylancavalcante">Dylan Cavalcante</a></td>
      <td align="left"></td>
    </tr>
    <tr>
      <td align="center"><a href="https://github.com/eduardar0">Eduarda Domingos</a></td>
      <td align="left"></td>
    </tr>
    <tr>
      <td align="center"><a href="https://github.com/GiovanaFontesS">Giovana Fontes</a></td>
      <td align="left"></td>
    </tr>
    <tr>
      <td align="center"><a href="https://github.com/leticialopes20">Letícia Lopes</a></td>
      <td align="left"></td>
    </tr>
  </tbody>
</table>
</div>

### RF01

<div align="center">
  <strong>Tabela 3 -</strong> Cartão do Requisito 01 - C01
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** |                 |
| **Descrição do Requisito** | |
| **Elos Backward-from:** | |
| **Elos Forward-from:** | |

<p align="center">Fonte: <a href="https://github.com/GiovanaFontesS">Giovana Fontes</a></p>

### RF02

<div align="center">
  <strong>Tabela 4 -</strong> Cartão do Requisito 02 - C02
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** |                 |
| **Descrição do Requisito** | |
| **Elos Backward-from:** | |
| **Elos Forward-from:** | |

<p align="center">Fonte: <a href="https://github.com/GiovanaFontesS">Giovana Fontes</a></p>

### RF03

<div align="center">
  <strong>Tabela 5 -</strong> Cartão do Requisito 03 - C03
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** |                 |
| **Descrição do Requisito** | |
| **Elos Backward-from:** | |
| **Elos Forward-from:** | |

<p align="center">Fonte: <a href="https://github.com/leticialopes20">Leticia Lopes</a></p>

### RF04

<div align="center">
  <strong>Tabela 6 -</strong> Cartão do Requisito 04 - C04
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** |                 |
| **Descrição do Requisito** | |
| **Elos Backward-from:** | |
| **Elos Forward-from:** | |

<p align="center">Fonte: <a href="https://github.com/leticialopes20">Leticia Lopes</a></p>

### RF05

<div align="center">
  <strong>Tabela 7 -</strong> Cartão do Requisito 05 - C05
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** |                 |
| **Descrição do Requisito** | |
| **Elos Backward-from:** | |
| **Elos Forward-from:** | |

<p align="center">Fonte: <a href="https://github.com/leticialopes20">Leticia Lopes</a></p>

### RF06

<div align="center">
  <strong>Tabela 8 -</strong> Cartão do Requisito 06 - C06
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** |                 |
| **Descrição do Requisito** | |
| **Elos Backward-from:** | |
| **Elos Forward-from:** | |

<p align="center">Fonte: <a href="https://github.com/eduardar0">Eduarda Domingos</a></p>

### RF07

<div align="center">
  <strong>Tabela 9 -</strong> Cartão do Requisito 07 - C07
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** |       |
| **Descrição do Requisito** |  |
| **Elos Backward-from:** | |
| **Elos Forward-from:** | |

<p align="center">Fonte: <a href="https://github.com/leticialopes20">Leticia Lopes</a></p>

### RF08

<div align="center">
  <strong>Tabela 10 -</strong> Cartão do Requisito 08 - C08
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** |                 |
| **Descrição do Requisito** | |
| **Elos Backward-from:** | |
| **Elos Forward-from:** | |

<p align="center">Fonte: <a href="https://github.com/leticialopes20">Leticia Lopes</a></p>

### RF09

<div align="center">
  <strong>Tabela 11 -</strong> Cartão do Requisito 09 - C09
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** |                 |
| **Descrição do Requisito** | |
| **Elos Backward-from:** | |
| **Elos Forward-from:** | |

<p align="center">Fonte: <a href="https://github.com/eduardar0">Eduarda Domingos</a></p>

### RF10

<div align="center">
  <strong>Tabela 12 -</strong> Cartão do Requisito 10 - C10
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF10](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf10) , [BS10](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming), [ST06](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Storytelling), [UC03](), [CEN03](), [US03]()                |
| **Descrição do Requisito** |  aplicativo deve disponibilizar informações sobre locais e parceiros que aceitam o benefício.|
| **Elos Backward-from:** | Agregação: RF10 ← BS10 - O requisito foi identificado através de brainstorming.<br>Agregação: RF10 ← ST06 - O requisito foi identificado através de storytelling.  |
| **Elos Forward-from:** | Satisfação: RF10 → UC03 - O requisito deu origem ao caso de uso "Consultar Locais e Parceiros".<br>Satisfação: RF10 → CEN03 - O requisito deu origem ao cenário "Consulta de Locais e Parceiros que Aceitam o Benefício".<br>Satisfação: RF10 → US03 - O requisito deu origem à história de usuário "Disponibilizar informações sobre locais e parceiros que aceitam o benefício". |

<p align="center">Fonte: <a href="https://github.com/eduardar0">Eduarda Domingos</a></p>

### RF11

<div align="center">
  <strong>Tabela 13 -</strong> Cartão do Requisito 11 - C11
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF11](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf11), [ENT05](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/), [BS08](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming), [IDJ05](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspecção/), [UC04](), [CEN04](), [US04]()                 |
| **Descrição do Requisito** | O sistema deve fornecer canal de suporte via chat, e-mail ou formulário de contato. |
| **Elos Backward-from:** |Agregação: RF11 ← ENT05 - O requisito foi identificado através de entrevista.<br>Agregação: RF11 ← BS08 - O requisito foi identificado através de brainstorming.<br>Agregação: RF11 ← IDJ05 - O requisito foi identificado através de introspecção. |
| **Elos Forward-from:** | Satisfação: RF11 → UC04 - O requisito deu origem ao caso de uso "Solicitar Suporte ao Beneficiário".<br>Satisfação: RF11 → CEN04 - O requisito deu origem ao cenário "Canal de Suporte via Chat, E-mail ou Formulário de Contato".<br>Satisfação: RF11 → US04 - O requisito deu origem à história de usuário "Fornecer canal de suporte via chat, e-mail ou formulário de contato".|

<p align="center">Fonte: <a href="https://github.com/eduardar0">Eduarda Domingos</a></p>

### RF12

<div align="center">
  <strong>Tabela 14 -</strong> Cartão do Requisito 12 - C12
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** |       |
| **Descrição do Requisito** |  |
| **Elos Backward-from:** | |
| **Elos Forward-from:** | |

<p align="center">Fonte: <a href="https://github.com/dylancavalcante">Dylan Cavalcante</a></p>

### RF13

<div align="center">
  <strong>Tabela 15 -</strong> Cartão do Requisito 13 - C13
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** |       |
| **Descrição do Requisito** |  |
| **Elos Backward-from:** | |
| **Elos Forward-from:** | |

<p align="center">Fonte: <a href="https://github.com/dylancavalcante">Dylan Cavalcante</a></p>

### RF14

<div align="center">
  <strong>Tabela 16 -</strong> Cartão do Requisito 14 - C14
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** |       |
| **Descrição do Requisito** |  |
| **Elos Backward-from:** | |
| **Elos Forward-from:** | |

<p align="center">Fonte: <a href="https://github.com/eduardar0">Eduarda Domingos</a></p>

### RF15

<div align="center">
  <strong>Tabela 17 -</strong> Cartão do Requisito 15 - C15
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** |       |
| **Descrição do Requisito** |  |
| **Elos Backward-from:** | |
| **Elos Forward-from:** | |

<p align="center">Fonte: <a href="https://github.com/eduardar0">Eduarda Domingos</a></p>

### RF16

<div align="center">
  <strong>Tabela 18 -</strong> Cartão do Requisito 16 - C16
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** |       |
| **Descrição do Requisito** |  |
| **Elos Backward-from:** | |
| **Elos Forward-from:** | |

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
| **Elos Forward-from:** | Satisfação: RF17 → UC17 - O requisito deu origem ao caso de uso "Compartilhar Carteirinha Digital".<br>Satisfação: RF17 → CEN17 - O requisito deu origem ao cenário "Compartilhar Carteirinha Digital em PDF ou Imagem".<br>Satisfação: RF17 → US17 - O requisito deu origem à história de usuário "Como jovem beneficiário, quero compartilhar minha carteirinha digital em PDF ou imagem para comprovar meus benefícios facilmente." | 

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
| **Elementos:** |       |
| **Descrição do Requisito** |  |
| **Elos Backward-from:** | |
| **Elos Forward-from:** | |

<p align="center">Fonte: <a href="https://github.com/brenolteixeira">Breno Teixeira</a></p>

### RF20

<div align="center">
  <strong>Tabela 22 -</strong> Cartão do Requisito 20 - C20
</div>

| **Categoria:** | Acessibilidade e Usabilidade |
|:---------------|:------------------------------|
| **Elementos:** | [RF20](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf20), [ENT09](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/), [IDJ18](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspecção/#idj18) , [UC09](), [CEN09](), [US09]() |
| **Descrição do Requisito:** | O sistema deve fornecer alertas sobre possíveis irregularidades no uso dos benefícios, identificando padrões suspeitos |
| **Elos Backward-from:** | Agregação: RF20 ← ENT09 - O requisito foi identificado a partir de entrevistas com stakeholders (usuários/gestores) que relataram a necessidade de monitoramento e prevenção de uso indevido do benefício. |
| **Elos Forward-from:** | Satisfação: RF20 → UC20 - O requisito deu origem ao caso de uso “Monitorar e Notificar Irregularidades de Uso”.<br>Satisfação: RF20 → CEN20 - O requisito deu origem ao cenário “Detecção de Padrão Suspeito e Emissão de Alerta”.<br>Satisfação: RF20 → US20 - O requisito deu origem à história de usuário “Como gestor do programa, desejo receber alertas sobre possíveis irregularidades para investigar fraudes e proteger os benefícios.” |
<p align="center">Fonte: <a href=https://github.com/arthurfernandesj">Arthur Fernandes</a></p>


### RF21

<div align="center">
  <strong>Tabela 12 -</strong> Cartão do Requisito 10 - C10
</div>

| **Categoria:** | Desenvolvimento e Experiência do Usuário |
|:---------------|:----------------|
| **Elementos:** | [RF21](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf21), [ENT10](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/), [ST06](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Storytelling/), [IDJ06](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspecção/#idj06), [UC21](), [CEN21](), [US21]() |
| **Descrição do Requisito:** | O sistema deve possuir um mapa interativo que permita visualizar geograficamente os parceiros e eventos culturais vinculados ao programa ID Jovem. |
| **Elos Backward-from:** | Agregação: RF21 ← ENT10 - O requisito foi identificado a partir das entrevistas, nas quais os usuários destacaram a importância de localizar visualmente os parceiros e eventos culturais próximos.<br>Agregação: RF21 ← ST06 - O requisito foi reforçado pelo storytelling, onde o jovem desejava encontrar facilmente locais parceiros e eventos acessíveis. |
| **Elos Forward-from:** | Satisfação: RF21 → UC21 - O requisito deu origem ao caso de uso “Visualizar Parceiros e Eventos em Mapa Interativo”.<br>Satisfação: RF21 → CEN21 - O requisito deu origem ao cenário “Consulta e Interação com o Mapa de Parceiros e Eventos”.<br>Satisfação: RF21 → US21 - O requisito deu origem à história de usuário “Como jovem beneficiário, desejo visualizar no mapa os parceiros e eventos próximos para facilitar meu acesso aos benefícios culturais.” |


<p align="center">Fonte: <a href=https://github.com/arthurfernandesj">Arthur Fernandes</a></p>

### RF22

<div align="center">
  <strong>Tabela 24 -</strong> Cartão do Requisito 22 - C22
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF21](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf21), [ENT10](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/), [ST06](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Storytelling/), [IDJ06](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspecção/#idj06), [UC21](), [CEN21](), [US21]() |
| **Descrição do Requisito:** | O sistema deve possuir um mapa interativo que permita visualizar geograficamente os parceiros e eventos culturais vinculados ao programa ID Jovem. |
| **Elos Backward-from:** | Agregação: RF21 ← ENT10 - O requisito foi identificado a partir das entrevistas, nas quais os usuários destacaram a importância de localizar visualmente os parceiros e eventos culturais próximos.<br>Agregação: RF21 ← ST06 - O requisito foi reforçado pelo storytelling, onde o jovem desejava encontrar facilmente locais parceiros e eventos acessíveis. |
| **Elos Forward-from:** | Satisfação: RF21 → UC21 - O requisito deu origem ao caso de uso “Visualizar Parceiros e Eventos em Mapa Interativo”.<br>Satisfação: RF21 → CEN21 - O requisito deu origem ao cenário “Consulta e Interação com o Mapa de Parceiros e Eventos”.<br>Satisfação: RF21 → US21 - O requisito deu origem à história de usuário “Como jovem beneficiário, desejo visualizar no mapa os parceiros e eventos próximos para facilitar meu acesso aos benefícios culturais.” |


<p align="center">Fonte: <a href="https://github.com/leticialopes20">Leticia Lopes</a></p>

### RF23

<div align="center">
  <strong>Tabela 25 -</strong> Cartão do Requisito 23 - C23
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** |       |
| **Descrição do Requisito** |  |
| **Elos Backward-from:** | |
| **Elos Forward-from:** | |

<p align="center">Fonte: <a href="https://github.com/brenolteixeira">Breno Teixeira</a></p>

### RF24

<div align="center">
  <strong>Tabela 26 -</strong> Cartão do Requisito 24 - C24
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** |       |
| **Descrição do Requisito** |  |
| **Elos Backward-from:** | |
| **Elos Forward-from:** | |

<p align="center">Fonte: <a href="https://github.com/dylancavalcante">Dylan Cavalcante</a></p>

### RF25

<div align="center">
  <strong>Tabela 27 -</strong> Cartão do Requisito 25 - C25
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** |       |
| **Descrição do Requisito** |  |
| **Elos Backward-from:** | |
| **Elos Forward-from:** | |

<p align="center">Fonte: <a href="https://github.com/GiovanaFontesS">Giovana Fontes</a></p>

### RF26

<div align="center">
  <strong>Tabela 28 -</strong> Cartão do Requisito 26 - C26
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** |       |
| **Descrição do Requisito** |  |
| **Elos Backward-from:** | |
| **Elos Forward-from:** | |

<p align="center">Fonte: <a href="https://github.com/GiovanaFontesS">Giovana Fontes</a></p>

### RF27

<div align="center">
  <strong>Tabela 29 -</strong> Cartão do Requisito 27 - C27
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** |       |
| **Descrição do Requisito** |  |
| **Elos Backward-from:** | |
| **Elos Forward-from:** | |

<p align="center">Fonte: <a href="https://github.com/dylancavalcante">Dylan Cavalcante</a></p>

### RF28

<div align="center">
  <strong>Tabela 30 -</strong> Cartão do Requisito 28 - C28
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** |       |
| **Descrição do Requisito** |  |
| **Elos Backward-from:** | |
| **Elos Forward-from:** | |

<p align="center">Fonte: <a href="https://github.com/dylancavalcante">Dylan Cavalcante</a></p>

### RF29

<div align="center">
  <strong>Tabela 31 -</strong> Cartão do Requisito 29 - C29
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** |       |
| **Descrição do Requisito** |  |
| **Elos Backward-from:** | |
| **Elos Forward-from:** | |

<p align="center">Fonte: <a href="https://github.com/brenolteixeira">Breno Teixeira</a></p>

### RF30

<div align="center">
  <strong>Tabela 32 -</strong> Cartão do Requisito 30 - C30
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** |       |
| **Descrição do Requisito** |  |
| **Elos Backward-from:** | |
| **Elos Forward-from:** | |

<p align="center">Fonte: <a href="https://github.com/brenolteixeira">Breno Teixeira</a></p>

### RF31

<div align="center">
  <strong>Tabela 33 -</strong> Cartão do Requisito 31 - C31
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** |       |
| **Descrição do Requisito** |  |
| **Elos Backward-from:** | |
| **Elos Forward-from:** | |

<p align="center">Fonte: <a href="https://github.com/brenolteixeira">Breno Teixeira</a></p>

### RF32

<div align="center">
  <strong>Tabela 34 -</strong> Cartão do Requisito 32 - C32
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** |       |
| **Descrição do Requisito** |  |
| **Elos Backward-from:** | |
| **Elos Forward-from:** | |

<p align="center">Fonte: <a href="https://github.com/brenolteixeira">Breno Teixeira</a></p>

### RF33

<div align="center">
  <strong>Tabela 35 -</strong> Cartão do Requisito 33 - C33
</div>

| **Categoria:** | Segurança e Auditoria |
|:---------------|:----------------------|
| **Elementos:** | [RF33](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf33), [ADD12](), [IDJ19](), [UC33](), [CEN33](), [US33]() |
| **Descrição do Requisito:** | O sistema deve registrar logs detalhados de acesso e de ações executadas pelos usuários, com informações como data, hora, tipo de ação, identificador do usuário e resultados das operações. Esses registros devem ser armazenados de forma segura, imutável e acessível apenas por administradores autorizados, permitindo auditorias e rastreamento de incidentes de segurança. |
| **Elos Backward-from:** | Agregação: RF33 ← ADD12 - O requisito foi adicionado com base na necessidade identificada durante a fase de adição, para reforçar a segurança e rastreabilidade do sistema.<br>Relação: RF33 ← IDJ19 - O requisito está diretamente associado à confiabilidade do sistema e à capacidade de auditoria de tentativas de validação. |
| **Elos Forward-from:** | Satisfação: RF33 → UC33 - O requisito deu origem ao caso de uso “Registrar e Consultar Logs de Auditoria”.<br>Satisfação: RF33 → CEN33 - O requisito deu origem ao cenário “Registro e Verificação de Ações para Auditoria”.<br>Satisfação: RF33 → US33 - O requisito deu origem à história de usuário “Como administrador, desejo visualizar registros de acesso e ações dos usuários para garantir a segurança e integridade do sistema.” |


<p align="center">Fonte: <a href="https://github.com/arthurfernandesj">Arthur Fernandes</a></p>

### RF34

<div align="center">
  <strong>Tabela 36 -</strong> Cartão do Requisito 34 - C34
</div>


| **Categoria:** | Notificações e Comunicação com o Usuário |
|:---------------|:------------------------------------------|
| **Elementos:** | [RF34](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf34), [BS12](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/), [IDJ11](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#idj11), [UC34](), [CEN34](), [US34]() |
| **Descrição do Requisito:** | O aplicativo deve enviar alertas e notificações aos jovens beneficiários sobre atualizações importantes do programa ID Jovem, como mudanças em regras, datas de vencimento de benefícios ou novos parceiros e eventos culturais. As notificações devem ser claras, oportunas e acessíveis em múltiplos canais (push notifications, e-mail ou SMS). |
| **Elos Backward-from:** | Agregação: RF34 ← BS12 - O requisito foi identificado durante brainstorming com a equipe, destacando a necessidade de manter os usuários informados.<br>Relação: RF34 ← IDJ11 - O requisito está diretamente associado à funcionalidade de envio de notificações sobre vencimento ou atualizações do programa. |
| **Elos Forward-from:** | Satisfação: RF34 → UC34 - O requisito deu origem ao caso de uso “Enviar Alertas e Notificações aos Usuários”.<br>Satisfação: RF34 → CEN34 - O requisito deu origem ao cenário “Recebimento de Notificações sobre Atualizações do Programa”.<br>Satisfação: RF34 → US34 - O requisito deu origem à história de usuário “Como jovem beneficiário, desejo receber alertas sobre novidades e mudanças no programa para não perder benefícios importantes.” |


<p align="center">Fonte: <a href="https://github.com/arthurfernandesj">Arthur Fernandes</a></p>

### RF35

<div align="center">
  <strong>Tabela 37 -</strong> Cartão do Requisito 35 - C35
</div>


| **Categoria:** | Segurança e Gestão de Conta |
|:---------------|:----------------------------|
| **Elementos:** | [RF35](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf35), [ADD13](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Analise_de_Documentos), [ENT22](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista), [UC35](), [CEN35](), [US35]() |
| **Descrição do Requisito:** | O sistema deve permitir que o usuário altere sua senha de acesso diretamente pelo aplicativo, garantindo segurança, facilidade de uso e validação de regras de complexidade de senha (como mínimo de caracteres, uso de letras, números e símbolos). A funcionalidade deve notificar o usuário sobre alterações bem-sucedidas e bloquear temporariamente tentativas suspeitas de alteração. |
| **Elos Backward-from:** | Agregação: RF35 ← ADD13 - O requisito foi adicionado durante a fase de adição para melhorar a autonomia do usuário sobre sua conta.<br>Agregação: RF35 ← ENT22 - O requisito foi identificado a partir de entrevistas, nas quais usuários expressaram a necessidade de alterar senhas de forma segura e independente. |
| **Elos Forward-from:** | Satisfação: RF35 → UC35 - O requisito deu origem ao caso de uso “Alterar Senha de Acesso pelo Aplicativo”.<br>Satisfação: RF35 → CEN35 - O requisito deu origem ao cenário “Usuário altera senha com validação de segurança e notificação de sucesso”.<br>Satisfação: RF35 → US35 - O requisito deu origem à história de usuário “Como jovem beneficiário, desejo alterar minha senha pelo aplicativo para manter minha conta segura sem depender de terceiros.” |

<p align="center">Fonte: <a href="https://github.com/arthurfernandesj">Arthur Fernandes</a></p>

### RF36

<div align="center">
  <strong>Tabela 38 -</strong> Cartão do Requisito 36 - C36
</div>

| **Categoria:** | Integração e Localização |
|:---------------|:-------------------------|
| **Elementos:** | [RF36](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf36), [BS12](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/), [IDJ12](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspecção/), [UC36](), [CEN36](), [US36]() |
| **Descrição do Requisito:** | O aplicativo deve fornecer integração com GPS para localizar estabelecimentos parceiros próximos em tempo real, permitindo ao usuário visualizar sua localização atual, encontrar rapidamente os pontos mais próximos, obter rotas e estimativas de distância, e filtrar estabelecimentos por tipo de serviço ou benefício oferecido. |
| **Elos Backward-from:** | Agregação: RF36 ← BS13 - O requisito foi identificado durante brainstorming, destacando a importância de integração com localização em tempo real.<br>Relação: RF36 ← IDJ12 - O requisito está relacionado ao risco de o jovem não conseguir localizar parceiros devido a dados desatualizados no CadÚnico, reforçando a necessidade de GPS e integração em tempo real. |


<p align="center">Fonte: <a href="https://github.com/arthurfernandesj">Arthur Fernandes</a></p>




---

## **Referências Bibliográficas**

> <a id="RP1" href="#TEC1">[1]</a> SAYÃO, Miriam; LEITE, Julio. *Rastreabilidade de Requisitos*. Rio de Janeiro: Departamento de Informática – PUC-Rio, 2005. Disponível em: [https://www-di.inf.puc-rio.br/~julio/rastre.pdf](https://www-di.inf.puc-rio.br/~julio/rastre.pdf). Acesso em: 27 Out. 2025.  

> <a id="RP2" href="#TEC2">[2]</a> KOTONYA, Gerald; SOMMERVILLE, Ian. *Requirements Engineering: Processes and Techniques*. John Wiley & Sons, 1998. Disponível em: [https://www.acqnotes.com/Attachments/The%20Requirements%20Engineering%20Handbook%20by%20Ralph%20R.%20Young.pdf](https://www.acqnotes.com/Attachments/The%20Requirements%20Engineering%20Handbook%20by%20Ralph%20R.%20Young.pdf). Acesso em: 27 Out. 2025.  

> <a id="RP3" href="#TEC3">[3]</a> SERRANO, Milene; SERRANO, Maurício. *Requisitos (Aula 26): Elicitação, Modelagem e Análise*. Universidade de Brasília – FGA, Brasília, 2023. Disponível em: [https://aprender3.unb.br/pluginfile.php/3210695/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf](https://aprender3.unb.br/pluginfile.php/3210695/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf). Acesso em: 27 Out. 2025.



## Histórico de Versão

| Versão |    Data    |       Descrição      |                                          Autor(es)                                         |                  Revisor(es)                  |
| :----: | :--------: | :------------------: | :----------------------------------------------------------------------------------------: | :-------------------------------------------: |
|  `1.0` | 09/10/2025 | Criação do documento |[Eduarda Domingos](https://github.com/eduardar0) | [Arthur](https://github.com/arthurfernandesj) |
|  `1.1` | 09/10/2025 | Introdução e metodologia | [Eduarda Domingos](https://github.com/eduardar0) | [Arthur](https://github.com/arthurfernandesj) |
|  `1.2` | 09/10/2025 | Adicionando C09 e C10| [Arthur Fernandes](https://github.com/arthurfernandesj) | [Eduarda Domingos](https://github.com/eduardar0) |

## Agrecimentos

Queremos agradecer ao [Chat GPT](https://chatgpt.com/share/6900b5f9-b0f4-8000-9e22-1c8d3e432359), ferramenta de Inteligência Artificial Generativa, pelo apoio durante o desenvolvimento deste projeto ID Jovem. Sua ajuda foi essencial na revisão de textos, na organização das ideias e na pesquisa de conteúdos complementares que contribuíram para deixar nossa documentação mais clara e completa.

De acordo com o Código de Conduta da Sociedade Brasileira de Computação (SBC), destacamos que a ferramenta foi utilizada apenas como apoio técnico e linguístico.
Todo o conteúdo apresentado é de autoria do Grupo 04, que assume total responsabilidade por sua originalidade e precisão.