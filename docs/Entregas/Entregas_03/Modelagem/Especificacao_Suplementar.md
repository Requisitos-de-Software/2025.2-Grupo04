# Especificação suplementar

## Introdução
A **Especificação Suplementar**, no contexto da engenharia de software, refere-se à prática de classificar e organizar os requisitos de um sistema em diferentes grupos ou categorias. Essa abordagem facilita a compreensão, o gerenciamento e a priorização dos requisitos durante o ciclo de desenvolvimento do software.

"Este documento captura os requisitos de sistema que não foram identificados imediatamente nos Casos de Uso do Modelo de Casos de Uso. Entre estes requisitos estão incluídos: o Requisitos legais e reguladores, incluindo padrões de aplicativo; Atributos de qualidade do sistema a ser criado, incluindo requisitos de usabilidade, confiabilidade, desempenho e suportabilidade. Outros requisitos, como sistemas operacionais e ambientes, requisitos de compatibilidade e restrições de design" <a id="TEC1" href="#RP1">[1]</a>. Esses requisitos são cruciais para garantir a qualidade do software e a satisfação do usuário  <a id="TEC2" href="#RP2">[2]</a>.

## Metodologia

A Metodologia utilizada neste artefato foi baseada no modelo FURPS+. "É um sistema para a classificação de requisitos, o acrônimo representa categorias que podem ser usadas na definição de requisitos" <a id="TEC3" href="#RP3">[3]</a>. Dentre elas: Funcionalidade, Usabilidade, Confiabilidade, Desempenho, Suportabilidade, sendo que o "+" engloba outros requisitos não-funcionais: requisitos de design, requisitos de implementação, requisitos de interface, requisitos físicos <a id="TEC3" href="#RP3">[3]</a>.

Este artefato foi desenvolvido de maneira assíncrona por cada membro do grupo. Após a conclusão, o material foi enviado ao [nome](https://github.com/) e [nome](https://github.com/), que ficaram responsáveis pela criação e publicação da página no GitHub Pages.

A Legenda para identificação dos requisitos em cada acrônimo estão representadas na tabela 1 e na tabela 2.


<p style="text-align: center"><strong>Tabela 1 -</strong> Legenda das tabelas FURPS</p>

| Acrônimo | Significado | Tradução | Identificador |
|:--:|:--:|:--:|:--:|
| F | Functionality | Funcionalidade | - |
| U | Usability | Usabilidade | RU |
| R | Reliability | Confiabilidade | RR |
| P | Performance | Desempenho | RP |
| S | Supportability | Suportabilidade | RS |

<p style="text-align: center"><strong>Fonte:</strong> <a href="https://github.com/">Arthur Fernandes</a>, 2025</p>

---

<p style="text-align: center"><strong>Tabela 2 -</strong> Legenda das tabelas +</p>

| Acrônimo | Significado | Tradução | Identificador |
|:--:|:--:|:--:|:--:|
| +D | Plus: Design constrains | Requisitos de Design | +D |
| +Im | Plus: Implementation constrains | Requisitos de Implementação | +Im |
| +In | Plus: Interface constrains | Requisitos de Interface | +In |
| +P | Plus: Physical constrains | Requisitos Físicos | +P |

<p style="text-align: center"><strong>Fonte:</strong> <a href="https://github.com/arthurfernandesj">Arthur Fernandes</a>, 2025</p>

## Funcionalidade

A **funcionalidade** trata do núcleo do sistema, abordando as funções e capacidades que o software precisa oferecer. Os requisitos de funcionalidade especificam o que o sistema deve fazer, englobando tarefas, operações, recursos e comportamentos esperados.

Os requisitos funcionais foram capturados ateriormente com as técnicas de [Brainstorming](), [Introspeção](), [Entrevista](), [Observação](), [Storytelling](), e podem ser consultados em [Técnicas Elicitados](). Os casos de uso também podem ser considerados como requisitos funcionais. 

## Usabilidade

A **usabilidade** no contexto do **aplicativo ID Jovem** refere-se à facilidade com que os jovens conseguem emitir, acessar e utilizar seu documento digital de identificação para obter benefícios, como meia-entrada em eventos culturais, esportivos e transporte interestadual gratuito ou com desconto. Essa usabilidade deve garantir simplicidade, acessibilidade e clareza nas informações apresentadas, considerando a diversidade do público jovem, incluindo pessoas com deficiência.

Esta seção abrange todos os requisitos que influenciam a usabilidade do sistema. Os requisitos não funcionais relacionados à usabilidade estão descritos na **Tabela 3**.

<p align="center"><strong>Tabela 3 -</strong> Requisitos de Usabilidade do ID Jovem</p>

| ID | Descrição do requisito |
|:-:|:-:|
| RU001 | O aplicativo ID Jovem deve ser fácil e intuitivo, permitindo que o jovem emita ou acesse sua identificação digital em até 5 minutos. |
| RU002 | O aplicativo deve informar o usuário, ao clicar em links externos (como acesso ao site do Governo Federal ou transportadoras), que será redirecionado para fora do ambiente do ID Jovem. |
| RU003 | Todas as imagens e ícones significativos devem conter texto alternativo que descreva sua função, garantindo acessibilidade a leitores de tela. |
| RU004 | Vídeos ou áudios explicativos sobre o uso do ID Jovem não devem iniciar automaticamente e devem oferecer transcrição. |
| RU005 | O fluxo de navegação deve ser lógico e contínuo, permitindo que o usuário retorne facilmente à tela inicial ou anterior. |
| RU006 | Os botões e rótulos devem possuir textos curtos e objetivos, como “Emitir ID”, “Consultar Benefício” e “Atualizar Dados”. |
| RU007 | O aplicativo deve disponibilizar **modo de alto contraste** para usuários com baixa visão. |
| RU008 | As fontes devem possuir tamanho ajustável pelo usuário e não serem fixas. |
| RU009 | O contraste entre elementos da interface e o plano de fundo deve atender aos critérios de sucesso **WCAG AA**. |
| RU010 | O contraste entre textos normais e o plano de fundo deve atender aos critérios de sucesso **WCAG AAA**. |
| RU011 | O contraste de textos grandes e o plano de fundo também deve atender aos critérios **WCAG AAA**. |
| RU012 | A hierarquia de conteúdo (título, subtítulo, texto e botões) deve seguir uma estrutura lógica e coerente. |
| RU013 | Caso sejam utilizados modais (como mensagens de confirmação ou erro), eles devem ser fáceis de fechar e não ocupar toda a tela. |
| RU014 | O aplicativo deve ser responsivo, permitindo uso tanto na orientação vertical quanto horizontal do dispositivo. |
| RU015 | Não deve haver rolagem horizontal nas telas do aplicativo. |
| RU016 | Deve haver espaçamento adequado entre botões e elementos interativos, evitando toques acidentais. |
| RU017 | O aplicativo deve incluir um campo de busca para localizar rapidamente informações, como pontos de emissão e transportadoras parceiras. |
| RU018 | O aplicativo deve exibir mensagens de erro e sucesso de forma clara e também oferecer suporte sonoro para usuários cegos. |
| RU019 | As áreas clicáveis (botões e links) devem ter dimensões mínimas de **44px x 44px**, conforme diretrizes de acessibilidade móvel. |

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/arthurfernandesj">Arthur Fernandes</a> 2025</p></font>


## Confiabilidade

## Desempenho

## Suportabilidade

## Outros requisitos do Produto (+)

### Requisitos de Design

### Requisitos de Implementação


### Requisitos de interface

### Requisitos Físicos

## Referências Bibliográficas

## Bibliografia

## Histórico de Versão

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
|--------|------|-----------|-----------|-------------|
| 1.0 | 09/10/2025 | Versão inicial da pagina de Especificação Suplementar. | [Arthur Fernandes](https://github.com/arthurfernandesj) | [ Leticia Lopes ](https://github.com/leticialopes20) |