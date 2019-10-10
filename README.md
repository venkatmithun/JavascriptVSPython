# JavascriptVSPython
In Progress

## Python vs JS truthy/falsy  

1) In Python, All values are considered "truthy" except for the following, which are "falsy":  
      1) None  
      2) False  
      3) 0  
      4) 0.0  
      5) 0j  
      6) Decimal(0)  
      7) Fraction(0, 1)  
      8) [] - an empty list  
      9) {} - an empty dict  
      10) () - an empty tuple  
      11) '' - an empty str  
      12) b'' - an empty bytes  
      13) set() - an empty set  
      14) an empty range, like range(0)  
      15) objects for which  
          obj.__bool__() returns False  
          obj.__len__() returns 0  
      A "truthy" value will satisfy the check performed by if or while statements. We use "truthy" and "falsy"    to differentiate from the bool values True and False.

2) Where as in JS, All values are truthy unless they are defined as falsy (i.e., except for __false, 0, 0n, "", null, undefined, and NaN__)
