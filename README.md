# Aegis-X Lite: Autonomous AI SOC Copilot

**Aegis-X Lite** is a fully self-contained, locally deployable, AI-powered Security Operations Center (SOC) copilot. It integrates **Reinforcement Learning (RL)** for sub-second tactical defense decisions with **Retrieval-Augmented Generation (RAG)** and **Local LLMs** (Llama 3/Mistral) for deep threat analysis and explainability.

Designed for privacy-first environments, Aegis-X Lite operates entirely offline without external APIs, ensuring zero data leakage.

### Key Features
*   **Hybrid AI Architecture:** Combines RL (PPO/DQN) for speed with LLMs for reasoning.
*   **Privacy-First:** Runs 100% locally using Ollama, FAISS, and PyTorch.
*   **Explainable AI:** Provides structured reasoning and MITRE ATT&CK context for every automated action.
*   **Interactive Dashboard:** Real-time incident simulation and response visualization via Streamlit.

### Tech Stack
*   **Backend:** Python, FastAPI, PyTorch, Stable Baselines3
*   **AI/ML:** Ollama (Llama 3), SentenceTransformers, FAISS
*   **Frontend:** Streamlit, Plotly