# 🚀 Gemma LLM Fine-Tuning, Evaluation & Deployment Pipeline

This repository showcases the **fine-tuning**, **evaluation**, **optimization**, and **deployment** of the **Gemma-7B** language model using **QLoRA** on reasoning datasets like **DeepSeek-R1**. It includes comprehensive evaluation, inference optimization using **knowledge distillation**, and **preference tuning (DPO)**. The final deployment is managed through a scalable **MLOps pipeline** integrating **Streamlit**, **Flask**, **MLflow**, **Docker**, and **KubeFlow**.

---

## 📋 Features

- ✅ **LLM Fine-Tuning:**  
  - Fine-tuned **Gemma-7B** using **QLoRA** on reasoning datasets (e.g., **DeepSeek-R1**).  
  - Efficient 4-bit quantization applied for memory optimization.
  - Weights & Biases Run:  
  [View Fine-Tuning on W&B ](https://wandb.ai/janvi24/Fine-tune-gemma-7b%20on%20Medical%20COT%20Dataset?nw=nwuserjanvi24)

- ✅ **LLM Evaluation:**  
  - Tracked metrics and performance using **MLflow** and **DagsHub**.  
  - Comprehensive evaluation covering BLEU, ROUGE, BERTScore, and Exact Match.
  - DagsHub MLflow Tracking:  
  [View Experiments on DagsHub and MLFlow ](https://dagshub.com/janvichokshi1998/gemma-7b-unsloth-mediQA.mlflow/#/experiments/1?viewStateShareKey=60b5838b3c07b10d688fd52b4dd6c37593b139dcfb12d21877e12fcb552682f6)

- ✅ **Inference Optimization:**  
  - Applied **knowledge distillation** to compress and distill the Gemma-7B into a smaller **Gemma-2B** model.  
  - Improved inference speed and efficiency.

- ✅ **Preference Tuning (DPO):**  
  - Enhanced model outputs with **Direct Preference Optimization (DPO)** for better alignment and reasoning.

- ✅ **MLOps Deployment Pipeline:**  
  - Built an end-to-end deployment pipeline using:  
    - **Streamlit + Flask** for interactive UI and API endpoints.  
    - **MLflow** for experiment tracking and model versioning.  
    - **Docker** and **KubeFlow** for containerization and orchestration.
