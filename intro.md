# **Financial Python**

## **Volume: Basic Concepts of Fixed Income**

### **Chapter Five: Par Yields**

Chapter Four established 149 zero prices using 304 bonds. These zero prices effectively "unwrap" the relative pricing of the bonds. This chapter utilizes those zero prices to calculate par yields.

**What are Par Yields?**

Par yields represent the necessary coupon rate (expressed as a proportion of the bond's par value) that would cause a bond's price to equal its par value. Although it might seem that a par yield is a characteristic of an individual bond, it is actually a concept derived from the estimated term structure of interest rates inferred from bond prices. It is not defined with a specific bond.

To illustrate, consider a single-period with a coupon amount of $\text{c}$, and both a price and par value of 100. The single-period rate of return ($\text{r}$) is calculated as:

$$\large\frac{\text{100 + c - 100}}{100}\normalsize = \text{r}$$

Because the price and par value are both 100, the par yield is $\Large\frac{\text{c}}{100}$. In this simple case, the par yield is equal to the rate of return:

$$1 + \Large\frac{\text{c}}{100}\normalsize - 1 = \text{r}$$

**Relationship to Interest Rates**

It is important to remember that the value is determined by the term structure. The rate of return ($\text{r}$) is the single-period spot rate of interest. For a single-period loan, this is the benchmark for the interest rate. For a multi-period loan with a fixed interest rate, the par yield is the periodic interest rate of the loan.

**Utility of Par Yields**

Par yields offer valuable information to both issuers and investors. Issuers can gain insight into the cost of their debt; investors, benchmark potential returns. Furthermore, par yields enable both borrowers and lenders to evaluate the trade-off between fixed and floating rate debt.

### **Leapfroggging into the chapter**

You can begin with Chapter Five even if you are unfamiliar with the content of the preceding chapters. This is possible because a custom module containing the functions developed earlier is imported directly into the chapter. There are no required dependencies between this chapter and previous ones.
