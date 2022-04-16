# Week 10, Tuesday


## Tuesday, 2022-Apr-19
In the previous lectures, we practiced the logic flow of hypothesis testing over and over again, so I hope you are now familiar with the concept of hypothesis testing. Basically, we have some knowledge about certain population parameters based on the previous studies or experience. For example:


{{< admonition type=abstract title="Knowledge" open=true >}}
- The proportion of people who have type B is 9%.
- The proportion of people who have type A is 32%.
- The normal body temperature is 37 degree Celcius.
{{< /admonition >}}

Then, we have some data at hands. Based on the observation, we come up with some hypotheses. Fo example:

 {{< admonition type=abstract title="Hypotheses based on current data" open=true >}}
- The proportion of people who have type B is not 9%.
- The proportion of people who have type A is greater than 32%.
- The normal body temperature is not 37 degree Celcius.
{{< /admonition >}}

How do we test them? As we mentioned repeatedly during previous lectures, there is no way we can directly test if those hypotheses are true or not. However, we can approach the probme in an indirect way. That is, we assume the opposite is true ($H_0$):

 {{< admonition type=abstract title="$\boldsymbol{H_0}$" open=true >}}
- The proportion of people who have type B is 9%.
- The proportion of people who have type A is less than 32%.
- The normal body temperature is 37 degree Celcius.
{{< /admonition >}}

Based on that, we use what we learned from the section of probability theory to calculate the probablity of observing the data we have or more extreme (the $p-$value). Then, we ask: `is the probability small or not` ? If it is not small, meaning the data we have is expected; if it is small, meaning that it is unlikely to observe the data we have given that our assumption ($H_0$) is true. Therefore, we question our original assumption ($H_0$). We set a __significance level__ $\alpha$. If the the $p-$value is smaller than $\alpha$, we reject our original assumption ($H_0$).

You can see, the __significance level__ $\alpha$ is never 0, meaning that there is still a chance we could draw the wrong conclusion when making a decision. That is, we make errors. On Tuesday, we will talk about those errors.

#### Lecture slides
- [Lecture 25 More On Hypothesis Testing](/lecture_slides/Lecture_25_More_On_Hypothesis_Testing_handout.pdf)
- [Lecture 26 Error Power And Sample Size Estimation](/lecture_slides/Lecture_26_Error_Power_And_Sample_Size_Estimation_handout.pdf)

#### Extra reading material
- None

#### Homework assignment
- [Assignment 6](/assignments/Assignment_6.pdf)

#### Interesting links
- [Hypothesis testing, type I and type II errors](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2996198/)

