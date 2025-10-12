# Especificação suplementar

## Introdução
A **Especificação Suplementar**, no contexto da engenharia de software, refere-se à prática de classificar e organizar os requisitos de um sistema em diferentes grupos ou categorias. Essa abordagem facilita a compreensão, o gerenciamento e a priorização dos requisitos durante o ciclo de desenvolvimento do software.

"Este documento captura os requisitos de sistema que não foram identificados imediatamente nos Casos de Uso do Modelo de Casos de Uso. Entre estes requisitos estão incluídos: o Requisitos legais e reguladores, incluindo padrões de aplicativo; Atributos de qualidade do sistema a ser criado, incluindo requisitos de usabilidade, confiabilidade, desempenho e suportabilidade. Outros requisitos, como sistemas operacionais e ambientes, requisitos de compatibilidade e restrições de design" <a id="TEC1" href="#RP1">[1]</a>. Esses requisitos são cruciais para garantir a qualidade do software e a satisfação do usuário  <a id="TEC2" href="#RP2">[2]</a>.

## Metodologia

A Metodologia utilizada neste artefato foi baseada no modelo FURPS+. "É um sistema para a classificação de requisitos, o acrônimo representa categorias que podem ser usadas na definição de requisitos" <a id="TEC3" href="#RP3">[3]</a>. Dentre elas: Funcionalidade, Usabilidade, Confiabilidade, Desempenho, Suportabilidade. <a id="TEC3" href="#RP3">[3]</a>.

A Tabela 1 apresenta os membros responsáveis pelo desenvolvimento deste artefato.

<p style="text-align: center"><strong>Tabela 1-</strong> Participantes</p>
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
<td>12/10/2025</td>
<td>00:00</td>
</tr>
<tr>
<td><a href="https://github.com/BrenoLTeixeira">Breno Lourenço</a></td>
<td>12/10/2025</td>
<td>00:00</td>
</tr>
<tr>
<td><a href="https://github.com/dylancavalcante">Dylan Cavalcante</a></td>
<td>12/10/2025</td>
<td>00:14</td>
</tr>
<tr>
<td><a href="https://github.com/eduardar0">Eduarda Domingos</a></td>
<td>12/10/2025</td>
<td>22:00</td>
</tr>
<tr>
<td><a href="https://github.com/GiovanaFontesS">Giovana Fontes</a></td>
<td>12/10/2025</td>
<td>11:33</td>
</tr>
<tr>
<td><a href="https://github.com/leticialopes20">Letícia Lopes</a></td>
<td>12/10/2025</td>
<td>21:00</td>
</tr>
</tbody>
</table>
</div>
<font size="2"><p style="text-align: center">Fonte: <i>[Leticia Lopes](https://github.com/leticialopes20)</i> </p></font>

---

A Legenda para identificação dos requisitos em cada acrônimo estão representadas na tabela 2.

<p style="text-align: center"><strong>Tabela 2 -</strong> Legenda do modelo FURPS</p>

| Acrônimo | Significado | Tradução | Identificador |
|:----:|:----:|:----:|:----:|
| F | Functionality |[Funcionalidade](#funcionalidade) | - |
| U | Usability | [Usabilidade](#usabilidade)| RU |
| R | Reliability |[Confiabilidade](#confiabilidade)  | RR |
| P | Performance | [Desempenho](#desempenho) | RP |
| S | Supportability | [Suportabilidade](#suportabilidade) | RS |

<p style="text-align: center"><strong>Fonte:</strong> <a href="https://github.com/arthurfernandesj">Arthur Fernandes</a>, 2025</p>


## Funcionalidade

A **funcionalidade** trata do núcleo do sistema, abordando as funções e capacidades que o software precisa oferecer. Os requisitos de funcionalidade especificam o que o sistema deve fazer, englobando tarefas, operações, recursos e comportamentos esperados.

Os requisitos funcionais foram capturados ateriormente com as técnicas de [Brainstorming](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/), [Introspeção](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspec%C3%A7%C3%A3o/), [Entrevista](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/), [Observação](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Observa%C3%A7%C3%A3o/), [Storytelling](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Observa%C3%A7%C3%A3o/), e podem ser consultados em [Requisitos Elicitados](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/). 

## Usabilidade

A **usabilidade** no contexto do **aplicativo ID Jovem** refere-se à facilidade com que os jovens conseguem emitir, acessar e utilizar seu documento digital de identificação para obter benefícios, como meia-entrada em eventos culturais, esportivos e transporte interestadual gratuito ou com desconto. Essa usabilidade deve garantir simplicidade, acessibilidade e clareza nas informações apresentadas, considerando a diversidade do público jovem, incluindo pessoas com deficiência.


## Confiabilidade

A **confiabilidade** refere-se à habilidade do sistema de operar continuamente e sem problemas, reduzindo ao máximo as falhas. Isso envolve a capacidade de lidar com falhas, a forma como os erros são gerenciados e a disponibilidade constante do sistema. Refere-se a integridade, conformidade e interoperabilidade do software [3].


## Desempenho

O **desempenho** diz respeito à rapidez e eficiência com que o sistema opera. Os requisitos de desempenho incluem fatores como a velocidade de resposta, a capacidade de processamento de dados e a habilidade do sistema de crescer e se adaptar a Outores demandas.


## Suportabilidade

A **suportabilidade** refere-se à facilidade de manter e suportar o sistema ao longo do tempo. Isso envolve requisitos como a frequência e facilidade de atualizações, a manutenção contínua, a disponibilidade de documentação completa e a necessidade de treinamento para os usuários e administradores.




## Referências Bibliográficas


## Bibliografia


## Histórico de Versão

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
|--------|------|-----------|-----------|-------------|
| 1.0 | 09/10/2025 | Versão inicial da pagina de Especificação Suplementar. | [Arthur Fernandes](https://github.com/arthurfernandesj) | [ Leticia Lopes ](https://github.com/leticialopes20) |
| 1.1 | 11/10/2025 | Adição do texto da Introdução,Metodologia e Bibliografia| [Arthur Fernandes](https://github.com/arthurfernandesj), [Leticia Lopes](https://github.com/leticialopes20) | [ Giovana ](https://github.com/) |
| 1.2 | 12/10/2025 | Criação da tabela dos requisitos| [Arthur Fernandes](https://github.com/arthurfernandesj), [Leticia Lopes](https://github.com/leticialopes20), | [ Eduarda ](https://github.com/) |
