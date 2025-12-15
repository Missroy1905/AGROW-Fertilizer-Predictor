![final-agroww-ezgif com-crop](https://github.com/user-attachments/assets/6bc935a2-3d7a-4c26-bfe6-575172d48a38)
## 🌱 AGROW-Fertilizer-Predictor: Precision Fertilizer Prediction

[![Python 3.x](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![Model: Logistic Regression](https://img.shields.io/badge/Model-Logistic%20Regression-red.svg)](https://scikit-learn.org/stable/modules/linear_model.html#logistic-regression)

---

## 💡 Overview

The **AGROW-Fertilizer-Predictor** is a web-based system designed to provide data-driven recommendations for optimal fertilizer usage. It employs a **Logistic Regression** machine learning model, which is trained on soil and environmental data to predict the ideal *level* or *type* of fertilizer required for a given crop.

This project promotes sustainable and efficient farming by minimizing resource waste and maximizing crop yield.

## ✨ Features

* **Intelligent Prediction:** Utilizes a pre-trained **Logistic Regression model** (`classifier.pkl`) for quick and accurate fertilizer level prediction based on key agricultural parameters (N, P, K, pH, etc.).
* **Web Application:** Simple and clean user interface (UI) served by the application's entry point (`main.py`).
* **Data Driven:** The full training process is transparently documented in the provided Jupyter Notebook (`Fertilizer Prediction.ipynb`).
* **User Management:** Includes a SQLite database (`users.db`) for potential user authentication and tracking prediction history.

## 🚀 Getting Started

Follow these steps to set up and run the application locally.

### Prerequisites

* Python: Version 3.8 or higher.
* Git: For cloning the repository.

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Missroy1905/AGROW-Fertilizer-Predictor.git](https://github.com/Missroy1905/AGROW-Fertilizer-Predictor.git)
    cd AGROW-Fertilizer-Predictor
    ```

2.  **Create a virtual environment (Recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Linux/macOS
    # .\venv\Scripts\activate  # On Windows
    ```

3.  **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

### Running the Application

1.  **Start the web server:**
    ```bash
    python main.py
    ```

2.  **Access the application** in your web browser at the address provided in the terminal (usually `http://127.0.0.1:5000/`).

---

## 🔬 Model and Training

The predictive core is a **Logistic Regression** classifier.

| File Name | Purpose |
| :--- | :--- |
| `Fertilizer Prediction.csv` | The raw dataset used for training the model. |
| `Fertilizer Prediction.ipynb` | Jupyter Notebook detailing data cleaning, feature engineering, training, and evaluation. **This is your primary model documentation.** |
| `classifier.pkl` | The final, saved, trained Logistic Regression model. |
| `fertilizer.pkl` | A supplementary file, likely containing necessary objects like the data scaler or label encoders. |

---

## 📂 Project Structure (Current)

This table outlines the current flat structure of the repository:

| File/Directory | Description |
| :--- | :--- |
| `main.py` | The application's entry point and web server logic. |
| `templates/` | Directory containing the front-end HTML files (e.g., `index.html`). |
| `requirements.txt` | Python dependencies. |
| `app.yaml` | Configuration file (e.g., for cloud deployment). |
| `users.db` | SQLite database for user data/history. |
| **Model/Data Files** | `Fertilizer Prediction.csv`, `Fertilizer Prediction.ipynb`, `classifier.pkl`, `fertilizer.pkl` |

---

## 🤝 Contributing

We welcome contributions! Please feel free to open issues or submit pull requests.

1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/model-optimization`).
3.  Commit your changes.
4.  Open a Pull Request.

---

