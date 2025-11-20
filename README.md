 this code is directly related to the manuscript you are currently submitting to The Visual Computer.
 PV Defect Detection
A deep learning-based project for photovoltaic (PV) panel defect detection using two benchmark datasets: PVEL-AD and PV-Multi-Defect.

📁 Datasets
PVEL-AD Dataset
Description: A comprehensive dataset for PV panel anomaly detection

Link: https://github.com/binyisu/PVEL-AD

Features: Contains various types of PV panel defects and anomalies

PV-Multi-Defect Dataset
Description: Multi-defect dataset for photovoltaic panel inspection

Link: https://github.com/CCNUZFW/PV-Multi-Defect

Features: Includes multiple defect categories for comprehensive PV panel inspection

⚙️ Experimental Setup
Hardware Environment
CPU: Intel® Xeon™ i5-14600KF
GPU: NVIDIA GeForce RTX 5060 Ti
OS: Windows
Software Environment
Python: 3.12
PyTorch: 2.7.0
CUDA: 12.8
Training Parameters
Parameter	Value
Optimizer	SGD
Epochs	500
Batch Size	64
Initial Learning Rate	0.01
Momentum	0.937
Weight Decay	0.0005
🚀 Quick Start
Installation
# Clone the repository
git clone https://github.com/your-username/pv-defect-detection.git
cd pv-defect-detection
# Install dependencies
pip install -r requirements.txt
Data Preparation
Download the datasets from the provided links
Organize the data structure as follows:
data/
├── PVEL-AD/
│   ├── train/
│   └── test/
└── PV-Multi-Defect/
    ├── train/
    └── test/
Training
python train.py --dataset PVEL-AD --epochs 500 --batch-size 64 --lr 0.01
Evaluation
python evaluate.py --dataset PV-Multi-Defect --weights best_model.pth
📊 Results
(Add your experimental results, metrics, and comparisons here)

🤝 Contributing
Contributions are welcome! Please feel free to submit pull requests or open issues for improvements.

📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

🙏 Acknowledgments
Thanks to the creators of PVEL-AD and PV-Multi-Defect datasets
