# Perfil de Usuário

## Introdução
A construção de um perfil de usuário é uma etapa fundamental para compreender quem são os indivíduos que irão interagir com o sistema e quais necessidades devem ser atendidas ao longo do desenvolvimento. Essa atividade consiste em identificar e descrever detalhadamente características relevantes do público-alvo, como faixa etária, nível de instrução, experiência prévia, objetivos e desafios enfrentados no contexto de uso. Trata-se de um processo essencial da Engenharia de Requisitos, pois fornece subsídios para decisões de projeto mais assertivas e garante que o sistema seja alinhado às demandas reais dos usuários [BARBOSA; SILVA, 2011](#barbosa2011).


Este documento tem como objetivo sintetizar informações coletadas por meio de fontes formais e dados empíricos, permitindo a elaboração de um perfil de usuário que ultrapassa aspectos puramente demográficos. Busca-se compreender motivações, expectativas e comportamentos que influenciam diretamente a interação com a aplicação, contribuindo para o desenvolvimento de uma solução mais eficaz, centrada no usuário e adequada ao seu contexto de uso.

<small><em>Revisado por [Chat GPT](https://chatgpt.com/), em 21 de Novembro 2025</em></small>



## Metodologia

Para a elaboração do perfil de usuário, foram empregadas duas técnicas de elicitação de requisitos: [Análise de Documentos](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Analise_de_Documentos/) e [Entrevistas](https://requisitos-de-software.github.io/2025.2-Grupo04/Entregas/Entregas_02/Elicitacao/Entrevista/).  
A Análise de Documentos concentrou-se em materiais oficiais e fontes institucionais, permitindo identificar de forma precisa o público-alvo formal e as diretrizes que orientam o sistema.

Complementarmente, foram conduzidas entrevistas com usuários reais, com o objetivo de obter dados qualitativos sobre seu comportamento, motivações, expectativas e dificuldades no uso da aplicação.

A integração entre as duas técnicas possibilitou confrontar informações documentais com o contexto de uso prático, resultando em uma compreensão mais completa e confiável sobre quem são os usuários e como interagem com o sistema.



## Vantagens da Metodologia

**Profundidade Qualitativa:** As entrevistas oferecem insights sobre experiências, necessidades implícitas e frustrações dos usuários, aspectos que dificilmente emergem na documentação.  
**Base Estruturada:** A análise de documentos fornece um panorama oficial e consistente, garantindo que o perfil produzido esteja alinhado às normas e objetivos do sistema.  
**Validação Cruzada:** A comparação entre dados formais e relatos reais permite identificar possíveis divergências e ajustar o perfil conforme o uso concreto da aplicação.  
**Compreensão Ampliada:** A combinação das técnicas possibilita compreender não apenas *quem* são os usuários, mas também *como* e *por que* utilizam o sistema em seu cotidiano.



## Desvantagens da Metodologia

**Amostra Reduzida:** Entrevistas costumam envolver poucos participantes, o que pode limitar a representação estatística do público total.  
**Possível Desatualização:** Documentos oficiais podem não refletir transformações recentes nos hábitos ou necessidades dos usuários.  
**Influência de Viés:** As respostas coletadas podem ser afetadas tanto pela percepção do entrevistado quanto pela condução da entrevista, impactando a precisão dos dados qualitativos.



## Definição do Usuário
A partir da análise documental e das entrevistas realizadas, foi possível consolidar um conjunto de características que define o perfil principal do usuário da aplicação.  
O arquétipo resultante — denominado “Sobrevivente Pragmático” — representa um indivíduo com elevada familiaridade com tecnologias digitais, mas que dispõe de tempo e recursos limitados.

Esse usuário utiliza o sistema de forma direta e objetiva, buscando solucionar suas necessidades com agilidade e eficiência, priorizando funcionalidades que tragam benefícios concretos em seu cotidiano.

### Perfil de usuário
A tabela 1 a seguir mostra o perfil do usuário.

<font size="3"><p style="text-align: center">Tabela 1: Perfil de Usuário</p></font>


| **Especificação** | **Perfil** |
|--------------------|------------|
| **Persona / Arquétipo** | Sobrevivente Pragmático |
| **Faixa Etária** | 15 a 29 anos (com maior concentração na faixa de 21-22 anos, segundo a amostra) |
| **Gênero** | Ambos, com possível predominância feminina (com base na amostra) |
| **Ocupação** | Estudante, principalmente de Ensino Superior |
| **Renda** | Baixa Renda (critério de elegibilidade do programa) |
| **Experiência Digital** | Alta, familiaridade com aplicativos para transações online |
| **Tarefa Primária** | Gerar a carteira digital para obter descontos em lazer e transporte |
| **Dispositivo** | Mobile (Smartphone ANDROID ou IOS) |
| **Necessidade** | Economizar e acessar atividades de lazer e cultura (cinema, viagens) consideradas caras |
| **Barreiras (Pontos de Dor)** | Processo de login complicado, falta de divulgação do programa e ausência de canais de suporte |
| **Motivação** | Economia financeira, autonomia e acesso a benefícios de forma rápida e eficiente |

<p align="center" style="font-size:10pt;">
Fontes:  
<a href="https://github.com/dylancavalcante">Dylan Cavalcante</a>,  
<a href="https://github.com/eduardar0">Eduarda Rodrigues</a>
</p>
<small><em>Revisado por [Chat GPT](https://chatgpt.com/), em 21 de Novembro 2025</em></small>

## Bibliografia

> <a id="vazquez2016"></a> VAZQUEZ, C. E.; SIMÕES, G. S. *Engenharia de Requisitos: software orientado ao negócio*. Rio de Janeiro: Brasport, 2016. Acesso em: 28 set. 2025.

> <a id="barbosa2011"></a> BARBOSA, S. D. J.; SILVA, B. S. *Interação Humano-Computador*. Rio de Janeiro: Elsevier, 2011.

> <a id="bilheteriadigital2023"></a> REQUISITOS DE SOFTWARE – Grupo Bilheteria Digital. *Repositório do Projeto*. 2023. Disponível em: [Bilheteria Digital](https://github.com/Requisitos-de-Software/2023.1-BilheteriaDigital). Acesso em: 21 nov. 2025.




## Histórico de Versão

| **Versão** | **Data** | **Descrição** | **Autor(es)** | **Revisor(es)** |
|-------------|-----------|---------------|----------------|-----------------|
| `1.0` | 28/09/2025 | Criação e estruturação do documento de perfil de usuário | [Dylan](https://github.com/dylancavalcante) e [Eduarda](https://github.com/eduardar0) | [Arthur](https://github.com/arthurfernandesj)|
| `1.1`  | 09/10/2025 | refatoração da página (adicionar introdução, metodologia e arrumar links quebrados)| [Dylan](https://github.com/dylancavalcante) | [Eduarda](https://github.com/eduardar0) |
| `1.2` | 09/10/2025 | Deixando mais clara a introdução e adicionando referência bibliográfica| [Breno](https://github.com/BrenoLteixeira) | [Eduarda](https://github.com/eduardar0) |
| `1.3` | 21/11/2025 |  Revisão completa do texto, correção da escrita, padronização das seções em Markdown, organização das referências e bibliografia conforme solicitado. | [Arthur Fernandes](https://github.com/arthurfernandesj) | [Leticia](https://github.com/leticialopes20) |
| `1.4`  | 22/11/2025 | Revisão e Polimento Final  | [Arthur Fernandes](https://github.com/arthurfernandesj) | [Leticia](https://github.com/leticialopes20) |



## Agrecimentos

Queremos agradecer ao [Chat GPT](https://chatgpt.com/), ferramenta de Inteligência Artificial Generativa, pelo apoio durante o desenvolvimento deste projeto ID Jovem. Sua ajuda foi essencial na revisão de textos, na organização das ideias e na pesquisa de conteúdos complementares que contribuíram para deixar nossa documentação mais clara e completa.

De acordo com o Código de Conduta da Sociedade Brasileira de Computação (SBC), destacamos que a ferramenta foi utilizada apenas como apoio técnico e linguístico.
Todo o conteúdo apresentado é de autoria do Grupo 04, que assume total responsabilidade por sua originalidade e precisão.

