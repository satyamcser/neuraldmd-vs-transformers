# NeuralDMD vs Transformers: A Spectral Benchmark for Economic Signal Forecasting

This repository contains the code, experiments, and paper accompanying our ICTA 2025 accepted work:

> **NeuralDMD vs Transformers: A Spectral Benchmark for Economic Signal Forecasting**  
> *Gia Bach, Satyam Mishra, Tran Duc Tan, Vishwanath Bijalwan*  
> Accepted at ICTA 2025

## 🌐 Abstract
We propose a unified benchmarking framework comparing Koopman operator-based forecasting (NeuralDMD) with Transformer and LSTM models on real-world economic signals. Using datasets from Yahoo Finance and FRED, we evaluate accuracy, interpretability, and runtime. NeuralDMD achieves competitive RMSE while offering interpretable Koopman spectra.


## 🧠 Models Compared

- **NeuralDMD**: Koopman operator forecasting with spectral interpretability
- **LSTM**: Baseline sequence model
- **Transformer**: Self-attention-based forecasting model

## 📊 Datasets

- Yahoo Finance (SPY)
- FRED: CPI, UNRATE, FEDFUNDS

## 🏁 Key Results

| Dataset        | NeuralDMD RMSE | LSTM RMSE | Transformer RMSE |
|----------------|----------------|------------|-------------------|
| CPI            | 0.014          | 0.021      | 0.020             |
| UNRATE         | 0.018          | 0.025      | 0.024             |
| FEDFUNDS       | 0.009          | 0.017      | 0.016             |
| SPY (Finance)  | 0.034          | 0.036      | 0.035             |

## 🏆 Citation

If you use this work, please cite:

```bibtex
@inproceedings{mishra2025neuraldmd,
  title     = {NeuralDMD vs Transformers: A Spectral Benchmark for Economic Signal Forecasting},
  author    = {Gia Bach and Satyam Mishra and Tran Duc Tan and Vishwanath Bijalwan},
  booktitle = {International Conference on Information and Communication Technologies and Applications (ICTA)},
  year      = {2025}
}
