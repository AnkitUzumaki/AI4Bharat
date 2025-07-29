# Airavata Quantized LLM API

This project demonstrates quantization of Ai4Bharat's Airavata LLM and serves it via a FastAPI backend.

## 🚀 Features
- 4-bit quantized model using `bitsandbytes`
- Runs on GPU (or CPU fallback)
- FastAPI backend `/predict` endpoint
- Benchmarking script to measure latency

## 🛠 Setup

```bash
pip install -r requirements.txt
