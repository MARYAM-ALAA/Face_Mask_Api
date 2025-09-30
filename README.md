# Sign Language Project

A small sign-language repo that includes training artifacts, a simple API and a demo notebook.

---

## Data & large files

GitHub does not accept very large files, so the dataset and some large model files are hosted on Google Drive:

https://drive.google.com/drive/folders/1qsUHYwlzRhIQdolXJUorkp8aZHImtjJu?usp=sharing

> **Important:** download the large files and place them in the repository folder (or the expected paths used by the code) before running training or inference.

---

## Contents / what each file does

- `README.md` — this file.  
- `SignLanguageModel.ipynb` — Jupyter notebook for model exploration / training / evaluation.  
- `app.py` — simple API / web server to run the model for inference (start this to serve predictions).  
- `main.py` — training or main entry point used for experiments (check notebook / comments for exact usage).  
- `requirements.txt` — Python dependencies required by the project.  
- `sign_model.pth` (or `sign_model.path`) — pre-trained model file. **(Large)** — stored on Google Drive (see link above).  
- `train_manifest.csv` — training metadata / manifest (small sample).  
- `val_manifest.csv` — validation metadata / manifest.

---

## Quick start (run on any machine)

These steps let anyone run the project on a local machine (Windows / macOS / Linux). Copy & paste the commands in a terminal.

### 1. Clone the repository
```bash
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>
```
طط
