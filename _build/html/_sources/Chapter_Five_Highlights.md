# Par Yields

**Chapter Five of the volume Basic Concepts of Fixed Income**

**Key Topics Covered**

* **The term structure and par yields**  
  * Define par yields   
  * Using zero price estimates to calculate par yields
  * Matching the cadence of par yields and coupon payment dates
  * Comparing our par yield estimates to those of the U.S. Treasury 
 
* **Python concepts:**  
  * NumPy arrays   
  * Pandas 
    * method <font color='green'>read_excel</font>  
    * method <font color='green'>cumsum</font>  
  * Custom modules.  
    * <font color='green'>accrued_interest</font>  
    * <font color='green'>bond_pay_data</font>  
    * <font color='green'>create_payoff_matrix</font>

    

## **Background**

This chapter's examples and discussions rely on the **Pandas,** **NumPy,** and **datetime** libraries.

* **Pandas** is introduced in [*A Quick Introduction to Pandas*](https://patrickjhess.github.io/Introduction-To-Python-For-Financial-Python/An_Introduction_To_Pandas.html#a-quick-introduction-to-pandas).  
* **NumPy** is introduced in [*A Quick Introduction to NumPy*](https://patrickjhess.github.io/Introduction-To-Python-For-Financial-Python/An_Introduction_To_NumPy.html#a-quick-introduction-to-numpy).
* **datetime** is introduced in [*A Quick Introduction to Manipulating Dates*](https://patrickjhess.github.io/Introduction-To-Python-For-Financial-Python/Manipulating_Dates.html).  
* The <font color='green'>accrued_interest</font> function is imported from [Chapter Two](https://patrickjhess.github.io/Vol-3-Chap-2-Chap-3/Chapter_Two_Highlights.html#accrued-interest)
* The <font color='green'>bond_pay_data</font> function is imported from [Chapter Three](https://patrickjhess.github.io/Vol-3-Chap-2-Chap-3/Chapter_Three_Highlights.html)  
* The <font color='green'>create_payoff_matrix</font> function is imported from [Chapter Four](https://patrickjhess.github.io/Vol-3-Chap-4/Creating_The_Payoff_Matrix.html#creating-the-payoff-matrix)  
* Additional relevant Python concepts can be found in the introductory volume, [*Background Material: An Introduction to Python for Financial Python*](https://patrickjhess.github.io/Introduction-To-Python-For-Financial-Python/intro.html), that relate to this and other chapters of *Basic Concepts of Fixed Income*.

**The chapter includes four  sections:**

1. *What are par yields*  defines and demonstrates how par yields are calculated from the term stucuture of interest rates.  
2. The  Jupyter notebook *Calculating Par Yields*
   * downloads data of 304 coupon bonds from DropBox.  
   * calculates the transaction prices.  
   * calculate the payoff matrix.  
   * estimte the term structure  
   * uses the term structure to calculate par yields   
   * an exercise asking you to use the term structure calculated with the 304 bonds to calculate the par yields of three bonds
4. *Par yields and financial analysis.* summarizes how par yields are used to make financial decisions.  
5. *Functions Imported by Calculating Par Yields*  describes the function imported from DropBox (*module_basic_concepts_fixed_income*).
```{tableofcontents}
```
