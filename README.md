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
  flowchart TD; 
      F(Forums);
      P(Publications);
      W(Websites);
  click F "/HealthECCO/community-resources/blob/main/forums.md"
  click P "/HealthECCO/community-resources/blob/main/publications.md"
    subgraph Tools
      direction TB;
      DA(Data Acquisition)-->DP(Data Processing);
        subgraph BioCypher
            
            DP-->DM(Data Mapping);
          end
      DM-->DO(Data Output);
     end
    click DO "/HealthECCO/community-resources/blob/main/README.md/#data-output"
```
## Data Acquisition

## Data Processing

## Data Mapping

## Data Output
