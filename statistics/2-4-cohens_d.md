[Think Stats Chapter 2 Exercise 4](http://greenteapress.com/thinkstats2/html/thinkstats2003.html#toc24) (Cohen's d)

Exercise 4   Using the variable totalwgt_lb, investigate whether first babies are lighter or heavier than others. Compute Cohen’s d to quantify the difference between the groups. How does it compare to the difference in pregnancy length?

### Call the function using totalwgt_lb for first born babies and others as arguments for the function

CohenEffectSize(firsts.totalwgt_lb, others.totalwgt_lb)  

-0.088672927072602006

### Call the function CohenEffectSize using pregnancy length.
CohenEffectSize(firsts.prglngth, others.prglngth)

0.028879044654449883

The difference in variance is negative for total weight and positive for pregancy length.  However, both values are very small suggesting that the difference in variances are not significant.  
