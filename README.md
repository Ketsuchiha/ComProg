# ComProg Streamlit Deployment

This repository contains an industrial manufacturing dashboard built with Streamlit.

## Run locally

```powershell
pip install -r requirements.txt
streamlit run streamlit_app.py
```

## Streamlit Cloud

Deploy the repository root and use `streamlit_app.py` as the app entrypoint.

The root `requirements.txt` includes the packages Streamlit Cloud needs to install, including `plotly` and `streamlit-autorefresh`.