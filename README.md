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
      DA(Data Acquisition)-->DP(Data Processing);
        subgraph BioCypher
          DP-->DM(Data Modelling);
          DM-->DL(Data Loading);
          end
      DL-->DO(Data Output);
    click DA "/HealthECCO/community-resources/blob/main/README.md/#data-acquisition"
    click DP "/HealthECCO/community-resources/blob/main/README.md/#data-processing"
    click DM "/HealthECCO/community-resources/blob/main/README.md/#data-modelling"
    click DL "/HealthECCO/community-resources/blob/main/README.md/#data-loading"
    click DO "/HealthECCO/community-resources/blob/main/README.md/#data-output"
```
## Data Acquisition

## Data Processing
- https://github.com/TranslatorSRI/NodeNormalization

## Data Modelling
- https://pypi.org/project/biolink-model/
- https://github.com/linkml/linkml

## Data Loading
- https://github.com/biolink/kgx/
- https://github.com/knowledge-Graph-Hub/
- https://github.com/Knowledge-Graph-Hub/kg-template

## Data Output
