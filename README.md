
# 🛡️ DDoS Detection System

DDoS detection system that analyzes captured network traffic to identify potential attacks using ML-based classification.

## 🔍 Features

* Detects DDoS attacks from `.pcap` or `.csv` traffic logs
* Extracts features from network flow data
* Trains and tests models to classify normal vs attack traffic

## ⚙️ Tech Stack

* Python
* Scikit-learn / TensorFlow
* Pandas, NumPy
* Wireshark (for `.pcap` capture & export)

## 🚀 Getting Started

```bash
git clone https://github.com/kpsan12/DDOS.git
cd DDOS
```

### 🧠 Train a Model

```bash
python train_model.py
```

### 📂 Run Detection on Captured Data

```bash
python detect_ddos.py --input traffic.csv
```


