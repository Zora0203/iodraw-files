```mermaid
flowchart TB

    subgraph 小商家
    a1[小商家]--实力较弱-->ban[半托管]
    end


    subgraph 大商家
    b1[大商家】-->b2
    end


    subgraph TEMU
    c1-->b2
    c1-->ban
    end
```