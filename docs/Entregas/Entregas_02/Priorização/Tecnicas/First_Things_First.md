### **Técnica First Things First**

"First Things First" é uma técnica de priorização mais elaborada, proposta por Karl E. Wiegers. Seu objetivo principal é equilibrar os benefícios de cada requisito com seus respectivos custos, riscos e implicações na arquitetura do software.

#### **O que é?**

É um método analítico que busca remover parte da subjetividade do processo de priorização ao utilizar uma abordagem baseada em múltiplos critérios. A técnica força uma análise detalhada que vai além do simples "valor para o cliente", incluindo perspectivas de custo, penalidade por não implementação e risco técnico. Ela é projetada para projetos onde uma decisão mais fundamentada e defensável é necessária, especialmente quando há muitos requisitos conflitantes. Não é recomendada para listas com mais de "dezenas" de requisitos.

#### **Como se usa?**

O processo é estruturado em uma planilha e envolve diferentes papéis: um gerente para liderar, representantes de clientes para classificar benefícios e penalidades, e representantes de desenvolvimento para avaliar custos e riscos.

1.  **Listar Requisitos:** Todos os requisitos e suas dependências lógicas são listados em uma planilha.
2.  **Estimar Benefício:** Representantes dos clientes estimam o benefício relativo que cada requisito trará, em uma escala de 1 (menos significativo) a 9 (mais significativo).
3.  **Estimar Penalidade:** Os mesmos representantes estimam a penalidade ou desvantagem que o negócio sofreria se o requisito não fosse implementado, também em uma escala de 1 a 9.
4.  **Calcular Valor Total:** Um valor total é calculado somando-se o benefício e a penalidade, com a possibilidade de aplicar pesos a cada um para ajustar sua importância relativa.
5.  **Estimar Custo:** Representantes do desenvolvimento estimam o custo relativo de implementação de cada requisito em uma escala de 1 a 9, considerando complexidade, esforço de teste, documentação, etc.
6.  **Estimar Risco:** A equipe de desenvolvimento também avalia o grau de risco técnico de cada requisito em uma escala de 1 a 9, considerando fatores como familiaridade com a tecnologia e disponibilidade de pessoal qualificado.
7.  **Calcular Prioridade:** Por fim, um índice de prioridade é calculado, geralmente dividindo o percentual do valor total pela soma dos percentuais de custo e risco. Os requisitos com o maior índice são os mais prioritários.

#### **Vantagens**

-   É uma técnica mais elaborada e estruturada do que as mais simples.
-   Equilibra os benefícios de uma funcionalidade contra seus custos e riscos, oferecendo uma visão mais completa e defensável para a tomada de decisão.
-   Define claramente os papéis e responsabilidades dos diferentes participantes no processo de priorização.

#### **Desvantagens**

-   Por ser mais elaborada, é mais complexa e consome mais tempo do que técnicas como MoSCoW.
-   Pode não ser adequada para projetos com um backlog muito extenso, sendo recomendada para listas que não ultrapassam a casa das dezenas.

---
## Gravação

<div align="center">
<p style="text-align: center"><a href="https://youtu.be/ywmlErJ7bdA" target="_blank"><b>Vídeo 1:</b> Técnica de Priorização - In or Out</a></p>

<iframe width="560" height="315" src="https://www.youtube.com/embed/ywmlErJ7bdA" title="Sessão de Técnica de Priorização - In or Out" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<font size="3"><p style="text-align: center"><b>Fontes:</b> <a href="https://github.com/GiovanaFontesS">Giovana Fontes</a>, 2025</p></font>
</div>
## 📚 Referências Bibliográficas

> SERRANO, Milene; SERRANO, Maurício. **Requisitos – Aula 07**. Gama, DF: Universidade de Brasília, [s.d.]. Material de aula.

> WIEGERS, Karl E. **Software Requirements**. 2. ed. Redmond, WA: Microsoft Press, 2003.

## 📝 Histórico de Versões

| Versão | Data       | Descrição                                                                            | Autor(es)                                 | Revisor(es) |
| ------ | ---------- | ------------------------------------------------------------------------------------ | ----------------------------------------- | ----------- |
| `1.0`  | 28/09/2025 | Criação do documento com a descrição da técnica de priorização " First Things First" | [Danilo Melo](https://github.com/EngDann) |             |
