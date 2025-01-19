```mermaid
flowchart TB
classDef CoralEdge stroke:#00CED1,stroke-width:4px

A1((Frankfurt)):::CoralEdge --> A2((Mannheim))
A1((Frankfurt)) --> A3((Würzburg))
A1((Frankfurt)) --> A4((Kassel)):::CoralEdge

A2((Mannheim)) --> A5((Karlsruhe))
A5((Karlsruhe)) --> A9((Augsburg))
A9((Augsburg)) --> A10((München:G1))

A3((Würzburg)) --> A6((Nürnberg))
A3((Würzburg)) --> A7((Erfurt))
A6((Nürnberg)) --> A8((Stuttgart))
A6((Nürnberg)) --> A11((München:G2))

A4((Kassel)) --> A12((München:G3)):::CoralEdge
