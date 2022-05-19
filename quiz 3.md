
<center><font size="+2"> Quiz 3 </font></center>

**Question 1** As we discussed in class, a Collateralized Mortgage Obligation (CMO) is a collection of cash flows that are crated by tranching the payments from a standard MBS pool. The underlying foundation for a Collateralized Mortgage Obligation (CMO) is the cash flows from a standard MBS pool. The only restriction on the manner in which CMO tranches are formed is that at every point in time all cash flows form the underlying mortgage-pool must be distributed as interest or principal somewhere in the CMO structure.1 At each point in time, the outstanding balance on all CMO tranches will be equal to the outstanding balance on the underlying mortgage pool.

(1) What is the reason that Collateralized Mortgage Obligations (CMOs) wereintroduced to the market?

_The reason why collateralized mortgaged obligation(CMOs) were introduced to the markets is to mitigate the adverse effect of prepayment._


(2) Describe the basic idea behind a sequential pay CMO.

 




(3) You are advising an insurance investor client on a simple two tranche sequential CMO where the total MBS pool is 100,000,000 and the two sequential pay tranches are structured to be 50,000,000 each and are referred to as A-tranche and B-tranche. This CMO is setup for you in the spreadsheet ‘Sequential Pay Q1.xlsx’. If your client is concerned that prepayments will be high (as a percentage of PSA) and their main concern is to fund payments that are required from long-term insurance liabilities, would your recommend either A-tranche or B-tranche as a suitable investment? Why?

**Question 2** Run the AIRG Economic Scenario Generator as of December 2020
(which is the default time for the file link I provided). Use 1000 scenarios, 30 year projection, Separate *.csv file for each term to maturity, monthly time step and output rates as Bond Rates (bond equivalent).

- Using the UST 10y.csv file that the AIRG Economic Scenario Generator produces, compute the mean and standard deviation of the simulated 10-year interest rate for the last 36 months of the simulation data across each path.



- Using the UST 10y.csv file that the AIRG Economic Scenario Generator produces, prepare a histogram of the simulated 10-year interest rate for the last
36 months of the simulation data across each path.






- Using the GFD US ten year treasury interest rate data provided in the file ‘Quiz 3 10yr Bond Yield Data.xlsx’, compute the mean and standard deviation of the data from January 1951. Also compute a histogram for this data
  
- Compare the simulated 10yr interest rate output from the AIRG Economic Scenario Generator for the last 36 months of the simulation data across each path with the GFD US ten year treasury interest rate data from January 1951
(i.e. historical data). Do you think that the AIRG validates well against this historical data?


**Question 3** You are using the Dynamic Nelson-Siegel Model as discussed in class.
You have decided that the appropriate value for λ is 0.127 (i.e. λ = 0.127).

- You are told that $L = 0.03$, $S = −0.022$ and $C = 0.0155^2$ What is the resulting 10 year interest rate?

According to lecture note, we have the following formula:
$$
y_t(\tau) = L_t + S_t(\frac{1-e^{-\lambda\tau}}{\lambda\tau}) + C_t(\frac{1-e^{-\lambda\tau}}{\lambda\tau} - e^{-\lambda\tau})
$$
Since we are computing the 10 year interest rate, and $L = 0.03$, $S = −0.022$, $C = 0.0155^2$,$\lambda = 0.127$, we have:

$$
\begin{aligned}
    y_t(10) &= 0.03 + −0.022(\frac{1-e^{-0.127*10}}{0.127*10}) + 0.0155(\frac{1-e^{-0.127*10}}{0.127*10} - e^{-0.127*10}) \\
    &= 0.03 - 0.01245 + 0.00442 \\
    &= 0.02197
\end{aligned}
$$

Hence, the resulting 10 year interest rate is 0.02197.

- We have been asked to use the model for simulating future interest rates. Explain how you would attempt to parameterize the model. [Follow the ideas that were described in class.]
