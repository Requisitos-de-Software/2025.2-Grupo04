# Requisitos Elicitados

## Introdução
<p align="justify">&emsp;&emsp;
Este artefato reúne todos os requisitos funcionais e não funcionais elicitados para o aplicativo <b>ID Jovem</b>, utilizando as técnicas de 
<a href="https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Analise_de_Documentos/">análise de documentos</a>,
<a href="https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/">entrevista</a>,
<a href="https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/">brainstorm</a>,
<a href="https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspec%C3%A7%C3%A3o/">introspecção</a> e
<a href="https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Storytelling/">storytelling</a>.
</p>

## Metodologia
<p align="justify">&emsp;&emsp;
A tabela a seguir apresenta os requisitos funcionais (RF) e não funcionais (RNF) elicitados, organizados por ID, descrição, rastreabilidade (técnica de origem), categoria e estado de implementação. 
</p>

**Legenda:**

- RF: Requisito Funcional  
- RNF: Requisito Não Funcional  
- ADDx: Análise de Documentos  
- ENTx: Entrevista  
- BSx: Brainstorming  
- ISx: Introspecção  
- STx: Storytelling
- IDJx: Introspecção   

---

## Requisitos

**Tabela 01 - Requisitos do ID Jovem**

| ID | Descrição | Rastreabilidade | Categoria | Implementado |
|:--:|:--|:--|:--:|:--:| 
| **RF01** <a id="rf01"></a> | O sistema deve permitir o cadastro do Jovem Beneficiário por meio do CPF. | ADD01 | RF | Sim |
| **RF02** <a id="rf02"></a> | O sistema deve fornecer mecanismos de autenticação e login via Gov.br. | ADD02, BS01, ST01 | RF | Sim |
| **RF03** <a id="rf03"></a> | O sistema deve permitir a geração e emissão da carteira digital ID Jovem. | ADD03, IDJ01, BS04 | RF | Sim |
| **RF04** <a id="rf04"></a> | O sistema deve permitir a consulta de benefícios como transporte gratuito e meia-entrada em eventos. | **ENT02**, IDJ03, BS05 | RF | Sim |
| **RF05** <a id="rf05"></a> | O sistema deve validar a carteira digital em estabelecimentos conveniados. | ADD04, IDJ02 | RF | Sim |
| **RF06** <a id="rf06"></a> | O sistema deve exibir uma seção de perguntas frequentes (FAQ) e suporte ao Jovem Beneficiário. | ADD05, BS08, IDJ04 | RF | Sim |
| **RF07** <a id="rf07"></a> | O sistema deve permitir integração com o CadÚnico para atualização automática de dados. | BS09, IDJ08 | RF | Não |
| **RF08** <a id="rf08"></a> | O sistema deve emitir notificações sobre vencimento, renovação do benefício, novos parceiros e eventos de interesse. | BS11, ST04, IDJ11, **ENT13** | RF | Não |
| **RF09** <a id="rf09"></a> | O sistema deve permitir o download da carteirinha para uso offline. | ST03, BS19 | RF | Sim |
| **RF10** <a id="rf10"></a> | O aplicativo deve disponibilizar informações sobre locais e parceiros que aceitam o benefício. | BS10, ST06 | RF | Não |
| **RF11** <a id="rf11"></a> | O sistema deve fornecer canal de suporte via chat, e-mail ou formulário de contato. | **ENT05**, BS08, IDJ05 | RF | Não |
| **RF12** <a id="rf12"></a> | O aplicativo deve permitir que o Jovem Beneficiário visualize o histórico de utilização dos benefícios. | ST08, **ENT12** | RF | Não |
| **RF13** <a id="rf13"></a> | O sistema deve apresentar uma seção de "Vantagens e Parcerias" com novidades, divulgação sobre o programa e ofertas exclusivas. | ADD07, BS07, **ENT16** | RF | Não |
| **RF14** <a id="rf14"></a> | O aplicativo deve permitir reserva e emissão de comprovantes de uso do benefício. | **ENT03** | RF | Sim |
| **RF15** <a id="rf15"></a> | O sistema deve validar automaticamente a elegibilidade do Jovem Beneficiário ao benefício. | ST02 | RF | Sim |
| **RF16** <a id="rf16"></a> | O sistema deve permitir integração com o Gov.br e outros serviços governamentais. | BS21, ST10 | RF | Sim |
| **RF17** <a id="rf17"></a> | O aplicativo deve permitir compartilhar a carteirinha em PDF ou imagem. | BS12 | RF | Não |
| **RF18** <a id="rf18"></a> | O sistema deve fornecer informações sobre pendências ou erros relacionados aos benefícios do usuário. | **ENT04** | RF | Não |
| **RF19** <a id="rf19"></a> | O sistema deve permitir que os usuários atualizem seu cadastro e definam preferências pessoais. | **ENT06** | RF | Não |
| **RF20** <a id="rf20"></a> | O sistema deve fornecer alertas sobre possíveis irregularidades no uso dos benefícios. | **ENT09** | RF | Não |
| **RF21** <a id="rf21"></a> | O sistema deve possuir um mapa interativo para visualizar geograficamente parceiros e eventos. | **ENT10** | RF | Não |
| **RF22** <a id="rf22"></a> | O sistema deve apresentar uma agenda integrada de eventos com filtros de busca. | **ENT11** | RF | Não |
| **RF23** <a id="rf23"></a> | O sistema deve fornecer um canal para denúncia ou feedback sobre estabelecimentos que recusam o benefício. | **ENT14** | RF | Não |
| **RF24** <a id="rf24"></a> | O sistema deve permitir que o usuário favorite eventos e estabelecimentos para consulta rápida. | **ENT15** | RF | Não |
| **RNF01** <a id="rnf01"></a> | O processo de login deve ser simples e com o menor número de etapas possível. | ENT17 | RNF | Sim |
| **RNF02** <a id="rnf02"></a> | A interface deve ser intuitiva, acessível, com layout claro e legível, mesmo para jovens com pouca experiência digital. | BS16, IDJ09, **ENT16, ENT20, ENT21** | RNF | Sim |
| **RNF03** <a id="rnf03"></a> | A emissão da carteira deve ocorrer em até 2 segundos após a solicitação. | BS28 | RNF | Sim |
| **RNF04** <a id="rnf04"></a> | O aplicativo deve ser gratuito e compatível com Android e iOS. | IDJ06 | RNF | Sim |
| **RNF05** <a id="rnf05"></a> | Os dados pessoais do Jovem Beneficiário devem ser protegidos com criptografia conforme a LGPD. |BS22, **ENT19** | RNF | Sim |
| **RNF06** <a id="rnf06"></a> | O aplicativo deve funcionar com baixo consumo de internet e ser acessível em regiões carentes. | BS24 | RNF | Não |
| **RNF07** <a id="rnf07"></a> | O aplicativo deve possuir recursos de acessibilidade (alto contraste, leitura de tela, voz e Libras). | BS20, IDJ09 | RNF | Não |
| **RNF08** <a id="rnf08"></a> | O sistema deve garantir disponibilidade mínima de 99,5%. | BS27 | RNF | Não |
| **RNF09** <a id="rnf09"></a> | O design deve ser responsivo em diferentes tamanhos de tela e dispositivos. | ST09 | RNF | Sim |
| **RNF10** | O tempo de carregamento das páginas do site oficial não deve exceder 3 segundos em conexões de internet de baixa velocidade. | BS24 | RNF | Não |
| **RNF11** | O aplicativo deve garantir que as informações sobre os benefícios estejam 100% sincronizadas com a base de dados oficial. | IDJ08 | RNF | Não |
| **RNF12** | O sistema deve ser compatível com as duas versões anteriores dos principais navegadores web e sistemas operacionais móveis. | BS15, BS23, ST09| RNF | Não |
| **RNF13** | A navegação entre as seções do site e do aplicativo deve ser consistente e previsível para o jovem beneficiário. | BS16, ENT17 | RNF | Não |
| **RNF14** | O aplicativo deve apresentar um feedback visual e sonoro claro para cada interação do jovem beneficiário. | BS26 | RNF | Não |
| **RNF15** | O sistema deve ter um tempo máximo de inatividade de 2 horas por mês, fora das janelas de manutenção programada. | BS27 | RNF | Não |
| **RNF16** | O tempo de resposta para validação da carteirinha (QR Code) não deve exceder 2 segundos. | BS28 | RNF | Não |
| **RNF17** | A equipe de desenvolvimento deve disponibilizar atualizações de segurança e correções de bugs em um ciclo de, no máximo, 3 meses. | BS29 | RNF | Não |
| **RNF18** | O aplicativo deve permitir que o jovem beneficiário personalize o tamanho da fonte e o esquema de cores para melhorar a legibilidade. | IDJ18 | RNF | Não |
| **RNF19** | O sistema deve registrar todas as tentativas de validação da carteira, bem-sucedidas ou não, para fins de auditoria. | IDJ19 | RNF | Não |
| **RNF20** | A consulta à elegibilidade do CadÚnico deve retornar o resultado em no máximo 3 segundos. | IDJ20 | RNF | Não |
| **RNF21** | O sistema deve ter capacidade de ser facilmente escalado para atender a um aumento de 50% no número de jovens beneficiários sem degradação do desempenho. | IDJ21 | RNF | Não |
| **RNF22** | O sistema deve manter um log de auditoria de todas as emissões e validações de carteirinhas por 5 anos. | ST12 | RNF | Não |
| **RNF23** | O aplicativo deve carregar as informações de eventos e parceiros em no máximo 3 segundos, mesmo com grande volume de dados. | ST13 | RNF | Não |
| **RNF24** | O aplicativo deve ser compatível com a API mais recente e as duas versões anteriores do sistema operacional móvel. | ST14 | RNF | Não |

<p align="center" style="font-size:10pt;">
Autor:  
<a href="https://github.com/dylancavalcante">Dylan Cavalcante</a>
</p>
---

## Histórico de Versão

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
|:--:|:--:|:--|:--|:--|
| 1.0 | 09/10/2025 | Criação do artefato consolidado de requisitos | [Dylan Cavalcante](https://github.com/dylancavalcante) | [Leticia Lopes](https://github.com/leticialopes20)|
| 1.1 | 09/10/2025 | Adicionados ids aos requisitos para facilitar a citação dos mesmos| [Eduarda Rodrigues](https://github.com/eduardar0) | [Dylan Cavalcante](https://github.com/dylancavalcante)|
| 1.2| 10/10/2025 | Adiciona mais requisitos elicitados em entrevista| [Dylan Cavalcante](https://github.com/dylancavalcante) | [Giovana Fontes](https://github.com/giovanaFontesS)|
| 1.3| 12/10/2025 |     Remoção de titulo da tabela duplicado| [Breno Teixeira](https://github.com/BrenoLteixeira) | [Giovana Fontes](https://github.com/giovanaFontesS)|
| 1.4| 10/10/2025 | Adiciona mais requisitos elicitados em várias técnicas de elicitação| [Dylan Cavalcante](https://github.com/dylancavalcante) | [Giovana Fontes](https://github.com/giovanaFontesS)|
| 1.5| 20/10/2025 | Correção da rastreabilidade de alguns RNF| [Breno Teixeira](https://github.com/BrenolTeixeira) | [Giovana Fontes](https://github.com/giovanaFontesS)|
</center>