## Quantum Finance (Quantum Computing for Finance)
Quantum Computing is emerging, and finance could be one of the first industry sectors to benefit from it. This is a new field where new ideas come out every day! That is why we create a collection to follow the up-to-now papers in this field! Welcome to join and update the collection!

The paper format follows the style: Paper Title (Author) [Institution]

Some papers are conducted by many institutions together, and we can only include the corresponding institution.

**Table of Contents**
- [Quantum Finance (Quantum Computing for Finance)](#quantum-finance-quantum-computing-for-finance)
  - [**Portfolio Optimization**](#portfolio-optimization)
  - [**Asset Pricing**](#asset-pricing)
  - [**Fraud Detection**](#fraud-detection)
  - [**Risk Management**](#risk-management)
  - [**Blockchain**](#blockchain)
  - [**Quantum Money**](#quantum-money)
  - [Quantum Inspired Algorithm (Norm-Sampling)](#quantum-inspired-algorithm-norm-sampling)
  - [**Others**](#others)
    - [**Predicting Financial Crashes**](#predicting-financial-crashes)
    - [**Transaction Settlement**](#transaction-settlement)
    - [**Quantum Accounting**](#quantum-accounting)
---

### **Portfolio Optimization**
- **[2018]** **"Quantum computational finance: quantum algorithm for portfolio optimization."** (P. Rebentrost and S. Lloyd) [CQT - NUS, MIT], [arXiv](https://arXiv.org/pdf/1811.03975).
  - First to present a quantum algorithm for portfolio optimization
  - Gate-based quantum computer
- **[2019]** **"Quantum-inspired algorithms in practice."** (Arrazola, J. M., Delgado, A., Bardhan, B. R., & Lloyd, S.)[arXiv](https://arxiv.org/abs/1905.10415)
- **[2019]** **"Reverse Quantum Annealing Approach to Portfolio Optimization Problems."** (D. Venturelli and A. Kondratyev) [USRA, Standard Chartered Bank], [Quantum Machine Intelligence](https://link.springer.com/article/10.1007/s42484-019-00001-w).
  - investigate a hybrid quantum-classical solution method to the mean-variance portfolio optimization problems
- **[2019]** **"Quantum Algorithms for Portfolio Optimization."** (I. Kerenidis, A. Prakash, and D. Szilágyi) [CNRS], [Proceedings of the 1st ACM Conference on Advances in Financial Technologies](https://dl.acm.org/doi/pdf/10.1145/3318041.3355465).
  - develop the first quantum algorithm for the constrained portfolio optimization problem
  - Gate-based quantum computer
- **[2019]** **"Portfolio rebalancing experiments using the Quantum Alternating Operator Ansatz."** (M. Hodson, B. Ruck, H. Ong, D. Garvin, and S. Dulman) [Rigetti, Commonwealth Bank of Australia], [arXiv](https://arXiv.org/pdf/1911.05296).
  - design a novel problem encoding and hard constraint mixers for the Quantum Alternating Operator Ansatz
  - Gate-based quantum computer
- **[2020]** **"Portfolio Optimization of 40 Stocks Using the DWave Quantum Annealer."**(J. Cohen, A. Khan, and C. Alexander) [Chicago Quantum], [arXiv](https://arXiv.org/pdf/2007.01430).
  - implement in a D-Wave quantum computer to solve the equilibrium state of a complex financial network (NP-Hard)
  - use DWaves 2,041 qubit quantum annealer through a repeatable research and business process. 
  - pick 40 assets, which creates a solution space of 240 or 1.1 trillion portfolios from which to select.
- **[2021]** **"Portfolio Optimization on Classical and Quantum Computers Using PortFawn."** (M. Owhadi-Kareshk and P. Boulanger) [University of Alberta], [arXiv](https://arXiv.org/pdf/2112.08998).
- **[2021]** **"Quantum walk-based portfolio optimisation."** (N. Slate, E. Matwiejew, S. Marsh, and J. B. Wang) [The University of Western Australia], [Quantum](https://quantum-journal.org/papers/q-2021-07-28-513/pdf/).
- **[2021]** **"Quantum Portfolio Optimization with Investment Bands and Target Volatility."** (Samuel Palmer, Serkan Sahin, Rodrigo Hernandez, Samuel Mugel, Roman Orus) [Multiverse Computing], [arXiv](https://arXiv.org/pdf/2106.06735).
- **[2022]** **"NISQ-HHL: Portfolio Optimization for Near-Term Quantum Hardware."** (R. Yalovetzky, P. Minssen, D. Herman, and M. Pistoia) [JP Morgan Chase Bank], [arXiv](https://arXiv.org/pdf/2110.15958).
  - the first hybrid formulation of HHL suitable for the end-to-end execution of small-scale portfolio-optimization problems on NISQ devices
  - Gate-based quantum computer
- **[2022]** **"Constrained Quantum Optimization for Extractive Summarization on a Trapped-ion Quantum Computer."** (P. Niroula et al.) [JP Morgan Chase Bank, University of Maryland], [Scientific Reports](https://www.nature.com/articles/s41598-022-20853-w).
- **[2022]** **A Quantum Online Portfolio Optimization Algorithm."** (D. Lim and P. Rebentrost) [CQT - NUS], [arXiv](https://arXiv.org/pdf/2208.14749).

  <!-- - give a sampling version of an existing classical online portfolio optimization algorithm while using a sampling procedure to reduce transaction costs the most by only investing one asset at each time point
  - The updating strategy “Erroneous exponentiated gradient update” needs an inner product process which can be speeded by quantum computing techniques. -->
  <!-- - Limitation: the updating strategy is based on single-asset price without considering potential risks and correlations between assets. -->

---

### **Asset Pricing**

- **[2018]** **"Quantum computational finance: Monte Carlo pricing of financial derivatives."** (P. Rebentrost, B. Gupt, and T. R. Bromley) [Xanadu], [Physical Review A](https://link.aps.org/pdf/10.1103/PhysRevA.98.022321).
  - First to present a quantum algorithm for option pricing
- **[2020]** **"Option Pricing using Quantum Computers."** ( N. Stamatopoulos et al.) [JPMorgan Chase, IBM, ETH Zurich], [Quantum](https://quantum-journal.org/papers/q-2020-07-06-291/).
  - implementation of the quantum circuits with the input states and operators needed by amplitude estimation to price the different option types
- **[2021]** **"Towards Pricing Financial Derivatives with an IBM Quantum Computer."** (A. Martin et al.) [University of the Basque Country UPV/EHU, et al.], [Physical Review Research](https://link.aps.org/pdf/10.1103/PhysRevResearch.3.013167).
- **[2021]** **"A Quantum Walk Model of Financial Options."** (D. Orrell) [Systems Forecasting], [Wiley Online Library](https://onlinelibrary.wiley.com/doi/pdf/10.1002/wilm.10918).
- **[2021]** **"Quantum algorithm for stochastic optimal stopping problems with applications in finance."** (P. Rebenstrost et. al)[CQT], [17th Conference on the Theory of Quantum Computation, Communication and Cryptography (TQC 2022)](https://drops.dagstuhl.de/opus/volltexte/2022/16509/pdf/LIPIcs-TQC-2022-2.pdf).
- **[2021]** **"Simulating option price dynamics with exponential quantum speedup."** (Javier Gonzalez-Conde et. al)[University of the Basque Country], [arXiv](https://www.academia.edu/download/86251409/2101.04023v3.pdf).
- **[2022]** **"Pricing Multi-Asset Derivatives by Finite-Difference Method on a Quantum Computer."** (K. Miyamoto and K. Kubo) [Osaka University], [IEEE Transactions on Quantum Engineering](https://ieeexplore.ieee.org/iel7/8924785/9669178/09618807.pdf).
- **[2022]** **"Quantum advantage for multi-option portfolio pricing and valuation adjustments."** (Jeong Yu Han, Patrick Rebentrost)[CQT], [arXiv](https://arxiv.org/pdf/2203.04924).
- **[2022]** **"Quantum computational finance: martingale asset pricing for incomplete markets."** (P. Rebentrost, A. Luongo, S. Bosch, and S. Lloyd) [CQT, MIT], [arXiv](https://arxiv.org/pdf/2209.08867).

---

### **Fraud Detection**
- **[2021]** **"Unsupervised quantum machine learning for fraud detection."** (Oleksandr Kyriienko and Einar B. Magnusson)[University of Exeter, HSBC], [arXiv](https://arxiv.org/pdf/2208.01203).
- **[2022]** **"Mixed Quantum-Classical Method For Fraud Detection with Quantum Feature Selection."** (M. Grossi et al.) [CERN, IBM], [IEEE Transactions on Quantum Engineering ](https://ieeexplore.ieee.org/iel7/8924785/9669178/09915517.pdf).
  - present a first end-to-end application of a Quantum Support Vector Machine (QSVM) algorithm for a classification problem in the financial payment industry.
- **[2022]** **"Approximate complex amplitude encoding algorithm and its application to classification problem in financial operations."** (Naoki Mitsuda, et. al)[Sumitomo Mitsui Trust Bank,  Keio University] [arXiv](https://arxiv.org/pdf/2211.13039).

---

### **Risk Management**
- **[2019]** **"Quantum Risk Analysis."** (S. Woerner and D. J. Egger) [IBM Research - Zurich], [npj Quantum Information](https://www.nature.com/articles/s41534-019-0130-6).
  - present a quantum algorithm that analyzes risk more efficiently than Monte Carlo simulations traditionally used on classical computers (financial risk for a two-asset portfolio )
- **[2020]** **"Improving Variational Quantum Optimization using CVaR."** (P. K. Barkoutsos, G. Nannicini, A. Robert, I. Tavernelli, and S. Woerner) [IBM Research, PSL University], [Quantum](https://quantum-journal.org/papers/q-2020-04-20-256/pdf/).
- **[2021]** **"Towards Quantum Advantage in Financial Market Risk using Quantum Gradient Algorithms."** (N. Stamatopoulos, G. Mazzola, S. Woerner, and W. J. Zeng) [Goldman Sachs, IBM], [Quantum](https://quantum-journal.org/papers/q-2022-07-20-770/).
- **[2021]** **"Credit Risk Analysis Using Quantum Computers."** (Daniel J. Egger , Ricardo Garcıa Gutierrez, Jordi Cahu e Mestre, and Stefan Woerner) [IBM], [IEEE Transactions on Quantum Engineering](https://ieeexplore.ieee.org/iel7/12/4358213/09259208.pdf).
- **[2021]** **"Quantum speedup of Monte Carlo integration with respect to the number of dimensions and its application to finance."** (Kazuya Kaneko, Koichi Miyamoto, Naoyuki Takeda, Kazuyoshi Yoshino)[Mizuho-DL Financial Technology Co, Center for Quantum Information and Quantum biology], [Quantum Information Processing](https://link.springer.com/article/10.1007/s11128-021-03127-8).
  <!-- - extend this to a quadratic error scaling advantage in market risk computation -->
---

### **Blockchain**
- **[2018]** **"Quantum-secured Blockchain."** (E. O. Kiktenko et al.) [Russian Quantum Center], [Quantum Science and Technology](https://iopscience.iop.org/article/10.1088/2058-9565/aabc6b/pdf).
- **[2021]** **"Quantum-resistance in blockchain networks."**(M. Allende et al.) [IDB, 2LACChain, CQC, Tecnologico de Monterrey], [arXiv](https://arxiv.org/pdf/2106.06640).
- **[2021]** **"Post-Quantum Blockchain Proofs of Work."** (A. Cojocaru, J. Garay, A. Kiayias, F. Song, and P. Wallden) [Inria, etc.], [arXiv](https://arxiv.org/pdf/2012.15254.pdf).
- **[2022]** **"Quantum Proof of Work with Parametrized Quantum Circuits** (M. Y. Shalaginov and M. Dubrovsky) [MIT], [arXiv](https://arxiv.org/pdf/2204.10643).
  - introduce a QPoW that involes a random quantum circuits which can not be simulated efficiently by classical computers.

---

### **Quantum Money**
- **[1960+]** **"Conjugate coding."** (Wiesner, Stephen) [Columbia university], [ACM Sigact News](https://dl.acm.org/doi/pdf/10.1145/1008908.1008920).
- **[2013]** **"Quantum Money from Hidden Subspaces."** (Aaronson, Scott, and Paul Christiano) [MIT], [STOC '12: Proceedings of the forty-fourth annual ACM symposium on Theory of computing](https://dl.acm.org/doi/abs/10.1145/2213977.2213983).
- **[2016]** **"Quantum Tokens for Digital Signatures."** (Ben-David, Shalev, and Or Sattath) [MIT, The Hebrew University], [arXiv](https://arxiv.org/pdf/1609.09047).
- **[2017]** **"Quantum Lightning Never Strikes the Same State Twice."** (M. Zhandry) [Princeton University], [arXiv](https://arxiv.org/pdf/1711.02276).
- **[2018]** **"Experimental preparation and verification of quantum money."** (Guan, Jian-Yu, Juan Miguel Arrazola, Ryan Amiri, Weijun Zhang, Hao Li, Lixing You, Zhen Wang, Qiang Zhang, and Jian-Wei Pan.) [USTC, CQT], [arXiv](https://arxiv.org/pdf/1709.05882.pdf).
- **[2018]** **"Experimental investigation of practical unforgeable quantum money."** (Bozzio, Mathieu, Adeline Orieux, Luis Trigo Vidarte, Isabelle Zaquine, Iordanis Kerenidis, and Eleni Diamanti.) [CNRS, CQT] [npj Quantum Information](https://www.nature.com/articles/s41534-018-0058-2).
- **[2019]** **"Practically feasible robust quantum money with classical verification."** (Kumar, Niraj) [University of Edinburgh], [Cryptography](https://www.mdpi.com/2410-387X/3/4/26/htm).
- **[2019]** **"Gentle measurement of quantum states and differential privacy."** (Aaronson, Scott, and Rothblum, Guy N.) [Proceedings of the 51st Annual ACM SIGACT Symposium on Theory of Computing](https://dl.acm.org/doi/10.1145/3313276.3316369).
- **[2020]** **"A quantum money solution to the blockchain scalability problem."** (Coladangelo, Andrea, and Or Sattath) [Caltech, Ben-Gurion University] [Quantum](https://quantum-journal.org/papers/q-2020-07-16-297/).
- **[2020]** **"One-shot signatures and applications to hybrid quantum/classical authentication."** (Ryan Amos, Marios Georgiou, Aggelos Kiayias, Mark Zhandry) [Princetion U, City U of New York, U of Edinburgh, etc] [Quantum](https://quantum-journal.org/papers/q-2020-07-16-297/).
- **[2021]** **"Public-Key Quantum Money with a Classical Bank."** (O. Shmueli) [Tel Aviv University], [STOC 2022: Proceedings of the 54th Annual ACM SIGACT Symposium on Theory of Computing](https://dl.acm.org/doi/pdf/10.1145/3519935.3519952).
- **[2021]** **"Quantum money from quaternion algebras."** (Kane, Daniel M., Shahed Sharif, and Alice Silverberg.) [UCSD, California State University, University of California, Irvine], [arXiv](https://arxiv.org/pdf/2109.12643).
- **[2022]** **"Publicly verifiable quantum money from random lattices."** (A. B. Khesin, J. Z. Lu, and P. W. Shor)[MIT, Harvard], [arXiv](https://arxiv.org/pdf/2207.13135).
- **[2022]** **"Another Round of Breaking and Making Quantum Money: How to Not Build It from Lattices, and More."** (Montgomery, Hart, Jiahui Liu, and Mark Zhandry.)[UTA, Linux & Fujitsu, NTT], [arXiv](https://arxiv.org/abs/2211.11994).   
- **[2023]** **"Quantum tokens for digital signatures."** (Ben-David, Shalev, and Sattath, Or) [Quantum 7](https://quantum-journal.org/papers/q-2023-01-19-901/pdf/).
---

### Quantum Inspired Algorithm (Norm-Sampling)
- **[2018] “A quantum-inspired classical algorithm for recommendation systems.”** (Ewin Tang) [arXiv](https://arxiv.org/pdf/1807.04271.pdf).
- **[2019] “Quantum-inspired algorithms in practice.”** (Juan Miguel Arrazola, Alain Delgado, Bhaskar Roy Bardhan, Seth Lloyd) [arXiv](https://arxiv.org/abs/1905.10415).
- **[2019] “A quantum-inspired classical algorithm for recommendation systems using the L2-norm.”** (Ewin Tang)** [ACM Digital Library](https://dl.acm.org/doi/10.1145/3313276.3316310).
- **[2019] “Faster Quantum-inspired Algorithms for Solving Linear Systems.”** (Changpeng Shao, Ashley Montanaro) [ACM Digital Library](https://dl.acm.org/doi/10.1145/3520141)
- **[2020] “Quantum Algorithms for Machine Learning and Optimization.”** (Sangeetha P; Prameela Kumari) [IEEE](https://ieeexplore.ieee.org/document/9315301).
- **[2021] “Quantum-inspired algorithms for multivariate analysis: from classical to quantum and back.”** (Juan José García-Ripoll) [Quantum Journal](https://quantum-journal.org/papers/q-2021-04-15-431/)
- **[2021] “Quantum-inspired support vector machine.”**  (Ding, C., Bao, T. Y., & Huang, H. L. ) [IEEE Transactions on Neural Networks and Learning Systems](https://ieeexplore.ieee.org/iel7/5962385/9966944/09451546.pdf)
- **[2022] “Sampling-based sublinear low-rank matrix arithmetic framework for dequantizing quantum machine learning.”** (Chia, N. H., Gilyén, A. P., Li, T., Lin, H. H., Tang, E., & Wang, C.) [Journal of the ACM](https://dl.acm.org/doi/full/10.1145/3549524)
- **[2022] "An improved quantum-inspired algorithm for linear regression."** (Gilyén, A., Song, Z., & Tang, E. ) [Quantum](https://quantum-journal.org/papers/q-2022-06-30-754/)
- **[2023] "A CS guide to the quantum singular value transformation."**  (Tang, E., & Tian, K.) [arXiv](https://arxiv.org/abs/2302.14324)

---
### **Others**
#### **Predicting Financial Crashes**
-  **[2019]** **"Forecasting financial crashes with quantum computing."** (R. Orus, S. Mugel, and E. Lizaso) [Multiverse Computing, etc.], [Physical Review A](https://link.aps.org/pdf/10.1103/PhysRevA.99.060301)
   -  implement on near-term quantum processors and provide a potentially more efficient way to assess financial equilibrium and predict financial crashes.
- **[2021]** **"Towards Prediction of Financial Crashes with a D-Wave Quantum Computer."** (Y. Ding et al.) [Shanghai University, University of the Basque Country UPV/EHU, etc.], [arXiv](https://arxiv.org/pdf/1904.05808).

#### **Transaction Settlement**
- **[2021]** **"Quantum Algorithms for Mixed Binary Optimization Applied to Transaction Settlement."** (L. Braine, D. J. Egger, J. Glick, and S. Woerner) [Barclays, IBM Quantum], [IEEE Transactions on Quantum Engineering](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9369145).
  - combine binary decision variables with continuous decision variables enables the modelling of inequality constraints via slack variables

#### **Quantum Accounting**
- **[2022]** **"Entropy, Double Entry Accounting and Quantum Entanglement."** (J. C. Fellingham, H. Lin, and D. Schroeder) [Fisher College of Business, The Ohio State University], [Foundations and Trends® in Accounting](https://www.nowpublishers.com/article/Download/ACC-069).


