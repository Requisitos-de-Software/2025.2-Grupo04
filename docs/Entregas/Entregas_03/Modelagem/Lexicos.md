
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


| Simbolo | Tipo | Noção (Descrição Conceitual) | Impacto (Reflexos/Consequências) |
| :-: | :-: | :-: | :-: | 

Os léxicos do sistema ID Jovem foram identificados a partir da utilização do aplicativo e dos [requisitos elicitados](https://github.com/Requisitos-de-Software/2025.2-Grupo04/blob/main/docs/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados.md) nas etapas anteriores. Na tabela 1 abaixo, temos um exemplo de como os léxicos serão apresentados e descritos:

| Léxico         | Sinônimo | Noção   | Impacto             | Classificação       | Rastreabilidade | Fonte      |
| -------------- | -------- | ------- | ------------------- | ------------------- | ------------------- | -----------|  
| Nome do Léxico | Sinônimo | Símbolo | Descrição do efeito | Verbo/Objeto/Estado | Código do requisito referente ao Léxico |Pessoa responsável |

<div style="text-align: center">
<p><b>Tabela 1:</b> Modelo dos léxicos (Autor: <a href="https://github.com/eduardar0">Eduarda</a>, 2025).</p>
</div>

 

## Referências Bibliográficas

< SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 10 [https://aprender3.unb.br/pluginfile.php/3210627/mod_resource/content/1/Aula%2010.pdf]. Brasília: UnB Gama, [2023]. (Disponível em: Aula 10.pdf, com acesso em: 10 out. 2025.)

## Histórico de Versão

| Versão |    Data    |       Descrição      |                                          Autor(es)                                         |                  Revisor(es)                  |
| :----: | :--------: | :------------------: | :----------------------------------------------------------------------------------------: | :-------------------------------------------: |
|  `1.0` | 09/10/2025 | Criação do documento | [Dylan](https://github.com/dylancavalcante) | [Arthur](https://github.com/arthurfernandesj) |
|  `1.1` | 10/10/2025 | Conteúdo introdutório | [Giovana](https://github.com/GiovanaFontesS) |  [Dylan](https://github.com/dylancavalcante) |