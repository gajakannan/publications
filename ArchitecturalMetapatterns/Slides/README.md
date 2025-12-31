# Presentations for Architectural Metapatterns

There are introductory presentations that summarize the main content of my book _Architectural Metapatterns_ (which is, surprisingly, an overview of architectural patterns):

## [Patterns of Patterns, and why we need them](https://speakerdeck.com/denyspoltorak/patterns-of-patterns-c322149c-fcdd-4df6-8c6c-f273c7ab17dd):
* The misery of having thousands of patterns.
* Local and distributed architectures are not dissimilar.
* Structure determines function.
* There are only so many elementary geometries.
* Which means that hundreds of patterns condense into several metapatterns.

## [Basic Architectures, the building blocks for complex systems](https://speakerdeck.com/denyspoltorak/basic-architectures):
* ___Monolith___ – a cohesive codebase.
* ___Shards___ – multiple instances of a (sub)system.
* ___Layers___ – subdivision by the level of abstractness.
* ___Services___ – components, dedicated to subdomains.
* ___Pipeline___ – a chain of data processing steps.

## [Architectural Extensions. Making use of specialized components](https://speakerdeck.com/denyspoltorak/architectural-extensions-c3e506c0-6472-4e2c-8113-b3d8ffa20d63):
* ___Middleware___ – communication and deployment.
* ___Shared Repository___ – persistence and synchronization.
* ___Proxy – protocols___, routing, and security.
* ___Orchestrator___ – integration and use cases.
* ___Combined Component___ – multiple aspects.

## [Fragmented Architectures. Patterns with smaller components](https://speakerdeck.com/denyspoltorak/fragmented-architectures-bf4d129f-4cd1-46bf-9fb0-248879872b25):
* ___Layered Services___ – divide into services, then into layers.
* ___Polyglot Persistence___ – employ multiple databases.
* ___Backends for Frontends___ (___BFF___) – dedicate a service to each kind of client.
* ___Service-Oriented Architecture___ (___SOA___) – divide into layers, then into services.
* ___Hierarchy___ – recursive subdivision.

## [Implementation Patterns. The high-level design of system components](https://speakerdeck.com/denyspoltorak/implementation-patterns):
* ___Plugins___ customize the component’s behavior.
* ___Hexagonal Architecture___ isolates the business logic from external dependencies.
* ___Microkernel___ mediates between resource providers and resource consumers.
* ___Mesh___ maintains a decentralized system.

I hope that the presentations will help you quickly find out if you are interested in the book. They are available for [reading online](https://speakerdeck.com/denyspoltorak) and for download from this folder.

Everything is licensed under [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International](LICENSE).
