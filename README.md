# Gephi Network Analysis - Engineering Firms in World Cities

This project analyzes the global connectivity of engineering and architectural firms using a network graph constructed from the dataset **"Engineering/Architectural Firms in World Cities: Nodal Size and Network Connectivity"**, sourced from the GaWC (Globalization and World Cities) Research Network.

## Dataset Overview

- **Nodes**: Represent global cities where engineering/architectural firms operate. (856 nodes)
- **Edges**: Represent connections established by the presence and operations of firms across multiple cities. (705 edges)
- **Source**: [GaWC Dataset](https://gawc.lboro.ac.uk/gawc-worlds/gawc-data/dataset-14/)

### Key Attributes
1. **Rank**: Indicates the importance of a city based on its total connectivity.
2. **City**: Lists the cities involved in the network.
3. **Total Connectivity**: Reflects the overall connections a city has within the network.
4. **Proportion of Highest**: Shows each city's connectivity as a fraction of the most connected city.

## Structural Properties of the Network

### Graph Properties:
- **Nodes**: 856  
- **Edges**: 705  
- **Network Diameter**: 3  
- **Graph Density**: 0.001  
- **Modularity**: 0.992  
- **Average Clustering Coefficient**: 0  
- **Average Degree**: 0.824  
- **Average Path Length**: 1.049  

### Centrality Metrics:
- **Betweenness Centrality**: The majority of cities (847/856) have a centrality of 0, while a few key cities serve as intermediaries.
- **Closeness Centrality**: 72.57% of cities are poorly connected, with a small core exhibiting high connectivity.
- **Eigenvector Centrality**: Influence is concentrated in a few global hubs.
- **PageRank**: Dominated by a few central cities, with most cities showing minimal influence.
- **Hub and Authority Scores**: Highlight the dominance of a few cities acting as key connectors and authorities.

### Connected Components:
- **Count**: 160  
- **Observation**: High fragmentation with many isolated clusters, indicating sparse global connectivity.

## Key Observations
1. **Sparse Network**: A graph density of 0.001 indicates strategic, selective connectivity.
2. **Small-World Nature**: Despite sparse connections, the low average path length (1.049) ensures efficient interaction between cities.
3. **High Modularity**: The network forms distinct clusters of cities, each dominated by regional hubs.
4. **Centralized Influence**: A few cities serve as critical hubs for global operations, dominating metrics like PageRank and Eigenvector Centrality.
5. **Vulnerability**: Targeting these central cities could disrupt the network's structure.

## **Visualization**

The network visualization created using **Gephi** reveals clustering among cities and highlights key hubs:

- **High-Modularity Clusters**: These clusters indicate distinct regional or sectoral groupings, showing how certain cities dominate in specific regions or industries.
- **Sparse Connectivity**: The absence of a clustering coefficient (average clustering coefficient = 0) reflects the sparse nature of connectivity between nodes in the network.

For a deeper dive into the network properties and additional visual insights, please refer to the **detailed report** [report](Report.docx)


## Repository Contents
- **Dataset**: The original dataset and processed files for analysis.
- **Gephi Files**: `.gephi` files used for visualization and analysis.
- **Analysis Report**: Detailed summary of the network properties and findings (`Report.docx`).

## How to Use
1. **Open Dataset**: Download the dataset from the repository or the source.
2. **Visualize in Gephi**: Use the `.gephi` files to explore the network.
3. **Modify the Network**: Experiment with various layouts, modularity settings, or apply advanced centrality measures.

## Conclusion
The **"Engineering/Architectural Firms in World Cities"** dataset reveals a hierarchical and modular network structure, where a few cities play a dominant role in global connectivity. The network's efficiency, despite its sparsity, highlights the strategic placement of firms in key global cities.

---

For further details, refer to the [report](Report.docx) included in this repository.
