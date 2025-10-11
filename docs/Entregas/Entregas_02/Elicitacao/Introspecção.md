# Introspecção

## Introdução

A introspecção é uma técnica de elicitação de requisitos que consiste em, por meio de uma análise pessoal e profunda, levantar o que é indispensável para um software, neste caso, o aplicativo **ID Jovem**. Embora seja um método subjetivo, ele se insere no contexto mais amplo da **Engenharia de Requisitos**, disciplina que estabelece os processos para garantir que um software atenda às suas metas de negócio e às necessidades de seus usuários<a id="anchor_5" href="#QT4">[4]</a>. Sendo assim, o responsável por realizar essa estratégia imagina uma situação hipotética na qual utilizaria o sistema para realizar determinadas tarefas, derivando daí suas funcionalidades e características essenciais. Isso posto, os requisitos elicitados a partir deste exercício estão demonstrados na **Tabela de Requisitos** a seguir.

## Metodologia

O processo de introspecção foi realizado a partir da perspectiva de um usuário do programa **ID Jovem**. A partir de uma análise individual e da simulação de cenários de uso, os requisitos foram levantados e, em seguida, integrados e categorizados na **Tabela de Requisitos**. As categorias utilizadas para a organização foram: Requisitos Funcionais (RF), Não-Funcionais (RNF), de Interface (RI), além de Riscos (RR) e Testes (RT) associados ao projeto.

## Estudo de Caso: O Programa ID Jovem como Ferramenta de Execução de Requisitos Pessoais

A relação entre a introspecção e a capacidade de aproveitar oportunidades pode ser claramente ilustrada através da análise do programa Identidade Jovem (ID Jovem) do Governo Federal.

### A Introspecção

Usar o aplicativo ID Jovem, por si só, não define os objetivos de um jovem; ele funciona como um habilitador, uma ferramenta que remove barreiras para a execução de metas previamente definidas. Na terminologia da engenharia de software, o ID Jovem não fornece os *requisitos funcionais* (o "o quê" fazer), mas aborda um *requisito não funcional* crítico e quase universal para este público: a necessidade de baixo custo. Ele atua como um solucionador de restrições. A sua utilidade, portanto, é diretamente proporcional ao nível de autoconhecimento e planejamento do beneficiário. Um jovem que realizou um processo de introspecção e definiu seus "requisitos" pessoais consegue transformar o ID Jovem de um simples benefício em uma poderosa ferramenta estratégica. Por exemplo, um requisito pessoal como "preciso participar de uma conferência nacional de tecnologia em outro estado para expandir minha rede profissional" enfrenta uma restrição comum de "o custo da viagem é proibitivo". O ID Jovem, ao oferecer transporte interestadual gratuito ou com desconto, resolve diretamente esta restrição, tornando o requisito exequível<a id="anchor_1" href="#QT1">[1]</a><a id="anchor_2" href="#QT3">[3]</a>.

### Cenários de Aplicação Prática

Para ilustrar essa dinâmica, considere dois cenários contrastantes:

* **Cenário 1 (Uso Estratégico):** Ana, uma jovem de 20 anos, realizou um profundo processo de introspecção e definiu como requisito de carreira tornar-se jornalista cultural. Ela utiliza seu ID Jovem de forma estratégica: viaja para capitais vizinhas para cobrir festivais de cinema e entrevistar artistas, pagando meia-entrada nos eventos e utilizando as vagas gratuitas no transporte interestadual. Para Ana, o ID Jovem é uma ferramenta que viabiliza diretamente a execução de seu plano de carreira, permitindo-lhe construir um portfólio rico e uma rede de contatos valiosa com um custo mínimo.

* **Cenário 2 (Uso Inerte):** Lucas, de 22 anos, também possui o ID Jovem. No entanto, ele não dedicou tempo à introspecção e possui apenas desejos vagos, sem metas concretas ou priorizadas. Ele sabe que tem direito a descontos e viagens, mas como não definiu nenhum "projeto" ou "requisito" para si mesmo — como visitar um museu específico, participar de um workshop em outra cidade ou assistir a uma peça de teatro que enriqueceria sua formação —, o benefício permanece inerte em sua carteira digital. A oportunidade existe, mas sem o trabalho prévio de engenharia de requisitos pessoais, seu potencial permanece completamente inexplorado.

## Introspecção de Requisitos para o aplicativo ID Jovem

Para materializar a conexão entre a introspecção e a engenharia de software, podemos esboçar uma análise de requisitos para um sistema hipotético focado no ID Jovem. Este exercício prático demonstra como as necessidades dos usuários (os jovens) e as regras do programa (o domínio do problema) são traduzidas em requisitos funcionais, não funcionais e outros artefatos que guiam o desenvolvimento de uma solução de software.

### Stakeholders
* **Jovens (15-29 anos, baixa renda):** Usuários finais que desejam emitir e utilizar os benefícios do ID Jovem de forma fácil e rápida.
* **Gestores de Programas Sociais (CRAS):** Profissionais que cadastram e atualizam os dados dos jovens no CadÚnico, a base para a concessão do benefício.
* **Empresas (Produtoras de eventos, companhias de transporte):** Entidades que precisam validar a autenticidade do documento ID Jovem para conceder os benefícios.
* **Governo Federal (Secretaria Nacional da Juventude):** Responsável pela gestão e divulgação do programa.

### Tabela de Requisitos
A tabela a seguir apresenta uma lista de requisitos de software levantados durante a introspecção do projeto ID Jovem. Cada requisito foi classificado em uma das cinco categorias:

* **RF:** Requisitos Funcionais - Descrevem o comportamento ou a funcionalidade que o software deve ter.
* **RNF:** Requisitos Não-Funcionais - Descrevem atributos de qualidade do software, como desempenho e segurança.
* **RI:** Requisitos de Interface - Descrevem as características da interface do usuário.
* **RR:** Riscos - Riscos associados ao desenvolvimento e uso do software.
* **RT:** Testes e Validações - Atividades necessárias para testar e validar o software.

| Identificação | Descrição | Categoria |
|---|---|---|
| IDJ01 | O sistema deve permitir que o jovem emita sua carteira ID Jovem virtual fornecendo NIS, nome completo, data de nascimento e nome da mãe<a id="anchor_3" href="#QT2">[2]</a>. | RF |
| IDJ02 | O sistema deve permitir que estabelecimentos comerciais e empresas de transporte validem a autenticidade de uma carteira ID Jovem.[9,11] | RF |
| IDJ03 | O sistema deve exibir claramente os benefícios do programa, como meia-entrada e vagas em transporte interestadual [9,16]<a id="anchor_4" href="#QT3">[3]</a>. | RF |
| IDJ04 | O sistema deve fornecer uma seção de "Dúvidas Frequentes" para esclarecer questões sobre o programa, o CadÚnico e os benefícios[17]. | RF |
| IDJ05 | O sistema deve ser gratuito para o cidadão[8]. | RNF |
| IDJ06 | O sistema deve ser compatível com os principais sistemas operacionais móveis (Android e iOS) e navegadores web[10]. | RNF |
| IDJ07 | O sistema deve proteger os dados pessoais dos jovens (CPF, NIS) conforme as leis de proteção de dados vigentes. | RNF |
| IDJ08 | O sistema deve se conectar à base de dados do CadÚnico para verificar a elegibilidade do jovem em tempo real. | RNF |
| IDJ09 | A interface deve ser intuitiva e acessível para jovens de diferentes níveis de letramento digital[12,13]. | RI |
| IDJ10 | A carteira virtual gerada deve conter um QR Code ou outro método de validação rápida. | RI |
| IDJ11 | O sistema deve enviar notificações ao usuário sobre o vencimento de sua carteira ID Jovem. | RI |
| IDJ12 | Risco de o jovem não conseguir emitir a carteira devido a dados desatualizados no CadÚnico[9,18]. | RR |
| IDJ13 | Risco de indisponibilidade ou lentidão no serviço de consulta à base do CadÚnico, impedindo a emissão da carteira. | RR |
| IDJ14 | Risco de empresas se recusarem a aceitar o benefício, gerando frustração no usuário e descrédito do programa. | RR |
| IDJ15 | O processo de emissão deve ser testado com diferentes perfis de jovens (NIS válido, NIS inválido, cadastro desatualizado). | RT |
| IDJ16 | O fluxo de validação da carteira deve ser testado a partir da perspectiva de um estabelecimento comercial. | RT |
| IDJ17 | Testes de usabilidade devem ser conduzidos com jovens na faixa etária de 15 a 29 anos para validar a clareza da interface. | RT |
<p style="text-align: center; font-size: 10pt;">Fonte: <a href="https://github.com/dylancavalcante">Dylan Cavalcante</a></p>

## Conclusão

A analogia entre a engenharia de requisitos de software e a jornada de autodesenvolvimento revela uma verdade fundamental: os processos disciplinados de elicitação, análise e validação são tão cruciais para a construção de uma vida com propósito quanto o são para a entrega de um software de sucesso. A ausência de um levantamento de requisitos pessoais claro e honesto leva a um "projeto de vida" que, mesmo que avance, pode não atender às necessidades mais profundas do seu único e principal *stakeholder*: o próprio indivíduo.

## Referências Bibliográficas

<p><a id="QT1" href="#anchor_1">1.</a> BRASIL. Governo Federal. <b>Programa Identidade Jovem</b>. Disponível em: <a href="https://idjovem.juventude.gov.br/">https://idjovem.juventude.gov.br/</a>. Acesso em: 28 set. 2025.</p>
<p><a id="QT2" href="#anchor_3">2.</a> BRASIL. Governo Federal. <b>Obter a Carteira de Identidade Jovem</b>. Disponível em: <a href="https://www.gov.br/pt-br/servicos/obter-a-carteira-de-identidade-jovem">https://www.gov.br/pt-br/servicos/obter-a-carteira-de-identidade-jovem</a>. Acesso em: 28 set. 2025.</p>
<p><a id="QT3" href="#anchor_2">3.</a> BRASIL. <b>Decreto nº 8.537, de 5 de outubro de 2015</b>. Regulamenta a Lei nº 12.852, de 5 de agosto de 2013, e a Lei nº 12.933, de 26 de dezembro de 2013, para dispor sobre o benefício do sistema de transporte coletivo interestadual. Disponível em: <a href="https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2015/decreto/d8537.htm">https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2015/decreto/d8537.htm</a>. Acesso em: 28 set. 2025.</p>
<p><a id="QT4" href="#anchor_5">4.</a> VAZQUEZ, Carlos Eduardo; SIMÕES, Guilherme Siqueira. <b>Engenharia de Requisitos: Software Orientado ao Negócio</b>. Rio de Janeiro: Brasport, 2016.</p>

## Bibliografia

> UBES. **ID Jovem**. Disponível em: <https://www.ubes.org.br/2019/id-jovem/>. Acesso em: 28 set. 2025.

## Histórico de Versão

| Versão |    Data    |      Descrição       |                        Autor(es)                        |                       Revisor(es)                       |
| :----: | :--------: | :------------------: | :-----------------------------------------------------: | :-----------------------------------------------------: |
| `1.0`  | 28/09/2025 | Criação do documento | [Dylan](https://github.com/dylancavalcante)| [Arthur](https://github.com/arthurfernandesj) |
| `1.1`  | 10/10/2025 | Adição da Introdução e metodologia | [Breno Teixeira](https://github.com/BrenoLTeixeira)| [Arthur](https://github.com/arthurfernandesj) |
| `1.2`  | 10/10/2025 | Arrumando as Referências | [Breno Teixeira](https://github.com/BrenoLTeixeira)| [Arthur](https://github.com/arthurfernandesj) |