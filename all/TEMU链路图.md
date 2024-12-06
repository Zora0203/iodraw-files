```mermaid
flowchart TB
    c1-->a2
    subgraph 小商家
    a1[小商家]--实力较弱->a2[半托管]
    end
    subgraph 大商家
    b1-->b2
    end
    subgraph TEMU
    c1-->b2
    end
```