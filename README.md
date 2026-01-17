# 🏠 Home Value Prediction App

[![Streamlit App](https://img.shields.io/badge/Streamlit-App-red)](https://homevalue-predictor.streamlit.app/)
![Python](https://img.shields.io/badge/Python-3.x-blue)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-orange)

End-to-end machine learning app to predict house prices using key property features. Built with Python and Streamlit, using a trained regression model for real-time price inference.

## Quick install & run

1. **Clone**
```bash
git clone https://github.com/<pratama-dev>/homevalue-streamlit.git
cd homevalue-streamlit
````

2. **(Recommended) Create a virtual environment**

```bash
python -m venv .venv
```

3. **Activate venv**

* Windows (CMD):

```bash
.venv\Scripts\activate
```

* Windows (PowerShell):

```bash
.venv\Scripts\Activate.ps1
```

* macOS / Linux:

```bash
source .venv/bin/activate
```

4. **Install dependencies**

```bash
pip install -r requirements.txt
```

5. **Check model files**
   Make sure these exist in the project root:

* `house_price_model.pkl`
* `feature_columns.pkl`

> If model files are >100 MB, use Git LFS or upload them to cloud storage and update README with links.

6. **Run the app**

```bash
streamlit run app.py
```

Open `http://localhost:8501` if it doesn't open automatically.
Stop the app: press `Ctrl + C` in the terminal.

---
