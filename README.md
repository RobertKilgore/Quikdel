# QuikDel

**QuikDel** is a scalable, Q-learning-based framework for optimizing **online food delivery routing** in dynamic, real-time environments. Unlike traditional static planning methods, QuikDel adapts to live order flows using distributed learning agents trained via reinforcement learning. It introduces a hierarchical routing architecture by dividing cities into **hotspots** and **superspots**, enabling efficient coordination among agents and reducing computational overhead.

## Collaborators
This work is only possible due to the additional hard work of:
- Md Nahid Hasan
- Ashman Mehra
- Yusuf Ozdemir
- Dr. Vaskar Raychoudhury
- Dr. Snehanshu Saha


## 🔍 Key Features
- 🚀 **Real-time routing** for dynamically arriving delivery orders
- 🧠 **Q-learning agents** trained offline, deployed online for fast decisions
- 🌆 **Hierarchical city partitioning** for scalable and modular delivery zones
- 📊 Tested across multiple U.S. cities (New York, Philadelphia, Chicago, Columbus)
- 📈 Outperforms baseline methods like DeliverAI and point-to-point routing

## 🛠 Components
- **QCense**: City data aggregation and census-based feature extraction
- **Hotspot/Superspot Selector**: Clustering logic to define city partitions
- **QuikSim**: A discrete-event simulator to benchmark delivery performance
- **Training Modules**: CTDE-based Q-learning for intra- and inter-cluster routing

## 📄 Paper & Results
This work was submitted to IEEE (2025).

## How To:
This is meant to be run using Google Colab. Download the repo and set your paths accordingly
