# 📡 Indoor Wi-Fi Fingerprinting Localization

This project implements a **Wi-Fi fingerprinting-based indoor localization system** using machine learning. RSSI values are collected from surrounding Wi-Fi access points and used to train models that estimate the device’s location within an indoor environment.

The goal is to evaluate and compare different ML techniques, such as **K-Nearest Neighbors (KNN)** and **Random Forest**, based on localization accuracy and error metrics like RMSE and mean error.

---

## 📁 Project Structure

- 📁 `data/` – Raw and processed RSSI data  
  └── 📁 `raw/` – Collected RSSI data per location  
  └── 📁 `processed/` – Cleaned dataset ready for modeling

- 📁 `notebooks/` – Jupyter notebooks for analysis and visualization

- 📁 `src/` – Python source code modules  
  └── 📄 `data_collection.py` – RSSI scanning logic using Mac terminal  
  └── 📄 `preprocessing.py` – Data cleaning and transformation  
  └── 📄 `models.py` – ML algorithms (KNN, Random Forest, etc.)  
  └── 📄 `utils.py` – Helper functions

- 📁 `results/` – Output plots, predictions, and performance metrics

- 📄 `main.py` – Main script to run the pipeline  
- 📄 `requirements.txt` – Python dependencies  
- 📄 `.gitignore` – Ignore rules for Git version control  
- 📄 `README.md` – Project overview and documentation

---

## 📜 License

This project is licensed under the **MIT License**.  
You are free to use, modify, and distribute this software with proper attribution.

> See the [`LICENSE`](LICENSE) file for full terms.