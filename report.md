##Investigation of the Stroop Effect
1. **What is our independent variable? What is our dependent variable?**  
Our independent variable is whether the task has the congruent or incongruent condition. Basically we are trying to figure out if there is a difference between those two tasks. The dependent variable, time, is what we are going to test to see if it changes in relation to our task.
2. **What is an appropriate set of hypotheses for this task? What kind of statistical test do you expect to perform? Justify your choices.**  
Because H<sub>0</sub> is usually saying that nothing changes, a good null hypothesis would be that there is no change in the times for the two tasks. However, based on past experiences with this task, my alternative hypothesis would be that it takes less time to do the congruent task (i.e. more time for the incongruent task). This turns our null hypothesis into a broader statement that there is either no change, or that it takes less time to complete the incongruent task. In more formal language:  
__H<sub>0</sub>__: &mu;<sub>incongruent</sub> &le; &mu;<sub>congruent</sub>  
__H<sub>A</sub>__: &mu;<sub>incongruent</sub> &gt; &mu;<sub>incongruent</sub>  
The most appropriate statistical test for our experiment would be a one-tailed t-test. Because our subjects took the tests at different times, we have dependent samples. We can compare the two averages of dependent samples with a one-tailed t-test.<sup>1</sup>
3. **Report some descriptive statistics regarding this dataset. Include at least one measure of central tendency and at least one measure of variability.**   
**x&#772;<sub>congruent</sub>** = 14.05  
**x&#772;<sub>incongruent</sub>** = 22.02  
**s<sub>congruent></sub>** = 3.56  
**s<sub>incongruent></sub>** = 4.80  
<hr>
1) This is based on information found in the [Udacity Statistics course](https://www.udacity.com/course/statistics--ud134-nd).
