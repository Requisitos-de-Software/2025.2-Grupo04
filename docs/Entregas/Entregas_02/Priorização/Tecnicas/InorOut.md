# **Técnica In or Out**

## Introdução

A técnica **In or Out** é um método de priorização direto e binário, utilizado para classificar requisitos de forma rápida e eficiente. Seu objetivo principal é separar os itens essenciais para o produto daqueles que podem ser considerados secundários ou desnecessários. Conforme descrito por Serrano e Serrano<a id="anchor_intro_serrano" href="#QT1">[1]</a>, essa técnica é especialmente útil nas fases iniciais do projeto, quando é necessário tomar decisões rápidas sobre o que será ou não desenvolvido. A simplicidade do método o torna ideal para situações onde o tempo é limitado e a equipe precisa de clareza imediata sobre o escopo básico do produto, uma abordagem fundamental também destacada por Wiegers<a id="anchor_intro_wiegers" href="#QT2">[2]</a> em seus estudos sobre requisitos de software.

#### **O que é?**

É um método de categorização simples onde cada requisito é classificado como "In" (dentro do escopo) ou "Out" (fora do escopo). Esta técnica é especialmente útil nas fases iniciais do projeto, quando é necessário tomar decisões rápidas sobre o que será ou não desenvolvido. A simplicidade do método o torna ideal para situações onde o tempo é limitado e a equipe precisa de clareza imediata sobre o escopo básico do produto.

#### **Como se usa?**

O processo é extremamente direto e pode ser realizado em uma única sessão de trabalho com os principais stakeholders:

1.  **Listar Requisitos:** Todos os requisitos candidatos são listados em cartões, post-its ou em uma planilha compartilhada.
2.  **Classificação Binária:** Para cada requisito, pergunta-se: "Este item é absolutamente essencial para a primeira versão do produto?"
3.  **Decisão In/Out:**
    -   **In:** Requisitos considerados fundamentais para o produto funcionar ou entregar valor mínimo ao usuário.
    -   **Out:** Requisitos que, embora possam ser desejáveis, não são críticos para o lançamento inicial. Estes podem ser reconsiderados para versões futuras.
4.  **Validação:** A lista final de itens "In" forma o escopo mínimo viável (MVP) ou a base para priorizações mais detalhadas subsequentes.

#### **Vantagens**

-   **Extrema simplicidade e velocidade:** A classificação binária torna o processo muito ágil.
-   **Clareza imediata:** Gera uma divisão clara e compreensível para toda a equipe sobre o que é essencial.
-   **Ideal para definir MVP:** Perfeita para estabelecer o escopo mínimo de um produto ou de uma release inicial.
-   **Ótimo ponto de partida:** Serve como um primeiro filtro antes da aplicação de técnicas de priorização mais refinadas (como MoSCoW ou First Things First).

#### **Desvantagens**

-   **Falta de nuance:** Não considera o valor relativo, custo, risco ou esforço entre os requisitos classificados como "In".
-   **Pode ser muito radical:** A natureza binária pode forçar a exclusão de funcionalidades valiosas que não são "absolutamente essenciais", mas que teriam um alto retorno com baixo custo.
-   **Depende do bom senso:** A qualidade do resultado depende muito do julgamento e da experiência dos participantes.

## Metodologia

Durante a aplicação da técnica **In or Out**, os membros da equipe de requisitos analisaram cada funcionalidade proposta com base nos seguintes critérios:

1.  **Valor essencial para o usuário final:** o requisito é crítico para a experiência do usuário?
2.  **Obrigatoriedade legal ou contratual:** o requisito é exigido por regulação ou contrato?
3.  **Impacto direto na funcionalidade central do sistema:** sua ausência compromete o uso do sistema?

Caso a resposta fosse afirmativa para qualquer um dos pontos acima, o requisito foi classificado como **IN**. Caso contrário, foi considerado **OUT**.

Requisitos classificados como **OUT** foram justificados com base em sua não essencialidade ou por se tratarem de melhorias de experiência, que podem ser postergadas.

## Participantes

<div align="center">
<p style="text-align: center; font-size: 12pt;"><strong>Tabela 1:</strong> Participantes da sessão</p>
<table>
  <thead>
    <tr>
      <th>Sessão</th>
      <th>Papel</th>
      <th>Participante</th>
      <th>Data</th>
      <th>Horário</th>
      <th>Local</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="4"><strong>Sessão 1</strong></td>
      <td>Mediadora</td>
      <td>Letícia Lopes</td>
      <td>29/09/2025</td>
      <td>12:30</td>
      <td>UnB Campus Gama</td>
    </tr>
    <tr>
      <td>Equipe</td>
      <td>Eduarda</td>
      <td>29/09/2025</td>
      <td>12:30</td>
      <td>UnB Campus Gama</td>
    </tr>
    <tr>
      <td>Equipe</td>
      <td>Giovana</td>
      <td>29/09/2025</td>
      <td>12:30</td>
      <td>UnB Campus Gama</td>
    </tr>
    <tr>
      <td>Usuário</td>
      <td>Noemy</td>
      <td>29/09/2025</td>
      <td>12:30</td>
      <td>UnB Campus Gama</td>
    </tr>
  </tbody>
</table>
<p style="text-align: center; font-size: 10pt;">Fonte: <a href="https://github.com/leticialopes20">Letícia Lopes</a>, 2025.</p>
</div>

# Requisitos priorizados

**Legendas:**

* RFx: Requisito Funcional número x
* RNFx: Requisito Não Funcional número x

<div align="center">
<p style="text-align: center; font-size: 12pt;"><strong>Tabela 2:</strong> Planilha de priorização - Técnica In or Out</p>
<table>
  <thead>
    <tr>
      <th>ID</th>
      <th>Fonte</th>
      <th>Requisito</th>
      <th>IN or OUT</th>
      <th>Justificativa</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>RNF-01</strong></td>
      <td>USA-01</td>
      <td>O processo de login deve ser simplificado e otimizado para minimizar o número de passos e a carga cognitiva do usuário</td>
      <td>IN</td>
      <td>Essencial para garantir a usabilidade básica do aplicativo</td>
    </tr>
    <tr>
      <td><strong>RNF-02</strong></td>
      <td>USA-02</td>
      <td>A interface do aplicativo deve ser intuitiva, com navegação clara, textos legíveis e design acessível</td>
      <td>IN</td>
      <td>Fundamental para a experiência do usuário e adoção do app</td>
    </tr>
    <tr>
      <td><strong>RNF-03</strong></td>
      <td>PER-01</td>
      <td>A geração e exibição do documento digital devem ser concluídas em no máximo 5 segundos</td>
      <td>IN</td>
      <td>Performance crítica para a funcionalidade principal</td>
    </tr>
    <tr>
      <td><strong>RNF-04</strong></td>
      <td>SEG-01</td>
      <td>Os dados pessoais devem ser armazenados e transmitidos utilizando criptografia forte</td>
      <td>IN</td>
      <td>Requisito de segurança obrigatório para dados pessoais</td>
    </tr>
    <tr>
      <td><strong>RNF-05</strong></td>
      <td>CON-01</td>
      <td>O aplicativo deve manter uma disponibilidade de serviço de 99.5%</td>
      <td>IN</td>
      <td>Confiabilidade essencial para serviço governamental</td>
    </tr>
    <tr>
      <td><strong>RNF-06</strong></td>
      <td>POR-01</td>
      <td>O aplicativo deve ser compatível com as duas versões mais recentes do Android e iOS</td>
      <td>IN</td>
      <td>Compatibilidade básica para alcançar o público-alvo</td>
    </tr>
    <tr>
      <td><strong>RF-01</strong></td>
      <td>CAD-01</td>
      <td>O sistema deve permitir o cadastro do usuário por meio do CPF</td>
      <td>OUT</td>
      <td>Substituído pelo login gov.br (RF-09)</td>
    </tr>
    <tr>
      <td><strong>RF-02</strong></td>
      <td>AUT-01</td>
      <td>O sistema deve fornecer mecanismos de autenticação e login para o usuário</td>
      <td>IN</td>
      <td>Segurança básica e controle de acesso</td>
    </tr>
    <tr>
      <td><strong>RF-03</strong></td>
      <td>EMI-01</td>
      <td>O sistema deve permitir a geração e emissão da carteira digital ID Jovem</td>
      <td>IN</td>
      <td>Funcionalidade principal do aplicativo</td>
    </tr>
    <tr>
      <td><strong>RF-04</strong></td>
      <td>BEN-01</td>
      <td>O sistema deve permitir a consulta de benefícios como transporte gratuito e acesso a eventos</td>
      <td>IN</td>
      <td>Valor principal para o usuário final</td>
    </tr>
    <tr>
      <td><strong>RF-05</strong></td>
      <td>VAL-01</td>
      <td>O sistema deve permitir a validação da carteira por estabelecimentos conveniados</td>
      <td>IN</td>
      <td>Essencial para a utilidade do programa</td>
    </tr>
    <tr>
      <td><strong>RF-06</strong></td>
      <td>FAQ-01</td>
      <td>O sistema deve disponibilizar uma seção de perguntas frequentes e informações de atendimento</td>
      <td>OUT</td>
      <td>Pode ser implementado em versão posterior</td>
    </tr>
    <tr>
      <td><strong>RF-07</strong></td>
      <td>SUP-01</td>
      <td>O sistema deve prover um canal de comunicação direto para suporte ao usuário</td>
      <td>IN</td>
      <td>Suporte essencial para usuários</td>
    </tr>
    <tr>
      <td><strong>RF-08</strong></td>
      <td>COM-01</td>
      <td>O sistema deve apresentar uma seção de "Novidades e Divulgação"</td>
      <td>OUT</td>
      <td>Não essencial para MVP</td>
    </tr>
    <tr>
      <td><strong>RF-09</strong></td>
      <td>BS-01</td>
      <td>O usuário deve realizar o login com o acesso unificado do gov.br</td>
      <td>IN</td>
      <td>Integração essencial com governo</td>
    </tr>
    <tr>
      <td><strong>RF-10</strong></td>
      <td>BS-02</td>
      <td>O usuário deve aceitar um termo de uso em seu primeiro acesso</td>
      <td>IN</td>
      <td>Requisito legal e de segurança</td>
    </tr>
    <tr>
      <td><strong>RF-11</strong></td>
      <td>BS-03</td>
      <td>O usuário deve conseguir consultar se está dentro dos critérios para ter direito ao ID Jovem</td>
      <td>IN</td>
      <td>Funcionalidade central de elegibilidade</td>
    </tr>
    <tr>
      <td><strong>RF-12</strong></td>
      <td>BS-04</td>
      <td>O usuário deve poder emitir sua carteirinha digital do ID Jovem</td>
      <td>IN</td>
      <td>Funcionalidade principal do sistema</td>
    </tr>
    <tr>
      <td><strong>RF-13</strong></td>
      <td>BS-05</td>
      <td>O usuário deve conseguir visualizar os benefícios disponíveis</td>
      <td>IN</td>
      <td>Valor direto para o usuário</td>
    </tr>
    <tr>
      <td><strong>RF-14</strong></td>
      <td>BS-06</td>
      <td>O usuário deve poder verificar a validade da sua carteirinha</td>
      <td>IN</td>
      <td>Informação essencial para uso</td>
    </tr>
    <tr>
      <td><strong>RF-15</strong></td>
      <td>BS-07</td>
      <td>O usuário deve ter acesso a um guia/tutorial explicativo</td>
      <td>OUT</td>
      <td>Pode ser simplificado na primeira versão</td>
    </tr>
    <tr>
      <td><strong>RF-16</strong></td>
      <td>BS-08</td>
      <td>O usuário deve ter acesso a perguntas frequentes e suporte</td>
      <td>IN</td>
      <td>Suporte básico necessário</td>
    </tr>
    <tr>
      <td><strong>RF-17</strong></td>
      <td>BS-09</td>
      <td>O aplicativo deve permitir atualização automática dos dados via CadÚnico</td>
      <td>IN</td>
      <td>Atualização automática evita retrabalho</td>
    </tr>
    <tr>
      <td><strong>RF-18</strong></td>
      <td>BS-10</td>
      <td>O usuário deve conseguir acessar informações sobre locais onde o ID Jovem é aceito</td>
      <td>IN</td>
      <td>Informação prática essencial</td>
    </tr>
    <tr>
      <td><strong>RF-19</strong></td>
      <td>BS-11</td>
      <td>O aplicativo deve oferecer notificações sobre vencimento e renovação</td>
      <td>IN</td>
      <td>Funcionalidade importante para usuário</td>
    </tr>
    <tr>
      <td><strong>RF-20</strong></td>
      <td>BS-12</td>
      <td>O usuário deve poder compartilhar a carteirinha digital em PDF ou imagem</td>
      <td>IN</td>
      <td>Funcionalidade importante para uso</td>
    </tr>
    <tr>
      <td><strong>RF-21</strong></td>
      <td>BS-13</td>
      <td>O sistema deve validar em tempo real a autenticidade da carteirinha</td>
      <td>IN</td>
      <td>Prevenção de fraudes essencial</td>
    </tr>
    <tr>
      <td><strong>RF-22</strong></td>
      <td>BS-14</td>
      <td>O aplicativo deve oferecer processo de onboarding adaptado</td>
      <td>IN</td>
      <td>Melhora experiência de primeiro uso</td>
    </tr>
    <tr>
      <td><strong>RF-23</strong></td>
      <td>INT-01</td>
      <td>O sistema deve permitir emissão da carteira com NIS, nome completo, data nascimento e nome da mãe</td>
      <td>IN</td>
      <td>Dados essenciais para identificação</td>
    </tr>
    <tr>
      <td><strong>RF-24</strong></td>
      <td>INT-02</td>
      <td>O sistema deve permitir que estabelecimentos validem a autenticidade da carteira</td>
      <td>IN</td>
      <td>Funcionalidade crítica para estabelecimentos</td>
    </tr>
    <tr>
      <td><strong>RF-25</strong></td>
      <td>INT-03</td>
      <td>O sistema deve exibir claramente os benefícios do programa</td>
      <td>IN</td>
      <td>Comunicação clara do valor oferecido</td>
    </tr>
    <tr>
      <td><strong>RF-26</strong></td>
      <td>INT-04</td>
      <td>O sistema deve fornecer uma seção de "Dúvidas Frequentes"</td>
      <td>IN</td>
      <td>Suporte básico necessário</td>
    </tr>
    <tr>
      <td><strong>RNF-07</strong></td>
      <td>BS-01</td>
      <td>O aplicativo deve ser leve e compatível com diferentes modelos de smartphones</td>
      <td>IN</td>
      <td>Acessibilidade para público diverso</td>
    </tr>
    <tr>
      <td><strong>RNF-08</strong></td>
      <td>BS-02</td>
      <td>O aplicativo deve ser intuitivo, com ícones e textos de fácil compreensão</td>
      <td>IN</td>
      <td>Usabilidade básica necessária</td>
    </tr>
    <tr>
      <td><strong>RNF-09</strong></td>
      <td>BS-03</td>
      <td>O aplicativo deve enviar notificações sobre prazos e eventos próximos</td>
      <td>OUT</td>
      <td>Funcionalidade secundária</td>
    </tr>
    <tr>
      <td><strong>RNF-10</strong></td>
      <td>BS-04</td>
      <td>O aplicativo deve organizar os menus de forma clara e acessível</td>
      <td>IN</td>
      <td>Navegação básica essencial</td>
    </tr>
    <tr>
      <td><strong>RNF-11</strong></td>
      <td>BS-05</td>
      <td>O aplicativo deve garantir funcionamento offline para exibição da carteirinha</td>
      <td>IN</td>
      <td>Crítico para situações sem internet</td>
    </tr>
    <tr>
      <td><strong>RNF-12</strong></td>
      <td>BS-06</td>
      <td>O aplicativo deve oferecer recursos de acessibilidade</td>
      <td>IN</td>
      <td>Requisito de inclusão importante</td>
    </tr>
    <tr>
      <td><strong>RNF-13</strong></td>
      <td>BS-07</td>
      <td>O sistema deve integrar-se com o CadÚnico e serviços digitais do governo</td>
      <td>IN</td>
      <td>Integração central do sistema</td>
    </tr>
    <tr>
      <td><strong>RNF-14</strong></td>
      <td>BS-08</td>
      <td>O aplicativo deve proteger os dados em conformidade com a LGPD</td>
      <td>IN</td>
      <td>Conformidade legal obrigatória</td>
    </tr>
    <tr>
      <td><strong>RNF-15</strong></td>
      <td>BS-09</td>
      <td>O aplicativo deve ser compatível com Android e iOS</td>
      <td>IN</td>
      <td>Alcance máximo do público-alvo</td>
    </tr>
    <tr>
      <td><strong>RNF-16</strong></td>
      <td>BS-10</td>
      <td>O aplicativo deve funcionar com baixo consumo de internet</td>
      <td>IN</td>
      <td>Otimização para realidade brasileira</td>
    </tr>
    <tr>
      <td><strong>RNF-17</strong></td>
      <td>BS-11</td>
      <td>O aplicativo deve estar disponível em português e suporte em outros idiomas</td>
      <td>IN</td>
      <td>Acessibilidade linguística importante</td>
    </tr>
    <tr>
      <td><strong>RNF-18</strong></td>
      <td>INT-01</td>
      <td>O sistema deve ser gratuito para o cidadão</td>
      <td>IN</td>
      <td>Princípio fundamental do programa</td>
    </tr>
    <tr>
      <td><strong>RNF-19</strong></td>
      <td>INT-02</td>
      <td>O sistema deve ser compatível com Android, iOS e navegadores web</td>
      <td>IN</td>
      <td>Multiplataforma amplia acesso</td>
    </tr>
    <tr>
      <td><strong>RNF-20</strong></td>
      <td>INT-03</td>
      <td>O sistema deve proteger os dados pessoais conforme leis vigentes</td>
      <td>IN</td>
      <td>Conformidade legal essencial</td>
    </tr>
    <tr>
      <td><strong>RNF-21</strong></td>
      <td>INT-04</td>
      <td>O sistema deve conectar à base do CadÚnico para verificar elegibilidade</td>
      <td>IN</td>
      <td>Funcionalidade central do sistema</td>
    </tr>
    <tr>
      <td><strong>RI-01</strong></td>
      <td>RI-01</td>
      <td>A interface deve ser intuitiva e acessível</td>
      <td>IN</td>
      <td>Usabilidade básica necessária</td>
    </tr>
    <tr>
      <td><strong>RI-02</strong></td>
      <td>RI-02</td>
      <td>A carteira virtual deve conter QR Code para validação rápida</td>
      <td>IN</td>
      <td>Método prático de validação</td>
    </tr>
    <tr>
      <td><strong>RI-03</strong></td>
      <td>RI-03</td>
      <td>O sistema deve enviar notificações sobre vencimento</td>
      <td>IN</td>
      <td>Lembretes importantes para usuário</td>
    </tr>
    <tr>
      <td><strong>RR-01</strong></td>
      <td>RR-01</td>
      <td>Risco de dados desatualizados no CadÚnico</td>
      <td>IN</td>
      <td>Risco que precisa ser mitigado</td>
    </tr>
    <tr>
      <td><strong>RR-02</strong></td>
      <td>RR-02</td>
      <td>Risco de indisponibilidade do serviço de consulta ao CadÚnico</td>
      <td>IN</td>
      <td>Contingência necessária</td>
    </tr>
    <tr>
      <td><strong>RR-03</strong></td>
      <td>RR-03</td>
      <td>Risco de empresas recusarem aceitar o benefício</td>
      <td>IN</td>
      <td>Risco operacional importante</td>
    </tr>
    <tr>
      <td><strong>RT-01</strong></td>
      <td>RT-01</td>
      <td>Teste de emissão com diferentes perfis de jovens</td>
      <td>IN</td>
      <td>Testes de emissão com diferentes perfis de jovens</td>
    </tr>
    <tr>
      <td><strong>RT-02</strong></td>
      <td>RT-02</td>
      <td>Teste de validação por estabelecimentos comerciais</td>
      <td>IN</td>
      <td>Testes de validação por estabelecimentos comerciais</td>
    </tr>
    <tr>
      <td><strong>RT-03</strong></td>
      <td>RT-03</td>
      <td>Testes de usabilidade com jovens de 15 a 29 anos</td>
      <td>IN</td>
      <td>Validação com público-alvo crítico</td>
    </tr>
  </tbody>
</table>
<p style="text-align: center; font-size: 10pt;">Fonte: <a href="https://github.com/leticialopes20">Letícia Lopes</a>, 2025.</p>
</div>

## Gravação

<div align="center">
<p style="text-align: center"><a href="https://youtu.be/dIxnYHoZO44" target="_blank"><b>Vídeo 1:</b> Técnica de Priorização - Moscow</a></p>

<p style="text-align: center"><a href="https://youtu.be/ywmlErJ7bdA" target="_blank"><b>Vídeo 1:</b> Técnica de Priorização - In or Out</a></p>

<iframe width="560" height="315" src="https://www.youtube.com/embed/ywmlErJ7bdA" title="Sessão de Técnica de Priorização - In or Out" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
<iframe width="560" height="315" src="https://www.youtube.com/embed/dIxnYHoZO44" title="Sessão de Técnica de Priorização - Moscow" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<p style="text-align: center; font-size: 10pt;">Fonte: <a href="https://github.com/GiovanaFontesS">Giovana Fontes</a>, 2025.</p>

</div>

## Referências Bibliográficas

><p><a id="QT1" href="#anchor_intro_serrano">1.</a> SERRANO, Milene; SERRANO, Maurício. <b>Requisitos – Aula 07</b>. Gama, DF: Universidade de Brasília, [s.d.]. Material de aula.</p>
><p><a id="QT2" href="#anchor_intro_wiegers">2.</a> WIEGERS, Karl E. **Software Requirements**. 2. ed. Redmond, WA: Microsoft Press, 2003.</p>
<p><a id="QT1" href="#anchor_intro_wiegers">1.</a> WIEGERS, Karl E. **Software Requirements**. 2. ed. Redmond, WA: Microsoft Press, 2003.</p>

## Bibliografia

> SERRANO, Milene; SERRANO, Maurício. **Requisitos – Aula 07**. Gama, DF: Universidade de Brasília, [s.d.]. Material de aula.

## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :--: | :--: | :-- | :-- | :-- |
| `1.0` | 28/09/2025 | Criação do documento com a descrição da técnica de priorização " In or Out" | [Danilo Melo](https://github.com/EngDann) | [Letícia Lopes](https://github.com/leticialopes20) |
| `1.1` | 30/09/2025 | Atualização da tabela de priorização e finalização do documento | [Letícia Lopes](https://github.com/leticialopes20) | [Arthur Fernandes](https://github.com/arthurfernandesj) |
| `1.2`  | 10/10/2025 | Arrumando citação das Referências | [Breno](https://github.com/BrenoLteixeira) | [Arthur](https://github.com/) |
| `1.0` | 28/09/2025 | Criação do documento com a descrição da técnica de priorização "MoSCoW" | [Danilo Melo](https://github.com/EngDann) | [Arthur Fernandes](https://github.com/arthurfernandesj) |
| `1.1` | 29/09/2025 | Atualização da técnica de priorização "MoSCoW e tabela de priorização adicionada" | [Arthur Fernandes](https://github.com/arthurfernandesj) | [Letícia Lopes](https://github.com/leticialopes20) |
| `1.2` | 30/09/2025 | Atualização da tabela de priorização de requisitos | [Letícia Lopes](https://github.com/leticialopes20) | [Arthur Fernandes](https://github.com/arthurfernandesj) |
| `1.3` | 30/09/2025 | Atualização da tabela de priorização de requisitos com novos dados e finalização do documento | [Letícia Lopes](https://github.com/leticialopes20) | [Arthur Fernandes](https://github.com/arthurfernandesj) |