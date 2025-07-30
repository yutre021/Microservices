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
