# Observabilidade

#### Tratando-se de aplicações distribuidas, colocar um aplicação no ar sem observabilidade é loucura!

---

### O que é OBSERVABILIDADE?
Na **teoria de controle**, a observabilidade é definida como uma medida de quão bem os estados internos de um sistema podem ser compreendidos/inferidos a partir do conhecimento das saídas externas desse sistema. 
Simplificando: observabilidade é quão bem você pode entender seu sistema complexo.

### Observabilidade vs Monitoramento
- Monitoramento nos mostra que há algo errado
- Monitoramento se baseia em saber com antecedência quais sinais você deseja monitorar
- Observabilidade nos permite perguntar o porquê algo esta dando errado.

### Os 3 pilares da observabilidade
- **Métricas** são numeros.
  - Métricas tecnicas
  - Métricas de negócio
- **Logs**
  - Resultados de eventos
  - O que está acontecendo com a aplicação
- **Tracing**
  - Capacidade de idenficar a ordem em que os eventos aconteceram
  - Identificar o erro e o contexto em que aconteceu
  - Capacidade de rastrear requisições entre microsserviços

### Elastic Stack

#### ELK Stack

- Elasticsearch
  - Search engine e analytics
  - Apache Lucene
  - 2010 - Elasticsearch N.V (Elastic)
  - Rápido
  - Escalável
  - Interface API Rest
  - Análise e visualização geoespacial
  - Application, website e enterprise search
  - Logging e analytics
  - Trabalha de forma distribuída através de shards que possuem redundância de dados.
  - Pode escalar milhares de servidores e manipular petabyte de dados

- Logstash
  - Processador de dados através de pipelines que consegue receber, transformar e enviar dados simultaneamente
  - Engine coletora de dados em tempo real
  - Inicio como manipulador de logs
  - Trabalha com pipelines
  - Recebe dados de múltiplas fontes
  - Normaliza a transforma dados
  - Envia dados para múltiplas fontes
  - Plugins

- Kibana
  - Permite usuários a visualizarem os dados do elasticsearch em diversas perspectivas