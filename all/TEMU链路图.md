```mermaid
flowchart TB


    subgraph TEMU
    c1[中台]-->quan
    c1-->ban
    end
    
     subgraph 1
   ban[半托管]--实力较弱--> a1[小商家]
    end


    subgraph 大商家
    b1[大商家]quan[全托管]
    end
```