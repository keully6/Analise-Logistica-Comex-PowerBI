# Análise Estratégica de Performance Logística

Dashboard interativo desenvolvido para analisar a performance de agentes de carga em processos de importação, focando na otimização de custos, tempo de trânsito e confiabilidade.

## 🎯 Objetivo do Projeto

A empresa enfrentava o desafio de escolher parceiros logísticos baseando-se em informações incompletas, sem uma visão clara do trade-off entre custo, velocidade e pontualidade. O objetivo deste projeto foi transformar dados operacionais brutos em um painel de inteligência de negócio interativo para suportar decisões estratégicas e reduzir riscos na cadeia de suprimentos.

## 🛠️ Ferramentas Utilizadas
* **Python (Pandas):** Para limpeza, tratamento de dados faltantes, padronização de categorias e engenharia de features (criação de colunas de análise).
* **Power BI:** Para visualização de dados, criação de um dashboard interativo e geração de insights.
* **GitHub:** Para versionamento e documentação do projeto.

## 📊 Dashboard Final
O painel consolidado permite uma análise multifacetada da performance dos fornecedores.

![Dashboard de Análise Logística](dashboard.png)

## 💡 Principais Insights Descobertos

* **O Trade-off Custo vs. Velocidade:** A análise revelou que o agente mais rápido (**MARITIMA EXPRESS**, nos seus dados) é também o mais caro, enquanto um grupo de agentes (**UNILOG, LOGGLOBAL, etc.**) oferece uma opção significativamente mais barata, porém mais lenta.
* **A Descoberta da Confiabilidade:** O agente mais rápido não se provou o mais confiável. A análise de pontualidade mostrou que a **AGIL CARGO** é o parceiro mais consistente, entregando cargas, em média, antes do prazo.
* **Identificação de Risco:** O agente **ATLANTIC SHIPPING** foi identificado como o menos confiável, apresentando a maior média de dias de atraso, o que representa um risco operacional para cargas com prazo crítico.
* **Sazonalidade do Risco Financeiro:** O valor de mercadoria em trânsito atinge seu pico no mês de Maio, exigindo maior atenção do planejamento financeiro neste período.

## 🚀 Recomendações Estratégicas

Com base nos insights, foram propostas as seguintes ações para a diretoria:

1.  **Para Cargas Urgentes:** Utilizar a **MARITIMA EXPRESS**, adicionando uma margem de segurança de 1-2 dias no planejamento devido à sua baixa pontualidade.
2.  **Para Confiabilidade Máxima:** Priorizar a **AGIL CARGO** para cargas críticas onde o cumprimento do prazo é mais importante que o custo.
3.  **Para Redução de Custos:** Em cargas não urgentes, focar nos agentes do cluster "lento e barato", **evitando a ATLANTIC SHIPPING** devido ao seu histórico de atrasos.
   # Analise-Logistica-Comex-PowerBI - Análise de performance de agentes de carga para otimização de custos e prazos na importação.
