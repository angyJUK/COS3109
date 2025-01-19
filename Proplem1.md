
**ตัวอย่างการวาด "Tree"**

```mermaid
flowchart TD
    a["a\nh=4"] -->|1| b["b\nh=3"]
    a -->|3| c["c\nh=2"]
    b -->|1| c_2["c\nh=2"]
    b -->|3| d["d\nh=1"]
    c -->|1| d_2["d\nh=1"]
    c -->|3| g["g\nh=0"]
    d -->|1| g_2["g\nh=0"]
    d_2 -->|1| g_3["g\nh=0"]
