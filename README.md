# Mermaid-Test

```mermaid
graph TD;
    Entity-->Component;
    Entity-->Relationship;
    Relationship-->Component;
    
    classDiagram
classA --|> classB : Inheritance
classC --* classD : Composition
classE --o classF : Aggregation
classG --> classH : Association
classI -- classJ : Link(Solid)
classK ..> classL : Dependency
classM ..|> classN : Realization
classO .. classP : Link(Dashed)

```
