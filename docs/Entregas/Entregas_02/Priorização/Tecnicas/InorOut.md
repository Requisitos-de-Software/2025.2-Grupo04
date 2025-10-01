# **Técnica In or Out**

A técnica **In or Out** é um método de priorização direto e binário, utilizado para classificar requisitos de forma rápida e eficiente. Seu objetivo principal é separar os itens essenciais para o produto daqueles que podem ser considerados secundários ou desnecessários.

#### **O que é?**

É um método de categorização simples onde cada requisito é classificado como "In" (dentro do escopo) ou "Out" (fora do escopo). Esta técnica é especialmente útil nas fases iniciais do projeto, quando é necessário tomar decisões rápidas sobre o que será ou não desenvolvido. A simplicidade do método o torna ideal para situações onde o tempo é limitado e a equipe precisa de clareza imediata sobre o escopo básico do produto.

#### **Como se usa?**

O processo é extremamente straightforward e pode ser realizado em uma única sessão de trabalho com os principais stakeholders:

1.  **Listar Requisitos:** Todos os requisitos candidatos são listados em cartões, post-its ou em uma planilha compartilhada.
2.  **Classificação Binária:** Para cada requisito, pergunta-se: "Este item é absolutamente essencial para a primeira versão do produto?"
3.  **Decisão In/Out:**
    - **In:** Requisitos considerados fundamentais para o produto funcionar ou entregar valor mínimo ao usuário.
    - **Out:** Requisitos que, embora possam ser desejáveis, não são críticos para o lançamento inicial. Estes podem ser reconsiderados para versões futuras.
4.  **Validação:** A lista final de itens "In" forma o escopo mínimo viável (MVP) ou a base para priorizações mais detalhadas subsequentes.

#### **Vantagens**

-   **Extrema simplicidade e velocidade:** A classificação binária torna o processo muito ágil.
-   **Clareza imediata:** Gera uma divisão clara e compreensível para toda a equipe sobre o que é essencial.
-   **Ideal para definir MVP:** Perfeita para estabelecer o escopo mínimo de um produto ou de uma release inicial.
-   **Ótimo ponto de partida:** Serve como um primeiro filtro antes da aplicação de técnicas de priorização mais refinadas (como MoSCoW ou First Things First).

#### **Desvantagens**

-   **Falta de nuance:** Não considera o valor relativo, custo, risco ou esforço entre os requisitos classificados como "In".
-   **Pode ser muito radical:** A natureza binária pode forçar a exclusão de funcionalidades valiosas que não são "absolutamente essenciais", mas que teriam um alto retorno com baixo custo.
-   **Depende do bom senso:** A qualidade do resultado depende muito do julgamento e da experiência dos participantes.

## Metodologia

Durante a aplicação da técnica **In or Out**, os membros da equipe de requisitos analisaram cada funcionalidade proposta com base nos seguintes critérios:

1. **Valor essencial para o usuário final:** o requisito é crítico para a experiência do usuário?
2. **Obrigatoriedade legal ou contratual:** o requisito é exigido por regulação ou contrato?
3. **Impacto direto na funcionalidade central do sistema:** sua ausência compromete o uso do sistema?

Caso a resposta fosse afirmativa para qualquer um dos pontos acima, o requisito foi classificado como **IN**. Caso contrário, foi considerado **OUT**.

Requisitos classificados como **OUT** foram justificados com base em sua não essencialidade ou por se tratarem de melhorias de experiência, que podem ser postergadas.

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
</div>

<font size="3"><p>Fonte:[Letícia Lopes](https://github.com/leticialopes20) </p></font>

# Requisitos priorizados

**Legendas:**

* RFx: Requisito Funcional número x
* RNFx: Requisito Não Funcional número x

<font size="3"><p style="text-align: center">Tabela 2: Planilha de priorização - Técnica In or Out</p></font>

<a name="Req"></a>

| Código | Origem | Descrição | Prioridade | Justificativa |
|--------|--------|-----------|------------|---------------|
| **RNF-01** | USA-01 | O processo de login deve ser simplificado e otimizado para minimizar o número de passos e a carga cognitiva do usuário | IN | Essencial para garantir a usabilidade básica do aplicativo |
| **RNF-02** | USA-02 | A interface do aplicativo deve ser intuitiva, com navegação clara, textos legíveis e design acessível | IN | Fundamental para a experiência do usuário e adoção do app |
| **RNF-03** | PER-01 | A geração e exibição do documento digital devem ser concluídas em no máximo 5 segundos | IN | Performance crítica para a funcionalidade principal |
| **RNF-04** | SEG-01 | Os dados pessoais devem ser armazenados e transmitidos utilizando criptografia forte | IN | Requisito de segurança obrigatório para dados pessoais |
| **RNF-05** | CON-01 | O aplicativo deve manter uma disponibilidade de serviço de 99.5% | IN | Confiabilidade essencial para serviço governamental |
| **RNF-06** | POR-01 | O aplicativo deve ser compatível com as duas versões mais recentes do Android e iOS | IN | Compatibilidade básica para alcançar o público-alvo |
| **RF-01** | CAD-01 | O sistema deve permitir o cadastro do usuário por meio do CPF | OUT | Substituído pelo login gov.br (RF-09) |
| **RF-02** | AUT-01 | O sistema deve fornecer mecanismos de autenticação e login para o usuário | IN | Segurança básica e controle de acesso |
| **RF-03** | EMI-01 | O sistema deve permitir a geração e emissão da carteira digital ID Jovem | IN | Funcionalidade principal do aplicativo |
| **RF-04** | BEN-01 | O sistema deve permitir a consulta de benefícios como transporte gratuito e acesso a eventos | IN | Valor principal para o usuário final |
| **RF-05** | VAL-01 | O sistema deve permitir a validação da carteira por estabelecimentos conveniados | IN | Essencial para a utilidade do programa |
| **RF-06** | FAQ-01 | O sistema deve disponibilizar uma seção de perguntas frequentes e informações de atendimento | OUT | Pode ser implementado em versão posterior |
| **RF-07** | SUP-01 | O sistema deve prover um canal de comunicação direto para suporte ao usuário | IN | Suporte essencial para usuários |
| **RF-08** | COM-01 | O sistema deve apresentar uma seção de "Novidades e Divulgação" | OUT | Não essencial para MVP |
| **RF-09** | BS-01 | O usuário deve realizar o login com o acesso unificado do gov.br | IN | Integração essencial com governo |
| **RF-10** | BS-02 | O usuário deve aceitar um termo de uso em seu primeiro acesso | IN | Requisito legal e de segurança |
| **RF-11** | BS-03 | O usuário deve conseguir consultar se está dentro dos critérios para ter direito ao ID Jovem | IN | Funcionalidade central de elegibilidade |
| **RF-12** | BS-04 | O usuário deve poder emitir sua carteirinha digital do ID Jovem | IN | Funcionalidade principal do sistema |
| **RF-13** | BS-05 | O usuário deve conseguir visualizar os benefícios disponíveis | IN | Valor direto para o usuário |
| **RF-14** | BS-06 | O usuário deve poder verificar a validade da sua carteirinha | IN | Informação essencial para uso |
| **RF-15** | BS-07 | O usuário deve ter acesso a um guia/tutorial explicativo | OUT | Pode ser simplificado na primeira versão |
| **RF-16** | BS-08 | O usuário deve ter acesso a perguntas frequentes e suporte | IN | Suporte básico necessário |
| **RF-17** | BS-09 | O aplicativo deve permitir atualização automática dos dados via CadÚnico | IN | Atualização automática evita retrabalho |
| **RF-18** | BS-10 | O usuário deve conseguir acessar informações sobre locais onde o ID Jovem é aceito | IN | Informação prática essencial |
| **RF-19** | BS-11 | O aplicativo deve oferecer notificações sobre vencimento e renovação | IN | Funcionalidade importante para usuário |
| **RF-20** | BS-12 | O usuário deve poder compartilhar a carteirinha digital em PDF ou imagem | IN | Funcionalidade importante para uso |
| **RF-21** | BS-13 | O sistema deve validar em tempo real a autenticidade da carteirinha | IN | Prevenção de fraudes essencial |
| **RF-22** | BS-14 | O aplicativo deve oferecer processo de onboarding adaptado | IN | Melhora experiência de primeiro uso |
| **RF-23** | INT-01 | O sistema deve permitir emissão da carteira com NIS, nome completo, data nascimento e nome da mãe | IN | Dados essenciais para identificação |
| **RF-24** | INT-02 | O sistema deve permitir que estabelecimentos validem a autenticidade da carteira | IN | Funcionalidade crítica para estabelecimentos |
| **RF-25** | INT-03 | O sistema deve exibir claramente os benefícios do programa | IN | Comunicação clara do valor oferecido |
| **RF-26** | INT-04 | O sistema deve fornecer uma seção de "Dúvidas Frequentes" | IN | Suporte básico necessário |
| **RNF-07** | BS-01 | O aplicativo deve ser leve e compatível com diferentes modelos de smartphones | IN | Acessibilidade para público diverso |
| **RNF-08** | BS-02 | O aplicativo deve ser intuitivo, com ícones e textos de fácil compreensão | IN | Usabilidade básica necessária |
| **RNF-09** | BS-03 | O aplicativo deve enviar notificações sobre prazos e eventos próximos | OUT | Funcionalidade secundária |
| **RNF-10** | BS-04 | O aplicativo deve organizar os menus de forma clara e acessível | IN | Navegação básica essencial |
| **RNF-11** | BS-05 | O aplicativo deve garantir funcionamento offline para exibição da carteirinha | IN | Crítico para situações sem internet |
| **RNF-12** | BS-06 | O aplicativo deve oferecer recursos de acessibilidade | IN | Requisito de inclusão importante |
| **RNF-13** | BS-07 | O sistema deve integrar-se com o CadÚnico e serviços digitais do governo | IN | Integração central do sistema |
| **RNF-14** | BS-08 | O aplicativo deve proteger os dados em conformidade com a LGPD | IN | Conformidade legal obrigatória |
| **RNF-15** | BS-09 | O aplicativo deve ser compatível com Android e iOS | IN | Alcance máximo do público-alvo |
| **RNF-16** | BS-10 | O aplicativo deve funcionar com baixo consumo de internet | IN | Otimização para realidade brasileira |
| **RNF-17** | BS-11 | O aplicativo deve estar disponível em português e suporte em outros idiomas | IN | Acessibilidade linguística importante |
| **RNF-18** | INT-01 | O sistema deve ser gratuito para o cidadão | IN | Princípio fundamental do programa |
| **RNF-19** | INT-02 | O sistema deve ser compatível com Android, iOS e navegadores web | IN | Multiplataforma amplia acesso |
| **RNF-20** | INT-03 | O sistema deve proteger os dados pessoais conforme leis vigentes | IN | Conformidade legal essencial |
| **RNF-21** | INT-04 | O sistema deve conectar à base do CadÚnico para verificar elegibilidade | IN | Funcionalidade central do sistema |
| **RI-01** | RI-01 | A interface deve ser intuitiva e acessível | IN | Usabilidade básica necessária |
| **RI-02** | RI-02 | A carteira virtual deve conter QR Code para validação rápida | IN | Método prático de validação |
| **RI-03** | RI-03 | O sistema deve enviar notificações sobre vencimento | IN | Lembretes importantes para usuário |
| **RR-01** | RR-01 | Risco de dados desatualizados no CadÚnico | IN | Risco que precisa ser mitigado |
| **RR-02** | RR-02 | Risco de indisponibilidade do serviço de consulta ao CadÚnico | IN | Contingência necessária |
| **RR-03** | RR-03 | Risco de empresas recusarem aceitar o benefício | IN | Risco operacional importante |
| **RT-01** | RT-01 | Teste de emissão com diferentes perfis de jovens | IN | Garantia de qualidade essencial |
| **RT-02** | RT-02 | Teste de validação por estabelecimentos comerciais | IN | Validação da funcionalidade principal |
| **RT-03** | RT-03 | Testes de usabilidade com jovens de 15 a 29 anos | IN | Validação com público-alvo crítico |

<p font-size: 10pt;>Fonte: <a href="https://github.com/leticialopes20"><i>Letícia Lopes</i></span></a></p>

## Gravação

<div align="center">

<p style="text-align: center"><a href="https://youtu.be/ywmlErJ7bdA" target="_blank"><b>Vídeo 1:</b> Técnica de Priorização - In or Out</a></p>

<iframe width="560" height="315" src="https://www.youtube.com/embed/ywmlErJ7bdA" title="Sessão de Técnica de Priorização - In or Out" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/GiovanaFontesS">Giovana Fontes</a>, 2025</p></font>

</div>

##  Referências Bibliográficas

> SERRANO, Milene; SERRANO, Maurício. **Requisitos – Aula 07**. Gama, DF: Universidade de Brasília, [s.d.]. Material de aula.

> WIEGERS, Karl E. **Software Requirements**. 2. ed. Redmond, WA: Microsoft Press, 2003.

##  Histórico de Versões

| Versão | Data       | Descrição                                                                            | Autor(es)                                 | Revisor(es) |
| ------ | ---------- | ------------------------------------------------------------------------------------ | ----------------------------------------- | ----------- |
| `1.0`  | 28/09/2025 | Criação do documento com a descrição da técnica de priorização " In or Out" | [Danilo Melo](https://github.com/EngDann) |  [Letícia Lopes] (https://github.com/leticialopes20)           |
| `1.1`  | 30/09/2025 | Atualização da tabela de priorização e finalização do documento| [Letícia Lopes](https://github.com/leticialopes20) |  [Arthur Fernandes](https://github.com/arthurfernandesj)                |