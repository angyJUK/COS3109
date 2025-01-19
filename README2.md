```mermaid
flowchart TB
classDef CoralEdge stroke:#FF7F50,stroke-width:4px

A1((Frankfurt)):::CoralEdge --> A2((Mannheim)):::CoralEdge
A1((Frankfurt)) --> A3((Würzburg)):::CoralEdge
A1((Frankfurt)) --> A4((Kassel)):::CoralEdge

A2((Mannheim)) --> A5((Karlsruhe)):::CoralEdge
A5((Karlsruhe)) --> A9((Augsburg))
A9((Augsburg)) --> A10((München:G1))

A3((Würzburg)) --> A6((Nürnberg)):::CoralEdge
A3((Würzburg)) --> A7((Erfurt)):::CoralEdge
A6((Nürnberg)) --> A8((Stuttgart))
A6((Nürnberg)) --> A11((München:G2))

A4((Kassel)) --> A12((München:G3)):::CoralEdge
