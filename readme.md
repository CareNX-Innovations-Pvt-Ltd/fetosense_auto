# Fetosense Auto

**A ML-based automated analysis tool for portable fetal monitoring (NST/CTG).**

This repository contains the training and model artifacts for Fetosense Auto—an advanced system for automated interpretation of Non-Stress Test (NST) / Cardiotocography (CTG) data, developed by CareNX Innovations Pvt. Ltd.

---

##  Project Structure

```
.
├── data/
│   └── sample_carenx.csv         # Example dataset for testing & training
├── plots/                        # Visualization outputs (e.g., loss curves)
├── saved_model/
│   └── final_model/              # Trained ML model (TensorFlow or similar)
├── fetosense_train.ipynb         # Jupyter notebook for model training
├── fetosense_cnn.ipynb           # Jupyter notebook for CNN model exploration
├── README.md                     # This documentation
├── CODE_OF_CONDUCT.md            # Community guidelines
└── LICENSE                       # MIT License
```

---

##  Getting Started

### Prerequisites

- Python 3.8+ (recommend using virtualenv or conda)
- Jupyter Notebook / JupyterLab
- Common libraries:
  ```bash
  pip install numpy pandas matplotlib seaborn tensorflow scikit-learn
  ```

### Usage

1. **Explore & Train**  
   Open and run `fetosense_train.ipynb` to see the full training pipeline—data preprocessing, model building, training, and evaluation.
   
2. **Experiment with CNN**  
   Explore the convolutional neural network approach in `fetosense_cnn.ipynb`.

3. **Visualize Performance**  
   Check the `plots/` directory to view training metrics and model comparisons.

4. **Deploy or Use Saved Model**  
   The trained model is available under `saved_model/final_model/`—load it into your production or evaluation pipeline.

---

##  Sample Data

- `data/sample_carenx.csv` provides sample data format and content to get you started quickly. Feel free to replace it with real CTG/NST datasets as needed.

---

##  Contribution

Contributions are welcome! Please refer to our [Code of Conduct](CODE_OF_CONDUCT.md) for community guidelines.

---

##  License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

##  About Fetosense by CareNX Innovations

Fetosense is a smartphone-based, wireless, portable fetal monitor that integrates CTG/NST capability for expectant mothers, enabling remote and affordable fetal monitoring in India and globally ([carenx.com](https://carenx.com/?utm_source=chatgpt.com)). This repository powers the “Auto” aspect—bringing automated, AI‑driven interpretation to Fetosense’s monitoring data.
