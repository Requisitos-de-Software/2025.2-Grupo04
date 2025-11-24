# Especificação suplementar

## Introdução
A **Especificação Suplementar**, no contexto da engenharia de software, refere-se à prática de classificar e organizar os requisitos de um sistema em diferentes grupos ou categorias. Essa abordagem facilita a compreensão, o gerenciamento e a priorização dos requisitos durante o ciclo de desenvolvimento do software.

"Este documento captura os requisitos de sistema que não foram identificados imediatamente nos Casos de Uso do Modelo de Casos de Uso. Entre estes requisitos estão incluídos: o Requisitos legais e reguladores, incluindo padrões de aplicativo; Atributos de qualidade do sistema a ser criado, incluindo requisitos de usabilidade, confiabilidade, desempenho e suportabilidade. Outros requisitos, como sistemas operacionais e ambientes, requisitos de compatibilidade e restrições de design" <a id="TEC1" href="#RP1">[1]</a>. Esses requisitos são cruciais para garantir a qualidade do software e a satisfação do usuário  <a id="TEC2" href="#RP2">[2]</a>.

<small><em>Revisado por [Chat GPT](https://chatgpt.com/share/6923b754-1e64-8000-8d6e-8645f6020b43), em 12 de outubro de 2025</em></small>

## Metodologia

A Metodologia utilizada neste artefato foi baseada no modelo FURPS+. "É um sistema para a classificação de requisitos, o acrônimo representa categorias que podem ser usadas na definição de requisitos" <a id="TEC2" href="#RP2">[2]</a>. Dentre elas: Funcionalidade, Usabilidade, Confiabilidade, Desempenho, Suportabilidade. <a id="TEC2" href="#RP2">[2]</a>


| Nome | Seções Relacionadas da Especificação Suplementar |
|------|--------------------------------------------------|
| **[Arthur Fernandes](https://github.com/arthurfernandesj)** | • [RNF01 – Processo de Login Simplificado](#RNF01)<br>• [RNF02 – Interface Intuitiva e Acessível](#RNF02)<br>• [RNF10 – Carregamento Eficiente](#RNF10)<br>• [RNF16 – Validação Rápida da Carteirinha](#RNF16) |
| **[Breno Teixeira](https://github.com/BrenoLTeixeira)** | • [RNF19 – Registro de Validações](#RNF19)<br>• [RNF22 – Log de Auditoria](#RNF22)<br>• [RNF12 – Compatibilidade Retroativa](#RNF12)<br>• [RNF17 – Ciclo de Atualização](#RNF17) <br>• [Validação](#ves01) |
| **[Dylan Cavalcante](https://github.com/dylancavalcante)** | • [RNF11 – Sincronização de Dados](#RNF11)<br>• [RNF15 – Controle de Inatividade](#RNF15)<br>• [RNF04 – Compatibilidade com Android e iOS](#RNF04)<br>• [RNF09 – Design Responsivo](#RNF09) |
| **[Eduarda Domingos](https://github.com/eduardar0)** | • [RNF07 – Recursos de Acessibilidade](#RNF07)<br>• [RNF13 – Navegação Consistente](#RNF13)<br>• [RNF21 – Escalabilidade do Sistema](#RNF21)<br>• [RNF24 – Compatibilidade com API](#RNF24) <br>• [Validação](#ves01) |
| **[Giovana Fontes](https://github.com/GiovanaFontesS)** | • [RNF14 – Feedback Visual e Sonoro](#RNF14)<br>• [RNF18 – Personalização de Leitura](#RNF18)<br>• [RNF03 – Emissão Rápida da Carteirinha](#RNF03)<br>• [RNF06 – Operação com Baixo Consumo de Internet](#RNF06) |
| **[Letícia Lopes](https://github.com/leticialopes20)** | • [RNF05 – Proteção de Dados Pessoais](#RNF05)<br>• [RNF08 – Alta Disponibilidade](#RNF08)<br>• [RNF20 – Consulta Rápida ao CadÚnico](#RNF20)<br>• [RNF23 – Carregamento de Dados](#RNF23) |

<p style="text-align: center; font-size: 10pt;">Autor: Giovana Fontes</p>

## Modelo FURPS



A Legenda para identificação dos requisitos em cada acrônimo estão representadas na tabela 2.



<p style="text-align: center"><strong>Tabela 2 -</strong> Legenda do modelo FURPS</p>
<div align="center">
<table>
<thead>
<tr>
<th>Acrônimo</th>
<th>Significado</th>
<th>Tradução</th>
<th>Identificador</th>
</tr>
</thead>
<tbody>
<tr>
<td>F</td>
<td>Functionality</td>
<td><a href="#funcionalidade">Funcionalidade</a></td>
<td>-</td>
</tr>
<tr>
<td>U</td>
<td>Usability</td>
<td><a href="#usabilidade">Usabilidade</a></td>
<td>RU</td>
</tr>
<tr>
<td>R</td>
<td>Reliability</td>
<td><a href="#confiabilidade">Confiabilidade</a></td>
<td>RR</td>
</tr>
<tr>
<td>P</td>
<td>Performance</td>
<td><a href="#desempenho">Desempenho</a></td>
<td>RP</td>
</tr>
<tr>
<td>S</td>
<td>Supportability</td>
<td><a href="#suportabilidade">Suportabilidade</a></td>
<td>RS</td>
</tr>
</tbody>
</table>
</div>


<p style="text-align: center"><strong>Fonte:</strong> <a href="https://github.com/arthurfernandesj">Arthur Fernandes</a>, 2025</p>


### Funcionalidade

A **funcionalidade** <a id="TEC2" href="#RP2">[2]</a> trata do núcleo do sistema, abordando as funções e capacidades que o software precisa oferecer. Os requisitos de funcionalidade especificam o que o sistema deve fazer, englobando tarefas, operações, recursos e comportamentos esperados.

Os requisitos funcionais foram capturados ateriormente com as técnicas de [Brainstorming](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/), [Introspeção](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspecção/), [Entrevista](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/), [Observação](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Observação/), [Storytelling](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Storytelling/), e podem ser consultados em [Requisitos Elicitados](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/). 

### Usabilidade

A **usabilidade**, <a id="TEC2" href="#RP2">[2]</a> no contexto do **aplicativo ID Jovem** refere-se à facilidade com que os jovens conseguem emitir, acessar e utilizar seu documento digital de identificação para obter benefícios, como meia-entrada em eventos culturais, esportivos e transporte interestadual gratuito ou com desconto. Essa usabilidade deve garantir simplicidade, acessibilidade e clareza nas informações apresentadas, considerando a diversidade do público jovem, incluindo pessoas com deficiência.

Esta seção abrange todos os requisitos que influenciam a usabilidade do sistema. Os requisitos não funcionais relacionados à usabilidade estão descritos na Tabela 3.

#### <p align="center"><strong>Tabela 3 -</strong>  Requisitos de Usabilidade</p>

|   Código   | Requisito Não Funcional         | Descrição                                                                                         | Justificativa                                                               |      Status      | Autor                                |
| :--------: | :------------------------------ | :------------------------------------------------------------------------------------------------ | :-------------------------------------------------------------------------- | :--------------: | :----------------------------------- |
| <a id="RNF01">RNF01</a> | Processo de login simplificado  | O processo de login deve ser simples, direto e com o menor número de etapas possível.             | Facilitar o acesso dos jovens beneficiários, reduzindo barreiras de uso.    |   Implementado   | [Arthur Fernandes](https://github.com/arthurfernandesj) |
| <a id="RNF02">RNF02</a> | Interface intuitiva e acessível | A interface deve ser clara, legível e acessível, mesmo para jovens com pouca experiência digital. | Promover inclusão digital e acessibilidade conforme princípios da WCAG 2.1. |   Implementado   | [Arthur Fernandes](https://github.com/arthurfernandesj)|
| <a id="RNF07">RNF07</a> | Recursos de acessibilidade | O aplicativo deve possuir alto contraste, leitura de tela, voz e Libras. | Tornar o app acessível a jovens com deficiência visual ou auditiva. |   Implementado   | [Eduarda Domingos](https://github.com/eduardar0)|
| <a id="RNF13">RNF13</a> | Navegação consistente           | A navegação entre seções deve ser previsível e coesa.                                             | Facilitar o uso e aprendizado do sistema.                                   | Não implementado | [Eduarda Domingos](https://github.com/eduardar0) |
| <a id="RNF14">RNF14</a> | Feedback visual e sonoro        | O aplicativo deve emitir feedback claro a cada interação.                                         | Melhorar a compreensão e confirmar ações realizadas.                        | Não implementado | [Giovana Fontes](https://github.com/GiovanaFontesS) |
| <a id="RNF18">RNF18</a> | Personalização de leitura       | O jovem beneficiário deve poder ajustar o tamanho da fonte e o esquema de cores.                  | Garantir conforto visual e legibilidade.                                    | Não implementado | [Giovana Fontes](https://github.com/GiovanaFontesS) |

<p align="center"><strong>Fontes:</strong> <a href="https://github.com/arthurfernandesj">Arthur Fernandes</a>, <a href="https://github.com/eduardar0">Eduarda Domingos</a>, <a href="https://github.com/GiovanaFontesS">Giovana Fontes</a>, 2025</p>

---

### Confiabilidade

A **confiabilidade**,  <a id="TEC2" href="#RP2">[2]</a> refere-se à habilidade do sistema de operar continuamente e sem problemas, reduzindo ao máximo as falhas. Isso envolve a capacidade de lidar com falhas, a forma como os erros são gerenciados e a disponibilidade constante do sistema. Refere-se a integridade, conformidade e interoperabilidade do software  <a id="TEC2" href="#RP2">[2]</a>.

Esta seção abrange todos os requisitos que influenciam o Confiabilidade do sistema. Os requisitos não funcionais relacionados à confiabilidade estão descritos na Tabela 4.

#### <p align="center"><strong>Tabela 4 -</strong>  Requisitos de Confiabilidade</p>

|   Código   | Requisito Não Funcional | Descrição                                                                          | Justificativa                                         |      Status      | Autor                                |
| :--------: | :---------------------- | :--------------------------------------------------------------------------------- | :---------------------------------------------------- | :--------------: | :----------------------------------- |
| <a id="RNF05">RNF05</a> | Proteção de dados pessoais | Os dados do jovem beneficiário devem ser protegidos por criptografia conforme a LGPD. | Garantir a segurança e confidencialidade das informações pessoais. | Implementado | [Letícia Lopes](https://github.com/leticialopes20) |
| <a id="RNF08">RNF08</a> | Alta disponibilidade    | O sistema deve garantir disponibilidade mínima de 99,5%.                           | Evitar falhas de acesso e interrupções nos serviços.  | Não implementado | [Letícia Lopes](https://github.com/leticialopes20) |
| <a id="RNF11">RNF11</a> | Sincronização de dados  | As informações dos benefícios devem estar sempre sincronizadas com a base oficial. | Garantir transparência e atualização das informações. | Não implementado | [Dylan Cavalcante](https://github.com/dylancavalcante) |
| <a id="RNF15">RNF15</a> | Controle de inatividade | O sistema deve ter no máximo 2h de inatividade mensal fora de manutenções.         | Garantir confiabilidade e continuidade de serviço.    | Não implementado | [Dylan Cavalcante](https://github.com/dylancavalcante) |
| <a id="RNF19">RNF19</a> | Registro de validações  | O sistema deve registrar todas as tentativas de validação de carteirinhas.         | Assegurar rastreabilidade e auditoria de ações.       | Não implementado | [Breno Teixeira](https://github.com/BrenoLTeixeira) |
| <a id="RNF22">RNF22</a> | Log de auditoria        | O sistema deve armazenar logs de emissões e validações por 5 anos.                 | Garantir rastreabilidade e controle de histórico.     | Não implementado | [Breno Teixeira](https://github.com/BrenoLTeixeira) |

<p align="center"><strong>Fontes:</strong> <a href="https://github.com/leticialopes20">Letícia Lopes</a>, <a href="https://github.com/dylancavalcante">Dylan Cavalcante</a>, <a href="https://github.com/BrenoLTeixeira">Breno Teixeira</a>, 2025</p>

---

### Desempenho

O **desempenho** <a id="TEC2" href="#RP2">[2]</a>diz respeito à rapidez e eficiência com que o sistema opera. Os requisitos de desempenho incluem fatores como a velocidade de resposta, a capacidade de processamento de dados e a habilidade do sistema de crescer e se adaptar a Outores demandas.

Esta seção abrange todos os requisitos que influenciam o desempenho do sistema. Os requisitos não funcionais relacionados à desempenho estão descritos na Tabela 5.

#### <p align="center"><strong>Tabela 5 -</strong>  Requisitos de Desempenho </p>

|   Código   | Requisito Não Funcional                | Descrição                                                                                 | Justificativa                                                             |      Status      | Autor                                |
| :--------: | :------------------------------------- | :---------------------------------------------------------------------------------------- | :------------------------------------------------------------------------ | :--------------: | :----------------------------------- |
| <a id="RNF03">RNF03</a> | Emissão rápida da carteirinha          | A emissão da carteirinha deve ocorrer em até 5 segundos após a solicitação.               | Melhorar a experiência e reduzir o tempo de espera do jovem beneficiário. |   Implementado   | [Giovana Fontes](https://github.com/GiovanaFontesS) |
| <a id="RNF06">RNF06</a> | Operação com baixo consumo de internet | O aplicativo deve funcionar com baixo consumo de dados e em regiões com conexão limitada. | Aumentar o acesso ao serviço por jovens em regiões carentes.              | Não implementado | [Giovana Fontes](https://github.com/GiovanaFontesS) |
| <a id="RNF10">RNF10</a> | Carregamento eficiente                 | O tempo de carregamento das páginas não deve exceder 3 segundos em redes lentas.          | Melhorar o desempenho e reduzir frustrações no uso.                       | Não implementado | [Arthur Fernandes](https://github.com/arthurfernandesj) |
| <a id="RNF16">RNF16</a> | Validação rápida da carteirinha        | O tempo de resposta da validação via QR Code não deve exceder 2 segundos.                 | Evitar atrasos em fiscalizações ou eventos.                               | Não implementado | [Arthur Fernandes](https://github.com/arthurfernandesj) |
| <a id="RNF20">RNF20</a> | Consulta rápida ao CadÚnico            | O retorno da verificação de elegibilidade deve ocorrer em até 3 segundos.                 | Melhorar o tempo de resposta e a satisfação dos jovens beneficiários.     | Não implementado | [Letícia Lopes](https://github.com/leticialopes20) |
| <a id="RNF23">RNF23</a> | Carregamento de dados                  | O aplicativo deve carregar informações de eventos e parceiros em até 3 segundos.          | Garantir desempenho mesmo com alto volume de dados.                       | Não implementado | [Letícia Lopes](https://github.com/leticialopes20) |

<p align="center"><strong>Fontes:</strong> <a href="https://github.com/GiovanaFontesS">Giovana Fontes</a>, <a href="https://github.com/arthurfernandesj">Arthur Fernandes</a>, <a href="https://github.com/leticialopes20">Letícia Lopes</a>, 2025</p>

---

### Suportabilidade

A **suportabilidade** <a id="TEC2" href="#RP2">[2]</a> refere-se à facilidade de manter e suportar o sistema ao longo do tempo. Isso envolve requisitos como a frequência e facilidade de atualizações, a manutenção contínua, a disponibilidade de documentação completa e a necessidade de treinamento para os usuários e administradores.

Esta seção abrange todos os requisitos que influenciam o Suportabilidade do sistema. Os requisitos não funcionais relacionados à suportabilidade estão descritos na Tabela 6.

#### <p align="center"><strong>Tabela 6 -</strong>  Requisitos de suportabilidade </p>

|   Código   | Requisito Não Funcional           | Descrição                                                                                          | Justificativa                                                    |      Status      | Autor                                |
| :--------: | :-------------------------------- | :------------------------------------------------------------------------------------------------- | :--------------------------------------------------------------- | :--------------: | :----------------------------------- |
| <a id="RNF04">RNF04</a> | Compatibilidade com Android e iOS | O aplicativo deve ser gratuito e compatível com sistemas Android e iOS.                            | Garantir o acesso universal à plataforma.                        |   Implementado   | [Dylan Cavalcante](https://github.com/dylancavalcante) |
| <a id="RNF09">RNF09</a> | Design responsivo                 | O design deve se adaptar a diferentes tamanhos de tela e dispositivos.                             | Garantir boa experiência em smartphones, tablets e computadores. |   Implementado   | [Dylan Cavalcante](https://github.com/dylancavalcante) |
| <a id="RNF12">RNF12</a> | Compatibilidade retroativa        | O sistema deve funcionar nas duas versões anteriores dos principais navegadores e sistemas móveis. | Ampliar o alcance e evitar incompatibilidades.                   | Não implementado | [Breno Teixeira](https://github.com/BrenoLTeixeira) |
| <a id="RNF17">RNF17</a> | Ciclo de atualização              | A equipe deve liberar atualizações de segurança a cada 3 meses.                                    | Manter o aplicativo seguro e estável.                            | Não implementado | [Breno Teixeira](https://github.com/BrenoLTeixeira) |
| <a id="RNF21">RNF21</a> | Escalabilidade do sistema         | O sistema deve suportar aumento de 50% de beneficiários sem perda de desempenho.                   | Garantir estabilidade com o crescimento da base de usuários.     | Não implementado | [Eduarda Domingos](https://github.com/eduardar0) |
| <a id="RNF24">RNF24</a> | Compatibilidade com API           | O app deve suportar a API mais recente e as duas versões anteriores do sistema operacional.        | Evitar falhas e garantir funcionamento contínuo.                 | Não implementado | [Eduarda Domingos](https://github.com/eduardar0) |

## Validação  

### **Gravação 1** <a id="ves01"></a> - Validação Breno e Eduarda 

<p style="text-align: center">
  <iframe width="560" height="315" 
    src="https://www.youtube.com/embed/HMZzNc8fmuM" 
    title="YouTube video player" 
    frameborder="0" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
    referrerpolicy="strict-origin-when-cross-origin" 
    allowfullscreen>
  </iframe>
</p>

 <font size="3">
    <p style="text-align: center">
      <b>Fonte:</b> <a href="https://github.com/eduardar0">Eduarda Domingos</a>, 2025
    </p>
  </font>

## Referências Bibliográficas

> <a id="RP1" href="#TEC1">1.</a> Requisitos de Software. Bilheteria-Digital (2023.1). Disponível em: [https://github.com/Requisitos-de-Software/2023.1-BilheteriaDigital](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/). Acesso em: 12 Out. 2025.

> <a id="RP2" href="#TEC2">2.</a> Eeles, Peter. QualidadeBR: FURPS+. jun, 2008. Disponível em: [https://qualidadebr.wordpress.com/2008/07/10/furps/](https://qualidadebr.wordpress.com/2008/07/10/furps/). Acesso em: 12 Out. 2025.


## Bibliografia

> <a id="RP3" href="#TEC3">3.</a> SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 13. UnB, 2025. Disponível em: <[https://aprender3.unb.br/course/section.php?id=305649](hhttps://aprender3.unb.br/course/section.php?id=305649)>. Acesso em: 12 de Out 2025. p. 27–30.

## Histórico de Versão

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
|--------|------|-----------|-----------|-------------|
| 1.0 | 09/10/2025 | Versão inicial da pagina de Especificação Suplementar. | [Arthur](https://github.com/arthurfernandesj) | [ Leticia ](https://github.com/leticialopes20) |
| 1.1 | 11/10/2025 | Adição do texto da Introdução,Metodologia e Bibliografia| [Arthur ](https://github.com/arthurfernandesj), [Leticia ](https://github.com/leticialopes20) | [ Giovana](https://github.com/GiovanaFontesS) |
| 1.2 | 12/10/2025 | Criação das tabelas de: Usabilidade, Confiabilidade, Desempenho, Suportabilidade e de participantes| [Arthur](https://github.com/arthurfernandesj), [Breno](https://github.com/BrenoLTeixeira), [Dylan ](https://github.com/dylancavalcante), [Eduarda](https://github.com/eduardar0), [Giovana](https://github.com/GiovanaFontesS), [Leticia](https://github.com/leticialopes20)| [Arthur](https://github.com/arthurfernandesj), [Breno](https://github.com/BrenoLTeixeira), [Dylan](https://github.com/dylancavalcante), [Eduarda](https://github.com/eduardar0), [Giovana](https://github.com/GiovanaFontesS), [Leticia](https://github.com/leticialopes20)|
| 1.3| 12/10/2025 | Correção de links da tabela 3| [Leticia](https://github.com/leticialopes20) |[Arthur](https://github.com/arthurfernandesj) |
| 1.4| 12/10/2025 | Adicionando as referências e a bibliografia | [Arthur](https://github.com/arthurfernandes) |[Leticia](https://github.com/leticialopes20) |

## Agrecimentos

Queremos agradecer ao [Chat GPT](https://chatgpt.com/share/6923b754-1e64-8000-8d6e-8645f6020b43), ferramenta de Inteligência Artificial Generativa, pelo apoio durante o desenvolvimento deste projeto ID Jovem. Sua ajuda foi essencial na revisão de textos, na organização das ideias e na pesquisa de conteúdos complementares que contribuíram para deixar nossa documentação mais clara e completa.

De acordo com o Código de Conduta da Sociedade Brasileira de Computação (SBC), destacamos que a ferramenta foi utilizada apenas como apoio técnico e linguístico.
Todo o conteúdo apresentado é de autoria do Grupo 04, que assume total responsabilidade por sua originalidade e precisão. 