## Introdução

<p style="text-align: justify;">Após o planejamento da verificação, foi iniciada a inspeção do artefato <b>Casos de Uso</b> referente ao aplicativo <b>ID Jovem</b>. O propósito da verificação é garantir que os Casos de Uso estejam devidamente estruturados, coerentes com os requisitos levantados e alinhados aos objetivos do aplicativo. A análise verifica se as interações dos atores, fluxos principais, alternativos e exceções estão corretamente documentados, seguindo os padrões da UML e as boas práticas de especificação. Como referência, utilizou-se (VAZQUEZ; SIMÕES, 2016) <a href="#RP1">[1]</a>, com foco no Capítulo 8.12 (Técnica: modelagem de casos de uso) e Capítulo 2.6 (Critérios de qualidade da especificação). Durante o processo, foram coletadas informações e identificadas inconsistências, com o intuito de aprimorar o artefato e assegurar sua adequação ao desenvolvimento do sistema.</p>

<small><em>Revisado por [Gemini](https://gemini.google.com/), em 12 de Novembro 2025</em></small>


## Objetivo 

<p style="text-align: justify;">O presente documento tem como finalidade relatar os resultados obtidos na verificação do artefato <b>Casos de Uso</b> do aplicativo <b>ID Jovem</b>, em sua versão 1.8, datada de 12/10/2025, integrante da Entrega 2 do grupo 4.</p>

## Metodologia 

<p style="text-align: justify;">A verificação foi conduzida com base na checklist definida na etapa de planejamento. Cada item da lista, focado na correta especificação dos casos de uso conforme (VAZQUEZ; SIMÕES, 2016) <a href="#RP1">[1]</a>, foi avaliado individualmente, sendo marcado como <b>Sim</b>, <b>Não</b> ou <b>Incompleto</b>. Quando necessário, os avaliadores adicionaram observações complementares para justificar as marcações e sugerir ajustes que contribuam para a melhoria do artefato.</p>

<h3 style="text-align: center;">Tabela 1: Participantes</h3>

<div align="center">

<table border="1" style="border-collapse: collapse; width: 80%; text-align: center;">
  <thead>
    <tr>
      <th>Nome</th>
      <th>Função</th>
      <th>Item</th>
      <th>Data</th>
      <th>Hora</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://github.com/GiovanaFontesS" target="_blank">Giovana Fontes</a></td>
      <td>Avaliadora</td>
      <td>1</td>
      <td>12/11/2025</td>
      <td>14:00</td>
    </tr>
    <tr>
      <td><a href="https://github.com/BrenoLTeixeira" target="_blank">Breno Teixeira</a></td>
      <td>Avaliador</td>
      <td>2</td>
      <td>12/11/2025</td>
      <td>14:15</td>
    </tr>
    <tr>
      <td><a href="https://github.com/arthurfernandesj" target="_blank">Arthur Fernandes</a></td>
      <td>Avaliador</td>
      <td>3</td>
      <td>12/11/2025</td>
      <td>14:30</td>
    </tr>
    <tr>
      <td><a href="https://github.com/dylancavalcante" target="_blank">Dylan Cavalcante</a></td>
      <td>Avaliador</td>
      <td>4</td>
      <td>12/11/2025</td>
      <td>14:45</td>
    </tr>
    <tr>
      <td><a href="https://github.com/eduardar0" target="_blank">Eduarda Rodrigues</a></td>
      <td>Avaliadora</td>
      <td>5, 6</td>
      <td>12/11/2025</td>
      <td>15:00</td>
    </tr>
    <tr>
      <td><a href="https://github.com/leticialopes20" target="_blank">Letícia Maria</a></td>
      <td>Avaliadora</td>
      <td>7</td>
      <td>12/11/2025</td>
      <td>15:15</td>
    </tr>
  </tbody>
</table>
<p style="text-align: center; font-size: 0.9em; color: gray;">
Fonte: <a href="https://github.com/BrenoLTeixeira" target="_blank">Breno Teixeira</a>
</p>
</div>



## Lista de Verificação 1.4 Casos de Uso

<p style="text-align: justify;">A seguir, apresenta-se a tabela com os itens utilizados na verificação do artefato <b>Casos de Uso</b> do aplicativo <b>ID Jovem</b>. O objetivo é assegurar que os diagramas e as especificações textuais sigam os padrões de modelagem (Cap 8.12) e os critérios de qualidade para especificação (Cap 2.6).</p>

<h3 style="text-align: center;">Tabela 2: Itens do artefato Casos de Uso – ID Jovem</h3>

<div align="center">
<table border="1" style="border-collapse: collapse; width: 95%; text-align: center;">
  <thead>
    <tr>
      <th style="width: 35%;">Item</th>
      <th style="width: 15%;">Referência</th>
      <th style="width: 10%;">Avaliação</th>
      <th style="width: 20%;">Observação</th>
      <th style="width: 5%;">Print</th>
      <th style="width: 15%;">Autor</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><b>01:</b> Os diagramas representam corretamente as interações entre os Atores e o Sistema (Casos de Uso)?</td>
      <td><a href="#" target="_blank">(VAZQUEZ; SIMÕES, 2016, p. 599-600)</a></td>
      <td>Sim</td>
      <td>Os diagramas (Implementados e Não Implementados) mostram claramente os atores (ex: Beneficiário) e suas interações com os casos de uso (elipses).</td>
      <td>-</td>
      <td><a href="https://github.com/GiovanaFontesS" target="_blank">Giovana Fontes</a></td>
    </tr>
    <tr>
      <td><b>02:</b> O nome de cada Caso de Uso segue o padrão (Verbo no Infinitivo + Complemento)?</td>
      <td><a href="#" target="_blank">(VAZQUEZ; SIMÕES, 2016, p. 660)</a></td>
      <td>Sim</td>
      <td>Todos os 12 casos de uso especificados seguem o padrão (ex: "Atualizar Dados...", "Consultar Locais...", "Baixar Carteirinha...").</td>
      <td>-</td>
      <td><a href="https://github.com/BrenoLTeixeira" target="_blank">Breno Teixeira</a></td>
    </tr>
    <tr>
      <td><b>03:</b> Os diagramas de caso de uso estão consistentes com as especificações textuais?</td>
      <td><a href="#" target="_blank">(VAZQUEZ; SIMÕES, 2016, p. 154)</a></td>
      <td>Incompleto</td>
      <td>Os diagramas separam "Implementados" e "Não Implementados". As 12 especificações (UC-01 a UC-12) detalham apenas os "Não Implementados". Faltam as especificações textuais dos casos de uso "Implementados" (ex: "Emitir Carteira", "Validar Carteira").</td>
      <td>-</td>
      <td><a href="https://github.com/arthurfernandesj" target="_blank">Arthur Fernandes</a></td>
    </tr>
    <tr>
      <td><b>04:</b> Cada especificação de caso de uso possui Pré-condições e Pós-condições claras?</td>
      <td><a href="#" target="_blank">(VAZQUEZ; SIMÕES, 2016, p. 667)</a></td>
      <td>Sim</td>
      <td>Todas as 12 tabelas de especificação possuem os campos "Pré-condições" e "Pós-condições" devidamente preenchidos.</td>
      <td>-</td>
      <td><a href="https://github.com/dylancavalcante" target="_blank">Dylan Cavalcante</a></td>
    </tr>
    <tr>
      <td><b>05:</b> Cada caso de uso detalha o Fluxo Principal, Fluxos Alternativos e Exceções?</td>
      <td><a href="#" target="_blank">(VAZQUEZ; SIMÕES, 2016, p. 668, 670)</a></td>
      <td>Sim</td>
      <td>As especificações de UC-01 a UC-12 detalham corretamente os fluxos, separando o "caminho feliz" (principal) dos cenários alternativos e de tratamento de erros (exceções).</td>
      <td>-</td>
      <td><a href="https://github.com/eduardar0" target="_blank">Eduarda Rodrigues</a></td>
    </tr>
    <tr>
      <td><b>06:</b> A especificação foca no "o quê" (comportamento) e evita detalhes de implementação ("como")?</td>
      <td><a href="#" target="_blank">(VAZQUEZ; SIMÕES, 2016, p. 659, 669)</a></td>
      <td>Sim</td>
      <td>Os fluxos descrevem o comportamento (ex: "O sistema valida...", "O jovem seleciona...") sem ditar detalhes de interface, banco de dados ou API.</td>
      <td>-</td>
      <td><a href="https://github.com/eduardar0" target="_blank">Eduarda Rodrigues</a></td>
    </tr>
    <tr>
      <td><b>07:</b> Cada caso de uso possui rastreabilidade para os requisitos elicitados (ex: Storytelling, Brainstorming)?</td>
      <td><a href="#" target="_blank">(VAZQUEZ; SIMÕES, 2016, p. 160, 736)</a></td>
      <td>Sim</td>
      <td>Todas as especificações de UC-01 a UC-12 possuem o campo "Rastreabilidade" preenchido, vinculando o caso de uso à sua origem.</td>
      <td>-</td>
      <td><a href="https://github.com/leticialopes20" target="_blank">Letícia Maria</a></td>
    </tr>
  </tbody>
</table>

<p style="text-align: center; font-size: 0.9em; color: gray;">
Fonte: <a href="https://github.com/BrenoLTeixeira" target="_blank">Breno Teixeira</a>
</p>
</div>

## Análises dos resultados 

<p style="text-align: justify;">
A verificação do artefato <b>Casos de Uso</b> demonstra um alto nível de conformidade com as práticas descritas em (VAZQUEZ; SIMÕES, 2016) <a href="#RP1">[1]</a>. Os elementos essenciais, como Atores, Fluxos, Pré/Pós-condições e Rastreabilidade, estão presentes e bem definidos na maioria das especificações.
</p>
<p style="text-align: justify;">
O principal ponto de melhoria, identificado no <b>Item 03</b>, é a inconsistência entre os diagramas e as especificações textuais. Os diagramas separam o sistema em "Implementados" e "Não Implementados", mas as 12 especificações de caso de uso detalham apenas os requisitos do segundo grupo ("Não Implementados"). Para que o artefato seja completo, é necessário que os casos de uso já implementados (como "Emitir Carteira") também sejam especificados textualmente, garantindo que todo o escopo do sistema esteja documentado de forma uniforme.
</p>

## Conclusão 

<p style="text-align: justify;">
O artefato <b>Casos de Uso</b> está bem estruturado e atende à maioria dos critérios de qualidade para a especificação de requisitos funcionais. As tabelas de especificação estão detalhadas, facilitando o entendimento dos desenvolvedores e testadores.
</p>
<p style="text-align: justify;">
Recomenda-se complementar o artefato com as especificações textuais dos casos de uso listados no diagrama "Implementados". Essa ação corrigirá a inconsistência apontada no <b>Item 03</b> e garantirá que o documento sirva como uma fonte completa e confiável de consulta para todo o escopo do aplicativo ID Jovem.
</p>

## Referencias Bibliograficas

> <a id="RP1" href="#TEC1">1.</a> VAZQUEZ, Carlos Eduardo; SIMÕES, Guilherme Siqueira. *Engenharia de Requisitos: Software Orientado ao Negócio.* 1. ed. Rio de Janeiro: Brasport, 2016. [Referenciado: Cap 2.6, Cap 8.12, Cap 9.6].

## Bibliografia 
> VAZQUEZ, Carlos; SIMÕES, Guilherme. Engenharia de Requisitos: software orientado ao negócio. Rio de Janeiro: Brasport, 2016.</a>. Acesso em: 10 out. 2025.
>

## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :--: | :--: | :-- | :-- | :-- |
| 1.0 | 12/11/2025 | Criação da página de verificação dos Casos de Uso | [Breno Teixeira](https://github.com/BrenoLTeixeira) | [Arthur Fernandes](https://github.com/arthurfernandesj) |
| 1.1 | 12/11/2025 | Preenchimento da checklist e análise dos resultados | [Breno Teixeira](https://github.com/BrenoLTeixeira) | [Giovana Fontes](https://github.com/GiovanaFontesS) |

## Agrecimentos

De acordo com o Código de Conduta da Sociedade Brasileira de Computação (SBC), destacamos que a ferramenta (Gemini) foi utilizada apenas como apoio técnico e linguístico. Todo o conteúdo apresentado é de autoria do Grupo 04, que assume total responsabilidade por sua originalidade e precisão.