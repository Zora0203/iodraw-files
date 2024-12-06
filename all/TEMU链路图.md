```mermaid


flowchart TB
    TEMU-->全托管
    subgraph 小商家
    小商家-->全托管
    end
    subgraph 大商家
    大商家-->半托管
    end
    subgraph TEMU
    c1-->半托管
    end
```