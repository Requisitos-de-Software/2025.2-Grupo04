
# Lexicos

## Introdução 

O Léxico é uma técnica de modelagem de requisitos que estabelece a terminologia e a descrição dos termos relevantes ao projeto, sendo essencialmente um Léxico Ampliado da Linguagem (LAL). Sua finalidade é garantir a comunicação e o entendimento uniformes entre todos os envolvidos, tratando aspectos técnicos e abstratos com clareza. Cada termo, ou símbolo, no Léxico é definido por dois componentes cruciais: a Noção e o Impacto. A Noção provê a descrição conceitual do símbolo, indicando o que ele é ou quem o realiza. Já o Impacto descreve os reflexos e as consequências do termo, como as ações ou mudanças de estado que são desencadeadas. As entradas no Léxico são classificadas em tipos, como Verbo, Objeto e Estado, o que estrutura a linguagem do domínio e serve como uma base sólida para a documentação e análise do sistema.


### *1) Objetivo*
O principal objetivo do Léxico (ou LAL – Léxico Ampliado da Linguagem) é fornecer uma terminologia e a descrição de termos relevantes ao software. Ele tem como foco a atividade de modelagem, que visa elaborar modelos capazes de representar características ou comportamentos de um software. Ao padronizar os termos, o Léxico atua como uma ferramenta para simplificar aspectos muito técnicos ou para tornar mais concreto e claro aspectos muito abstratos do sistema, que muitas vezes são complexos e pouco conhecidos dos clientes.

### *2) Justificativa do Uso*
O uso do Léxico é justificado por ser uma forma de tratar aspectos abstratos ou técnicos com apelo visual , o que melhora a comunicação e a compreensão do sistema. Ao estabelecer a terminologia do domínio, ele garante que todos os envolvidos, incluindo clientes, usem e compreendam a mesma linguagem. Dessa forma, ele contribui para a clareza e objetividade dos modelos de requisitos, sendo fundamental para o desenvolvimento de modelos simples e claros, com notações adequadas.

## Metodologia
A metodologia para a criação do Léxico, conforme apresentado, exige que cada termo, ou símbolo, seja descrito com dois elementos chave: Noção e Impacto.

### **Noção (O Que é e O Que Faz):** 
Define a descrição conceitual do símbolo. Dependendo do tipo de entrada, a Noção pode significar: <a id="TEC1" href="#RP1">[1]</a>

* Para um Verbo (ação), quem a realiza, qual ambiente ou procedimento está envolvido.
* Para um Objeto (entidade), sua definição e as ações que podem ser aplicadas a ele.
* Para um Estado (condição), o que ele significa e quais ações levam ou provocam o estado.

### **Impacto (Quais Ações Musculares):** 
Descreve os reflexos ou consequências daquele símbolo.<a id="TEC1" href="#RP1">[1]</a>

* Para um Verbo, descreve os reflexos no criador, no ambiente, nos outros criadores, e quais novos estados são consequentes.
* Para um Objeto, as ações que podem ser realizadas para alterar o objeto e o impacto disso no sistema.
* Para um Estado, quais outros estados ou ações podem ordenar o estado que se desenvolve.

Cada entrada no Léxico pertence a somente um tipo (Verbo, Objeto, Estado), e a heurística de definição (Noção e Impacto) é aplicada de acordo com esse tipo. Essa descrição estruturada dos termos é fundamental para o LAL.

## Léxico Ampliado da Linguagem (LAL) do ID Jovem

Os léxicos do sistema ID Jovem foram identificados a partir da utilização do aplicativo e dos [requisitos elicitados](https://github.com/Requisitos-de-Software/2025.2-Grupo04/blob/main/docs/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados.md) nas etapas anteriores. Na tabela 1 abaixo, temos um exemplo de como os léxicos serão apresentados e descritos:

<div style="text-align: center">
<p><b>Tabela 1:</b> Modelo dos léxicos
</div>

| Léxico         | Sinônimo | Noção   | Impacto             | Classificação       | Rastreabilidade | Fonte      |
| -------------- | -------- | ------- | ------------------- | ------------------- | ------------------- | -----------|  
| Nome do Léxico | Sinônimo | Símbolo | Descrição do efeito | Verbo/Objeto/Estado | Código do requisito referente ao Léxico |Pessoa responsável |

<p align="center"><strong>Fonte:</strong><a href="https://github.com/eduardar0"> Eduarda</a>, 2025</p>


## Objetos

Os léxicos do tipo objeto referem-se às entidades, elementos ou objetos que são manipulados ou sobre os quais as ações são realizadas dentro do aplicativo ID Jovem. Nas tabelas à seguir, é possível verificar os principais léxicos classificados como objetos que foram identificados no ID Jovem. Esses léxicos incluem elementos como "Jovem Beeficiário", "Carteira Digital" entre outros. Cada um desses léxicos é descrito detalhadamente, incluindo sua noção, que define o objeto e seus relacionamentos com outros objetos, e seu impacto, que descreve as ações possíveis sobre o objeto dentro do sistema.


<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 2: </b>Léxicos classificados como Objetos</p></font>
</div>

| Léxico               | Sinônimo            | Noção                        | Impacto                                                                                               | Classificação | Rastreabilidade                           | Fonte                                      |
|----------------------|--------------------|------------------------------|------------------------------------------------------------------------------------------------------|---------------|--------------------------------------------|-------------------------------------------|
| L01 - Jovem Beneficiário        | Jovem, Participante | Dados do jovem             | Permite cadastro, atualização e acesso à carteira digital do ID Jovem.                                | Objeto        | [RF01, RF02, RF15](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/)             | [Eduarda](https://github.com/eduardar0)                           |
| L02 - Carteira Digital| Carteirinha do ID Jovem    | Identificação digital        | O Jovem Beneficiário pode visualizar, baixar e compartilhar sua carteira digital.                               | Objeto        | [RF03, RF05](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/)                       | [Eduarda](https://github.com/eduardar0)             |
| L03 - Cadastro    |  Registro, Inscrição, Conta, Perfil  | Refere-se ao processo de registro e armazenamento das informações do Jovem Beneficiário no sistema ID Jovem, incluindo dados pessoais e de identificação.            |   O cadastro é essencial para liberar o acesso à carteirinha digital e aos benefícios do programa. Sem ele, o usuário não pode autenticar-se nem gerar seu ID Jovem.       | Objeto        | [RF01](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/), [RF19](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/)                     | [Giovana](https://github.com/GiovanaFontesS)                                  |
| L04 - Elegibilidade      |  Validação, Critério de acesso, Confirmação de direito  |   Representa a verificação automática que o sistema realiza para confirmar se o Jovem Beneficiário cumpre os critérios exigidos para receber o benefício ID Jovem.          |  A elegibilidade garante que apenas jovens com perfil válido possam gerar e utilizar a carteirinha. Essa validação é essencial para evitar uso indevido dos benefícios.        | Objeto        | [RF15](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/)                     | [Giovana](https://github.com/GiovanaFontesS)                                   |
| L04 - Transporte Gratuito   | Passagem Livre, Viagem Interestadual  |  Serviço que oferece gratuidade ou desconto no transporte interestadual para jovens cadastrados no ID Jovem | Facilita o deslocamento dos beneficiários entre estados, garantindo o direito de mobilidade previsto pelo programa.     | Objeto        | [RF04](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/)                       | [Arthur](https://github.com/arthurfernandesj)                                     |
| L05 - Estabelecimento Conveniado     |  Parceiro, Local Credenciado     | Empresa, instituição ou ponto de serviço que aceita o ID Jovem como comprovante de benefício. | Permite a utilização dos benefícios de meia-entrada e transporte gratuito, ampliando o alcance do programa. | Objeto        | [RF05](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/)                            | [Arthur](https://github.com/arthurfernandesj)                                  |
| L07 - Benefício | Vantagem, Desconto | Refere-se aos direitos garantidos pelo programa. | O Jovem Beneficiário pode consultar os benefícios disponíveis, visualizar seu histórico de uso e emitir comprovantes de utilização. | Objeto | [RF04](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/), [RF12](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/) | [Breno](https://github.com/BrenoLteixeira) |
| L08 - Parceiro | Estabelecimento conveniado, Empresa parceira | Entidade que aceita a carteira ID Jovem e concede os benefícios. | O Jovem Beneficiário pode consultar a lista de parceiros, visualizar sua localização e obter informações de contato. | Objeto | [RF10](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/), [RF13](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/) | [Breno](https://github.com/BrenoLteixeira) |
| L09 - FAQ e Suporte       | Ajuda, Central de Atendimento   |   Seção do aplicativo dedicada a responder dúvidas frequentes e oferecer suporte técnico e informativo ao Jovem Beneficiário.   | Facilita o entendimento do funcionamento do aplicativo, reduzindo erros e aumentando a autonomia do jovem beneficiário.      | Objeto        | [RF06](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/)  | [Letícia](https://github.com/leticialopes20)    |
| L10 - Agenda de Eventos       | Cronograma, Calendário de Atividades   | Cronograma, Calendário de Atividades  | Permite ao Jovem Beneficiário visualizar, filtrar e se planejar para eventos, incentivando o uso do benefício de meia-entrada.      | Objeto  | [RF22](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/)   | [Letícia](https://github.com/leticialopes20)                                    |
| L11 -  Notificação   |  Alerta, Aviso  |  Mensagem automatizada enviada pelo sistema para informar o Jovem Beneficiário sobre vencimentos, novos parceiros, ou eventos de interesse.  | Mantém o jovem beneficiário atualizado, melhorando o engajamento e evitando a perda de prazos relacionados ao benefício      | Objeto | [RF08](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/)   | [Dylan](https://github.com/dylancavalcante)                                    |
| L12 - Mapa Interativo | Localizador, Mapa de Parceiros   |Localizador, Mapa de Parceiros |Facilita o planejamento e deslocamento do Jovem Beneficiário até locais onde pode usufruir dos benefícios.       | Objeto        | [RF21](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/)                                  | [Dylan](https://github.com/dylancavalcante)                                   |

<p align="center"><strong>Fontes:</strong> <a href="https://github.com/leticialopes20">Letícia</a>, <a href="https://github.com/dylancavalcante">Dylan</a>, <a href="https://github.com/BrenoLTeixeira">Breno</a>,<a href="https://github.com/arthurfernandesj">Arthur Fernandes</a>, <a href="https://github.com/eduardar0">Eduarda</a>, <a href="https://github.com/GiovanaFontesS">Giovana</a>, 2025</p>




<div align="center">
<font size="3"><p style="text-align: center"></p></font>

</div>
## Verbos

Os léxicos do tipo verbo representam ações ou operações que os Jovens Beneficiários podem executar dentro do aplicativo "ID Jovem". Essas ações detalham as funcionalidades acessíveis para os Jovens Beneficiários, permitindo interações específicas e operações dentro do aplicativo. Na Tabela 3, é possível conferir os principais léxicos classificados como verbos que foram identificados no ID Jovem. Esses léxicos incluem ações como "Cadastrar" e "Autenticar", cada uma descrevendo uma interação essencial que os Jovens Beneficiários podem realizar. Além disso, esses léxicos ajudam a definir os fluxos de uso do aplicativo, orientando os Jovens Beneficiários em suas tarefas e melhorando a experiência de navegação e uso dos serviços disponíveis.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 3:</b> Léxicos classificados como Verbos</p></font>
</div>

| Léxico | Sinônimo | Noção | Impacto | Classificação | Rastreabilidade | Fonte |
|--------|----------|-------|---------|---------------|-----------------|-------|
| L13 - Cadastrar | Registrar, Incluir | Ação de criar um novo cadastro no sistema ID Jovem | Permite que o Jovem Beneficiário tenha acesso aos benefícios e serviços do programa | Verbo | [RF01](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/) | [Eduarda](https://github.com/eduardar0) |
| L14 - Autenticar | Logar, Acessar | Processo de verificação de identidade via Gov.br | Permite o acesso seguro às funcionalidades do aplicativo ID Jovem | Verbo | [RF02](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/) | [Eduarda](https://github.com/eduardar0) |
| L15 - Emitir | Gerar, Produzir, Criar, Disponibilizar | Ação de criar e disponibilizar a carteira digital ID Jovem para o beneficiário após validação dos dados. | Permite que o Jovem Beneficiário tenha acesso à sua carteirinha digital, garantindo o uso dos benefícios do programa. | Verbo | [RF03](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/) | [Giovana](https://github.com/GiovanaFontesS)  |
| L16 - Compartilhar | Enviar, Exportar | Ação de enviar ou disponibilizar a carteira digital ID Jovem em PDF ou imagem para terceiros. | Permite que o Jovem Beneficiário compartilhe sua carteirinha de forma segura, mantendo a validade do benefício e o controle sobre seus dados. | Verbo | [RF17, RFN05](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/) | Arthur |
| L17 - Atualizar| Editar, Modificar | Ação que permite ao Jovem Beneficiário alterar informações pessoais ou preferências cadastradas. |Garante que os dados do jovem beneficiário permaneçam corretos e sincronizados com o CadÚnico, evitando inconsistências.  | Verbo | [RF19](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/) | [Dylan](https://github.com/dylancavalcante) |
| L18 - Consultar | Pesquisar, Verificar, Visualizar | Ação de buscar informações sobre benefícios, parceiros ou o histórico de uso da carteira. | Exibe ao Jovem Beneficiário as informações solicitadas, permitindo-lhe planejar o uso de seus direitos e acompanhar seu uso. | Verbo | [RF04](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/), [RF10](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/), [RF12](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/) | [Breno](https://github.com/BrenoLteixeira) |
| L19 - Favoritar| Salvar, Marcar |Ação de adicionar eventos ou estabelecimentos à lista de favoritos do usuário.  | Permite ao Jovem Beneficiário acessar rapidamente locais e eventos de seu interesse, melhorando a navegação e personalização do aplicativo. | Verbo | [RF24](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/) | [Leticia](https://github.com/leticialopes20)  |
| L20 - Denunciar | Reportar, Reclamar |Ação de enviar um relato sobre estabelecimentos ou parceiros que negaram o uso do benefício.  |Gera feedback para os administradores e promove o cumprimento adequado dos direitos do Jovem Beneficiário.  | Verbo | [RF20](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/) | [Leticia](https://github.com/leticialopes20)  |


<p align="center"><strong>Fontes:</strong> <a href="https://github.com/leticialopes20">Letícia</a>, <a href="https://github.com/dylancavalcante">Dylan</a>, <a href="https://github.com/BrenoLTeixeira">Breno</a>,<a href="https://github.com/arthurfernandesj">Arthur Fernandes</a>, <a href="https://github.com/eduardar0">Eduarda</a>, <a href="https://github.com/GiovanaFontesS">Giovana</a>, 2025</p>

## Estados

Os léxicos do tipo estado referem-se às condições, situações ou configurações específicas que podem ocorrer dentro do aplicativo "ID Jovem". Esses estados representam diversos cenários em que o Jovem Beneficiário ou o sistema pode se encontrar durante a interação com o aplicativo. Na Tabela 4, é possível verificar os principais léxicos classificados como estados que foram identificados no ID Jovem. Esses léxicos incluem estados como "Elegível", "Ativo" e "Vencido", cada um descrevendo uma condição específica que afeta as ações subsequentes e as opções disponíveis para o Jovem Beneficiário. A compreensão desses estados é essencial para navegar eficientemente pelo aplicativo e utilizar suas funcionalidades de forma eficaz.

<div align="center">
<font size="3"><p style="text-align: center"><b> Tabela 4: </b>Léxicos classificados como Estados</p></font>
</div>

| Léxico | Sinônimo | Noção | Impacto | Classificação | Rastreabilidade | Fonte |
|--------|----------|-------|---------|---------------|-----------------|-------|
| L21 - Elegível | Qualificado, Aptidão | Condição do Jovem Beneficiário que atende aos critérios do programa | Permite o acesso e utilização dos benefícios do ID Jovem | Estado | [RF15](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/) | [Eduarda](https://github.com/eduardar0) |
| L22 - Ativo | Válido, Vigente | Estado da carteira digital que está dentro do prazo de validade | Permite a utilização dos benefícios em estabelecimentos parceiros | Estado | [RF03](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/) | [Eduarda](https://github.com/eduardar0) |
| L23- Download Realizado | Salvo, Offline | Estado em que o Jovem Beneficiário possui a carteirinha disponível para uso offline  | Permite utilização do benefício sem conexão com a internet | Estado | [RF09](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/) | [Giovana](https://github.com/GiovanaFontesS) |
| L24 - Pendência | Alerta, Problema  | Condição do Jovem Beneficiário que indica que há algum problema ou ação necessária relacionada aos benefícios  | Bloqueia ou restringe temporariamente o acesso a determinados benefícios até que a situação seja resolvida  | Estado | [RF18, RF20](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/) | [Arthur](https://github.com/arthurfernandesj) |
| L25 - Sincronizado| Atualizado, Conectado |Estado em que os dados do Jovem Beneficiário estão alinhados com as informações do Gov.br e CadÚnico. | Garante o funcionamento correto dos serviços e a validade da carteira digital. | Estado | [RF07, RF16](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/) | [Dylan](https://github.com/dylancavalcante)  |
| L26 - Vencido | Expirado, Inválido | Estado da carteira digital após o término de seu prazo de validade. | Impede o Jovem Beneficiário de utilizar os benefícios e o instrui a realizar a renovação do cadastro. | Estado | [RF08](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/) | [Breno](https://github.com/brenolteixeira)|
| L27 - Em Análise |Pendente de Verificação, Em Processamento  | Estado em que os dados ou denúncias enviadas pelo Jovem Beneficiário estão sendo avaliadas pelo sistema ou equipe administrativa. | Impede ações adicionais até que a análise seja concluída, garantindo segurança e verificação de informações. | Estado | [RF27](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/) | [Leticia](https://github.com/leticialopes20)  |
| L28 - Personalizado |Configurado, Adaptado  |Estado do aplicativo após o usuário definir suas preferências pessoais e filtros de eventos.  | Melhora a experiência de uso, exibindo conteúdos e benefícios conforme os interesses do Jovem Beneficiário. | Estado | [RF28](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/) | [Leticia](https://github.com/leticialopes20)  |


<p align="center"><strong>Fontes:</strong> <a href="https://github.com/leticialopes20">Letícia</a>, <a href="https://github.com/dylancavalcante">Dylan</a>, <a href="https://github.com/BrenoLTeixeira">Breno</a>,<a href="https://github.com/arthurfernandesj">Arthur Fernandes</a>, <a href="https://github.com/eduardar0">Eduarda</a>, <a href="https://github.com/GiovanaFontesS">Giovana</a>, 2025</p>

# Ligações entre Léxicos


<div align="center"> <font size="3"><p style="text-align: center"><b>Tabela 5:</b> Ligações entre Léxicos do ID Jovem</p></font> </div>

| Léxico | Ligações Diretas | Tipo de Ligação |
|--------|------------------|----------------|
| L01 - Jovem Beneficiário | L13 - Cadastrar, L14 - Autenticar, L21 - Elegível, L22 - Ativo | Objeto-Verbo, Objeto-Estado |
| L02 - Carteira Digital | L15 - Emitir, L16 - Compartilhar, L22 - Ativo, L26 - Vencido | Objeto-Verbo, Objeto-Estado |
| L03 - Cadastro | L13 - Cadastrar, L17 - Atualizar, L21 - Elegível | Objeto-Verbo, Objeto-Estado |
| L04 - Elegibilidade | L21 - Elegível, L13 - Cadastrar, L15 - Emitir | Objeto-Estado, Objeto-Verbo |
| L05 - Transporte Gratuito | L18 - Consultar, L07 - Benefício | Objeto-Verbo, Objeto-Objeto |
| L06 - Estabelecimento Conveniado | L18 - Consultar, L19 - Favoritar, L20 - Denunciar | Objeto-Verbo |
| L07 - Benefício | L18 - Consultar, L05 - Transporte Gratuito, L08 - Parceiro | Objeto-Verbo, Objeto-Objeto |
| L08 - Parceiro | L18 - Consultar, L19 - Favoritar, L20 - Denunciar | Objeto-Verbo |
| L09 - FAQ e Suporte | L18 - Consultar | Objeto-Verbo |
| L10 - Agenda de Eventos | L18 - Consultar, L19 - Favoritar | Objeto-Verbo |
| L11 - Notificação | L26 - Vencido, L25 - Sincronizado | Objeto-Estado |
| L12 - Mapa Interativo | L18 - Consultar, L08 - Parceiro | Objeto-Verbo, Objeto-Objeto |
| L13 - Cadastrar | L01 - Jovem Beneficiário, L03 - Cadastro, L21 - Elegível | Verbo-Objeto, Verbo-Estado |
| L14 - Autenticar | L01 - Jovem Beneficiário, L25 - Sincronizado | Verbo-Objeto, Verbo-Estado |
| L15 - Emitir | L02 - Carteira Digital, L04 - Elegibilidade, L21 - Elegível | Verbo-Objeto, Verbo-Estado |
| L16 - Compartilhar | L02 - Carteira Digital | Verbo-Objeto |
| L17 - Atualizar | L03 - Cadastro, L25 - Sincronizado | Verbo-Objeto, Verbo-Estado |
| L18 - Consultar | L07 - Benefício, L08 - Parceiro, L10 - Agenda de Eventos, L12 - Mapa Interativo | Verbo-Objeto |
| L19 - Favoritar | L06 - Estabelecimento Conveniado, L08 - Parceiro, L10 - Agenda de Eventos | Verbo-Objeto |
| L20 - Denunciar | L06 - Estabelecimento Conveniado, L08 - Parceiro, L27 - Em Análise | Verbo-Objeto, Verbo-Estado |
| L21 - Elegível | L01 - Jovem Beneficiário, L03 - Cadastro, L04 - Elegibilidade, L15 - Emitir | Estado-Objeto, Estado-Verbo |
| L22 - Ativo | L01 - Jovem Beneficiário, L02 - Carteira Digital | Estado-Objeto |
| L23 - Download Realizado | L02 - Carteira Digital, L16 - Compartilhar | Estado-Objeto, Estado-Verbo |
| L24 - Pendência | L01 - Jovem Beneficiário, L17 - Atualizar | Estado-Objeto, Estado-Verbo |
| L25 - Sincronizado | L14 - Autenticar, L17 - Atualizar, L11 - Notificação | Estado-Verbo, Estado-Objeto |
| L26 - Vencido | L02 - Carteira Digital, L11 - Notificação | Estado-Objeto |
| L27 - Em Análise | L20 - Denunciar, L28 - Personalizado | Estado-Verbo, Estado-Estado |
| L28 - Personalizado | L19 - Favoritar, L27 - Em Análise | Estado-Verbo, Estado-Estado |


<p align="center"><strong>Fontes:</strong> <a href="https://github.com/leticialopes20">Letícia</a>, <a href="https://github.com/dylancavalcante">Dylan</a>, <a href="https://github.com/BrenoLTeixeira">Breno</a>,<a href="https://github.com/arthurfernandesj">Arthur Fernandes</a>, <a href="https://github.com/eduardar0">Eduarda</a>, <a href="https://github.com/GiovanaFontesS">Giovana</a>, 2025</p>


## Referência bibliográfica
> <a id="QT1" href="#anchor_1">1.</a> SERRANO, Milene. Requisitos - Aula 10. Local: UnB-FGA, Gama, DF. Apresentação de Power Point. 35, color. Disponível em: [Requisitos - Aula 10](https://aprender3.unb.br/pluginfile.php/3210627/mod_resource/content/1/Aula%2010.pdf). Página 19. Acesso em: 11 de Outubro de 2025.

## Bibliografia

> SERRANO, Milene. Requisitos - Aula 10. Local: UnB-FGA, Gama, DF. Apresentação de Power Point. 35, color. Disponível em: [Requisitos - Aula 10](https://aprender3.unb.br/pluginfile.php/3210627/mod_resource/content/1/Aula%2010.pdf). Acesso em: 11 de Outubro de 2025.
>


## Histórico de Versão

| Versão |    Data    |       Descrição      |                                          Autor(es)                                         |                  Revisor(es)                  |
| :----: | :--------: | :------------------: | :----------------------------------------------------------------------------------------: | :-------------------------------------------: |
|  `1.0` | 09/10/2025 | Criação do documento | [Dylan](https://github.com/dylancavalcante) | [Arthur](https://github.com/arthurfernandesj) |
|  `1.1` | 10/10/2025 | Conteúdo introdutório | [Giovana](https://github.com/GiovanaFontesS) |  [Dylan](https://github.com/dylancavalcante) |
|  `1.2` | 11/10/2025 | Criação das tabelas de: Objetos, verbos e Estados | [Eduarda](https://github.com/eduardar0) |  [Giovana](https://github.com/GiovanaFontesS) |
|  `1.3` | 11/10/2025 | Fix: tabela quebrada | [Eduarda](https://github.com/eduardar0) | [Dylan](https://github.com/dylancavalcante) |
|  `1.4` | 11/10/2025 | Correção da bibliografia/referencia bibliográfica | [Eduarda](https://github.com/eduardar0) | [Dylan](https://github.com/dylancavalcante) |
|  `1.5` | 11/10/2025 | Adicionado L01, L02, L013, L14, L21, L22 | [Eduarda](https://github.com/eduardar0) | [Giovana](https://github.com/GiovanaFontesS) |
|  `1.6` | 12/10/2025 | Adicionado L07, L08, L018, L26| [Breno](https://github.com/brenolteixeira) | [Eduarda](https://github.com/Eduarar0) |
|  `1.7` | 12/10/2025 | Adicionado L04, L05, L16, L24| [Arthur](https://github.com/arthurfernandesj) | [Eduarda](https://github.com/Eduarar0)|
|  `1.8` | 12/10/2025 | Adicionado L11, L12, L15, L17, L25| [Dylan](https://github.com/dylancavalcante) | [Eduarda](https://github.com/Eduarar0)|
|  `1.9` | 12/10/2025 | Adicionado L09, L10, L19, L20, L27 e L28| [Leticia](https://github.com/leticialopes20) | [Eduarda](https://github.com/Eduarar0)|
|  `2.0` | 12/10/2025 | Adicionado tabela de ligação entre lexicos| [Eduarda](https://github.com/Eduarar0) | [Dylan](https://github.com/dylancavalcante)|
|  `2.1` | 12/10/2025 | Arrumando links das tabelas e do documento| [Leticia](https://github.com/leticialopes20) | [Dylan](https://github.com/dylancavalcante)|