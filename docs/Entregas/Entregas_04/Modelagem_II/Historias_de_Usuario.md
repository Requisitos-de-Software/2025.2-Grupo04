# Introdução 

As histórias de usuário são uma forma simples e ágil de representar requisitos funcionais de um sistema, descrevendo de maneira breve o que o usuário precisa que o software faça. Segundo **Vazquez e Simões (Engenharia de Requisitos)**, elas surgiram no contexto da Extreme Programming (XP) como uma unidade de funcionalidade que demonstra o progresso do projeto por meio da entrega de código testado e integrado. Cada história de usuário deve ser compreensível para o cliente, testável pelos desenvolvedores e pequena o suficiente para ser implementada dentro de uma iteração. Atualmente, essa técnica é amplamente utilizada em métodos ágeis, como o Scrum, em que o Product Owner é responsável por elaborá-las com base nas necessidades dos usuários. O uso de histórias de usuário promove a colaboração da equipe, facilita a priorização e garante que o valor entregue seja claro, embora não seja indicado para ambientes que exigem documentação extensa e formal.


### Objetivo

O principal objetivo das histórias de usuário no contexto do ID Jovem é traduzir as necessidades dos jovens beneficiários em funcionalidades claras e testáveis, garantindo que o aplicativo seja acessível, funcional e atenda aos requisitos de inclusão digital. Através delas, o time de desenvolvimento consegue priorizar entregas que realmente impactam a experiência do usuário, assegurando que cada iteração do projeto contribua para um produto final mais eficiente e alinhado às expectativas do público.

### Justificativa de Uso

O uso de histórias de usuário no desenvolvimento do aplicativo ID Jovem se justifica por se tratar de uma abordagem ágil, que permite compreender e documentar de forma simples as necessidades reais dos usuários do sistema — jovens que buscam acesso facilitado a benefícios culturais, esportivos e de transporte. Esse formato favorece a comunicação entre a equipe de desenvolvimento e o Product Owner, garantindo que cada funcionalidade desenvolvida tenha valor prático e direto para o público-alvo. Além disso, as histórias de usuário tornam o processo mais dinâmico e colaborativo, possibilitando ajustes contínuos conforme o feedback dos usuários e a evolução do projeto.

## Metodologia 

As Histórias de Usuário foram elaboradas a partir dos requisitos funcionais, reinterpretados do ponto de vista do usuário do ID Jovem. Cada narrativa descreve de forma clara o que o aplicativo deve fazer e como contribui para o aprendizado, garantindo uma abordagem centrada no usuário e alinhada às práticas ágeis.
A elaboração de uma história de usuário segue um processo simples e objetivo, que busca transformar as necessidades dos usuários em funcionalidades claras e de valor para o sistema. Segundo **Vazquez e Simões (Engenharia de Requisitos)**, uma boa história de usuário deve responder a três perguntas essenciais: quem se beneficia, o que se quer e qual é o benefício.

- *Passo 1* – Identificar o ator **(Quem se beneficia?)**
Define-se quem é o usuário ou parte interessada que se beneficiará da funcionalidade. No caso do aplicativo ID Jovem, esse ator pode ser o jovem beneficiário, o administrador do sistema ou o atendente de suporte.

- *Passo 2* – Definir a funcionalidade **(O que se quer?)**
Descreve-se de forma simples o que o usuário deseja fazer no sistema, sem entrar em detalhes técnicos.

- *Passo 3* – Determinar o valor ou benefício **(Por quê?)**
Explica-se o motivo e o valor que essa funcionalidade traz ao usuário ou ao negócio.

- *Passo 4* – Escrever a história de usuário
Com as informações anteriores, a história é escrita de forma padronizada:
Como (papel), eu quero (ação) para (benefício).

- Passo 5 – Validar e detalhar
A história é validada com o Product Owner e a equipe, podendo ser ajustada ou subdividida se estiver muito ampla. Também são definidos os critérios de aceitação, que servem para testar se a história foi corretamente implementada.

### Participantes


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
<td>00/10/2025</td>
<td>00:00</td>
</tr>
<tr>
<td><a href="https://github.com/BrenoLTeixeira">Breno Teixeira</a></td>
<td>20/10/2025</td>
<td>03:52</td>
</tr>
<tr>
<td><a href="https://github.com/dylancavalcante">Dylan Cavalcante</a></td>
<td>19/10/2025</td>
<td>19:08</td>
</tr>
<tr>
<td><a href="https://github.com/eduardar0">Eduarda Domingos</a></td>
<td>00/10/2025</td>
<td>00:00</td>
</tr>
<tr>
<td><a href="https://github.com/GiovanaFontesS">Giovana Fontes</a></td>
<td>00/10/2025</td>
<td>00:00</td>
</tr>
<tr>
<td><a href="https://github.com/leticialopes20">Letícia Lopes</a></td>
<td>00/10/2025</td>
<td>00:00</td>
</tr>
</tbody>
</table>
</div>
<font size="2"><p style="text-align: center">Fonte: <i>[Dylan Cavalcante](https://github.com/dylancavalcante)</i> </p></font>



## Sumário

- [H01 – Integração com o CadÚnico  (RF07)](#h01)
- [H02 – Emitir notificações sobre vencimento, renovação do benefício (RF08)](#h02)
- [H03 – Disponibilizar informações sobre locais e parceiros que aceitam o benefício (RF10)](#h03)
- [H04 – Fornecer canal de suporte via chat, e-mail ou formulário de contato (RF11)](#h04)
- [H05 – Permitir que o Jovem Beneficiário visualize o histórico de utilização dos benefícios (RF12)](#h05)
- [H06 – Seção de "Vantagens e Parcerias" com novidades, divulgação sobre o programa e ofertas exclusivas (RF13)](#h06)
- [H07 – Permitir compartilhar a carteirinha em PDF ou imagem (RF17)](#h07)
- [H08 – Fornecer informações sobre pendências ou erros relacionados aos benefícios do usuário (RF18)](#h08)
- [H09 – Permitir que os usuários atualizem seu cadastro e definam preferências pessoais (RF19)](#h09)
- [H10 – Fornecer alertas sobre possíveis irregularidades no uso dos benefícios (RF20)](#h10)
- [H11 – Possuir um mapa interativo para visualizar geograficamente parceiros e eventos (RF21)](#h11)
- [H12 – Apresentar uma agenda integrada de eventos com filtros de busca (RF22)](#h12)
- [H13 – Fornecer um canal para denúncia ou feedback sobre estabelecimentos que recusam o benefício (RF23)](#h13)
- [H14 –  Permitir que o usuário favorite eventos e estabelecimentos para consulta rápida (RF24)](#h14)

---

## Tabela Padrão 

A tabela abaixo será utilizada como modelo para a elaboração das histórias de usuário do projeto. Ela padroniza os principais elementos necessários, como a descrição da necessidade, critérios de aceitação, prioridade, status de validação, entre outros. O objetivo é garantir consistência, rastreabilidade e clareza em todas as histórias documentadas.

<font size="3"><p style="text-align: center">Tabela 1: Tabela de Padronização das Historia de usuário</p></font>

| **ID** | USN° |
|--------|------|
| **Rastreabilidade** | Relacionamento com o(s) requisito(s) funcional(is) correspondente(s) à história |
| **Tema** | Funcionalidade principal que a história aborda |
| **Descrição** | Breve explicação do que o usuário deseja fazer e o valor que isso traz  |
| **Critérios de Aceitação** | - Usuário consegue acessar a funcionalidade.<br>- Sistema retorna informações corretas.<br>- Funcionalidade funciona em dispositivos móveis. |
| **Prioridade Usuário** | Alta, média ou baixa |
| **Status** | Validada ou não pelo usuário |
| **Autor** | [Giovana Fontes](https://github.com/GiovanaFontesS) |

<font size="2"><p style="text-align: center">Autor: [Giovana Fontes ](https://github.com/GiovanaFontesS)</p></font>


# **Histórias de Usuário**

### <a name="h01"></a> História 01: Integração com o CadÚnico 

<font size="3"><p style="text-align: center">Tabela 1: US01</p></font>

| **ID** | [US01](#) |
|--------|-------|
| **Rastreabilidade** | [RF07](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf07) |
| **Tema** |  |
| **Descrição** |  |
| **Critérios de Aceitação** |  |
| **Prioridade Usuário** |  |
| **Status** |  |
| **Autor** | [Seu nome](https://github.com/seu-usuario) |

<font size="2"><p style="text-align: center">Autor: [Seu nome ](https://github.com/seu-usuario)</p></font>

### <a name="h02"></a> História 02: Emitir notificações sobre vencimento e renovação do benefício 

<font size="3"><p style="text-align: center">Tabela 2: US02</p></font>

| **ID** | [US02](#) |
|--------|-------|
| **Rastreabilidade** | [RF08](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf08) |
| **Tema** |  |
| **Descrição** |  |
| **Critérios de Aceitação** |  |
| **Prioridade Usuário** |  |
| **Status** |  |
| **Autor** | [Seu nome](https://github.com/seu-usuario) |

<font size="2"><p style="text-align: center">Autor: [Seu nome ](https://github.com/seu-usuario)</p></font>

### <a name="h03"></a> História 03: Disponibilizar informações sobre locais e parceiros que aceitam o benefício

<font size="3"><p style="text-align: center">Tabela 3: US03</p></font>

| **ID** | [US03](#) |
|--------|-------|
| **Rastreabilidade** | [RF10](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf10) |
| **Tema** |  |
| **Descrição** |  |
| **Critérios de Aceitação** |  |
| **Prioridade Usuário** |  |
| **Status** |  |
| **Autor** | [Seu nome](https://github.com/seu-usuario) |

<font size="2"><p style="text-align: center">Autor: [Seu nome ](https://github.com/seu-usuario)</p></font>

### <a name="h04"></a> História 04: Fornecer canal de suporte via chat, e-mail ou formulário de contato

<font size="3"><p style="text-align: center">Tabela 4: US04</p></font>

| **ID** | [US04](#) |
|--------|-------|
| **Rastreabilidade** | [RF11](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf11) |
| **Tema** |  |
| **Descrição** |  |
| **Critérios de Aceitação** |  |
| **Prioridade Usuário** |  |
| **Status** |  |
| **Autor** | [Seu nome](https://github.com/seu-usuario) |

<font size="2"><p style="text-align: center">Autor: [Seu nome ](https://github.com/seu-usuario)</p></font>

### <a name="h05"></a> História 05: Permitir que o Jovem Beneficiário visualize o histórico de utilização dos benefícios 

<font size="3"><p style="text-align: center">Tabela 5: US05</p></font>

| **ID** | [US05](#) |
|--------|-------|
| **Rastreabilidade** | [RF12](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf12) |
| **Tema** | Permitir que o Jovem Beneficiário visualize o histórico de utilização dos benefícios  |
| **Descrição** | Eu, como Jovem Beneficiário, desejo visualizar um histórico de onde e quando utilizei meus benefícios (como viagens interestaduais e meia-entrada), para poder acompanhar meu uso e ter um registro das minhas atividades. |
| **Critérios de Aceitação** | - O histórico deve exibir uma lista cronológica das utilizações. 
|                             |  - Cada item da lista deve detalhar o tipo de benefício usado (ex: Meia-entrada, Vaga gratuita em transporte). 
|                             | - Cada item deve registrar a data e, se possível, a empresa ou evento onde foi utilizado. 
|     _ | - O histórico deve ser de fácil acesso a partir do menu principal ou do perfil do jovem beneficiário. |
| **Prioridade Usuário** | média |
| **Status** | Aguardando validação |
| **Autor** | [Dylan Cavalcante](https://github.com/dylancavalcante) |

<font size="2"><p style="text-align: center">Autor: [Dylan Cavalcante](https://github.com/dylancavalcante)</p></font>

### <a name="h06"></a> História 06: Seção de "Vantagens e Parcerias" com novidades, divulgação sobre o programa e ofertas exclusivas 

<font size="3"><p style="text-align: center">Tabela 6: US06</p></font>

| **ID** | [US06](#) |
|--------|-------|
| **Rastreabilidade** | [RF13](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf13) |
| **Tema** | Seção de "Vantagens e Parcerias" com novidades, divulgação sobre o programa e ofertas exclusivas |
| **Descrição** | Eu, como Jovem Beneficiário, desejo acessar uma seção de "Vantagens e Parcerias" para descobrir novidades sobre o programa, cursos profissionalizantes, e ofertas exclusivas de parceiros. |
| **Critérios de Aceitação** | - A seção deve ser claramente visível no menu principal do aplicativo. 
|                             | - O conteúdo deve ser dividido em categorias (ex: 'Novidades do Programa', 'Cursos e Capacitação', 'Ofertas de Parceiros'). 
|                             | - O conteúdo deve ser atualizado regularmente. 
|                             | - As ofertas e notícias devem ser relevantes para o público do ID Jovem. |
| **Prioridade Usuário** | média|
| **Status** | Aguardando validação |
| **Autor** | [Dylan Cavalcante](https://github.com/dylancavalcante) |

<font size="2"><p style="text-align: center">Autor: [Dylan Cavalcante](https://github.com/dylancavalcante)</p></font>

### <a name="h07"></a> História 07: Permitir compartilhar a carteirinha em PDF ou imagem

<font size="3"><p style="text-align: center">Tabela 7: US07</p></font>

| **ID** | [US07](#) |
|--------|-------|
| **Rastreabilidade** | [RF17](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf17) |
| **Tema** |  |
| **Descrição** |  |
| **Critérios de Aceitação** |  |
| **Prioridade Usuário** |  |
| **Status** |  |
| **Autor** | [Seu nome](https://github.com/seu-usuario) |

<font size="2"><p style="text-align: center">Autor: [Seu nome ](https://github.com/seu-usuario)</p></font>

### <a name="h08"></a> História 08: Fornecer informações sobre pendências ou erros relacionados aos benefícios do jovem beneficiário

<font size="3"><p style="text-align: center">Tabela 8: US08</p></font>

| **ID** | [US08](#) |
|--------|-------|
| **Rastreabilidade** | [RF18](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf18) |
| **Tema** |  |
| **Descrição** |  |
| **Critérios de Aceitação** |  |
| **Prioridade Usuário** |  |
| **Status** |  |
| **Autor** | [Seu nome](https://github.com/seu-usuario) |

<font size="2"><p style="text-align: center">Autor: [Seu nome ](https://github.com/seu-usuario)</p></font>

### <a name="h09"></a> História 09: Permitir que o jovem beneficiário atualize seu cadastro e defina preferências pessoais 

<font size="3"><p style="text-align: center">Tabela 9: US09</p></font>

| **ID** | [US09](#) |
|--------|-------|
| **Rastreabilidade** | [RF19](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf19) |
| **Tema** | Gerenciamento de Perfil e Preferências |
| **Descrição** | Eu, como Jovem Beneficiário, desejo poder atualizar minhas informações de cadastro e definir preferências pessoais, para manter meus dados corretos e receber conteúdo alinhado aos meus interesses. |
| **Critérios de Aceitação** | - O usuário deve conseguir acessar uma seção "Meu Perfil" ou "Configurações".<br>- O usuário deve conseguir editar campos cadastrais (ex: e-mail, telefone).<br>- O usuário deve conseguir salvar as alterações no perfil.<br>- O usuário deve poder selecionar categorias de interesse (ex: shows, esportes, teatro) para personalizar notificações. |
| **Prioridade Usuário** | Média |
| **Status** | Aguardando validação |
| **Autor** | [Breno Teixeira](https://github.com/BrenoLTeixeira) |

<font size="2"><p style="text-align: center">Autor: [Breno Teixeira](https://github.com/BrenoLTeixeira)</p></font>

### <a name="h10"></a> História 10: Fornecer alertas sobre possíveis irregularidades no uso dos benefícios 

<font size="3"><p style="text-align: center">Tabela 10: US10</p></font>

| **ID** | [US10](#) |
|--------|-------|
| **Rastreabilidade** | [RF20](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf20) |
| **Tema** |  |
| **Descrição** |  |
| **Critérios de Aceitação** |  |
| **Prioridade Usuário** |  |
| **Status** |  |
| **Autor** | [Seu nome](https://github.com/seu-usuario) |

<font size="2"><p style="text-align: center">Autor: [Seu nome ](https://github.com/seu-usuario)</p></font>

### <a name="h11"></a> História 11: Possuir um mapa interativo para visualizar geograficamente parceiros e eventos

<font size="3"><p style="text-align: center">Tabela 11: US11</p></font>

| **ID** | [US11](#) |
|--------|-------|
| **Rastreabilidade** | [RF21](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf21) |
| **Tema** |  |
| **Descrição** |  |
| **Critérios de Aceitação** |  |
| **Prioridade Usuário** |  |
| **Status** |  |
| **Autor** | [Seu nome](https://github.com/seu-usuario) |

<font size="2"><p style="text-align: center">Autor: [Seu nome ](https://github.com/seu-usuario)</p></font>

### <a name="h12"></a> História 12: Apresentar uma agenda integrada de eventos com filtros de busca 

<font size="3"><p style="text-align: center">Tabela 12: US12</p></font>

| **ID** | [US12](#) |
|--------|-------|
| **Rastreabilidade** | [RF22](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf22) |
| **Tema** |  |
| **Descrição** |  |
| **Critérios de Aceitação** |  |
| **Prioridade Usuário** |  |
| **Status** |  |
| **Autor** | [Seu nome](https://github.com/seu-usuario) |

<font size="2"><p style="text-align: center">Autor: [Seu nome ](https://github.com/seu-usuario)</p></font>

### <a name="h13"></a> História 13: Fornecer um canal para denúncia ou feedback sobre estabelecimentos que recusam o benefício

<font size="3"><p style="text-align: center">Tabela 13: US13</p></font>

| **ID** | [US13](#) |
|--------|-------|
| **Rastreabilidade** | [RF23](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf23) |
| **Tema** | Canal de Denúncia e Feedback |
| **Descrição** | Eu, como Jovem Beneficiário, desejo ter um canal para enviar denúncias ou feedbacks sobre estabelecimentos que recusaram a ID Jovem, para que os administradores do programa possam tomar providências e garantir meu direito. |
| **Critérios de Aceitação** | - Deve existir uma seção "Denúncia" ou "Reportar Problema" no aplicativo.<br>- O formulário deve permitir inserir o nome do estabelecimento, data, local e uma descrição do ocorrido.<br>- O sistema deve permitir (opcionalmente) anexar uma foto do local ou comprovante.<br>- O sistema deve enviar uma confirmação de recebimento da denúncia/feedback. |
| **Prioridade Usuário** | Alta |
| **Status** | Aguardando validação |
| **Autor** | [Breno Teixeira](https://github.com/BrenoLTeixeira) |

<font size="2"><p style="text-align: center">Autor: [Breno Teixeira](https://github.com/BrenoLTeixeira)</p></font>

### <a name="h14"></a> História 14: Permitir que o jovem beneficiário favorite eventos e estabelecimentos para consulta rápida 

<font size="3"><p style="text-align: center">Tabela 14: US14</p></font>

| **ID** | [US14](#) |
|--------|-------|
| **Rastreabilidade** | [RF24](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf24) |
| **Tema** | Permitir que o jovem beneficiário favorite eventos e estabelecimentos para consulta rápida  |
| **Descrição** | Eu, como Jovem Beneficiário, desejo salvar (favoritar) eventos e estabelecimentos parceiros do meu interesse para poder consultá-los rapidamente no futuro em uma lista dedicada. |
| **Critérios de Aceitação** | - Deve haver um botão ou ícone (ex: estrela, coração) visível na página de detalhes de cada evento/estabelecimento para favoritá-lo. 
|         _ | - Deve existir uma seção "Meus Favoritos" no aplicativo, acessível pelo menu ou perfil do jovem beneficiário. 
|                             | - Ao clicar no botão de favoritar, o item deve ser adicionado à lista "Meus Favoritos". 
|                             | - O jovem beneficiário deve poder remover um item da lista de favoritos a qualquer momento. |
| **Prioridade Usuário** | baixa |
| **Status** | Aguardando validação |
| **Autor** | [Dylan Cavalcante](https://github.com/dylancavalcante) |

<font size="2"><p style="text-align: center">Autor: [Dylan Cavalcante](https://github.com/dylancavalcante)</p></font>

##  Referências Bibliográficas

> <a id="RP3" href="#TEC3">3.</a> VAZQUEZ, Carlos Eduardo; SIMÕES, Guilherme Siqueira; SIMÕES. *Engenharia de Requisitos: Software Orientado ao Negócio.* São Paulo , 2016. Acesso em: 19 de outubro de 2025.



##  Histórico de Versão

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
|--------|------|-----------|-----------|-------------|
| 1.0 | 19/10/2025 | Criação do Documento: Introdução, Metodologia, justificativa de uso e objetivo  | [Giovana Fontes](https://github.com/GiovanaFontesS) | [ Leticia ](https://github.com/leticialopes20) |
| 1.1 | 19/10/2025 | Historia de usuario [US05](#), [US06](#), [US14](#) | [Dylan Cavalcante](https://github.com/dylancavalcante) | [ Leticia ](https://github.com/leticialopes20) |
| 1.2 | 20/10/2025 | Preenchimento das histórias de usuário [US09](#) e [US13](#).| [Breno Teixeira](https://github.com/BrenoLTeixeira) | [ Dylan Cavalcante ](https://github.com/dylancavalcante) |