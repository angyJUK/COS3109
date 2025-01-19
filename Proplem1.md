
**ตัวอย่างการวาด "Tree"**

```mermaid
flowchart TB
classDef CoralEdge stroke:#00CED1,stroke-width:4px

a((a)) -->|1| b((b))
a((a)) -->|3| c((c))

b((b)) -->|1| cb((c))
b((b)) -->|3| db((d))

c((c)) -->|1| dc((d))
c((c)) -->|3| gc((g))

dc((d)) -->|1| gdc((g))

cb((c))-->|1| dcb((d))
cb((c)) -->|3| gcb((g))

db((d)) -->|1| gd((g))

dcb((d)) -->|1| gdcb((g))
