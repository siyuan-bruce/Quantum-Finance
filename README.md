# Quantum Finance (Quantum Computing for Finance)
Quantum Computing is emerging, and finance could be one of the first industry sectors to benefit from it. This is a new field where new ideas come out every day! That is why we create a collection to follow the up-to-now papers in this field! Welcome to join and update the collection!

The paper format follows the style: Paper Title (Author) [Institution]

Some papers are conducted by many institutions together, and we can only include the corresponding institution.

## Table of Contents
  - [Portfolio Optimization](#portfolio-optimization)
  - [Asset Pricing](#asset-pricing)
  - [Fraud Detection](#fraud-detection)
  - [Risk Management](#risk-management)
  - [Blockchain](#blockchain)
  - [Quantum Money](#quantum-money)
  - [Others](#Others)
---

### **Portfolio Optimization**
- **[2018]** **"Quantum computational finance: quantum algorithm for portfolio optimization."** (P. Rebentrost and S. Lloyd) [CQT - NUS, MIT]
  - First to present a quantum algorithm for portfolio optimization
  - Gate-based quantum computer
- **[2019]** **"Reverse Quantum Annealing Approach to Portfolio Optimization Problems."** (D. Venturelli and A. Kondratyev) [USRA, Standard Chartered Bank]
  - investigate a hybrid quantum-classical solution method to the mean-variance portfolio optimization problems
- **[2019]** **"Quantum Algorithms for Portfolio Optimization."** (I. Kerenidis, A. Prakash, and D. Szilágyi) [CNRS]
  - develop the first quantum algorithm for the constrained portfolio optimization problem
  - Gate-based quantum computer
- **[2019]** **"Portfolio rebalancing experiments using the Quantum Alternating Operator Ansatz."** (M. Hodson, B. Ruck, H. Ong, D. Garvin, and S. Dulman) [Rigetti, Commonwealth Bank of Australia]
  - design a novel problem encoding and hard constraint mixers for the Quantum Alternating Operator Ansatz
  - Gate-based quantum computer
- **[2020]** **"Portfolio Optimization of 40 Stocks Using the DWave Quantum Annealer."**(J. Cohen, A. Khan, and C. Alexander) [Chicago Quantum]
  - implement in a D-Wave quantum computer to solve the equilibrium state of a complex financial network (NP-Hard)
  - use DWaves 2,041 qubit quantum annealer through a repeatable research and business process. 
  - pick 40 assets, which creates a solution space of 240 or 1.1 trillion portfolios from which to select.
- **[2021]** **"Portfolio Optimization on Classical and Quantum Computers Using PortFawn."** (M. Owhadi-Kareshk and P. Boulanger) [University of Alberta]
-  **"Quantum walk-based portfolio optimisation."** (N. Slate, E. Matwiejew, S. Marsh, and J. B. Wang) [The University of Western Australia]
- **[2022]** **"NISQ-HHL: Portfolio Optimization for Near-Term Quantum Hardware."** (R. Yalovetzky, P. Minssen, D. Herman, and M. Pistoia) [JP Morgan Chase Bank]
  - the first hybrid formulation of HHL suitable for the end-to-end execution of small-scale portfolio-optimization problems on NISQ devices
  - Gate-based quantum computer
- **[2022]** **"Constrained Quantum Optimization for Extractive Summarization on a Trapped-ion Quantum Computer."** (P. Niroula et al.) [JP Morgan Chase Bank, University of Maryland]
- **[2022]** **A Quantum Online Portfolio Optimization Algorithm."** (D. Lim and P. Rebentrost) [CQT - NUS]
  <!-- - give a sampling version of an existing classical online portfolio optimization algorithm while using a sampling procedure to reduce transaction costs the most by only investing one asset at each time point
  - The updating strategy “Erroneous exponentiated gradient update” needs an inner product process which can be speeded by quantum computing techniques. -->
  <!-- - Limitation: the updating strategy is based on single-asset price without considering potential risks and correlations between assets. -->

---

### **Asset Pricing**

- **[2018]** **"Quantum computational finance: Monte Carlo pricing of financial ."** (P. Rebentrost, B. Gupt, and T. R. Bromley) [Xanadu]
  - First to present a quantum algorithm for option pricing
- **[2020]** **"Option Pricing using Quantum Computers."** ( N. Stamatopoulos et al.) [JPMorgan Chase, IBM, ETH Zurich]
  - implementation of the quantum circuits with the input states and operators needed by amplitude estimation to price the different option types
- **[2021]** **"Towards Pricing Financial Derivatives with an IBM Quantum Computer."** (A. Martin et al.) [University of the Basque Country UPV/EHU, et al.]
- **[2021]** **A Quantum Walk Model of Financial Options."** (D. Orrell) [Systems Forecasting]
- **[2022]** **"Pricing Multi-Asset Derivatives by Finite-Difference Method on a Quantum Computer."** (K. Miyamoto and K. Kubo) [Osaka University]
- **[2022]** **"Quantum computational finance: martingale asset pricing for incomplete markets."** (P. Rebentrost, A. Luongo, S. Bosch, and S. Lloyd) [CQT, MIT]

---

### **Fraud Detection**
- **[2022]** **"Mixed Quantum-Classical Method For Fraud Detection with Quantum Feature Selection."** (M. Grossi et al.) [CERN, IBM]
  - present a first end-to-end application of a Quantum Support Vector Machine (QSVM) algorithm for a classification problem in the financial payment industry.

---

### **Risk Management**
- **[2019]** **"Quantum risk analysis."** (S. Woerner and D. J. Egger) [IBM Research - Zurich]
  - present a quantum algorithm that analyzes risk more efficiently than Monte Carlo simulations traditionally used on classical computers (financial risk for a two-asset portfolio )
- **[2020]** **"Improving Variational Quantum Optimization using CVaR."** (P. K. Barkoutsos, G. Nannicini, A. Robert, I. Tavernelli, and S. Woerner) [IBM Research, PSL University]
- **[2021]** **"Towards Quantum Advantage in Financial Market Risk using Quantum Gradient Algorithms."** (N. Stamatopoulos, G. Mazzola, S. Woerner, and W. J. Zeng) [Goldman Sachs, IBM]
  - extend this to a quadratic error scaling advantage in market risk computation

---

### **Blockchain**
- **[2018]** **"Quantum-secured blockchain."** (E. O. Kiktenko et al.) [Russian Quantum Center]
- **[2021]** **"Quantum-resistance in blockchain networks."**(M. Allende et al.) [IDB, 2LACChain, CQC, Tecnologico de Monterrey]
- **[2021]** **"Post-Quantum Blockchain Proofs of Work."** (A. Cojocaru, J. Garay, A. Kiayias, F. Song, and P. Wallden) [Inria, etc.]
- **[2022]** **"Quantum Proof of Work with Parametrized Quantum Circuits** (M. Y. Shalaginov and M. Dubrovsky) [MIT]
  - introduce a QPoW that involes a random quantum circuits which can not be simulated efficiently by classical computers.
- **[2022]** **"Publicly verifiable quantum money from random lattices."** (A. B. Khesin, J. Z. Lu, and P. W. Shor) [MIT, Harvard]

---

### **Quantum Money**
- **[1983]** **"Conjugate coding."** (Wiesner, Stephen) [Columbia university]
- **[2013]** **"Quantum money from hidden subspaces."** (Aaronson, Scott, and Paul Christiano. ) [MIT], Theory of Computing.
- **[2016]** **"Quantum tokens for digital signatures."** (Ben-David, Shalev, and Or Sattath) [MIT, The Hebrew University]
- **[2017]** **"Quantum Lightning Never Strikes the Same State Twice."** (M. Zhandry) [Princeton University]
- **[2018]** **"Experimental preparation and verification of quantum money."** (Guan, Jian-Yu, Juan Miguel Arrazola, Ryan Amiri, Weijun Zhang, Hao Li, Lixing You, Zhen Wang, Qiang Zhang, and Jian-Wei Pan.) [USTC, CQT]
- **[2018]** **"Experimental investigation of practical unforgeable quantum money."** (Bozzio, Mathieu, Adeline Orieux, Luis Trigo Vidarte, Isabelle Zaquine, Iordanis Kerenidis, and Eleni Diamanti.) [CNRS, CQT] npj Quantum Information.
- **[2019]** **"Practically feasible robust quantum money with classical verification."** (Kumar, Niraj) [University of Edinburgh]
- **[2020]** **"A quantum money solution to the blockchain scalability problem."** (Coladangelo, Andrea, and Or Sattath) [Caltech, Ben-Gurion University] Quantum.
- **[2021]** **"Public-Key Quantum Money with a Classical Bank."** (O. Shmueli) [Tel Aviv University]
- **[2021]** **"Quantum money from quaternion algebras."** (Kane, Daniel M., Shahed Sharif, and Alice Silverberg.) [UCSD, California State University, University of California, Irvine], arxiv.
- **[2022]** **"Publicly verifiable quantum money from random lattices."** (A. B. Khesin, J. Z. Lu, and P. W. Shor)[MIT, Harvard]

---

### **Others**
#### **Predicting Financial Crashes**
-  **[2019]** **"Forecasting financial crashes with quantum computing."** (R. Orus, S. Mugel, and E. Lizaso) [Multiverse Computing, etc.]
   -  implement on near-term quantum processors and provide a potentially more efficient way to assess financial equilibrium and predict financial crashes.

- **[2021]** **"Towards Prediction of Financial Crashes with a D-Wave Quantum Computer."** (Y. Ding et al.) [Shanghai University, University of the Basque Country UPV/EHU, etc.]

#### **Transaction Settlement**
- **[2021]** **"Quantum Algorithms for Mixed Binary Optimization Applied to Transaction Settlement."** (L. Braine, D. J. Egger, J. Glick, and S. Woerner) [Barclays, IBM Quantum]
  - combine binary decision variables with continuous decision variables enables the modelling of inequality constraints via slack variables

#### **Quantum Accounting**
- **[2022]** **"Entropy, Double Entry Accounting and Quantum Entanglement."** (J. C. Fellingham, H. Lin, and D. Schroeder) [Fisher College of Business, The Ohio State University]

