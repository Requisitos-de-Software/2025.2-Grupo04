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

<p style="text-align: center; font-size: 12pt;"><strong>Tabela 2:</strong> Planilha de priorização - Técnica MoSCoW</p>

| Código | Origem | Descrição | Prioridade|Justificativa|
|--------|-----------|--------|-------|-------|
|[RF01](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf01)  |[ADD01](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Analise_de_Documentos/#ad01)  |O sistema deve permitir o cadastro do Jovem Beneficiário por meio do CPF.  |MUST| |
|[RF02](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf02) |[ADD02](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Analise_de_Documentos/#ad02), [BS01](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs01), [ST01](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Storytelling/#st01)  |O sistema deve fornecer mecanismos de autenticação e login via Gov.br. |MUST||
|[RF03](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf03) | [ADD03](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Analise_de_Documentos/#ad03), [IDJ01](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspeccao/#idj01), [BS04](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs04)  |O sistema deve permitir a geração e emissão da carteira digital ID Jovem.  |MUST||
|[RF04](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf04) |[ENT02](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/#ent02), [IDJ03](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspeccao/#idj03), [BS05](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs05)  |O sistema deve permitir a consulta de benefícios como transporte gratuito e meia-entrada em eventos.  |SHOULD| |
|[RF05](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf05)|[ADD04](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Analise_de_Documentos/#ad04), [IDJ02](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspeccao/#idj02)  |O sistema deve validar a carteira digital em estabelecimentos conveniados. |MUST||
|[RF06](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf06) | [ADD05](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Analise_de_Documentos/#ad05), [BS08](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs08), [IDJ04](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspeccao/#idj04)  |O sistema deve exibir uma seção de perguntas frequentes (FAQ) e suporte ao Jovem Beneficiário.  |COULD||
|[RF07](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf07) | [BS09](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs09), [IDJ08](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspeccao/#idj08)  | O sistema deve permitir integração com o CadÚnico para atualização automática de dados. |COULD||
|[RF08](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf08)  |[BS11](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs11), [ST04](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Storytelling/#st04), [IDJ11](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspeccao/#idj11), [ENT13](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/#ent13)  |O sistema deve emitir notificações sobre vencimento, renovação do benefício, novos parceiros e eventos de interesse.  |SHOULD||
|[RF09](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf09)  |[ST03](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Storytelling/#st03), [BS19](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs19)  |O sistema deve permitir o download da carteirinha para uso offline.  |COULD||
|[RF10](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf10)  |[BS10](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs10), [ST06](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Storytelling/#st06)  |O aplicativo deve disponibilizar informações sobre locais e parceiros que aceitam o benefício.  |SHOULD||
|[RF11](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf11)  |[ENT05](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/#ent05), [BS08](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs08), [IDJ05](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspeccao/#idj05)  |O sistema deve fornecer canal de suporte via chat, e-mail ou formulário de contato.  |SHOULD||
|[RF12](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf12)  | [ST08](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Storytelling/#st08), [ENT12](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/#ent12)  |O aplicativo deve permitir que o Jovem Beneficiário visualize o histórico de utilização dos benefícios.  |COULD||
|[RF13](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf13)  |[ADD07](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Analise_de_Documentos/#ad07), [BS07](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs07), [ENT16](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/#ent16)  |O sistema deve apresentar uma seção de "Vantagens e Parcerias" com novidades, divulgação sobre o programa e ofertas exclusivas.|COULD||
|[RF14](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf14)  |[ENT03](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/#ent03)  |O aplicativo deve permitir reserva e emissão de comprovantes de uso do benefício.  |COULD||
|[RF15](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf15)  | [ST02](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Storytelling/#st02)  |O sistema deve validar automaticamente a elegibilidade do Jovem Beneficiário ao benefício.  |MUST||
|[RF16](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf16)  | [BS21](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs21), [ST10](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Storytelling/#st10)  |O sistema deve permitir integração com o Gov.br e outros serviços governamentais.  |MUST||
|[RF17](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf17)  | [BS12](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs12)  |O aplicativo deve permitir compartilhar a carteirinha em PDF ou imagem.  |SHOULD||
|[RF18](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf18)  |[ENT04](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/#ent04)  |O sistema deve fornecer informações sobre pendências ou erros relacionados aos benefícios do usuário. |COULD||
|[RF19](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf19)  |[ENT06](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/#ent06)  |O sistema deve permitir que os usuários atualizem seu cadastro e definam preferências pessoais.  |SHOULD||
|[RF20](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf20)  |[ENT09](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/#ent09)  |	O sistema deve fornecer alertas sobre possíveis irregularidades no uso dos benefícios.  |COULD||
|[RF21](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf21)  |[ENT10](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/#ent10)  |O sistema deve possuir um mapa interativo para visualizar geograficamente parceiros e eventos.  |COULD||
|[RF22](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf22)  |[ENT11](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/#ent11)  |	O sistema deve apresentar uma agenda integrada de eventos com filtros de busca.  |COULD||
|[RF23](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf23)   |[ENT14](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/#ent14)  |O sistema deve fornecer um canal para denúncia ou feedback sobre estabelecimentos que recusam o benefício.  |COULD||
|[RF24](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf24)   |[ENT15](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/#ent15)  |O sistema deve permitir que o usuário favorite eventos e estabelecimentos para consulta rápida.  |COULD||
|[RF25](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf25)   |[ADD07](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Analise_de_Documentos/#ad07), [ENT16](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/#ent16)  |	O sistema deve permitir que o usuário recupere o acesso à conta por meio de verificação via e-mail, SMS ou Gov.br.  |MUST||
|[RF26](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf26)   |[BS09](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs09), [IDJ09](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspeccao/#idj09)  |	O aplicativo deve disponibilizar um tutorial interativo para orientar novos usuários sobre como utilizar o ID Jovem e seus benefícios.  |COULD||
|[RF27](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rf27)   |[BS10](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs10), [ENT18](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/#ent18)  |	O sistema deve permitir que o usuário avalie parceiros e estabelecimentos conveniados com notas e comentários.  |COULD||
|[RNF01](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf01)  |[ENT17](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/#ent17)  |O processo de login deve ser simples e com o menor número de etapas possível.  |MUST||
|[RNF02](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf01)  |[BS16](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs16), [IDJ09](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspeccao/#idj09), [ENT16](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/#ent16), [ENT20](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/#ent20), [ENT21](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/#ent21)  |A interface deve ser intuitiva, acessível, com layout claro e legível, mesmo para jovens com pouca experiência digital.  |MUST||
|[RNF03](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf01)  |[BS28](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs28)  |A emissão da carteira deve ocorrer em até 2 segundos após a solicitação.  |MUST||
|[RNF04](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf01)  |[IDJ06](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspeccao/#idj06)  |O aplicativo deve ser gratuito e compatível com Android e iOS.  |COULD||
|[RNF05](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf01)  |[BS22](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs22), [ENT19](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/#ent19)  |Os dados pessoais do Jovem Beneficiário devem ser protegidos com criptografia conforme a LGPD.  |MUST||
|[RNF06](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf01)  |[BS24](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs24)  | O aplicativo deve funcionar com baixo consumo de internet e ser acessível em regiões carentes. |SHOULD||
|[RNF07](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf01)  |[BS20](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs20), [IDJ09](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspeccao/#idj09)  |O aplicativo deve possuir recursos de acessibilidade (alto contraste, leitura de tela, voz e Libras).  |SHOULD||
|[RNF08](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf01)  |[BS27](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs27)  |O sistema deve garantir disponibilidade mínima de 99,5%.  |MUST||
|[RNF09](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf01)  |[ST09](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Storytelling/#st09)  |O design deve ser responsivo em diferentes tamanhos de tela e dispositivos.  |SHOULD||
|[RNF10](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf01)  |[BS24](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs24) |O tempo de carregamento das páginas do site oficial não deve exceder 3 segundos em conexões de internet de baixa velocidade.  |COULD||
|[RNF11](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf01)  | [IDJ08](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspeccao/#idj08)  |O aplicativo deve garantir que as informações sobre os benefícios estejam 100% sincronizadas com a base de dados oficial.  |MUST||
|[RNF12](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf01)  | [BS15](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs15), [BS23](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs23), [ST09](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Storytelling/#st09)  |O sistema deve ser compatível com as duas versões anteriores dos principais navegadores web e sistemas operacionais móveis.  |COULD||
|[RNF13](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf01)  |[BS16](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs16), [ENT17](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/#ent17)  |	A navegação entre as seções do site e do aplicativo deve ser consistente e previsível para o jovem beneficiário.  |COULD||
|[RNF14](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf01)  | [BS26](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs26)  |O aplicativo deve apresentar um feedback visual e sonoro claro para cada interação do jovem beneficiário.  |SHOULD||
|[RNF15](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf01)  |[BS27](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs27)  |O sistema deve ter um tempo máximo de inatividade de 2 horas por mês, fora das janelas de manutenção programada.	  |OUT|A disponibilidade de 99,5% (RNF08) já estabelece um padrão adequado.|COULD||
|[RNF16](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf01)  |[BS28](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs28)  |O tempo de resposta para validação da carteirinha (QR Code) não deve exceder 2 segundos.  |MUST||
|[RNF17](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf01)  |[BS29](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Brainstorming/#bs29)  |	A equipe de desenvolvimento deve disponibilizar atualizações de segurança e correções de bugs em um ciclo de, no máximo, 3 meses.  |COULD||
|[RNF18](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf01)  |[IDJ18](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspeccao/#idj18)  |O aplicativo deve permitir que o jovem beneficiário personalize o tamanho da fonte e o esquema de cores para melhorar a legibilidade.|COULD||
|[RNF19](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf01)  | [IDJ19](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspeccao/#idj19)  |O sistema deve registrar todas as tentativas de validação da carteira, bem-sucedidas ou não, para fins de auditoria.  |COULD||
|[RNF20](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Requisitos_Elicitados/#rnf01)  | [IDJ20](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Introspeccao/#idj20)  |A consulta à elegibilidade do CadÚnico deve retornar o resultado em no máximo 3 segundos.  |COULD||

<p style="text-align: center; font-size: 10pt;">Fonte: <a href="https://github.com/leticialopes20">Letícia Lopes</a>, <a href="https://github.com/arthurfernandesj">Arthur Fernandes</a>, 2025.</p>


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

## Agrecimentos

Queremos agradecer ao [Chat GPT](), ferramenta de Inteligência Artificial Generativa, pelo apoio durante o desenvolvimento deste projeto ID Jovem. Sua ajuda foi essencial na revisão de textos, na organização das ideias e na pesquisa de conteúdos complementares que contribuíram para deixar nossa documentação mais clara e completa.

De acordo com o Código de Conduta da Sociedade Brasileira de Computação (SBC), destacamos que a ferramenta foi utilizada apenas como apoio técnico e linguístico.
Todo o conteúdo apresentado é de autoria do Grupo 04, que assume total responsabilidade por sua originalidade e precisão.

## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :--: | :--: | :-- | :-- | :-- |
| `1.0` | 28/09/2025 | Criação do documento com a descrição da técnica de priorização "MoSCoW" | [Danilo Melo](https://github.com/EngDann) | [Arthur Fernandes](https://github.com/arthurfernandesj) |
| `1.1` | 29/09/2025 | Atualização da técnica de priorização "MoSCoW e tabela de priorização adicionada" | [Arthur Fernandes](https://github.com/arthurfernandesj), [Letícia Lopes](https://github.com/leticialopes20) |[Breno](https://github.com/BrenoLteixeira) |
| `1.2` | 30/09/2025 | Atualização da tabela de priorização de requisitos | [Letícia Lopes](https://github.com/leticialopes20) | [Arthur Fernandes](https://github.com/arthurfernandesj) |
| `1.3` | 30/09/2025 | Atualização da tabela de priorização de requisitos com novos dados e finalização do documento | [Letícia Lopes](https://github.com/leticialopes20) | [Arthur Fernandes](https://github.com/arthurfernandesj) |
