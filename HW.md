# Homework EPI 809, Module 1

## HW1: Correlation and Linear Regression

**Due  Jan 24th in D2L**

**1: Correlation**
  
  **1.1.** Using the [gout](https://github.com/gdlc/EPI809/blob/master/gout.txt) data set produce the following summary statistics:
  
    * Mean, SD, quartiles and range for serum uruate (SU) y for Age
    * A histogram of each the variables listed above.
    * A scatter plot of SU versus Age
    * Summarize in no more than three sentences your findings.
   
  **1.2.** Report the correlation between SU and Age, p-values for two-sided and a one-sded (HA r>=0) test, and 95 and 99% CI for the correlation. For the CI report both a CI assuming normality and one Fisher's Z-transform.

 
**2: Linear Regression-I**

  **2.1.** Using the gout data set estimate the regression of SU on Age, report parameter estimates, SE and p-values (Hint: use the `fm<-lm()` function and apply the `summary(fm)` function to the object returned by `lm()`.
  
  **2.2.** Does Age has a significant effect on SU?
  
  **2.3.** Explain with your own words the interpretation of each of the parameters of the model.
  
  **2.4.** Report the predicted SU for individuals of 40, 50, 60, and 70 years.
  
  **2.5.** Summarize your findings (no more than 3 sentences).


**3: Linear Regression II**

Reproduce the results of Figure 11.1 of the textbook, including:
  
  **3.1.** Parameter estimates
  
  **3.2.** ANOVA Table (example 11.13), and
  
  **3.3.** Plot of Figure 11.1
