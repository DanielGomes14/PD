## Relatório de Progresso
#### Semana 1 - 30 Setembro
  - Definição de objetivos da dissertação
  - Leitura de diversos artigos orientados à temática de orquestração de multi-domínios para Verticais através de NFV(*Network Function Virtualization*)
  - Pesquisa do estado de arte em orquestradores de Verticais
#### Semana 2 - 8 de Outubro
  - Início da implementação de *Service Discovery* dos Peers do NetOr. Para tal recorreu-se a um Servidor DNS onde estes se registam e se anunciam aos restantes peers, ou seja,  *DNS-Based Service Discovery*,  seguindo o Standard RFC-6753.
  - Alteração do serviço de autenticação do NetOr, *Tenant*, para o IDP ***KeyStone*** do *Openstack*
  -  Leitura de Standards da ETSI como o SOL005



#### Semana 3 - 14 de Outubro

- Refactor de Diversos Serviços do NetOr, de forma a possibilitiar a implementação de novas featurs de forma sustentavel
- Procura e Leitura de mais artigos relacionados com orquestração multi-dominio, como por exemplo  *Hierarchical Distributed Overarching*
  *Architecture of Decoupled Federation and Orchestration Frameworks for Multidomain NFV MANOs*
- Pesquisa sobre standard 3GPP TS28.530 SA5 https://www.3gpp.org/news-events/3gpp-news/sa5-5g

#### Semana 4 - 21 de Outubro

- Conclusão do refactor Base ao Netor
- Começo da escrita de testes no módulo Domain

#### Semana 5 - 28 de Outubro

- Após alguma investigação a decisão de colocar o IDP como o KeyStone foi alterada devido a problemas relacionados com deprecation na sua implementação assim como suporte. Assim o IDP decidido e implementado foi o **KeyCloak**

- Continuação da escrita de testes unitários de integração

  

#### Semana 6 -  4 de Novembro

- Novas funcionalidades como a execução de day-2 operations via NetOr
-  Novos testes unitários ao modulo Coordinator
- Corrigidos alguns problemas de infraestrutura relacionados com o OSM, que é utilizado como NFVO(Network Function Virtualization Orchestrator) do NetOr

#### Semana 7 - 11 de Novembro

- Continuação da escrita da tese ( Background Concepts como Traditional Networks, SDN&NFV)
- Preparação do Netor para um cenário de produção no projeto 5GASP juntamente com OdinS

### Semana 8 - 18 de Novembro

- Cenário de Produção do Netor com OdinS e Universidade de Patras em progresso
- Escrita de tese (5G, Network Slicing)
- Investigação de como gestão de SLAs podem ser efetuada no NetOr

###  Semana 9 -  25 de Novembro

- Cenário de Produção do Netor com Patras e OdinS concluído
- Escrita de tese (ETSI NFV Architecture e soluções MANO)
- Gestão de SLAs não será feita. Para fornecer resiliência e performance, o NetOr terá monotorização ativa da rede mesh dos peers, ajustando as rotas de forma a obter o melhor desempenho

### Semana 10 -  2 de Dezembro

- Preparação  e começo para a escrita de um paper no ambito da tese e do projeto 5GASP : "5GASP's Mesh VPN as a Service "

### Semana 11 - 9 de Dezembro 

- Continuação da escrita do Paper mencionado acima
- Escrita de tese (Vertical Service Orchestrators)

### Semana 12 - 16 de Dezembro

- Escrita de tese (conclusão do tópico dos Vertical Service Orchestrators)
- Recolha de resultados para o paper mencionado acima

### Semana 13 - 23 de Dezembro

- Escrita da secção de resultados para o paper

- Escrita da secção de Service Discovery na tese

### Semana 14 - 30 de Dezembro

- Investigação sobre monitorização
- Investigação da proposta de framework da ETSI sobre Active Monitoring

### Semana 15 - 6 de Janeiro

- Investigação sobre estrategias que tenham como base a proposta da ETSI sobre Active Monitoring

### Semana 16 -  13 de Janeiro

- Finalização das escritas das secções sobre monitorização da tese e Revisão com o Orientador
- Escrita da Work Proposal
