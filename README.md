# Contact Tracing Ball Tree

Efficient spatial querying system for infectious disease contact tracing using Ball Tree algorithm. Simulates real-time proximity detection between infected individuals and student populations with configurable distance and time thresholds.

## Features

- **Ball Tree Spatial Indexing**: O(log n) proximity queries vs O(n) brute-force
- **Threshold-Based Filtering**: Distance (meters) + time window (minutes) criteria
- **Synthetic Data Generation**: Simulates 1,000+ student movement patterns
- **Geospatial Visualization**: Matplotlib plots of infection spread and contact clusters
- **Performance Benchmarking**: Compares Ball Tree vs brute-force search

## Installation

```bash
git clone https://github.com/asma1463/contact-tracing-balltree.git
cd contact-tracing-balltree
pip install -r requirements.txt
