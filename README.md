# Nabil Rakaiza Abror

Data Science & Analytics @ NUS, second major in Computer Science.
Open to **July 2027** internships (5 to 6 months) as an **ML / AI Engineer, Data Scientist, or NLP/LLM (incl. research) intern**.

[Portfolio](https://nabilrakaiza.vercel.app) · [LinkedIn](https://linkedin.com/in/nabilrakaiza) · [Email](mailto:nabilraka1234@gmail.com)

## About

Third-year student in Singapore. I work mostly on NLP, AI/ML, and LLMs, and I learn things by rebuilding them from scratch: a Transformer for translation, GPT-1, and language models from n-grams up. I care about measuring things properly: eval harnesses, controlled comparisons, and saying so when a result is negative.

Previously a Distribution Operations intern at Singlife (automating reporting pipelines in Python and Qlik) and a Data Science intern at Quantum Teknologi Nusantara in Jakarta (route optimisation and LLM pipelines). Starting an Operations Automation Engineer internship at ShopBack in January 2027.

I also teach: TA for CS2030 (Programming Methodology II) and CS2040 (Data Structures & Algorithms) at NUS.

## Projects

**[interruptible-mle-agent](https://github.com/nabilrakaiza/interruptible-mle-agent)**: A tree-search LLM agent for ML engineering that you can watch and steer mid-run. Led a 4-person team; 118 four-hour runs on MLE-bench Lite. The agent beat the leaderboard median on all 63 text-task runs, and none of the human interventions we tested beat it running on its own. The report explains why.

**[socialsim-rag](https://github.com/nabilrakaiza/socialsim-rag)**: RAG narrative simulation where characters answer only from their own retrieved memories. Hybrid retrieval (Postgres full-text + pgvector, Reciprocal Rank Fusion) and a hand-labelled eval harness took MRR from 0.47 to 0.86. [Play it](https://nabilrakaiza.vercel.app/playground/socialsim).

**[papertrail](https://github.com/nabilrakaiza/papertrail)**: Kneser-Ney trigram, RNN, LSTM and Transformer language models on WikiText-2 under one evaluation protocol, plus a frozen-embedding ablation and a topic-classification probe. Test perplexity 226 → 149.5 from trigram to Transformer.

**[paperflash](https://github.com/nabilrakaiza/paperflash)**: GPT-1 built from scratch, then used to study how small Transformers learn arithmetic. Reproduced grokking on modular addition and found the Fourier structure in the learned embeddings. Multi-digit addition in progress.

**[id-en-translator](https://github.com/nabilrakaiza/id-en-translator)**: Indonesian to English translation with a Transformer and BPE tokenizer written from scratch, trained on opus-100, deployed on Hugging Face Spaces. [Try it](https://nabilrakaiza.vercel.app/playground/id-en-translator).

**[human-activity-recognition](https://github.com/nabilrakaiza/human-activity-recognition)**: CNN-LSTM on raw smartphone sensor windows (UCI HAR), 94.2% accuracy and 0.87 macro F1, vs 0.54 macro F1 on hand-engineered features with the same model.

**[Papper](https://github.com/nabilrakaiza/Papper)**: React Native + Supabase point-of-sale app running at my family's cafe, with rules enforced in Postgres row-level security.

More on my [portfolio](https://nabilrakaiza.vercel.app).

## Stack

**Languages**: Python, TypeScript, Java, SQL, R<br>
**ML**: PyTorch, scikit-learn, XGBoost, SHAP, pandas<br>
**LLM & retrieval**: Hugging Face, LangChain, LangGraph, pgvector, FAISS, hybrid search<br>
**Infra & apps**: Docker, Streamlit, Gradio, Supabase, Next.js, React Native, AWS S3
