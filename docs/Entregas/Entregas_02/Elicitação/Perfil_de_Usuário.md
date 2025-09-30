# Análise de Perfil de Usuário 


## 1. Caracterização do Usuário-Alvo do ID Jovem
A primeira etapa da Engenharia de Requisitos é a compreensão aprofundada das partes interessadas (*stakeholders*) e do seu contexto.[[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)
 Para o aplicativo ID Jovem, esta etapa envolve a construção de uma persona detalhada do usuário-alvo, sintetizando a definição oficial do programa com os dados empíricos coletados. O resultado é um perfil que transcende a simples demografia, revelando as motivações e as circunstâncias que moldam a interação do usuário com o software.

### 1.1. Perfil Demográfico e Socioeconômico
A análise de documentos oficiais estabelece que o público-alvo do programa ID Jovem é composto por "jovens de baixa renda".[[2]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Analise_de_Documentos)
 Esta definição ampla é crucial, mas ganha contornos específicos e operacionais quando cruzada com os dados demográficos das entrevistas realizadas.[[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)
 As entrevistadas, Mariane Ruas de Oliveira (22 anos) e Noemy da Luz Cardoso (21 anos), são ambas estudantes universitárias cursando o ensino superior.[[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)


Este dado empírico permite refinar a persona do usuário-alvo. Não se trata de um jovem de baixa renda genérico, mas de um arquétipo específico: o jovem adulto que, apesar das restrições financeiras, está ativamente engajado em um processo de mobilidade social e qualificação profissional por meio da educação superior. Este contexto é fundamental, pois define um usuário com um conjunto particular de necessidades, habilidades e limitações. São indivíduos com alta familiaridade com o ambiente digital, mas cujo tempo e recursos financeiros são extremamente escassos e valiosos. A Tabela 1.1 consolida este perfil, integrando as fontes oficiais e empíricas para criar uma visão unificada do usuário.

**Tabela 1.1: Perfil Demográfico e Socioeconômico Consolidado do Usuário ID Jovem**

| Atributo | Descrição Consolidada | Fonte(s) |
| :--- | :--- | :--- |
| **Faixa Etária** | 15 a 29 anos (definição oficial do programa). A amostra da entrevista (21-22 anos) situa o usuário na fase de jovem adulto. | [1, 1] |
| **Gênero** | A amostra da entrevista é exclusivamente feminina, sugerindo uma base de usuários potencialmente com maior representação deste gênero. | [[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)
 |
| **Nível de Escolaridade** | Ensino Superior Incompleto. Este dado da amostra indica um usuário em processo de formação acadêmica avançada. | [[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)
 |
| **Ocupação Principal** | Estudante. A principal atividade do usuário é a dedicação aos estudos, o que implica em restrições de tempo e, frequentemente, de renda. | [[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)
 |
| **Condição Socioeconômica** | Baixa Renda. Este é o critério fundamental para a elegibilidade no programa, definindo o contexto de escassez de recursos do usuário. | [[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)
 |

<p style="text-align: center; font-size: 10pt;">Fonte: <a href="https://github.com/dylancavalcante">Dylan Cavalcante</a></p>

### 1.2. Insights sobre o Contexto do Usuário
A combinação dos dados demográficos com as motivações de uso revela um perfil comportamental que pode ser caracterizado como o "Sobrevivente Pragmático". Este usuário é, por um lado, digitalmente competente, habituado a utilizar aplicativos para diversas finalidades, como a compra de ingressos online.[[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)
 Por outro lado, sua condição socioeconômica o torna extremamente sensível ao custo-benefício de qualquer interação.

A principal motivação para o uso do ID Jovem é puramente econômica. Mariane afirma que seu objetivo é "economizar e conseguir lazer com um valor mais acessível", enquanto Noemy relata que começou a usar o programa porque atividades como viagens e cinema são "algo caro".[[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)
 Isso demonstra que o valor percebido do aplicativo está diretamente atrelado ao benefício financeiro que ele proporciona.

Adicionalmente, o contexto de estudante implica uma severa restrição de tempo. O comportamento de uso reflete essa realidade: as sessões no aplicativo são extremamente curtas e focadas na tarefa. Mariane relata passar "poucos minutos, só o tempo de acessar e gerar o documento digital", e Noemy estima o tempo de uso em "uns 5 minutos, apenas para fazer login e pegar as informações necessárias".[[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)
 O usuário não navega ou explora o aplicativo; ele o utiliza como uma ferramenta para executar uma transação específica e obter um resultado imediato.

Portanto, o "Sobrevivente Pragmático" engaja com o aplicativo sob uma condição implícita: o valor econômico do benefício obtido deve superar, de forma clara e imediata, o custo em tempo e esforço cognitivo para acessá-lo. Este perfil de usuário possui baixa tolerância a processos de login complicados, interfaces confusas ou qualquer outra forma de fricção que atrase a conclusão de seu objetivo. Este entendimento é vital para a priorização de requisitos não funcionais, como desempenho e, principalmente, usabilidade.

## 2. Análise de Objetivos, Motivações e Comportamento de Uso
A elicitação de requisitos, conforme a teoria, busca desvendar as "necessidades das partes interessadas" para traduzi-las em requisitos de solução.[[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)
 Nesta seção, a análise aprofunda-se no "porquê" da interação do usuário com o ID Jovem, contrastando os objetivos oficiais do programa com as motivações reais e os padrões de comportamento observados nas entrevistas.

### 2.1. Objetivos Primários: Acesso a Lazer e Economia
A análise das entrevistas revela, de forma inequívoca, que o objetivo primário do usuário é transacional: utilizar o aplicativo como um meio para acessar benefícios econômicos em atividades de lazer e cultura. O discurso das usuárias é consistentemente focado em resultados tangíveis. Mariane busca "acesso a passagens de ônibus interestadual com desconto e ingressos de cinema com meia-entrada".[[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)
 De forma similar, Noemy utiliza o programa para ter "mais acesso ao lazer", citando especificamente "viagens e cinema".[[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)


Esta perspectiva pragmática do usuário contrasta com a linguagem mais ampla e social dos documentos oficiais, que enquadram o ID Jovem como uma iniciativa para "facilitar o acesso de jovens a direitos e benefícios sociais e culturais".[[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)
 Enquanto a política pública visa a promoção de direitos, o usuário final percebe e utiliza o programa como um cartão de descontos. Esta diferença de percepção é crucial: para o usuário, o sucesso do aplicativo não é medido pela promoção de um direito abstrato, mas pela eficácia com que ele consegue comprar um ingresso de cinema mais barato ou obter uma passagem de ônibus gratuita.

### 2.2. Padrões de Comportamento: Uso Utilitário e Infrequente
O comportamento de uso do aplicativo ID Jovem reforça sua natureza puramente utilitária, em oposição a uma plataforma de engajamento contínuo.

*   **Frequência de Uso:** A interação com o aplicativo é esporádica e motivada por eventos específicos. Noemy, uma usuária de longa data, relata uma frequência de uso de, "em média, uma vez a cada dois meses, geralmente para ir ao cinema".[[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)
 Mariane, por ser uma usuária recente, ainda não possui um padrão estabelecido, mas seu uso também está atrelado a eventos pontuais, como a compra de ingressos.[[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)

*   **Duração da Sessão:** As sessões são notavelmente breves, durando apenas o tempo necessário para completar a tarefa de gerar ou apresentar a identidade digital. As estimativas variam de "poucos minutos" a "uns 5 minutos".[[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)
 Este padrão indica que os usuários não exploram funcionalidades secundárias; eles seguem um caminho direto para o objetivo principal.
*   **Benefícios Prioritários:** Há uma clara concentração no uso de benefícios específicos. Tanto a análise documental quanto as entrevistas apontam consistentemente para o acesso a eventos culturais (principalmente cinema) e ao transporte interestadual como os principais vetores de valor do programa.[1, 1]

A Tabela 2.1 sintetiza esses padrões, mapeando os benefícios mais valorizados com a frequência de uso e as justificativas apresentadas pelas usuárias.

**Tabela 2.1: Padrões de Uso e Benefícios Prioritários**

| Benefício Prioritário | Frequência de Uso (Amostra) | Importância Percebida (Justificativa do Usuário) | Fonte(s) |
| :--- | :--- | :--- | :--- |
| **Cinema (Meia-entrada)** | Baixa (e.g., bimestral) | Alta. Citado como um dos principais usos e motivações para adesão ao programa, por ser uma atividade de lazer considerada cara. | [[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)
 |
| **Transporte Interestadual** | Baixa (dependente de necessidade de viagem) | Alta. Percebido como um benefício de grande valor econômico, sendo um dos principais objetivos de uso. | [[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)
 |

<p style="text-align: center; font-size: 10pt;">Fonte: <a href="https://github.com/dylancavalcante">Dylan Cavalcante</a></p>

### 2.3. Insights sobre a Percepção do Produto
A análise aprofundada do comportamento e do discurso dos usuários revela uma percepção fundamental: o aplicativo ID Jovem é visto primariamente como uma "credencial digital", e não como uma plataforma de serviços. Esta distinção no modelo mental do usuário tem implicações profundas para a estratégia do produto.

O padrão de uso — abrir o aplicativo, gerar o documento e fechar — indica que a função central é a prova de identidade e elegibilidade.[[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)
 A própria linguagem de Noemy reforça essa visão ao afirmar que "acaba utilizando mais a carteirinha do ID Jovem" do que o aplicativo em si, separando conceitualmente a credencial (o que ela precisa) da plataforma que a entrega (o meio para obtê-la).[[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)


As sugestões de melhoria corroboram essa percepção. As usuárias não solicitam novas funcionalidades interativas ou serviços adicionais dentro do aplicativo. Em vez disso, suas recomendações focam em otimizar o acesso e o suporte à credencial: simplificar o login para obter a carteira mais facilmente, melhorar a divulgação para que mais pessoas saibam da existência da credencial, e criar um canal de suporte para resolver problemas relacionados à credencial.[[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)


Este modelo mental de "credencial digital" explica por que funcionalidades mais amplas, como servir de "porta de entrada para outros programas sociais" — uma aspiração mencionada por Noemy, mas não uma funcionalidade que ela busca ativamente no app — têm baixo engajamento.[[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)
 A arquitetura da informação e a estratégia de funcionalidades futuras devem levar em conta que, para o usuário atual, qualquer recurso que não contribua diretamente para a geração, apresentação, validação ou divulgação da sua credencial será percebido como secundário ou irrelevante.

## 3. Identificação de Necessidades, Pontos de Dor e Oportunidades
A atividade de Análise de Requisitos envolve a identificação de problemas, inconsistências e omissões nas informações elicitadas, transformando-as em oportunidades de melhoria para a solução.[[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)
 Esta seção documenta os desafios e frustrações enfrentados pelos usuários do ID Jovem, utilizando suas próprias palavras para ilustrar os pontos de dor e, em seguida, recontextualizando-os como oportunidades estratégicas para a evolução do aplicativo.

### 3.1. Pontos de Dor na Experiência do Usuário (Pain Points)
A partir das entrevistas, quatro temas centrais de frustração emergiram, representando barreiras significativas para uma experiência de usuário fluida e satisfatória.[[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)


*   **Fricção de Usabilidade:** O ponto de dor mais imediato e técnico é a dificuldade de uso do aplicativo. Noemy é explícita ao afirmar que "O login é complicado, poderia ser simplificado".[[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)
 Este é um obstáculo crítico, pois ocorre no ponto de entrada do serviço, podendo levar à desistência antes mesmo que o usuário acesse o benefício. A percepção de Mariane, embora mais branda, aponta na mesma direção: mesmo que o aplicativo funcione, "a usabilidade poderia ser melhorada para facilitar o acesso".[[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)

*   **Lacuna de Conhecimento e Divulgação:** Um ponto de dor que transcende o aplicativo e afeta o programa como um todo é a falta de divulgação. Ambas as entrevistadas identificam isso como uma falha grave. Mariane sugere que "deve haver mais divulgação. Muitas pessoas não conhecem o programa e poderiam se beneficiar".[[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)
 Noemy ecoa essa percepção, afirmando que "muitos não sabem da existência do ID Jovem" e que o próprio aplicativo deveria "trazer mais informações".[[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)
 Esta lacuna limita o impacto potencial do programa, impedindo que muitos jovens elegíveis sequer saibam de sua existência.
*   **Vácuo de Suporte e Comunicação:** Quando encontram problemas ou têm dúvidas, os usuários não possuem um canal de suporte claro e acessível. A solução atual é recorrer a buscas genéricas na internet.[[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)
 A necessidade de um mecanismo de ajuda é uma demanda explícita de Noemy, que sugere a criação de "Um canal mais direto de comunicação entre os usuários e os responsáveis pelo aplicativo, para dúvidas e sugestões".[[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)
 A ausência desse canal gera frustração e deixa o usuário desamparado.
*   **Inconsistência na Aceitação (Histórico):** Noemy relata uma dificuldade significativa no passado, relacionada à aceitação do benefício por parte dos estabelecimentos: "No começo foi difícil, porque nem todos aceitavam, mesmo sendo meu direito. Tive que mostrar a lei em alguns lugares".[[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)
 Embora ela observe que a situação melhorou, este relato expõe uma vulnerabilidade do ecossistema do ID Jovem. O valor do aplicativo para o usuário depende criticamente da cooperação e do conhecimento de terceiros (empresas de transporte, cinemas, etc.), tornando a validação da carteira um ponto crítico do processo.

### 3.2. Oportunidades de Melhoria (Sugestões dos Usuários)
Os pontos de dor identificados não são apenas problemas, mas também um roteiro claro para a melhoria do produto, fornecido pelos próprios usuários. Cada frustração aponta para uma oportunidade de agregar valor e otimizar a experiência.

*   **Otimizar o Fluxo de Autenticação:** A queixa sobre o "login complicado" é uma oportunidade direta para redesenhar o processo de entrada no aplicativo, possivelmente explorando integrações com sistemas de identidade digital unificados, como a plataforma Gov.br, para reduzir a fricção.[[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)

*   **Ampliar o Alcance via Canais Digitais:** A falta de divulgação pode ser combatida utilizando os canais que os próprios jovens indicam. As sugestões de usar redes sociais como "Instagram e TikTok, para alcançar mais jovens" são uma diretriz estratégica clara para as campanhas de comunicação do programa.[[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)

*   **Implementar um Canal de Suporte no Aplicativo:** A necessidade de um canal de comunicação direto pode ser transformada em uma nova funcionalidade, como um chat de suporte ou um sistema de tickets integrado ao aplicativo. Isso não apenas resolveria os problemas dos usuários, mas também forneceria uma fonte valiosa de feedback para a equipe de desenvolvimento.[[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)


## 4. Derivação de Requisitos a Partir do Perfil do Usuário
A etapa final e mais concreta da Análise de Requisitos é a tradução das necessidades, objetivos e pontos de dor do usuário em um conjunto estruturado de Requisitos de Solução.[[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)
 Esta seção formaliza os achados das etapas anteriores em Requisitos Funcionais (RF), que descrevem o que o sistema deve fazer, e Requisitos Não Funcionais (RNF), que definem os atributos de qualidade e as restrições sob as quais o sistema deve operar.[[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista) [[2]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Analise_de_Documentos)
 Cada requisito é explicitamente rastreado até sua fonte — seja a análise de documentos ou as entrevistas com usuários — para garantir que o desenvolvimento futuro esteja firmemente ancorado nas necessidades reais.

### Tabela 4.1: Requisitos Funcionais (RF) Elicitados e Derivados
Esta tabela consolida os requisitos funcionais identificados nos documentos e nas entrevistas, e adiciona novos requisitos derivados diretamente da análise dos pontos de dor e oportunidades. A coluna "Fonte/Justificativa" estabelece a rastreabilidade, um princípio chave da Gerência de Requisitos.[[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)


| ID | Descrição | Fonte/Justificativa |
| :--- | :--- | :--- |
| RF-CAD-01 | O sistema deve permitir o cadastro do usuário por meio do CPF. | Análise de Documentos.[[2]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Analise_de_Documentos) |
| RF-AUT-01 | O sistema deve fornecer mecanismos de autenticação e login para o usuário. | Análise de Documentos.[[2]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Analise_de_Documentos)|
| RF-EMI-01 | O sistema deve permitir a geração e emissão da carteira digital ID Jovem. | Análise de Documentos.[[2]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Analise_de_Documentos) |
| RF-BEN-01 | O sistema deve permitir a consulta de benefícios como transporte gratuito e acesso a eventos culturais e esportivos. | Entrevista [[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista) |
| RF-VAL-01 | O sistema deve permitir a validação da carteira por estabelecimentos conveniados. | Análise de Documentos.[[2]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Analise_de_Documentos) |
| RF-FAQ-01 | O sistema deve disponibilizar uma seção de perguntas frequentes (FAQ) e informações de atendimento. | Análise de Documentos.[[2]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Analise_de_Documentos) |
| **RF-SUP-01 (Derivado)** | O sistema deve prover um canal de comunicação direto (e.g., chat ou formulário de contato) para suporte ao usuário. | Entrevista (Noemy).[[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)|
| **RF-COM-01 (Derivado)** | O sistema deve apresentar uma seção de "Novidades e Divulgação" para informar sobre o programa, novos parceiros e benefícios. | Entrevista (Mariane, Noemy).[[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista) |

<p style="text-align: center; font-size: 10pt;">Fonte: <a href="https://github.com/dylancavalcante">Dylan Cavalcante</a></p>

### Tabela 4.2: Requisitos Não Funcionais (RNF) Elicitados e Derivados
Esta tabela detalha os atributos de qualidade essenciais para o sucesso do aplicativo, baseando-se nas expectativas e frustrações dos usuários. A categorização segue as classificações padrão da Engenharia de Requisitos, como Usabilidade, Desempenho e Segurança.[[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)


| ID | Categoria | Descrição | Fonte/Justificativa |
| :--- | :--- | :--- | :--- |
| RNF-USA-01 | **Usabilidade** | O processo de login deve ser simplificado e otimizado para minimizar o número de passos e a carga cognitiva do usuário. | Entrevista (Noemy).[[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista) |
| RNF-USA-02 | **Usabilidade** | A interface do aplicativo deve ser intuitiva, com navegação clara, textos legíveis e um design acessível, mesmo para jovens com pouca experiência digital. | Entrevista [[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista) |
| RNF-PER-01 | **Desempenho** | A geração e exibição do documento digital (carteira) devem ser concluídas em no máximo 5 segundos após a solicitação do usuário. | Entrevista.[[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista) |
| RNF-SEG-01 | **Segurança** | Os dados pessoais do usuário, especialmente o CPF, devem ser armazenados e transmitidos utilizando criptografia forte para garantir a proteção contra acessos não autorizados. | Análise de Documentos.[[2]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Analise_de_Documentos) |
| RNF-CON-01 | **Confiabilidade** | O aplicativo deve manter uma disponibilidade de serviço de 99.5%, garantindo que o usuário possa acessar sua identidade digital quando necessário. | Derivado do contexto de uso. A falha no acesso à credencial no momento da compra ou embarque invalida completamente o propósito do aplicativo. |
| RNF-POR-01 | **Portabilidade** | O aplicativo deve ser compatível e funcional nas duas versões mais recentes dos sistemas operacionais Android e iOS. | Análise de Documentos.[[2]](hhttps://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Analise_de_Documentos)|

<p style="text-align: center; font-size: 10pt;">Fonte: <a href="https://github.com/dylancavalcante">Dylan Cavalcante</a></p>

## 5. Tabela Resumo: Perfil Geral do Usuário

**Tabela 5.1: Síntese das Características Gerais do Perfil do Usuário**

| Categoria | Característica | Descrição | Fonte(s) |
| :--- | :--- | :--- | :--- |
| **Persona/Arquétipo** | Sobrevivente Pragmático | Jovem que utiliza o aplicativo de forma transacional para obter benefícios econômicos, com baixa tolerância a ineficiências. | [[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)|
| **Demografia** | Faixa Etária | 15-29 anos (oficial); 21-22 anos (amostra da entrevista). | [[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)|
| | Gênero | Feminino (amostra da entrevista). | [[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)|
| | Escolaridade | Ensino Superior Incompleto (amostra da entrevista). | [[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)|
| | Ocupação | Estudante. | [[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)|
| | Renda | Baixa Renda (critério de elegibilidade do programa). | [[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)|
| **Comportamento Digital** | Competência | Alta familiaridade com o ambiente digital; utiliza apps para compras online. | [[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)|
| | Padrão de Uso | Utilitário, infrequente (e.g., bimestral), com sessões curtas e focadas na tarefa (2-5 minutos). | [[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)|
| **Motivações** | Principal Motivação | Econômica: economizar e acessar atividades de lazer (cinema, viagens) consideradas caras. | [[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)|
| | Valor Percebido | O valor do aplicativo está diretamente ligado ao benefício financeiro tangível que ele proporciona. | [[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)|
| **Pontos de Dor** | Usabilidade | Dificuldade com o processo de login, percebido como "complicado". | [[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)|
| | Divulgação | Falta de conhecimento sobre a existência do programa entre o público-alvo. | [[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)|
| | Suporte | Ausência de um canal de comunicação direto para tirar dúvidas ou fazer sugestões. | [[1]](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista)|

<p style="text-align: center; font-size: 10pt;">Fonte: <a href="https://github.com/dylancavalcante">Dylan Cavalcante</a></p>

## 6. Conclusão: O Perfil do Usuário 
A análise detalhada das fontes documentais e das entrevistas com usuários permitiu construir um perfil robusto e acionável do usuário do aplicativo ID Jovem. Este perfil, quando utilizado como um guia estratégico, pode direcionar de forma eficaz os esforços futuros de desenvolvimento, garantindo que o produto evolua em alinhamento com as necessidades e o contexto de seus beneficiários.

### 6.1. Síntese do Perfil "Sobrevivente Pragmático"
O usuário do ID Jovem pode ser sintetizado na persona do "Sobrevivente Pragmático". Este perfil representa um jovem estudante, com alta competência digital, mas que opera sob severas restrições de tempo e dinheiro. Sua motivação para usar o aplicativo é singular e poderosa: o valor econômico direto. Ele não busca engajamento, comunidade ou funcionalidades complexas; ele busca um meio eficiente para obter um benefício tangível. A lealdade deste usuário não é com a marca ou com a missão abstrata do programa, mas com a eficácia transacional do aplicativo. Qualquer elemento que introduza fricção, complexidade ou perda de tempo atua como um forte desincentivo, ameaçando o abandono da ferramenta.

### 6.2. Recomendações Estratégicas
Com base neste perfil, três áreas de atuação emergem como prioritárias para a evolução do ID Jovem:

1.  **Prioridade 1: Reduzir a Fricção.** O foco imediato do desenvolvimento deve ser a otimização radical da usabilidade. Isso começa com a simplificação do fluxo de login (RNF-USA-01), o ponto de maior atrito identificado. Cada clique, cada segundo economizado na jornada do usuário para obter sua credencial digital reforça o valor do aplicativo e aumenta a probabilidade de uso e retenção. A experiência deve ser tão fluida e instantânea quanto possível.
2.  **Prioridade 2: Aumentar a Consciência (Awareness).** O sucesso do aplicativo está intrinsecamente ligado ao conhecimento do programa por parte dos jovens elegíveis e dos estabelecimentos parceiros. Uma estratégia de comunicação e marketing robusta, que utilize os canais sugeridos pelos próprios usuários — como as redes sociais Instagram e TikTok — é tão crucial quanto o desenvolvimento de novas funcionalidades (RF-COM-01). Sem divulgação, o melhor aplicativo do mundo não cumpre seu propósito.
3.  **Prioridade 3: Fechar o Loop de Feedback.** A implementação de um canal de suporte direto e acessível dentro do aplicativo (RF-SUP-01) é essencial. Esta funcionalidade atende a uma necessidade explícita dos usuários e cumpre três objetivos estratégicos: resolve problemas imediatos, evitando a frustração e o abandono; coleta feedback valioso que pode informar os próximos ciclos de desenvolvimento; e transforma os usuários de meros consumidores de benefícios em parceiros ativos na melhoria contínua do programa.

### 6.3. Considerações Finais
Para um programa com uma missão social tão importante como o ID Jovem, a aplicação rigorosa dos princípios da Engenharia de Requisitos e uma compreensão profunda e empática do usuário final não são apenas boas práticas de desenvolvimento de software. São, na verdade, condições fundamentais para o cumprimento dos objetivos centrais do programa: a promoção da inclusão, do acesso à cultura e da cidadania para a juventude brasileira. Negligenciar a experiência do usuário, neste contexto, é o equivalente a falhar na própria missão. A evolução do aplicativo ID Jovem deve ser guiada por uma premissa simples: servir ao "Sobrevivente Pragmático" de forma eficiente, confiável e sem atritos.

---
## Referências Bibliográficas


>< UNIVERSIDADE DE BRASÍLIA. Grupo 04 – Projeto de Requisitos de Software. **Relatório de Elicitação de Requisitos: Análise de Documentos – Identidade Jovem (ID Jovem)**. Brasília, 2025. Disponível em: [https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Analise_de_Documentos](https://requisitos-de-software.github.io/2025.>< 2-Grupo04/><Entregas/Entregas_02/Elicitação/Analise_de_Documentos). Acesso em: 28 set. 2025.

>< UNIVERSIDADE DE BRASÍLIA. Grupo 04 – Projeto de Requisitos de Software. **Relatório de Elicitação de Requisitos: Entrevista – Identidade Jovem (ID Jovem)**. Brasília, 2025. >< Disponível em: [https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitação/Entrevista](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas Entregas_02/><Elicitação/Entrevista). Acesso em: 28 set. 2025.

## Bibliografia 

>< VAZQUEZ, C. E.; SIMÕES, G. S. *Engenharia de Requisitos: software orientado ao negócio*. Rio de Janeiro: >< Brasport, 2016.

---
## Histórico de Versão

| Versão |    Data    |       Descrição      |                                          Autor(es)                                         |                  Revisor(es)                  |
| :----: | :--------: | :------------------: | :----------------------------------------------------------------------------------------: | :-------------------------------------------: |
|  `1.0` | 28/09/2025 | Criação do documento | [Dylan](https://github.com/dylancavalcante) e [Eduarda](https://github.com/eduardar0) | [Arthur](https://github.com/arthurfernandesj) |