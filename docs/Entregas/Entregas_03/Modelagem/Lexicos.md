
# Lexicos

## Introdução 

O Léxico é uma técnica de modelagem de requisitos que estabelece a terminologia e a descrição dos termos relevantes ao projeto, sendo essencialmente um Léxico Ampliado da Linguagem (LAL). Sua finalidade é garantir a comunicação e o entendimento uniformes entre todos os envolvidos, tratando aspectos técnicos e abstratos com clareza. Cada termo, ou símbolo, no Léxico é definido por dois componentes cruciais: a Noção e o Impacto. A Noção provê a descrição conceitual do símbolo, indicando o que ele é ou quem o realiza. Já o Impacto descreve os reflexos e as consequências do termo, como as ações ou mudanças de estado que são desencadeadas. As entradas no Léxico são classificadas em tipos, como Verbo, Objeto e Estado, o que estrutura a linguagem do domínio e serve como uma base sólida para a documentação e análise do sistema.


### *1) Objetivo*
O principal objetivo do Léxico (ou LAL – Léxico Ampliado da Linguagem) é fornecer uma terminologia e a descrição de termos relevantes ao software. Ele tem como foco a atividade de modelagem, que visa elaborar modelos capazes de representar características ou comportamentos de um software. Ao padronizar os termos, o Léxico atua como uma ferramenta para simplificar aspectos muito técnicos ou para tornar mais concreto e claro aspectos muito abstratos do sistema, que muitas vezes são complexos e pouco conhecidos dos clientes.

### *2) Justificativa do Uso*
O uso do Léxico é justificado por ser uma forma de tratar aspectos abstratos ou técnicos com apelo visual , o que melhora a comunicação e a compreensão do sistema. Ao estabelecer a terminologia do domínio, ele garante que todos os envolvidos, incluindo clientes, usem e compreendam a mesma linguagem. Dessa forma, ele contribui para a clareza e objetividade dos modelos de requisitos, sendo fundamental para o desenvolvimento de modelos simples e claros, com notações adequadas.

## Metodologia
A metodologia para a criação do Léxico, conforme apresentado, exige que cada termo, ou símbolo, seja descrito com dois elementos chave: Noção e Impacto.

### **Noção (O Que é e O Que Faz):** 
Define a descrição conceitual do símbolo. Dependendo do tipo de entrada, a Noção pode significar:

* Para um Verbo (ação), quem a realiza, qual ambiente ou procedimento está envolvido.
* Para um Objeto (entidade), sua definição e as ações que podem ser aplicadas a ele.
* Para um Estado (condição), o que ele significa e quais ações levam ou provocam o estado.

### **Impacto (Quais Ações Musculares):** 
Descreve os reflexos ou consequências daquele símbolo.

* Para um Verbo, descreve os reflexos no criador, no ambiente, nos outros criadores, e quais novos estados são consequentes.
* Para um Objeto, as ações que podem ser realizadas para alterar o objeto e o impacto disso no sistema.
* Para um Estado, quais outros estados ou ações podem ordenar o estado que se desenvolve.

Cada entrada no Léxico pertence a somente um tipo (Verbo, Objeto, Estado), e a heurística de definição (Noção e Impacto) é aplicada de acordo com esse tipo. Essa descrição estruturada dos termos é fundamental para o LAL.

## Léxico Ampliado da Linguagem (LAL) do ID Jovem

Os léxicos do sistema ID Jovem foram identificados a partir da utilização do aplicativo e dos [requisitos elicitados](https://github.com/Requisitos-de-Software/2025.2-Grupo04/blob/main/docs/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados.md) nas etapas anteriores. Na tabela 1 abaixo, temos um exemplo de como os léxicos serão apresentados e descritos:

| Léxico         | Sinônimo | Noção   | Impacto             | Classificação       | Rastreabilidade | Fonte      |
| -------------- | -------- | ------- | ------------------- | ------------------- | ------------------- | -----------|  
| Nome do Léxico | Sinônimo | Símbolo | Descrição do efeito | Verbo/Objeto/Estado | Código do requisito referente ao Léxico |Pessoa responsável |

<div style="text-align: center">
<p><b>Tabela 1:</b> Modelo dos léxicos (Fonte: <a href="https://github.com/eduardar0">Eduarda</a>, 2025).</p>
</div>


## Objetos

Os léxicos do tipo objeto referem-se às entidades, elementos ou objetos que são manipulados ou sobre os quais as ações são realizadas dentro do aplicativo ID Jovem. Nas tabelas à seguir, é possível verificar os principais léxicos classificados como objetos que foram identificados no ID Jovem. Esses léxicos incluem elementos como "Jovem Beeficiário", "Carteira Digital" entre outros. Cada um desses léxicos é descrito detalhadamente, incluindo sua noção, que define o objeto e seus relacionamentos com outros objetos, e seu impacto, que descreve as ações possíveis sobre o objeto dentro do sistema.


| Léxico               | Sinônimo            | Noção                        | Impacto                                                                                               | Classificação | Rastreabilidade                           | Fonte                                      |
|----------------------|--------------------|------------------------------|------------------------------------------------------------------------------------------------------|---------------|--------------------------------------------|-------------------------------------------|
| L01 - Jovem Beneficiário        | Jovem, Participante | Dados do jovem             | Permite cadastro, atualização e acesso à carteira digital do ID Jovem.                                | Objeto        | [RF01, RF02, RF15](/docs/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados.md#rf01)             | [Eduarda](https://github.com/eduardar0)                           |
| L02 - Carteira Digital| Carteirinha do ID Jovem    | Identificação digital        | O Jovem Beneficiário pode visualizar, baixar e compartilhar sua carteira digital.                               | Objeto        | [RF03, RF05](/docs/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados.md#rf03)                       | [Eduarda](https://github.com/eduardar0)             |
| L03 -       |    |             |          | Objeto        | [](#)                      | Giovana                                    |
| L04 -       |    |             |          | Objeto        | [](#)                      | Giovana                                    |
| L04 -     |  |         |                    | Objeto        |                        | Arthur                                     |
| L05 -     |       |  | .       | Objeto        | [](#)                            | Arthur                                      |
| L07 -         |   |            |                             | Objeto        | [](#)                            | Breno                                      |
| L08 -       |      |              |                               | Objeto        | [](#)                                  | Breno                        |
| L09 -        |    |              |       | Objeto        | [](#)                                  | Letícia                                    |
| L10 -        |    |              |       | Objeto        | [](#)                                  | Letícia                                    |
| L11 -        |    |              |       | Objeto        | [](#)                                  | Dylan                                    |
| L12 -        |    |              |       | Objeto        | [](#)                                  | Dylan                                    |

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 2: </b>Léxicos classificados como Objetos - ID Jovem (Fonte: Arthur, Breno, Eduarda, Giovana, Leticia, 2025)</p></font>
</div>


<div align="center">
<font size="3"><p style="text-align: center"></p></font>

</div>
## Verbos

Os léxicos do tipo verbo representam ações ou operações que os Jovens Beneficiários podem executar dentro do aplicativo "ID Jovem". Essas ações detalham as funcionalidades acessíveis para os Jovens Beneficiários, permitindo interações específicas e operações dentro do aplicativo. Na Tabela 3, é possível conferir os principais léxicos classificados como verbos que foram identificados no ID Jovem. Esses léxicos incluem ações como "Cadastrar" e "Autenticar", cada uma descrevendo uma interação essencial que os Jovens Beneficiários podem realizar. Além disso, esses léxicos ajudam a definir os fluxos de uso do aplicativo, orientando os Jovens Beneficiários em suas tarefas e melhorando a experiência de navegação e uso dos serviços disponíveis.

| Léxico | Sinônimo | Noção | Impacto | Classificação | Rastreabilidade | Fonte |
|--------|----------|-------|---------|---------------|-----------------|-------|
| L13 - Cadastrar | Registrar, Incluir | Ação de criar um novo cadastro no sistema ID Jovem | Permite que o Jovem Beneficiário tenha acesso aos benefícios e serviços do programa | Verbo | [RF01](../../Elicitacao/Requisitos_Elicitados.md#rf01) | [Eduarda](https://github.com/eduardar0) |
| L14 - Autenticar | Logar, Acessar | Processo de verificação de identidade via Gov.br | Permite o acesso seguro às funcionalidades do aplicativo ID Jovem | Verbo | [RF02](../../Elicitacao/Requisitos_Elicitados.md#rf02) | [Eduarda](https://github.com/eduardar0) |
| L15 |  |  |  | Verbo | [](#) | Giovana |
| L16 |  |  |  | Verbo | [](#) | Arthur |
| L17 |  |  |  | Verbo | [](#) | Dylan |
| L18 |  |  |  | Verbo | [](#) | Breno |
| L19 |  |  |  | Verbo | [](#) | Leticia |
| L20 |  |  |  | Verbo | [](#) | Leticia |

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 3:</b> Léxicos classificados como Verbos (Fonte: Arthur, Breno, Eduarda, Giovana, Leticia, 2025)</p></font>
</div>

## Estados

Os léxicos do tipo estado referem-se às condições, situações ou configurações específicas que podem ocorrer dentro do aplicativo "ID Jovem". Esses estados representam diversos cenários em que o Jovem Beneficiário ou o sistema pode se encontrar durante a interação com o aplicativo. Na Tabela 4, é possível verificar os principais léxicos classificados como estados que foram identificados no ID Jovem. Esses léxicos incluem estados como "Elegível", "Ativo" e "Vencido", cada um descrevendo uma condição específica que afeta as ações subsequentes e as opções disponíveis para o Jovem Beneficiário. A compreensão desses estados é essencial para navegar eficientemente pelo aplicativo e utilizar suas funcionalidades de forma eficaz.

| Léxico | Sinônimo | Noção | Impacto | Classificação | Rastreabilidade | Fonte |
|--------|----------|-------|---------|---------------|-----------------|-------|
| L21 - Elegível | Qualificado, Aptidão | Condição do Jovem Beneficiário que atende aos critérios do programa | Permite o acesso e utilização dos benefícios do ID Jovem | Estado | [RF15](../../Elicitacao/Requisitos_Elicitados.md#rf15) | [Eduarda](https://github.com/eduardar0) |
| L22 - Ativo | Válido, Vigente | Estado da carteira digital que está dentro do prazo de validade | Permite a utilização dos benefícios em estabelecimentos parceiros | Estado | [RF03](../../Elicitacao/Requisitos_Elicitados.md#rf03) | [Eduarda](https://github.com/eduardar0) |
| L23 |  |  |  | Estado | [](#) | Giovana |
| L24 |  |  |  | Estado | [](#) | Arthur |
| L25 |  |  |  | Estado | [](#) | Dylan |
| L26 |  |  |  | Estado | [](#) | Breno |
| L27 |  |  |  | Estado | [](#) | Leticia |
| L28 |  |  |  | Estado | [](#) | Leticia |

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 4: </b>Léxicos classificados como Estados (Autor: Fonte: Arthur, Breno, Eduarda, Giovana, Leticia, 2025)</p></font>
</div>


## Referências Bibliográficas

< SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 10 [https://aprender3.unb.br/pluginfile.php/3210627/mod_resource/content/1/Aula%2010.pdf]. Brasília: UnB Gama, [2023]. (Disponível em: Aula 10.pdf, com acesso em: 10 out. 2025.)

## Histórico de Versão

| Versão |    Data    |       Descrição      |                                          Autor(es)                                         |                  Revisor(es)                  |
| :----: | :--------: | :------------------: | :----------------------------------------------------------------------------------------: | :-------------------------------------------: |
|  `1.0` | 09/10/2025 | Criação do documento | [Dylan](https://github.com/dylancavalcante) | [Arthur](https://github.com/arthurfernandesj) |
|  `1.1` | 10/10/2025 | Conteúdo introdutório | [Giovana](https://github.com/GiovanaFontesS) |  [Dylan](https://github.com/dylancavalcante) |
|  `1.2` | 11/10/2025 | Criação das tabelas de: Objetos, verbos e Estados | [Eduarda](https://github.com/eduardar0) |  [Giovana](https://github.com/GiovanaFontesS) |
|  `1.3` | 11/10/2025 | Fix: tabela quebrada | [Eduarda](https://github.com/eduardar0) | [Dylan](https://github.com/dylancavalcante) |

