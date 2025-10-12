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


### Funcionalidade

A **funcionalidade** trata do núcleo do sistema, abordando as funções e capacidades que o software precisa oferecer. Os requisitos de funcionalidade especificam o que o sistema deve fazer, englobando tarefas, operações, recursos e comportamentos esperados.

Os requisitos funcionais foram capturados ateriormente com as técnicas de [Brainstorming](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/), [Introspeção](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspec%C3%A7%C3%A3o/), [Entrevista](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/), [Observação](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Observa%C3%A7%C3%A3o/), [Storytelling](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Observa%C3%A7%C3%A3o/), e podem ser consultados em [Requisitos Elicitados](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/). 

### Usabilidade

A **usabilidade** no contexto do **aplicativo ID Jovem** refere-se à facilidade com que os jovens conseguem emitir, acessar e utilizar seu documento digital de identificação para obter benefícios, como meia-entrada em eventos culturais, esportivos e transporte interestadual gratuito ou com desconto. Essa usabilidade deve garantir simplicidade, acessibilidade e clareza nas informações apresentadas, considerando a diversidade do público jovem, incluindo pessoas com deficiência.

Esta seção abrange todos os requisitos que influenciam a usabilidade do sistema. Os requisitos não funcionais relacionados à usabilidade estão descritos na Tabela 3.

#### <p style="text-align: center"><strong>Tabela 3 -</strong>  Requisitos de Usabilidade do ID Jovem</p>

|   Código   | Requisito Não Funcional         | Descrição                                                                                         | Justificativa                                                               |      Status      | Autor                                |
| :--------: | :------------------------------ | :------------------------------------------------------------------------------------------------ | :-------------------------------------------------------------------------- | :--------------: | :----------------------------------- |
| [RNF01](#) | Processo de login simplificado  | O processo de login deve ser simples, direto e com o menor número de etapas possível.             | Facilitar o acesso dos jovens beneficiários, reduzindo barreiras de uso.    |   Implementado   | [Arthur Fernandes](https://github.com/arthurfernandesj) |
| [RNF02](#) | Interface intuitiva e acessível | A interface deve ser clara, legível e acessível, mesmo para jovens com pouca experiência digital. | Promover inclusão digital e acessibilidade conforme princípios da WCAG 2.1. |   Implementado   | [Arthur Fernandes](https://github.com/arthurfernandesj)|
| [RNF07](#) | Recursos de acessibilidade | O aplicativo deve possuir alto contraste, leitura de tela, voz e Libras. | Tornar o app acessível a jovens com deficiência visual ou auditiva. |   Implementado   | [Eduarda Domingos](https://github.com/eduardar0)|
| [RNF13](#) | Navegação consistente           | A navegação entre seções deve ser previsível e coesa.                                             | Facilitar o uso e aprendizado do sistema.                                   | Não implementado | [Eduarda Domingos](https://github.com/eduardar0) |
| [RNF14](#) | Feedback visual e sonoro        | O aplicativo deve emitir feedback claro a cada interação.                                         | Melhorar a compreensão e confirmar ações realizadas.                        | Não implementado | [Giovana Fontes](https://github.com/GiovanaFontesS) |
| [RNF18](#) | Personalização de leitura       | O jovem beneficiário deve poder ajustar o tamanho da fonte e o esquema de cores.                  | Garantir conforto visual e legibilidade.                                    | Não implementado | [Giovana Fontes](https://github.com/GiovanaFontesS) |

<p align="center"><strong>Fontes:</strong> <a href="https://github.com/arthurfernandesj">Arthur Fernandes</a>, <a href="https://github.com/eduardar0">Eduarda Domingos</a>, <a href="https://github.com/GiovanaFontesS">Giovana Fontes</a>, 2025</p>



### Confiabilidade

A **confiabilidade** refere-se à habilidade do sistema de operar continuamente e sem problemas, reduzindo ao máximo as falhas. Isso envolve a capacidade de lidar com falhas, a forma como os erros são gerenciados e a disponibilidade constante do sistema. Refere-se a integridade, conformidade e interoperabilidade do software [3].

Esta seção inclui todos os requisitos que afetam a confiabilidade. Os requisitos de confiabilidade estão representados na tabela 4.

#### <p style="text-align: center"><strong>Tabela 4 -</strong>  Requisitos de Confiabilidade do ID Jovem</p>

|   Código   | Requisito Não Funcional | Descrição                                                                          | Justificativa                                         |      Status      | Autor                                |
| :--------: | :---------------------- | :--------------------------------------------------------------------------------- | :---------------------------------------------------- | :--------------: | :----------------------------------- |
| [RNF05](#) | Proteção de dados pessoais | Os dados do jovem beneficiário devem ser protegidos por criptografia conforme a LGPD. | Garantir a segurança e confidencialidade das informações pessoais. | Implementado | [Letícia Lopes](https://github.com/leticialopes20) |
| [RNF08](#) | Alta disponibilidade    | O sistema deve garantir disponibilidade mínima de 99,5%.                           | Evitar falhas de acesso e interrupções nos serviços.  | Não implementado | [Letícia Lopes](https://github.com/leticialopes20) |
| [RNF11](#) | Sincronização de dados  | As informações dos benefícios devem estar sempre sincronizadas com a base oficial. | Garantir transparência e atualização das informações. | Não implementado | [Dylan Cavalcante](https://github.com/dylancavalcante) |
| [RNF15](#) | Controle de inatividade | O sistema deve ter no máximo 2h de inatividade mensal fora de manutenções.         | Garantir confiabilidade e continuidade de serviço.    | Não implementado | [Dylan Cavalcante](https://github.com/dylancavalcante) |
| [RNF19](#) | Registro de validações  | O sistema deve registrar todas as tentativas de validação de carteirinhas.         | Assegurar rastreabilidade e auditoria de ações.       | Não implementado | [Breno Lourenço](https://github.com/BrenoLTeixeira) |
| [RNF22](#) | Log de auditoria        | O sistema deve armazenar logs de emissões e validações por 5 anos.                 | Garantir rastreabilidade e controle de histórico.     | Não implementado | [Breno Lourenço](https://github.com/BrenoLTeixeira) |

<p align="center"><strong>Fontes:</strong> <a href="https://github.com/leticialopes20">Letícia Lopes</a>, <a href="https://github.com/dylancavalcante">Dylan Cavalcante</a>, <a href="https://github.com/BrenoLTeixeira">Breno Lourenço</a>, 2025</p>


### Desempenho

O **desempenho** diz respeito à rapidez e eficiência com que o sistema opera. Os requisitos de desempenho incluem fatores como a velocidade de resposta, a capacidade de processamento de dados e a habilidade do sistema de crescer e se adaptar a Outores demandas.

#### <p style="text-align: center"><strong>Tabela 5 -</strong>  Requisitos de Desempenho do ID Jovem</p>

|   Código   | Requisito Não Funcional                | Descrição                                                                                 | Justificativa                                                             |      Status      | Autor                                |
| :--------: | :------------------------------------- | :---------------------------------------------------------------------------------------- | :------------------------------------------------------------------------ | :--------------: | :----------------------------------- |
| [RNF03](#) | Emissão rápida da carteirinha          | A emissão da carteirinha deve ocorrer em até 5 segundos após a solicitação.               | Melhorar a experiência e reduzir o tempo de espera do jovem beneficiário. |   Implementado   | [Giovana Fontes](https://github.com/GiovanaFontesS) |
| [RNF06](#) | Operação com baixo consumo de internet | O aplicativo deve funcionar com baixo consumo de dados e em regiões com conexão limitada. | Aumentar o acesso ao serviço por jovens em regiões carentes.              | Não implementado | [Giovana Fontes](https://github.com/GiovanaFontesS) |
| [RNF10](#) | Carregamento eficiente                 | O tempo de carregamento das páginas não deve exceder 3 segundos em redes lentas.          | Melhorar o desempenho e reduzir frustrações no uso.                       | Não implementado | [Arthur Fernandes](https://github.com/arthurfernandesj) |
| [RNF16](#) | Validação rápida da carteirinha        | O tempo de resposta da validação via QR Code não deve exceder 2 segundos.                 | Evitar atrasos em fiscalizações ou eventos.                               | Não implementado | [Arthur Fernandes](https://github.com/arthurfernandesj) |
| [RNF20](#) | Consulta rápida ao CadÚnico            | O retorno da verificação de elegibilidade deve ocorrer em até 3 segundos.                 | Melhorar o tempo de resposta e a satisfação dos jovens beneficiários.     | Não implementado | [Letícia Lopes](https://github.com/leticialopes20) |
| [RNF23](#) | Carregamento de dados                  | O aplicativo deve carregar informações de eventos e parceiros em até 3 segundos.          | Garantir desempenho mesmo com alto volume de dados.                       | Não implementado | [Letícia Lopes](https://github.com/leticialopes20) |

<p align="center"><strong>Fontes:</strong> <a href="https://github.com/GiovanaFontesS">Giovana Fontes</a>, <a href="https://github.com/arthurfernandesj">Arthur Fernandes</a>, <a href="https://github.com/leticialopes20">Letícia Lopes</a>, 2025</p>

### Suportabilidade

A **suportabilidade** refere-se à facilidade de manter e suportar o sistema ao longo do tempo. Isso envolve requisitos como a frequência e facilidade de atualizações, a manutenção contínua, a disponibilidade de documentação completa e a necessidade de treinamento para os usuários e administradores.


#### <p style="text-align: center"><strong>Tabela 6 -</strong>  Requisitos de suportabilidade do ID Jovem</p>

|   Código   | Requisito Não Funcional           | Descrição                                                                                          | Justificativa                                                    |      Status      | Autor                                |
| :--------: | :-------------------------------- | :------------------------------------------------------------------------------------------------- | :--------------------------------------------------------------- | :--------------: | :----------------------------------- |
| [RNF04](#) | Compatibilidade com Android e iOS | O aplicativo deve ser gratuito e compatível com sistemas Android e iOS.                            | Garantir o acesso universal à plataforma.                        |   Implementado   | [Dylan Cavalcante](https://github.com/dylancavalcante) |
| [RNF09](#) | Design responsivo                 | O design deve se adaptar a diferentes tamanhos de tela e dispositivos.                             | Garantir boa experiência em smartphones, tablets e computadores. |   Implementado   | [Dylan Cavalcante](https://github.com/dylancavalcante) |
| [RNF12](#) | Compatibilidade retroativa        | O sistema deve funcionar nas duas versões anteriores dos principais navegadores e sistemas móveis. | Ampliar o alcance e evitar incompatibilidades.                   | Não implementado | [Breno Lourenço](https://github.com/BrenoLTeixeira) |
| [RNF17](#) | Ciclo de atualização              | A equipe deve liberar atualizações de segurança a cada 3 meses.                                    | Manter o aplicativo seguro e estável.                            | Não implementado | [Breno Lourenço](https://github.com/BrenoLTeixeira) |
| [RNF21](#) | Escalabilidade do sistema         | O sistema deve suportar aumento de 50% de beneficiários sem perda de desempenho.                   | Garantir estabilidade com o crescimento da base de usuários.     | Não implementado | [ Eduarda Domingos](https://github.com/eduardar0) |
| [RNF24](#) | Compatibilidade com API           | O app deve suportar a API mais recente e as duas versões anteriores do sistema operacional.        | Evitar falhas e garantir funcionamento contínuo.                 | Não implementado | [Eduarda Domingos](https://github.com/eduardar0) |

<p align="center"><strong>Fontes:</strong> <a href="https://github.com/dylancavalcante">Dylan Cavalcante</a>, <a href="https://github.com/BrenoLTeixeira">Breno Lourenço</a>, <a href="https://github.com/eduardar0">Eduarda Domingos</a>, 2025</p>

## Referências Bibliográficas


## Bibliografia


## Histórico de Versão

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
|--------|------|-----------|-----------|-------------|
| 1.0 | 09/10/2025 | Versão inicial da pagina de Especificação Suplementar. | [Arthur](https://github.com/arthurfernandesj) | [ Leticia ](https://github.com/leticialopes20) |
| 1.1 | 11/10/2025 | Adição do texto da Introdução,Metodologia e Bibliografia| [Arthur ](https://github.com/arthurfernandesj), [Leticia ](https://github.com/leticialopes20) | [ Giovana](https://github.com/GiovanaFontesS) |
| 1.2 | 12/10/2025 | Criação das tabelas de: Usabilidade, Confiabilidade, Desempenho, Suportabilidade e de participantes| [Arthur](https://github.com/arthurfernandesj), [Breno](https://github.com/BrenoLTeixeira), [Dylan ](https://github.com/dylancavalcante), [Eduarda](https://github.com/eduardar0), [Giovana](https://github.com/GiovanaFontesS), [Leticia](https://github.com/leticialopes20)| [Arthur](https://github.com/arthurfernandesj), [Breno](https://github.com/BrenoLTeixeira), [Dylan](https://github.com/dylancavalcante), [Eduarda](https://github.com/eduardar0), [Giovana](https://github.com/GiovanaFontesS), [Leticia](https://github.com/leticialopes20)|
