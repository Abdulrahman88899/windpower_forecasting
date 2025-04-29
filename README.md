# A Hybrid Decomposition-Based Deep Learning Approach for Enhanced Wind Power Forecasting

## Introduction
This repository presents the work conducted during my master's thesis, focused on improving wind power forecasting accuracy through a novel hybrid framework that combines Complete Ensemble Empirical Mode Decomposition with Adaptive Noise (CEEMDAN), Empirical Wavelet Transform (EWT), and Gated Recurrent Unit (GRU) neural networks.  
The thesis explores the challenges of forecasting due to the non-stationary and nonlinear nature of wind power data, and proposes a hybrid preprocessing and deep learning strategy to enhance forecasting performance.

## Key Contributions

- **Development of a Hybrid Forecasting Framework**  
  Proposed a CEEMDAN-EWT-GRU model to enhance feature quality, reduce noise, and improve prediction accuracy.

- **Evaluation of Input and Output Lengths**  
  Conducted extensive experiments to determine the optimal configurations for wind power forecasting.

- **Benchmarking with State-of-the-Art Models**  
  Compared the proposed framework against models like RNN, LSTM, GRU, Bi-LSTM, and hybrid approaches using RMSE, MAE, R², and Margin of Error metrics.

- **Incorporation of Meteorological Features**  
  Investigated the impact of additional meteorological variables on forecasting performance.

- **Development of a Hybrid GRU-BiLSTM Model**  
  Proposed a GRU-BiLSTM architecture based on IMF frequency splitting to further enhance accuracy.

- **Contribution to Renewable Energy Research**  
  Aimed to advance forecasting methodologies for wind power applications.

## Repository Structure
This repository is organized into three main folders:

- **1_Thesis_Documents/**  
  Contains the following:
  - Final Thesis Paper
  - PowerPoint Presentation (Defense Slides)
  - Conference Paper (Submitted to IEEE SMC 2025)

- **2_Dataset/**  
  Includes the dataset used for training and evaluation during the thesis experiments.

- **3_Code_Experiments/**  
  Contains all scripts related to:
  - Data preprocessing
  - CEEMDAN and EWT decomposition
  - Model training and evaluation (GRU and benchmark models)
  - Performance metrics calculations

## How to Use
1. **Clone the repository**
   ```bash
   git clone https://github.com/Abdulrahman88899/windower_forecasting.git


> 📌 *Citation details will be updated once the conference paper is officially published.*

---

## Contact

For any questions, feedback, or collaboration inquiries, please reach out:

- **Name**: [Abdulrahman Khalid Almansoori]
- **Email**: [a.almansoori98@gmail.com]
