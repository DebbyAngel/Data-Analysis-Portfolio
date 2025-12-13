# Network Analysis of the Web-Google Graph

## Project Overview
This project explores the structural properties of the **Web-Google network**, a large-scale directed graph representing web pages and hyperlinks between them. Using network analysis techniques, the study examines connectivity patterns, influential nodes, and the overall robustness of the network.

## Problem Statement
Large web networks often contain millions of interconnected pages, making it difficult to understand how information flows and which nodes play critical roles. This project aims to identify key structural characteristics of the Web-Google graph and determine which nodes are most central to network connectivity and influence.

## Dataset & Files (Hosted on Google Drive)
All project files are located in a shared Google Drive folder:

**[Click here to access Project Files](https://drive.google.com/drive/folders/1nHORtJ0Z5k6dgPoEEx-3E7e-xIQ2XrQC)**

Inside the folder, you’ll find:
- **Graph dataset** (`web-Google.txt`) — Web-Google directed network data  
- **Jupyter Notebook** — Network construction and analysis workflow  
- **PDF analytical report** — Detailed explanation of methods and findings  
- **Presentation slides** — Visual summary of the network analysis results  

## Network Construction
- Loaded the Web-Google edge list as a directed graph.
- Constructed the network using NetworkX.
- Verified node and edge counts to ensure data integrity.

## Analysis Approach
The analysis focused on understanding both global and local network structure:
- Degree distribution analysis
- Identification of highly connected and influential nodes
- Examination of connectivity patterns and components

## Centrality & Connectivity Analysis
- Computed degree, betweenness, and closeness centrality measures.
- Identified hubs and structurally important nodes.
- Evaluated node influence on information flow.

## Network Robustness
- Assessed network resilience by analyzing the effect of removing high-centrality nodes.
- Observed significant fragmentation when key hubs were removed.
- Highlighted structural vulnerabilities within the network.

## Key Findings
- The network exhibits a scale-free structure with few highly connected hubs.
- A small number of nodes dominate connectivity and influence.
- Removing central nodes significantly impacts network stability.
- Most nodes have low connectivity, while few act as major hubs.

## Conclusion
This analysis demonstrates how large web networks are shaped by a small number of influential nodes. Understanding these structural properties is essential for applications such as search optimization, information diffusion, and network resilience planning.

## Tools & Libraries
- Python  
- NetworkX  
- Pandas  
- Matplotlib  

## Author
- **Muoghalu Chinedu Deborah**  
- **LinkedIn:** [Muoghalu Chinedu Deborah](https://www.linkedin.com/in/chinedu-muoghalu-321979b9)  
- **GitHub:** [DebbyAngel](https://github.com/DebbyAngel)
