```mermaid


flowchart TB
    TEMU-->全托管
    subgraph 小商家
    商家-->全托管
    end
    subgraph 大商家
    商家-->半托管
    end
    subgraph three
    c1-->c2
    end
```