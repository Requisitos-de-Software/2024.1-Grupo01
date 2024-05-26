## <a> Introdução </a>

O **Non-Functional Requirements (NFR) Framework** é uma abordagem estruturada para tratar os requisitos não funcionais em projetos de engenharia de software. Requisitos não funcionais são aqueles que definem atributos de qualidade do sistema, como desempenho, segurança, usabilidade e confiabilidade, que são críticos para o sucesso do software, mas que não dizem respeito diretamente às funcionalidades específicas do sistema.<a id="anchor_1" href="#REF1">^1^</a>

Proposto por Lawrence Chung e colaboradores, o NFR Framework visa integrar esses requisitos ao processo de desenvolvimento de software de maneira sistemática. O framework trata os requisitos não funcionais como "softgoals", que são metas qualitativas e subjetivas, e fornece uma estrutura para representar, refinar e analisar esses softgoals.  <a id="anchor_1" href="#REF1">^1^</a>

## <a> Softgoal Interdependency Graph (SIG) </a>

O **Softgoal Interdependency Graph (SIG)** é uma ferramenta central dentro do NFR Framework que facilita a modelagem e a análise de requisitos não funcionais. O SIG permite a visualização das interdependências entre diferentes softgoals e ajuda a entender como diferentes soluções contribuem para a satisfação desses requisitos.<a id="anchor_1" href="#REF1">^1^</a>

### <a> Identificação e Representação dos Softgoals </a>

No SIG, os requisitos não funcionais são inicialmente identificados como softgoals. Esses softgoals são representados como nós no gráfico e refletem as aspirações e preocupações dos stakeholders, como exemplo na Figura 1. Cada softgoal é expresso de maneira qualitativa, permitindo uma compreensão mais ampla e flexível dos objetivos de qualidade do sistema.

### <a> Refinamento dos Softgoals </a>

Os softgoals são refinados em subgoals, que detalham as características específicas necessárias para satisfazer os requisitos não funcionais. Este refinamento pode ocorrer em vários níveis, permitindo uma decomposição detalhada dos objetivos de qualidade. Cada nível de refinamento oferece uma visão mais granular das metas a serem alcançadas.
 
### <a> Estabelecimento de Contribuições </a>

As relações de contribuição entre os diferentes softgoals e subgoals são estabelecidas. Essas contribuições podem ser positivas, negativas ou neutras e são representadas como arestas no gráfico. A análise dessas contribuições permite visualizar os trade-offs entre diferentes requisitos não funcionais, ajudando a identificar possíveis conflitos e sinergias.

### <a> Construção e Análise do SIG </a>

O SIG é construído com base nos softgoals, subgoals e nas relações de contribuição identificadas. Este gráfico fornece uma visualização clara das interdependências entre os requisitos não funcionais e facilita a análise das alternativas e soluções, como exemplo na Figura 1. A análise do SIG permite uma avaliação das opções de design e uma justificativa racional para as decisões tomadas.

### <a> Aplicação do SIG </a>

A aplicação do SIG no processo de desenvolvimento de software garante que os requisitos não funcionais sejam considerados de maneira explícita e estruturada. Ele fornece uma base sólida para a discussão e documentação das decisões de design, promovendo a rastreabilidade e a compreensão dos trade-offs envolvidos.

<font size="3"><p style="text-align: center"><b>Figura 1:</b> NFR Framework</p></font>

<p align="center">
  <img src="https://github.com/Requisitos-de-Software/2024.1-DiarioOficialdaUniao/blob/main/docs/modelagem/images/nfr.png?raw=true" alt="NFR Framework" />
</p>
<font size="3"><p style="text-align: center">Fonte: JANEIRO, José. GOMES, Joaquim. 2007/2008</p></font>

## <a> Metodologia </a>

1. **Identificação dos Softgoals**: Requisitos não funcionais são identificados e expressos como softgoals.
2. **Refinamento dos Softgoals**: Softgoals são detalhados em subgoals para especificar características específicas.
3. **Estabelecimento de Contribuições**: Relações de contribuição entre softgoals e subgoals são identificadas.
4. **Construção do Softgoal Interdependency Graph (SIG)**: Um gráfico é construído para visualizar interdependências e trade-offs.
5. **Análise e Racionalização**: Alternativas e soluções são analisadas para suportar decisões de design.

## <a> Cartões de Especificação </a>
Na tabela 1, temos o cartão de especificação do softgoal "Usabilidade".

<center>

**Tabela 1** - Cartão de especificação 1 - Usabilidade

| Tópico | Usabilidade/Fácil Aprendizado | 
| :------: | :------: |
| ID |  |
| Descrição |  |
| Justificativa |  |
| Origem do Requisito |  |
| Critério de Aceitação |  |
| Dependências |  |
| Prioridade |  |
| Conflito |  |
| História |  |

_Fonte: [Luiz Gustavo](https://github.com/LuizGust4vo)_

</center>

## <a> Referência Bibliográfica </a>

> <a id="REF1" href="#anchor_1">1.</a> Chung, L., Nixon, B. A., Yu, E., Mylopoulos, J. Non-functional requirements in software engineering. Springer Science & Business Media: [S.l.], 2000. v. 5.

## <a> Bibliografia </a>

> JANEIRO, José. GOMES, Joaquim. NFR Framework. ESTIC, Brasil, 2008. Disponível em: [http://jaejaneiro.orgfree.com/engsofnfr.pdf](http://jaejaneiro.orgfree.com/engsofnfr.pdf). Acesso em: 25/05/2024.

## <a> Histórico de versão </a>

| Versão | Data | Data Prevista de Revisão | Descrição | Autor | Revisor |
| :------: | :----------: |:-----------: | :----------------------: | :---------: |:---------: |
| `1.0` | 25/05/2024 | 25/05/2024 | Criação da Documentação e conceitos sobre o NFR | [Douglas Marinho](https://github.com/M4RINH0) | [Arthur Alves](https://github.com/Arthrok) |