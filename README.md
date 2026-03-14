# 🧬 Breast Cancer Drug–Gene Interaction Network Analysis

[![Tool: Cytoscape](https://img.shields.io/badge/Tool-Cytoscape-orange.svg)](https://cytoscape.org/)
[![Domain: Cancer Bioinformatics](https://img.shields.io/badge/Domain-Cancer_Bioinformatics-purple.svg)]()
[![Network Analysis](https://img.shields.io/badge/Analysis-Network_Topology-blue.svg)]()
[![Status](https://img.shields.io/badge/Status-Research_Project-success.svg)]()

> **A Cytoscape-based network analysis of drug–gene interactions focusing on node degree centrality to identify and visualize key therapeutic targets in breast cancer.**

---

# 🔬 Drug–Gene Interaction Network Analysis

## 📌 Overview

This repository contains the **data and visualizations for a drug–gene interaction network analysis**.

The network was constructed and analyzed using **Cytoscape** to map the relationships between **key genes and potential pharmacological agents** involved in breast cancer.

This project demonstrates how **network biology approaches** can help identify **important therapeutic targets** and understand molecular connectivity within cancer pathways.

---

## 🧠 Project Context

This analysis focuses on evaluating the **network topology of breast cancer targets** to identify **critical vulnerabilities**.

By analyzing metrics such as **Degree Centrality** within Cytoscape, the project highlights:

- Highly connected **hub genes**
- Their corresponding **drug interactions**
- Key **therapeutic targets**

This approach helps bridge the gap between:

- 🧬 **Molecular pathways**
- 💊 **Drug discovery**
- 🎯 **Therapeutic intervention**

---

## 📂 Repository Contents

This repository includes the **raw network data** and the **exported visual representations** of the analysis.

### 📄 `gene_interaction_results-27_2_2026.tsv.sif`

**Description**

- A **Simple Interaction Format (SIF)** file used to construct the network in Cytoscape.

**Details**

- Defines the **nodes**  
  - Genes  
  - Drugs  

- Defines the **edges (interactions)**  
  - Directed interactions  
  - Undirected interactions  

This file represents the **core interaction dataset** used to build the network.

---

### 📄 `gene_interaction_results-27_2_2026.tsv.pdf`

**Description**

- A **high-resolution PDF export** of the Cytoscape network visualization.

**Details**

- Displays the **clustered drug–gene interactions**
- Highlights **central nodes**
- Helps identify **highly targeted pathways**

This visualization makes the **network structure easier to interpret**.

---

## ⚙️ Methodology

The analysis followed three major steps.

### 1️⃣ Network Construction

Drug–gene interaction data was imported into **Cytoscape** using the standard `.sif` format.

```
File Format: .sif
Nodes: Genes + Drugs
Edges: Interactions
```

---

### 2️⃣ Topological Analysis

The network was analyzed using **network topology metrics**, particularly:

- **Degree Centrality**

This metric helps identify:

- Highly connected **hub genes**
- **Biologically significant targets**

---

### 3️⃣ Network Visualization

Custom **visual styles** were applied in Cytoscape to improve interpretability.

Visualization features include:

- 🎯 Distinct **gene nodes**
- 💊 Distinct **drug nodes**
- 🔗 Highlighted **interaction pathways**
- 📊 Layout optimized to emphasize **therapeutic hubs**

---

## 🧬 Research Significance

This network analysis provides insights into:

- Breast cancer **molecular interaction networks**
- Identification of **drug–gene connectivity**
- Discovery of **high-value therapeutic targets**

Network-based approaches like this are widely used in:

- **Systems biology**
- **Computational drug discovery**
- **Cancer bioinformatics**

---

## 🛠 Tools Used

- **Cytoscape** – Network construction and visualization
- **Drug–Gene Interaction Data**
- **Network Topology Analysis**

---

## 👨‍🔬 Author

**Dr. Nagendra**

Research Focus:

- Bioinformatics  
- Cancer Network Biology  
- Drug Target Discovery  
- Computational Biology  

---

## ⭐ Repository Purpose

This repository demonstrates how **drug–gene interaction networks** can be used to:

- Identify **critical cancer targets**
- Visualize **molecular interaction networks**
- Support **computational drug discovery research**

---

⭐ *If this project helps your research, consider giving the repository a star.*
