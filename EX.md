```mermaid
graph TD
classDef CoralEdge stroke:#AFEEEE,stroke-width:5px

A1((Bangkok)):::CoralEdge --> A2((Nonthaburi))
A1((Bangkok)) --> A3((PathumThani)):::CoralEdge
A1((Bangkok)) --> A4((Ayutthaya))

A2((Nonthaburi)) --> A5((Angthong:1))
A5((Angthong:1)) --> A6((Singburi:1))

A3((PathumThani)) --> A7((Angthong:2)):::CoralEdge
A7((Angthong:2)) --> A9((Singburi:2)):::CoralEdge

A4((Ayutthaya)) --> A8((Angthong:3))
A8((Angthong:3)) --> A10((Singburi:3))
A4((Ayutthaya)) --> A11((Singburi:4))
