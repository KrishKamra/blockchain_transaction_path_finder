# 🔗 Blockchain Transaction Path Finder

### **AI-driven graph analysis for tracing transaction routes and evaluating wallet risk levels.**

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Python: 3.13+](https://img.shields.io/badge/Python-3.13+-blue.svg)
![Framework: FastAPI](https://img.shields.io/badge/Framework-FastAPI-009688.svg)
![Library: NetworkX](https://img.shields.io/badge/Library-NetworkX-orange.svg)

---

## 📖 Overview

The **Blockchain Transaction Path Finder** is a production-grade analytical engine designed to solve the "needle in a haystack" problem within distributed ledgers. By treating blockchain addresses as nodes and transactions as edges, this tool allows investigators and developers to map complex financial flows with mathematical precision.

This project was born from the need for a low-latency, "Silicon Minimalist" approach to anti-money laundering (AML) and security auditing. Unlike heavy enterprise tools, it focuses on high-performance graph traversal and real-time risk propagation.

### Why this exists:
* **Traceability:** Instantly identify the shortest or most "risky" path between any two wallets.
* **Security:** Proactively detect suspicious clusters using dynamic risk scoring.
* **Efficiency:** Optimized for Intel NPU hardware, ensuring high-speed analysis without heavy GPU overhead.

---

## 💎 Core Highlights

| Feature | Description | Icon |
| :--- | :--- | :---: |
| **Path Finding** | BFS, DFS, and $A^*$ implementations for route optimization. | 🚀 |
| **Risk Scoring** | Dynamic propagation of risk based on node proximity and value. | ⚖️ |
| **Interactive Viz** | 3D interactive network maps powered by Pyvis and React. | 🌐 |
| **First-Principles** | Built from scratch to maximize transparency and "under the hood" control. | 🛠️ |

---

## 🏗️ Architecture Overview

```mermaid
graph LR
    A[Synthetic Data Generator] --> B[(Blockchain CSV)]
    B --> C{Graph Processor}
    C --> D[BFS/DFS Search]
    C --> E[A* Heuristic Engine]
    D --> F[Path Analyzer]
    E --> F
    F --> G[Dynamic Risk Propagator]
    G --> H[Interactive HTML Viz]
    G --> I[Final PDF Report]
```


### Architectural Highlights:
* **Graph-Centric Design:** Leverages `NetworkX` for robust directed-graph operations.
* **Heuristic Optimization:** The $A^*$ implementation uses transaction value and risk as weight factors.
* **Stateless Analysis:** Designed to be wrapped in a `FastAPI` layer for microservice deployment.

---

## 🔍 Technical Deep Dive

### Performance Metrics
Based on project evaluation, the system demonstrates high reliability in detecting suspicious routes:
* **Accuracy:** 95.0%
* **Recall:** 100%
* **Precision:** 81.8%

### Core Components
| Module | Technology | Responsibility |
| :--- | :--- | :--- |
| **Agent Engine** | Python / NetworkX | Pathfinding and Risk Propagation. |
| **Visualization** | Pyvis / HTML5 | Interactive node-link diagrams. |
| **Report Gen** | ReportLab | Automated PDF performance insights. |

---

## ✨ Key Features

* **Advanced Pathfinding:** Toggle between BFS (breadth), DFS (depth), and $A^*$ (optimized) to find transaction links.
* **Dynamic Risk Propagation:** Risk isn't static; it flows through the network. When a high-risk wallet interacts with others, the system recalculates proximity scores in real-time.
* **Visual Network Analysis:** View your data through an interactive `interactive_blockchain.html` file that allows for zooming, filtering, and node inspection.

---

## 📂 Project Structure

```text
blockchain_transaction_path_finder/
├── .gitignore                   # Excludes checkpoints and cache
├── main.ipynb                   # Primary development and logic notebook
├── requirements.txt             # Project dependencies
├── synthetic_blockchain_data.csv # Generated transaction dataset
├── interactive_blockchain.html  # Interactive graph visualization
├── Blockchain_Final_Report.pdf  # Comprehensive performance insights
└── README.md                    # Modern documentation
```

---

## 🚀 Quick Start

### 1. Clone the Repository
```bash
git clone https://github.com/KrishKamra/blockchain_transaction_path_finder.git
cd blockchain_transaction_path_finder
```

### 2. Install Dependencies
Ensure you have Python 3.13+ installed.
```bash
pip install -r requirements.txt
```

### 3. Run the Analysis
Open your Jupyter environment and execute `main.ipynb` or run via CLI:
```bash
python main.py
```

---

## 🗺️ Roadmap

- [x] Phase 1: Core Graph Representation & Search Algorithms.
- [x] Phase 2: Dynamic Risk Scoring Implementation.
- [x] Phase 3: Interactive Visualization Engine.
- [ ] Phase 4: Integration with real-time Ethereum/Bitcoin RPC providers.
- [ ] Phase 5: NPU-accelerated sub-graph matching for fraud patterns.

---

## 🛠️ Contributing

Contributions are what make the open-source community an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 👨‍💻 Author

**Krish Kamra**
 
**License:** Distributed under the MIT License. See `LICENSE` for more information.

---

