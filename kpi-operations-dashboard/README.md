# KPI Operations Dashboard

Projeto autoral de análise de indicadores operacionais, criado para praticar **Excel, Power BI, SQL e análise de dados** em cenários de logística, suporte e operações de TI.

> Projeto independente, desenvolvido para fins de estudo e portfólio. Não utiliza dados reais, confidenciais ou internos de empresas.

## Objetivo

Construir um painel de indicadores capaz de transformar dados operacionais fictícios em informações úteis para tomada de decisão.

O projeto simula uma operação com chamados de suporte e atividades logísticas, permitindo acompanhar produtividade, qualidade, prazos e volume de demandas.

## Indicadores principais

### Atendimento e suporte

- Total de chamados registrados;
- Chamados resolvidos;
- Chamados pendentes;
- Chamados reabertos;
- Tempo médio de atendimento — TMA;
- Tempo médio de resolução — TMR;
- Percentual de resolução dentro do SLA;
- Taxa de reincidência;
- Distribuição por prioridade;
- Distribuição por categoria.

### Operações logísticas

- Volume processado;
- Produtividade por colaborador;
- Taxa de erros;
- Percentual de entregas no prazo;
- Lead time médio;
- Backlog de atividades;
- Cumprimento de SLA;
- Índice de retrabalho.

## Dashboard planejado

O painel deverá apresentar:

- Cards com os principais KPIs;
- Gráficos de evolução diária e mensal;
- Filtros por período, área, prioridade e responsável;
- Ranking de categorias com maior volume;
- Comparação entre meta e resultado;
- Identificação de gargalos;
- Tabela detalhada para investigação dos indicadores.

## Tecnologias e ferramentas

- Microsoft Excel;
- Power Query;
- Power BI;
- SQL/PostgreSQL;
- Python para tratamento de dados;
- Git e GitHub;
- Documentação em Markdown.

## Modelo de dados sugerido

```text
fato_atendimentos
├── id_atendimento
├── data_abertura
├── data_fechamento
├── area
├── categoria
├── prioridade
├── responsavel
├── status
├── tempo_atendimento_minutos
├── tempo_resolucao_minutos
├── dentro_sla
├── reaberto
└── nota_satisfacao
```

## Exemplos de análises

- Qual categoria concentra mais chamados?
- Qual período apresenta maior volume de demandas?
- Quais atendimentos ultrapassaram o SLA?
- Qual é o tempo médio de resolução por prioridade?
- Qual área apresenta maior taxa de reincidência?
- Como o resultado atual se compara à meta definida?
- Quais processos apresentam maior índice de retrabalho?

## Entregas planejadas

- [ ] Criar base de dados fictícia;
- [ ] Tratar os dados com Power Query ou Python;
- [ ] Modelar as tabelas no Power BI;
- [ ] Criar medidas DAX;
- [ ] Construir dashboard interativo;
- [ ] Documentar os indicadores e suas fórmulas;
- [ ] Criar relatório executivo com conclusões;
- [ ] Publicar imagens do dashboard no README.

## Competências demonstradas

- Análise de dados;
- Construção e acompanhamento de KPIs;
- Excel e Power Query;
- Visualização de dados;
- Power BI e DAX;
- SQL;
- Pensamento analítico;
- Identificação de gargalos;
- Apoio à tomada de decisão;
- Comunicação de resultados.

## Observação

Todos os dados utilizados no projeto deverão ser fictícios ou anonimizados, sem exposição de informações confidenciais do ambiente profissional.
