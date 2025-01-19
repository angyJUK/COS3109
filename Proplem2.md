**ตัวอย่างการวาด "Tree"**

```mermaid
flowchart TB
classDef CoralEdge stroke:#00CED1,stroke-width:4px

a((a)) -->|1| b((b))
a((a)) -->|3| h((h))

b((b)) -->|1| cb((c))
b((b)) -->|3| db((d))

h((h)) -->|1| j((j))

db((d)) -->|3| e((e))
db((d)) -->|1| g((g))
