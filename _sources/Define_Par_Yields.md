

## Definition Of Par Yield

<br>

Par yield is the coupon rate that causes a bond to trade at its principal or face value.

<br>

### Formula and Calculation:

<br>

The par yield is derived from the bond's present value calculation:

<br>

$$\text{Principal} = \sum _{t=1}^{T}\text{PV}(t)\times \text{Par Yield}\times\text{Principal}+ \text{PV}(T)\times\text{Principal}$$

<br>

By dividing by the $\text{Principal}$ and isolating the $\text{Par Yield}$, the formula simplifies to:

<br>
$$\text{Par Yield}=\frac{1-PV(T)}{\sum _{t=1}^{T}PV(t)}$$

<br>

In simple terms, the par yield is equal to one minus the present value factor at maturity ($\text{PV(T)}$) divided by the sum of the present value factors ($\text{PV(t)}$) for all payment dates. As a reminder, a present value factor is equivalent to the price of a zero coupon for a specified maturity and zero coupon prices follow from spot rates of returns. Different ways of describing the term structure of interest rates.

<br>

### Why Par Yield Matters:

<br>

*   **For Issuers**: It provides an indication of the coupon rate they should expect to pay on new debt, making it a key component in determining the cost of debt.
*   **For Corporations**: It serves as a benchmark for evaluating the cost of their existing outstanding debt and, consequently, their overall cost of capital.
*   **For investors**: It calibrates a periodic return measure available in the bond market.

<br>

### Illustrative Example:

<br>

Consider an example with a six-month and one-year annualized spot rate of 5%. The zero prices (or present value factors) are calculated as:

<br>

*   **Six-month** ($\text{t=0.5}$):
$\text{PV}(0.5) = e^{-0.05\times 0.5} = \text{ 0.9753}$
*   **One-year** ($\hspace{0.3cm}\text{t=1.0}$):
$\text{PV}(1.0) = e^{-0.05\times 1.0} = \text{ 0.9512}$

<br>

Using the par yield formula, the semi-annual coupon rate is:

<br>

$$\text{2.532%}=\frac{1 - 0.9512}{0.9753+0.9512}$$

<br>

Plugging this semi-annual coupon rate back into the present value formula confirms the principal value:

<br>

$$\text{100} = \text{2.532}\times\text{0.9753} + \text{102.532}\times\text{0.9512}$$

<br>

This calculation confirms that the annual-par-yield coupon for a \$100 principal is:

<br>

 $$\text{\$5.064} = \text{2.532%}\times\text{\$100}\times 2$$
<br>

The calculation of par yields only depends upon the term structure.  Chapter Four identified 149 unique zero prices that can be used to calculate par yields.  Chpater Nine introduces the Nelson-Siegel model that allows us to expand our estimates of the term structure and par yields.
