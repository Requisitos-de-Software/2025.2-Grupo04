# MoSCoW

## Introdução  

O **MoSCoW** é uma técnica amplamente utilizada para **priorização de requisitos em projetos de software**. Sua simplicidade e objetividade permitem alinhar expectativas entre a equipe de desenvolvimento e os stakeholders, garantindo foco nos itens indispensáveis para o sucesso do sistema.  

O método organiza os requisitos em quatro classificações (**M, S, C ou W**), proporcionando uma alternativa mais clara à tradicional divisão em níveis de prioridade (baixo, médio, alto). Essa abordagem é especialmente útil em sistemas como o **ID Jovem**, em que é necessário diferenciar o que é crítico (como validação de dados pessoais e emissão do benefício) do que pode ser adicionado posteriormente.

## Técnica MoSCoW  

O MoSCoW divide os requisitos em quatro categorias:  

- **M – Must have (Tem que ter):** Requisitos críticos, indispensáveis para o funcionamento do sistema. Sem eles, o projeto não pode ser considerado bem-sucedido.  
- **S – Should have (Deveria ter):** Requisitos importantes, mas não essenciais na entrega inicial. Sua ausência não inviabiliza o sistema, mas pode impactar a experiência do usuário.  
- **C – Could have (Poderia ter):** Requisitos desejáveis que aumentam a satisfação do usuário, implementados apenas se houver tempo e recursos.  
- **W – Won't have (Não terá):** Requisitos que, em comum acordo com os stakeholders, não serão implementados nesta versão, mas podem ser considerados em futuras releases.  

Apesar de prática, a técnica pode gerar dúvidas: quando se classifica um requisito como **Won't**, significa que ele nunca será implementado ou apenas não estará presente na primeira versão? Por isso, recomenda-se que o MoSCoW seja complementado por outras técnicas de priorização.

### Vantagens  

- Linguagem simples e acessível.  
- Facilita a participação de todos os stakeholders.  
- Define claramente o escopo mínimo viável (MVP).  
- Permite ajustes durante o andamento do projeto.  
- Ajuda a focar nos itens que realmente agregam valor imediato.

### Desvantagens  

- Pode ser simplista em contextos mais complexos.  
- Subjetividade na decisão das classificações.  
- Risco de influências políticas sobre critérios técnicos.  
- Necessidade de que os envolvidos conheçam bem o negócio para uma priorização eficaz.

## Metodologia de Aplicação  

Para aplicar o MoSCoW ao **ID Jovem**, seguimos as etapas:  

1. **Levantamento:** Reunimos os requisitos obtidos pelas técnicas de elicitação.  
2. **Discussão:** Avaliamos em conjunto com os stakeholders a relevância de cada requisito, através de uma planilha.
3. **Classificação:** Cada requisito foi categorizado em Must, Should, Could ou Won't.  
4. **Validação:** A priorização foi revisada com todos os envolvidos.  
5. **Revisão contínua:** Considerando que o ID Jovem pode evoluir (novos serviços, integrações e legislações), os requisitos podem ser reavaliados a qualquer momento.

## Participantes

<font size="3"><p style="text-align: center">Tabela 1: Participantes</p></font>

<div align="center">
  <table>
    <thead>
      <tr>
        <th>Sessão</th>
        <th>Papel</th>
        <th>Nome</th>
        <th>Data</th>
        <th>Hora</th>
        <th>Local</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td rowspan="4"><strong>Sessão 1</strong></td>
        <td>Mediador</td>
        <td>Arthur Fernandes</td>
        <td>30/09/2025</td>
        <td>10:00</td>
        <td>UnB Campus Gama</td>
      </tr>
      <tr>
        <td>Equipe</td>
        <td>Dylan</td>
        <td>30/09/2025</td>
        <td>10:00</td>
        <td>UnB Campus Gama</td>
      </tr>
      <tr>
        <td>Equipe</td>
        <td>Giovana</td>
        <td>30/09/2025</td>
        <td>10:00</td>
        <td>UnB Campus Gama</td>
      </tr>
      <tr>
        <td>Usuário</td>
        <td>Wellington</td>
        <td>30/09/2025</td>
        <td>10:00</td>
        <td>UnB Campus Gama</td>
      </tr>
    </tbody>
  </table>
</div>

<font size="3"><p>Fonte:[Letícia Lopes](https://github.com/leticialopes20) </p></font>

## Requisitos Priorizados

A Tabela 2 apresenta a classificação dos requisitos do **ID Jovem**, considerando sua relevância para o sistema.

<font size="3"><p style="text-align: center">Tabela 2: Planilha de priorização - Técnica MoSCoW</p></font>

| Código | Origem | Descrição | Prioridade | Justificativa |
|--------|--------|-----------|------------|---------------|
| **RNF-01** | USA-01 | O processo de login deve ser simplificado e otimizado para minimizar o número de passos e a carga cognitiva do usuário | MUST | Essencial para usabilidade básica e adoção do aplicativo |
| **RNF-02** | USA-02 | A interface do aplicativo deve ser intuitiva, com navegação clara, textos legíveis e design acessível | MUST | Fundamental para experiência do usuário e inclusão digital |
| **RNF-03** | PER-01 | A geração e exibição do documento digital devem ser concluídas em no máximo 5 segundos | MUST | Performance crítica para funcionalidade principal |
| **RNF-04** | SEG-01 | Os dados pessoais devem ser armazenados e transmitidos utilizando criptografia forte | MUST | Requisito de segurança obrigatório para dados sensíveis |
| **RNF-05** | CON-01 | O aplicativo deve manter uma disponibilidade de serviço de 99.5% | SHOULD | Alta disponibilidade desejável para serviço governamental |
| **RNF-06** | POR-01 | O aplicativo deve ser compatível com as duas versões mais recentes do Android e iOS | MUST | Compatibilidade básica para alcançar público-alvo |
| **RF-01** | CAD-01 | O sistema deve permitir o cadastro do usuário por meio do CPF | WON'T | Substituído pelo login gov.br (RF-09) - redundante |
| **RF-02** | AUT-01 | O sistema deve fornecer mecanismos de autenticação e login para o usuário | MUST | Segurança básica e controle de acesso obrigatório |
| **RF-03** | EMI-01 | O sistema deve permitir a geração e emissão da carteira digital ID Jovem | MUST | Funcionalidade principal do aplicativo |
| **RF-04** | BEN-01 | O sistema deve permitir a consulta de benefícios como transporte gratuito e acesso a eventos | MUST | Valor principal para o usuário final |
| **RF-05** | VAL-01 | O sistema deve permitir a validação da carteira por estabelecimentos conveniados | MUST | Essencial para utilidade do programa |
| **RF-06** | FAQ-01 | O sistema deve disponibilizar uma seção de perguntas frequentes e informações de atendimento | COULD | Pode ser implementado em versão posterior como valor agregado |
| **RF-07** | SUP-01 | O sistema deve prover um canal de comunicação direto para suporte ao usuário | SHOULD | Suporte importante para resolver dúvidas |
| **RF-08** | COM-01 | O sistema deve apresentar uma seção de "Novidades e Divulgação" | WON'T | Não essencial para MVP - pode ser adiado indefinidamente |
| **RF-09** | BS-01 | O usuário deve realizar o login com o acesso unificado do gov.br | MUST | Integração obrigatória com governo federal |
| **RF-10** | BS-02 | O usuário deve aceitar um termo de uso em seu primeiro acesso | MUST | Requisito legal e de segurança obrigatório |
| **RF-11** | BS-03 | O usuário deve conseguir consultar se está dentro dos critérios para ter direito ao ID Jovem | MUST | Funcionalidade central de elegibilidade |
| **RF-12** | BS-04 | O usuário deve poder emitir sua carteirinha digital do ID Jovem | MUST | Funcionalidade principal do sistema |
| **RF-13** | BS-05 | O usuário deve conseguir visualizar os benefícios disponíveis | MUST | Informação essencial para usuário |
| **RF-14** | BS-06 | O usuário deve poder verificar a validade da sua carteirinha | MUST | Controle importante para usuário |
| **RF-15** | BS-07 | O usuário deve ter acesso a um guia/tutorial explicativo | COULD | Pode ser simplificado na primeira versão |
| **RF-16** | BS-08 | O usuário deve ter acesso a perguntas frequentes e suporte | SHOULD | Suporte básico desejável |
| **RF-17** | BS-09 | O aplicativo deve permitir atualização automática dos dados via CadÚnico | MUST | Atualização automática evita retrabalho e erros |
| **RF-18** | BS-10 | O usuário deve conseguir acessar informações sobre locais onde o ID Jovem é aceito | MUST | Informação prática essencial |
| **RF-19** | BS-11 | O aplicativo deve oferecer notificações sobre vencimento e renovação | SHOULD | Funcionalidade importante mas não crítica |
| **RF-20** | BS-12 | O usuário deve poder compartilhar a carteirinha digital em PDF ou imagem | MUST | Funcionalidade essencial para uso prático |
| **RF-21** | BS-13 | O sistema deve validar em tempo real a autenticidade da carteirinha | MUST | Prevenção de fraudes crítica |
| **RF-22** | BS-14 | O aplicativo deve oferecer processo de onboarding adaptado | COULD | Melhora experiência mas não é crítica |
| **RF-23** | INT-01 | O sistema deve permitir emissão da carteira com NIS, nome completo, data nascimento e nome da mãe | MUST | Dados essenciais para identificação |
| **RF-24** | INT-02 | O sistema deve permitir que estabelecimentos validem a autenticidade da carteira | MUST | Funcionalidade crítica para estabelecimentos |
| **RF-25** | INT-03 | O sistema deve exibir claramente os benefícios do programa | MUST | Comunicação clara do valor oferecido |
| **RF-26** | INT-04 | O sistema deve fornecer uma seção de "Dúvidas Frequentes" | COULD | Suporte desejável mas não crítico |
| **RNF-07** | BS-01 | O aplicativo deve ser leve e compatível com diferentes modelos de smartphones | MUST | Acessibilidade para público diverso essencial |
| **RNF-08** | BS-02 | O aplicativo deve ser intuitivo, com ícones e textos de fácil compreensão | MUST | Usabilidade básica necessária |
| **RNF-09** | BS-03 | O aplicativo deve enviar notificações sobre prazos e eventos próximos | WON'T | Funcionalidade secundária - pode ser excluída |
| **RNF-10** | BS-04 | O aplicativo deve organizar os menus de forma clara e acessível | MUST | Navegação básica essencial |
| **RNF-11** | BS-05 | O aplicativo deve garantir funcionamento offline para exibição da carteirinha | MUST | Crítico para situações sem internet |
| **RNF-12** | BS-06 | O aplicativo deve oferecer recursos de acessibilidade | MUST | Inclusão e acessibilidade obrigatórias |
| **RNF-13** | BS-07 | O sistema deve integrar-se com o CadÚnico e serviços digitais do governo | MUST | Integração central do sistema |
| **RNF-14** | BS-08 | O aplicativo deve proteger os dados em conformidade com a LGPD | MUST | Conformidade legal obrigatória |
| **RNF-15** | BS-09 | O aplicativo deve ser compatível com Android e iOS | MUST | Alcance máximo do público-alvo |
| **RNF-16** | BS-10 | O aplicativo deve funcionar com baixo consumo de internet | SHOULD | Otimização desejável para realidade brasileira |
| **RNF-17** | BS-11 | O aplicativo deve estar disponível em português e suporte em outros idiomas | COULD | Funcionalidade adicional interessante |
| **RNF-18** | INT-01 | O sistema deve ser gratuito para o cidadão | MUST | Princípio fundamental do programa |
| **RNF-19** | INT-02 | O sistema deve ser compatível com Android, iOS e navegadores web | SHOULD | Multiplataforma desejável para ampliar acesso |
| **RNF-20** | INT-03 | O sistema deve proteger os dados pessoais conforme leis vigentes | MUST | Conformidade legal essencial |
| **RNF-21** | INT-04 | O sistema deve conectar à base do CadÚnico para verificar elegibilidade | MUST | Funcionalidade central do sistema |
| **RI-01** | RI-01 | A interface deve ser intuitiva e acessível | MUST | Usabilidade básica necessária |
| **RI-02** | RI-02 | A carteira virtual deve conter QR Code para validação rápida | MUST | Método prático e eficiente de validação |
| **RI-03** | RI-03 | O sistema deve enviar notificações sobre vencimento | SHOULD | Lembretes úteis mas não críticos |
| **RR-01** | RR-01 | Risco de dados desatualizados no CadÚnico | MUST | Risco crítico que precisa ser mitigado |
| **RR-02** | RR-02 | Risco de indisponibilidade do serviço de consulta ao CadÚnico | MUST | Contingência necessária para operação |
| **RR-03** | RR-03 | Risco de empresas recusarem aceitar o benefício | SHOULD | Risco importante a ser considerado |
| **RT-01** | RT-01 | Teste de emissão com diferentes perfis de jovens | MUST | Garantia de qualidade essencial |
| **RT-02** | RT-02 | Teste de validação por estabelecimentos comerciais | MUST | Validação da funcionalidade principal |
| **RT-03** | RT-03 | Testes de usabilidade com jovens de 15 a 29 anos | MUST | Validação com público-alvo crítico |

<font size="3"><p>Fonte: <a href="https://github.com/leticialopes20">Letícia Lopes</a>, <a href="https://github.com/arthurfernandesj">Arthur Fernandes</a>, 2025</p></font>

## Gravação

[![Assista à gravação](https://img.youtube.com/vi/dIxnYHoZO44/hqdefault.jpg)](https://youtu.be/dIxnYHoZO44)

**Vídeo 1:** Técnica de Priorização - Moscow  

**Fonte:** [Giovana Fontes](https://github.com/GiovanaFontesS), 2025

## Referências Bibliográficas

> WIEGERS, Karl E. **Software Requirements**. 2. ed. Redmond, WA: Microsoft Press, 2003.

## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
|--------|------|------------|-----------|-------------|
| `1.0` | 28/09/2025 | Criação do documento com a descrição da técnica de priorização "MoSCoW" | [Danilo Melo](https://github.com/EngDann) | [Arthur Fernandes](https://github.com/arthurfernandesj) |
| `1.1` | 29/09/2025 | Atualização da técnica de priorização "MoSCoW e tabela de priorização adicionada" | [Arthur Fernandes](https://github.com/arthurfernandesj) | [Letícia Lopes](https://github.com/leticialopes20) |
| `1.2` | 30/09/2025 | Atualização da tabela de priorização de requisitos | [Letícia Lopes](https://github.com/leticialopes20) | [Arthur Fernandes](https://github.com/arthurfernandesj) |
| `1.3` | 30/09/2025 | Atualização da tabela de priorização de requisitos com novos dados e finalização do documento | [Letícia Lopes](https://github.com/leticialopes20) | [Arthur Fernandes](https://github.com/arthurfernandesj) |