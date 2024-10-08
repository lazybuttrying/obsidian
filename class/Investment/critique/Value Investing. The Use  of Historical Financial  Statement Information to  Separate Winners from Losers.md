
- Examine whether an accounting-based fundamental analysis strategy, when applied to a broad portfolio of high book-to-market firms, can shift the distribution of returns earned by an investor.
- Within the **portfolio of high BM firms**, the benefits to financial statement analysis are concentrated in **small and medium-sized firms**, companies with **low share turnover**, and firms with **no analyst following** and the superior performance is not dependent on purchasing firms with low share prices
- Result
	- Observed patterns of long-window and announcement-period returns are inconsistent with common notions of risk
		- Fama's BM effect is related to financial distress; however, among high BM firms, the healthiest firms appear to generate the strongest returns.
- Implications
	- Financial markets slowly incorporate public historical information into prices and that the sluggishness appears to be concentrated in low-volume, small, and thinly followed firms. 
- Limitation
	- The existence of a potential data-snooping bias


- Variables
	- $F\_SCORE$: aggregate signal as the sum of the nine binary signals
		- measure the overall quality, or strength, of the firm's financial position, and the decision to purchase is ultimately based on the strength of the aggregate signal
		- $F\_SCORE =$
			- $F\_ROA + F\_\Delta ROA + F\_CFO + F\_ACCRUAL$
			- $+ F\_ \Delta MARGIN + F\_ \Delta TURN$ 
			- $+ F\_ \Delta LEVER + F\_ \Delta LIQUID + EQ\_OFFER.$
	- Performance factors
		- $ROA$: net income before extraordinary items from operations
			- scaled by beginning-of-the-year total assets
			- $F\_ROA$ indicator variable whether $ROA$ is positive(1) or not(0)
		- $CFO$: net income before extraordinary cash flow from operations
			- scaled by beginning-of-the-year total assets
			- $F\_CFO$ indicator variable whether $CFO$ is positive(1) or not(0)
		- $\Delta ROA$: current year's $ROA$ less the prior year's $ROA$
			- $F\_\Delta ROA$ indicator variable whether $\Delta ROA > 0$ (1) or not(0)
		- $ACCRUAL$: current year's net income before extraordinary items less cash flow from operations
			- scaled by beginning-of-the-year total assets
			- $F\_ACCRUAL$ indicator variable whether $CFO > ROA$ (1) or not(0)
	- Measure changes in capital structure & firm's ability to meet future debt service obligations
		- $\Delta LEVER$: captures changes s in the firm's long-term debt levels.
			- historical change in the ratio of total long-term debt to average total assets
			- view an increase/decrease in financial leverage as a negative/positive signal
			- $F\_ \Delta LEVER$ indicator variable whether firm's leverage ratio fell(1) or rose(0) in the year preceding portfolio formation
		- $\Delta LIQUID$: measures the historical change in the firm's current ratio between the current and prior year
			- current ratio = the ratio of current assets to current liabilities at fiscal yearend
			- Improvement in liquidity (i.e., $\Delta LIQUID > 0$) is a good signal about the firm's ability to service current debt obligations
			- $F\_ \Delta LIQUID$ indicator variable whether firm's liquidity improvedl(1) or not(0)
		- $EQ\_OFFER$: indicator variable whether firm did not issue common equity(1) in the year proceding portfolio formation, zero otherwise.
			- Similar to an increase in long-term debt, financially dis- tressed firms that raise external capital could be signaling their inability to generate sufficient internal funds to service future obligations
	- Measure changes in the efficiency of the firm's operations
		- $\Delta MARGIN$: firm's current gross margin ratio (gross margin scaled by total sales) less the prior year's gross margin ratio
			- improvement in margins signifies a potential improvement in factor costs, a reduction in inventory costs, or a rise in the price of the firm's product.
			- $F\_\Delta MARGIN$ indicator variable whether $\Delta MARGIN > 0$ (1) or not(0)
		- $\Delta TURN$: firm's current year asset turnover ratio (total sales scaled by beginning-of-the-year total assets) less the prior year's asset turnover ratio
			- improvement in asset turnover signifies greater productivity from the asset base.
			- $F\_\Delta TURN$ indicator variable whether $\Delta TURN > 0$ (1) or not(0