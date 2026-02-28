# breast-cancer-drug-network
"A Cytoscape-based network analysis of drug-gene interactions, focusing on node degree centrality to identify and visualize key therapeutic targets in breast cancer."
# Drug-Gene Interaction Network Analysis

## Overview
This repository contains the data and visualizations for a drug-gene interaction network analysis. The network was constructed and analyzed using [Cytoscape](https://cytoscape.org/) to map the relationships between key genes and potential pharmacological agents. 

## Project Context
This analysis focuses on evaluating the network topology of breast cancer targets to identify critical vulnerabilities. By analyzing metrics such as "Degree" centrality within Cytoscape, this project highlights highly connected hub genes and their corresponding drug interactions, bridging the gap between molecular pathways and therapeutic intervention.

## Repository Contents
This repository includes the raw network data and the exported visual representations of the analysis:

* **`gene_interaction_results-27_2_2026.tsv.sif`**: The Simple Interaction Format (SIF) file used to construct the network in Cytoscape. This file defines the nodes (genes and drugs) and the directed/undirected edges (interactions) between them.
* **`gene_interaction_results-27_2_2026.tsv.pdf`**: A high-resolution PDF export of the Cytoscape network visualization. This visualizes the clustered interactions, making it easier to identify the central nodes and heavily targeted pathways.

## Methodology
1. **Network Construction**: Drug-gene interaction data was imported into Cytoscape using the standard `.sif` format.
2. **Topological Analysis**: The network was analyzed to calculate node degree centrality, identifying the most highly connected and biologically significant targets.
3. **Visualization**: Visual styles were applied to differentiate between gene nodes and drug nodes, optimizing the layout to highlight therapeutic hubs.
