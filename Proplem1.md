
**ตัวอย่างการวาด "Tree"**

```mermaid
flowchart TB
classDef CoralEdge stroke:#e06377,stroke-width:5px

a((a)):::CoralEdge -->|1| b((b)):::CoralEdge
a((a)) -->|3| c((c))

b((b)) -->|1| cb((c)):::CoralEdge
b((b)) -->|3| db((d))

c((c)) -->|1| dc((d))
c((c)) -->|3| gc((g))

dc((d)) -->|1| gdc((g))

cb((c))-->|1| dcb((d)):::CoralEdge
cb((c)) -->|3| gcb((g))

db((d)) -->|1| gd((g))

dcb((d)) -->|1| gdcb((g)):::CoralEdge
