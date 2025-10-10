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

---

## Requisitos


**Tabela 01 - Requisitos do ID Jovem**

| ID | Descrição | Rastreabilidade | Categoria | Implementado |
|:--:|:--|:--|:--:|:--:|
| **RF01** | O sistema deve permitir o cadastro do usuário por meio do CPF. | ADD01 | RF | Sim |
| **RF02** | O sistema deve fornecer mecanismos de autenticação e login via Gov.br. | ADD02, BS01, ST01 | RF | Sim |
| **RF03** | O sistema deve permitir a geração e emissão da carteira digital ID Jovem. | ADD03, IDJ01, BS04 | RF | Sim |
| **RF04** | O sistema deve permitir a consulta de benefícios como transporte gratuito e meia-entrada em eventos. | ENTx, IDJ03, BS05 | RF | Sim |
| **RF05** | O sistema deve validar a carteira digital em estabelecimentos conveniados. | ADD04, IDJ02 | RF | Sim |
| **RF06** | O sistema deve exibir uma seção de perguntas frequentes (FAQ) e suporte ao usuário. | ADD05, BS08, IDJ04 | RF | Sim |
| **RF07** | O sistema deve permitir integração com o CadÚnico para atualização automática de dados. | BS09, IDJ08 | RF | Não |
| **RF08** | O sistema deve emitir notificações sobre vencimento e renovação do benefício. | BS11, ST04, IDJ11 | RF | Não |
| **RF09** | O sistema deve permitir o download da carteirinha para uso offline. | ST03, BS19 | RF | Sim |
| **RF10** | O aplicativo deve disponibilizar informações sobre locais e parceiros que aceitam o benefício. | BS10, ST06 | RF | Não |
| **RF11** | O sistema deve fornecer canal de suporte via chat, e-mail ou formulário de contato. | ENTx, BS08, IDJ05 | RF | Não |
| **RF12** | O aplicativo deve permitir que o usuário visualize o histórico de benefícios e viagens. | ST08 | RF | Não |
| **RF13** | O sistema deve apresentar uma seção de novidades e divulgação sobre o programa e novos parceiros. | ADD07, ENT07, BS07| RF | Não |
| **RF14** | O aplicativo deve permitir reserva e emissão de comprovantes de uso do benefício. | ENT10| RF | Sim |
| **RF15** | O sistema deve validar automaticamente a elegibilidade do usuário ao benefício. | ST02 | RF | Sim |
| **RF16** | O sistema deve permitir integração com o Gov.br e outros serviços governamentais. | BS21, ST10 | RF | Sim |
| **RF17** | O aplicativo deve permitir compartilhar a carteirinha em PDF ou imagem. | BS12 | RF | Não |
| **RNF01** | O processo de login deve ser simples e com o menor número de etapas possível. | ENT15, RNF-USA-01 | RNF | Sim |
| **RNF02** | A interface deve ser intuitiva, acessível e legível para jovens com pouca experiência digital. | RNF-USA-02, BS16, ENT16, IDJ09 | RNF | Sim |
| **RNF03** | A emissão da carteira deve ocorrer em até 5 segundos após a solicitação. | RNF-PER-01 | RNF | Sim |
| **RNF04** | O aplicativo deve ser gratuito e compatível com Android e iOS. | RNF-POR-01, IDJ06 | RNF | Sim |
| **RNF05** | Os dados pessoais do usuário devem ser protegidos com criptografia conforme a LGPD. | RNF-SEG-01, BS22 | RNF | Sim |
| **RNF06** | O aplicativo deve funcionar com baixo consumo de internet e ser acessível em regiões carentes. | BS24 | RNF | Não |
| **RNF07** | O aplicativo deve possuir recursos de acessibilidade (alto contraste, leitura de tela, voz e Libras). | BS20, IDJ09 | RNF | Não |
| **RNF08** | O sistema deve garantir disponibilidade mínima de 99,5%. | RNF-CON-01 | RNF | Não |
| **RNF09** | O design deve ser responsivo em diferentes tamanhos de tela e dispositivos. | ST09 | RNF | Sim |

<p align="center" style="font-size:10pt;">
Autor:  
<a href="https://github.com/dylancavalcante">Dylan Cavalcante</a>
</p>
---

## Histórico de Versão

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
|:--:|:--:|:--|:--|:--|
| 1.0 | 09/10/2025 | Criação do artefato consolidado de requisitos | [Dylan Cavalcante](https://github.com/dylancavalcante) | [Leticia Lopes](https://github.com/leticialopes20)|

</center>