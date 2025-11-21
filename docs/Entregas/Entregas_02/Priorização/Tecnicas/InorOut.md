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

* Mediadora: Responsável por conduzir a sessão de aplicação da técnica;
* Membro apoiadora de fundamentação teórica: Responsável por garantir a aplicação correta da técnica seguindo embasamento teórico claro.
* Usuária: Responsável por realizar a classificação dos requisitos de acordo com a técnica;

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
      <td>Membro Apoiadora</td>
      <td>Eduarda</td>
      <td>29/09/2025</td>
      <td>12:30</td>
      <td>UnB Campus Gama</td>
    </tr>
    <tr>
      <td>Membro Apoiadora</td>
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

**Legenda:**

* RFx: Requisito Funcional número x
* RNFx: Requisito Não Funcional número x
* ENTx: Entrevista número x 
* BSx: Brainstorming número x
* ISx: Introspecção número x
* STx: Storytelling número x
* IDJx: Introspecção número x

<p style="text-align: center; font-size: 12pt;"><strong>Tabela 2:</strong> Planilha de priorização - Técnica In or Out</p>

| Código | Origem | Descrição | IN or OUT | Justificativa|
|--------|-----------|--------|-------|-------|
|[RF01](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf01)  |[ADD01](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Analise_de_Documentos/#ad01)  |O sistema deve permitir o cadastro do Jovem Beneficiário por meio do CPF.  |  |  |  
|[RF02](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf02) |[ADD02](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Analise_de_Documentos/#ad02), [BS01](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs01), [ST01](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Storytelling/#st01)  |O sistema deve fornecer mecanismos de autenticação e login via Gov.br.  |  |  |  
|[RF03](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf03) | [ADD03](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Analise_de_Documentos/#ad03), [IDJ01](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspeccao/#idj01), [BS04](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs04)  |O sistema deve permitir a geração e emissão da carteira digital ID Jovem.  |  |  |  
|[RF04](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf04) |[ENT02](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/#ent02), [IDJ03](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspeccao/#idj03), [BS05](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs05)  |O sistema deve permitir a consulta de benefícios como transporte gratuito e meia-entrada em eventos.  |  |  |  
|[RF05](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf05)|[ADD04](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Analise_de_Documentos/#ad04), [IDJ02](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspeccao/#idj02)  |O sistema deve validar a carteira digital em estabelecimentos conveniados.  |  |  |  
|[RF06](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf06) | [ADD05](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Analise_de_Documentos/#ad05), [BS08](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs08), [IDJ04](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspeccao/#idj04)  |O sistema deve exibir uma seção de perguntas frequentes (FAQ) e suporte ao Jovem Beneficiário.  |  |  |  
|[RF07](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf07) | [BS09](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs09), [IDJ08](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspeccao/#idj08)  | O sistema deve permitir integração com o CadÚnico para atualização automática de dados. |  |  |  
|[RF08](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf08)  |[BS11](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs11), [ST04](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Storytelling/#st04), [IDJ11](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspeccao/#idj11), [ENT13](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/#ent13)  |O sistema deve emitir notificações sobre vencimento, renovação do benefício, novos parceiros e eventos de interesse.  |  |  |  
|[RF09](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf09)  |[ST03](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Storytelling/#st03), [BS19](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs19)  |O sistema deve permitir o download da carteirinha para uso offline.  |  |  |  
|[RF10](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf10)  |[BS10](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs10), [ST06](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Storytelling/#st06)  |O aplicativo deve disponibilizar informações sobre locais e parceiros que aceitam o benefício.  |  |  |  
|[RF11](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf11)  |[ENT05](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/#ent05), [BS08](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs08), [IDJ05](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspeccao/#idj05)  |O sistema deve fornecer canal de suporte via chat, e-mail ou formulário de contato.  |  |  |  
|[RF12](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf12)  | [ST08](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Storytelling/#st08), [ENT12](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/#ent12)  |O aplicativo deve permitir que o Jovem Beneficiário visualize o histórico de utilização dos benefícios.  |  |  |  
|[RF13](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf13)  |[ADD07](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Analise_de_Documentos/#ad07), [BS07](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs07), [ENT16](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/#ent16)  |O sistema deve apresentar uma seção de "Vantagens e Parcerias" com novidades, divulgação sobre o programa e ofertas exclusivas.|  |  |  
|[RF14](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf14)  |[ENT03](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/#ent03)  |O aplicativo deve permitir reserva e emissão de comprovantes de uso do benefício.  |  |  |  
|[RF15](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf15)  | [ST02](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Storytelling/#st02)  |O sistema deve validar automaticamente a elegibilidade do Jovem Beneficiário ao benefício.  |  |  |  
|[RF16](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf16)  | [BS21](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs21), [ST10](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Storytelling/#st10)  |O sistema deve permitir integração com o Gov.br e outros serviços governamentais.  |  |  |  
|[RF17](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf17)  | [BS12](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs12)  |O aplicativo deve permitir compartilhar a carteirinha em PDF ou imagem.  |  |  |  
|[RF18](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf18)  |[ENT04](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/#ent04)  |O sistema deve fornecer informações sobre pendências ou erros relacionados aos benefícios do usuário.  |  |  |  
|[RF19](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf19)  |[ENT06](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/#ent06)  |O sistema deve permitir que os usuários atualizem seu cadastro e definam preferências pessoais.  |  |  |  
|[RF20](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf20)  |[ENT09](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/#ent09)  |	O sistema deve fornecer alertas sobre possíveis irregularidades no uso dos benefícios.  |  |  |  
|[RF21](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf21)  |[ENT10](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/#ent10)  |O sistema deve possuir um mapa interativo para visualizar geograficamente parceiros e eventos.  |  |  |  
|[RF22](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf22)  |[ENT11](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/#ent11)  |	O sistema deve apresentar uma agenda integrada de eventos com filtros de busca.  |  |  |  
|[RF23](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf23)   |[ENT14](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/#ent14)  |O sistema deve fornecer um canal para denúncia ou feedback sobre estabelecimentos que recusam o benefício.  |  |  |  
|[RF24](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf24)   |[ENT15](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/#ent15)  |O sistema deve permitir que o usuário favorite eventos e estabelecimentos para consulta rápida.  |  |  |  
|[RF25](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf25)   |[ADD07](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Analise_de_Documentos/#ad07), [ENT16](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/#ent16)  |	O sistema deve permitir que o usuário recupere o acesso à conta por meio de verificação via e-mail, SMS ou Gov.br.  |  |  |  
|[RF26](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf26)   |[BS09](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs09), [IDJ09](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspeccao/#idj09)  |	O aplicativo deve disponibilizar um tutorial interativo para orientar novos usuários sobre como utilizar o ID Jovem e seus benefícios.  |  |  |  
|[RF27](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf27)   |[BS10](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs10), [ENT18](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/#ent18)  |	O sistema deve permitir que o usuário avalie parceiros e estabelecimentos conveniados com notas e comentários.  |  |  |  
|[RNF01](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf01)  |[ENT17](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/#ent17)  |O processo de login deve ser simples e com o menor número de etapas possível.  |  |  |  
|[RNF02](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf01)  |[BS16](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs16), [IDJ09](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspeccao/#idj09), [ENT16](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/#ent16), [ENT20](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/#ent20), [ENT21](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/#ent21)  |A interface deve ser intuitiva, acessível, com layout claro e legível, mesmo para jovens com pouca experiência digital.  |  |  |  
|[RNF03](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf01)  |[BS28](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs28)  |A emissão da carteira deve ocorrer em até 2 segundos após a solicitação.  |  |  |  
|[RNF04](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf01)  |[IDJ06](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspeccao/#idj06)  |O aplicativo deve ser gratuito e compatível com Android e iOS.  |  |  |  
|[RNF05](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf01)  |[BS22](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs22), [ENT19](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/#ent19)  |Os dados pessoais do Jovem Beneficiário devem ser protegidos com criptografia conforme a LGPD.  |  |  |  
|[RNF06](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf01)  |[BS24](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs24)  | O aplicativo deve funcionar com baixo consumo de internet e ser acessível em regiões carentes. |  |  |  
|[RNF07](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf01)  |[BS20](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs20), [IDJ09](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspeccao/#idj09)  |O aplicativo deve possuir recursos de acessibilidade (alto contraste, leitura de tela, voz e Libras).  |  |  |  
|[RNF08](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf01)  |[BS27](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs27)  |O sistema deve garantir disponibilidade mínima de 99,5%.  |  |  |  
|[RNF09](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf01)  |[ST09](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Storytelling/#st09)  |O design deve ser responsivo em diferentes tamanhos de tela e dispositivos.  |  |  |  
|[RNF10](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf01)  |[BS24](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs24) |O tempo de carregamento das páginas do site oficial não deve exceder 3 segundos em conexões de internet de baixa velocidade.  |  |  |  
|[RNF11](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf01)  | [IDJ08](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspeccao/#idj08)  |O aplicativo deve garantir que as informações sobre os benefícios estejam 100% sincronizadas com a base de dados oficial.  |  |  |  
|[RNF12](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf01)  | [BS15](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs15), [BS23](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs23), [ST09](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Storytelling/#st09)  |O sistema deve ser compatível com as duas versões anteriores dos principais navegadores web e sistemas operacionais móveis.  |  |  |  
|[RNF13](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf01)  |[BS16](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs16), [ENT17](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/#ent17)  |	A navegação entre as seções do site e do aplicativo deve ser consistente e previsível para o jovem beneficiário.  |  |  |  
|[RNF14](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf01)  | [BS26](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs26)  |O aplicativo deve apresentar um feedback visual e sonoro claro para cada interação do jovem beneficiário.  |  |  |  
|[RNF15](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf01)  |[BS27](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs27)  |O sistema deve ter um tempo máximo de inatividade de 2 horas por mês, fora das janelas de manutenção programada.	  |  |  |  
|[RNF16](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf01)  |[BS28](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs28)  |O tempo de resposta para validação da carteirinha (QR Code) não deve exceder 2 segundos.  |  |  |  
|[RNF17](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf01)  |[BS29](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs29)  |	A equipe de desenvolvimento deve disponibilizar atualizações de segurança e correções de bugs em um ciclo de, no máximo, 3 meses.  |  |  |  
|[RNF18](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf01)  |[IDJ18](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspeccao/#idj18)  |	A equipe de desenvolvimento deve disponibilizar atualizações de segurança e correções de bugs em um ciclo de, no máximo, 3 meses.  |  |  |  
|[RNF19](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf01)  | [IDJ19](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspeccao/#idj19)  |O sistema deve registrar todas as tentativas de validação da carteira, bem-sucedidas ou não, para fins de auditoria.  |  |  |  
|[RNF20](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf01)  | [IDJ20](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspeccao/#idj20)  |A consulta à elegibilidade do CadÚnico deve retornar o resultado em no máximo 3 segundos.  |  |  |  

<p style="text-align: center; font-size: 10pt;">Fonte: <a href="https://github.com/leticialopes20">Letícia Lopes</a>, 2025.</p>


## Gravação

<div align="center">

<p style="text-align: center"><a href="https://youtu.be/ywmlErJ7bdA" target="_blank"><b>Vídeo 1:</b> Técnica de Priorização - In or Out</a></p>

<iframe width="560" height="315" src="https://www.youtube.com/embed/ywmlErJ7bdA" title="Sessão de Técnica de Priorização - In or Out" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
<p style="text-align: center; font-size: 10pt;">Fonte: <a href="https://github.com/GiovanaFontesS">Giovana Fontes</a>, 2025.</p>

</div>

## Referências Bibliográficas

><p><a id="QT1" href="#anchor_intro_serrano">1.</a> SERRANO, Milene; SERRANO, Maurício. <b>Requisitos – Aula 07</b>. Gama, DF: Universidade de Brasília, [s.d.]. Material de aula.</p>
><p><a id="QT2" href="#anchor_intro_wiegers">2.</a> WIEGERS, Karl E. **Software Requirements**. 2. ed. Redmond, WA: Microsoft Press, 2003.</p>

## Bibliografia

> SERRANO, Milene; SERRANO, Maurício. **Requisitos – Aula 07**. Gama, DF: Universidade de Brasília, [s.d.]. Material de aula.

## Agrecimentos

Queremos agradecer ao [Chat GPT](), ferramenta de Inteligência Artificial Generativa, pelo apoio durante o desenvolvimento deste projeto ID Jovem. Sua ajuda foi essencial na revisão de textos, na organização das ideias e na pesquisa de conteúdos complementares que contribuíram para deixar nossa documentação mais clara e completa.

De acordo com o Código de Conduta da Sociedade Brasileira de Computação (SBC), destacamos que a ferramenta foi utilizada apenas como apoio técnico e linguístico.
Todo o conteúdo apresentado é de autoria do Grupo 04, que assume total responsabilidade por sua originalidade e precisão.

## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :--: | :--: | :-- | :-- | :-- |
| `1.0` | 28/09/2025 | Criação do documento com a descrição da técnica de priorização " In or Out" | [Letícia Lopes](https://github.com/leticialopes20) | [Giovana Fontes](https://github.com/GiovanaFontesS) |
| `1.1` | 30/09/2025 | Criação da tabela de priorização e finalização do documento | [Letícia Lopes](https://github.com/leticialopes20) | [Arthur Fernandes](https://github.com/arthurfernandesj) |
| `1.2`  | 10/10/2025 | Arrumando citação das Referências | [Breno](https://github.com/BrenoLteixeira) | [Letícia Lopes](https://github.com/leticialopes20) |
| `1.3` | 20/11/2025 | Atualização da tabela de priorização de requisitos com novos dados| [Letícia Lopes](https://github.com/leticialopes20) | [Arthur Fernandes](https://github.com/arthurfernandesj) |