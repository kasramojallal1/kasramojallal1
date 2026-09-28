# Kasra Mojallal

**AI/Software Engineer** · LLMs, retrieval, and computer vision in production · Canada

[LinkedIn](https://www.linkedin.com/in/kasra-mojallal/) · [Google Scholar](https://scholar.google.ca/citations?hl=en&user=JVfAdmsAAAAJ) · [kasramojallal1@gmail.com](mailto:kasramojallal1@gmail.com)

I take AI products from architecture to production: system design, model services, and the infrastructure that ships them. Before industry I did research at the University of Windsor on fine-tuned LLMs for robotics, federated learning, and LLM security.

## Now

**Senior AI/Software Engineer, MealLens** (Sep 2025 to present; company code is private)

- Lead one of the company's products from architecture to production, including its **AI microservices**, working with a team of engineers and interns.
- Build **hybrid retrieval**, **computer vision**, and **fine-tuned LLM** services.
- Drive **inference cost reductions** through right-sized cloud infrastructure, and replaced a vendor solution with an in-house fine-tuned model.
- Designed the **CI/CD and release workflow** across backend and mobile: per-PR test and coverage gates, one-command deploys with rollback, dev-by-default promotion to prod, and per-branch local environments.

## Projects

| Project | What it is | Result |
|---|---|---|
| [**graph-paat**](https://github.com/kasramojallal1/graph-paat) | Offline CLI that gives AI coding agents a code graph of repositories too large for their context window. 15 languages via tree-sitter, no model calls. | On **189 real SWE-bench issues**, puts the file maintainers changed in the top 3 **50% of the time vs. 43% for graphify** |
| [**Packi**](https://github.com/kasramojallal1/llm-robotic-packer) | 3D robotic bin packing driven by a fine-tuned 3B LLM (Llama 3.2 + LoRA). | **87% bin utilization**, outperforming **11 proprietary API models** on a single 16GB consumer GPU |
| [**learning-from-demonstration**](https://github.com/kasramojallal1/learning-from-demonstration) | The Learning-from-Demonstration + LoRA/QLoRA (4-bit) pipeline that trains Packi. | Trajectories validated in a **PyBullet UR-robot simulation** |
| [**FedMod**](https://github.com/kasramojallal1/FedMod) | Vertical federated learning with multi-server additive secret sharing, no heavy cryptography. | My MSc thesis, **published at IDEAS 2025** |
| [**DRL Stock Trader**](https://github.com/kasramojallal1/stocktrader-deep-reinforcement-learning) | Ensemble deep RL trader (PPO, A2C, DDPG) with Sharpe-based model selection per rebalance, plus a Django monitoring UI. | **24% alpha over the Dow Jones Index** in walk-forward backtests on Dow-30 |
| **Health Tracker** | Fully on-device, privacy-first iPhone health app that turns smartwatch data into explained insights. Nothing leaves the phone. | Private; public release soon |

## Publications

- [Prompt Attacks and Safeguards in Large Language Models: A Survey](https://link.springer.com/chapter/10.1007/978-981-95-7078-2_29). PRICAI 2025
- [FedMod: Vertical Federated Learning Using Multi Server Secret Sharing](https://link.springer.com/chapter/10.1007/978-3-032-06744-9_10). IDEAS 2025
- Human-robot interaction for robot programming using Augmented Reality and Digital Twin. CCECE 2026
- [Prediction of TNM stage in head and neck cancer using hybrid machine learning systems and radiomics features](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/12033/120332H/Prediction-of-TNM-stage-in-head-and-neck-cancer-using/10.1117/12.2612998.short). SPIE Medical Imaging 2022
- Packi: Robotic 3D Bin Packing with LLMs Fine-tuned by Learning from Demonstration (submitted)
- Trustformer: A Trusted Federated Transformer (submitted)

## Stack

- **Languages:** Python, SQL, Bash
- **ML & LLMs:** PyTorch, TensorFlow, Hugging Face, LoRA/QLoRA, PEFT, 4-bit quantization, RAG, hybrid retrieval (BM25 + embeddings), Federated Learning, Deep RL (Stable-Baselines3), scikit-learn
- **Vision & on-device:** YOLO-World, SAM, Florence-2, OpenCV, PaddleOCR, Core ML, CUDA
- **Serving & infra:** FastAPI, Django REST Framework, Ollama, Docker, AWS (EC2, RDS, S3, CloudFront), DigitalOcean, GitHub Actions, PostgreSQL, pgvector
- **Product:** React Native, Expo, SwiftUI

## Education

- **MSc Computer Science**, University of Windsor (2024). Thesis: FedMod.
- **BSc Computer Engineering**, Amirkabir University of Technology (2022). Ranked in the top 1.3% of 148,000 participants.
