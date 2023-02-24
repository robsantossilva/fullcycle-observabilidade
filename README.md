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