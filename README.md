# UnifoLM-WMA-0 Inference Acceleration

> **7.77× speedup** for Unitree's humanoid robot world model — ASC26 Competition Project

## 🏆 About

This project was developed by **Team Zero Point** from 
**Chongqing University of Posts and Telecommunications (CQUPT)** 
for the **ASC26 World Student Supercomputer Challenge**.

## 📊 Results

| Optimization | Speedup |
|--------------|---------|
| Baseline | 1.00× |
| + DDIM Step Reduction | 2.50× |
| + Kernel Fusion | 3.33× |
| + Async Pipeline | 3.92× |
| + Mixed Precision | 5.60× |
| + KV Cache | 7.00× |
| + CUDA Graph | **7.77×** |

## 🛠️ Techniques

- DDIM sampling step reduction (50→20)
- CUDA kernel fusion
- Asynchronous pipeline with CUDA streams
- FP16 mixed precision
- KV cache + sparse attention
- CUDA graph capture

## 📁 Structure

🚧 Under construction...

## 📄 License

Apache 2.0
