# Introducao ao Elastic Stack

![Elastic Stack](https://www.elastic.co/static-res/images/elk/elk-stack-elkb-diagram.svg)

## Elastic Search
> Engine de search and analytics
> - Banco de dados Orientado a Documentos
> - Engine de Busca
> - Análise de dados
> - Rápido
> - Escalável e distribuído
> - API Rest


## Logstash
> Processador de dados através de pipelines que consegue receber, transformar e enviar dados simultaneamente (incluindo ao elasticsearch)
> - Teve início como manipulador de logs
> - Engine coletora de dados em tempo real
> - Trabalha com pipelines
> - Recebe dados de múltiplas fontes
> - Normaliza / Transforma dados
> - Envia dados para múltiplas fontes
> - Plugins



## Kibana
> Permite aos usuários a visualização dos dados do elasticsearch através de gráficos, etc.
> - Ferramenta de visualização e exploração de dados
> - Usado com: Logs, Análise de séries, Monitoramento de aplicações, e inteligência operacional
> - Integrado com Elasticsearch
> - Agregadores e filtragem de dados
> - Dashboards
> - Gráficos interativos
> - Mapas

## Beats!
> Foi anunciado em 2015.
> - "lightweight data shipper"
> - Agente coletor de dados
> - Integrado facilmente com Elasticsearch ou Logstash
> - Logs, Métricas, Network data, Audit Data, Uptime Monitoring
> - Você pode construir seu próprio Beat

- [ ] Kibana
- [ ] TSVB

[Grok Patterns](https://github.com/hpcugent/logstash-patterns/blob/master/files/grok-patterns)


## Referências:
https://github.com/deviantony/docker-elk
https://www.elastic.co/pt/
https://www.elastic.co/pt/what-is/elk-stack
