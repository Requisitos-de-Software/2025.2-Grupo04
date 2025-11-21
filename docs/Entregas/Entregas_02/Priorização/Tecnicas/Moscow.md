# MoSCoW

## Introdução

O **MoSCoW** é uma técnica amplamente utilizada para **priorização de requisitos em projetos de software**. Sua simplicidade e objetividade permitem alinhar expectativas entre a equipe de desenvolvimento e os stakeholders, garantindo foco nos itens indispensáveis para o sucesso do sistema. Conforme abordado por Wiegers<a id="anchor_intro_wiegers" href="#QT1">[1]</a>, essa técnica organiza os requisitos em quatro classificações (**M, S, C ou W**), proporcionando uma alternativa mais clara à tradicional divisão em níveis de prioridade (baixo, médio, alto). Essa abordagem é especialmente útil em sistemas como o **ID Jovem**, em que é necessário diferenciar o que é crítico (como validação de dados pessoais e emissão do benefício) do que pode ser adicionado posteriormente.

## Técnica MoSCoW

O MoSCoW divide os requisitos em quatro categorias:

-   **M – Must have (Tem que ter):** Requisitos críticos, indispensáveis para o funcionamento do sistema. Sem eles, o projeto não pode ser considerado bem-sucedido.
-   **S – Should have (Deveria ter):** Requisitos importantes, mas não essenciais na entrega inicial. Sua ausência não inviabiliza o sistema, mas pode impactar a experiência do usuário.
-   **C – Could have (Poderia ter):** Requisitos desejáveis que aumentam a satisfação do usuário, implementados apenas se houver tempo e recursos.
-   **W – Won't have (Não terá):** Requisitos que, em comum acordo com os stakeholders, não serão implementados nesta versão, mas podem ser considerados em futuras releases.

Apesar de prática, a técnica pode gerar dúvidas: quando se classifica um requisito como **Won't**, significa que ele nunca será implementado ou apenas não estará presente na primeira versão? Por isso, recomenda-se que o MoSCoW seja complementado por outras técnicas de priorização.

### Vantagens

-   Linguagem simples e acessível.
-   Facilita a participação de todos os stakeholders.
-   Define claramente o escopo mínimo viável (MVP).
-   Permite ajustes durante o andamento do projeto.
-   Ajuda a focar nos itens que realmente agregam valor imediato.

### Desvantagens

-   Pode ser simplista em contextos mais complexos.
-   Subjetividade na decisão das classificações.
-   Risco de influências políticas sobre critérios técnicos.
-   Necessidade de que os envolvidos conheçam bem o negócio para uma priorização eficaz.

## Metodologia de Aplicação

Para aplicar o MoSCoW ao **ID Jovem**, seguimos as etapas:

1.  **Levantamento:** Reunimos os requisitos obtidos pelas técnicas de elicitação.
2.  **Discussão:** Avaliamos em conjunto com os stakeholders a relevância de cada requisito, através de uma planilha.
3.  **Classificação:** Cada requisito foi categorizado em Must, Should, Could ou Won't.
4.  **Validação:** A priorização foi revisada com todos os envolvidos.
5.  **Revisão contínua:** Considerando que o ID Jovem pode evoluir (novos serviços, integrações e legislações), os requisitos podem ser reavaliados a qualquer momento.

## Participantes

<div align="center">
<p style="text-align: center; font-size: 12pt;"><strong>Tabela 1:</strong> Participantes</p>
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
<p style="text-align: center; font-size: 10pt;">Fonte: <a href="https://github.com/leticialopes20">Letícia Lopes</a>, 2025.</p>
</div>

## Requisitos Priorizados

A Tabela 2 apresenta a classificação dos requisitos do **ID Jovem**, considerando sua relevância para o sistema.

**Legenda:**

* RFx: Requisito Funcional número x
* RNFx: Requisito Não Funcional número x
* ENTx: Entrevista número x 
* BSx: Brainstorming número x
* ISx: Introspecção número x
* STx: Storytelling número x
* IDJx: Introspecção número x

<div align="center">
<p style="text-align: center; font-size: 12pt;"><strong>Tabela 2:</strong> Planilha de priorização - Técnica MoSCoW</p>
<table>
  <thead>
    <tr>
      <th>Código</th>
      <th>Origem</th>
      <th>Descrição</th>
      <th>Prioridade</th>
      <th>Justificativa</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>RNF-01</strong></td>
      <td>USA-01</td>
      <td>O processo de login deve ser simplificado e otimizado para minimizar o número de passos e a carga cognitiva do usuário</td>
      <td>MUST</td>
      <td>Essencial para usabilidade básica e adoção do aplicativo</td>
    </tr>
    <tr>
      <td><strong>RNF-02</strong></td>
      <td>USA-02</td>
      <td>A interface do aplicativo deve ser intuitiva, com navegação clara, textos legíveis e design acessível</td>
      <td>MUST</td>
      <td>Fundamental para experiência do usuário e inclusão digital</td>
    </tr>
    <tr>
      <td><strong>RNF-03</strong></td>
      <td>PER-01</td>
      <td>A geração e exibição do documento digital devem ser concluídas em no máximo 5 segundos</td>
      <td>MUST</td>
      <td>Performance crítica para funcionalidade principal</td>
    </tr>
    <tr>
      <td><strong>RNF-04</strong></td>
      <td>SEG-01</td>
      <td>Os dados pessoais devem ser armazenados e transmitidos utilizando criptografia forte</td>
      <td>MUST</td>
      <td>Requisito de segurança obrigatório para dados sensíveis</td>
    </tr>
    <tr>
      <td><strong>RNF-05</strong></td>
      <td>CON-01</td>
      <td>O aplicativo deve manter uma disponibilidade de serviço de 99.5%</td>
      <td>SHOULD</td>
      <td>Alta disponibilidade desejável para serviço governamental</td>
    </tr>
    <tr>
      <td><strong>RNF-06</strong></td>
      <td>POR-01</td>
      <td>O aplicativo deve ser compatível com as duas versões mais recentes do Android e iOS</td>
      <td>MUST</td>
      <td>Compatibilidade básica para alcançar público-alvo</td>
    </tr>
    <tr>
      <td><strong>RF-01</strong></td>
      <td>CAD-01</td>
      <td>O sistema deve permitir o cadastro do usuário por meio do CPF</td>
      <td>WON'T</td>
      <td>Substituído pelo login gov.br (RF-09) - redundante</td>
    </tr>
    <tr>
      <td><strong>RF-02</strong></td>
      <td>AUT-01</td>
      <td>O sistema deve fornecer mecanismos de autenticação e login para o usuário</td>
      <td>MUST</td>
      <td>Segurança básica e controle de acesso obrigatório</td>
    </tr>
    <tr>
      <td><strong>RF-03</strong></td>
      <td>EMI-01</td>
      <td>O sistema deve permitir a geração e emissão da carteira digital ID Jovem</td>
      <td>MUST</td>
      <td>Funcionalidade principal do aplicativo</td>
    </tr>
    <tr>
      <td><strong>RF-04</strong></td>
      <td>BEN-01</td>
      <td>O sistema deve permitir a consulta de benefícios como transporte gratuito e acesso a eventos</td>
      <td>MUST</td>
      <td>Valor principal para o usuário final</td>
    </tr>
    <tr>
      <td><strong>RF-05</strong></td>
      <td>VAL-01</td>
      <td>O sistema deve permitir a validação da carteira por estabelecimentos conveniados</td>
      <td>MUST</td>
      <td>Essencial para utilidade do programa</td>
    </tr>
    <tr>
      <td><strong>RF-06</strong></td>
      <td>FAQ-01</td>
      <td>O sistema deve disponibilizar uma seção de perguntas frequentes e informações de atendimento</td>
      <td>COULD</td>
      <td>Pode ser implementado em versão posterior como valor agregado</td>
    </tr>
    <tr>
      <td><strong>RF-07</strong></td>
      <td>SUP-01</td>
      <td>O sistema deve prover um canal de comunicação direto para suporte ao usuário</td>
      <td>SHOULD</td>
      <td>Suporte importante para resolver dúvidas</td>
    </tr>
    <tr>
      <td><strong>RF-08</strong></td>
      <td>COM-01</td>
      <td>O sistema deve apresentar uma seção de "Novidades e Divulgação"</td>
      <td>WON'T</td>
      <td>Não essencial para MVP - pode ser adiado indefinidamente</td>
    </tr>
    <tr>
      <td><strong>RF-09</strong></td>
      <td>BS-01</td>
      <td>O usuário deve realizar o login com o acesso unificado do gov.br</td>
      <td>MUST</td>
      <td>Integração obrigatória com governo federal</td>
    </tr>
    <tr>
      <td><strong>RF-10</strong></td>
      <td>BS-02</td>
      <td>O usuário deve aceitar um termo de uso em seu primeiro acesso</td>
      <td>MUST</td>
      <td>Requisito legal e de segurança obrigatório</td>
    </tr>
    <tr>
      <td><strong>RF-11</strong></td>
      <td>BS-03</td>
      <td>O usuário deve conseguir consultar se está dentro dos critérios para ter direito ao ID Jovem</td>
      <td>MUST</td>
      <td>Funcionalidade central de elegibilidade</td>
    </tr>
    <tr>
      <td><strong>RF-12</strong></td>
      <td>BS-04</td>
      <td>O usuário deve poder emitir sua carteirinha digital do ID Jovem</td>
      <td>MUST</td>
      <td>Funcionalidade principal do sistema</td>
    </tr>
    <tr>
      <td><strong>RF-13</strong></td>
      <td>BS-05</td>
      <td>O usuário deve conseguir visualizar os benefícios disponíveis</td>
      <td>MUST</td>
      <td>Informação essencial para usuário</td>
    </tr>
    <tr>
      <td><strong>RF-14</strong></td>
      <td>BS-06</td>
      <td>O usuário deve poder verificar a validade da sua carteirinha</td>
      <td>MUST</td>
      <td>Controle importante para usuário</td>
    </tr>
    <tr>
      <td><strong>RF-15</strong></td>
      <td>BS-07</td>
      <td>O usuário deve ter acesso a um guia/tutorial explicativo</td>
      <td>COULD</td>
      <td>Pode ser simplificado na primeira versão</td>
    </tr>
    <tr>
      <td><strong>RF-16</strong></td>
      <td>BS-08</td>
      <td>O usuário deve ter acesso a perguntas frequentes e suporte</td>
      <td>SHOULD</td>
      <td>Suporte básico desejável</td>
    </tr>
    <tr>
      <td><strong>RF-17</strong></td>
      <td>BS-09</td>
      <td>O aplicativo deve permitir atualização automática dos dados via CadÚnico</td>
      <td>MUST</td>
      <td>Atualização automática evita retrabalho e erros</td>
    </tr>
    <tr>
      <td><strong>RF-18</strong></td>
      <td>BS-10</td>
      <td>O usuário deve conseguir acessar informações sobre locais onde o ID Jovem é aceito</td>
      <td>MUST</td>
      <td>Informação prática essencial</td>
    </tr>
    <tr>
      <td><strong>RF-19</strong></td>
      <td>BS-11</td>
      <td>O aplicativo deve oferecer notificações sobre vencimento e renovação</td>
      <td>SHOULD</td>
      <td>Funcionalidade importante mas não crítica</td>
    </tr>
    <tr>
      <td><strong>RF-20</strong></td>
      <td>BS-12</td>
      <td>O usuário deve poder compartilhar a carteirinha digital em PDF ou imagem</td>
      <td>MUST</td>
      <td>Funcionalidade essencial para uso prático</td>
    </tr>
    <tr>
      <td><strong>RF-21</strong></td>
      <td>BS-13</td>
      <td>O sistema deve validar em tempo real a autenticidade da carteirinha</td>
      <td>MUST</td>
      <td>Prevenção de fraudes crítica</td>
    </tr>
    <tr>
      <td><strong>RF-22</strong></td>
      <td>BS-14</td>
      <td>O aplicativo deve oferecer processo de onboarding adaptado</td>
      <td>COULD</td>
      <td>Melhora experiência mas não é crítica</td>
    </tr>
    <tr>
      <td><strong>RF-23</strong></td>
      <td>INT-01</td>
      <td>O sistema deve permitir emissão da carteira com NIS, nome completo, data nascimento e nome da mãe</td>
      <td>MUST</td>
      <td>Dados essenciais para identificação</td>
    </tr>
    <tr>
      <td><strong>RF-24</strong></td>
      <td>INT-02</td>
      <td>O sistema deve permitir que estabelecimentos validem a autenticidade da carteira</td>
      <td>MUST</td>
      <td>Funcionalidade crítica para estabelecimentos</td>
    </tr>
    <tr>
      <td><strong>RF-25</strong></td>
      <td>INT-03</td>
      <td>O sistema deve exibir claramente os benefícios do programa</td>
      <td>MUST</td>
      <td>Comunicação clara do valor oferecido</td>
    </tr>
    <tr>
      <td><strong>RF-26</strong></td>
      <td>INT-04</td>
      <td>O sistema deve fornecer uma seção de "Dúvidas Frequentes"</td>
      <td>COULD</td>
      <td>Suporte desejável mas não crítico</td>
    </tr>
    <tr>
      <td><strong>RNF-07</strong></td>
      <td>BS-01</td>
      <td>O aplicativo deve ser leve e compatível com diferentes modelos de smartphones</td>
      <td>MUST</td>
      <td>Acessibilidade para público diverso essencial</td>
    </tr>
    <tr>
      <td><strong>RNF-08</strong></td>
      <td>BS-02</td>
      <td>O aplicativo deve ser intuitivo, com ícones e textos de fácil compreensão</td>
      <td>MUST</td>
      <td>Usabilidade básica necessária</td>
    </tr>
    <tr>
      <td><strong>RNF-09</strong></td>
      <td>BS-03</td>
      <td>O aplicativo deve enviar notificações sobre prazos e eventos próximos</td>
      <td>WON'T</td>
      <td>Funcionalidade secundária - pode ser excluída</td>
    </tr>
    <tr>
      <td><strong>RNF-10</strong></td>
      <td>BS-04</td>
      <td>O aplicativo deve organizar os menus de forma clara e acessível</td>
      <td>MUST</td>
      <td>Navegação básica essencial</td>
    </tr>
    <tr>
      <td><strong>RNF-11</strong></td>
      <td>BS-05</td>
      <td>O aplicativo deve garantir funcionamento offline para exibição da carteirinha</td>
      <td>MUST</td>
      <td>Crítico para situações sem internet</td>
    </tr>
    <tr>
      <td><strong>RNF-12</strong></td>
      <td>BS-06</td>
      <td>O aplicativo deve oferecer recursos de acessibilidade</td>
      <td>MUST</td>
      <td>Inclusão e acessibilidade obrigatórias</td>
    </tr>
    <tr>
      <td><strong>RNF-13</strong></td>
      <td>BS-07</td>
      <td>O sistema deve integrar-se com o CadÚnico e serviços digitais do governo</td>
      <td>MUST</td>
      <td>Integração central do sistema</td>
    </tr>
    <tr>
      <td><strong>RNF-14</strong></td>
      <td>BS-08</td>
      <td>O aplicativo deve proteger os dados em conformidade com a LGPD</td>
      <td>MUST</td>
      <td>Conformidade legal obrigatória</td>
    </tr>
    <tr>
      <td><strong>RNF-15</strong></td>
      <td>BS-09</td>
      <td>O aplicativo deve ser compatível com Android e iOS</td>
      <td>MUST</td>
      <td>Alcance máximo do público-alvo</td>
    </tr>
    <tr>
      <td><strong>RNF-16</strong></td>
      <td>BS-10</td>
      <td>O aplicativo deve funcionar com baixo consumo de internet</td>
      <td>SHOULD</td>
      <td>Otimização desejável para realidade brasileira</td>
    </tr>
    <tr>
      <td><strong>RNF-17</strong></td>
      <td>BS-11</td>
      <td>O aplicativo deve estar disponível em português e suporte em outros idiomas</td>
      <td>COULD</td>
      <td>Funcionalidade adicional interessante</td>
    </tr>
    <tr>
      <td><strong>RNF-18</strong></td>
      <td>INT-01</td>
      <td>O sistema deve ser gratuito para o cidadão</td>
      <td>MUST</td>
      <td>Princípio fundamental do programa</td>
    </tr>
    <tr>
      <td><strong>RNF-19</strong></td>
      <td>INT-02</td>
      <td>O sistema deve ser compatível com Android, iOS e navegadores web</td>
      <td>SHOULD</td>
      <td>Multiplataforma desejável para ampliar acesso</td>
    </tr>
    <tr>
      <td><strong>RNF-20</strong></td>
      <td>INT-03</td>
      <td>O sistema deve proteger os dados pessoais conforme leis vigentes</td>
      <td>MUST</td>
      <td>Conformidade legal essencial</td>
    </tr>
    <tr>
      <td><strong>RNF-21</strong></td>
      <td>INT-04</td>
      <td>O sistema deve conectar à base do CadÚnico para verificar elegibilidade</td>
      <td>MUST</td>
      <td>Funcionalidade central do sistema</td>
    </tr>
    <tr>
      <td><strong>RI-01</strong></td>
      <td>RI-01</td>
      <td>A interface deve ser intuitiva e acessível</td>
      <td>MUST</td>
      <td>Usabilidade básica necessária</td>
    </tr>
    <tr>
      <td><strong>RI-02</strong></td>
      <td>RI-02</td>
      <td>A carteira virtual deve conter QR Code para validação rápida</td>
      <td>MUST</td>
      <td>Método prático e eficiente de validação</td>
    </tr>
    <tr>
      <td><strong>RI-03</strong></td>
      <td>RI-03</td>
      <td>O sistema deve enviar notificações sobre vencimento</td>
      <td>SHOULD</td>
      <td>Lembretes úteis mas não críticos</td>
    </tr>
    <tr>
      <td><strong>RR-01</strong></td>
      <td>RR-01</td>
      <td>Risco de dados desatualizados no CadÚnico</td>
      <td>MUST</td>
      <td>Risco crítico que precisa ser mitigado</td>
    </tr>
    <tr>
      <td><strong>RR-02</strong></td>
      <td>RR-02</td>
      <td>Risco de indisponibilidade do serviço de consulta ao CadÚnico</td>
      <td>MUST</td>
      <td>Contingência necessária para operação</td>
    </tr>
    <tr>
      <td><strong>RR-03</strong></td>
      <td>RR-03</td>
      <td>Risco de empresas recusarem aceitar o benefício</td>
      <td>SHOULD</td>
      <td>Risco importante a ser considerado</td>
    </tr>
    <tr>
      <td><strong>RT-01</strong></td>
      <td>RT-01</td>
      <td>Testes de emissão com diferentes perfis de jovens</td>
      <td>MUST</td>
      <td>Garantia de qualidade essencial</td>
    </tr>
    <tr>
      <td><strong>RT-02</strong></td>
      <td>RT-02</td>
      <td>Testes de validação por estabelecimentos comerciais</td>
      <td>MUST</td>
      <td>Validação da funcionalidade principal</td>
    </tr>
    <tr>
      <td><strong>RT-03</strong></td>
      <td>RT-03</td>
      <td>Testes de usabilidade com jovens de 15 a 29 anos</td>
      <td>MUST</td>
      <td>Validação com público-alvo crítico</td>
    </tr>
  </tbody>
</table>
<p style="text-align: center; font-size: 10pt;">Fonte: <a href="https://github.com/leticialopes20">Letícia Lopes</a>, <a href="https://github.com/arthurfernandesj">Arthur Fernandes</a>, 2025.</p>
</div>

## Gravação

<div align="center">
<p style="text-align: center"><a href="https://youtu.be/dIxnYHoZO44" target="_blank"><b>Vídeo 1:</b> Técnica de Priorização - Moscow</a></p>

<iframe width="560" height="315" src="https://www.youtube.com/embed/dIxnYHoZO44" title="Sessão de Técnica de Priorização - Moscow" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<p style="text-align: center; font-size: 10pt;">Fonte: <a href="https://github.com/GiovanaFontesS">Giovana Fontes</a>, 2025.</p>
</div>

## Referências Bibliográficas

><p><a id="QT1" href="#anchor_intro_wiegers">1.</a> WIEGERS, Karl E. **Software Requirements**. 2. ed. Redmond, WA: Microsoft Press, 2003.</p>

## Bibliografia

> SERRANO, Milene; SERRANO, Maurício. **Requisitos – Aula 07**. Gama, DF: Universidade de Brasília, [s.d.]. Material de aula.

## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :--: | :--: | :-- | :-- | :-- |
| `1.0` | 28/09/2025 | Criação do documento com a descrição da técnica de priorização "MoSCoW" | [Danilo Melo](https://github.com/EngDann) | [Arthur Fernandes](https://github.com/arthurfernandesj) |
| `1.1` | 29/09/2025 | Atualização da técnica de priorização "MoSCoW e tabela de priorização adicionada" | [Arthur Fernandes](https://github.com/arthurfernandesj) | [Letícia Lopes](https://github.com/leticialopes20) |
| `1.2` | 30/09/2025 | Atualização da tabela de priorização de requisitos | [Letícia Lopes](https://github.com/leticialopes20) | [Arthur Fernandes](https://github.com/arthurfernandesj) |
| `1.3` | 30/09/2025 | Atualização da tabela de priorização de requisitos com novos dados e finalização do documento | [Letícia Lopes](https://github.com/leticialopes20) | [Arthur Fernandes](https://github.com/arthurfernandesj) |