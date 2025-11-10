# Storytelling

## Introdução

A técnica de **Storytelling** baseia-se na utilização de histórias em grupos, incluindo organizações, como um método de comunicação para que os envolvidos possam compartilhar conhecimento. Emprega-se o uso de técnicas de contação de histórias que inspiram e motivam os participantes através de linguagens mais cotidianas, criando entretenimento durante o processo de construção<a id="anchor_1" href="#QT1">[1]</a>. Alguns dos benefícios dessa técnica são:

* Engajamento de Stakeholders.
* Visão das necessidades do usuário.
* Obtenção de novas ideias.
* Melhoria na comunicação entre a equipe e os usuários.
* Refinamento e contextualização dos requisitos.

## Metodologia

Foram utilizadas as [Personas](./Definicao_de_Personas.md) definidas anteriormente no projeto do aplicativo **ID Jovem** para a elaboração das histórias e contextos. Essa abordagem, que utiliza narrativas para explorar o uso de um sistema, é fundamental na criação de cenários<a id="anchor_2" href="#QT2">[2]</a>. As histórias foram essenciais para entendermos as necessidades e os anseios de cada persona. A partir desses contextos, conseguimos identificar e listar os requisitos que o aplicativo precisa atender para fazer a diferença na vida deles.

## Storytelling

### História 1

**Ana Clara**, 19 anos, estudante universitária, ama viajar e participar de eventos culturais, mas possui uma renda limitada.
Ela utiliza o **ID Jovem** para garantir descontos em passagens de ônibus e acesso gratuito a eventos culturais.

Porém, Ana já perdeu oportunidades por não conseguir verificar rapidamente se seu benefício estava válido.
Ela deseja que o aplicativo seja simples, com **login rápido**, notificações automáticas sobre a validade do documento e a possibilidade de **baixar sua carteirinha offline**, para não depender de internet em suas viagens.

---

### História 2

**João Pedro**, 24 anos, trabalhador informal, usa o benefício do ID Jovem para visitar sua família em outra cidade.

Com a rotina corrida, João precisa de um aplicativo **confiável e estável**, que permita a compra de passagens diretamente pelo sistema ou redirecione para empresas de transporte parceiras.
Ele valoriza principalmente a **segurança dos seus dados** e quer que o aplicativo seja **acessível em qualquer dispositivo**, já que alterna entre celular e computador.

---

### História 3

**Camila Souza**, 23 anos, em busca de oportunidades no mercado de trabalho, gosta de frequentar museus, cinemas e shows.
O ID Jovem é, para ela, uma ferramenta de inclusão cultural.

Camila deseja que o aplicativo traga um **mapa interativo de eventos e estabelecimentos parceiros**, atualizado em tempo real. Além disso, gostaria de receber **recomendações personalizadas** com base em sua localização e interesses.
Isso ajudaria Camila a se sentir mais conectada à cidade e aproveitar melhor os benefícios.

---

## Lista de Requisitos Elicitados


<p align="center"><strong>Tabela 1 - </strong> Requisitos elicitados pelo storytelling.</p>

| Identificador | Tipo | Requisito | Implementação |
| :--: | :--: | :-- | :--: |
| **ST01** <a id="st01"></a> | RF | O usuário deve realizar login com a conta gov.br. | Sim |
| **ST02** <a id="st02"></a> | RF | O sistema deve validar automaticamente a elegibilidade do benefício. | Sim |
| **ST03** <a id="st03"></a> | RF | O aplicativo deve permitir baixar a carteirinha para uso offline. | Sim |
| **ST04** <a id="st04"></a> | RF | O sistema deve disponibilizar notificações sobre a expiração do benefício. | Não |
| **ST05** <a id="st05"></a> | RF | O usuário deve poder consultar e reservar passagens diretamente no app ou via integração com empresas parceiras. | Não |
| **ST06** <a id="st06"></a> | RF | O aplicativo deve fornecer mapa de eventos culturais e parceiros disponíveis. | Não |
| **ST07** <a id="st07"></a> | RF | O sistema deve oferecer recomendações personalizadas de eventos conforme localização do usuário. | Não |
| **ST08** <a id="st08"></a> | RF | O usuário deve conseguir verificar histórico de viagens realizadas com o ID Jovem. | Não |
| **ST09** <a id="st09"></a> | RNF | O design deve ser acessível e responsivo em diferentes dispositivos. | Sim |
| **ST10** <a id="st10"></a> | RNF | O sistema deve garantir segurança e integridade dos dados dos usuários. | Sim |
| **ST11** <a id="st11"></a> | RNF | Usabilidade: O fluxo de emissão da carteirinha digital deve ser concluído em no máximo 5 passos | Não |
| **ST12** <a id="st12"></a> | RNF | Confiabilidade: O sistema deve manter um log de auditoria de todas as emissões e validações de carteirinhas por 5 anos. | Não |
| **ST13** <a id="st13"></a> | RNF | Desempenho: O aplicativo deve carregar as informações de eventos e parceiros em no máximo 3 segundos, mesmo com grande volume de dados. | Não |
| **ST14** <a id="st14"></a> | RNF | Suportabilidade: O aplicativo deve ser compatível com a API mais recente e as duas versões anteriores do sistema operacional móvel. | Não |

<p style="text-align: center; font-size: 10pt;">Fonte: <a href="https://github.com/eduardar0">Eduarda Rodrigues</a></p>

## Referências Bibliográficas

<p><a id="QT1" href="#anchor_1">1.</a> SERRANO, M.; SERRANO, M. <b>Requisitos – Aula 07</b>. [S. l.], 2025. Material de aula (slide).</p>
<p><a id="QT2" href="#anchor_2">2.</a> Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) <b>Interação Humano-Computador e Experiência do usuário</b>. Autopublicação. ISBN: 978-65-00-19677-1. Cap 8.3: Cenários.</p>

## Histórico de Versão
| Versão |    Data    |      Descrição       |                        Autor(es)                        |                       Revisor(es)                       |
| :----: | :--------: | :------------------: | :-----------------------------------------------------: | :-----------------------------------------------------: |
| `1.0` | 29/09/2025 | Versão inicial da página de Storytelling para o ID Jovem | [Eduarda](https://github.com/eduardar0) | [Arthur](https://github.com/) |
| `1.1`  | 10/10/2025 | Arrumando citação das Referências | [Breno](https://github.com/BrenoLteixeira) | [Arthur](https://github.com/) |
