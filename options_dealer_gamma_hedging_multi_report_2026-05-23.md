# Options Dealer Gamma Hedging Research -- Multi-Source Paper Archive

**Search keyword:** `options dealer gamma hedging`  
**Sources:** Semantic Scholar: 13, NBER: 15, RePEc: 15  
**Total papers:** 43  
**PDFs downloaded:** 15/43  
**Generated:** 2026-05-23  

---

## Semantic Scholar (13 papers)

### 1. Gamma Hedging without Rough Paths

**Authors:** J. Armstrong, P. Das  
**Published:** 2026-01-13  
**Link:** [View Paper](https://www.semanticscholar.org/paper/b8f6858fe4f4f8f3f9d311dc5c39083268be04c9)  
**PDF:** *No direct PDF URL*  

<details>
<summary>Abstract</summary>

We show how the robustness of gamma hedging can be understood without using rough-path theory. Instead, we use the concepts of $p^{th}$ variation along a partition sequence and Taylor's theorem directly, rather than defining an integral and proving a version of It\^o's lemma. The same approach allows classical results on delta-hedging to be proved without defining an integral and without the need to define the concept of self-financing in continuous time. We show that the approach can also be applied to barrier options and Asian options

</details>

---

### 2. Inferring Latent Market Forces: Evaluating LLM Detection of Gamma Exposure Patterns via Obfuscation Testing

**Authors:** Christopher F. Regan, Yingqi Xie  
**Published:** 2025-12-08  
**Link:** [View Paper](https://www.semanticscholar.org/paper/9b1bc2f5b9edb2188e331fff93e444e8ba9b5ebc)  
**PDF:** *No direct PDF URL*  

<details>
<summary>Abstract</summary>

We introduce obfuscation testing, a novel methodology for validating whether large language models detect structural market patterns through causal reasoning rather than temporal association. Testing three dealer hedging constraint patterns (gamma positioning, stock pinning, ODTE hedging) on 242 trading days (95.6 % coverage) of S&P 500 options data, we find LLMs achieve 71.5 % detection rate using unbiased prompts that provide only raw gamma exposure values without regime labels or temporal context. The WHO → WHOM → WHAT causal framework forces models to identify the economic actors (dealers), affected parties (directional traders), and structural mechanisms (forced hedging) underlying observed market dynamics. Critically, detection accuracy (91.2 %) remains stable even as economic profitability varies quarterly, demonstrating that models identify structural constraints rather than profitable patterns. When prompted with regime labels, detection increases to 100 %, but the 71.5 % unbiased rate validates genuine pattern recognition. Our findings suggest LLMs possess emergent capabilities for detecting complex financial mechanisms through pure structural reasoning, with implications for systematic strategy development, risk management, and our understanding of how transformer architectures process financial market dynamics.

</details>

---

### 3. Deep Hedging with Options Using the Implied Volatility Surface

**Authors:** Pascal Franccois, Geneviève Gauthier, Frédéric Godin, C. O. P'erez-Mendoza  
**Published:** 2025-04-08  
**Link:** [View Paper](https://www.semanticscholar.org/paper/90893ba32609bb0cddc79a8aa33dfd6c723d625a)  
**PDF:** *No direct PDF URL*  

<details>
<summary>Abstract</summary>

We propose a deep hedging framework for index option portfolios, grounded in a realistic market simulator that captures the joint dynamics of S&P 500 returns and the full implied volatility surface. Our approach integrates surface-informed decisions with multiple hedging instruments and explicitly accounts for transaction costs. The hedging strategy also considers the variance risk premium embedded in the hedging instruments, enabling more informed and adaptive risk management. Tested on a historical out-of-sample set of straddles from 2020 to 2023, our method consistently outperforms traditional delta-gamma hedging strategies across a range of market conditions.

</details>

---

### 4. A deep BSDE approach for the simultaneous pricing and delta-gamma hedging of large portfolios consisting of high-dimensional multi-asset Bermudan options

**Authors:** Balint Negyesi, C. Oosterlee  
**Published:** 2025-02-17  
**Link:** [View Paper](https://www.semanticscholar.org/paper/4e57c4e9ecc1985e9812322cad772348719bc21d)  
**PDF:** *No direct PDF URL*  

<details>
<summary>Abstract</summary>

A deep BSDE approach is presented for the pricing and delta-gamma hedging of high-dimensional Bermudan options, with applications in portfolio risk management. Large portfolios of a mixture of multi-asset European and Bermudan derivatives are cast into the framework of discretely reflected BSDEs. This system is discretized by the One Step Malliavin scheme (Negyesi et al. [2024, 2025]) of discretely reflected Markovian BSDEs, which involves a $\Gamma$ process, corresponding to second-order sensitivities of the associated option prices. The discretized system is solved by a neural network regression Monte Carlo method, efficiently for a large number of underlyings. The resulting option Deltas and Gammas are used to discretely rebalance the corresponding replicating strategies. Numerical experiments are presented on both high-dimensional basket options and large portfolios consisting of multiple options with varying early exercise rights, moneyness and volatility. These examples demonstrate the robustness and accuracy of the method up to $100$ risk factors. The resulting hedging strategies significantly outperform benchmark methods both in the case of standard delta- and delta-gamma hedging.

</details>

---

### 5. Deep Gamma Hedging

**Authors:** J. Armstrong, George Tatlow  
**Published:** 2024-09-20  
**Link:** [View Paper](https://www.semanticscholar.org/paper/ebf94e4496042314f361771d571fb819642e2ccf)  
**PDF:** *No direct PDF URL*  

<details>
<summary>Abstract</summary>

We train neural networks to learn optimal replication strategies for an option when two replicating instruments are available, namely the underlying and a hedging option. If the price of the hedging option matches that of the Black–Scholes model then we find the network will successfully learn the Black–Scholes gamma hedging strategy, even if the dynamics of the underlying do not match the Black–Scholes model, so long as we choose a loss function that rewards coping with model uncertainty. While transaction costs have been cited as a motivation for reducing gamma exposure, our results indicate that model uncertainty provides an even stronger incentive.

</details>

---

### 6. Hedging Interest Rate Options with Reinforcement Learning: an investigation of a heavy-tailed distribution

**Authors:** Allan Jonathan da Silva, J. Baczynski, L. F. De Mello  
**Published:** 2023-12-20  
**Link:** [View Paper](https://www.semanticscholar.org/paper/f0c307bac61f4e7d8c9558d62bb38df6e0bfb0e7)  
**PDF:** *No direct PDF URL*  

<details>
<summary>Abstract</summary>

Purpose: The study intends to model an interest rate index option using a heavy-tailed distribution. The goal is to calculate the interest rate path-dependent option prices that are consistent with market data and to develop a reinforcement learning strategy to discretely hedge the position considering transaction costs. Methodology: This paper presents a mathematical framework to calculate the price of interest rate path-dependent options. The research adapted a Fourier cosine series formula to employ the characteristic function of the present value of the forward index, which is modeled as a variance-gamma process and uses deep Q-learning to hedge such options. Findings: There is market evidence that the implied volatility curve is not flat. The study demonstrated that the variance-gamma process generates an increasing volatility smile, which is consistent with market observations. Additionally, hedging results show that the path-dependent options generated from the variance-gamma process can be efficiently hedged with advanced Q-learning techniques. Research limitations/implications: The study comprised only the variance-gamma process. Other probability distributions, such as the Normal Inverse Gaussian model, should be investigated. Practical implications: This study reveals which type of probability distribution should be present in a pricing engine to be consistent with implied volatilities. The approach provided here can assist managers in evaluating and comprehending market pricing behavior as well as achieving discrete hedging with costs. Originality: The paper addressed the merging of a fast pricing method for the interest rate options with a heavy-tailed distribution and the discrete interest rate derivatives hedging with reinforcement learning.

</details>

---

### 7. Gamma hedging and rough paths

**Authors:** J. Armstrong, Andrei Ionescu  
**Published:** 2023-09-10  
**Link:** [View Paper](https://www.semanticscholar.org/paper/2ce6583c4a638b2e411f22fab7fd34ccf500e31d)  
**PDF:** *No direct PDF URL*  

<details>
<summary>Abstract</summary>

We apply rough-path theory to study the discrete-time gamma-hedging strategy. We show that if a trader knows that the market prices of a set of European options are given by a diffusive pricing model, then the discrete-time gamma-hedging strategy enables them to replicate other European options so long as the underlying pricing signal has finite p\documentclass[12pt]{minimal} \usepackage{amsmath} \usepackage{wasysym} \usepackage{amsfonts} \usepackage{amssymb} \usepackage{amsbsy} \usepackage{mathrsfs} \usepackage{upgreek} \setlength{\oddsidemargin}{-69pt} \begin{document}$p$\end{document}-variation for p<3\documentclass[12pt]{minimal} \usepackage{amsmath} \usepackage{wasysym} \usepackage{amsfonts} \usepackage{amssymb} \usepackage{amsbsy} \usepackage{mathrsfs} \usepackage{upgreek} \setlength{\oddsidemargin}{-69pt} \begin{document}$p<3$\end{document}, with the error in the discrete-time replication strategy tending to zero as the length of the largest hedging interval tends to zero. This is a sure result and does not require that the underlying pricing signal has a quadratic variation corresponding to a probabilistic pricing model. We show how to generalise this result to exotic derivatives when the gamma is defined to be the Gubinelli derivative of the delta by deriving rough-path versions of the Clark–Ocone formula. We illustrate our theory by proving that if a stock price path has finite p\documentclass[12pt]{minimal} \usepackage{amsmath} \usepackage{wasysym} \usepackage{amsfonts} \usepackage{amssymb} \usepackage{amsbsy} \usepackage{mathrsfs} \usepackage{upgreek} \setlength{\oddsidemargin}{-69pt} \begin{document}$p$\end{document}-variation for p<3\documentclass[12pt]{minimal} \usepackage{amsmath} \usepackage{wasysym} \usepackage{amsfonts} \usepackage{amssymb} \usepackage{amsbsy} \usepackage{mathrsfs} \usepackage{upgreek} \setlength{\oddsidemargin}{-69pt} \begin{document}$p<3$\end{document} and if the implied volatility process for a European derivative on the stock (with a smooth, convex, nonlinear payoff and maturity T\documentclass[12pt]{minimal} \usepackage{amsmath} \usepackage{wasysym} \usepackage{amsfonts} \usepackage{amssymb} \usepackage{amsbsy} \usepackage{mathrsfs} \usepackage{upgreek} \setlength{\oddsidemargin}{-69pt} \begin{document}$T$\end{document}) has finite q\documentclass[12pt]{minimal} \usepackage{amsmath} \usepackage{wasysym} \usepackage{amsfonts} \usepackage{amssymb} \usepackage{amsbsy} \usepackage{mathrsfs} \usepackage{upgreek} \setlength{\oddsidemargin}{-69pt} \begin{document}$q$\end{document}-variation for q<2\documentclass[12pt]{minimal} \usepackage{amsmath} \usepackage{wasysym} \usepackage{amsfonts} \usepackage{amssymb} \usepackage{amsbsy} \usepackage{mathrsfs} \usepackage{upgreek} \setlength{\oddsidemargin}{-69pt} \begin{document}$q<2$\end{document} and 1p+1q>1\documentclass[12pt]{minimal} \usepackage{amsmath} \usepackage{wasysym} \usepackage{amsfonts} \usepackage{amssymb} \usepackage{amsbsy} \usepackage{mathrsfs} \usepackage{upgreek} \setlength{\oddsidemargin}{-69pt} \begin{document}$\frac{1}{p}+\frac{1}{q}>1$\end{document}, one can use the gamma-hedging strategy to replicate any European derivative with smooth payoff and maturity T\documentclass[12pt]{minimal} \usepackage{amsmath} \usepackage{wasysym} \usepackage{amsfonts} \usepackage{amssymb} \usepackage{amsbsy} \usepackage{mathrsfs} \usepackage{upgreek} \setlength{\oddsidemargin}{-69pt} \begin{document}$T$\end{document}. This is a sure result which holds without assuming any probabilistic model for the trajectory of the stock price path.

</details>

---

### 8. Pricing and Hedging Index Options under Mean-Variance Criteria in Incomplete Markets

**Authors:** Pornnapat Yamphram, Phiraphat Sutthimat, Udomsak Rakwongwan  
**Published:** 2023-02-07  
**Link:** [View Paper](https://www.semanticscholar.org/paper/ae2a05848ffb7ab610a863a04d38716fe7dde6c5)  
**PDF:** *No direct PDF URL*  

<details>
<summary>Abstract</summary>

This paper studies the portfolio selection problem where tradable assets are a bank account, and standard put and call options are written on the S&P 500 index in incomplete markets in which there exist bid–ask spreads and finite liquidity. The problem is mathematically formulated as an optimization problem where the variance of the portfolio is perceived as a risk. The task is to find the portfolio which has a satisfactory return but has the minimum variance. The underlying is modeled by a variance gamma process which can explain the extreme price movement of the asset. We also study how the optimized portfolio changes subject to a user’s views of the future asset price. Moreover, the optimization model is extended for asset pricing and hedging. To illustrate the technique, we compute indifference prices for buying and selling six options namely a European call option, a quadratic option, a sine option, a butterfly spread option, a digital option, and a log option, and propose the hedging portfolios, which are the portfolios one needs to hold to minimize risk from selling or buying such options, for all the options. The sensitivity of the price from modeling parameters is also investigated. Our hedging strategies are decent with the symmetry property of the kernel density estimation of the portfolio payout. The payouts of the hedging portfolios are very close to those of the bought or sold options. The results shown in this study are just illustrations of the techniques. The approach can also be used for other derivatives products with known payoffs in other financial markets.

</details>

---

### 9. Gamma and vega hedging using deep distributional reinforcement learning

**Authors:** Jay Cao, Jacky Chen, Soroush Farghadani, J. Hull, Zissis Poulos, Zeyu Wang, Jun Yuan  
**Published:** 2022-05-10  
**Link:** [View Paper](https://www.semanticscholar.org/paper/4c63447559f6380b2d05776efc3c56d155439f9e)  
**PDF:** *No direct PDF URL*  

<details>
<summary>Abstract</summary>

We show how reinforcement learning can be used in conjunction with quantile regression to develop a hedging strategy for a trader responsible for derivatives that arrive stochastically and depend on a single underlying asset. We assume that the trader makes the portfolio delta-neutral at the end of each day by taking a position in the underlying asset. We focus on how trades in options can be used to manage gamma and vega. The option trades are subject to transaction costs. We consider three different objective functions. We reach conclusions on how the optimal hedging strategy depends on the trader's objective function, the level of transaction costs, and the maturity of the options used for hedging. We also investigate the robustness of the hedging strategy to the process assumed for the underlying asset.

</details>

---

### 10. Hedging cryptocurrency options

**Authors:** Jovanka Matić, N. Packham, W. Härdle  
**Published:** 2021-11-23  
**Link:** [View Paper](https://www.semanticscholar.org/paper/3a3f3adccb5f013df7f52b6b564a8bd59fd7d9a9)  
**PDF:** *No direct PDF URL*  

<details>
<summary>Abstract</summary>

The cryptocurrency market is volatile, non-stationary and non-continuous. Together with liquid derivatives markets, this poses a unique opportunity to study risk management, especially the hedging of options, in a turbulent market. We study the hedge behaviour and effectiveness for the class of affine jump diffusion models and infinite activity Lévy processes. First, market data is calibrated to stochastic volatility inspired-implied volatility surfaces to price options. To cover a wide range of market dynamics, we generate Monte Carlo price paths using an stochastic volatility with correlated jumps model, a close-to-actual-market GARCH-filtered kernel density estimation as well as a historical backtest. In all three settings, options are dynamically hedged with Delta, Delta–Gamma, Delta–Vega and Minimum Variance strategies. Including a wide range of market models allows to understand the trade-off in the hedge performance between complete, but overly parsimonious models, and more complex, but incomplete models. The calibration results reveal a strong indication for stochastic volatility, low jump frequency and evidence of infinite activity. Short-dated options are less sensitive to volatility or Gamma hedges. For longer-dated options, tail risk is consistently reduced by multiple-instrument hedges, in particular by employing complete market models with stochastic volatility.

</details>

---

### 11. Pricing and Hedging Options on Assets with Options on Related Assets

**Authors:** D. Madan, King Wang  
**Published:** 2020-07-02  
**Link:** [View Paper](https://www.semanticscholar.org/paper/5a5da43e3022727ae630f0ae859ddcd6b460b4db)  
**PDF:** *No direct PDF URL*  

<details>
<summary>Abstract</summary>

The question addressed is the pricing of options on the CBOE Skew Index. The option pricing theory developed partially hedges risk by taking positions in the market for options on a related asset. The option is then priced at the cost of this hedge. The theory is applied to pricing Volatility Index (VIX) options hedged by the SPDR S&P 500 ETF Trust (SPY) options and pricing options on JPMorgan hedged by Financial Select Sector SPDR (XLF) options. The approach is then applied to illustrate the pricing of CBOE Skew Index options with a hedge in the market for SPY options. The Skew Index smile is then seen to imply the VIX and SKEW of the Skew Index itself. The pricing of VIX options with SPY as the related asset has the Gaussian copula underpricing options while the t-copula significantly overprices them. The multivariate bilateral gamma models are closer to market. The premia of cross-asset hedge prices over the market price are observed to fall with moneyness and maturity and rise with the level of the VIX. TOPICS: Derivatives, options, exchange-traded funds and applications, quantitative methods, statistical methods, performance measurement Key Findings ▪ Time series data on physical returns may be used to obtain market relevant option prices provided market-relevant hedging costs are incorporated. ▪ Options on the CBOE Skew Index are priced at the cost of an SPY option hedge portfolio. ▪ Residual risk pricing technologies may be applied more widely with market calibrated parameters if desired.

</details>

---

### 12. Delta-gamma-theta Hedging of Crude Oil Asian Options

**Authors:** J. Hruška  
**Published:** 2015-12-26  
**Link:** [View Paper](https://www.semanticscholar.org/paper/206c5a9028a0c6bb7c106e7af7ead752c0a539cc)  
**PDF:** *No direct PDF URL*  

<details>
<summary>Abstract</summary>

Since Black-Scholes formula was derived, many methods have been suggested for vanilla as well as exotic options pricing. More of investing and hedging strategies have been developed based on these pricing models. Goal of this paper is to derive delta-gamma-theta hedging strategy for Asian options and compere its efficiency with gamma-delta-theta hedging combined with predictive model. Fixed strike Asian options are type of exotic options, whose special feature is that payoff is calculated from the difference of average market price and strike price for call options and vice versa for the put options. Methods of stochastic analysis are used to determine deltas, gammas and thetas of Asian options. Asian options are cheaper than vanilla options and therefore they are more suitable for precise portfolio creation. On the other hand their deltas are also smaller as well as profits. That means that they are also less risky and more suitable for hedging. Results, conducted on chosen commodity, confirm better feasibility of Asian options compering with vanilla options in sense of gamma hedging.

</details>

---

### 13. Hedging of Covered Options with Linear Market Impact and Gamma Constraint

**Authors:** B. Bouchard, G. Loeper, Yiyi Zou  
**Published:** 2015-12-22  
**Link:** [View Paper](https://www.semanticscholar.org/paper/68308338f6ff03413a4db9977dea773a9c178889)  
**PDF:** *No direct PDF URL*  

<details>
<summary>Abstract</summary>

Within a financial model with linear price impact, we study the problem of hedging a covered European option under gamma constraint. Using stochastic target and partial differential equation smoothing techniques, we prove that the super-replication price is the viscosity solution of a fully non-linear parabolic equation. As a by-product, we show how e-optimal strategies can be constructed. Finally, a numerical resolution scheme is proposed.

</details>

---

## NBER (15 papers)

### 14. The Alpha Beta Gamma of the Labor Market

**Authors:** Victoria Gregory, Guido Menzio, David G. Wiczer  
**Published:** Unknown  
**Link:** [View Paper](https://www.nber.org/papers/w28663)  
**PDF:** [Open Local PDF](../data/options_dealer_gamma_hedging_pdfs/nber_231018.pdf)  

<details>
<summary>Abstract</summary>

Based on patterns of employment transitions, we identify three different types of workers in the US labor market: 's 's and 's. Workers of type  make up over half of all workers, are most likely to remain on the same job for more than 2 years and, when they become unemployed, typically find a new

</details>

---

### 15. Risk-Adjusted Gamma Discounting

**Authors:** Martin L. Weitzman  
**Published:** Unknown  
**Link:** [View Paper](https://www.nber.org/papers/w15588)  
**PDF:** [Open Local PDF](../data/options_dealer_gamma_hedging_pdfs/nber_69010.pdf)  

<details>
<summary>Abstract</summary>

It is widely recognized that the economics of distant-future events, like climate change, is critically dependent upon the choice of a discount rate. Unfortunately, it is unclear how to discount distant-future events when the future discount rate itself is unknown. In previous work, an analytically

</details>

---

### 16. Risk Preferences Implied by Synthetic Options

**Authors:** Ian Dew-Becker, Stefano Giglio  
**Published:** Unknown  
**Link:** [View Paper](https://www.nber.org/papers/w31833)  
**PDF:** [Open Local PDF](../data/options_dealer_gamma_hedging_pdfs/nber_751893.pdf)  

<details>
<summary>Abstract</summary>

The historical returns on equity index options are well known to be strikingly negative. That is typically explained either by investors having convex marginal utility over stock returns (e.g. crash/variance aversion) or by intermediaries demanding a premium for hedging risk. This paper examines the

</details>

---

### 17. Option-Implied Spreads and Option Risk Premia

**Authors:** Christopher L. Culp, Mihir Gandhi, Yoshio Nozawa, Pietro Veronesi  
**Published:** Unknown  
**Link:** [View Paper](https://www.nber.org/papers/w28941)  
**PDF:** [Open Local PDF](../data/options_dealer_gamma_hedging_pdfs/nber_268736.pdf)  

<details>
<summary>Abstract</summary>

We propose implied spreads (IS) and normalized implied spreads (NIS) as simple measures to characterize option prices. IS is the credit spread of an options implied bond, the portfolio long a risk-free bond and short a put option. NIS normalizes IS by the risk-neutral default probability and

</details>

---

### 18. Option Hedging Using Empirical Pricing Kernels

**Authors:** Joshua V. Rosenberg, Robert F. Engle  
**Published:** Unknown  
**Link:** [View Paper](https://www.nber.org/papers/w6222)  
**PDF:** [Open Local PDF](../data/options_dealer_gamma_hedging_pdfs/nber_85221.pdf)  

<details>
<summary>Abstract</summary>

This paper develops a method for option hedging which is consistent with time-varying preferences and probabilities. The preferences are expressed in the form of an empirical pricing kernel (EPK), which measures the state price per unit probability, while probabilities are derived from an estimated

</details>

---

### 19. Optimal Risk Management Using Options

**Authors:** Dong-Hyun Ahn, Jacob Boudoukh, Matthew Richardson, Robert F. Whitelaw  
**Published:** Unknown  
**Link:** [View Paper](https://www.nber.org/papers/w6158)  
**PDF:** [Open Local PDF](../data/options_dealer_gamma_hedging_pdfs/nber_85171.pdf)  

<details>
<summary>Abstract</summary>

This paper addresses the question of how an institution might optimally manage the market risk of a given exposure. We provide an analytical approach to optimal risk management under the assumption that the institution wishes to minimize its Value-at-Risk (VaR) using options follows a geometric

</details>

---

### 20. Macro-Hedging for Commodity Exporters

**Authors:** Eduardo Borensztein, Olivier Jeanne, Damiano Sandri  
**Published:** Unknown  
**Link:** [View Paper](https://www.nber.org/papers/w15452)  
**PDF:** [Open Local PDF](../data/options_dealer_gamma_hedging_pdfs/nber_68877.pdf)  

<details>
<summary>Abstract</summary>

This paper uses a dynamic optimization model to estimate the welfare gains of hedging against commodity price risk for commodity-exporting countries. We show that the introduction of hedging instruments such as futures and options enhances domestic welfare through two channels. First, by reducing

</details>

---

### 21. Hedging and Competition

**Authors:** Erasmo Giambona, Anil Kumar, Gordon M. Phillips  
**Published:** Unknown  
**Link:** [View Paper](https://www.nber.org/papers/w29207)  
**PDF:** [Open Local PDF](../data/options_dealer_gamma_hedging_pdfs/nber_309463.pdf)  

<details>
<summary>Abstract</summary>

We study how risk management through hedging impacts firms and competition among firms in the life insurance industry - an industry with over 7 Trillion in assets and over 1,000 private and public firms. We show that firms that are likely to face costly external finance increase hedging after

</details>

---

### 22. Hedging Sudden Stops and Precautionary Contractions

**Authors:** Ricardo J. Caballero, Stavros Panageas  
**Published:** Unknown  
**Link:** [View Paper](https://www.nber.org/papers/w9778)  
**PDF:** [Open Local PDF](../data/options_dealer_gamma_hedging_pdfs/nber_88276.pdf)  

<details>
<summary>Abstract</summary>

Even well managed emerging market economies are exposed to significant external risk, the bulk of which is financial. At a moment's notice, these economies may be required to reverse the capital inflows that have supported the preceding boom. While capital flows crises are sudden nonlinear events

</details>

---

### 23. Hedging Options in a GARCH Environment: Testing the Term Structure of Stochastic Volatility Models

**Authors:** Robert F. Engle, Joshua Rosenberg  
**Published:** Unknown  
**Link:** [View Paper](https://www.nber.org/papers/w4958)  
**PDF:** [Open Local PDF](../data/options_dealer_gamma_hedging_pdfs/nber_84150.pdf)  

<details>
<summary>Abstract</summary>

This paper develops a methodology for testing the term structure of volatility forecasts derived from stochastic volatility models, and implements it to analyze models of S&P 500 index volatility. Volatility models are compared by their ability to hedge options positions sensitive to the term

</details>

---

### 24. Hedging Macroeconomic and Financial Uncertainty and Volatility

**Authors:** Ian Dew-Becker, Stefano Giglio, Bryan T. Kelly  
**Published:** Unknown  
**Link:** [View Paper](https://www.nber.org/papers/w26323)  
**PDF:** [Open Local PDF](../data/options_dealer_gamma_hedging_pdfs/nber_82005.pdf)  

<details>
<summary>Abstract</summary>

We study the pricing of uncertainty shocks using a wide-ranging set of options that reveal premia for macroeconomic risks. Portfolios hedging macro uncertainty have historically earned zero or even significantly positive returns, while those exposed to the realization of large shocks have earned

</details>

---

### 25. Hedge Fund Leverage

**Authors:** Andrew Ang, Sergiy Gorovyy, Gregory B. van Inwegen  
**Published:** Unknown  
**Link:** [View Paper](https://www.nber.org/papers/w16801)  
**PDF:** [Open Local PDF](../data/options_dealer_gamma_hedging_pdfs/nber_70152.pdf)  

<details>
<summary>Abstract</summary>

We investigate the leverage of hedge funds in the time series and cross section. Hedge fund leverage is counter-cyclical to the leverage of listed financial intermediaries and decreases prior to the start of the financial crisis in mid-2007. Hedge fund leverage is lowest in early 2009 when the

</details>

---

### 26. GARCH Gamma

**Authors:** Robert F. Engle, Joshua V. Rosenberg  
**Published:** Unknown  
**Link:** [View Paper](https://www.nber.org/papers/w5128)  
**PDF:** [Open Local PDF](../data/options_dealer_gamma_hedging_pdfs/nber_84310.pdf)  

<details>
<summary>Abstract</summary>

This paper addresses the issue of hedging option positions when the underlying asset exhibits stochastic volatility. By parameterizing the volatility process as GARCH, and utilizing risk- neutral valuation, we estimate hedging parameters (delta and gamma) using Monte-Carlo simulation. We estimate

</details>

---

### 27. Do Banks Hedge Using Interest Rate Swaps?

**Authors:** Lihong McPhail, Philipp Schnabl, Bruce Tuckman  
**Published:** Unknown  
**Link:** [View Paper](https://www.nber.org/papers/w31166)  
**PDF:** [Open Local PDF](../data/options_dealer_gamma_hedging_pdfs/nber_637551.pdf)  

<details>
<summary>Abstract</summary>

We analyze whether banks use interest rate swaps to hedge the interest rate risk of their assets, primarily loans and securities. By examining regulatory data on individual swap positions from the largest 250 U.S. banks, we find that banks hold large swap positions with an average notional value of

</details>

---

### 28. Demand-Based Option Pricing

**Authors:** Nicolae Garleanu, Lasse Heje Pedersen, Allen M. Poteshman  
**Published:** Unknown  
**Link:** [View Paper](https://www.nber.org/papers/w11843)  
**PDF:** [Open Local PDF](../data/options_dealer_gamma_hedging_pdfs/nber_65295.pdf)  

<details>
<summary>Abstract</summary>

We model the demand-pressure effect on prices when options cannot be perfectly hedged. The model shows that demand pressure in one option contract increases its price by an amount proportional to the variance of the unhedgeable part of the option. Similarly, the demand pressure increases the price

</details>

---

## RePEc (15 papers)

### 29. &lt;div&gt;
 The Structural Upward Bias in Equity Markets: A First-Principles Examination of Options Dealer Hedging, Gamma Convexity, and the Volatility Risk Premium Paradox
&lt;/div&gt;

**Authors:** Robert Balan  
**Published:** 2026-01-01  
**Link:** [View Paper](https://doi.org/10.2139/ssrn.6682358)  
**PDF:** *No direct PDF URL*  

<details>
<summary>Abstract</summary>

<jats:p>&lt;span&gt;Equity markets exhibit a persistent structural and mechanical tendency to move higher over time, even in the absence of favorable earnings growth, macroeconomic tailwinds, or positive fundamental news. This upward bias is derived directly from first-principles mechanics of options markets: customer demand for downside protection, dealer delta-hedging flows, gamma exposure (GEX), and the persistently positive Volatility Risk Premium (VRP). &lt;/span&gt; &lt;br&gt; &lt;br&gt;&lt;i&gt;&lt;b&gt;&lt;strong&gt;Typical “bearish” customer positioning (put buying combined with call selling) does not create generic downward pressure. Instead, it widens the VRP, transfers premium to dealers, and generates second-derivative convexity that produces a mechanical bid on dips. The downside, by contrast, is conditional and explosive—activated only when price breaches negative-GEX zones. &lt;/strong&gt;&lt;/b&gt;&lt;/i&gt; &lt;br&gt; &lt;br&gt;&lt;span&gt;We contrast this with the inverse (bullish customer flow) and discuss implications for a dollar-neutral, beta-neutral long/short equity strategy that monetizes relative positioning rather than directional bets.&lt;/span&gt;</jats:p>

</details>

---

### 30. Zero DTE Options Gamma Hedging

**Authors:** Dmitry Garmash  
**Published:** 2025-01-01  
**Link:** [View Paper](https://doi.org/10.2139/ssrn.5329719)  
**PDF:** *No direct PDF URL*  

---

### 31. Construction and Hedging of Equity Index Options Portfolios

**Authors:** Robert Ślepaczuk, Maciej Wysocki  
**Published:** 2024-01-01  
**Also found in:** RePEc, Semantic Scholar  
**Link:** [View Paper](https://doi.org/10.33138/2957-0506.2024.14.450)  
**PDF:** *No direct PDF URL*  

<details>
<summary>Abstract</summary>

<jats:p>This research presents a comprehensive evaluation of systematic index option-writing strategies, focusing on S&amp;P500 index options. We compare the performance of hedging strategies using the Black-Scholes-Merton (BSM) model and the Variance-Gamma (VG) model, emphasizing varying moneyness levels and different sizing methods based on delta and the VIX Index. The study employs 1-minute data of S&amp;P500 index options and index quotes spanning from 2018 to 2023. The analysis benchmarks hedged strategies against buy-and-hold and naked option-writing strategies, with a focus on risk-adjusted performance metrics including transaction costs. Portfolio delta approximations are derived using implied volatility for the BSM model and market-calibrated parameters for the VG model. Key findings reveal that system atic optionwriting strategies can potentially yield superior returns compared to buy-and-hold benchmarks. The BSM model generally provided better hedging outcomes than the VG model, although the VG model showed profitability in certain naked strategies as a tool for position sizing. In terms of rehedging frequency, we found that intraday heding in 130-minute intervals provided both reliable protection against adverse market movements and a satisfactory returns profile.</jats:p>

</details>

---

### 32. Decoupling Asia Revisited

**Authors:** Cyn-Young Park  
**Published:** 2017-01-01  
**Link:** [View Paper](https://doi.org/10.22617/wps178597-2)  
**PDF:** *No direct PDF URL*  

---

### 33. Jump Starting GARCH: Pricing and Hedging Options with Jumps in Returns and Volatilities

**Authors:** Chuan Duan-Jin, Peter Ritchken, Zhiquiang Sun  
**Published:** 2006-12-01  
**Link:** [View Paper](https://doi.org/10.26509/frbc-wp-200619)  
**PDF:** *No direct PDF URL*  

---

### 34. A Strategic Approach to Hedging and Contracting

**Authors:** David Downie, Ed Nosal  
**Published:** 2001-10-01  
**Link:** [View Paper](https://doi.org/10.26509/frbc-wp-200119)  
**PDF:** *No direct PDF URL*  

---

### 35. Hedging strategies using catastrophe insurance options

**Authors:** Thomas O'Brien  
**Published:** 1997-11-01  
**Link:** [View Paper](https://doi.org/10.1016/s0167-6687(97)00029-2)  
**PDF:** *No direct PDF URL*  

---

### 36. Closed-Form Analytic Pricing and Hedging of Arithmetic Asian Options using a Reciprocal Gamma Distribution

**Authors:** Moshe Arye Milevsky, Steven E. Posner  
**Published:** 1997-01-01  
**Link:** [View Paper](https://doi.org/10.2139/ssrn.37676)  
**PDF:** *No direct PDF URL*  

---

### 37. Optimal hedging with futures options

**Authors:** Avner Wolf  
**Published:** 1987-05-01  
**Link:** [View Paper](https://doi.org/10.1016/0148-6195(87)90013-0)  
**PDF:** *No direct PDF URL*  

---

### 38. Hedging options

**Authors:** Nai-fu Chen, Herb Johnson  
**Published:** 1985-06-01  
**Link:** [View Paper](https://doi.org/10.1016/0304-405x(85)90021-2)  
**PDF:** *No direct PDF URL*  

---

### 39. Futures Trading and Hedging

**Authors:** Holbrook Working  
**Published:** 1976-01-01  
**Link:** [View Paper](https://doi.org/10.1007/978-1-349-02693-7_3)  
**PDF:** *No direct PDF URL*  

---

### 40. Price Supports and the Effectiveness of Hedging

**Authors:** Holbrook Working  
**Published:** 1953-12-01  
**Link:** [View Paper](https://doi.org/10.2307/1233272)  
**PDF:** *No direct PDF URL*  

---

### 41. Hedging Reconsidered

**Authors:** Holbrook Working  
**Published:** 1953-11-01  
**Link:** [View Paper](https://doi.org/10.2307/1233368)  
**PDF:** *No direct PDF URL*  

---

### 42. Memo Cruz working as a sleep dealer

**Authors:** Unknown  
**Published:** Unknown  
**Link:** [View Paper](https://doi.org/10.3998/mpub.14526607.cmp.rv042x441)  
**PDF:** *No direct PDF URL*  

---

### 43. Economics Technical Working Paper

**Authors:** Unknown  
**Published:** Unknown  
**Link:** [View Paper](https://doi.org/10.14217/b83b8430-en)  
**PDF:** *No direct PDF URL*  

---

