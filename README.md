## 📍 Spatiotemporal Crime Pattern Analysis – Chicago

This project presents a hybrid framework for detecting, analyzing, and forecasting crime hotspots in Chicago by integrating spatial, temporal, graph-based, and probabilistic modeling techniques. Using publicly available crime data, we used ST-DBSCAN, T-OPTICS, Clique Clustering, Spatiotemporal Graph Convolutional Networks (ST-GCN), Gaussian Mixture Models (GMM), and the Join-Less Approach for Co-Location Pattern Mining to uncover complex, evolving crime patterns on the Chicago Crime Dataset.

## 🔧 Techniques Used
- **ST-DBSCAN** – Detects evolving spatiotemporal crime hotspots using dual thresholds for space and time.
- **T-OPTICS** – Detects crime clusters based on spatial and temporal proximity, capturing irregular shapes without needing a set number of clusters.
- **Clique-Based Clustering** – Identifies dense regions of co-occurring crimes in both spatial and temporal proximity.
- **ST-GCN** – Learns temporal crime trends using a dynamic graph neural network architecture.
- **GMM (Gaussian Mixture Models)** – Detects overlapping hotspot regions through soft probabilistic clustering.
- **Join-Less Co-Location Pattern Mining** – Identifies significant spatial co-location patterns among crime types efficiently without spatial joins.


## 📊 Dataset

- **Source:** [Chicago Crime 2012 to 2017](https://www.kaggle.com/datasets/abhisheksinghblr/chicago-crime?select=Chicago_Crimes_2012_to_2017.csv)
- **Usage:** We filtered for valid latitude/longitude entries, selected crime types, and a specific multi-year range for training temporal models.

## 🛠️ Technologies Used
- Python – A Core programming language for analysis and modeling.
- Pandas, NumPy – Data manipulation and preprocessing.
- Matplotlib, Seaborn – Visualization of trends, clusters, and evaluation metrics.
- Scikit-learn – Clustering algorithms, evaluation metrics, and preprocessing utilities.
- PyTorch, PyTorch Geometric Temporal – Spatiotemporal Graph Convolutional Network (ST-GCN) implementation.
- NetworkX – Graph construction for clique clustering and dynamic network modeling.
- Geopy, Haversine – Spatial distance calculations between crime coordinates.
- Kaggle – Dataset source: Chicago Crimes 2012–2017
- Google Colab – Environment for running experiments and visualizing results
- Git & GitHub – Version control and collaborative development

## 👩‍💻 Authors
- Shreya Nilesh Gaikwad - sgaikwad2@student.gsu.edu
- Bhavana Jayappa - – bjayappa1@student.gsu.edu
- Mervyn Benedict Antonio - bmervyn1@student.gsu.edu
