# MoSCoW

## Introdução  

O **MoSCoW** é uma técnica amplamente utilizada para **priorização de requisitos em projetos de software**. Sua simplicidade e objetividade permitem alinhar expectativas entre a equipe de desenvolvimento e os stakeholders, garantindo foco nos itens indispensáveis para o sucesso do sistema.  

O método organiza os requisitos em quatro classificações (**M, S, C ou W**), proporcionando uma alternativa mais clara à tradicional divisão em níveis de prioridade (baixo, médio, alto). Essa abordagem é especialmente útil em sistemas como o **ID Jovem**, em que é necessário diferenciar o que é crítico (como validação de dados pessoais e emissão do benefício) do que pode ser adicionado posteriormente.  

---

## Técnica MoSCoW  

O MoSCoW divide os requisitos em quatro categorias:  

- **M – Must have (Tem que ter):** Requisitos críticos, indispensáveis para o funcionamento do sistema. Sem eles, o projeto não pode ser considerado bem-sucedido.  
- **S – Should have (Deveria ter):** Requisitos importantes, mas não essenciais na entrega inicial. Sua ausência não inviabiliza o sistema, mas pode impactar a experiência do usuário.  
- **C – Could have (Poderia ter):** Requisitos desejáveis que aumentam a satisfação do usuário, implementados apenas se houver tempo e recursos.  
- **W – Won’t have (Não terá):** Requisitos que, em comum acordo com os stakeholders, não serão implementados nesta versão, mas podem ser considerados em futuras releases.  

⚠️ Apesar de prática, a técnica pode gerar dúvidas: quando se classifica um requisito como **Won’t**, significa que ele nunca será implementado ou apenas não estará presente na primeira versão? Por isso, recomenda-se que o MoSCoW seja complementado por outras técnicas de priorização.  

---

## Metodologia de Aplicação  

Para aplicar o MoSCoW ao **ID Jovem**, seguimos as etapas:  

1. **Levantamento:** Reunimos os requisitos obtidos pelas técnicas de elicitação.  
2. **Discussão:** Avaliamos em conjunto com os stakeholders a relevância de cada requisito.  
3. **Classificação:** Cada requisito foi categorizado em Must, Should, Could ou Won’t.  
4. **Validação:** A priorização foi revisada com todos os envolvidos.  
5. **Revisão contínua:** Considerando que o ID Jovem pode evoluir (novos serviços, integrações e legislações), os requisitos podem ser reavaliados a qualquer momento.  

---

## Vantagens  

- Linguagem simples e acessível.  
- Facilita a participação de todos os stakeholders.  
- Define claramente o escopo mínimo viável (MVP).  
- Permite ajustes durante o andamento do projeto.  
- Ajuda a focar nos itens que realmente agregam valor imediato.  

---

## Desvantagens  

- Pode ser simplista em contextos mais complexos.  
- Subjetividade na decisão das classificações.  
- Risco de influências políticas sobre critérios técnicos.  
- Necessidade de que os envolvidos conheçam bem o negócio para uma priorização eficaz.  

---

## Priorização de Requisitos do ID Jovem com MoSCoW  

A Tabela 1 apresenta a classificação dos requisitos do **ID Jovem**, considerando sua relevância para o sistema.  

<font size="3"><p style="text-align: center">Tabela 1 – Priorização dos requisitos do ID Jovem com a técnica MoSCoW</p></font>

| Código      | Descrição                                                                                                                                       | Classificação | Justificativa |
|------------|-------------------------------------------------------------------------------------------------------------------------------------------------|---------------|---------------|
| RNF-USA-01 | O processo de login deve ser simplificado e otimizado para minimizar o número de passos e a carga cognitiva do usuário.                           |               |               |
| RNF-USA-02 | A interface do aplicativo deve ser intuitiva, com navegação clara, textos legíveis e um design acessível, mesmo para jovens com pouca experiência digital. |               |               |
| RNF-PER-01 | A geração e exibição do documento digital (carteira) devem ser concluídas em no máximo 5 segundos após a solicitação do usuário.                 |               |               |
| RNF-SEG-01 | Os dados pessoais do usuário, especialmente o CPF, devem ser armazenados e transmitidos utilizando criptografia forte para garantir a proteção contra acessos não autorizados. |               |               |
| RNF-CON-01 | O aplicativo deve manter uma disponibilidade de serviço de 99.5%, garantindo que o usuário possa acessar sua identidade digital quando necessário. |               |               |
| RNF-POR-01 | O aplicativo deve ser compatível e funcional nas duas versões mais recentes dos sistemas operacionais Android e iOS.                             |               |               |
| RF-CAD-01  | O sistema deve permitir o cadastro do usuário por meio do CPF.                                                                                   |               |               |
| RF-AUT-01  | O sistema deve fornecer mecanismos de autenticação e login para o usuário.                                                                       |               |               |
| RF-EMI-01  | O sistema deve permitir a geração e emissão da carteira digital ID Jovem.                                                                        |               |               |
| RF-BEN-01  | O sistema deve permitir a consulta de benefícios como transporte gratuito e acesso a eventos culturais e esportivos.                             |               |               |
| RF-VAL-01  | O sistema deve permitir a validação da carteira por estabelecimentos conveniados.                                                               |               |               |
| RF-FAQ-01  | O sistema deve disponibilizar uma seção de perguntas frequentes (FAQ) e informações de atendimento.                                             |               |               |
| RF-SUP-01  | (Derivado) O sistema deve prover um canal de comunicação direto (e.g., chat ou formulário de contato) para suporte ao usuário.                  |               |               |
| RF-COM-01  | (Derivado) O sistema deve apresentar uma seção de "Novidades e Divulgação" para informar sobre o programa, novos parceiros e benefícios.       |               |               |
| RF-BS-01   | O usuário deve realizar o login com o acesso unificado do gov.br.                                                                                |               |               |
| RF-BS-02   | O usuário deve aceitar um termo de uso em seu primeiro acesso ao aplicativo.                                                                     |               |               |
| RF-BS-03   | O usuário deve conseguir consultar se está dentro dos critérios para ter direito ao ID Jovem.                                                  |               |               |
| RF-BS-04   | O usuário deve poder emitir sua carteirinha digital do ID Jovem.                                                                                 |               |               |
| RF-BS-05   | O usuário deve conseguir visualizar os benefícios disponíveis, como meia-entrada em eventos culturais.                                          |               |               |
| RF-BS-06   | O usuário deve poder verificar a validade da sua carteirinha do ID Jovem.                                                                       |               |               |
| RF-BS-07   | O usuário deve ter acesso a um guia/tutorial explicativo sobre como utilizar o ID Jovem.                                                       |               |               |
| RF-BS-08   | O usuário deve ter acesso a perguntas frequentes (FAQ) e suporte para dúvidas.                                                                 |               |               |
| RF-BS-09   | O aplicativo deve permitir atualização automática dos dados do beneficiário com base nas informações do CadÚnico.                               |               |               |
| RF-BS-10   | O usuário deve conseguir acessar informações sobre locais e serviços onde o ID Jovem é aceito.                                                |               |               |
| RF-BS-11   | O aplicativo deve oferecer notificações sobre vencimento e renovação do benefício.                                                             |               |               |
| RF-BS-12   | O usuário deve poder compartilhar a carteirinha digital em PDF ou imagem para uso em estabelecimentos.                                         |               |               |
| RF-BS-13   | O sistema deve validar em tempo real a autenticidade da carteirinha.                                                                           |               |               |
| RF-BS-14   | O aplicativo deve oferecer um processo de onboarding adaptado para usuários com diferentes níveis de familiaridade tecnológica.                 |               |               |
| RNF-BS-01  | O aplicativo deve ser leve e compatível com diferentes modelos de smartphones, inclusive de baixo custo.                                       |               |               |
| RNF-BS-02  | O aplicativo deve ser intuitivo, com ícones e textos de fácil compreensão.                                                                     |               |               |
| RNF-BS-03  | O aplicativo deve enviar notificações sobre prazos e eventos próximos.                                                                         |               |               |
| RNF-BS-04  | O aplicativo deve organizar os menus de forma clara e acessível para jovens com pouca experiência digital.                                      |               |               |
| RNF-BS-05  | O aplicativo deve garantir funcionamento offline para exibição da carteirinha já emitida.                                                     |               |               |
| RNF-BS-06  | O aplicativo deve oferecer recursos de acessibilidade (alto contraste, leitura de tela, comandos por voz).                                     |               |               |
| RNF-BS-07  | O sistema deve integrar-se com o CadÚnico e outros serviços digitais do governo.                                                               |               |               |
| RNF-BS-08  | O aplicativo deve proteger os dados dos usuários em conformidade com a LGPD, utilizando criptografia.                                          |               |               |
| RNF-BS-09  | O aplicativo deve ser compatível com Android e iOS.                                                                                            |               |               |
| RNF-BS-10  | O aplicativo deve funcionar com baixo consumo de internet, garantindo acessibilidade a jovens em regiões carentes.                              |               |               |
| RNF-BS-11  | O aplicativo deve estar disponível em português e oferecer suporte básico em outros idiomas oficiais do Brasil (como Libras em vídeo).         |               |               |
| RF-INT-01  | O sistema deve permitir que o jovem emita sua carteira ID Jovem virtual fornecendo NIS, nome completo, data de nascimento e nome da mãe.       |               |               |
| RF-INT-02  | O sistema deve permitir que estabelecimentos comerciais e empresas de transporte validem a autenticidade de uma carteira ID Jovem.             |               |               |
| RF-INT-03  | O sistema deve exibir claramente os benefícios do programa, como meia-entrada e vagas em transporte interestadual.                             |               |               |
| RF-INT-04  | O sistema deve fornecer uma seção de "Dúvidas Frequentes" para esclarecer questões sobre o programa, o CadÚnico e os benefícios.               |               |               |
| RNF-INT-01 | O sistema deve ser gratuito para o cidadão.                                                                                                     |               |               |
| RNF-INT-02 | O sistema deve ser compatível com os principais sistemas operacionais móveis (Android e iOS) e navegadores web.                               |               |               |
| RNF-INT-03 | O sistema deve proteger os dados pessoais dos jovens (CPF, NIS) conforme as leis de proteção de dados vigentes.                                 |               |               |
| RNF-INT-04 | O sistema deve se conectar à base de dados do CadÚnico para verificar a elegibilidade do jovem em tempo real.                                   |               |               |
| RI-01      | A interface deve ser intuitiva e acessível para jovens de diferentes níveis de letramento digital.                                             |               |               |
| RI-02      | A carteira virtual gerada deve conter um QR Code ou outro método de validação rápida.                                                         |               |               |
| RI-03      | O sistema deve enviar notificações ao usuário sobre o vencimento de sua carteira ID Jovem.                                                    |               |               |
| RR-01      | Risco de o jovem não conseguir emitir a carteira devido a dados desatualizados no CadÚnico.                                                 |               |               |
| RR-02      | Risco de indisponibilidade ou lentidão no serviço de consulta à base do CadÚnico, impedindo a emissão da carteira.                            |               |               |
| RR-03      | Risco de empresas se recusarem a aceitar o benefício, gerando frustração no usuário e descrédito do programa.                                 |               |               |
| RT-01      | O processo de emissão deve ser testado com diferentes perfis de jovens (NIS válido, NIS inválido, cadastro desatualizado).                     |               |               |
| RT-02      | O fluxo de validação da carteira deve ser testado a partir da perspectiva de um estabelecimento comercial.                                      |               |               |
| RT-03      | Testes de usabilidade devem ser conduzidos com jovens na faixa etária de 15 a 29 anos para validar a clareza da interface.                     |               |               |


**Fontes:** [Arthur Fernandes](https://github.com/arthurfernandesj), 2025  

---

## Histórico de Versões

| Versão |    Data    |      Descrição       |                        Autor(es)                        |                       Revisor(es)                       |
| :----: | :--------: | :------------------: | :-----------------------------------------------------: | :-----------------------------------------------------: |
| `1.0`  | 28/09/2025 | Criação do documento com a descrição da técnica de priorização "MoSCoW" | [Danilo Melo](https://github.com/EngDann) |  [ Arthur Fernandes](https://github.com/arthurfernandesj)|
| `1.1`  | 29/09/2025 | Atualização da técnica de priorização "MoSCoW e tabela de priorização adicionada" | [Arthur Fernandes](https://github.com/arthurfernandesj) |  [Letícia Lopes](https://github.com/leticialopes20) |
| `1.2`  | 30/09/2025 | Atualização da tabela de priorização de requisitos | [Letícia Lopes](https://github.com/leticialopes20) |   [Arthur Fernandes](https://github.com/arthurfernandesj)|