```mermaid
flowchart TB
    c1-->a2
    subgraph 小商家
    a1[-->a2
    end
    subgraph 大商家
    b1-->b2
    end
    subgraph TEMU
    c1-->b2
    end
```