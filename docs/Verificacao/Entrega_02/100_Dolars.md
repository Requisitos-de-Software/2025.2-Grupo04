# Verificação da Técnica de Elicitação - $100

## Introdução

Realizado o planejamento do que verificar, é o momento de realizar a inspeção em si. Esse documento apresenta os objetivos da verificação, a metodologia utilizada e os dados da verificação. Além disso, os principais problemas encontrados são sumarizados e analisados obtendo informações valiosas que serão utilizadas para sugerir ações corretivas para os mesmos.

## Objetivo

O objetivo deste documento é relatar os resultados das verificações realizadas acerca do artefato [00 Dólares](https://requisitos-de-software.github.io/2025.2-Grupo04/elicitacao/priorizacao/100/) da Etapa 2 do [grupo](https://github.com/requisitos-de-software/2025.2-Grupo04).

## Metodologia

Os resultados da verificação do artefato foram obtidos a partir de checklist elaborada com base em referências bibliográficas. Para responder às perguntas apresentadas na checklist o avaliador usará as opções **Sim**, **Não**, **Incompleto** ou **Não se aplica**. O avaliador poderá também escrever observações em cada pergunta detalhando pontos que achar necessários.

### Cronograma e Participantes

Os participantes são os integrantes do grupo que serão responsáveis por realizar a verificação e a correção dos problemas encontrados. A tabela 1 apresenta os participantes.

<center>

**Tabela 1** - Participantes da Verificação.

| Participante | Papel |
| :----------: | :---: |
| [Arthur Fernandes](https://github.com/arthurfernandesj) | Avaliador |
| [Breno Lourenço](https://github.com/BrenoLTeixeira) | Revisor |

_Fonte: [Eduarda Domingos](https://github.com/eduardar0), 2025._

</center>

### Sumários dos Dados Encontrados

A tabela 2 a seguir apresenta a checklist com os dados obtidos a partir da verificação.

<center>

**Tabela 2** - Checklist de Verificação.

| ID | Descrição | Avaliação | Observações |
| :-: | :--------- | :-------: | :---------: |
| **Padronização** | | | |
| 1 | O artefato possui introdução? | Sim | - |
| 2 | O artefato possui uma bibliografia/referência bibliográfica? | Sim | - |
| 3 | O artefato possui um histórico de versões com o id e descrição das versões, data, autores e revisores? | Sim | - |
| 4 | Todas as tabelas e imagens são chamadas no texto, possuem legendas e fontes? | Sim | - |
| 5 | Todos os textos estão na norma padrão? | Sim | - |
| **$100** | | | |
| 6 | A priorização foi realizada em conjunto com um usuário real? | Sim | - |
| 6.1 | O usuário que participou se enquadrava no perfil de usuário estabelecido? | Sim | - |
| 7 | Os requisitos priorizados haviam sido previamente elicitados? | Sim | - |
| 7.1 | Os requisitos priorizados passaram por algum processo de validação? | Incompleto | Falta detalhamento. |
| 7.2 | Os requisitos priorizados tinham ID identificando de qual técnica de elicitação eles eram provenientes? | Sim | - |
| 8 | Utilizou-se $100 para serem distribuídos entre os requisitos a fim de priorizá-los? | Sim | - |
| 9 | O processo de priorização levou em consideração a dependência entre requisitos? | Incompleto | Não está explícito. |
| 9.1 | Os requisitos de maior prioridade são também os com mais dependências? | Incompleto | Não foi analisado. |
| 10 | Para o uso posterior desse artefato, fase de modelagem, os requisitos foram separados de forma clara quanto a sua prioridade? | Incompleto | - |
| 10.1 | Os requisitos foram, posteriormente, separados por nível de prioridade? | Não | - |

_Fonte: [Eduarda Domingos](https://github.com/eduardar0), 2025._

</center>

## Problemas Encontrados e Análise dos Dados

### ID 7.1

No artefato, está explícito que os requisitos utilizados foram obtidos através de técnicas de elicitação. No entanto não está aparente se os dados obtidos foram de alguma forma validados, ou seja, se houve reunião com stakeholders para definir se esses requisitos estavam condizentes com o intuito do projeto.

### ID 9

O artefato não menciona explicitamente se as dependências entre requisitos foram consideradas durante o processo de priorização. Esta é uma informação importante para garantir que requisitos interdependentes sejam tratados de forma coerente.

### ID 10.1

Segundo a literatura, é importante que após a obtenção de dados vindos de alguma técnica de priorização, esses requisitos sejam separados de forma clara para que sejam reutilizados de forma eficiente em etapas posteriores do projeto. O artefato apresenta os requisitos ordenados por valor total, mas não os classifica em níveis de prioridade (alta, média, baixa).

## Sugestões de Correção

Tendo em vista os problemas abordados anteriormente, fica como sugestão a realização das seguintes correções:

- Apresentar no artefato se essa priorização foi previamente validada;
- Explicitar se as dependências entre requisitos foram consideradas;
- Classificar os requisitos por níveis de prioridade (alta, média, baixa) após a execução da técnica.





_Fonte: [Eduarda Domingos](https://github.com/eduardar0), 2025._

</center>

## Retrabalho

Como proposto por Fagan, para o retrabalho os autores do artefato verificado serão responsáveis em um primeiro momento por corrigir os problemas apresentados seguindo a lista de sugestão de correção apresentada anteriormente. O responsável por essa verificação fará uma revisão das correções feitas, checando se as correções são suficientes e se foi introduzido novos erros ou não. A tabela 3 a seguir apresenta o cronograma de correções.

<center>

**Tabela 3** - Cronograma de Correções.

| Data de Correção | Descrição | Responsável(eis) | Revisor(es) | Status |
| :--------------: | :-------- | :--------------: | :---------: | :----: |
| 15/11/2025 | Apresentar a validação dos requisitos. | [Letícia Lopes](https://github.com/leticialopes20) | [Arthur Fernandes](https://github.com/arthurfernandesj) | Pendente |
| 15/11/2025 | Explicitar consideração de dependências. | [Letícia Lopes](https://github.com/leticialopes20) | [Arthur Fernandes](https://github.com/arthurfernandesj) | Pendente |
| 15/11/2025 | Classificar requisitos por níveis de prioridade. | [Letícia Lopes](https://github.com/leticialopes20) | [Arthur Fernandes](https://github.com/arthurfernandesj) | Pendente |

_Fonte: [Eduarda Domingos](https://github.com/eduardar0), 2025._

</center>

## Referências Bibliográficas

> COURAGE, C. & BAXTER,K. **Understending your users: a pratical guide to user requirements, methods, tools, and techniques**. San Francisco: Morgan Kaufman Publishers, 2005.

> WIEGERS, Karl; BEATTY, Joy. **Software Requirements (Developer Best Practices)**, 3rd Edition, Microsoft Press, 2013.

> HACKOS, J.T. & REDISH, J.C. **User and task analysis for interface design**. New York: John Wiley & Sons, 1998.

## Histórico de Versões

| Versão | Data       | Descrição | Autor(es) | Revisor(es) |
| :----: | :--------- | :-------- | :-------- | :---------- |
| `1.0`  | 12/11/2025 | Criação da página. | [Eduarda Domingos](https://github.com/eduardar0) | [Breno Lourenço](https://github.com/BrenoLTeixeira) |