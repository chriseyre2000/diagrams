# diagrams
Some diagrams that I am working on

This is a sample of using the inline mermaid editor

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

# Recreating EventStorming

```mermaid
graph TD;
classDef facadeCommand fill:#779fae
classDef command fill:#aec6cf
classDef result fill:#cfcfc4 
classDef event fill:#ffb853
classDef domainEvent fill:#ffcb81
classDef integrationEvent fill:#ffdeaf
classDef query fill:#62d862
classDef readModel fill:#77dd77
classDef userInterface fill:#a2e8a2
classDef aggregate fill:#fdfd9d
classDef service fill:#fcfc78
classDef policy fill:#b6a2db
classDef saga fill:#c9bbe5
classDef process fill:#ddd4ee
classDef timer fill:#cfcfc4
classDef person fill:#ffd1dc
classDef system fill:#ffd1dc
classDef comment fill:transparent

FacadeCommand:::facadeCommand --> Command:::command
Result:::result --> Event:::event
DomainEvent:::domainEvent --> IntegrationEvent:::integrationEvent
Query:::query --> ReadModel:::readModel
UserInterface:::userInterface --> Aggregate:::aggregate
Service:::service --> Policy:::policy
Saga:::saga --> Process:::process
Timer:::timer --> Person:::person
System:::system --> Comment:::comment

```
