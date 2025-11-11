# First Things First

## Introdução

A priorização de requisitos é uma parte importante da engenharia de requisitos, pois ajuda a definir quais funcionalidades devem ser feitas primeiro. Esse processo organiza as funcionalidades de acordo com critérios como valor para o negócio, consequências de não implementar, esforço necessário para o desenvolvimento e possíveis riscos. Assim, a equipe consegue focar no que traz mais benefício e evitar desperdício de recursos. A técnica First Things First junta todos esses fatores em um único índice, facilitando a comparação entre os requisitos. Dessa forma, as decisões se tornam mais claras, consistentes e alinhadas com as limitações de tempo e orçamento do projeto. Além disso, a priorização auxilia no planejamento do trabalho da equipe e garante que o sistema entregue resultados mais próximos das reais necessidades dos usuários.

## Objetivo

O objetivo de utilizar a técnica First Things First no nosso projeto de ID Jovem é priorizar as funcionalidades mais importantes do sistema de forma clara e objetiva, garantindo que a equipe foque no que realmente agrega valor para os usuários. Dessa forma, podemos organizar as tarefas e decisões de desenvolvimento de acordo com critérios de relevância, esforço e impacto, otimizando o uso do tempo e recursos da equipe.

## Justificativa de uso 

A justificativa para usar esta técnica é que o ID Jovem envolve diferentes funcionalidades que precisam ser desenvolvidas e entregues dentro de prazos limitados. Com o First Things First, conseguimos comparar e classificar os requisitos de maneira colaborativa, considerando tanto a importância para os usuários quanto os riscos e esforços de implementação. Isso garante que o projeto avance de forma estruturada, evitando desperdício de tempo em funcionalidades de menor prioridade e aumentando as chances de entregar um sistema útil e eficiente para os jovens beneficiários.

## Integrantes do Grupo

A tabela abaixo apresenta todos os integrantes da equipe que participaram da etapa de priorização de requisitos, assim como a contribuição de cada um durante o desenvolvimento do projeto.

| **Nome** | **Quais Etapas Participou** |
|--------|------|
| Leticia Maria |Participou da priorização presencial (Observador) |
| Arthur Fernandes |Participou da priorização presencial (Redator) e fez a documentação do arquivo |
| Dylan Cavalcante | Participou da priorização presencial (Entrevistador) |

## Metodologia

A etapa de análise e priorização dos requisitos foi conduzida de forma presencial e colaborativa, envolvendo todos os membros da equipe e um usuário real para validação dos itens. O objetivo foi organizar os requisitos de maneira estruturada, identificando quais funcionalidades deveriam receber atenção prioritária no desenvolvimento do projeto.

Para guiar o processo, foram considerados os seguintes critérios de avaliação:

- **Benefício esperado:** identifica o valor ou vantagem que a implementação de cada requisito trará para o sistema e para os usuários.
- **Impacto da não implementação:** avalia as consequências ou prejuízos associados à ausência do requisito.
- **Esforço necessário:** mede os recursos, tempo e complexidade envolvidos na implementação de cada requisito.
- **Probabilidade de risco:** analisa a chance de atrasos, falhas ou dificuldades técnicas durante o desenvolvimento.

O uso desses critérios permitiu uma priorização mais objetiva e fundamentada, auxiliando a equipe a concentrar esforços nas funcionalidades que oferecem maior valor e minimizam riscos ao projeto.

## Tabela da Priorização 

| **ID** | **Categoria** | **Requisito** | **Benefício Relativo** | **Penalidade Relativa** | **Valor Total** | **Custo Relativo** | **Risco Relativo** | **Prioridade** |
|--------|------|--------|------|--------|------|--------|------|------|
| [RF01](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf01) | RF | O sistema deve permitir o cadastro do Jovem Beneficiário por meio do CPF. | 8  | 7 | 20 | 6 | 3  | 4  |
| [RF02](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf02) | RF | O sistema deve fornecer mecanismos de autenticação e login via Gov.br. | 7 | 5 | 6 | 12 | 3 | 2  |
| [RF03](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf03) | RF | O sistema deve permitir a geração e emissão da carteira digital ID Jovem. | 9 | 8 | 15  | 4  | 5  | 6 |
| [RF04](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf04) | RF | O sistema deve permitir a consulta de benefícios como transporte gratuito e meia-entrada em eventos. |6 | 6 | 11| 3 |5  | 5 |
| [RF05](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf05) | RF | O sistema deve validar a carteira digital em estabelecimentos conveniados. | 5 | 5 | 9 | 3 | 4 | 4 |
| [RF06](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf06) | RF | O sistema deve exibir uma seção de perguntas frequentes (FAQ) e suporte ao Jovem Beneficiário. | 6 | 7 | 13 | 7 | 4 | 6 |
| [RF07](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf07) | RF | O sistema deve permitir integração com o CadÚnico para atualização automática de dados. | 7 | 6 | 12 | 4 | 8 | 7 |
| [RF08](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf08) | RF | O sistema deve emitir notificações sobre vencimento, renovação do benefício, novos parceiros e eventos de interesse. | 8 | 7 | 15 | 4 | 6 | 7 |
| [RF09](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf09) | RF | O sistema deve permitir o download da carteirinha para uso offline. | 9 | 9 | 16 | 7 | 8 | 8 |
| [RF10](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf10) | RF | O aplicativo deve disponibilizar informações sobre locais e parceiros que aceitam o benefício. | 6 | 6 | 11 | 4 | 5 | 4 |
| [RF11](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf11) | RF | O sistema deve fornecer canal de suporte via chat, e-mail ou formulário de contato. | 9  | 8 | 12 | 7 | 5 |6  |
| [RF12](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf12) | RF | O aplicativo deve permitir que o Jovem Beneficiário visualize o histórico de utilização dos benefícios. | 7 | 6 | 8 | 5 | 4 | 5 |
| [RF13](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf13) | RF | O sistema deve apresentar uma seção de "Vantagens e Parcerias" com novidades, divulgação sobre o programa e ofertas exclusivas. | 4 | 5 | 9| 5 | 4 | 6 |
| [RF14](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf14) | RF | O aplicativo deve permitir reserva e emissão de comprovantes de uso do benefício. | 10 | 9 | 20 | 7 | 8 | 9 |
| [RF15](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf15) | RF | O sistema deve validar automaticamente a elegibilidade do Jovem Beneficiário ao benefício. | 10  | 10  | 21 | 9 | 6 | 8 |
| [RF16](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf16) | RF | O sistema deve permitir integração com o Gov.br e outros serviços governamentais. | 10 | 9 | 20 | 8 |6  | 8  |
| [RF17](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf17) | RF | O aplicativo deve permitir compartilhar a carteirinha em PDF ou imagem. | 10 | 10 | 22 | 8 | 7 |9  |
| [RF18](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf18) | RF | O sistema deve fornecer informações sobre pendências ou erros relacionados aos benefícios do usuário. | 9  | 9  | 17 | 5 | 7 | 6 |
| [RF19](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf19) | RF | O sistema deve permitir que os usuários atualizem seu cadastro e definam preferências pessoais. | 7 | 8 | 16 | 5 | 6 | 6 |
| [RF20](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf20) | RF | O sistema deve fornecer alertas sobre possíveis irregularidades no uso dos benefícios. | 10 | 9 | 17 | 2 | 5 | 8 |
| [RF21](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf21) | RF | O sistema deve possuir um mapa interativo para visualizar geograficamente parceiros e eventos. | 6 | 5 | 8 | 5 | 7 | 5 |
| [RF22](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf22) | RF | O sistema deve apresentar uma agenda integrada de eventos com filtros de busca. | 6 | 5 | 8 | 7 | 3 | 6 |
| [RF23](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf23) | RF | O sistema deve fornecer um canal para denúncia ou feedback sobre estabelecimentos que recusam o benefício. | 4 | 5 | 7 | 4 | 2 | 8 |
| [RF24](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf24) | RF | O sistema deve permitir que o usuário favorite eventos e estabelecimentos para consulta rápida. | 5 | 3 | 7| 8 |4  |5  |

<font size="2"><p style="text-align: center">Fonte: [Giovana Fontes ](https://github.com/GiovanaFontesS)</p></font>


## Gravação


| **Nome** | **Data** | **Hora** | **Local**| 
|--------|------|--------|------|
| Yasmin Moreira  | 10/11/2025 | 15:00  | FCTE - Gama |




## Referências Bibliográficas

<p><a id="QT1" href="#anchor_intro_wiegers">1.</a> WIEGERS, Karl E. **Software Requirements**. 2. ed. Redmond, WA: Microsoft Press, 2003.</p>

## Bibliografia

> SERRANO, Milene; SERRANO, Maurício. **Requisitos – Aula 07**. Gama, DF: Universidade de Brasília, [s.d.]. Material de aula.

## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :--: | :--: | :-- | :-- | :-- |
| `1.0` | 28/09/2025 | Criação do documento com a descrição da técnica de priorização "First Ting Firts" | [Giovana Fontes](https://github.com/GiovanaFontesS) | [Arthur Fernandes](https://github.com/arthurfernandesj) |
