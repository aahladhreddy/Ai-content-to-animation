# Ai-content-to-animation
An AI-powered creative engine that takes text, scripts, or ideas and instantly generates animations.
#environment
python -m venv .venv
source .venv/Scripts/activate   # Windows PowerShell
pip install -r requirements.txt
python -m spacy download en_core_web_sm
#run
streamlit run app/ui.py
