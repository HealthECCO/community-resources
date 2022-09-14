# Knowledge Graph Resources Online
A collection of useful knowledge graph resources available online
```mermaid
  graph TD; 
      F(Forums);
      P(Publications);
      W(Websites);
  click F "/HealthECCO/community-resources/blob/main/forums.md"
  click P "/HealthECCO/community-resources/blob/main/publications.md"
```

```mermaid
  graph LR; 
      DA(Data Acquisition)-->DP(Data Processing);
      subgraph BioCypher
        DP-->DM(Data Modelling);
      end
      DM-->DO(Data Output);
    click DA "https://www.github.com"
```
