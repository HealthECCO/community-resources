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
  flowchart LR; 
      F(Forums);
      P(Publications);
      W(Websites);
  click F "/HealthECCO/community-resources/blob/main/forums.md"
  click P "/HealthECCO/community-resources/blob/main/publications.md"
    subgraph Tools
      DA(Data Acquisition)-->DP(Data Processing);
        subgraph BioCypher
            DP-->DM(Data Mapping);
          end
      DM-->DO(Data Output);
     end
    click DA "https://www.github.com"
```
## Data Acquisition

## Data Processing

## Data Mapping

## Data Output
