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


| ID   | Requisito                        | Descrição                                                                 | Tipo           | Classificação |
|:----:|----------------------------------|---------------------------------------------------------------------------|----------------|---------------|
| RF01 | Cadastro                         | O sistema deve permitir o cadastro do jovem com validação automática do NIS| Funcional      | Must          |
| RF02 | Login                            | O sistema deve permitir login seguro com CPF e senha                       | Funcional      | Must          |
| RF03 | Emissão de cartão digital        | O sistema deve emitir o cartão ID Jovem em formato digital com QR Code     | Funcional      | Must          |
| RF04 | Validação de Benefício           | O sistema deve validar automaticamente se o jovem atende aos critérios     | Funcional      | Must          |
| RNF01| Acessibilidade                   | A aplicação deve ser acessível a usuários com deficiência                  | Não Funcional  | Must          |
| RNF02| Compatibilidade                  | O sistema deve ser suportado nos principais sistemas mobile                | Não Funcional  | Should        |
| RF05 | Histórico de uso                 | O sistema deve disponibilizar histórico de utilizações do benefício        | Funcional      | Should        |
| RF06 | FAQ                              | O sistema deve disponibilizar perguntas frequentes                         | Funcional      | Should        |
| RNF03| Facilidade de uso                | A interface deve ser intuitiva e de fácil entendimento                     | Não Funcional  | Should        |
| RF07 | Integração com carteiras digitais| O cartão ID Jovem deve poder ser adicionado ao Google Wallet / Apple Pay   | Funcional      | Could         |
| RF08 | Notificações                     | O sistema pode enviar notificações sobre atualizações e lembretes          | Funcional      | Could         |
| RF09 | Personalização                   | O sistema pode permitir personalização de cores e temas                    | Funcional      | Could         |
| RF10 | Eventos e promoções culturais    | O sistema pode sugerir eventos culturais disponíveis na região do jovem    | Funcional      | Won’t         |

**Fontes:** [Arthur Fernandes](https://github.com/arthurfernandesj), 2025  
*Tabela 1 – Priorização dos requisitos do ID Jovem com a técnica MoSCoW*  

---

## Histórico de Versões

| Versão |    Data    |      Descrição       |                        Autor(es)                        |                       Revisor(es)                       |
| :----: | :--------: | :------------------: | :-----------------------------------------------------: | :-----------------------------------------------------: |
| `1.0`  | 28/09/2025 | Criação do documento com a descrição da técnica de priorização "MoSCoW" | [Danilo Melo](https://github.com/EngDann) |  [ Arthur Fernandes](https://github.com/arthurfernandesj)|
| `1.1`  | 29/09/2025 | Atualização da técnica de priorização "MoSCoW e tabela de priorização adicionada" | [Arthur Fernandes](https://github.com/arthurfernandesj) |  [](https://github.com/)|