<!--
  Profile README for @nabilrakaiza
  Repo must be named EXACTLY "nabilrakaiza".
  TODO before pushing: verify every repo link. Slugs are guesses.
-->

<div align="center">

# `nabil rakaiza abror`

**Data Science & Analytics @ NUS · CS second major**

*Open to Jan 2027 internships:*
`AI Engineer` · `ML Engineer` · `Data Scientist` · `Software Engineer` · `Data Engineer` · `Data Analyst`

[**portfolio**](https://nabilrakaiza.vercel.app) · [**linkedin**](https://linkedin.com/in/nabilrakaiza) · [**email**](mailto:nabilraka1234@gmail.com)

</div>

<br/>

```console
$ whoami

nabil — y3 at NUS, singapore. currently interning in distribution ops at
singlife, where i turn manual reporting into python that runs itself.

i mostly work on NLP, LLMs, and retrieval. my actual hobby is reimplementing
things that already exist: GPT-1, a transformer NMT model, a chess engine.
it is slower than importing them. it is also the only way i have ever
properly understood any of them.

$ _
```

<br/>

## about

I like the part of a project where the obvious approach stops working.

Cosine similarity ranking short conversational queries badly. A CNN-LSTM scoring 0.87 macro F1 on raw sensor data and 0.54 on the same data after somebody helpfully engineered features for it. SMOTE making a model *worse*. Those are the moments I remember, and most of what I build ends up organised around chasing one of them down.

Outside of that: TA for **CS2030** and **CS2040** at NUS, 20+ students a week on Java, OO design, and data structures. Previously Data Science Intern at **Quantum Teknologi Nusantara** in Jakarta, and Senior Developer at **PINUS**, leading two juniors on the org's forms platform.

<sub>GPA 4.63/5.00 · Top Student in CS1010S (Programming Methodology I) and IT1244 (AI & Machine Learning) · A+ in CS2040</sub>

<br/>

## stack

```python
stack = {
    "core":      ["Python", "TypeScript", "Java", "SQL", "R"],
    "ml":        ["PyTorch", "scikit-learn", "XGBoost", "LightGBM", "SHAP", "pandas"],
    "llm":       ["LangChain", "Hugging Face", "transformers.js", "ONNX Runtime Web"],
    "retrieval": ["pgvector", "Postgres FTS", "hybrid search (RRF)", "eval harnesses"],
    "product":   ["Next.js", "React Native + Expo", "Flask", "Streamlit", "Supabase"],
    "at_work":   ["Qlik Sense", "Power Automate", "SharePoint", "openpyxl"],
}

learning_next = ["CS4225 (big data)", "CS4246 (AI planning)", "mech interp"]
```

<br/>

## projects

**[social-sim-rag](https://github.com/nabilrakaiza/social-sim-rag)** · `TypeScript` `pgvector` `Gemini`
A narrative simulation with three characters, each holding siloed memory across a 30-day run and no scripted dialogue. Built a 23-case labelled eval harness first, then moved retrieval MRR from 0.47 to 0.86. Short greetings turned out to be unrankable by embedding similarity at any threshold, so I replaced the threshold with a lexical intent gate: correct no-retrieval went from 0% to 100% with zero hit-rate loss.

**[id-en-translator](https://github.com/nabilrakaiza/id-en-translator)** · `PyTorch` `Gradio`
Indonesian to English NMT. Transformer written from scratch, trained on `opus-100` on one Colab T4, deployed live on Hugging Face Spaces.

**[human activity recognition](https://github.com/NbF5/CS3244-repo)** · `CNN-LSTM` `time series`
94.24% accuracy and 0.869 macro F1 on UCI HAR from raw sensor windows. The same architecture fed the dataset's 561 pre-engineered features got 0.54. Class weighting and SMOTE both degraded the raw-sequence baseline, which is the opposite of what the imbalance playbook says should happen.

**[automatic survey analyzer](https://github.com/nabilrakaiza/automatic-survey-analyzer)** · `XGBoost` `SHAP` `Streamlit`
Five-stage pipeline that takes a raw survey export and returns a written report: design flags, XGBoost + SHAP on what drives incomplete responses, DBSCAN segmentation with LLM column identification, sentiment analysis, and a synthesis pass.

**[oil temperature forecasting](https://github.com/nabilrakaiza/oil-temp-prediction)** · `LSTM` `GRU` `RFE`
13 models across 2 transformers and 3 horizons, with XGBoost-based feature elimination and 5-fold time-series CV. RNNs won the 1-hour horizon, CNN/LSTM won the 1-week.

**[papper](https://github.com/nabilrakaiza/papper)** · `React Native` `Supabase`
POS system for a real kitchen. Manager PIN overrides through `SECURITY DEFINER` RPCs with an audit trail, ingredient-level COGS, soft stock warnings, Bluetooth thermal receipt printing.

<details>
<summary><b>also on the shelf</b></summary>

<br/>

**SATPAM** · Concept for a browser-side detector for illegal gambling and lending ads in Indonesia. Frozen text and CLIP embeddings with one small detection head per harm domain, so a new domain costs three classifiers instead of a new model. Measured at 537ms text encode, 180ms per image, in-browser. Submitted to Datathon UI 2026, placed 37th.

**fairy chess engine** · Minimax with alpha-beta, ported from Python to TypeScript, with custom Squire and Combatant pieces. Playable on the portfolio.

**GrindHub** · Productivity app with an LLM study chatbot on a Flask + LangChain service layer.

</details>

<br/>

<div align="center">
<img height="150" src="https://github-readme-stats.vercel.app/api?username=nabilrakaiza&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117&title_color=2dd4bf&icon_color=8b5cf6&text_color=8b949e" alt="stats"/>
<img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=nabilrakaiza&layout=compact&langs_count=6&hide_border=true&bg_color=0d1117&title_color=2dd4bf&text_color=8b949e" alt="languages"/>
</div>

<div align="center">
<sub>always up for a conversation about retrieval, evals, or anything worth rebuilding from scratch.</sub>
</div>
