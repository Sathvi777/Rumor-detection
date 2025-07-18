# 🕸️ Rumor Detection using Graph-Based Analysis

This project simulates a social media network and applies centrality and community detection techniques to identify potential rumor sources.

## 📌 Problem Statement

With misinformation spreading rapidly on social platforms, early detection of rumor sources is essential. This project uses a directed graph (NetworkX) to analyze and trace the spread of rumors via tweet nodes.

---

## 📂 Dataset

- File: `label.txt`
- Format: `label:tweet_id`
- Classes: `true`, `false`, `unverified`, `non-rumor`

---

## ⚙️ Technologies Used

- Python 3
- Pandas
- NetworkX
- Matplotlib

---

## 🔍 Methodology

1. **Data Preprocessing**: Load, clean, encode labels
2. **Graph Creation**: Simulate tweet propagation
3. **Subgraph Extraction**: Focus on rumor-labeled tweets
4. **Centrality Metrics**: Identify influential nodes using:
   - Degree centrality
   - Betweenness centrality
   - Closeness centrality
5. **Community Detection**: Apply Girvan–Newman algorithm

---

## 📈 Results

- Simulated propagation of 50 rumor nodes with 2–5 interactions each.
- Detected **X communities** in the rumor subgraph.
- Identified top 5 central nodes as most influential in rumor spreading.

---

## 🧠 Insights

- Graph theory can effectively flag possible rumor sources early in the spread.
- High-centrality nodes are prime candidates for rumor origin detection.
- Community detection helps isolate clusters for monitoring.

---

## 🚀 How to Run

1. Clone the repo
```bash
git clone https://github.com/yourusername/rumor-detection-networkx.git
cd rumor-detection-networkx
