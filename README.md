# TP 21 – Architecture Micro-services avec WebClient

## Présentation du projet

Ce TP a pour objectif de mettre en œuvre une architecture basée sur les microservices avec Spring Boot, en utilisant `WebClient` pour assurer la communication entre les différents services.

WebClient est un client HTTP réactif qui permet d'effectuer des requêtes vers des API REST de manière non bloquante, facilitant ainsi les échanges entre les composants d'une application distribuée.

## Objectifs

- Comprendre les principes d'une architecture microservices.
- Développer des microservices indépendants avec Spring Boot.
- Exposer des fonctionnalités à travers des API REST.
- Utiliser WebClient pour effectuer des appels HTTP entre microservices.
- Découvrir les principes de la programmation réactive.
- Gérer les réponses et les échanges de données entre les services.

## Technologies utilisées

- Java
- Spring Boot
- Spring WebFlux
- WebClient
- REST API
- Maven
- JSON

## Architecture du projet

L'application repose sur plusieurs microservices indépendants qui communiquent à travers des requêtes HTTP.

- **Microservice principal :** reçoit les requêtes des clients et coordonne les traitements.
- **Microservice distant :** fournit des données ou des fonctionnalités aux autres services.
- **WebClient :** assure les appels HTTP entre les microservices avec une approche non bloquante


## Conclusion

Ce TP permet de découvrir WebClient comme solution de communication entre microservices et de comprendre les avantages d'une approche réactive et non bloquante dans le développement d'applications distribuées avec Spring Boot.
