# Microservices
Microservices Learning

<img src="src/i7a6ghi7a6ghi7a6.png" alt="Diagrama de Arquitetura em 4 Camadas" width="500px">



# Resumo das Camadas do Ecossistema de Microsserviços

## Camada 1: A Camada de Hardware

### Português
A camada de hardware (camada 1) do ecossistema de microsserviços contém:
* os servidores físicos (de propriedade da empresa ou alugados de provedores de serviços de nuvem)
* databases (dedicados e/ou compartilhados)
* o sistema operacional
* isolamento e abstração de recursos
* gerenciamento de configuração
* monitoramento em nível de servidor
* logging em nível de servidor

### English
The hardware layer (layer 1) of the microservices ecosystem contains:
* physical servers (company-owned or rented from cloud service providers)
* databases (dedicated and/or shared)
* the operating system
* resource isolation and abstraction
* configuration management
* server-level monitoring
* server-level logging

## Camada 2: A Camada de Comunicação

### Português
A camada de comunicação (camada 2) do ecossistema de microsserviços contém:
* rede
* DNS
* Remote Procedure Calls (RPCs)
* endpoints
* troca de mensagens
* descoberta de serviço
* registro de serviço
* balanceamento de carga

### English
The communication layer (layer 2) of the microservices ecosystem contains:
* network
* DNS
* Remote Procedure Calls (RPCs)
* endpoints
* message exchange
* service discovery
* service registration
* load balancing

## Camada 3: A Camada da Plataforma de Aplicação

### Português
A camada da plataforma de aplicação (camada 3) do ecossistema de microsserviços contém:
* ferramentas internas de desenvolvimento do tipo autosserviço
* ambiente de desenvolvimento
* ferramentas de teste, empacotamento, build e liberação
* pipeline de deployment
* logging em nível de microsserviço
* monitoramento em nível de microsserviço

### English
The application platform layer (layer 3) of the microservices ecosystem contains:
* internal self-service development tools
* development environment
* testing, packaging, build, and release tools
* deployment pipeline
* microservice-level logging
* microservice-level monitoring

## Camada 4: A Camada dos Microsserviços

### Português
A camada dos microsserviços (camada 4) do ecossistema de microsserviços contém:
* os microsserviços
* todas as configurações específicas dos microsserviços

### English
The microservices layer (layer 4) of the microservices ecosystem contains:
* the microservices
* all microservice-specific configurations


# Resumo: A Lei de Conway e Sua Reversa no Contexto de Microsserviços

## Português

A **Lei de Conway**, nomeada em homenagem a Melvin Conway (1968), postula que a arquitetura de um sistema reflete as estruturas de comunicação e organizacionais da empresa que o constrói.

O texto destaca que o **reverso da Lei de Conway** (ou Lei de Conway Reversa) também é verdadeiro e particularmente relevante para ecossistemas de microsserviços: a estrutura organizacional de uma empresa é moldada pela arquitetura de seu produto.

Mais de quarenta anos após sua introdução, tanto a lei original quanto sua reversa continuam válidas, sendo evidentes em grandes empresas de tecnologia como Microsoft, Google e Amazon, cujas estruturas organizacionais se assemelham à arquitetura de seus produtos. Empresas que adotam arquitetura de microsserviços não são exceção a esta regra.

## English

# Summary: Conway's Law and Its Reverse in the Context of Microservices

## English

**Conway's Law**, named after Melvin Conway (1968), states that the architecture of a system will mirror the communication and organizational structures of the company that builds it.

The text emphasizes that the **reverse of Conway's Law** is also valid and particularly relevant for microservices ecosystems: a company's organizational structure is determined by its product's architecture.

Over forty years after its introduction, both the original law and its reverse remain valid. This is evident in major tech companies like Microsoft, Google, and Amazon, whose organizational structures resemble their product architectures. Companies adopting microservices architecture are no exception to this rule.


# Resumo: Microsserviços, Lei de Conway Reversa e Estrutura Organizacional

## Português

A arquitetura de microsserviços é caracterizada por muitos serviços pequenos, independentes e isolados. A **Lei de Conway Reversa** implica que qualquer empresa que adote essa arquitetura deve ter uma estrutura organizacional composta por equipes pequenas, isoladas e independentes.

Essa estrutura de equipe, embora leve a um ecossistema de microsserviços mais sofisticado e eficiente, também pode resultar em fenômenos de segregação e dispersão.

Para os desenvolvedores, a Lei de Conway Reversa significa que eles se tornarão, de certa forma, como os microsserviços que criam: serão capazes de executar tarefas específicas muito bem, mas estarão isolados em termos de responsabilidade, conhecimento de domínio e experiência. Coletivamente, os desenvolvedores de um ecossistema de microsserviços possuem o conhecimento completo, mas individualmente são altamente especializados em suas áreas de responsabilidade.

## English

# Summary: Microservices, Reverse Conway's Law, and Organizational Structure

## English

Microservices architecture is characterized by numerous small, independent, and isolated services. **Reverse Conway's Law** implies that any company adopting this architecture must have an organizational structure composed of small, isolated, and independent teams.

While this team structure leads to a more sophisticated and efficient microservices ecosystem, it can also result in phenomena of segregation and dispersion.

For developers, Reverse Conway's Law means they will, in many aspects, become like the microservices they build: they will be able to perform specific tasks very well but will be isolated in terms of responsibility, domain knowledge, and experience. Collectively, developers within a microservices ecosystem will possess complete knowledge, but individually they will be highly specialized in their areas of responsibility.
