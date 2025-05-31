
# HighFreqTrading

## 📂 Repository Structure & Lab Content

This repository is designed to support the **High-Frequency Trading (HFT)** course by Ioane Muni Toke at CentraleSupélec.
It covers both theory and Python-based laboratory exercises aligned with the lectures.


---


## 🗂️ Folder Structure

```
/Data/                  → Compressed research datasets (not public; do not share)
/DHF-LABX-...ipynb      → Python notebooks for each lab
```

---


## 🧪 Detailed Lab Overview & Techniques

| Lab #     | Topics                                         | Techniques & Knowledge Gained                                                                                                                  |
| --------- | ---------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| **Lab 1** | Timescales in finance, limit order books (LOB) | Statistical analysis of high-frequency data; spread, tick size, trade signs, imbalances, order lifetimes, empirical patterns                   |
| **Lab 2** | Poisson processes                              | Simulation of Poisson processes; intensity functions; event counting; analyzing arrival times and durations                                    |
| **Lab 3** | Hawkes processes                               | Simulating Hawkes processes (thinning, branching); fitting kernels; understanding endogeneity, self-excitation, maximum likelihood estimation  |
| **Lab 4** | Hawkes processes in finance, realized variance | Signature plots, Epps effect, Hayashi-Yoshida estimator; applying Hawkes models to LOB; simulating correlated event processes                  |
| **Lab 5** | 	Empirical microstructure analysis, response functions               | Compute and plot signed autocorrelations, empirical response functions, signed event-event correlations, and compare theoretical vs empirical responses under constant impact models         |



### 📊 High-Frequency Trading Insights & Knowledge

Throughout the course, students gain:

* Understanding of microstructure: order types, market making, liquidity dynamics
* Modeling tools: point processes, renewal models, Hawkes processes, stochastic intensity
* Statistical tools: variance estimators, correlation estimators, response function estimators
* Execution models: cost minimization, mean-variance optimization, impact mitigation
* Simulation techniques: Monte Carlo, thinning, branching, Poisson draws, kernel fitting
* Python-specific practices: reproducible notebooks, scientific libraries (NumPy, pandas, matplotlib), working with compressed tick data


### ⚠️ Important Notes on Data Usage

* The data used is confidential, provided under research agreements.
* Do **NOT** upload or share these datasets publicly or on GitHub.
* Use the datasets **only** within the course context.


---




## 📈 Getting Started

### Prerequisites

* Python 3.8 or higher
* Conda (for environment management)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/martinpasche/HighFreqTrading.git
   cd HighFreqTrading
   ```


2. **Create and activate the Conda environment:**

   ```bash
   conda env create -f env.yml
   conda activate hft_env
   ```

3. **Install additional requirements (if any):**

   ```bash
   pip install -r requirements.txt
   ```



## 👥 Contributors

This project was done by the following contributors:

- [Martín Pasche](https://github.com/martinpasche)  
- [Hugo Yeremian](https://github.com/h-yer) 


## 🖊️ License

This project is licensed under the MIT License.
