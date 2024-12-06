```mermaid
flowchart TB


    subgraph TEMU
    c1[中台]-->quan
    c1-->ban
    end
        subgraph 小商家
    a1[小商家]--实力较弱-->ban[半托管]
    end


    subgraph 大商家
    b1[大商家]--拥有海外自营仓-->quan[全托管]
    end
```