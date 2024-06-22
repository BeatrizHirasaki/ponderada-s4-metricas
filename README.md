# Implementação de Monitoramento de Métricas em Aplicações .NET

## Introdução

Este relatório detalha a implementação de um sistema de monitoramento de métricas em uma aplicação .NET, utilizando as melhores práticas e a biblioteca System.Diagnostics.Metrics. Inspirado por um guia oficial da documentação do .NET, este projeto é um exemplo prático de como instrumentar aplicações para obter dados de desempenho em tempo real.


## Principais Conceitos Abordados

Durante a elaboração deste projeto, diversos conceitos importantes foram estudados e aplicados de maneira prática, incluindo:

- **Medidores e Métricas**: Exploração da criação e uso de medidores para definir e gerir métricas personalizadas dentro da aplicação.

- **Contadores**: Utilização de contadores para monitorar incrementos em valores, como vendas ou o número de transações processadas.

- **Histogramas**: Aplicação de histogramas para avaliar a distribuição de valores medidos, a exemplo do tempo necessário para processar pedidos.

- **Gauges Observáveis**: Utilização de gauges observáveis para acompanhar variações de métricas ao longo do tempo, como o status de pedidos pendentes.

- **MeterListener**: Implementação de ouvintes para captar e responder a eventos métricos, permitindo a coleta de dados de maneira eficaz.

- **Gerenciamento de Métricas em Tempo Real**: Configuração de um sistema interativo para visualizar e ajustar métricas em tempo real através de um console.


## Evidências do Projeto

As capturas de tela a seguir apresentam diferentes estágios e componentes do projeto em ação, demonstrando a funcionalidade do sistema de monitoramento implementado:

**Evidência 1:** Configuração inicial e teste dos contadores de vendas.

<img src='./assets/Captura de tela 2024-06-21 191103.png'/>


**Evidência 2:** Implementação e verificação dos histogramas para o tempo de processamento de pedidos.

<img src='./assets/Captura de tela 2024-06-21 192414.png'/>


**Evidência 3:** Demonstração dos gauges observáveis e sua utilização para monitoramento de pedidos pendentes.

<img src='./assets/Captura de tela 2024-06-21 193429.png'/>


**Evidência 4:** Ativação do MeterListener e sua integração para a coleta de métricas.

<img src='./assets/Captura de tela 2024-06-21 191654.png'/>


**Evidência 5:** Interface do usuário final no console, permitindo interação direta para controle do fluxo de dados métricos.

<img src='./assets/Captura de tela 2024-06-21 194746.png'/>


#### Conclusão
Este projeto não só solidificou o entendimento sobre instrumentação de métricas em .NET, mas também servirá como base sólida para o aprimoramento contínuo de nossas práticas de desenvolvimento de software.