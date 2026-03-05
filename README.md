# Blockchain Transaction Path Finder

An AI-driven graph analysis tool designed to trace transaction paths and evaluate wallet risk levels within a blockchain network. This project implements graph-based search algorithms to identify links between wallets and evaluate security metrics.

## 🚀 Key Features
* **Pathfinding Algorithms:** Implementation and comparison of DFS, BFS, and $A^*$ search.
* **Risk Analysis:** Dynamic evaluation of wallet risk scores based on transaction behavior.
* **Interactive Graphs:** Full-scale interactive network visualization (`interactive_blockchain.html`) using Pyvis.
* **Performance Metrics:** The agent achieves high precision and accuracy in path detection.

## 📊 Performance Summary
Based on the final evaluation, the pathfinder achieved the following:
* **Accuracy:** 95.0%
* **Precision:** 81.8%
* **Recall:** 100%
* **F1 Score:** 90.0%

## 🛠️ Installation
If you wish to run this locally, install the dependencies:

pip install -r requirements.txt

## 📂 Project Structure
```text
├── main.ipynb                 # Core logic and algorithm implementation
├── synthetic_blockchain_data.csv # Transaction dataset
├── interactive_blockchain.html # Interactive graph visualization
├── Blockchain_Final_Report.pdf # Detailed performance report
├── requirements.txt           # Python dependencies
└── .gitignore                 # Files to exclude from Git

