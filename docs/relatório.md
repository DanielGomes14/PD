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

