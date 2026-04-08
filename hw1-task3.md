# Homework 1 Task 3

---

Answer the following questions based on exercises from *An Introduction to Statistical Learning with Applications in Python*.

## Chapter 2.4 Exercises

---

### Exercise 1 (ISLP exercise 2)

Explain whether each scenario is a **classification or regression** problem, and indicate whether we are most interested in **inference or prediction**. Finally, provide **n** (size of observation dataset) and **p** (number of predictors).

**(a)**  We collect data on 200 protected marine reserves worldwide. For each reserve we record species richness, reserve size, years since establishment, enforcement budget, and proximity to human settlements. We are interested in understanding which factors affect species richness.

> regression

---

**(b)** A conservation agency wants to know whether a proposed habitat corridor will successfully support wildlife movement or fail to do so. They collect data on 30 previously established corridors. For each corridor they have recorded whether wildlife movement was successful or unsuccessful, corridor width, length, surrounding land use type, and eight other variables.

> classification

---

**(c)** We are interested in predicting weekly average ground-level ozone concentration in a coastal city. We collect weekly data for all of 2019. For each week we record average ozone concentration, sea surface temperature, wind speed, solar radiation, and atmospheric

> regression

---

### Exercise 2 (ISLP exercise 5)

What are the advantages and disadvantages of a very flexible (versus a a less flexible) approach for regression? Under what circumstances might a more flexible approach be preferred to a less flexible approach? When might a less flexible approach be preferred?

> A more flexible approach might be preferred in instances where there is little tolerance for lots of bias in the model and an emphasis on prediction accuracy with a large dataset. Something such as predicting algae bloom concentration from dozens of interacting climate variables with years of weekly data would fit that. Less flexible approaches shine when there isn't a lot of data to go off of and inference of important variables is the key with usually a linear relationship. An example could be determining which of 4 factors most influences fish mortality when you only have 30 observations. 



---

### Exercise 3 (ISLP exercise 6)

Describe the differences between a **parametric** and a **non-parametric** statistical learning approach. What are the **advantages** of a parametric approach to regression or classification (as opposed to a non-parametric approach)? What are its **disadvantages**?

> Parametric models are for situations that call for a strong training model that can estimate nuances within relationships and can follow trends more closely and precisely whereas non-parametric models do not assume and are very strict in nature. the biggest con to using parametric models is that they are susceptible to noise/errors from following data too closely and also can be less interpretive than stricter models because there are too many moving variables. 