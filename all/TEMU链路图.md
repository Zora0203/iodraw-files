```mermaid
flowchart TB


    subgraph 核心产品
    A --> B[搜索 Search]
    A --> C[广告 Advertisement]
    A --> D[顶部功能区 Top Functional]
    A --> H[产品类别 Categories]
    A --> I[推荐 Recommended]
    A --> J[导航 Navigation]
    A --> K[首页 Home]
    A --> M[个人中心]
    A --> N[购物车 Cart]
    end
    
     subgraph 1
   ban--实力较弱--> a1[小商家]
    end


    subgraph 2
    quan--拥有海外自营仓-->b1[大商家]
 

    
    %% 顶部功能区展开
    D --> E[标语 Tagline<br>▪ 免费送货 Free returns<br>▪ 免费退货 Free returns]
    D --> F[限时秒杀 Lightning deals<br>▪ 人找货模式<br>▪ 关键词搜索转化]
    D --> G[广告 Advertisement<br>▪ 单品推广<br>▪ 主题推广]
    
    %% 流量分布体系
    A --> O[流量分布]
    O --> P[搜索 Search<br>▪ 谷歌关键词投放]
    O --> Q[行业流量<br>▪ 渠道适配性分析]
    O --> R[活动流量<br>▪ 秒杀活动<br>▪ 大促活动]
    O --> S[市场推广<br>▪ 节庆营销<br>▪ 新品推荐]
    
    %% 数据标注
    Z[["数据来源：人人都是产品经理（佳佳原创）
    广发证券发展研究中心"]]:::source
    
    %% 样式定义
    classDef title fill:#f0f8ff,stroke:#1a3d66,stroke-width:1.5px,font-size:14pt
    classDef default fill:#fff,stroke:#1a3d66,stroke-width:1px,font-size:10pt
    classDef source fill:#fafafa,stroke:#999,stroke-width:0.8px,font-size:8pt
    class A,Z title,source
```