# MonteCarloSimulationCallOption
Using Monte Carlo Simulation with python for pricing Call option

使用蒙地卡羅模擬法評價買權

主要是假設股價服從幾何布朗運動，且是對數常態分配
- $S_{t+1}=S_te^{(r-0.5\sigma^2)\Delta{t}+\sigma\epsilon\sqrt{\Delta{t}}}$
- $\ln{S_{t+1}}=\ln{S_t} + e^{(r-0.5\sigma^2)\Delta{t}+\sigma\epsilon\sqrt{\Delta{t}}}$
- 
其中:

$\epsilon$是服從標準常態的隨機變數

$r$ 是無風險利率

$S_{t+1}$和$S_{t}$是下一期股價以及本期股價

$\sigma$是標的資產的報酬標準差

$\Delta{t}$是變動期數或是切割期數，例如1年切割250天，則 $\Delta{t}$ 就是 $\frac{1}{250}$
