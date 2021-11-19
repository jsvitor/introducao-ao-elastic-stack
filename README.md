# O Elastic Stack

> Sarch. Observe. Protect.

<p align="center">
  <img src="https://www.elastic.co/static-res/images/elk/elk-stack-elkb-diagram.svg"
       alt="Elastic Stack"
       style="float: left; align: center; width: 300px" />
</p>



## Elasticsearch
> Engine de search and analytics
<details>
    <summary>Características</summary>
  
> - Banco de dados Orientado a Documentos
> - Engine de Busca
> - Análise de dados
> - Rápido
> - Escalável e distribuído
> - API Rest

### Elastic Search Indices

  
##### Data Lakes vs Data Warehoses
  
| Data Lakes | Data Warehouses |
|--|--|
|  |  |

  
</details>

## Logstash
> Processador de dados através de pipelines que consegue receber, transformar e enviar dados simultaneamente (incluindo ao elasticsearch)

<details>
    <summary>Características</summary>
  
> - Teve início como manipulador de logs
> - Engine coletora de dados em tempo real
> - Trabalha com pipelines
> - Recebe dados de múltiplas fontes
> - Normaliza / Transforma dados
> - Envia dados para múltiplas fontes
> - Plugins

</details>


## Kibana
> Permite aos usuários a visualização dos dados do elasticsearch através de gráficos, etc.

<details>
    <summary>Características</summary>

> - Ferramenta de visualização e exploração de dados
> - Usado com: Logs, Análise de séries, Monitoramento de aplicações, e inteligência operacional
> - Integrado com Elasticsearch
> - Agregadores e filtragem de dados
> - Dashboards
> - Gráficos interativos
> - Mapas

</details>

### Kibana Fundamentals Course | elastic.co

#### Lesson 1: Introduction to Kibana

#### Lesson 2: Visualizing Data


#### Lesson 3: Discover

> Kibana é mais do que uma ferramenta de visualização de dados. Kibana Discover permite que você faça consultas nos dados do elasticsearch e exportar os resultados para futuras análises.

### Exploring and querying your data.
Neste vídeo, apreendi sobre a estrutura do discover, KQL - a linguagem de consulta do Kibana, adicionar filtro à tabela dos documentos recentes, e exportação de resultados.

## Beats!
> é uma plataforma gratuita e aberta para agentes de dados de finalidade única.

<details>
    <summary>Características</summary>
  
> - "lightweight data shipper"
> - Agente coletor de dados
> - Integrado facilmente com Elasticsearch ou Logstash
> - Logs, Métricas, Network data, Audit Data, Uptime Monitoring
> - Você pode construir seu próprio Beat
</details>

- [ ] Kibana
- [ ] TSVB

[Grok Patterns](https://github.com/hpcugent/logstash-patterns/blob/master/files/grok-patterns)




## Referências:
- https://github.com/deviantony/docker-elk
- https://www.elastic.co/pt/
- https://www.elastic.co/pt/what-is/elk-stack
- https://www.youtube.com/watch?v=Bb3g8xk0Cys
- https://github.com/sherifabdlnaby/elastdocker
- https://towardsdatascience.com/running-securing-and-deploying-elastic-stack-on-docker-f1a8ebf1dc5b
