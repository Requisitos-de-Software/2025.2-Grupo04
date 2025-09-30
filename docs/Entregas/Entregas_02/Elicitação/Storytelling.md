# Storytelling

## Introdução

A técnica de **Storytelling**  se basela na utilzação de histórias em grupos de pessoas, incluindo organizações, como um metado da comunicação para que os envolvidos possam compartilhar conhecimento. Emprega-se o uso de técnicas de contagem de histórias que inspiram e motivam os pericipantes atravez de linguagens mais cotidianas, criando entretenimento durante o porcesso de construção. <a id="TEC1" href="#RP1">[1]</a>. Alguns dos beneficios dessa tecnica são: 

* Engajamento de Stakeholders.  
* Visão das necessidades do usuário
* Obter novas ideias.  
* Melhoria na comunicação entre a equipe e os usuários  
* Refinamento e contextualização dos requisitos  


## Metodologia

Foram utilizadas as [Personas](./Definicao_de_Personas.md) definidas anteriormente no projeto do aplicativo **ID Jovem**, para elaboração das histórias e contextos. Essas histórias foram essenciais para entendermos de verdade as necessidades e os anseios de cada persona. A partir desses contextos, conseguimos identificar e listar os requisitos que o aplicativo precisa atender para fazer a diferença na vida deles.


## Storytelling

### História 1

**Ana Clara**, 19 anos, estudante universitária, ama viajar e participar de eventos culturais, mas possui uma renda limitada.  
Ela utiliza o **ID Jovem** para garantir descontos em passagens de ônibus e acesso gratuito a eventos culturais.  

Porém, Ana já perdeu oportunidades por não conseguir verificar rapidamente se seu benefício estava válido.  
Ela deseja que o aplicativo seja simples, com **login rápido**, notificações automáticas sobre a validade do documento e a possibilidade de **baixar sua carteirinha offline**, para não depender de internet em suas viagens.  


---

### História 2

**João Pedro**, 24   anos, trabalhador informal, usa o benefício do ID Jovem para visitar sua família em outra cidade.  

Com a rotina corrida, João precisa de um aplicativo **confiável e estável**, que permita a compra de passagens diretamente pelo sistema ou redirecione para empresas de transporte parceiras.  
Ele valoriza principalmente a **segurança dos seus dados** e quer que o aplicativo seja **acessível em qualquer dispositivo**, já que alterna entre celular e computador.  

---

### História 3

**Camila Souza**, 23 anos, em busca de oportunidades no mercado de trabalho, gosta de frequentar museus, cinemas e shows.  
O ID Jovem é, para ela, uma ferramenta de inclusão cultural.  

Camila deseja que o aplicativo traga um **mapa interativo de eventos e estabelecimentos parceiros**, atualizado em tempo real. Além disso, gostaria de receber **recomendações personalizadas** com base em sua localização e interesses.  
Isso ajudaria Camila a se sentir mais conectada à cidade e aproveitar melhor os benefícios.  

---


## Lista de Requisitos Elicitados

| Identificador | Tipo | Requisito | Implementação |
| :-: | :-: | :- | :-: |
| ST01 | RF | O usuário deve realizar login com a conta gov.br. | Sim |
| ST02 | RF | O sistema deve validar automaticamente a elegibilidade do benefício. | Sim |
| ST03 | RF | O aplicativo deve permitir baixar a carteirinha para uso offline. | Sim |
| ST04 | RF | O sistema deve disponibilizar notificações sobre a expiração do benefício. | Não |
| ST05 | RF | O usuário deve poder consultar e reservar passagens diretamente no app ou via integração com empresas parceiras. | Não |
| ST06 | RF | O aplicativo deve fornecer mapa de eventos culturais e parceiros disponíveis. | Não |
| ST07 | RF | O sistema deve oferecer recomendações personalizadas de eventos conforme localização do usuário. | Não |
| ST08 | RF | O usuário deve conseguir verificar histórico de viagens realizadas com o ID Jovem. | Não |
| ST09 | RNF | O design deve ser acessível e responsivo em diferentes dispositivos. | Sim |
| ST10 | RNF | O sistema deve garantir segurança e integridade dos dados dos usuários. | Sim |


## Referências Bibliográficas


> <a id="QT1" href="#anchor_1">1.</a> SERRANO, M.; SERRANO, M. Requisitos – Aula 07. [S. l.], 2025. Material de aula (slide).



## Bibliografia


> <a id="QT1" href="#anchor_1">1.</a> Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. Autopublicação. ISBN: 978-65-00-19677-1. Cap 8.3: Cenários.

## Histórico de Versão
| Versão | Data | Descrição | Autor(es) | Data de revisão | Revisor(es) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| `1.0` | 29/09/2025 | Versão inicial da página de Storytelling para o ID Jovem | [Eduarda](https://github.com/eduardar0) | -- | -- |