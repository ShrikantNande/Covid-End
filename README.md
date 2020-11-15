# Covid-Levitt-matrix
1. Covid analysis based on Levitt matrix 
Method used by Bhaskaran Raman :
   Levitt’s Metric: In the data presented, Levitt defines H(t) = X(t)/X(t-1), where X(t) is the cumulative count until day t. The count could be of deaths or cases.
Bhaskaran Raman calculated the H(t) metric on Covid-19 deaths rather than cases. There are certain reasons for not selecting ‘Number of cases’ as a metric. First reason, it depends on testing capacity which varies temporally. It also depends on people’s access to tests, which depends upon many policies like are private tests allowed, are tests without prescription allowed, do people have transportation to go to test center, etc. which are all time variant. To add to this, number of tests also depends on social acceptance of tests, which is also highly variable. Also finally, what we most care about is the number of deaths, rather than number of cases So we plot the plots graphs using this information which are as given in the comparison.

![India](https://github.com/ShrikantNande/Covid-End/blob/main/india.png "Title")

Let's check for India data
## At end of Jan 2021 pandamic will end !!!
# Conclusion :
    * H(t) is 1.001 that means pandamic is over as per lavitt's matrix statement. 
    * Matrix Stated: H(t) will reach at 1.001 when x(Days) will be around 185 days but even after 280 days it did not reach there.
    * to reach H(t) at 1.001 approx 380 days will be required as per above graph. 
    * New value for H(t) will reach at 1.001 definately twice the given value(Levitt’s Metric).
    * Due several outlier's such as lockdown open and other's Levitt’s Metric results show's huge variations.
    * It was observed that H(t) falls linearly with x(Days) But doesnot follow tight linearity.
    * Evan r^2 show's huge variation as for livitt matrix it was around 0.0896 and in this observation it is around 0.94.
