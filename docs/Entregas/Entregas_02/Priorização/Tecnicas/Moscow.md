
# MoSCoW

## Introdução

O **MoSCoW** é uma técnica amplamente utilizada para **priorização de requisitos em projetos de software**. Sua simplicidade e objetividade permitem alinhar expectativas entre a equipe de desenvolvimento e os stakeholders, garantindo foco nos itens indispensáveis para o sucesso do sistema.

O método organiza os requisitos em quatro classificações (**M, S, C ou W**), proporcionando uma alternativa mais clara à tradicional divisão em níveis de prioridade (baixo, médio, alto). Essa abordagem é especialmente útil em sistemas como o **ID Jovem**, em que é necessário diferenciar o que é crítico (como validação de dados pessoais e emissão do benefício) do que pode ser adicionado posteriormente.

---

## Técnica MoSCoW

O MoSCoW divide os requisitos em quatro categorias:

-   **M – Must have (Tem que ter):** Requisitos críticos, indispensáveis para o funcionamento do sistema. Sem eles, o projeto não pode ser considerado bem-sucedido.
-   **S – Should have (Deveria ter):** Requisitos importantes, mas não essenciais na entrega inicial. Sua ausência não inviabiliza o sistema, mas pode impactar a experiência do usuário.
-   **C – Could have (Poderia ter):** Requisitos desejáveis que aumentam a satisfação do usuário, implementados apenas se houver tempo e recursos.
-   **W – Won’t have (Não terá):** Requisitos que, em comum acordo com os stakeholders, não serão implementados nesta versão, mas podem ser considerados em futuras releases.

⚠️ Apesar de prática, a técnica pode gerar dúvidas: quando se classifica um requisito como **Won’t**, significa que ele nunca será implementado ou apenas não estará presente na primeira versão? Por isso, recomenda-se que o MoSCoW seja complementado por outras técnicas de priorização.

---

## Metodologia de Aplicação

Para aplicar o MoSCoW ao **ID Jovem**, seguimos as etapas:

1.  **Levantamento:** Reunimos os requisitos obtidos pelas técnicas de elicitação.
2.  **Discussão:** Avaliamos em conjunto com os stakeholders a relevância de cada requisito.
3.  **Classificação:** Cada requisito foi categorizado em Must, Should, Could ou Won’t.
4.  **Validação:** A priorização foi revisada com todos os envolvidos.
5.  **Revisão contínua:** Considerando que o ID Jovem pode evoluir (novos serviços, integrações e legislações), os requisitos podem ser reavaliados a qualquer momento.

---

### Vantagens

-   Linguagem simples e acessível.
-   Facilita a participação de todos os stakeholders.
-   Define claramente o escopo mínimo viável (MVP).
-   Permite ajustes durante o andamento do projeto.
-   Ajuda a focar nos itens que realmente agregam valor imediato.

---

### Desvantagens

-   Pode ser simplista em contextos mais complexos.
-   Subjetividade na decisão das classificações.
-   Risco de influências políticas sobre critérios técnicos.
-   Necessidade de que os envolvidos conheçam bem o negócio para uma priorização eficaz.

---

## Priorização de Requisitos do ID Jovem com MoSCoW

A Tabela 1 apresenta a classificação dos requisitos do **ID Jovem**, considerando sua relevância para o sistema.

<font size="3"><p style="text-align: center">Tabela 1 – Priorização dos requisitos do ID Jovem com a técnica MoSCoW</p></font>

| Código | Descrição | Classificação | Justificativa |
| :--- | :--- | :--- | :--- |
| RNF-USA-01 | O processo de login deve ser simplificado e otimizado para minimizar o número de passos e a carga cognitiva do usuário. | S - Should have | O usuário indicou que "deveria ter" um processo de login simplificado. |
| RNF-USA-02 | A interface do aplicativo deve ser intuitiva, com navegação clara, textos legíveis e um design acessível, mesmo para jovens com pouca experiência digital. | M - Must have | O usuário considera que a interface intuitiva é algo que "tem que ter". |
| RNF-PER-01 | A geração e exibição do documento digital (carteira) devem ser concluídas em no máximo 5 segundos após a solicitação do usuário. | W - Won't have | O usuário indicou que era um desejo, mas não essencial. |
| RNF-SEG-01 | Os dados pessoais do usuário, especialmente o CPF, devem ser armazenados e transmitidos utilizando criptografia forte para garantir a proteção contra acessos não autorizados. | M - Must have | O usuário considera "muito importante" a segurança dos dados com criptografia. |
| RNF-CON-01 | O aplicativo deve manter uma disponibilidade de serviço de 99.5%, garantindo que o usuário possa acessar sua identidade digital quando necessário. | M - Must have | O usuário quer o aplicativo disponível a qualquer momento, concordando com a alta disponibilidade. |
| RNF-POR-01 | O aplicativo deve ser compatível e funcional nas duas versões mais recentes dos sistemas operacionais Android e iOS. | M - Must have | A compatibilidade é tratada como um requisito básico para o funcionamento. |
| RF-CAD-01 | O sistema deve permitir o cadastro do usuário por meio do CPF. | M - Must have | O cadastro é um requisito fundamental para o uso do sistema. |
| RF-AUT-01 | O sistema deve fornecer mecanismos de autenticação e login para o usuário. | S - Should have | Considerado importante, mas a simplificação é o foco principal. |
| RF-EMI-01 | O sistema deve permitir a geração e emissão da carteira digital ID Jovem. | M - Must have | A emissão da carteira é a função principal do aplicativo. |
| RF-BEN-01 | O sistema deve permitir a consulta de benefícios como transporte gratuito e acesso a eventos culturais e esportivos. | M - Must have | A consulta de benefícios é uma funcionalidade essencial destacada pelo usuário. |
| RF-VAL-01 | O sistema deve permitir a validação da carteira por estabelecimentos conveniados. | C - Could have | O usuário concorda com a validação, mas a considera a partir da perspectiva do estabelecimento. |
| RF-FAQ-01 | O sistema deve disponibilizar uma seção de perguntas frequentes (FAQ) e informações de atendimento. | M - Must have | O usuário considera "muito importante" a seção de dúvidas frequentes. |
| RF-SUP-01 | (Derivado) O sistema deve prover um canal de comunicação direto (e.g., chat ou formulário de contato) para suporte ao usuário. | S - Should have | Derivado da necessidade de esclarecer dúvidas, mas não explicitamente solicitado como "tem que ter". |
| RF-COM-01 | (Derivado) O sistema deve apresentar uma seção de "Novidades e Divulgação" para informar sobre o programa, novos parceiros e benefícios. | C - Could have | Seria um complemento interessante, mas não foi mencionado como essencial. |
| RF-BS-01 | O usuário deve realizar o login com o acesso unificado do gov.br. | S - Should have | A simplificação do login foi classificada como "deveria ter". |
| RF-BS-02 | O usuário deve aceitar um termo de uso em seu primeiro acesso ao aplicativo. | M - Must have | O aceite dos termos é um passo fundamental e obrigatório. |
| RF-BS-03 | O usuário deve conseguir consultar se está dentro dos critérios para ter direito ao ID Jovem. | M - Must have | É uma etapa essencial e pré-requisito para que o usuário possa emitir a carteira. |
| RF-BS-04 | O usuário deve poder emitir sua carteirinha digital do ID Jovem. | M - Must have | Esta é a função primária e o principal objetivo do aplicativo para o usuário. |
| RF-BS-05 | O usuário deve conseguir visualizar os benefícios disponíveis, como meia-entrada em eventos culturais. | M - Must have | O usuário demonstrou que a consulta de benefícios é uma das funcionalidades centrais. |
| RF-BS-06 | O usuário deve poder verificar a validade da sua carteirinha do ID Jovem. | S - Should have | Importante para a confiança do usuário no documento, mas secundário à sua emissão. |
| RF-BS-07 | O usuário deve ter acesso a um guia/tutorial explicativo sobre como utilizar o ID Jovem. | S - Should have | Apoia a exigência de uma interface intuitiva, facilitando o uso para pessoas com pouca experiência digital. |
| RF-BS-08 | O usuário deve ter acesso a perguntas frequentes (FAQ) e suporte para dúvidas. | M - Must have | O usuário classificou a seção de dúvidas frequentes como "muito importante". |
| RF-BS-09 | O aplicativo deve permitir atualização automática dos dados do beneficiário com base nas informações do CadÚnico. | S - Should have | Garante a integridade dos dados e a continuidade do benefício sem transtornos para o usuário. |
| RF-BS-10 | O usuário deve conseguir acessar informações sobre locais e serviços onde o ID Jovem é aceito. | S - Should have | Agrega grande valor prático ao benefício, embora a função principal seja a posse do documento. |
| RF-BS-11 | O aplicativo deve oferecer notificações sobre vencimento e renovação do benefício. | S - Should have | É um recurso de conveniência que melhora a experiência e evita que o usuário perca o benefício. |
| RF-BS-12 | O usuário deve poder compartilhar a carteirinha digital em PDF ou imagem para uso em estabelecimentos. | C - Could have | O usuário respondeu com um "Tá?", indicando que seria uma possibilidade, mas não essencial. |
| RF-BS-13 | O sistema deve validar em tempo real a autenticidade da carteirinha. | S - Should have | O usuário reconhece a importância da validação em tempo real. |
| RF-BS-14 | O aplicativo deve oferecer um processo de onboarding adaptado para usuários com diferentes níveis de familiaridade tecnológica. | C - Could have | Desejável para melhorar a experiência inicial, complementando a necessidade de uma interface intuitiva. |
| RNF-BS-01 | O aplicativo deve ser leve e compatível com diferentes modelos de smartphones, inclusive de baixo custo. | S - Should have | Garante que o aplicativo seja acessível para o público-alvo, que pode não possuir aparelhos de última geração. |
| RNF-BS-02 | O aplicativo deve ser intuitivo, com ícones e textos de fácil compreensão. | M - Must have | O usuário foi enfático ao afirmar que a interface intuitiva e clara "tem que ter". |
| RNF-BS-03 | O aplicativo deve enviar notificações sobre prazos e eventos próximos. | S - Should have | Aumenta o engajamento e o valor percebido do aplicativo, informando proativamente o usuário. |
| RNF-BS-04 | O aplicativo deve organizar os menus de forma clara e acessível para jovens com pouca experiência digital. | M - Must have | Requisito fundamental que deriva diretamente da necessidade de uma navegação clara e intuitiva. |
| RNF-BS-05 | O aplicativo deve garantir funcionamento offline para exibição da carteirinha já emitida. | C - Could have | Aumenta a confiabilidade, permitindo que o usuário acesse seu documento mesmo sem conexão com a internet. |
| RNF-BS-06 | O aplicativo deve oferecer recursos de acessibilidade (alto contraste, leitura de tela, comandos por voz). | C - Could have | Desejável para tornar o aplicativo inclusivo, alinhado às boas práticas de design acessível. |
| RNF-BS-07 | O sistema deve integrar-se com o CadÚnico e outros serviços digitais do governo. | M - Must have | É um requisito técnico indispensável; sem essa integração, o sistema não pode validar a elegibilidade do usuário. |
| RNF-BS-08 | O aplicativo deve proteger os dados dos usuários em conformidade com a LGPD, utilizando criptografia. | M - Must have | O usuário classificou a segurança e criptografia dos dados pessoais como "muito importante". |
| RNF-BS-09 | O aplicativo deve ser compatível com Android e iOS. | M - Must have | Essencial para garantir que a grande maioria do público-alvo possa acessar o serviço. |
| RNF-BS-10 | O aplicativo deve funcionar com baixo consumo de internet, garantindo acessibilidade a jovens em regiões carentes. | S - Should have | Importante para a inclusão de usuários com planos de dados limitados. |
| RNF-BS-11 | O aplicativo deve estar disponível em português e oferecer suporte básico em outros idiomas oficiais do Brasil (como Libras em vídeo). | W - Won't have | Considerado fora do escopo inicial para focar nas funcionalidades essenciais. |
| RF-INT-01 | O sistema deve permitir que o jovem emita sua carteira ID Jovem virtual fornecendo NIS, nome completo, data de nascimento e nome da mãe. | M - Must have | Define o fluxo principal para a obtenção do benefício, sendo um requisito fundamental. |
| RF-INT-02 | O sistema deve permitir que estabelecimentos comerciais e empresas de transporte validem a autenticidade de uma carteira ID Jovem. | M - Must have | Sem a validação, a carteira perde sua utilidade prática no mercado. |
| RF-INT-03 | O sistema deve exibir claramente os benefícios do programa, como meia-entrada e vagas em transporte interestadual. | M - Must have | O usuário confirmou ser uma função essencial do aplicativo. |
| RF-INT-04 | O sistema deve fornecer uma seção de "Dúvidas Frequentes" para esclarecer questões sobre o programa, o CadÚnico e os benefícios. | M - Must have | O usuário considerou esta seção como "muito importante" para o suporte. |
| RNF-INT-01 | O sistema deve ser gratuito para o cidadão. | M - Must have | Sendo um programa social do governo, a gratuidade é uma premissa básica e inegociável. |
| RNF-INT-02 | O sistema deve ser compatível com os principais sistemas operacionais móveis (Android e iOS) e navegadores web. | M - Must have | Requisito fundamental para garantir o amplo acesso ao serviço. |
| RNF-INT-03 | O sistema deve proteger os dados pessoais dos jovens (CPF, NIS) conforme as leis de proteção de dados vigentes. | M - Must have | A segurança dos dados foi classificada pelo usuário como de alta importância. |
| RNF-INT-04 | O sistema deve se conectar à base de dados do CadÚnico para verificar a elegibilidade do jovem em tempo real. | M - Must have | Requisito técnico essencial que viabiliza todo o funcionamento do programa. |
| RI-01 | A interface deve ser intuitiva e acessível para jovens de diferentes níveis de letramento digital. | M - Must have | O usuário reforçou que uma interface intuitiva "tem que ter", sendo um pilar para o sucesso do app. |
| RI-02 | A carteira virtual gerada deve conter um QR Code ou outro método de validação rápida. | S - Should have | O usuário considera "importante" que a carteira tenha um método de validação. |
| RI-03 | O sistema deve enviar notificações ao usuário sobre o vencimento de sua carteira ID Jovem. | S - Should have | Melhora a experiência do usuário, evitando a perda do benefício por esquecimento. |
| RR-01 | Risco de o jovem não conseguir emitir a carteira devido a dados desatualizados no CadÚnico. | M - Must have | Um risco que deve ser obrigatoriamente tratado para não inviabilizar o acesso ao benefício. |
| RR-02 | Risco de indisponibilidade ou lentidão no serviço de consulta à base do CadÚnico, impedindo a emissão da carteira. | M - Must have | Mitigação obrigatória para garantir a disponibilidade do serviço, conforme expectativa do usuário. |
| RR-03 | Risco de empresas se recusarem a aceitar o benefício, gerando frustração no usuário e descrédito do programa. | M - Must have | O tratamento deste risco é crucial para que o programa cumpra seu propósito e tenha credibilidade. |
| RT-01 | O processo de emissão deve ser testado com diferentes perfis de jovens (NIS válido, NIS inválido, cadastro desatualizado). | M - Must have | Teste essencial para garantir que a funcionalidade mais crítica do sistema opere corretamente. |
| RT-02 | O fluxo de validação da carteira deve ser testado a partir da perspectiva de um estabelecimento comercial. | S - Should have | O usuário concorda com a importância de testar a validação a partir da perspectiva do estabelecimento. |
| RT-03 | Testes de usabilidade devem ser conduzidos com jovens na faixa etária de 15 a 29 anos para validar a clareza da interface. | M - Must have | Necessário para validar o requisito "Must have" de uma interface intuitiva e acessível. |

<font size="3"><p style="text-align: center"> **Fontes:** [Arthur Fernandes](https://github.com/arthurfernandesj), [Dylan Cavalcante](https://github.com/dylancavalcante) & [Letícia Lopes](https://github.com/leticialopes20), 2025

---

## Gravação

<font size="3"><p style="text-align: center"> [![Assista à gravação](https://img.youtube.com/vi/dIxnYHoZO44/hqdefault.jpg)](https://youtu.be/dIxnYHoZO44)

<font size="3"><p style="text-align: center"> **Vídeo 1:** Técnica de Priorização - Moscow

<font size="3"><p style="text-align: center"> **Fontes:** [Giovana Fontes](https://github.com/GiovanaFontesS), 2025

## Referências Bibliográficas

> WIEGERS, Karl E. **Software Requirements**. 2. ed. Redmond, WA: Microsoft Press, 2003.

## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :---: | :---: | :---: | :---: | :---: |
| `1.0` | 28/09/2025 | Criação do documento com a descrição da técnica de priorização "MoSCoW" | [Danilo Melo](https://github.com/EngDann) | [ Arthur Fernandes](https://github.com/arthurfernandesj)|
| `1.1` | 29/09/2025 | Atualização da técnica de priorização "MoSCoW e tabela de priorização adicionada" | [Arthur Fernandes](https://github.com/arthurfernandesj) | [Letícia Lopes](https://github.com/leticialopes20) |
| `1.2` | 30/09/2025 | Atualização da tabela de priorização de requisitos | [Letícia Lopes](https://github.com/leticialopes20) | [Arthur Fernandes](https://github.com/arthurfernandesj)|
| `1.2` | 30/09/2025 | Atualização da tabela de priorização de requisitos | [Dylan Cavalcante](https://github.com/dylancavalcante) | [Giovana Fontes](https://github.com/GiovanaFontesS)|